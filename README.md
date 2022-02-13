# APIGatewayOcelotASPNET
:book: How to build an API Gateway in ASP.NET Core using Ocelot


API Gateway is an API management tool that usually sits between the external caller (Web or Mobile) and the internal services. The API Gateway can provide multiple features like:

1. Routing
2. Request Aggregation
3. Authentication
4. Authorization
5. Rate Limiting
6. Caching
7. Load Balancing
ETC.

Ocelot is an ASP.Net Core (Supports .Net Core 3.1) API Gateway. It's a NuGet package, which can be added to any ASP.Net Core application to make it an API Gateway.

Ocelot API Gateway supports all the features that any standard API Gateway does.

I will cover the following features of Ocelot API Gateway in this video:

1. Routing (Basic routing to internal service)
2. Authentication (JWT Token-based authentication)
3. Response Caching (Using Ocelot.Cache.CacheManager NuGet package)
4. Rate limiting

More information about Ocelot API Gateway is available in their website here: https://ocelot.readthedocs.io/en/latest/index.html

The source code for video studig is available in GitHub repo here: https://github.com/choudhurynirjhar/ocelot-demo
