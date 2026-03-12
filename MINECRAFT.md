sudo apt update && sudo apt install apache2 

mv minecraft.html /var/www/html/ && sudo service apache2 reload

sudo chmod +x run.sh && ./run.sh
