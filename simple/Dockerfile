FROM mcr.microsoft.com/dotnet/core/aspnet:2.2
LABEL author leomicheloni
LABEL email leomicheloni@hotmail.com
ENV ASPNETCORE_URLS=http://+:81
EXPOSE 81
WORKDIR /app
COPY publish/. .
ENTRYPOINT [ "dotnet", "samples.dll" ]