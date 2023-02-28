# BitCoint

## Installation

```
yum install epel-release
yum install autoconf
yum install automake
yum install libtool
yum install gcc gcc-c++
yum-config-manager --enable rhel-server-rhscl-7-rpms
yum install devtoolset-8
scl enable devtoolset-8 bash
yum install libevent
./configure --disable-wallet
```