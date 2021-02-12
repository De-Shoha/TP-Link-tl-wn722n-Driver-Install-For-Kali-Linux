it is for TP Link TL-Wn722n

go to same directory of Istalltplinktl-wn722n.sh
open terminal
type
	chmod +x  Installtplinktl-wn722n.sh
then 
./Installtplinktl-wn722n.sh

if error occures run it again
IF Error Occures Contruct me at idoneoone@gmail.com

or do it manualy

sudo apt install bc

sudo rmmod r8188eu.ko

git clone https://github.com/aircrack-ng/rtl8188eus

sudo echo "blacklist r8188eu.ko" > "/etc/modprobe.d/realtek.conf"

cd rtl8188eus/

sudo make

sudo make install

sudo modprobe 8188eu

sudo ip link set wlan1 down

sudo iw dev wlan1 set type monitorly

