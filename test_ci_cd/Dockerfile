FROM gcr.io/google-appengine/aspnetcore:3.1
ADD ./ /app
ENV ASPNETCORE_URLS=http://*:5000
WORKDIR /app
ENTRYPOINT [ "dotnet", "test_ci_cd.dll" ]