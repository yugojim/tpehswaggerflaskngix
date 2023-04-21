使用Dockerfile compose創建image
sudo docker-compose -f docker-compose.yaml create
sudo docker-compose -f docker-compose.yaml start
############################################
#Docker Network not Found 網路服務有問題   #
#sudo docker-compose up -d --force-recreate#
############################################
sudo docker-compose -f docker-compose.yaml stop
sudo docker-compose -f docker-compose.yaml rm