## Installation of C# Extension on VS Code

https://www.youtube.com/watch?v=WeTesTCzep0

## .NET Installation On Ubuntu

```

sudo -s

wget https://packages.microsoft.com/config/ubuntu/20.10/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb

sudo apt-get update; \
  sudo apt-get install -y apt-transport-https && \
  sudo apt-get update && \
  sudo apt-get install -y dotnet-sdk-5.0
  
 sudo apt-get update; \
  sudo apt-get install -y apt-transport-https && \
  sudo apt-get update && \
  sudo apt-get install -y aspnetcore-runtime-5.0

dotnet --version

dotnet new

dotnet new console -o hello-world 

cd run/

dotnet run 

```
