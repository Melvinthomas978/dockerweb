FROM mcr.microsoft.com/dotnet/sdk:5.0 AS build-env
WORKDIR /app



# Copy everything else and build
COPY /test/ /app
ENTRYPOINT ["dotnet", "ServiceApp.Api.dll"]