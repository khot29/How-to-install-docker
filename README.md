# On amazon Linux or debian based system 

   1 yum install docker
   
   2 which docker

# On ubuntu system 

   1  sudo apt-get install ca-certificates curl gnupg lsb-release
   
   2  echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
      $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
      
   3  ls -al /etc/apt/sources.list.d | grep docker
   
   4  sudo apt update -y

   5  sudo apt-get install docker-ce docker-ce-cli containerd.io

   6  which docker

