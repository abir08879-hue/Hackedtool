pkg update && pkg upgrade -y
pkg install git net-tools -y
git clone https://github.com/abir08879-hue/hacked-checker
cd hacked-checker
chmod +x hacked.sh
./hacked.sh
