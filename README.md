# Cara Install Omada-Controller
```
sudo apt-get update
sudo apt install openssh-server -y
sudo apt install openjdk-8-jre-headless jsvc curl -y
curl -fsSL https://www.mongodb.org/static/pgp/server-4.4.asc | sudo apt-key add -
sudo apt update && sudo apt-get install mongodb
sudo apt-get install jsvc
sudo apt-get install openjdk-8-jdk
sudo update-alternatives --config java
sudo apt install gdebi-core -y
cd
sudo wget https://static.tp-link.com/2021/202102/20210209/Omada_SDN_Controller_v4.2.11_linux_x64.deb
cd
sudo -i gdebi Omada_SDN_Controller_v4.2.11_linux_x64.deb
