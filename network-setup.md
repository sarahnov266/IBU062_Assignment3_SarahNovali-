                                                                             Computer network setup

--------------------------------------------------------------------------

Device Name: PC2
Device model: PC-PT 
IP adress 210.3.12.4
Subnet mask: 255.255.255.0
Default Gateway: 210.3.14.1
DNS server: 8.8.8.8
Port
FastEthernet0

---------------------------------------------------------------------------

Device Name: Server0
Device Model: Server-PT
IP adress 168.90.0.5
Subnet mask: 255.255.0.0
Default Gateway: 168.90.0.1
DNS server: 8.8.8.8
Port
FastEthernet0

----------------------------------------------------------------------------

Device Name: Server1
Device Model: Server-PT
IP adress 210.3.14.2
Subnet mask: 255.255.255.0
Default Gateway: 210.3.14.1
DNS server: 8.8.8.8
Port
FastEthernet0

-----------------------------------------------------------------------------

Device Name: Server2
Device Model: Server2
IP adress 210.3.14.3
Subnet mask: 255.255.255.0
Default Gateway: 210.3.14.1
DNS server: 8.8.8.8
Port
FastEthernet0

----------------------------------------------------------------------------------

Device Name: Laptop0
Device Model: Laptop-PT
IP adress 168.90.0.2
Subnet mask: 255.255.0.0
Default Gateway: 168.90.0.1
DNS server: 8.8.8.8
Port
FastEthernet0


-------------------------------------------------------------------

Device Name: PC0
Device Model: PC-PT
IP adress 168.90.0.4
Subnet mask: 255.255.0.0
Default Gateway: 168.90.0.1
DNS server: 8.8.8.8
Port
FastEthernet0

----------------------------------------------------------------

Device Name: PC1
Device Model: PC-PT
IP adress 168.90.0.3
Subnet mask: 255.255.0.0
Default Gateway: 168.90.0.1
DNS server: 8.8.8.8
Port
FastEthernet0

------------------------------------------------------------------

Device Name: Router0
Device Model: 1941
Hostname: dhcp-router

Port 		Link
GigabitEthernet0/0 Up   (Switch0 - IP address 168.90.0.1)
GigabitEthernet0/1 Up	(Switch1 - IP address 210.3.14.1)

--------------------------------------------------------------

Device Name: Switch0
Custom Device Model: 2960 IOS15
Hostname: Switch

Port 			Link
FastEthernet0/2 	Up
FastEthernet0/3 	Up
FastEthernet0/5 	Up
FastEthernet0/6		Up


--------------------------------------------------------------

Device Name: Switch1
Custom Device Model: 2960 IOS15
Hostname: Switch

Port 		Link
FastEthernet0/1 Up
FastEthernet0/2 Up
FastEthernet0/3 Up
FastEthernet0/4 Up