## easy-java
You can easily install the full version of Java or even multiple versions of Java and work with them at the same time, each with a different version installed. It is only supported on arm64 and Linux systems such as: debian, ubuntu and termux.

### Tool tested on
this tool has been tested on arm64 systems such as:

<a href="https://github.com/mishakorzik"><img title="Termux" src="https://img.shields.io/badge/Tested on-Raspberry_pi-blue?style=for-the-badge&logo=github"></a>
<a href="https://github.com/mishakorzik"><img title="Termux" src="https://img.shields.io/badge/Tested on-Termux-blue?style=for-the-badge&logo=github"></a>

### How to Install

```
apt install wget
wget https://raw.githubusercontent.com/mishakorzik/easy-java/main/easy-java
chmod +x easy-java
./easy-java
```

### How to Uninstall

```
# if you're using debian or ubuntu
cd /usr/local
sudo rm -rf jdk-*

# if you're using termux
cd $PREFIX/..
rm -rf java

```
