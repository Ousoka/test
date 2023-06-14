# test
cmd 14_06_2023 lubuntu firewall config


To run a command as administrator (user "root"), use "sudo <command>".
See "man sudo_root" for details.

ousoka@Lubuntu1:~$ sudo -i
[sudo] password for ousoka: 
root@Lubuntu1:~# cd /etc/netplan
root@Lubuntu1:/etc/netplan# ls
01-network-manager-all.yaml
root@Lubuntu1:/etc/netplan# nano 01-network-manager-all.yaml 
root@Lubuntu1:/etc/netplan# nano 01-network-manager-all.yaml 
root@Lubuntu1:/etc/netplan# ifconfig
Command 'ifconfig' not found, but can be installed with:
apt install net-tools
root@Lubuntu1:/etc/netplan# apt install net-tools
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following NEW packages will be installed
  net-tools
0 to upgrade, 1 to newly install, 0 to remove and 0 not to upgrade.
Need to get 204 kB of archives.
After this operation, 819 kB of additional disk space will be used.
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Err:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
  Temporary failure resolving ‘archive.ubuntu.com’
E: Failed to fetch http://archive.ubuntu.com/ubuntu/pool/main/n/net-tools/net-tools_1.60%2bgit20181103.0eebece-1ubuntu5_amd64.deb  Temporary failure resolving ‘archive.ubuntu.com’
E: Unable to fetch some archives, maybe run apt-get update or try with --fix-missing?
root@Lubuntu1:/etc/netplan# ifconfig
Command 'ifconfig' not found, but can be installed with:
apt install net-tools
root@Lubuntu1:/etc/netplan# apt install net-tools
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following NEW packages will be installed
  net-tools
0 to upgrade, 1 to newly install, 0 to remove and 0 not to upgrade.
Need to get 204 kB of archives.
After this operation, 819 kB of additional disk space will be used.
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Err:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
  Temporary failure resolving ‘archive.ubuntu.com’
E: Failed to fetch http://archive.ubuntu.com/ubuntu/pool/main/n/net-tools/net-tools_1.60%2bgit20181103.0eebece-1ubuntu5_amd64.deb  Temporary failure resolving ‘archive.ubuntu.com’
E: Unable to fetch some archives, maybe run apt-get update or try with --fix-missing?
root@Lubuntu1:/etc/netplan# apt get-update
E: Invalid operation get-update
root@Lubuntu1:/etc/netplan# apt update
Ign:1 http://archive.ubuntu.com/ubuntu jammy InRelease
Ign:2 http://archive.ubuntu.com/ubuntu jammy-updates InRelease
Ign:3 http://archive.ubuntu.com/ubuntu jammy-backports InRelease
Ign:4 http://security.ubuntu.com/ubuntu jammy-security InRelease
Ign:4 http://security.ubuntu.com/ubuntu jammy-security InRelease
Ign:1 http://archive.ubuntu.com/ubuntu jammy InRelease
Ign:2 http://archive.ubuntu.com/ubuntu jammy-updates InRelease
Ign:3 http://archive.ubuntu.com/ubuntu jammy-backports InRelease
Ign:1 http://archive.ubuntu.com/ubuntu jammy InRelease
Ign:4 http://security.ubuntu.com/ubuntu jammy-security InRelease
Ign:2 http://archive.ubuntu.com/ubuntu jammy-updates InRelease
Ign:3 http://archive.ubuntu.com/ubuntu jammy-backports InRelease
Err:1 http://archive.ubuntu.com/ubuntu jammy InRelease
  Temporary failure resolving ‘archive.ubuntu.com’
Err:2 http://archive.ubuntu.com/ubuntu jammy-updates InRelease
  Temporary failure resolving ‘archive.ubuntu.com’
Err:4 http://security.ubuntu.com/ubuntu jammy-security InRelease
  Temporary failure resolving ‘security.ubuntu.com’
