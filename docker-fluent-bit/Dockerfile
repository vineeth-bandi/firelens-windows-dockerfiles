FROM mcr.microsoft.com/windows/servercore:ltsc2019 
COPY container_setup.ps1 /container_setup.ps1
COPY fluent-bit.exe /fluent-bit.exe
EXPOSE 24224 5140
ENTRYPOINT ["powershell", "C:\\container_setup.ps1"]

