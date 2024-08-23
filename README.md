# My-first-Repository-by-Git-Hub
analyst@6af7d8e8f017:~$ mkdir apt 
analyst@6af7d8e8f017:~$ sudo install suricata 
install: missing destination file operand after 'suricata'
Try 'install --help' for more information.
analyst@6af7d8e8f017:~$ 
analyst@6af7d8e8f017:~$ KYes
-bash: KYes: command not found
analyst@6af7d8e8f017:~$ YEs
-bash: YEs: command not found
analyst@6af7d8e8f017:~$ Yes
-bash: Yes: command not found
analyst@6af7d8e8f017:~$ suricata
-bash: suricata: command not found
analyst@6af7d8e8f017:~$ sudo apt remove suricata 
Reading package lists... Done
Building dependency tree       
Reading state information... Done
Package 'suricata' is not installed, so not removed
0 upgraded, 0 newly installed, 0 to remove and 59 not upgraded.
analyst@6af7d8e8f017:~$ 
analyst@6af7d8e8f017:~$ Yes
-bash: Yes: command not found
analyst@6af7d8e8f017:~$ suricata
-bash: suricata: command not found
analyst@6af7d8e8f017:~$ sudo apt install tcpdump
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following additional packages will be installed:
  libpcap0.8
Suggested packages:
  apparmor
The following NEW packages will be installed:
  libpcap0.8 tcpdump
