# config-windows-chocolatey
repositorio com alguns comandos de instalacao de do chocolatey no windows




#-- COMANDO PARA INSTALAR  CHOCOLATEY ---

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))


choco install googlechrome -y

choco install notepadplusplus.install -y

choco install git.install -y

choco install nodejs.install -y

choco install microsoft-teams -y

choco install openjdk11 -y

choco install openjdk11jre -y

choco install python -y

choco install vscode -y

choco install maven -y
