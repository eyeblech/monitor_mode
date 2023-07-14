
# Monitor Mode



 









```bash
  iwconfig

  ifconfig [network interface name here] down

 #finding network interface name and don't use the [ ] sign while executing 

  ifconfig 


![Screenshot from 2023-07-14 19-09-41](https://github.com/eyeblech/monitor_mode/assets/78268197/ca07027e-d3b6-4e83-8624-1c3447e67db1)



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










