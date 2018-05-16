# <a name="aspnet-core-middleware-extensibility-sample"></a><span data-ttu-id="26c04-101">ASP.NET Core 中间件扩展性示例</span><span class="sxs-lookup"><span data-stu-id="26c04-101">ASP.NET Core Middleware Extensibility Sample</span></span>

<span data-ttu-id="26c04-102">本示例演示如何将 [IMiddleware](https://docs.microsoft.com/dotnet/api/microsoft.aspnetcore.http.imiddleware) 和 [IMiddlewareFactory](https://docs.microsoft.com/dotnet/api/microsoft.aspnetcore.http.imiddlewarefactory) 与第三方依赖项注入容器[简单注入器](https://simpleinjector.org)配合使用。</span><span class="sxs-lookup"><span data-stu-id="26c04-102">This sample illustrates the use of [IMiddleware](https://docs.microsoft.com/dotnet/api/microsoft.aspnetcore.http.imiddleware) and [IMiddlewareFactory](https://docs.microsoft.com/dotnet/api/microsoft.aspnetcore.http.imiddlewarefactory) with a 3rd party dependency injection container, [Simple Injector](https://simpleinjector.org).</span></span> <span data-ttu-id="26c04-103">本示例演示 [Middleware activation with a third-party container in ASP.NET Core](https://docs.microsoft.com/aspnet/core/fundamentals/middleware/extensibility-third-party-container)（使用 ASP.NET Core 中的第三方容器激活中间件）中所述的功能。</span><span class="sxs-lookup"><span data-stu-id="26c04-103">This sample demonstrates the features described in [Middleware activation with a third-party container in ASP.NET Core](https://docs.microsoft.com/aspnet/core/fundamentals/middleware/extensibility-third-party-container).</span></span>