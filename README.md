# pcf-coso-header

setup:
Install .Net 6 SDK
wget https://packages.microsoft.com/config/ubuntu/22.04/packages-microsoft-prod.deb -O packages-microsoft-prod.deb
sudo dpkg -i packages-microsoft-prod.deb
rm packages-microsoft-prod.deb
sudo apt-get update && \
  sudo apt-get install -y dotnet-sdk-6.0

dotnet --list-sdks

rm dotnet 7 in folder