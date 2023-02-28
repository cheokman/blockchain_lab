# BitCoint

## Download Ubuntu from

```
https://ubuntu.com/download/server
```

Install in Virtual Box

## BitCoin Installation in Ubuntu

```
apt install autoconf
apt install pkg-config
apt-get install libtool
apt-get install g++
apt install make
```

### Install Boost 1.64.0
```
 wget https://boostorg.jfrog.io/artifactory/main/release/1.64.0/source/boost_1_64_0.tar.gz
 tar zxvf boost_1_64_0.tar.gz
```

### Install libevent 2.1.8 
```
wget https://launchpad.net/ubuntu/+archive/primary/+sourcefiles/libevent/2.1.8-stable-4build1/libevent_2.1.8-stable.orig.tar.gz
tar zxvf libevent_2.1.8-stable.orig.tar.gz
libevent-2.1.8-stable/
./autogen.sh
./configure
make
make install
```

### Build Bitcoin

```
cd bitcoin
./configure --with-boost=/root/boost_1_64_0
make
```