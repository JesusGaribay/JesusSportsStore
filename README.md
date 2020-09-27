# JesusSportsStore
Walkthrough from Adam Freeman's book Pro ASP.NET Core 3

dotnet new globaljson --sdk-version 3.1.401 --output ECommerceProject
dotnet new web --no-https --output ECommerceProject --framework netcoreapp3.1
dotnet new sln -o ECommerceProject
dotnet sln ECommerceProject add ECommerceProject
dotnet new xunit -o ECommerceProject.Tests --framework netcoreapp3.1
dotnet sln ECommerceProject add ECommerceProject.Tests
dotnet add ECommerceProject.Tests reference ECommerceProject
# Chapter 7 screenshot
