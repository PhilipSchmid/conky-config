# Conky Config

![Conky Screenshot](Screenshot.png)

## Prerequisites

### Tools
```bash
sudo apt install conky-all
```

### Configuration
Replace `wlp0s20f3` with the actual network interface name you would like to monitor.

## Installation
```bash
git clone git@github.com:PhilipSchmid/conky-config.git
cd conky-config/
cp .conkyrc ~/
```

## Autostart
Add `conky -p 20` to your autostart.

## Available Conky Variables
See http://conky.sourceforge.net/variables.html

## Credit
- https://github.com/kematzy/conky
- https://github.com/pascalwhoop/conky.conf