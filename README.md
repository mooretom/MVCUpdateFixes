# MVC Update Fixes
This project was created after I started a new .NET framework 4.8 MVC project, then applied all of the pending NuGet updates and everything broke.

This seems to throw people off quite a bit, so I have collected all of the changes into a single GitHub Repo. That you can grab. As I find things that are broken, I will try and add the files in there. Most of the problems seem to arise from updating the bootstrap package which is used extensively in the default MVC Project.

# Using this project:
Create a new ASP .NET MVC application.

Use NuGet to update all packages.

Use the files in this package to update your project.

# Files updated in this package:
App_Start/
     BundleConfig.cs - Updated

Content/
     jumbotron.css - Added

Views/
     Shared/
          _Layout.shtml
          _LoginPartial.shtml
