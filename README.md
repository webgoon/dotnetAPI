# dotnetAPI
A core project to run Dotnet API to use a perferable front end to fetch data.


# dotnet new -l     << This gives you a list of possibly to install .net related.

dotnet new gitignore 

# Visual Studio Shortcuts
Ctrl + Shift + P = opens all commands.
we use visual studio code to install microfot packages into the project by using nuget gallery.

ctrl + shift + F = find files

# Dotnet CLI
dotnet --version = gives you the version of your dotnet environment.
dotnet ef = gives you the lis of Entiry Framework Core --current version 7.0.0--

dotnet ef migrations add InitialCreate

# To install dot net ef match your sdk like this:

dotnet tool install --global dotnet-ef --version 6.0.4

dotnet tool update --global dotnet-ef --version 6.0.4

# -- Needs to be done on the first migration at least navigate into API directory--
dotnet ef migrations add InitialCreate -o Data/Migrations

# -- this will take a look at the migrations and if it doesn't already have a database then it will create one -------
dotnet ef database update

dotnet ef database drop

# Finally
dotnet watch run





dotnet ef database drop
dotnet watch run
==================================================================
Note: In VS code if you too make a constuctor type ctor   << make a constructor

Made a new source project
https://github.com/webgoon/dotnetAPI.git

git commit -m "First Commit"  << Type your commit message i.e (First Commit)"

git branch -M main    << Turn your local files 
