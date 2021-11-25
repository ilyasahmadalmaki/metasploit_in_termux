# Metasploit Framework 6 in Termux

![Metasploit 6 running](https://i.imgur.com/yLFQhvP.png)

## CARA INSTALL:
### OTOMATIS
```bash
source <(curl -fsSL https://shorturl.at/mE145) 
```

### MANUAL
```bash
pkg install wget

wget https://raw.githubusercontent.com/ilyasahmadalmaki/metasploit_in_termux/master/metasploit.sh

chmod +x metasploit.sh

./metasploit.sh
```

## Setelah instalasi selesai
Start `postgresql`
```bash
./msfconnect.sh start
```

SELANJUTNYA KETIK `msfconsole`
```bash
msfconsole
```
