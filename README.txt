2024-01-18
1329
# Project Title: MvcMovie
## Part 1: Added a Controller to ASP.NET Core MVC App
Created a new ASP.NET Core Web App (.Net 8).....
Created a web project....
Added a controller

2024-01-18
1329
## Part 2: Added a Controller to ASP.NET Core MVC App....
Added my name and id 
Created README.TXT file


2024-01-18
1329
## Part 3: Added a view to an ASP.NET Core MVC app.....
Created new folder called hello world
Added Image and changed the welcome message with hello world
Changed the layout of app....

2024-01-25
1300

##Part 4
I Understand all models.
In Model folder added class and named file as movie.cs
Then under Controllers folder Added New Scaffolded Item and selcted movie option under the model class
To get Migration folder, selected NuGet Package Manager From the Tools menu and gave required command under Package Manager Console 
Then Run the app and selected the Movie App and modified the data

2024-01-25
1315

##Part 5: Work with a Database
I explored database interactions in ASP.NET Core MVC.
Worked with database and From the View menu, opened SQL Server Object Explorer (SSOX).
Right-clicked on the Movie table under dbo.Movie expaned View Designer to 
I learned how to connect an application to a database and perform CRUD operations.
Created a new class named SeedData in the Models folder and added the neccessary code

2024-01-25
1320

##Part 6: Controller Actions and Views
I het into controller actions and views. 
I learned how to handle user requests, 
Then processed and displayed data the appropriate views.
1>------ Build started: Project: MvcMovie, Configuration: Debug Any CPU ------
1>Skipping analyzers to speed up the build. You can execute 'Build' or 'Rebuild' command to run analyzers.
1>MvcMovie -> C:\Users\eluri\source\repos\MVcMovie\MvcMovie\bin\Debug\net8.0\MvcMovie.dll
========== Build: 1 succeeded, 0 failed, 0 up-to-date, 0 skipped ==========
========== Build completed at 1:22 PM and took 51.234 seconds ==========

2024-01-26
1510
##Part 7: Add Search to filter:
I added search button to check records by filter.
Then Navigated to /Movies/Index to displayed filtered movies.
Opened the Views/Movies/Index.cshtml file, and added the form markup to get Title filter option for easy search.

2024-01-26
1530
##Part 8: Add a New Field named Rating:
First I Added the rating Property in Models/Movie.cs. 
Later, Edited the /Views/Movies/Index.cshtml file and add a Rating field inside view templates in order to display.
Updated the SeedData class so that it provides a value in between the genre and price field for the column Rating = "R",
From the Tools menu, selected NuGet Package Manager > Package Manager Console In the PMC, enter the commands : Add-Migration Rating
Update-Database to examine the current Movie model.

Then I have varied the functionality of filter option by filtering bollywoord movies name, rating and genre.

2024-01-31
2110
##Part 9: Add Validation:
I have applied validation to confirm data accuracy by ensuring user input and handling validation errors.
to examine the current Movie model.
Confirmed that in the Movie class, attributes such as Required, StringLength, RegularExpression, Range and the DataType exist.
In Next step I updated existing movie list with my 2 top most favorite Bollywood pictures.

2024-01-31
2158
##Part 10: Examine Details and Delete methods:
I have explored the details to check view and deletion operation.
I have understood how to display users detailed information and allow them to delete records..
At the end, Then I have varified the functionality of filter option by filtering bollywoord movies name, rating and genre


