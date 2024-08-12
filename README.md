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

### Screenshots 
Here are screenshots of installing Java on debian and termux
<p align="center">
<img width="99.9%" src="https://raw.githubusercontent.com/mishakorzik/easy-java/main/Screenshot_2024-08-12-16-27-52-544_com.termux-edit.jpg"/>
  
<img width="99.9%" src="https://raw.githubusercontent.com/mishakorzik/easy-java/main/Screenshot_2024-08-12-16-41-13-938_com.termux-edit.jpg"/>

To update Java, you just need to run the installation of the version of Java that you installed last time.




