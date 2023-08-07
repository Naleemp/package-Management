### **Author:Simon Peter Mendy **
### **Email:simonpeter@nalempinfotech.com,mendysimonpeter@gmail.com**
#!/bin/bash
sudo apt update -y
sudo apt install docker.io -y
sudo service docker start
sudo docker info
sudo hostnamectl set-hostname docker   
sudo su - ubuntu