0 upgraded, 2 newly installed, 0 to remove and 59 not upgraded.
Need to get 540 kB of archives.
After this operation, 1475 kB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://deb.debian.org/debian buster/main amd64 libpcap0.8 amd64 1.8.1-6+deb10u1 [140 kB]
Get:2 http://deb.debian.org/debian buster/main amd64 tcpdump amd64 4.9.3-1~deb10u2 [400 kB]
Fetched 540 kB in 0s (4081 kB/s)
debconf: delaying package configuration, since apt-utils is not installed
Selecting previously unselected package libpcap0.8:amd64.
(Reading database ... 22919 files and directories currently installed.)
Preparing to unpack .../libpcap0.8_1.8.1-6+deb10u1_amd64.deb ...
Unpacking libpcap0.8:amd64 (1.8.1-6+deb10u1) ...
Selecting previously unselected package tcpdump.
Preparing to unpack .../tcpdump_4.9.3-1~deb10u2_amd64.deb ...
Unpacking tcpdump (4.9.3-1~deb10u2) ...
Setting up libpcap0.8:amd64 (1.8.1-6+deb10u1) ...
Setting up tcpdump (4.9.3-1~deb10u2) ...
Processing triggers for man-db (2.8.5-2+deb10u1) ...
Processing triggers for libc-bin (2.28-10+deb10u2) ...
analyst@6af7d8e8f017:~$ apt list --installed
Listing... Done
adduser/oldoldstable,now 3.118 all [installed,automatic]
apt/oldoldstable,oldoldstable-updates,now 1.8.2.3 amd64 [installed,automatic]
base-files/oldoldstable,now 10.3+deb10u13 amd64 [installed,automatic]
base-passwd/oldoldstable,now 3.5.46 amd64 [installed,automatic]
bash/oldoldstable,now 5.0-4 amd64 [installed,automatic]
binutils-x86-64-linux-gnu/oldoldstable,now 2.31.1-16 amd64 [installed,automatic]
binutils/oldoldstable,now 2.31.1-16 amd64 [installed,automatic]
bsdmainutils/oldoldstable,now 11.1.2+b1 amd64 [installed,automatic]
bsdutils/oldoldstable,now 1:2.33.1-0.1 amd64 [installed,upgradable to: 1:2.33.1-0.1+deb10u1]
build-essential/oldoldstable,now 12.6 amd64 [installed,automatic]
bzip2/oldoldstable,now 1.0.6-9.2~deb10u2 amd64 [installed,automatic]
ca-certificates/oldoldstable,oldoldstable-updates,now 20200601~deb10u2 all [installed,automatic]
coreutils/oldoldstable,now 8.30-3 amd64 [installed,automatic]
cpp-8/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
cpp/oldoldstable,now 4:8.3.0-1 amd64 [installed,automatic]
dash/oldoldstable,now 0.5.10.2-5 amd64 [installed,automatic]
dbus/now 1.12.24-0+deb10u1 amd64 [installed,upgradable to: 1.12.28-0+deb10u1]
debconf/oldoldstable,now 1.5.71+deb10u1 all [installed,automatic]
debian-archive-keyring/oldoldstable,now 2019.1+deb10u1 all [installed,upgradable to: 2019.1+deb10u2]
debianutils/oldoldstable,now 4.8.6.1 amd64 [installed,automatic]
dh-python/oldoldstable,now 3.20190308 all [installed,automatic]
diffutils/oldoldstable,now 1:3.7-3 amd64 [installed,automatic]
dirmngr/oldoldstable,oldoldstable,now 2.2.12-1+deb10u2 amd64 [installed,automatic]
dmsetup/oldoldstable,now 2:1.02.155-3 amd64 [installed,automatic]
dpkg-dev/oldoldstable,oldoldstable,now 1.19.8 all [installed,automatic]
dpkg/oldoldstable,oldoldstable,now 1.19.8 amd64 [installed,automatic]
e2fsprogs/oldoldstable,now 1.44.5-1+deb10u3 amd64 [installed,automatic]
fakeroot/oldoldstable,now 1.23-1 amd64 [installed,automatic]
fdisk/oldoldstable,now 2.33.1-0.1 amd64 [installed,upgradable to: 2.33.1-0.1+deb10u1]
file/oldoldstable,now 1:5.35-4+deb10u2 amd64 [installed,automatic]
findutils/oldoldstable,now 4.6.0+git+20190209-2 amd64 [installed,automatic]
g++-8/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
g++/oldoldstable,now 4:8.3.0-1 amd64 [installed,automatic]
gcc-8-base/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
gcc-8/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
gcc/oldoldstable,now 4:8.3.0-1 amd64 [installed,automatic]
gir1.2-glib-2.0/oldoldstable,now 1.58.3-2 amd64 [installed,automatic]
gnupg-l10n/oldoldstable,oldoldstable,now 2.2.12-1+deb10u2 all [installed,automatic]
gnupg-utils/oldoldstable,oldoldstable,now 2.2.12-1+deb10u2 amd64 [installed,automatic]
gnupg/oldoldstable,oldoldstable,now 2.2.12-1+deb10u2 all [installed,automatic]
gpg-agent/oldoldstable,oldoldstable,now 2.2.12-1+deb10u2 amd64 [installed,automatic]
gpg-wks-client/oldoldstable,oldoldstable,now 2.2.12-1+deb10u2 amd64 [installed,automatic]
gpg-wks-server/oldoldstable,oldoldstable,now 2.2.12-1+deb10u2 amd64 [installed,automatic]
gpg/oldoldstable,oldoldstable,now 2.2.12-1+deb10u2 amd64 [installed,automatic]
gpgconf/oldoldstable,oldoldstable,now 2.2.12-1+deb10u2 amd64 [installed,automatic]
gpgsm/oldoldstable,oldoldstable,now 2.2.12-1+deb10u2 amd64 [installed,automatic]
gpgv/oldoldstable,oldoldstable,now 2.2.12-1+deb10u2 amd64 [installed,automatic]
grep/oldoldstable,now 3.3-1 amd64 [installed,automatic]
groff-base/oldoldstable,now 1.22.4-3+deb10u1 amd64 [installed,automatic]
gzip/oldoldstable,oldoldstable,now 1.9-3+deb10u1 amd64 [installed,automatic]
hostname/oldoldstable,now 3.21 amd64 [installed,automatic]
info/oldoldstable,now 6.5.0.dfsg.1-4+b1 amd64 [installed]
init-system-helpers/oldoldstable,now 1.56+nmu1 all [installed,automatic]
install-info/oldoldstable,now 6.5.0.dfsg.1-4+b1 amd64 [installed,automatic]
iproute2/oldoldstable,now 4.20.0-2+deb10u1 amd64 [installed]
iputils-ping/oldoldstable,now 3:20180629-2+deb10u2 amd64 [installed]
krb5-locales/now 1.17-3+deb10u5 all [installed,upgradable to: 1.17-3+deb10u6]
libacl1/oldoldstable,now 2.2.53-4 amd64 [installed,automatic]
libalgorithm-diff-perl/oldoldstable,now 1.19.03-2 all [installed,automatic]
libalgorithm-diff-xs-perl/oldoldstable,now 0.04-5+b1 amd64 [installed,automatic]
libalgorithm-merge-perl/oldoldstable,now 0.08-3 all [installed,automatic]
libapparmor1/oldoldstable,now 2.13.2-10 amd64 [installed,automatic]
libapt-pkg5.0/oldoldstable,oldoldstable-updates,now 1.8.2.3 amd64 [installed,automatic]
libargon2-1/oldoldstable,now 0~20171227-0.2 amd64 [installed,automatic]
libasan5/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
libassuan0/oldoldstable,now 2.5.2-1 amd64 [installed,automatic]
libatomic1/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
libattr1/oldoldstable,now 1:2.4.48-4 amd64 [installed,automatic]
libaudit-common/oldoldstable,now 1:2.8.4-3 all [installed,automatic]
libaudit1/oldoldstable,now 1:2.8.4-3 amd64 [installed,automatic]
libbinutils/oldoldstable,now 2.31.1-16 amd64 [installed,automatic]
libblkid1/oldoldstable,now 2.33.1-0.1 amd64 [installed,upgradable to: 2.33.1-0.1+deb10u1]
libbsd0/oldoldstable,now 0.9.1-2+deb10u1 amd64 [installed,automatic]
libbz2-1.0/oldoldstable,now 1.0.6-9.2~deb10u2 amd64 [installed,automatic]
libc-bin/now 2.28-10+deb10u2 amd64 [installed,upgradable to: 2.28-10+deb10u4]
libc-dev-bin/now 2.28-10+deb10u2 amd64 [installed,upgradable to: 2.28-10+deb10u4]
libc6-dev/now 2.28-10+deb10u2 amd64 [installed,upgradable to: 2.28-10+deb10u4]
libc6/now 2.28-10+deb10u2 amd64 [installed,upgradable to: 2.28-10+deb10u4]
libcap-ng0/oldoldstable,now 0.7.9-2 amd64 [installed,automatic]
libcap2-bin/oldoldstable,now 1:2.25-2 amd64 [installed,automatic]
libcap2/oldoldstable,now 1:2.25-2 amd64 [installed,automatic]
libcc1-0/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
libcom-err2/oldoldstable,now 1.44.5-1+deb10u3 amd64 [installed,automatic]
libcryptsetup12/oldoldstable,now 2:2.1.0-5+deb10u2 amd64 [installed,automatic]
libdb5.3/oldoldstable,now 5.3.28+dfsg1-0.5 amd64 [installed,automatic]
libdbus-1-3/now 1.12.24-0+deb10u1 amd64 [installed,upgradable to: 1.12.28-0+deb10u1]
libdebconfclient0/oldoldstable,now 0.249 amd64 [installed,automatic]
libdevmapper1.02.1/oldoldstable,now 2:1.02.155-3 amd64 [installed,automatic]
libdpkg-perl/oldoldstable,oldoldstable,now 1.19.8 all [installed,automatic]
libedit2/oldoldstable,now 3.1-20181209-1 amd64 [installed,automatic]
libelf1/oldoldstable,now 0.176-1.1 amd64 [installed,upgradable to: 0.176-1.1+deb10u1]
libexpat1-dev/now 2.2.6-2+deb10u6 amd64 [installed,upgradable to: 2.2.6-2+deb10u7]
libexpat1/now 2.2.6-2+deb10u6 amd64 [installed,upgradable to: 2.2.6-2+deb10u7]
libext2fs2/oldoldstable,now 1.44.5-1+deb10u3 amd64 [installed,automatic]
libfakeroot/oldoldstable,now 1.23-1 amd64 [installed,automatic]
libfdisk1/oldoldstable,now 2.33.1-0.1 amd64 [installed,upgradable to: 2.33.1-0.1+deb10u1]
libffi6/oldoldstable,now 3.2.1-9 amd64 [installed,automatic]
libfile-fcntllock-perl/oldoldstable,now 0.22-3+b5 amd64 [installed,automatic]
libgcc-8-dev/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
libgcc1/oldoldstable,now 1:8.3.0-6 amd64 [installed,automatic]
libgcrypt20/oldoldstable,now 1.8.4-5+deb10u1 amd64 [installed,automatic]
libgdbm-compat4/oldoldstable,now 1.18.1-4 amd64 [installed,automatic]
libgdbm6/oldoldstable,now 1.18.1-4 amd64 [installed,automatic]
libgirepository-1.0-1/oldoldstable,now 1.58.3-2 amd64 [installed,automatic]
libglib2.0-0/now 2.58.3-2+deb10u4 amd64 [installed,upgradable to: 2.58.3-2+deb10u6]
libglib2.0-data/now 2.58.3-2+deb10u4 all [installed,upgradable to: 2.58.3-2+deb10u6]
libgmp10/oldoldstable,now 2:6.1.2+dfsg-4+deb10u1 amd64 [installed,automatic]
libgpg-error0/oldoldstable,now 1.35-1 amd64 [installed,automatic]
libgpm2/oldoldstable,now 1.20.7-5 amd64 [installed,automatic]
libgssapi-krb5-2/now 1.17-3+deb10u5 amd64 [installed,upgradable to: 1.17-3+deb10u6]
libhogweed4/oldoldstable,oldoldstable,now 3.4.1-1+deb10u1 amd64 [installed,automatic]
libicu63/oldoldstable,now 63.1-6+deb10u3 amd64 [installed,automatic]
libidn11/oldoldstable,now 1.33-2.2 amd64 [installed,automatic]
libidn2-0/oldoldstable,oldoldstable,now 2.0.5-1+deb10u1 amd64 [installed,automatic]
libip4tc0/oldoldstable,now 1.8.2-4 amd64 [installed,automatic]
libisl19/oldoldstable,now 0.20-2 amd64 [installed,automatic]
libitm1/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
libjson-c3/oldoldstable,oldoldstable,now 0.12.1+ds-2+deb10u1 amd64 [installed,automatic]
libk5crypto3/now 1.17-3+deb10u5 amd64 [installed,upgradable to: 1.17-3+deb10u6]
libkeyutils1/oldoldstable,now 1.6-6 amd64 [installed,automatic]
libkmod2/oldoldstable,now 26-1 amd64 [installed,automatic]
libkrb5-3/now 1.17-3+deb10u5 amd64 [installed,upgradable to: 1.17-3+deb10u6]
libkrb5support0/now 1.17-3+deb10u5 amd64 [installed,upgradable to: 1.17-3+deb10u6]
libksba8/oldoldstable,now 1.3.5-2+deb10u2 amd64 [installed,automatic]
libldap-2.4-2/oldoldstable,oldoldstable,now 2.4.47+dfsg-3+deb10u7 amd64 [installed,automatic]
libldap-common/oldoldstable,oldoldstable,now 2.4.47+dfsg-3+deb10u7 all [installed,automatic]
liblocale-gettext-perl/oldoldstable,now 1.07-3+b4 amd64 [installed,automatic]
liblsan0/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
liblz4-1/oldoldstable,oldoldstable,now 1.8.3-1+deb10u1 amd64 [installed,automatic]
liblzma5/oldoldstable,oldoldstable,now 5.2.4-1+deb10u1 amd64 [installed,automatic]
libmagic-mgc/oldoldstable,now 1:5.35-4+deb10u2 amd64 [installed,automatic]
libmagic1/oldoldstable,now 1:5.35-4+deb10u2 amd64 [installed,automatic]
libmnl0/oldoldstable,now 1.0.4-2 amd64 [installed,automatic]
libmount1/oldoldstable,now 2.33.1-0.1 amd64 [installed,upgradable to: 2.33.1-0.1+deb10u1]
libmpc3/oldoldstable,now 1.1.0-1 amd64 [installed,automatic]
libmpdec2/oldoldstable,now 2.4.2-2 amd64 [installed,automatic]
libmpfr6/oldoldstable,now 4.0.2-1 amd64 [installed,automatic]
libmpx2/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
libncurses6/now 6.1+20181013-2+deb10u3 amd64 [installed,upgradable to: 6.1+20181013-2+deb10u5]
libncursesw6/now 6.1+20181013-2+deb10u3 amd64 [installed,upgradable to: 6.1+20181013-2+deb10u5]
libnettle6/oldoldstable,oldoldstable,now 3.4.1-1+deb10u1 amd64 [installed,automatic]
libnpth0/oldoldstable,now 1.6-1 amd64 [installed,automatic]
libnss-systemd/oldoldstable,now 241-7~deb10u8 amd64 [installed,upgradable to: 241-7~deb10u10]
libp11-kit0/oldoldstable,oldoldstable,now 0.23.15-2+deb10u1 amd64 [installed,automatic]
libpam-modules-bin/oldoldstable,now 1.3.1-5 amd64 [installed,automatic]
libpam-modules/oldoldstable,now 1.3.1-5 amd64 [installed,automatic]
libpam-runtime/oldoldstable,now 1.3.1-5 all [installed,automatic]
libpam-systemd/oldoldstable,now 241-7~deb10u8 amd64 [installed,upgradable to: 241-7~deb10u10]
libpam0g/oldoldstable,now 1.3.1-5 amd64 [installed,automatic]
libpcap0.8/oldoldstable,now 1.8.1-6+deb10u1 amd64 [installed,automatic]
libpcre2-8-0/oldoldstable,now 10.32-5 amd64 [installed,upgradable to: 10.32-5+deb10u1]
libpcre3/oldoldstable,now 2:8.39-12 amd64 [installed,automatic]
libperl5.28/oldoldstable,now 5.28.1-6+deb10u1 amd64 [installed,automatic]
libpipeline1/oldoldstable,now 1.5.1-2 amd64 [installed,automatic]
libprocps7/oldoldstable,now 2:3.3.15-2 amd64 [installed,automatic]
libpsl5/oldoldstable,now 0.20.2-2 amd64 [installed,automatic]
libpython3-dev/oldoldstable,now 3.7.3-1 amd64 [installed,automatic]
libpython3-stdlib/oldoldstable,now 3.7.3-1 amd64 [installed,automatic]

