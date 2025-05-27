# 📚 Library Management System  

## Overview  
The **Library Management System** is a C# .NET 8.0 application designed to streamline the management of books, members, borrowing records, and reservations in a library. Built using **Entity Framework 6** and **SQLite**, this project follows the **MVC architecture** with a **Service Layer** design pattern to ensure scalability, maintainability, and clean separation of concerns.  

## Features  
✅ **Books Management** – Add, edit, delete, and view book records (title, author, genre, ISBN).  
✅ **Members Management** – Create, edit, delete, and view member profiles.  
✅ **Borrowing System** – Track borrowing records, including due dates and return statuses.  
✅ **Reservations** – Allow members to reserve books and manage reservations.    

## Tech Stack  
- **Language:** C# (.NET 8.0)  
- **Database:** SQLite (with Entity Framework 6)  
- **Architecture:** MVC with a Service Layer  
- **UI:** WinForms  

## Installation & Setup  
1. Clone the repository:  
   ```sh
   git clone https://github.com/lak-git/Library-Management-System.git
   cd Library-Management-System
   ```
2. Open the solution in Visual Studio.
3. Restore dependencies using NuGet Package Manager.
4. Apply database migrations:
```sh
dotnet ef database update
```
5. Build and run the application in Visual Studio.

## Usage
1. **Login**:  
   - Use Admin credentials for access to all functionalities (Username:admin|Password:admin123).  
   - Members and Librarians have limited access.  
2. **Manage Books and Reservations**:  
   - Navigate to the books or reservations section to add, update, or delete them.  
   - Use filters to sort and find specific items quickly.   

## Contribution & Version Control
* Follows Git best practices using Git branching for features and bug fixes.
* Pull Requests are required before merging changes into the main branch.
* Uses semantic versioning for releases.

## License
This project is licensed under the MIT License.
