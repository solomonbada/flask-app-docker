Introduction


Pre-requistes
sudo apt


To run on Google Cloud Platform with Jenkins





To Run with Docker

#First install Docker
curl https://get.docker.com|sudo bash
#to use docker without sudo
sudo usermod -aG docker $(whoami)
#to confirm user has been added to docker group
id -nG
#check status of docker
systemctl status docker 
#create an image
docker run hello-world 

#Create a Docker directory
mkdir 'your choosen name'

#Pull down Dockerfile and use it to build an image 
docker build -t Stylist
docker run -d -p 5000:5000 --name flaskapp flaskapp 





To run with Jenkins