libpython3.7-dev/now 3.7.3-2+deb10u4 amd64 [installed,upgradable to: 3.7.3-2+deb10u7]
libpython3.7-minimal/now 3.7.3-2+deb10u4 amd64 [installed,upgradable to: 3.7.3-2+deb10u7]
libpython3.7-stdlib/now 3.7.3-2+deb10u4 amd64 [installed,upgradable to: 3.7.3-2+deb10u7]
libpython3.7/now 3.7.3-2+deb10u4 amd64 [installed,upgradable to: 3.7.3-2+deb10u7]
libquadmath0/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
libreadline7/oldoldstable,now 7.0-5 amd64 [installed,automatic]
libsasl2-2/oldoldstable,oldoldstable,now 2.1.27+dfsg-1+deb10u2 amd64 [installed,automatic]
libsasl2-modules-db/oldoldstable,oldoldstable,now 2.1.27+dfsg-1+deb10u2 amd64 [installed,automatic]
libsasl2-modules/oldoldstable,oldoldstable,now 2.1.27+dfsg-1+deb10u2 amd64 [installed,automatic]
libseccomp2/oldoldstable,now 2.3.3-4 amd64 [installed,automatic]
libselinux1/oldoldstable,now 2.8-1+b1 amd64 [installed,automatic]
libsemanage-common/oldoldstable,now 2.8-2 all [installed,automatic]
libsemanage1/oldoldstable,now 2.8-2 amd64 [installed,automatic]
libsepol1/oldoldstable,now 2.8-1 amd64 [installed,automatic]
libsmartcols1/oldoldstable,now 2.33.1-0.1 amd64 [installed,upgradable to: 2.33.1-0.1+deb10u1]
libsqlite3-0/oldoldstable,now 3.27.2-3+deb10u2 amd64 [installed,automatic]
libss2/oldoldstable,now 1.44.5-1+deb10u3 amd64 [installed,automatic]
libssl1.1/now 1.1.1n-0+deb10u4 amd64 [installed,upgradable to: 1.1.1n-0+deb10u6]
libstdc++-8-dev/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
libstdc++6/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
libsystemd0/oldoldstable,now 241-7~deb10u8 amd64 [installed,upgradable to: 241-7~deb10u10]
libtasn1-6/oldoldstable,now 4.13-3+deb10u1 amd64 [installed,automatic]
libtinfo6/now 6.1+20181013-2+deb10u3 amd64 [installed,upgradable to: 6.1+20181013-2+deb10u5]
libtsan0/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
libubsan1/oldoldstable,now 8.3.0-6 amd64 [installed,automatic]
libuchardet0/oldoldstable,now 0.0.6-3 amd64 [installed,automatic]
libudev1/oldoldstable,now 241-7~deb10u8 amd64 [installed,upgradable to: 241-7~deb10u10]
libunistring2/oldoldstable,now 0.9.10-1 amd64 [installed,automatic]
libuuid1/oldoldstable,now 2.33.1-0.1 amd64 [installed,upgradable to: 2.33.1-0.1+deb10u1]
libwrap0/oldoldstable,now 7.6.q-28 amd64 [installed,automatic]
libx11-6/oldoldstable,now 2:1.6.7-1+deb10u2 amd64 [installed,upgradable to: 2:1.6.7-1+deb10u4]
libx11-data/oldoldstable,now 2:1.6.7-1+deb10u2 all [installed,upgradable to: 2:1.6.7-1+deb10u4]
libxau6/oldoldstable,now 1:1.0.8-1+b2 amd64 [installed,automatic]
libxcb1/oldoldstable,now 1.13.1-2 amd64 [installed,automatic]
libxdmcp6/oldoldstable,now 1:1.1.2-3 amd64 [installed,automatic]
libxext6/oldoldstable,now 2:1.3.3-1+b2 amd64 [installed,automatic]
libxml2/now 2.9.4+dfsg1-7+deb10u5 amd64 [installed,upgradable to: 2.9.4+dfsg1-7+deb10u6]
libxmuu1/oldoldstable,now 2:1.1.2-2+b3 amd64 [installed,automatic]
libxtables12/oldoldstable,now 1.8.2-4 amd64 [installed,automatic]
libzstd1/oldoldstable,oldoldstable,now 1.3.8+dfsg-3+deb10u2 amd64 [installed,automatic]
linux-libc-dev/now 4.19.269-1 amd64 [installed,upgradable to: 4.19.316-1]
login/oldoldstable,now 1:4.5-1.1 amd64 [installed,automatic]
lsb-base/oldoldstable,now 10.2019051400 all [installed,automatic]
make/oldoldstable,now 4.2.1-1.2 amd64 [installed,automatic]
man-db/oldoldstable,now 2.8.5-2+deb10u1 amd64 [installed]
manpages-dev/oldoldstable,now 4.16-2 all [installed,automatic]
manpages/oldoldstable,now 4.16-2 all [installed,automatic]
mawk/oldoldstable,now 1.3.3-17+b3 amd64 [installed,automatic]
mime-support/oldoldstable,now 3.62 all [installed,automatic]
mount/oldoldstable,now 2.33.1-0.1 amd64 [installed,upgradable to: 2.33.1-0.1+deb10u1]
nano/oldoldstable,now 3.2-3+deb10u1 amd64 [installed]
ncurses-base/now 6.1+20181013-2+deb10u3 all [installed,upgradable to: 6.1+20181013-2+deb10u5]
ncurses-bin/now 6.1+20181013-2+deb10u3 amd64 [installed,upgradable to: 6.1+20181013-2+deb10u5]
ncurses-term/now 6.1+20181013-2+deb10u3 all [installed,upgradable to: 6.1+20181013-2+deb10u5]
netbase/oldoldstable,now 5.6 all [installed,automatic]
openssh-client/oldoldstable,now 1:7.9p1-10+deb10u2 amd64 [installed,upgradable to: 1:7.9p1-10+deb10u4]
openssh-server/oldoldstable,now 1:7.9p1-10+deb10u2 amd64 [installed,upgradable to: 1:7.9p1-10+deb10u4]
openssh-sftp-server/oldoldstable,now 1:7.9p1-10+deb10u2 amd64 [installed,upgradable to: 1:7.9p1-10+deb10u4]
openssl/now 1.1.1n-0+deb10u4 amd64 [installed,upgradable to: 1.1.1n-0+deb10u6]
passwd/oldoldstable,now 1:4.5-1.1 amd64 [installed,automatic]
patch/oldoldstable,oldoldstable,now 2.7.6-3+deb10u1 amd64 [installed,automatic]
perl-base/oldoldstable,now 5.28.1-6+deb10u1 amd64 [installed,automatic]
perl-modules-5.28/oldoldstable,now 5.28.1-6+deb10u1 all [installed,automatic]
perl/oldoldstable,now 5.28.1-6+deb10u1 amd64 [installed,automatic]
pinentry-curses/oldoldstable,now 1.1.0-2 amd64 [installed,automatic]
procps/oldoldstable,now 2:3.3.15-2 amd64 [installed,automatic]
psmisc/oldoldstable,now 23.2-1+deb10u1 amd64 [installed,automatic]
publicsuffix/oldoldstable,now 20220811.1734-0+deb10u1 all [installed,automatic]
python-pip-whl/oldoldstable,now 18.1-5 all [installed,automatic]
python3-asn1crypto/oldoldstable,now 0.24.0-1 all [installed,automatic]
python3-cffi-backend/oldoldstable,now 1.12.2-1 amd64 [installed,automatic]
python3-crypto/oldoldstable,now 2.6.1-9+b1 amd64 [installed,automatic]
python3-cryptography/oldoldstable,now 2.6.1-3+deb10u4 amd64 [installed,automatic]
python3-dbus/oldoldstable,now 1.2.8-3 amd64 [installed,automatic]
python3-dev/oldoldstable,now 3.7.3-1 amd64 [installed,automatic]
python3-distutils/oldoldstable,now 3.7.3-1 all [installed,automatic]
python3-entrypoints/oldoldstable,now 0.3-1 all [installed,automatic]
python3-gi/oldoldstable,now 3.30.4-1 amd64 [installed,automatic]
python3-keyring/oldoldstable,now 17.1.1-1 all [installed,automatic]
python3-keyrings.alt/oldoldstable,now 3.1.1-1 all [installed,automatic]
python3-lib2to3/oldoldstable,now 3.7.3-1 all [installed,automatic]
python3-minimal/oldoldstable,now 3.7.3-1 amd64 [installed,automatic]
python3-pip/oldoldstable,now 18.1-5 all [installed]
python3-pkg-resources/oldoldstable,now 40.8.0-1 all [installed,automatic]
python3-secretstorage/oldoldstable,now 2.3.1-2 all [installed,automatic]
python3-setuptools/oldoldstable,now 40.8.0-1 all [installed,automatic]
python3-six/oldoldstable,now 1.12.0-1 all [installed,automatic]
python3-wheel/oldoldstable,now 0.32.3-2 all [installed,automatic]
python3-xdg/oldoldstable,now 0.25-5 all [installed,automatic]
python3.7-dev/now 3.7.3-2+deb10u4 amd64 [installed,upgradable to: 3.7.3-2+deb10u7]
python3.7-minimal/now 3.7.3-2+deb10u4 amd64 [installed,upgradable to: 3.7.3-2+deb10u7]
python3.7/now 3.7.3-2+deb10u4 amd64 [installed,upgradable to: 3.7.3-2+deb10u7]
python3/oldoldstable,now 3.7.3-1 amd64 [installed]
readline-common/oldoldstable,now 7.0-5 all [installed,automatic]
sed/oldoldstable,now 4.7-1 amd64 [installed,automatic]
sensible-utils/oldoldstable,now 0.0.12 all [installed,automatic]
shared-mime-info/oldoldstable,now 1.10-1 amd64 [installed,automatic]
sudo/now 1.8.27-1+deb10u5 amd64 [installed,upgradable to: 1.8.27-1+deb10u6]
systemd-sysv/oldoldstable,now 241-7~deb10u8 amd64 [installed,upgradable to: 241-7~deb10u10]
systemd/oldoldstable,now 241-7~deb10u8 amd64 [installed,upgradable to: 241-7~deb10u10]
sysvinit-utils/oldoldstable,now 2.93-8 amd64 [installed,automatic]
tar/oldoldstable,now 1.30+dfsg-6 amd64 [installed,upgradable to: 1.30+dfsg-6+deb10u1]
tcpdump/oldoldstable,now 4.9.3-1~deb10u2 amd64 [installed]
tree/oldoldstable,now 1.8.0-1 amd64 [installed]
tzdata/now 2021a-0+deb10u8 all [installed,upgradable to: 2024a-0+deb10u1]
ucf/oldoldstable,now 3.0038+nmu1 all [installed,automatic]
util-linux/oldoldstable,now 2.33.1-0.1 amd64 [installed,upgradable to: 2.33.1-0.1+deb10u1]
wget/oldoldstable,now 1.20.1-1.1 amd64 [installed]
xauth/oldoldstable,now 1:1.0.10-1 amd64 [installed,automatic]
xdg-user-dirs/oldoldstable,now 0.17-2 amd64 [installed,automatic]
xz-utils/oldoldstable,oldoldstable,now 5.2.4-1+deb10u1 amd64 [installed,automatic]
zlib1g/oldoldstable,now 1:1.2.11.dfsg-1+deb10u2 amd64 [installed,automatic]
analyst@6af7d8e8f017:~$ sudo apt install suricata 
Reading package lists... Done
Building dependency tree       
Reading state information... Done
The following additional packages will be installed:
  geoip-database libauthen-sasl-perl libdata-dump-perl libencode-locale-perl libevent-2.1-6
  libevent-core-2.1-6 libevent-pthreads-2.1-6 libfile-listing-perl libfont-afm-perl libgeoip1
  libhiredis0.14 libhtml-form-perl libhtml-format-perl libhtml-parser-perl libhtml-tagset-perl
  libhtml-tree-perl libhtp2 libhttp-cookies-perl libhttp-daemon-perl libhttp-date-perl
  libhttp-message-perl libhttp-negotiate-perl libhyperscan5 libio-html-perl libio-socket-ssl-perl
  libjansson4 libltdl7 libluajit-5.1-2 libluajit-5.1-common liblwp-mediatypes-perl
  liblwp-protocol-https-perl libmailtools-perl libnet-http-perl libnet-smtp-ssl-perl
  libnet-ssleay-perl libnet1 libnetfilter-log1 libnetfilter-queue1 libnfnetlink0 libnspr4 libnss3
  libprelude23 libpython-stdlib libpython2-stdlib libpython2.7-minimal libpython2.7-stdlib
  libtimedate-perl libtry-tiny-perl liburi-perl libwww-perl libwww-robotrules-perl libyaml-0-2
  oinkmaster perl-openssl-defaults prelude-utils python python-minimal python-simplejson python2
  python2-minimal python2.7 python2.7-minimal snort-rules-default suricata-oinkmaster
