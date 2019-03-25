# ProPT


Development Prerequisites:
* Visual Studio 2017 Professional - Install from MSDN
* Sql Server Management Studio 2017- Install from MSDN
* [Microsoft .NET Framework 4.7.1 Developer Pack](https://www.microsoft.com/en-us/download/details.aspx?id=56119)
* [NET Core SDK 2.1.4](https://www.microsoft.com/net/download/thank-you/dotnet-sdk-2.1.4-windows-x64-installer)
. [NET Core Windows Hosting](https://aka.ms/dotnetcore-2-windowshosting)
* [Windows Management Framework 5.0 (includes PowerShell 5.0)](https://www.microsoft.com/en-us/download/details.aspx?id=50395)


Troubleshooting:

* If you have "The site can't be reached problem", please follow the instructions mentioned [here](https://stackoverflow.com/a/52281551)


Project Structure:
The whole project consists of several sub projects.

* ProPT.Api:

  This is the main entry project. Inside this project, there are several files: 
  * Program.cs: Main cs file which have the main method to run.
  * Startup.cs: All startup configuration(database, logging etc) are written in here
