# 📅 Daily Log — {{2026-02-19}

---

## 🎯 Daily Objectives
- stay focused on CCNA & python

### 🌐 CCNA
## converting the mac address 48 bit to 64 bit mac address for ipv6 eui-64 format

0030.f236.4502
0030.f2ff.fe36.4502
0000.0000.0011.0000
1234.5678
0000.0010.0011.0000
0230.f2ff.fe36.4502

- add the network prefix 2001:db8
- ipv6 interface address 2001:db8::230:f2ff:fe36:4502/64
-

- Hardware is CN Gigabit Ethernet, address is 0001.63b0.b802 (bia 0001.63b0.b802)
- now calculate the eui-64 mac address converted to 64 bits
add fffe to the middle and switch the 7th bit
then add the network prefix to the a converted mac address to get the eui-64 address

0001.63b0.b802
0001.63ff.feb0.b802
convert the first 16 bits to binary
0000.0000.0000.0001
1234.5678
0000.0010.0000.0001
convert back to hexidecimal
0201:63ff:feb0:b802
add the the network prefix 2001:db08
ipv6 eui-64 2001:db08:201:63ff:feb0:b802/64


