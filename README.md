# praNk via termux
pkg update
pkg upgrade
pkg install git
pkg install curl
git clone https://github.com/InexBots/praNk
cd troll_project
chmod +x *
termux-fix-shebang troll.sh
./troll.sh


#praNk via vps
apt update
apt upgrade
apt install git
apt instll curl
git clone https://github.com/InexBots/praNk
cd troll_project
chmod +x *
./troll.sh
