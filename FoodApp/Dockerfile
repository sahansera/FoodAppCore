FROM mcr.microsoft.com/dotnet/core/aspnet
COPY ./app /app
WORKDIR /app
EXPOSE 8080
ENV ASPNETCORE_URLS=http://*:8080/
ENTRYPOINT ["dotnet", "FoodApp.dll"]