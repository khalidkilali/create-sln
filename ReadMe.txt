C# 10 and .net 6 with visual code 

to install Visual Code : 
https://code.visualstudio.com/Download

After installing VS Code, you will want to add the C# extension found here:
https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.csharp

--- Lets now create our first C# console application program --

When you start Visual Studio Code, you are presented with a blank slate. Creating solutions and projects 
must be done through the .NET 6 command-line interface, also known as the CLI. To start, open a folder 
with Visual Studio Code by selecting File ➤ Open Folder, and navigate through the explorer window to 
where you want your solution and project to live. Next, open a terminal window by selecting Terminal ➤
New Terminal or by pressing Ctl+`

we start by creating a new solution under directory in our case we choose .net6andCsharp as name zith the folowing instruction 
"dotnet new sln -n FirstSln -o .\.net6andCsharp10"
if any error lets create our first Console application project with the following instruction : 
"dotnet new console -lang c# -n CsharpConsoleApplication -o .\.net6andCsharp10\CsharpConsoleApplication -f net6.0"
At the end of our build we need to add the project to our solution by : 
"dotnet sln  .\.net6andCsharp10\FirstSln.sln add .\.net6andCsharp10\CsharpConsoleApplication\"

===> this is just a small sample of what cli is capable of. to discover what cli can do check this commamd :
dotnet -h
Now our projet is ready 

Build and Run : is the first lets see how to run a project 
make sur that you a located at the project container and run 

dotnet build

if the build complete without any error run : 
dotnet run 

Hello, World! will appear in the screen.
