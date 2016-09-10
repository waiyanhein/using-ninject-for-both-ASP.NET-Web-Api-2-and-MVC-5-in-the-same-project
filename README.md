## Using ninject for both ASP.NET Web-Api 2 and MVC 5 in the same project (using C# programming language)

This is the solution for using ninject dependency injection in ASP.NET for Web Api 2 and MVC 5 in the same project.Just follow the following steps.

####Step 1 - Install Ninject for Web Api using nuget package manager

![alt tag](https://github.com/waiyanhein/using-ninject-for-both-ASP.NET-Web-Api-2-and-MVC-5-in-the-same-project/blob/master/Screenshot%20(185).png)

####Step 2 - Install ninject Ninject.Web package using nuget package manager

![alt tag](https://github.com/waiyanhein/using-ninject-for-both-ASP.NET-Web-Api-2-and-MVC-5-in-the-same-project/blob/master/Screenshot%20(182).png)

####Step 3 - Install Ninject for MVC 5 web application using nuget package manager

![alt tag](https://github.com/waiyanhein/using-ninject-for-both-ASP.NET-Web-Api-2-and-MVC-5-in-the-same-project/blob/master/Screenshot%20(184).png)

####Step 4 - Then replace your NinjectWebCommon class in the App_Start folder with this one

https://github.com/waiyanhein/using-ninject-for-both-ASP.NET-Web-Api-2-and-MVC-5-in-the-same-project/blob/master/NinjectWebCommon.cs

#####That's it. You are done. Now you can use ninject to resolve dependencies for ASP.NET MVC Web project built together with Web Api 2. 

####If Ninject.WebApi.DependencyResolver is required or missing, run "install-package Ninject.WebApi.DependencyResolver" in package manager console.

#####If any error throwing, update packages running this command in package manager console
``
update-package
``