Suggested packages:
  libdigest-hmac-perl libgssapi-perl geoip-bin libcrypt-ssleay-perl libauthen-ntlm-perl python-doc
  python-tk python2-doc python2.7-doc binfmt-support snort | snort-pgsql | snort-mysql
  libtcmalloc-minimal4
The following NEW packages will be installed:
  geoip-database libauthen-sasl-perl libdata-dump-perl libencode-locale-perl libevent-2.1-6
  libevent-core-2.1-6 libevent-pthreads-2.1-6 libfile-listing-perl libfont-afm-perl libgeoip1
  libhiredis0.14 libhtml-form-perl libhtml-format-perl libhtml-parser-perl libhtml-tagset-perl
  libhtml-tree-perl libhtp2 libhttp-cookies-perl libhttp-daemon-perl libhttp-date-perl
  libhttp-message-perl libhttp-negotiate-perl libhyperscan5 libio-html-perl libio-socket-ssl-perl
  libjansson4 libltdl7 libluajit-5.1-2 libluajit-5.1-common liblwp-mediatypes-perl
  liblwp-protocol-https-perl libmailtools-perl libnet-http-perl libnet-smtp-ssl-perl
  libnet-ssleay-perl libnet1 libnetfilter-log1 libnetfilter-queue1 libnfnetlink0 libnspr4 libnss3
  libprelude23 libpython-stdlib libpython2-stdlib libpython2.7-minimal libpython2.7-stdlib
  libtimedate-perl libtry-tiny-perl liburi-perl libwww-perl libwww-robotrules-perl libyaml-0-2
  oinkmaster perl-openssl-defaults prelude-utils python python-minimal python-simplejson python2
  python2-minimal python2.7 python2.7-minimal snort-rules-default suricata suricata-oinkmaster
0 upgraded, 65 newly installed, 0 to remove and 59 not upgraded.
Need to get 16.6 MB of archives.
After this operation, 62.2 MB of additional disk space will be used.
Do you want to continue? [Y/n] apt list --installed 
Abort.
analyst@6af7d8e8f017:~$ 
