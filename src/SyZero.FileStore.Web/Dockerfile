﻿FROM mcr.microsoft.com/dotnet/aspnet:8.0 AS base

WORKDIR /app
EXPOSE 5001
COPY . .
ENTRYPOINT ["dotnet", "SyZero.FileStore.Web.dll"]