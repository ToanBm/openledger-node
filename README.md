# OPENLEDGER NODE
Testnet Whitelist: Final Countdown!
1. Like & Retweet this post: https://x.com/OpenledgerHQ/status/1867560990541590704
2. Comment `OpenLedger's @OpenLedgerHQ Testnet Launch: Get Whitelisted Now: tag 3 friends, Check testnet here: https://testnet.openledger.xyz/`
3. Join Discord: https://discord.gg/qqxhwAt7Da
4. Form: https://forms.gle/Wh8bAg4w7DzNFAYG6

## 1. Setting up your xrdp:
```Bash
wget https://raw.githubusercontent.com/0xtnpxsgt/Install-xrdp-on-linux-vps/refs/heads/main/install-script.sh && chmod +x install-script.sh && ./install-script.sh
```
```Bash
sudo usermod -aG docker USERNAMESAXRDP
```
```Bash
newgrp docker
sudo chown root:docker /var/run/docker.sock
sudo chmod 660 /var/run/docker.sock
```

* Use Remote Desktop connect with your VPS
* Login with User & Passworld
* Right click to open Terminal
* Follow next step
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
openledger-node
```
