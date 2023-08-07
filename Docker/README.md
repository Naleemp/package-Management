
#!/bin/bash
sudo hostname docker
sudo hostnamectl set hostname docker  
sudo apt update -y 
sudo apt install docker.io -y
sudo usermod -aG docker ubuntu 
sudo su - ubuntu