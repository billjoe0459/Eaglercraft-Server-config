first run 
sudo apt-get update

then run
sudo apt-get install apache2 -y && cd Eaglercraft-Server-config-main && sudo mv minecraft.html /var/www/html/ && sudo service apache2 restart && sudo chmod +x run.sh && ./run.sh
