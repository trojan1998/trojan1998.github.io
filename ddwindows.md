linux转windows
KVM架构才可以，openvz架构不适用

1.先运行以下代码

Debian/Ubuntu:
apt-get update

安装运行库

Debian/Ubuntu:
apt-get install -y xz-utils openssl gawk file

apt-get install wget

2.代码安装格式，最后两个代码二选一即可

wget --no-check-certificate -qO InstallNET.sh 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh' && bash InstallNET.sh -dd 'Windows的软件包'

（注意：不适用于新出的ARM框架机型）

DD Windows Server 2012 R2 64位 精简版 [账户Administrator密码nat.ee]
wget --no-check-certificate -qO InstallNET.sh 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh' && bash InstallNET.sh -dd 'https://oss.sunpma.com/Windows/Oracle_Win_Server2012R2_64_Administrator_nat.ee.gz'

内存为1G，所以推荐使用下面的win7企业版

DD Windows7 sp1 64位 企业精简版 [账户Administrator密码nat.ee]
wget --no-check-certificate -qO InstallNET.sh 'https://moeclub.org/attachment/LinuxShell/InstallNET.sh' && bash InstallNET.sh -dd 'https://oss.sunpma.com/Windows/Oracle_Win7_sp1_64_Administrator_nat.ee.gz'