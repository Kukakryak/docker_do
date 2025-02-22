# docker_do
CLI commands to build images and run containers:
  docker build -t yourtag/ubuntu_nginx:v1
  docker build -t yourtag/mysql:v1
  docker run -d --name yourname -p 8080:80 -p 334:443 yourname/ubuntu_nginx:v1
  docker run -d --name yourname -p 6603:3306 yourname/mysql:v1
