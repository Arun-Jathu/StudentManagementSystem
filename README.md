# Student Management Application

## Overview
This is a Windows Forms application designed to manage timetables for an educational institution. It allows users to view, add, edit, and delete timetable entries, with features for filtering by room type and role-based access (Admin, Staff, Student).

## Features
- **User Authentication**: Supports different roles (Admin, Staff, Student) with restricted access.
- **Timetable Management**: Add, edit, and delete timetable entries with subject, time slot, and room details.
- **Room Type Filter**: Filter timetables by room type (e.g., Halls, Labs).
- **Data Persistence**: Uses SQL Server for storing timetable data.
- **Asynchronous Operations**: Implements async/await for database interactions.

## Technologies Used
- **C#**: Core programming language.
- **Windows Forms**: Graphical user interface.
- **SQL Server**: Database management.
- **Async/Await**: For non-blocking database calls.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/StudentManagementSystem.git
    ```
2. Open the solution in Visual Studio.  
3. Restore NuGet packages if prompted.  
4. Update the connection string in `DatabaseManager.cs` to point to your SQL Server instance.  
5. Build and run the project.

## Usage
- **Admin**: Log in to add, edit, or delete timetables and filter by room type.
- **Staff/Student**: View timetables based on role permissions.
- To edit a timetable entry, select a row and click "Edit".

## Contributing
Feel free to fork this repository and submit pull requests. Issues can be reported on the GitHub page.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For questions, contact [your.arunjathu0@gmail.com](mailto:your.arunjathu0@gmail.com).
