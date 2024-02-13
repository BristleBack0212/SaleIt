# SaleIt

A Simple Vehicle Dealer App built with ASP.NET Core + Angular 4

## Features 
- Only Admin/Moderator can perform Create/Edit/Delete operations & upload photos.
- Normal User only can view the vehicle details & see report of vehicles in charts view.
- Server Side Sorting & Pagination
- Role Based Athentication

## Framework / Library / Service Used
- Angular 4 *(Frontend)*
- ASP.NET Core *(Backend)*
- Entity Framework Core *(ORM)*
- Auth0 *(Authentication & Authorization)*
- AutoMapper *(For mapping into Domain Model & DTO)*
- Chart.js *(For Pie Chart)*

## To run the project:
```
    > npm install
    > dotnet restore
    > set ASPNETCORE_ENVIRONMENT=Development
    > set connectionString:Default="<YOUR CONNETION STRING>"
    > npm i webpack -g
    > webpack --config webpack.config.vendor.js
    > webpack 
    > dotnet ef database update
    > dotnet watch run 
```