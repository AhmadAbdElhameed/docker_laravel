## rebuild using image cache if any change happened it will affect (if you change in image configuration)
docker-compose up -d --build server  

## run artisan command
sudo docker-compose run  --rm artisan migrate   
