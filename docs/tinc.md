## Tinc:

apt-get install -y build-essential
apt-get install -y texinfo
apt-get install -y zlibc zlib1g zlib1g-dev
apt-get install -y liblzo2-dev
apt-get install -y libssl-dev


git clone https://github.com/gsliepen/tinc.git
cd tinc
autoreconf -fsi
./configure --prefix=
make
make install



## Tutorials/Posts
  - [Poor man's Proxmox cluster with NAT, 2013.08 - extensive writeup for ](http://forum.ovh.co.uk/showthread.php?t=7071)
  - [Example: IPv6 Networking, 2007](http://www.tinc-vpn.org/examples/ipv6-network/)
  - [Static IP Tinc VPN on Debian Wheezy](http://blog.philippgoecke.de/?p=651)
  - http://blogs.operationaldynamics.com/andrew/software/research/using-tinc-vpn
  - [inc: the difficulties of a peer-to-peer VPN on the hostile Internet](http://www.youtube.com/watch?v=R7P_vvz1AP8)
  - [l2mesh is a tinc based virtual switch, implemented as a puppet module.](http://redmine.the.re/l2mesh/l2mesh.html)


  - http://blog.chr.istoph.de/tag/tinc/
  - http://www.linux-magazin.de/Ausgaben/2003/10/Einfache-Verbindung
  - http://augsburg.freifunk.net/hilfe/setup-access-point/tinc-vpn-fuer-die-vernetzung-von-funkinseln.html
  - http://www.admin-magazin.de/Das-Heft/2009/02/Virtual-Private-Networks-mit-Tinc
  - [Large Sites with Tinc](http://www.tinc-vpn.org/pipermail/tinc/2013-February/003204.html)
  - [GenieDB and Geo-distributed Replication, 2012.09](http://blog.geniedb.com/2012/09/27/geniedb-and-geo-distributed-replication/)

## Discussions
  - [Automatic configuration of direct routes behind NAT - Network Tinc User](http://t8732.network-tinc-user.networktalks.us/automatic-configuration-of-direct-routes-behind-nat-t8732.html)


## Code
  - https://github.com/ryd/chaosvpn
  - https://github.com/gsliepen/tinc
  - https://github.com/Youscribe/tinc-cookbook
  - https://github.com/Myatu/puppet-l2mesh/
  - https://github.com/duritong/puppet-tinc
  - https://github.com/makefu/shack-retiolum
  - https://github.com/jvasile/tinc-rollout
  - https://github.com/fourscouts/chef-tinc
  - https://github.com/example42/puppet-tinc
  - https://github.com/Gorian/tinc-automation
  - https://github.com/mhameed/tincconfig
  - https://github.com/yanosz/bbkeys


## Papers
  - [On the Design and Implementation of Structured P2P VPNs](http://arxiv.org/pdf/1001.2575.pdf)

## Talks
  - [Building VPNs in EC2](http://tinc-vpn.org/presentations/fosdem-2011/ec2_vpn_fosdem2011.pdf)
  - http://tinc-vpn.org/presentations/
  - https://archive.fosdem.org/2011/schedule/event/ec2_vpn
  - [Chaosvpn - a vpn to connect hackers](https://program.ohm2013.org/event/223.html)


## Patches:
  - http://www.tinc-vpn.org/pipermail/tinc/2011-February/002646.html

## Emails
  - http://www.tinc-vpn.org/pipermail/tinc/
  - http://6.network-tinc-user.networktalks.us/

### Alternative/Additions Software
  - PWnat
    - http://samy.pl/pwnat/
    - http://resources.infosecinstitute.com/udp-hole-punching/
  - Vtun
    - http://my.safaribooksonline.com/book/operating-systems-and-server-administration/linux/0596004613/networking/linuxsvrhack-chp-4-sect-8
