FROM microsoft/aspnetcore:2.0
ARG source
WORKDIR /app
EXPOSE 9001/tcp
COPY ${source:-obj/Docker/publish} .
ENTRYPOINT ["dotnet", "CI.WebApp.dll"]
