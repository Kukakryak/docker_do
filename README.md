# docker_do
CLI commands to build images and run containers:
------------------------------------------------
**Building in ./ubuntu_nginx:**\
docker build -t yourtag/ubuntu_nginx:v1 .

**Building in ./mysql:**\
docker build -t yourtag/mysql:v1 .

**Running containers and publishing their ports:**\
docker run -d --name yourname -p 8080:80 -p 334:443 yourname/ubuntu_nginx:v1\
docker run -d --name yourname -p 6603:3306 yourname/mysql:v1
