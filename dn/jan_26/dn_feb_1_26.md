### February daily notes

Day 28 Jeremies IT lab for CCNA
- lab

The lab is to troubleshoot ospf on a simple network

commands used:

#R1
sh ip int br
conf t
int s0/0/0
ip add 192.168.12.1 255.255.255.252
do sh controllers s0/0/0
clock rate 128000
no shut

#R2
en
sh ip int br
conf t
int s0/0/0
ip add 192.168.12.2 255.255.255.252


!(ccna_lab)[pt_feb_1.png]







