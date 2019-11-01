Introduction
The web app was maded using Flask which is a micro web framework using python language. 

Pre-requistes
sudo apt


Running the App with Google cloud platform with Jenkins
#install git 
sudo apt-get install git
#clone down the repo
git clone https://github.com/sharonkele/gcp
cd in Stylist
#install Jenkins using the the script called Jenkins-install.sh
Create a new item with freestyle project








To Run with Docker in Google cloud platform 

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
#run the app in
docker run -d -p 5000:5000 --name flaskapp flaskapp 





To run with Jenkins
