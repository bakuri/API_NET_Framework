FROM mcr.microsoft.com/windows/servercore:ltsc2019
SHELL ["powershell"]

RUN Install-WindowsFeature NET-Framework-45-ASPNET ; \
    Install-WindowsFeature Web-Asp-Net45

EXPOSE 80
