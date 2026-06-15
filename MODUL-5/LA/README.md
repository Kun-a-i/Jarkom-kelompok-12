# LAPORAN TUGAS MODUL 5

Pada tugas modul ini, praktikan diperintahkan untuk membuat sebuah jaringan yang terdiri dari dua fortinet. Setiap fortinet berperan sebagai firewall untuk Kota Jakarta dan Kota Surabaya. Berikut merupakan detil pembuatan jaringan tersebut.

--------------------
## TOPOLOGI

Berikut merupakan Topologi dari jaringan yang akan dibuat. 

![](./img/topologi)

-----
## TUGAS 1 
Berikut merupakan hasil dari konfigurasi untuk Cisco Switch Jakarta

![SWTCH0](./img/CISCOJKT_SWTCH_0.jpeg)
![SWTCH1](./img/CISCOJKT_SWTCH_1.jpeg)

-----
## TUGAS 2
Berikut merupakan hasil dari konfigurasi untuk Cisco Router Jakarta

![](./img/CISCOJKT_0.jpeg)
![](./img/CISCOJKT_1.jpeg)

-----
## TUGAS 3
Berikut merupakan hasil dari 
* `ip address print`, 
* `interface vrrp print`, 
* `ip dhcp-relay print`, 
* `ip route print`, 
* Bukti hasil ping ke Fortigate.

untuk Switch Mikrotik Jakarta

![RTR0](./img/MKTK_JKT_RTR_0.jpeg)
![RTR1](./img/MKTKJKT_RTR_1.jpeg)
![RTR2](./img/MKTKJKT_RTR_2.jpeg)

-----
## TUGAS 4
Berikut merupakan hasil dari perintah 
* `ip a` 
* `ip` 
* `/etc/dhcp/dhcp.conf`
* `ping 8.8.8.8`

untuk Ubuntu Server Jakarta.

![USRVR](./img/UJKT_SRVR_0.jpeg)
![USRVR0](./img/UJKT_SRVR_1.jpeg)

-----
## TUGAS 5
Berikut merupakan hasil dari perintah

* `get system interface physical`
* `get router info routing-table all`
* Firewall policy
* ping ke 8.8.8.8
* ping ke IP tunnel Surabaya
* `get router info ospf neighbor`
* `get router info routing-table ospf`
untuk FortiGate Jakarta

![FGAT0](./img/JKT_FGAT_0.jpeg)
![FGAT1](./img/JKT_FGAT_1.jpeg)
![FGAT2](./img/JKT_FGAT_2.jpeg)
![FGAT3](./img/JKT_FGAT_3.jpeg)

----
## TUGAS 6
Berikut merupakan hasil dari perintah

* `ip address print`
* `ip route print`
* `ip firewall nat print`
* `ping 8.8.8.8`
* ping antar WAN FortiGate

![ISP0](./img/ISP_MKTK_0.jpeg)
![ISP1](./img/ISP_MKTK_1.jpeg)

----
## TUGAS 7
Berikut merupakan hasil dari konfigurasi Switch dan Mikrotik Router Surabaya dengan perintah sebagai berikut.

* `show vlan brief`
* `show interface trunk`
* `ip address print`
* `ip dhcp-server print`
* `ip pool print`
* `ip route print`
* VPC VLAN 30 mendapatkan IP DHCP
* VPC ping ke 8.8.8.8

![SWTCH0](./img/SWTCH_SBY_0.jpeg)
![MKTK0](./img/MKTK_SBY_0.jpeg)
![VPC0](./img/VPC30_SBY_0.jpeg)

----
## TUGAS 8
Berikut merupakan hasil dari konfigurasi FortiGate Surabaya untuk perintah

* `get system interface physical`
* `get router info routing-table all`
* Firewall policy
* Ping ke 8.8.8.8
* ping ke IP Tunnel Jakarta
* `get router info ospf neighbor`
* `get router info routing-table ospf`

![FGAT00](./img/FGAT_SBY_0.jpeg)
![FGAT01](./img/FGAT_SBY_1.jpeg)
![FGAT02](./img/FGAT_SBY_2.jpeg)
![FGAT03](./img/FGAT_SBY_3.jpeg)
![FGAT04](./img/FGAT_SBY_4.jpeg)

----
## TUGAS 9
Berikut merupakan hasil konfigurasi GRE Tunnel dan OSPF over GRE dengan ketentuan.

* Ping WAN antar FortiGate
* Ping tunnel antar FortiGate
* `get router info ospf neighbor`
* `get router info routing-table ospf`
* Ping client Jakarta ke client Surabaya
* Ping client Surabaya ke client Jakarta

![FGATJ0](./img/FGAT_JKT_0.jpeg)
![FGATS0](./img/FGATS_SBY_0.jpeg)
![FGATJ1](./img/FGAT_JKT_1.jpeg)
![FGATJ0](./img/JKT_SBY0.jpeg)
![FGATJ0](./img/SBY_JKT0.jpeg)

----
## TUGAS 10
Berikut merupakan pengujian akhir dengan ketentuan

* IP DHCP client Jakarta VLAN 10
* IP DHCP client Surabaya VLAN 20
* Ping internet dari Jakarta
* Ping internet dari Surabaya
* Ping antar site
* Akses web server Jakarta dari Surabaya
* Routing table OSPF
* Analisis singkat jalur traffic Jakarta ke Surabaya

![VLAN10](./img/JKT_SBY.jpeg)
![VLAN20](./img/SBY_JKT.jpeg)
![VLAN30](./img/VLAN30_PING.jpeg)
![VLAN10F](./img/VLAN10F_PING.jpeg)
![VLAN40](./img/VLAN40.jpeg)
![WEB](./img/WEB.jpeg)
