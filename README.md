# motd.d
a set of scipts to enhance the basic motd experience


## Example
```
SYSTEM INFORMATION
 Architecture:   armv7l                                     
 Distribution:   Raspbian GNU/Linux 10 (buster)             
 Kernel Version: 4.19.58-v7+                                
 Platform:       GNU/Linux                                  
 Processes:      149                                        
 Users:          1                                          
 Date:           Fri Aug  2 23:41:23 NZST 2019              
 Uptime:   0 days, 0 hours, 32 minutes                      
 CPU Temp: 53.7°C              CPU Load: 0.40, 0.21, 0.31
 Memory:   [■■■■■·····] 51.2%  CPU Load: [■·········] 10.0%

NETWORK INFORMATION
 Hostname:       raspberrypi-desktop                        
 IPv4 Address:   192.168.1.10                               
 IPv4 Address:   192.168.1.11                               
 IPv6 Address:   fe80::653f:dc6:a998:752b                   
 IPv6 Address:   fe80::260e:657:5268:2e62                   
 Gateway:        192.168.1.1                                

DISK INFORMATION
 Boot:     [■■■■■■··································] 16%   
 Root:     [■■■■■■■■■■■■■■■■■■······················] 44%   
 Log:      [■■■■■■··································] 16%   
 Swap:     [■·······································]  2%   
```

## Installation
```
cd /etc/update-motd.d/
sudo wget https://raw.githubusercontent.com/saint-lascivious/motd.d/master/00-header
sudo wget https://raw.githubusercontent.com/saint-lascivious/motd.d/master/10-sysinfo
sudo wget https://raw.githubusercontent.com/saint-lascivious/motd.d/master/99-footer
sudo chmod +x *
```

## Documentation
Some basic information on the Debian motd system can be found [here](https://wiki.debian.org/motd).

## Contact
* Discord
[SaintLascivious](https://discord.gg/9Cq4gRg)

* Email
saint.lascivious@gmail.com

* IRC
[##saint-lascivious](https://webchat.freenode.net/##saint-lascivious)

* Reddit
[saint-lascivious](https://www.reddit.com/user/saint-lascivious)

![alt text][logo]

[logo]:https://vignette.wikia.nocookie.net/pokemon/images/7/76/265Wurmple.png "Using the spikes on its rear end, Wurmple peels the bark off trees and feeds on the sap that oozes out. This Pokémon's feet are tipped with suction pads that allow it to cling to glass without slipping."