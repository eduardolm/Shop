# Shop
## Basic Authentication / Authorization API, using JWT, written in C#

This is a sample .NET Core Web API.
The API illustrates how easy it can be to implement basic authentication and authorization usin JWT with .NET Core.
The API creates two users, with different roles and allows them to login and use the generated JWT to access different endpoints.

## Installation
In order to use this API, .NET Core SDK 3 must be installed.
After making sure the .NET Core requirements have been satisfied, just clone this repository to your computer. After cloning, type the following code on either command prompt or powershell:

    cd Shop
    dotnet restore
    dotnet add package Microsoft.AspNetCore.Authentication
    dotnet add package Microsoft.AspNetCore.Authentication.JwtBearer

Finally, just open the project using your preferred IDE and run it.
