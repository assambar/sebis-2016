# Какво
Свалете source кода от тук
https://bitbucket.org/ogi/aspnetecommerce

#Стъпки

1. Подкарване на web site във Visual Studio
 - Създайте нов сайт - New > Web Site > Empty C# Web Site (НЕ ИЗПОЛЗВАЙТЕ New > Project > Web Site)
 - Копирайте кода от глава 03/BalloonShop във вашия проект през Windows Explorer
 - Refresh
 - Run
 
2. Подкарване на връзката с базата данни
 - Създайте нов сайт
 - Копирайте кода от глава 04/BalloonShop и цъкнете Refresh
 - На вашия SQL server създайте база BalloonShop
 - Изпълнете заявките от глава 04/Database
 - Конфигурирайте настройките за връзка с базата в web.config
 - Run
 
3. Подкарване на Full-text search
 - Създайте нов сайт
 - Копирайте кода от глава 08/BalloonShop и цъкнете Refresh
 - Изпълнете заявките от Database от глава 05 до глава 08
 - Конфигурирайте настройките за връзка с базата в web.config
 - Run
 
4. Подкарване на потребителски account-и
 - Създайте нов сайт
 - Копирайте кода от глава 11/BalloonShop и го Refresh-нете
 - Изпълнете C:\Windows\Microsoft.NET\Framework\v2.0.50727\aspnet_regsql.exe за да добавите потребителски таблици към BalloonShop 
 - Пуснете администриращото приложение на ASP.NET
 
          cd "C:\Program Files\IIS Express"
          iisexpress.exe /path:C:\Windows\Microsoft.NET\Framework\v4.0.30319\ASP.NETWebAdminFiles /vpath:"/ASP.NETWebAdminFiles" /port:8082 /clr:4.0 /ntlm


 - В browser-а отворете следния URL 
   http://localhost:8082/ASP.NETWebAdminFiles/default.aspx?applicationPhysicalPath=C:\<PATH_TO_YOUR_PROJECT_FOLDER>&applicationUrl=/`
