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
![JesusSportsStore](https://user-images.githubusercontent.com/68295669/94358113-7f1fad00-0053-11eb-9f8d-817365641cac.PNG)

# Chapter 8 screenshot
![Chapter 8](https://user-images.githubusercontent.com/68295669/95005647-28b0f200-05b0-11eb-91e9-018de63239ac.PNG)
