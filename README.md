# _Eau Claire's Salon_
## Salon Business Management App

#### By _Dani Steely_

#### _A Stylist and Client management application using Entity Framework Core and MySQL database; a project made for Epicodus C# with .NET course_

## Technologies Used
* _C#_
* _Razor Markdown_
* _ASP.NET Core MVC_
* _Entity Framework Core_
* _MySQL_

## Description

This application is an independent project created as part of [Epicodus][Epicodus] coursework in [C# with .Net][C# course main]. The project was completed after week six: ["Database Basics"][C# chapter]. The application displays stylist and client information for a fictional hair salon business. The application was created to demonstrate ability to use the Entity Framework Core and to use MySQL databases with one-to-many relationships. The application uses ASP.NET Core MVC to handle routing and requests and uses Entity FrameWork Core to communicate to a MySql database using .NET objects. The user is able to add new stylists and view a list of stylists, view details about the stylist, add a new client connected to a singular stylist, view a list of all clients, and view details about the client. 

## Stretch Goals/Next Steps
- _Include Edit and Delete biews for both clients and stylists_
- _Include form for searching stylists_
- _Include form for searching client_
- _Add appointments to clients/stylists with check for conflicting appointments_
- _Add payment tracking functionality_

## Setup/Installation Requirements
#### Setting up directories
* clone this repo to your desktop
* navigate to project directory in your terminal
* you may want to include a .gitignore file in your root directory
* in your .gitignore file you can include the appsettings.json file that you will need to create in the next step
#### Creating an appsettings file
* navigate to "HairSalon" directory
* create a new file in "HairSalon" folder titled appsettings.json
* the following code should go in the appsettings.json file
```json
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=[DATABASE-NAME];uid=[USERNAME];pwd={PASSWORD};"
  }
}
```
* within the appsettings.json file, you will need to replace `[DATABASE-NAME]` with the name of the database, `[USERNAME]` with your username, and `[PASSWORD]` with your password
#### Launching application
* navigate to "HairSalon" directory
* launch with command `$ dotnet run`
* if you make changes, you may want to use a file watcher
* you can run program with watcher using command `$ dotnet watch run`

## Known Bugs
- No known bugs

## License

_MIT License_
MIT License

Copyright (c) _3/11/23_ _Dani Steely_

[Epicodus]: https://www.epicodus.com/
[C# course main]: https://www.learnhowtoprogram.com/c-and-net-part-time
[C# chapter]: https://www.learnhowtoprogram.com/c-and-net-part-time/database-basics
