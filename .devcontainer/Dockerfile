FROM mcr.microsoft.com/windows/servercore:ltsc2019 AS base
ARG VARIANT="sdk"
RUN powershell.exe -Command "Invoke-WebRequest -Uri https://dotnet.microsoft.com/download/dotnet-core/scripts/v1/dotnet-install.ps1 -OutFile dotnet-install.ps1;.\dotnet-install.ps1 -Channel 6.0 -InstallDir 'C:\\Program Files\\dotnet' -NoPath"
# 根据需要添加更多的安装步骤，比如安装其他开发工具等
