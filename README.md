# Task-1 : 
## Scanning for local network or open ports
#### Objective : 
Learn to discover open ports on devices in your local network to
understand network exposure.
#### Tools: Nmap (free), Wireshark.

Procedure :
##### 1. using nmap to find open ports for a specific ip addresses range. 
you have to know your ip address and  local network range by following command
```bash
ifconfig
```

Using nmap to scan the local network connected devices
```bash
nmap -sS <ipaddress-range>
```
![Screenshot_2025-05-26_21-34-23](https://github.com/user-attachments/assets/aeec2da9-4033-4ed8-82e4-13c6f0de04af)

##### 2. using wireshark to capture the details of the packet transfers. 
![Screenshot_2025-05-26_21_48_50](https://github.com/user-attachments/assets/02f3a6f7-15c9-41db-8f13-8e5fcc73bd5d)
