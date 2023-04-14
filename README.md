# kendimedocker
kullandığım docker komutları
# docker ps
# docker ps -a
# tüm docker ağlarını listelemek için : docker network ls
# docker-compose -v
# docker logs --follow <CONTAINER_NAME>
# docker stop <CONTAINER_NAME>
# docker rm <CONTAINER_NAME>
# docker restart <CONTAINER_NAME>
# docker start <CONTAINER_NAME>
# docker sorun yaşayanlar için kodlar:
# sudo apt install pkg-config curl git-all build-essential libssl-dev libclang-dev ufw 
# sudo apt-get install ca-certificates curl gnupg lsb-release
# sudo mkdir -p /etc/apt/keyrings
# curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /etc/apt/keyrings/docker.gpg
# echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/etc/apt/keyrings/docker.gpg] https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
  # sudo chmod a+r /etc/apt/keyrings/docker.gpg
# sudo apt-get update
# sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose-plugin
# sudo apt install docker-compose
# sudo docker run hello-world
# docker-compose -v
