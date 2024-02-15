# Wireshark

SCENARIO
LAN segment data:
1. LAN segment range: 172.16.2.0/24 (172.16.2.0 through 172.16.2.255)
2. Domain: tinsolutions.net
3. Domain controller: 172.16.2.2 (Tinsolutions-DC)
4. LAN segment gateway: 172.16.2.1
5. LAN segment broadcast address: 172.16.2.255
TASK
In the past three days, three Windows hosts on the internal corporate network
for tinsolutions.net were infected with malware. You have packet captures
(pcaps) of network traffic when each host becomes infected. You also have the
associated alerts on this network traffic. Finally, you have the three emails that
kicked off the infection activity. Your task is to answer the following questions
for each infection:
1. What date and time did the infection activity start?
2. What is the IP address of the Windows infected host?
3. What is the MAC address of the Windows infected host?
4. What is the host name of the infected Windows host?
5. What is the user account name from the infected Windows host?
6. What type of malware(s) was the host infected with?

PCAP-1
1. What date and time did the infection activity start?
Start of infection: Oct 3, 2019 22:51:59.552856000 India Standard Time
2. What is the IP address of the Windows infected host?
172.16.2.197
3. What is the MAC address of the Windows infected host?
b8:97:5a:34:cd:91 (BiostarM_34:cd:91)
4. What is the host name of the infected Windows host?
BURGESS-WIN7-PC
5. What is the user account name from the infected Windows host?
 theodore.burgess
6. What type of malware(s) was the host infected with?
trojan.emotet/deepscan (family labels- emotet,deepscan,marte)
PCAP-2
1. What date and time did the infection activity start?
Start of infection: Oct 4, 2019 20:35 India Standard Time
2. what is the IP address of the Windows infected host?
172.16.2.219
3. What is the MAC address of the Windows infected host?
08:17:f4:67:20:0b (Ibm_67:20:0b)
4. What is the host name of the infected Windows host?
G-UNDERWOOD-PC
5. What is the user account name from the infected Windows host?
geneva.underwood
6. What type of malware(s) was the host infected with?
trojan.ursnif/aivf (family labels- ursnif,aivf,aovpj)
PCAP-3
1. What date and time did the infection activity start?
Start of infection: Oct 5, 2019 22:36 India Standard Time
2. what is the IP address of the Windows infected host?
172.16.2.83
3. What is the MAC address of the Windows infected host?
14:9f:e8:39:13:1b (LevonoMo_39:13:1b)
4. What is the host name of the infected Windows host?
MOTHRA-RULEZ-PC
As soon as the file is downloaded, the fakeurl are spammed. Which indicates that
this PC is infected.
5. What is the user account name from the infected Windows host?
lyndon.russ
