# dockertraining_hansy_solis
#Created image through publish option in visual studio with dockerhub
docker run --name site1 -p 8085:80 dockertraining2020/dockertraininghansysolis
docker run --name site2 -p 8086:80 -e "AppSettings:StoreName"="Plano" dockertraining2020/dockertraininghansysolis
