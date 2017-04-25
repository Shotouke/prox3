# prox3

~~~~
git clone https://github.com/iceman1001/proxmark3
cd /proxmark3
make clean && make all
./client/flasher /dev/cu.usbmodem1411 -b bootrom/obj/bootrom.elf
./client/flasher /dev/cu.usbmodem1411 armsrc/obj/fullimage.elf
cd client
./proxmark3 /dev/cu.usbmodem1411
~~~~
