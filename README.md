pkg update && pkg upgrade -y
pkg install git net-tools -y
git clone https://github.com/TOMAR_USERNAME/hacked-checker.git
cd hacked-checker
chmod +x hacked.sh
./hacked.sh
