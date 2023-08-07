### **Author:Simon Peter Mendy **
### **Email:simonpeter@nalempinfotech.com,mendysimonpeter@gmail.com**
###**Install Docker on  Ubuntu**


sudo apt update -y


sudo apt install docker.io -y


sudo service docker start

sudo docker info

sudo hostnamectl set-hostname docker   

sudo su - ubuntu

You will get permission denied error as regular user 
doesn't have permissions to execute docker commands. 
Add user to docker group.

sudo usermod -aG docker $USER 
     or 
sudo usermod -aG docker ubuntu
sudo su - ubuntu  

# Exit From Current SSH Terminal & SSH(Login) again . Then execute 
docker ps

# Amazon Linux
###########################
sudo yum update -y    
sudo yum install docker -y
sudo service docker start

Add Regular user to docker group
sudo usermod -aG docker  <username>
