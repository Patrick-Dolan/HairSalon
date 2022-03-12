# Eau Clairs Salon Manager

#### By _**Patrick Dolan**_

#### _A simple management software that tracks stylists and their individual clients._

## Technologies Used

* C#
* .NET 5.0
* dotnet

## Description

A management software for Eau Clair's Salon to track stylists and their clients. You can do the following operations with the software:

* View a list of all stylists.
* Select a stylist to see their details and a list of their clients.
* Add new stylists to the system.
* Add new clients to a specified stylist. (All clients must be assigned to a stylist)

## Setup/Installation Requirements

* Download repo to your computer using either clone or the download link.
* Open the project in VScode or your terminal/IDE of choice.
* Create a <code>appsettings.json</code> file in the root directory of the project folder. And add the following code replacing anything in square brackets with the information it represents specific to the project database:
```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=[DATABASE-NAME-HERE];uid=[USER-ID-HERE];pwd=[YOUR-PASSWORD-HERE];"
  }
}

```

Example of complete appsettings.json:
```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=to_do_list;uid=root;pwd=MySuperStrongPassword;"
  }
}

```
* CONTINUE WITH PROJECT SPECIFIC INSTRUCTIONS FROM HERE!

### Test Setup/Installation

* Open the repo on your editor of choice/terminal
* Navigate to ProjectName.Tests directory in your terminal
* Run the following command to setup testing:  
<code>dotnet restore</code>  
* Run tests by going to the test project in the terminal (ProjectName.Solution/ProjectName.Tests) and running the following command:  
<code>dotnet test</code>  

## Known Bugs

* _No known issues_

## Contact Me

Let me know if you run into any issues or have questions, ideas or concerns:  
dolanp1992@gmail.com
## License

_MIT_

Copyright (c) _2022_ _Patrick Dolan_