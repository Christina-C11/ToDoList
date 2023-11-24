# To Do List Application 
https://github.com/Christina-C11/ToDoList/assets/75556703/0633010e-170f-421e-a7e9-f783b9a94339
## Overview
This application is a comprehensive set of interconnected projects for the To Do List application, designed to effectively manage to-do items. It includes the Database Script, Backend, and UI components.

## Project 1: To Do List Database Script
### [To Do List DB Script Repository](https://github.com/Christina-C11/ToDoList.DBScript.git)
Responsible for the To Do List's table structure and management within Microsoft SQL Server.

#### Technologies Used
- Microsoft SQL Server Express 2022
- Microsoft SQL Server Management Studio 2019

#### Features
- SQL scripts for setting up the To Do List's table structure
- Ensures proper data structuring for to-do item management

#### Database Setup
1. **Install Microsoft SQL Server Express 2022**:
   - Download the installer from the official Microsoft website.
   - Run the installer and follow the on-screen instructions.
   - Select the 'Custom' installation type to configure SQL Server features.
   - In the 'Feature Selection' screen, ensure that the Database Engine Services is selected.
   - Proceed with the installation until you reach the 'Database Engine Configuration' screen.
2. **Configure 'sa' Account**:
   - In the 'Database Engine Configuration' screen, select the 'Mixed Mode' for authentication.
   - Set a password for the 'sa' account. Ensure it is strong and secure.
   - Add any required SQL Server administrators.
   - Complete the installation process.
3. **Install Microsoft SQL Server Management Studio 2019**:
   - Download SSMS from the official Microsoft website.
   - Run the installer and follow the on-screen instructions to complete the installation.
4. **Set Up the To Do List's Tables**:
   - Clone the repository: `git clone https://github.com/Christina-C11/ToDoList.DBScript.git`.
   - Open SQL Server Management Studio and connect to the server using the 'sa' account.
   - Run the provided SQL scripts to set up the To Do List's tables.
   - Configure the connection to use encryption and set `trust server certificate` to `true`.

## Project 2: To Do List Maintenance (Backend)
### [To Do List Backend Repository](https://github.com/Christina-C11/ToDoList.Maintenance.git)
Handles all logic for to-do item operations in the application.

#### Technologies Used
- .NET 6.0
- Programming Language: C#

#### Features
- To-do item prioritization and status tracking
- Advanced editing with validations for to-do items
- Search and retrieval system for to-do items
- Confirmation prompt for safe deletion of to-do items
- Permanent deletion of to-do items from the database
- Error handling and logging

#### Backend Setup and Running Instructions
- Install Microsoft Visual Studio 2022 (Community Edition).
- Clone the repository: `git clone https://github.com/Christina-C11/ToDoList.Maintenance.git`.
- Open the solution in Visual Studio.
- Navigate to `appSettings > ConnectionStrings > DefaultConnection` and update the Password to match the 'sa' user of the SQL Server.
- Ensure `ToDoList.Maintenance` is set as the startup project.
- Compile the project by selecting `Build > Build Solution` from the menu.
- Run the project by selecting `Debug > Start Debugging`.

## Project 3: To Do List UI
### [To Do List UI Repository](https://github.com/Christina-C11/ToDoList.UI.git)
The user interface of the application, providing a dynamic and interactive experience for managing to-do items.

#### Technologies Used
- Angular CLI: 16.1.8
- Node: 20.9.0
- npm: 10.1.0
- Programming Language: TypeScript

#### Features
- Interactive interface for to-do item management
- Dynamic addition, editing, and viewing of to-do items
- Real-time update of the to-do list

#### UI Setup and Running Instructions
- Install the latest version of Microsoft Visual Studio Code.
- Clone the repository: `git clone https://github.com/Christina-C11/ToDoList.UI.git`.
- Open the project in Visual Studio Code.
- Ensure Node.js and Angular CLI are installed.
- Run `npm i` in the project directory to install dependencies.
- Compile and run the UI with `ng serve`.
- Access the application through `http://localhost:4200` in a web browser.
