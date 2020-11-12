# CDP_Private_Cloud

### Clone Repository
```
$ https://github.com/Govind66/CDP_Private_Cloud.git
```
$ cd System_prerequisites

## Pre-requisites:
```
$ sudo yum install wget nano –y
```
```
$ sh check-pre-req.sh
```
```
$ sh disable_iptables.sh 
```
```
$ sh disable_ipv6.sh
```
```
$ sh disable_selinux.sh
```
```
$ sh disable_thp.sh
```
```
$ sh install_lzo.sh
```
```
$ sh install_nscd.sh
```
```
$ sh install_ntp.sh
```
```
$ sh install_tools.sh
```
```
$ sh remove_tuned.sh
```
```
$ sh tune_kernel.sh
```
```
$  echo 1 > /proc/sys/vm/swappiness    (temporory)
```
```
$ sudo nano /etc/sysctl.conf
```
```
$ vm.swappiness = 1
```
```
$ echo -e  'y\n'| ssh-keygen -t rsa -P "" -f $HOME/.ssh/id_rsa
    cat  ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys && ssh localhost
```
```
$ sudo yum install java-1.8.0-openjdk-devel
```
```
$ wget https://archive.cloudera.com/cm7/7.1.3/cloudera-manager-installer.bin
```
```
$ chmod +x cloudera-manager-installer.bin
```
```
$ sudo ./cloudera-manager-installer.bin
```
