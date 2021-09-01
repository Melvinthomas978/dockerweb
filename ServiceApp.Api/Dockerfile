FROM mcr.microsoft.com/dotnet/sdk:5.0 AS build-env
WORKDIR /app



# Copy everything else and build
COPY / /app
ENTRYPOINT ["dotnet", "ServiceApp.Api.dll"]