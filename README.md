# SudentInformationSystem-MVC-DotNet
Advanced Student Information System: Leveraging C# and SQL Server in .NET Framework 6.0 with Intuitive Windows Forms Interface
## Project Summary: Student Information System (SIS)

### Overview
This repository hosts the Student Information System (SIS), a comprehensive application developed as part of a programming module. The project emphasises the application of advanced programming concepts, code review, refactoring, and rigorous testing. The SIS is designed to provide CRUD (Create, Read, Update, Delete) operations for managing student data, showcasing interaction with a database using Visual Studio and SQL Server Management Studio (SSMS).

### Key Features
- **Database Integration:** Utilises SQL Server Management Studio (SSMS) V18.12.1 and a local database with Windows authentication.
- **User Interface:** Developed with Windows Forms in Visual Studio 2022, providing an intuitive drag-and-drop interface.
- **Refactoring and Testing:** Code has been refactored for efficiency and tested for verification and validation to ensure robust functionality.

### Technical Stack
- **Programming Language:** C# (targeting .NET Framework 6.0).
- **Development Environment:** Visual Studio 2022.
- **Database Management:** SQL Server Management Studio (SSMS) V18.12.1.
- **Additional Tools:** NuGet package manager with packages like Dapper (ORM) and System.Data.SqlClient.

### Implementation Highlights
- **SIS Repository:** Serves as the main conduit for database communication, adopting a design pattern principle to maintain modular code structure.
- **User Interface (UI):** Simplified and functional UI design, focusing on user input efficiency and effective data presentation.
- **Stored Procedures and Views:** Implemented for secure and efficient database operations, reducing risks like SQL injection.
- **SIS.Models:** Acts as a blueprint for all models in the project, facilitating smooth integration between the database and the main application.

### Development Challenges and Learning
- Faced and resolved challenges related to null values, datatype errors, and database connection issues.
- Gained valuable insights into error resolution beyond IntelliSense, enhancing problem-solving skills in programming.

### Future Scope
- The project lays a strong foundation for scalability and potential enhancements to meet production-level quality.
- Future developments could integrate more advanced features, adhering to SOLID principles and sophisticated design patterns.

### Contributions
This project is open to contributions and enhancements. Please read the [CONTRIBUTING.md](#) for guidelines on how to contribute.



### Acknowledgements
Special thanks to the resources and tutorials that supported this project, listed in the [References](#) section.
Reference:
1.	adegeo (2021). What’s new in Windows Forms .NET 6 - Windows Forms .NET. [online] Microsoft.com. Available at: https://learn.microsoft.com/en-us/dotnet/desktop/winforms/whats-new/net60?view=netdesktop-6.0 [Accessed 7 Nov. 2022].
2.	Ashraf, H. (2020). Use SQL Server Management Studio to Connect to Database. [online] Mssqltips.com. Available at: https://www.mssqltips.com/sqlservertutorial/9273/use-sql-server-management-studio-to-connect-to-database/ [Accessed 13 Nov. 2022].
3.	BillWagner (2022). Language-Integrated Query (LINQ) (C#). [online] Microsoft.com. Available at: https://learn.microsoft.com/en-us/dotnet/csharp/programming-guide/concepts/linq/?redirectedfrom=MSDN [Accessed 14 Nov. 2022].
4.	Connectionstrings.com. (2019). .NET Framework Data Provider for SQL Server Connection Strings - ConnectionStrings.com. [online] Available at: https://www.connectionstrings.com/sqlconnection/ [Accessed 15 Nov. 2022].
5.	IAmTimCorey (2021). Simple C# Data Access with Dapper and SQL - Minimal API Project Part 1. YouTube. Available at: https://www.youtube.com/watch?v=dwMFg6uxQ0I [Accessed 1 Nov. 2022].
6.	 Jetbrains.com. (2020). Basics of Dapper - .NET Guide. [online] Available at: https://www.jetbrains.com/dotnet/guide/tutorials/basics/dapper/ [Accessed 17 Nov. 2022].
7.	Nuget.org. (2021). Dapper 2.0.123. [online] Available at: https://www.nuget.org/packages/Dapper [Accessed 17 Nov. 2022].
8.	Rick-Anderson (2022). Creating a Connection String and Working with SQL Server LocalDB. [online] Microsoft.com. Available at: https://learn.microsoft.com/en-us/aspnet/mvc/overview/getting-started/introduction/creating-a-connection-string [Accessed 17 Nov. 2022].
9.	WilliamDAssafMSFT (2022). Create a Stored Procedure - SQL Server. [online] Microsoft.com. Available at: https://learn.microsoft.com/en-us/sql/relational-databases/stored-procedures/create-a-stored-procedure?view=sql-server-ver16 [Accessed 13 Nov. 2022].