Err:3 http://archive.ubuntu.com/ubuntu jammy-backports InRelease
  Temporary failure resolving ‘archive.ubuntu.com’
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
All packages are up-to-date.
W: Failed to fetch http://archive.ubuntu.com/ubuntu/dists/jammy/InRelease  Temporary failure resolving ‘archive.ubuntu.com’
W: Failed to fetch http://archive.ubuntu.com/ubuntu/dists/jammy-updates/InRelease  Temporary failure resolving ‘archive.ubuntu.com’
W: Failed to fetch http://security.ubuntu.com/ubuntu/dists/jammy-security/InRelease  Temporary failure resolving ‘security.ubuntu.com’
W: Failed to fetch http://archive.ubuntu.com/ubuntu/dists/jammy-backports/InRelease  Temporary failure resolving ‘archive.ubuntu.com’
W: Some index files failed to download. They have been ignored, or old ones used instead.
root@Lubuntu1:/etc/netplan# apt ugrade
E: Invalid operation ugrade
root@Lubuntu1:/etc/netplan# apt upgrade
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Calculating upgrade... Done
0 to upgrade, 0 to newly install, 0 to remove and 0 not to upgrade.
root@Lubuntu1:/etc/netplan# apt install net-tools
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following NEW packages will be installed
  net-tools
0 to upgrade, 1 to newly install, 0 to remove and 0 not to upgrade.
Need to get 204 kB of archives.
After this operation, 819 kB of additional disk space will be used.
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Err:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
  Temporary failure resolving ‘archive.ubuntu.com’
E: Failed to fetch http://archive.ubuntu.com/ubuntu/pool/main/n/net-tools/net-tools_1.60%2bgit20181103.0eebece-1ubuntu5_amd64.deb  Temporary failure resolving ‘archive.ubuntu.com’
E: Unable to fetch some archives, maybe run apt-get update or try with --fix-missing?
root@Lubuntu1:/etc/netplan# apt get- upgrade
E: Invalid operation get-
root@Lubuntu1:/etc/netplan# apt get-upgrade
E: Invalid operation get-upgrade
root@Lubuntu1:/etc/netplan# apt-get upgrade
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
Calculating upgrade... Done
0 to upgrade, 0 to newly install, 0 to remove and 0 not to upgrade.
root@Lubuntu1:/etc/netplan# apt-get update
Ign:1 http://security.ubuntu.com/ubuntu jammy-security InRelease
Ign:2 http://archive.ubuntu.com/ubuntu jammy InRelease
Ign:3 http://archive.ubuntu.com/ubuntu jammy-updates InRelease
Ign:4 http://archive.ubuntu.com/ubuntu jammy-backports InRelease
Ign:1 http://security.ubuntu.com/ubuntu jammy-security InRelease
Ign:2 http://archive.ubuntu.com/ubuntu jammy InRelease
Ign:3 http://archive.ubuntu.com/ubuntu jammy-updates InRelease
Ign:4 http://archive.ubuntu.com/ubuntu jammy-backports InRelease
Ign:1 http://security.ubuntu.com/ubuntu jammy-security InRelease
Ign:2 http://archive.ubuntu.com/ubuntu jammy InRelease
Ign:3 http://archive.ubuntu.com/ubuntu jammy-updates InRelease
Ign:4 http://archive.ubuntu.com/ubuntu jammy-backports InRelease
Err:1 http://security.ubuntu.com/ubuntu jammy-security InRelease
  Temporary failure resolving ‘security.ubuntu.com’
Err:2 http://archive.ubuntu.com/ubuntu jammy InRelease
  Temporary failure resolving ‘archive.ubuntu.com’
Err:3 http://archive.ubuntu.com/ubuntu jammy-updates InRelease
  Temporary failure resolving ‘archive.ubuntu.com’
Err:4 http://archive.ubuntu.com/ubuntu jammy-backports InRelease
  Temporary failure resolving ‘archive.ubuntu.com’
Reading package lists... Done
W: Failed to fetch http://archive.ubuntu.com/ubuntu/dists/jammy/InRelease  Temporary failure resolving ‘archive.ubuntu.com’
W: Failed to fetch http://archive.ubuntu.com/ubuntu/dists/jammy-updates/InRelease  Temporary failure resolving ‘archive.ubuntu.com’
W: Failed to fetch http://security.ubuntu.com/ubuntu/dists/jammy-security/InRelease  Temporary failure resolving ‘security.ubuntu.com’
W: Failed to fetch http://archive.ubuntu.com/ubuntu/dists/jammy-backports/InRelease  Temporary failure resolving ‘archive.ubuntu.com’
W: Some index files failed to download. They have been ignored, or old ones used instead.
root@Lubuntu1:/etc/netplan# apt-get install net-tools
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following NEW packages will be installed
  net-tools
0 to upgrade, 1 to newly install, 0 to remove and 0 not to upgrade.
Need to get 204 kB of archives.
After this operation, 819 kB of additional disk space will be used.
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Err:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
  Temporary failure resolving ‘archive.ubuntu.com’
