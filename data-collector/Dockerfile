FROM mcr.microsoft.com/powershell:7.1.0-ubuntu-focal
RUN apt update && apt install brotli
ENTRYPOINT ["pwsh", "-c", "/bigipreport/bigipreport.ps1"]
