# Desativando Hibernação do Windows

PowerShell como Administrador e rodar o comando: 

powercfg.exe /hibernate off 

# config-windows-chocolatey
repositorio com alguns comandos de instalação do chocolatey no windows

# -- COMANDO PARA INSTALAR  CHOCOLATEY ---

Abrir o PowerShell como Administrador e executar :

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

# Alguns Programas

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

choco install dbeaver -y

choco install postman -y

choco install eclipse -y

choco install jetbrainstoolbox -y

choco upgrade chocolatey

choco install powershell-core -y

choco install ccleaner -y --ignore-checksums
