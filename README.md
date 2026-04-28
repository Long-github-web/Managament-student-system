#Features
User authentication with cookie-based login and “Remember Me”
Role-based access control (Admin, Student, Faculty)
User management (CRUD, role and status management)
Student management (CRUD, profile update with permission checks)
Course management (CRUD, unique course code)
Student enrollment with duplicate prevention
Grade management per course and student
GPA calculation based on course credits
Dashboard with system statistics (students, courses, enrollments)
Search functionality (live search for students and courses)
Audit logging (track user actions with IP address)

#Technologies Used
Backend: ASP.NET Core MVC (.NET 8)
Authentication & Authorization: Cookie Authentication, Role-based policies
Database: SQL Server, Entity Framework Core (EF Core)
Architecture: Dependency Injection, Repository & Service pattern
Frontend: Razor Views, Bootstrap 5, jQuery, jQuery Validation
Testing: xUnit, Moq, EF Core InMemory, Coverlet
