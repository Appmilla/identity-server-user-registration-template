# identity-server-user-registration-template
.Net CLI template for Identity Server with ASP.Net Core Identity

IdentityServer v6 with ASP.Net Core Identity for user registration and focus on mobile client using PKCE OAuth 2.0 flow.

The nuget package containing the template is available at :- https://www.nuget.org/packages/Appmilla.IdentityUserReg/1.0.0

An overview video with a demo can be found at https://youtu.be/U4WXru88NCQ

Example clients can be found in this repo:- https://github.com/Appmilla/identity-server-user-registration-example

To install the template from the nuget package:-
dotnet new -i Appmilla.IdentityUserReg.1.0.0.nupkg

The installed template should be listed like this:-

Identity Server with ASP.NET User Registration isuserreg [C#] Web/MVC/Razor Pages

To create a new IdentityServer host project use :

dotnet new isuserreg -n YOUR_NAME_FOR_THE_SERVER

Running the project should display the Duende IdentityServer page on port 5001

The Identity Server supports registering a user, login and logout with a variety of clients including PKCE.
