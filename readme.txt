Author: Aarsal Masoodi
Date Created: November 1st, 2021

Date Modified: November 2nd, 2021

I created a project through Visual Studio 2019. It was through an ASP.NET Core Web App (Model-View-Controller) template.
I explored the defaulty created Models, Views, and Controllers. 
I reviewed the other default files as well, such as the IActionResult that takes me to the various navigations and returns the View.

I experimented with debugging and creating break points at the home controller page.

I chose a different bootstrap theme through the website Bootswatch.com. The theme I chose is called "Solar".
I replaced the bootstrap.min.css file under the wwwroot/lib/boostrap/dist/css folders. 
I replaced the site.css found under wwwroot/css with a file I obtained from blackboard.

I changed various properties in the project, such as making the nav class have a dark nav bar instead of white.
I added several additional scripts that I will use in the site. I added them to the bottom of the _Layout.cshtml page.

I created 3 new projects, which were .Net Core class library projects. I then copied the Data folder from the main project into the AarsalsBooks.Data class library.
I installed two packages through the NuGet installer built into visual studio 2019. EntityFramework Core.Relational and Core.SqlServer.

I then deleted the migrations folder, inside the data folder. 