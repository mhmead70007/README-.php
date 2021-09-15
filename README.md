
#!/usr/bin/env bash
cd $HOME/adrbvx
rm -rf $HOME/.telegram-cli
install(1729366306:AAEKmPRXxj2ubJPv0P7m0q4lmP0WblskzVA) {
apt install dnsutils
rm -rf $HOME/.telegram-cli
sudo chmod +x tg
chmod +x adrbvx
chmod +x ts
./ts
}
if [ "$1" = "ins" ]; then
install
fi
chmod +x install.sh
lua start.lua
