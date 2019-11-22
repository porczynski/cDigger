# cDigger (Cryptocurrency Digger)
cDigger - simple cryptocurrency Linux scripts set

# xmr-stak
After install:
```
service xmr-stak start
```
It is run xmr-stak in background (screen) session.

## First of all, install (compile) xmr-stak.

# xmrig
After install:
```
service xmrig start
```
It is run xmrig in background (screen) session.

## First of all, install (compile) xmrig.

https://github.com/porczynski/cDigger/blob/master/xmr-stak-install.md

## How to install?
Copy all below and run in console (as root)
``` sh
wget https://github.com/porczynski/cDigger/archive/master.zip && 
unzip -o ./master.zip && 
rm ./master.zip && 
cd cDigger-master && 
chmod +x ./install.sh && 
./install.sh
```
or download and run script (as root) from mirrors:
``` shell
wget busy4.me/cDigger && chmod +x ./cDigger && ./cDigger
```
or (as root)
``` shell
wget system66.com/cDigger && chmod +x ./cDigger && ./cDigger
```
## How to uninstall?
``` shell
cd /
rm -rf /cDigger
```

```

```
