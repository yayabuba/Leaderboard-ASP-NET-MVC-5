## Features
The leader board table shows the highest ranking Competitor at the top.
The leader board aggregates number of games played, won, lost, drawn and the total points for each competitor.  
The leader board order updates as head to head competitions are added.
New Competitors can added.
New Head to Head competitions can be added. 
The round can be selected when Head to Head competitions are added.
The first three rounds are have already been added. 
Selecting an existing round will overwrite that round.

## Setup
Project Targets .NET Framework 4.6.1
Run in Visual Studio 2017
Right Click Project / Manage NuGet Packages... / Click the Restore button to get required packages.

## Notes
I decided against using ASP.NET Core MVC because I have a better knowledge of ASP.NET MVC 5.
I did not have time to add a Referee identity. I was considering using the Microsoft.AspNet.Identity.Core package.
I did not have time to add tests to the controller and models.
The model uses static data rather than a database.
