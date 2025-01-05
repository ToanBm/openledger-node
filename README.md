# openledger-node

## 1. Setting up your xrdp:
```Bash
wget https://raw.githubusercontent.com/0xtnpxsgt/Install-xrdp-on-linux-vps/refs/heads/main/install-script.sh && chmod +x install-script.sh && ./install-script.sh
```
## 2. Install OpenLedger:
```Bash
wget https://cdn.openledger.xyz/openledger-node-1.0.0-linux.zip
```
```Bash
unzip openledger-node-1.0.0-linux.zip
```
```Bash
sudo dpkg -i openledger-node-1.0.0.deb
```
## 3. Start node:
```Bash
openledger-node --no-sandbox
```
