# InterviewCodeChallenge_React

For designing task use:
https://app.diagrams.net/

Pre-Requisites:
* .Net Core 3.1 installed.
* Visual Studio or VS Code installed.
* npm and nvm.


Steps to Create the project (using Visual Studio)
* Launch Visual Studio as an administrator.
* Choose "Create a new project"
*   ![image](https://user-images.githubusercontent.com/6515261/169511752-eebc5e4b-f8be-4b66-80cb-128c3ce3305a.png)
*   Search for React template, choose project type "ASP.NET Core with React.js" and click "Next"
*   ![image](https://user-images.githubusercontent.com/6515261/169511903-cdd65700-6de1-4327-be3f-19e4671656b2.png)
*   Enter the project name as "InterviewCodeChallenge_React" and click "Next"
*   ![image](https://user-images.githubusercontent.com/6515261/169512097-2639e5a8-60ea-45f8-b348-29a1052009e4.png)
*   Choose Framework -> .Net Core 3.1 and click on "Create"
*   ![image](https://user-images.githubusercontent.com/6515261/169512215-31dfe20e-4c8c-4dd6-8d13-b6f6a07665a0.png)
*   Try building and running the template project.

Run the Project using Visual Studio:

Troubleshooting:
* Build Failure with "The command "npm install" exited with code 1."
* ![image](https://user-images.githubusercontent.com/6515261/169512529-585c1a1a-dec1-45e3-9518-939d164c62dd.png)
* Resolution:
* Open the .csproj file and update the npm install command to install with force
* ![image](https://user-images.githubusercontent.com/6515261/169512949-4ce92ba1-c9a9-438f-81fc-62e34c9f922b.png)

Run the project using VS Code.
* Open the project folder using VSCode.
* Using terminal in the project directory, enter the command "dotnet build"
* ![image](https://user-images.githubusercontent.com/6515261/169513395-78ab4f1a-a544-45a2-bedc-227bd12081ac.png)
* Using terminal in the project directory, enter the command "dotnet run"
* ![image](https://user-images.githubusercontent.com/6515261/169513568-801bcf2b-0176-497e-bbd8-832072f3df4a.png)
* Navigate to the URL mentioned in the terminal to browse.






