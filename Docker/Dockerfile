FROM mcr.microsoft.com/dotnet/aspnet:8.0

WORKDIR /app

COPY publish/ ./

ENV ASPNETCORE_HTTP_PORTS=4000
ENV ASPNETCORE_URLS=http://0.0.0.0:4000

EXPOSE 4000

ENTRYPOINT ["dotnet", "SporeServer.dll"]
