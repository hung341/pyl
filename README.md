pkg update

pkg upgrade -y

termux-setup-storage

pkg install clang -y

pkg install python -y

pkg install nodejs -y

pkg install openssh -y

pkg install nano -y

pkg install git -y

pkg install tur-repo -y

pkg install code-server -y

passwd

whoami

ifconfig

sshd

clang --version

python --version

node --version
ifconfig wlan0 | grep inet

netstat -tulnp | grep 8022