E: Failed to fetch http://archive.ubuntu.com/ubuntu/pool/main/n/net-tools/net-tools_1.60%2bgit20181103.0eebece-1ubuntu5_amd64.deb  Temporary failure resolving ‘archive.ubuntu.com’
E: Unable to fetch some archives, maybe run apt-get update or try with --fix-missing?
root@Lubuntu1:/etc/netplan# 

root@Lubuntu1:/etc/netplan# apt-get install net-tools
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following NEW packages will be installed
  net-tools
0 to upgrade, 1 to newly install, 0 to remove and 0 not to upgrade.
Need to get 204 kB of archives.
After this operation, 819 kB of additional disk space will be used.
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Ign:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
Err:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5
  Temporary failure resolving ‘archive.ubuntu.com’
E: Failed to fetch http://archive.ubuntu.com/ubuntu/pool/main/n/net-tools/net-tools_1.60%2bgit20181103.0eebece-1ubuntu5_amd64.deb  Temporary failure resolving ‘archive.ubuntu.com’
E: Unable to fetch some archives, maybe run apt-get update or try with --fix-missing?
root@Lubuntu1:/etc/netplan# apt-get update
Hit:1 http://archive.ubuntu.com/ubuntu jammy InRelease
Get:2 http://archive.ubuntu.com/ubuntu jammy-updates InRelease [119 kB]
Get:3 http://security.ubuntu.com/ubuntu jammy-security InRelease [110 kB]
Get:4 http://archive.ubuntu.com/ubuntu jammy-backports InRelease [108 kB]
Get:5 http://archive.ubuntu.com/ubuntu jammy/main i386 Packages [1040 kB]
Get:6 http://archive.ubuntu.com/ubuntu jammy/main Translation-en_GB [483 kB]
Get:7 http://archive.ubuntu.com/ubuntu jammy/restricted i386 Packages [30,4 kB]
Get:8 http://archive.ubuntu.com/ubuntu jammy/restricted Translation-en_GB [5768 B]
Get:9 http://archive.ubuntu.com/ubuntu jammy/universe i386 Packages [7474 kB]
Get:10 http://archive.ubuntu.com/ubuntu jammy/universe Translation-en_GB [838 kB]
Get:11 http://archive.ubuntu.com/ubuntu jammy/multiverse i386 Packages [112 kB]
Get:12 http://archive.ubuntu.com/ubuntu jammy/multiverse Translation-en_GB [102 kB]
Get:13 http://archive.ubuntu.com/ubuntu jammy-updates/main i386 Packages [419 kB]
Get:14 http://security.ubuntu.com/ubuntu jammy-security/main i386 Packages [235 kB]
Get:15 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 Packages [676 kB]
Get:16 http://archive.ubuntu.com/ubuntu jammy-updates/main Translation-en [183 kB]
Get:17 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 DEP-11 Metadata [99,8 kB]
Get:18 http://archive.ubuntu.com/ubuntu jammy-updates/main DEP-11 48x48 Icons [33,0 kB]
Get:19 http://archive.ubuntu.com/ubuntu jammy-updates/main DEP-11 64x64 Icons [51,3 kB]
Get:20 http://archive.ubuntu.com/ubuntu jammy-updates/main DEP-11 128x128 Icons [109 kB]
Get:21 http://archive.ubuntu.com/ubuntu jammy-updates/main amd64 c-n-f Metadata [15,1 kB]
Get:22 http://archive.ubuntu.com/ubuntu jammy-updates/restricted amd64 Packages [350 kB]
Get:23 http://archive.ubuntu.com/ubuntu jammy-updates/restricted i386 Packages [28,3 kB]
Get:24 http://archive.ubuntu.com/ubuntu jammy-updates/restricted Translation-en [52,8 kB]
Get:25 http://archive.ubuntu.com/ubuntu jammy-updates/restricted amd64 c-n-f Metadata [604 B]
Get:26 http://archive.ubuntu.com/ubuntu jammy-updates/universe i386 Packages [623 kB]
Get:27 http://security.ubuntu.com/ubuntu jammy-security/main amd64 Packages [457 kB]
Get:28 http://archive.ubuntu.com/ubuntu jammy-updates/universe amd64 Packages [921 kB]
Get:29 http://archive.ubuntu.com/ubuntu jammy-updates/universe Translation-en [194 kB]
Get:30 http://archive.ubuntu.com/ubuntu jammy-updates/universe amd64 DEP-11 Metadata [274 kB]
Get:31 http://archive.ubuntu.com/ubuntu jammy-updates/universe DEP-11 48x48 Icons [185 kB]
Get:32 http://archive.ubuntu.com/ubuntu jammy-updates/universe DEP-11 64x64 Icons [284 kB]
Get:33 http://archive.ubuntu.com/ubuntu jammy-updates/universe DEP-11 128x128 Icons [643 kB]
Get:34 http://security.ubuntu.com/ubuntu jammy-security/main Translation-en [123 kB]
Get:35 http://archive.ubuntu.com/ubuntu jammy-updates/universe amd64 c-n-f Metadata [20,0 kB]
Get:36 http://archive.ubuntu.com/ubuntu jammy-updates/multiverse i386 Packages [3884 B]
Get:37 http://archive.ubuntu.com/ubuntu jammy-updates/multiverse amd64 Packages [35,3 kB]
Get:38 http://security.ubuntu.com/ubuntu jammy-security/main amd64 DEP-11 Metadata [41,5 kB]
Get:39 http://archive.ubuntu.com/ubuntu jammy-updates/multiverse Translation-en [8452 B]
Get:40 http://archive.ubuntu.com/ubuntu jammy-updates/multiverse amd64 DEP-11 Metadata [940 B]
Get:41 http://archive.ubuntu.com/ubuntu jammy-updates/multiverse amd64 c-n-f Metadata [468 B]
Get:42 http://archive.ubuntu.com/ubuntu jammy-backports/main amd64 Packages [40,9 kB]
Get:43 http://security.ubuntu.com/ubuntu jammy-security/main DEP-11 48x48 Icons [13,8 kB]
Get:44 http://archive.ubuntu.com/ubuntu jammy-backports/main i386 Packages [33,7 kB]
Get:45 http://archive.ubuntu.com/ubuntu jammy-backports/main Translation-en [10,2 kB]
Get:46 http://archive.ubuntu.com/ubuntu jammy-backports/main amd64 DEP-11 Metadata [7976 B]
Get:47 http://archive.ubuntu.com/ubuntu jammy-backports/main DEP-11 48x48 Icons [7156 B]
Get:48 http://archive.ubuntu.com/ubuntu jammy-backports/main DEP-11 64x64 Icons [10,7 kB]
Get:49 http://archive.ubuntu.com/ubuntu jammy-backports/main DEP-11 64x64@2 Icons [29 B]
Get:50 http://security.ubuntu.com/ubuntu jammy-security/main DEP-11 64x64 Icons [22,7 kB]
Get:51 http://archive.ubuntu.com/ubuntu jammy-backports/main DEP-11 128x128 Icons [24,2 kB]
Get:52 http://security.ubuntu.com/ubuntu jammy-security/main DEP-11 128x128 Icons [50,2 kB]
Get:53 http://archive.ubuntu.com/ubuntu jammy-backports/main amd64 c-n-f Metadata [388 B]
Get:54 http://archive.ubuntu.com/ubuntu jammy-backports/restricted amd64 c-n-f Metadata [116 B]
Get:55 http://archive.ubuntu.com/ubuntu jammy-backports/universe i386 Packages [13,9 kB]
Get:56 http://archive.ubuntu.com/ubuntu jammy-backports/universe amd64 Packages [23,4 kB]
Get:57 http://archive.ubuntu.com/ubuntu jammy-backports/universe Translation-en [15,0 kB]
Get:58 http://security.ubuntu.com/ubuntu jammy-security/main amd64 c-n-f Metadata [10,2 kB]
Get:59 http://archive.ubuntu.com/ubuntu jammy-backports/universe amd64 DEP-11 Metadata [16,9 kB]
Get:60 http://archive.ubuntu.com/ubuntu jammy-backports/universe DEP-11 48x48 Icons [13,3 kB]
Get:61 http://archive.ubuntu.com/ubuntu jammy-backports/universe DEP-11 64x64 Icons [22,2 kB]
Get:62 http://archive.ubuntu.com/ubuntu jammy-backports/universe DEP-11 64x64@2 Icons [29 B]
Get:63 http://archive.ubuntu.com/ubuntu jammy-backports/universe DEP-11 128x128 Icons [43,5 kB]
Get:64 http://security.ubuntu.com/ubuntu jammy-security/restricted i386 Packages [28,0 kB]
Get:65 http://archive.ubuntu.com/ubuntu jammy-backports/universe amd64 c-n-f Metadata [548 B]
Get:66 http://archive.ubuntu.com/ubuntu jammy-backports/multiverse amd64 c-n-f Metadata [116 B]
Get:67 http://security.ubuntu.com/ubuntu jammy-security/restricted amd64 Packages [349 kB]
Get:68 http://security.ubuntu.com/ubuntu jammy-security/restricted Translation-en [52,6 kB]
Get:69 http://security.ubuntu.com/ubuntu jammy-security/restricted amd64 c-n-f Metadata [604 B]
Get:70 http://security.ubuntu.com/ubuntu jammy-security/universe amd64 Packages [735 kB]
Get:71 http://security.ubuntu.com/ubuntu jammy-security/universe i386 Packages [534 kB]
Get:72 http://security.ubuntu.com/ubuntu jammy-security/universe Translation-en [130 kB]
Get:73 http://security.ubuntu.com/ubuntu jammy-security/universe amd64 DEP-11 Metadata [21,9 kB]
Get:74 http://security.ubuntu.com/ubuntu jammy-security/universe DEP-11 48x48 Icons [19,7 kB]
Get:75 http://security.ubuntu.com/ubuntu jammy-security/universe DEP-11 64x64 Icons [31,7 kB]
Get:76 http://security.ubuntu.com/ubuntu jammy-security/universe DEP-11 128x128 Icons [61,4 kB]
Get:77 http://security.ubuntu.com/ubuntu jammy-security/universe amd64 c-n-f Metadata [15,6 kB]
Get:78 http://security.ubuntu.com/ubuntu jammy-security/multiverse i386 Packages [1028 B]
Get:79 http://security.ubuntu.com/ubuntu jammy-security/multiverse amd64 Packages [30,2 kB]
Get:80 http://security.ubuntu.com/ubuntu jammy-security/multiverse Translation-en [5828 B]
Get:81 http://security.ubuntu.com/ubuntu jammy-security/multiverse amd64 c-n-f Metadata [252 B]
Fetched 18,9 MB in 10s (1840 kB/s)                                          
Reading package lists... Done
root@Lubuntu1:/etc/netplan# 
























