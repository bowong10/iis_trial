# IIS_trial
IIS Trial

Install ISS
https://docs.microsoft.com/en-us/aspnet/web-forms/overview/deployment/visual-studio-web-deployment/deploying-to-iis

Control Panel -> Program and Features -> Turn Windows features on or off -> 
Internet Information Services -> World Wide Web Services -> Application Development Feature -> ASP.Net, Extensibility (install all)

Install Web Platform Installer
https://www.microsoft.com/web/downloads/platform.aspx
Install these with the installer:
1) URL rewrite
2) IIS: .net extensibility 4.5
3) IIS: Management Service
4) IIS: WAS .Net Environment
5) IIS: Windows Authentication

-- To Azure and beyond lol
https://www.youtube.com/watch?v=PPaqVyBkwMk

Config at Internet Information Services (IIS) Manager

-- add ip mapping here
C:\Windows\System32\drivers\etc\hosts

-- good video :)
https://www.youtube.com/watch?v=1VdxPWwtISA 

add this to hostfile => 127.0.0.1	test_web.com
edit your binding to set hostname = test_web.com

then you will browse to that site when you enter the domain in browser
outside currently has to use IP:port to access

ref
https://stackify.com/how-to-deploy-asp-net-core-to-iis/
https://stackoverflow.com/questions/18981118/http-error-403-14-forbidden-the-web-server-is-configured-to-not-list-the-con
https://www.c-sharpcorner.com/article/how-to-deploy-asp-net-mvc-4-application-on-local-iis/
