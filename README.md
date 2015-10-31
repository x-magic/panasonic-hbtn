# panasonic-hbtn
Panasonic CF-18/19 (Toughbook) Tablet Button driver for Linux

## Usage
```bash
cd /usr/local/src/
git clone https://github.com/x-magic/panasonic-hbtn.git

cd panasonic-hbtn
make all
make install

depmod -a
modprobe panasonic-hbtn
```
Then try out if those buttons are in working order. 

Tested with CF-19C MK1 with Ubuntu 15.10 i386 desktop. 
