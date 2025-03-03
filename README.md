Task: Employee Development Tracker Management
Objective:
Develop a web application using ASP.NET (C#) and SQL Server to track employee development tasks.
Features to Implement:
1.	User Authentication:
o	Implement login and logout functionality.
2.	Employee Task CRUD Operations:
o	Employees should be able to create, read, update, and delete tasks assigned to them.
o	Each task should have the following attributes:
	Title
	Description
	Due Date
	Status (Pending, In Progress, Completed)
3.	Role-Based Access Control (RBAC):
o	Normal Employees can only manage their own tasks.
o	Managers/Heads have access to modify tasks assigned to any employee.


Setup Instructions

Clone the repository:

[git clone https://github.com/your-repo/employee-tracker.git
cd employee-tracker](https://github.com/Chikalesakshi/NewRepo.git)

Configure the database in appsettings.json:

"ConnectionStrings": {
   "DefaultConnection": "Server=your_server;Database=EmployeeTracker;Trusted_Connection=True;"
}

Run database migrations:

dotnet ef database update

Run the application:

dotnet run
-------------------------------------------
Log In Credentials
Mail-  admin@example.com
Password- Admin@123

