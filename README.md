
# Monitor Mode



 









```bash
  iwconfig

  ifconfig [network interface name here] down

 #finding network interface name and don't use the [ ] sign while executing 

  ifconfig 

  airmon-ng check kill
  
  iwconfig [network interface name] mode monitor

  ifconfig [network interface name] up

  iwconfig

```
# Packet Sniffing [On Monitor Mode]

```bash
iwconfig

airodump-ng [network interface name]

#ctrl+c to quit
```
# Targeted Packet Sniffing
```bash
airodump-ng --bssid [bssid of specific wifi] --channel [channel no.] --write test [network interface name]

#ctrl + c to quit 

ls

#use wireshark to investigate the $$#$.cap file

[file test.cap]
```










