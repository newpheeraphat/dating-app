- dotnet --info: show the info of the dotnet SDK
- dotnet -h: get help

# To Create a Project

- dotnet new -h: See the whole new project (optional)
- dotnet new sln: Create the solution file
- dotnet new webapi -n <FOLDER_NAME> --use-controllers: Create an api controller
- dotnet sln add <PROJECT_PATH>: Add <PROJECT_PATH> to solution file
- dotnet sln list: See the list of project in solution file (optional)
- dotnet tool list -g: See the list of package

# Run Dotnet

- dotnet run: Run the project
- dotnet watch: Run the file while chaging
- dotnet dev-certs https --trust: Trust https
- dotnet dev-certs https --clean: Clean https

# To create a database

- dotnet ef -h: Get help from dotnet-ef
- dotnet ef migrations add <INITIAL_NAME> -o <OUTPUT_DIR:Data/Migrations>: Create a migration file to prepare for creating data
- dotnet ef database update: Create Database

# Create source control

- git init: Initialize the git control
- dotnet new gitignore: Create ignore file
- dotnet new globaljson: Create global file
- git add -A: Add all file to staging change
- git commit -m <MESSAGE_GIT>: Add message before commit
