![красотищатокакая-code](https://user-images.githubusercontent.com/88341460/189535591-84f204da-08af-4989-821f-e6608902a4a1.gif)

### ARP SPOOFER

[![Version](https://img.shields.io/badge/Version-3.1.0-green)]()
[![Python](https://img.shields.io/badge/Python-v3.9-yellow)]()

 ==> This program will arp spoofing device in network

### NOTICE

~~I'm no longer maintaining this project salvatore .~~

### install requirements

```
pip install scapy

```
```
pip install optparse

```
### Support                                                  

It motivates me to keep updating this program.

subscribe my channel

```                                                                 
https://youtu.be/Nx0FqqmzZLI

```                                                                       
  
# Installing

* ```git clone https://github.com/blackmask00/arp-spoofer.git```
* ```cd arp-spoofer```
* ```python arp-spoofer.py```


# help

```
  


⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⢀⡤⢤⡤⣤⣤⣤⠀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
 ⠀⠀⠀⠀⠀⠀⠀⠀⢠⣶⢺⡹⡜⢢⡙⢮⡵⣻⣼⣳⢿⣟⣧⣆⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀    **************************
⠀⠀⠀⠀⠀⠀⠀⠀⣴⣏⠷⣓⢌⢣⡝⣣⢟⣵⣳⢯⣿⣾⣿⣿⣿⠁⡠⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀     * █▓▒▒░░░ARP spoof░░░▒▒▓█*
⠀⠀⠀⠀⠀⠀⠀⢰⡿⣜⡫⡜⡌⢶⣩⢗⣻⢾⣽⣻⢾⣷⣿⣿⠇⢸⣻⣿⣾⢶⣠⠀⣀⠀⠀⠀⢀⣀⠀⠤⠤⣆⣿⡇     **************************
⠀⠀⠀⠀⠀⠀⠀⣾⡳⣝⢲⠱⣘⢧⡺⣭⢟⣾⣳⢯⣿⣿⣿⡷⠀⣏⣿⣿⣯⠿⣬⠳⣌⠡⡁⠄⢀⠠⠐⢠⢓⣮⣯⠁          ❚█══Salvatore══█❚                    
⠀⠀⠀⠀⠀⠀⢰⢷⡹⢎⡣⢓⡜⣲⡝⣾⣻⢾⣽⣻⣿⣿⡿⠃⣸⣽⣿⡿⣞⡻⢆⡳⢌⠒⡀⠐⡀⠄⡈⢆⢯⣾⠆⠀       
⠀⠀⠀⠀⠀⢀⣟⣧⢻⡱⢌⢣⠞⣵⢫⡷⣯⣟⣾⣟⣿⣿⡻⢀⣥⣿⣿⢿⡽⣙⠮⡔⢊⡐⠀⡐⠀⡐⢠⣋⢾⠟⠀⠀
⠀⠀⠀⠀⠀⣨⡿⣜⢣⡜⣌⣧⣛⣼⣯⢷⣻⢾⣽⣿⣿⣿⠃⡴⣾⣿⣟⡿⣜⢣⡓⡌⢂⠄⠂⢀⠂⠄⣣⢞⡿⠃⠀⠀
⠀⠀⠀⠀⠀⣿⣵⠿⠛⠋⣉⡉⡀⢀⣉⠉⠙⠻⢹⢿⣿⡏⢰⢶⣿⣿⢯⡽⢎⡳⢌⠰⢁⠠⠐⠀⠂⡜⣰⣻⡻⠀⠀⠀
⠀⠀⠀⠀⢠⣭⣿⡾⣧⣳⢯⣿⣻⣿⣿⣿⣷⣤⣬⡘⠻⠃⣿⣿⣿⣿⡿⣿⢾⡳⣞⠰⢨⠀⠆⢃⢦⣽⣻⣿⠇⠀⠀⠀
⠀⠀⠀⢀⣿⣿⣻⠹⢃⡟⣞⡻⣏⡿⣿⣿⣿⣿⣿⣷⡇⠀⠋⢿⣿⣿⡻⡿⢏⡹⠎⡘⠀⠆⠃⠎⣸⣞⡿⡛⠀⠀⠀⠀
⠀⠀⠀⣼⡿⣞⡥⢋⠲⣘⢦⡻⣼⣻⣟⣿⣿⣿⣿⣯⠁⠞⣧⣦⠀⠉⠓⠻⠆⠵⠬⣤⠶⠲⠾⠋⢛⠉⠀⠀⠀⠀⠀⠀
⠀⠀⢰⣿⢿⡱⢎⢡⢋⣜⣣⢟⣵⣿⣻⣿⣿⣿⣿⡇⣼⣿⡿⣝⡻⡖⣥⢐⡒⢀⠀⠐⠒⠂⠈⠡⡑⣺⡏⠀⠀⠀⠀⠀
⠀⠀⣾⣟⣯⢳⡉⢦⡙⢦⣛⡾⣽⣾⣿⣿⣿⣿⡿⠁⣏⣿⡽⣏⠷⣹⠐⡆⡘⠠⠀⠀⠀⠀⠠⢑⣰⣯⠀⠀⠀⠀⠀⠀
⠀⢸⣿⣻⢬⢣⠘⢦⣙⢧⢯⡽⣷⣿⣿⣿⣿⣿⠃⣸⣽⡿⡽⣎⡟⠴⣉⠔⠡⠀⠀⠀⠀⡀⢡⠒⣼⠆⠀⠀⠀⠀⠀⠀
⢀⣿⣯⢗⣋⢆⡙⢦⡝⣮⠿⣽⣿⣿⣿⣿⣿⡟⢀⣷⡿⣽⡳⡝⣜⠣⢌⠂⠡⠈⠀⠀⠀⡐⠤⣩⠷⠀⠀⠀⠀⠀⠀⠀
⣸⡿⣽⣺⣴⠌⠾⠷⠞⠷⠯⢿⢻⣿⣿⣿⣿⠁⡴⣾⣟⡷⣹⣙⠦⡍⢢⠘⠀⠀⠀⠀⡐⢠⢃⣾⠃⠀⠀⠀⠀⠀⠀⠀
⠛⠛⠈⠁⠀⠀⠀⠀⠀⠀⠀⠀⠈⠉⠹⢿⡕⢴⢷⣿⡽⣺⡕⣎⢒⠡⠂⠄⠁⠀⠀⡀⠐⡄⢺⡋⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠹⢻⣳⢟⡵⣚⡌⢎⠡⠘⠀⠀⠀⠀⠠⢑⣌⣟⠁⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠙⠓⠞⢬⣤⢧⣬⣤⢤⣶⠶⠟⠛⠉⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀


  
Usage: arp-spoofer.py [options]

Options:
  -h, --help            show this help message and exit
  -t TARGET_IP, --target=TARGET_IP
                        specify Victim IP Address
  -r ROUTER_IP, --router=ROUTER_IP
                        specify Geteway IP Address
```

# Example :


*``` python arp-spoofer.py -t 192.168.0.1x -r router gateway 192.168.0.1```



This script for arp spoofing target  application that performs a Man in the middle The tool is intended to automate arp in network 

### script image

<img src="./slva.png" alt="ig">
## Social media

```
https://youtube.com/@cyber-security_morocco_00
```

```
https://instagram.com/6ec_0
```