root@Lubuntu1:/etc/netplan# 
























root@Lubuntu1:/etc/netplan# apt-get install net-tools
Reading package lists... Done
Building dependency tree... Done
Reading state information... Done
The following NEW packages will be installed
  net-tools
0 to upgrade, 1 to newly install, 0 to remove and 205 not to upgrade.
Need to get 204 kB of archives.
After this operation, 819 kB of additional disk space will be used.
Get:1 http://archive.ubuntu.com/ubuntu jammy/main amd64 net-tools amd64 1.60+git20181103.0eebece-1ubuntu5 [204 kB]
Fetched 204 kB in 1s (333 kB/s)   
Selecting previously unselected package net-tools.
(Reading database ... 252686 files and directories currently installed.)
Preparing to unpack .../net-tools_1.60+git20181103.0eebece-1ubuntu5_amd64.deb ...
Unpacking net-tools (1.60+git20181103.0eebece-1ubuntu5) ...
Setting up net-tools (1.60+git20181103.0eebece-1ubuntu5) ...
Processing triggers for man-db (2.10.2-1) ...
root@Lubuntu1:/etc/netplan# ifconfig
enp0s3: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet6 fe80::23c4:bd74:801f:5279  prefixlen 64  scopeid 0x20<link>
        ether 08:00:27:73:fa:40  txqueuelen 1000  (Ethernet)
        RX packets 86  bytes 19583 (19.5 KB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 498  bytes 80161 (80.1 KB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

enp0s8: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet6 fe80::512c:2051:d732:e234  prefixlen 64  scopeid 0x20<link>
        ether 08:00:27:df:f6:d6  txqueuelen 1000  (Ethernet)
        RX packets 71  bytes 17227 (17.2 KB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 489  bytes 78845 (78.8 KB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

enp0s9: flags=4163<UP,BROADCAST,RUNNING,MULTICAST>  mtu 1500
        inet 10.162.125.147  netmask 255.255.240.0  broadcast 10.162.127.255
        inet6 fe80::3f36:1f8:46e8:5086  prefixlen 64  scopeid 0x20<link>
        ether 08:00:27:de:78:3c  txqueuelen 1000  (Ethernet)
        RX packets 22688  bytes 28345773 (28.3 MB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 7737  bytes 964511 (964.5 KB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

lo: flags=73<UP,LOOPBACK,RUNNING>  mtu 65536
        inet 127.0.0.1  netmask 255.0.0.0
        inet6 ::1  prefixlen 128  scopeid 0x10<host>
        loop  txqueuelen 1000  (Local Loopback)
        RX packets 17253  bytes 1287588 (1.2 MB)
        RX errors 0  dropped 0  overruns 0  frame 0
        TX packets 17253  bytes 1287588 (1.2 MB)
        TX errors 0  dropped 0 overruns 0  carrier 0  collisions 0

root@Lubuntu1:/etc/netplan# cd /etc/
root@Lubuntu1:/etc# ls
acpi                           hp                   profile.d
adduser.conf                   ifplugd              protocols
adjtime                        ImageMagick-6        pulse
alsa                           init                 python3
alternatives                   init.d               python3.10
anacrontab                     initramfs-tools      rc0.d
apm                            inputrc              rc1.d
apparmor                       ipp-usb              rc2.d
apparmor.d                     iproute2             rc3.d
apport                         issue                rc4.d
appstream.conf                 issue.net            rc5.d
apt                            kernel               rc6.d
avahi                          kernel-img.conf      rcS.d
bash.bashrc                    kerneloops.conf      request-key.conf
bash_completion                keyutils             request-key.d
bash_completion.d              ldap                 resolv.conf
bindresvport.blacklist         ld.so.cache          rmt
binfmt.d                       ld.so.conf           rpc
bluetooth                      ld.so.conf.d         rsyslog.conf
ca-certificates                legal                rsyslog.d
ca-certificates.conf           libaudit.conf        sane.d
ca-certificates.conf.dpkg-old  libblockdev          sddm
chatscripts                    libnl-3              sddm.conf
console-setup                  libpaper.d           security
cracklib                       libreoffice          selinux
cron.d                         locale.alias         sensors3.conf
cron.daily                     locale.conf          sensors.d
cron.hourly                    locale.gen           services
cron.monthly                   localtime            shadow
crontab                        logcheck             shadow-
cron.weekly                    login.defs           shells
cryptsetup-initramfs           logrotate.conf       skel
crypttab                       logrotate.d          snmp
cups                           lsb-release          ssh
cupshelpers                    lvm                  ssl
dbus-1                         machine-id           subgid
dconf                          magic                subgid-
debconf.conf                   magic.mime           subuid
debian_version                 mailcap              subuid-
default                        mailcap.order        sudo.conf
deluser.conf                   manpath.config       sudoers
depmod.d                       menu-methods         sudoers.d
dhcp                           mime.types           sudo_logsrvd.conf
dictionaries-common            mke2fs.conf          sysctl.conf
dpkg                           ModemManager         sysctl.d
e2scrub.conf                   modprobe.d           systemd
emacs                          modules              terminfo
environment                    modules-load.d       thermald
environment.d                  mtab                 timezone
ethertypes                     nanorc               tmpfiles.d
fonts                          netconfig            ubuntu-advantage
fstab                          netplan              ucf.conf
fuse.conf                      network              udev
fwupd                          networkd-dispatcher  udisks2
gai.conf                       NetworkManager       ufw
gamin                          networks             uniconf.conf
geoclue                        newt                 update-manager
ghostscript                    nftables.conf        update-motd.d
glvnd                          nsswitch.conf        update-notifier
gnome                          opt                  UPower
groff                          os-release           usb_modeswitch.conf
group                          PackageKit           usb_modeswitch.d
group-                         pam.conf             vconsole.conf
grub.d                         pam.d                vdpau_wrapper.cfg
gshadow                        papersize            vim
gshadow-                       passwd               vtrgb
gss                            passwd-              vulkan
gtk-2.0                        pcmcia               w3m
gtk-3.0                        perl                 wgetrc
hdparm.conf                    pki                  wpa_supplicant
host.conf                      pm                   wvdial.conf
hostname                       pnm2ppa.conf         X11
hosts                          polkit-1             xattr.conf
hosts.allow                    ppp                  xdg
hosts.deny                     profile              zsh_command_not_found
root@Lubuntu1:/etc# nano sysctl.conf
root@Lubuntu1:/etc# cd ..
root@Lubuntu1:/# sysctl -p /etc/sysctl.conf
net.ipv4.ip_forward = 1
root@Lubuntu1:/# 
