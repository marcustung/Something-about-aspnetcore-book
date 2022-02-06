# Something about ASP.NET Core ebook
The Something about ASP.NET Core Book is introduction to  web programming and based on ASP.NET Core 2.2

*by Marcus Tung*

***

<img alt="star-wars-font" border="0" src="https://fontmeme.com/permalink/190813/68dded8b6b02cad6215108ab0b70a6d3.png" />

## 前言
ASP.NET Core 的二三事

* Something about ASP.NET Core 電子書是自己在學習 ASP.NET Core 的個人筆記整理而成，如果內容有不清楚或是錯誤的地方歡迎一起討論。
* 電子書內容會持續更新，目前以 .NET Core 2.2 為主，待 .NET Core 3.0 Release 之後會持續加入 3.0 相關內容。
* 範例程式 sample code 位置 (持續補齊中) : [傳送門](https://github.com/marcustung/BlogSampleCode)

## 章節 
目前電子書版本為 alpha 版，章節如下

* Logging
    > Logging 日誌初體驗 (一)  
    > Logging 日誌初體驗 (二)  
    > 使用 NLog 紀錄日誌資訊    
    > Serilog 初體驗  
    > Serilog - 配置設定  
    > Serilog - Events Types 和 Enrichment  
    > Serilog Analyzer  
    > ASP.NET Core Web API 中使用 Serilog

* Configuration
    > 如何取得 appsettings.json 組態設定  
    > ENVIRONMENT 使用環境變數  
    > Windows 如何更新環境變數 Environment Variable  
    > 如何在 ASP.NET Core 中使用 YAML  
    > 設定 JSON 序列化格式      
    > ASP.NET Core 使用強型別取代 IOption 注入配置 

* Startup
    > 環境佈署設定 appsettings.json  

* Dependency-Injection
    > ASP.NET Core DI 生命週期 LifeTime  

* Middleware 
    > UseStaticFiles  
    > 使用 Big5 中文編碼  
    > Health Check  

* Web Server
    > 在 IIS 執行 ASP.NET Core 應用程式  
    > Kestrel Web Server  

* Entity Framework Core
    > 安裝 Entity Framework Core  
    > 安裝 Entity Framework Core - 使用 EF Core Power Tool  
    > Entity Framework Core 初體驗  

* Gerenic Hosting
    > 建立排程服務 - Generic Host 搭配 Quartz.Net - Hosted Builder  
    > 建立排程服務 - Generic Host 搭配 Quartz.Net - Quartz.NET  
    > 建立排程服務 - Generic Host 搭配 Quartz.Net - Windows Service  

* ASP.NET Core 3.0
    > 3.0 Preview 體驗  

* 第三方 Library  
    > Quartz.NET 初體驗  
    > 限流框架 AspNetCoreRateLimit  
    > 限流框架 AspNetCoreRateLimit 整合 Redis  
    > 使用 Polly 實現重試 (Retry) 策略  
    > Polly 的超時 TimeOut 和 Wrap 策略  
    > Polly 重試機制搭配 jitter 策略  

* Microsoft Azure
    > Azure 初體驗    
    > 打包 ASP.NET Core 應用程式到 Docker Hub 並發佈到 Azure    
    > Microsoft Azure 免費 DevOps 電子書開放下載   
    > 建立 Azure Container Registry 並整合 Microsoft Team 通知   

* 遇到的問題
    > [IIS] Unable to connect to web server 'IIS Express'  
    > [IIS] 'IWebHostBuilder' does not contain a definition for 'ConfigureKestrel' and no accessible extension method 'ConfigureKestrel'  
    > [IIS] 啟動失敗 - failed to start process with commandline   
    > [IIS] 啟動異常 - HTTP Error 500.30 - ANCM In-Process Start Failure  
    > [IIS] 啟動失敗 - 嘗試存取通訊端被拒絕，因為存取權限不足  
    > [Job] Quartz.NET 排程執行異常 - All triggers of Job class set to ERROR state.  
    > [Unittest] ASP.NET Core 2.2 測試專案中的版本衝突  
    > [Azure] VisualStudio 2019 部署 Azure 失敗 : Publish has encountered an error. Build Failed.

* 分散式追蹤
    > 現代化監控使用 OpenTelemetry 實現 : 可觀測性(Observability)     
    > 現代化監控使用 OpenTelemetry 實現 : OpenTelemetry 開放遙測     
    > 現代化監控使用 OpenTelemetry 實現 : 在 .NET 如何使用 OpenTelemetry     
    
* 未分類
    > QueryHelpers - 建立與解析 QueryString 參數  
    > Dotnet Watch - 使用 Dotnet Watch 自動編譯 ASP.NET Core 應用程式   
    > Apiversion - 加入 API 版本控制   
    > 自己的 SSD 自己救 - 移除未使用的 ASP.NET Core SDK    
    > BenchmarkDotNet - 使用 BenchmarkDotNet 測試程式碼效能     
    > 如何在 ASP.NET Core Middleware 加上單元測試 UnitTest    
    > ASP.NET Core 中的例外處理方式  
 

## ASP.NET Core 學習資源

* [ASP.NET Core](https://docs.microsoft.com/zh-tw/aspnet/core/) : 微軟官方線上文件
* [ASP.NET Core 中文](https://docs.microsoft.com/zh-tw/aspnet/core) : 微軟官方線上文件中文版
* [ASP.NET Core in Action ](https://www.manning.com/books/asp-net-core-in-action?a_aid=aspnetcore-in-action&a_bid=5b1b11eb) : 電子書 by Andrew Lock
* [ASP.NET Core 應用開發](https://www.tenlong.com.tw/products/9787302479901) : 實體書
* [ASP.NET Core 跨平臺開發從入門到實戰](https://www.tenlong.com.tw/products/9787121311451) : 實體書
* [Awesome-dotnet-core](https://github.com/thangchung/awesome-dotnet-core) : Awesome 系列 github repo
* [C# in Depth Fourth Edit](https://www.manning.com/books/c-sharp-in-depth-fourth-edition) : 電子書  
* [SNEAK PEEK: ASP .NET Core A-Z eBook](https://wakeupandcode.com/sneak-peek-asp-net-core-a-z-ebook/) : 電子書
* [STEVE GORDON](https://www.stevejgordon.co.uk/)
* [Artech](https://www.cnblogs.com/artech/) 

## 給作者鼓勵 ⭐️⭐️⭐️
如果你喜歡 Something about ASP.NET Core 電子書或者覺得這本電子書對你有幫助，請不吝給我一顆星給予鼓勵，非常感謝您 :)

Blog : [m@rcus 學習筆記](https://marcus116.blogspot.com/)  
GitHub : [https://github.com/marcustung](https://github.com/marcustung)  
聯絡信箱 : [GMAIL](marcustung116@gmail.com)
