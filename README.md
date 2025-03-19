you can download the new version of PocketMine using this link 

update the system and download the necessary packages.
sudo apt update && sudo apt upgrade -y
sudo apt install curl tar unzip git screen -y

installing PHP

sudo apt install software-properties-common -y
sudo add-apt-repository ppa:ondrej/php -y
sudo apt update
sudo apt install php8.2 php8.2-curl php8.2-mbstring php8.2-xml php8.2-zip -y

go to your home directory

CD

download pocketmine

curl -sL https://get.pmmp.io | bash -s - -r

start the server

./start.sh

turn on the setup wizard by pressing Y (optional)
choose the desired language
there will be easy questions that you will definitely answer.
after that, the server will start.
to turn off the server, press Ctrl+c to turn it on, enter ./start.sh
