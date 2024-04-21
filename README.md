# docker installation and 
     #1  docker -v
    2  docker --version
    3  sudo apt-get update
    4  sudo apt-get install ca-certificates curl
    5  sudo install -m 0755 -d /etc/apt/keyrings
    6  sudo curl -fsSL https://download.docker.com/linux/ubuntu/gpg -o /etc/apt/keyrings/docker.asc
    7  sudo chmod a+r /etc/apt/keyrings/docker.asc
    8  echo   "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.asc] https://download.docker.com/linux/ubuntu \
    9    $(. /etc/os-release && echo "$VERSION_CODENAME") stable" |   sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
   10  sudo apt-get update
   11  sudo apt-get install docker-ce docker-ce-cli containerd.io docker-buildx-plugin docker-compose-plugin
   12  docker -v
   13  service docker status 
   14  sudo usermod -aG docker ubuntu --after that restart the server..
   15  docker images
   16  docker run -itd --name studentapp -p 8080:8080 49721599fbb0
   17  docker ps -a
   18  docker port studentapp
   19  ls
   20  mysql -h docker-new-rds.cl8ke82qot1x.ap-south-1.rds.amazonaws.com -u admin -p
   21  ls
   22  docker ps -a
   23  history --> -->
