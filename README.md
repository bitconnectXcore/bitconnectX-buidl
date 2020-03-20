# bitconnectX-buidl

**Compile An Open-Source BlockChain Crypto-Currency For Linux, ~~Windows Or Mac~~.**

**Changes From The Original:** [List](https://github.com/bitconnectXcore/bitconnectX-Genesis/commits/master "List") **|** [Log](https://github.com/bitconnectXcore/bitconnectX-Genesis#change-log "Log")

**The Original bitconnectX Release:** [bitconnectX](https://github.com/bitconnectCoin/bitconnectX "bitconnectX")

**Original Build Documents:** [QT](https://github.com/bitconnectCoin/bitconnectX/blob/master/doc/readme-qt.rst "QT") **|** [Unix](https://github.com/bitconnectCoin/bitconnectX/blob/master/doc/build-unix.txt "Unix") **|** [Windows](https://github.com/bitconnectCoin/bitconnectX/blob/master/doc/build-msw.txt "Windows") **|** [Mac](https://github.com/bitconnectCoin/bitconnectX/blob/master/doc/build-osx.txt "Mac")

#

### Operating System Images

**Windows 10 ISO -** https://www.microsoft.com/en-gb/software-download/windows10

**Ubuntu ISO -** https://ubuntu.com/download

#

### Key Apps

**VirtualBox**

https://www.virtualbox.org **|** Ubuntu Software Centre

**QT Creator**

https://www.qt.io/download-open-source **|** https://wiki.qt.io/Install_Qt_5_on_Ubuntu **|** Ubuntu Software Centre App

**GitHub Desktop**

https://github.com/desktop **|** https://desktop.github.com **|** Ubuntu Software Centre App

**ATOM**

https://github.com/atom **|** https://github.com/atom **|** Ubuntu Software Centre App

**Visual Studio 2019 Community**

https://visualstudio.microsoft.com/downloads/

#

### Key Folders

Compiling the daemon (bitconnectxd) on Linux is done directly within this folder *(src)* - https://github.com/bitconnectXcore/bitconnectX-Genesis/tree/master/src | **/bitconnectX-Genesis/src**

Compiling the wallet (bitconnectx-qt) on Linux is done directly within this folder *(bitconnectX-Genesis)* - https://github.com/bitconnectXcore/bitconnectX-Genesis/ **/bitconnectX-Genesis/**

Building the LevelDB files on Linux is done directly within this folder *(leveldb)* - https://github.com/bitconnectXcore/bitconnectX-Genesis/tree/master/src/leveldb **/bitconnectX-Genesis/src/leveldb**

#

### Key Files



#

### Linux Terminal And QT Notes / Examples

git clone https://github.com/bitconnectXcore-bitconnectX-Genesis

cd bitconnectx-genesis/src

make -f makefile.unix

make -f makefile.unix USE_UPNP=1 USE_IPV6=1

strip bitconnectxd

chmod +x bitconnectd

chmod +x bitconnectx-qt

./bitconnectxd -daemon

./bitconnectx-qt

qmake

make

sudo apt install libboost-all-dev

CONFIG += static

QMAKE_LFLAGS += -no-pie

QMAKE_LFLAGS += -static

QMAKE_CXXFLAGS += -static 

chmod +x build_detect_platform

make clean

make libleveldb.a libmemenv.a

...

*(QR Codes Not Implemented - USE_QRCODE=1)*

---

## Unix | Linux

**Ubuntu 14**

**Ubuntu 16**

**Ubuntu 18**

**Ubuntu 19**

**Ubuntu Server 18**

**Ubuntu Server 19**

---

**Resources**
