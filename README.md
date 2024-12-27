# Initverse-Node-Run-Full-Guide

### Need Some Requirements for PC Users

1. For Windows Install WSL - https://learn.microsoft.com/en-us/windows/wsl/install#install-wsl-command

2. For macOS If you have Installed Homebrew (https://brew.sh/) to manage packages on OS X,
run this command to install Git.
```
brew install git
```

1️⃣ Dependencies for WINDOWS & LINUX & VPS
```
sudo apt update
sudo apt upgrade
```

For VPS Only
```
apt install screen -y
```

2️⃣ Download Some Files
```
wget https://github.com/Project-InitVerse/ini-miner/releases/download/v1.0.0/iniminer-linux-x64
```
```
chmod +x iniminer-linux-x64
```

For VPS Only
```
screen -S init
```

3️⃣ Start Node
```
./iniminer-linux-x64 --pool stratum+tcp://YOUR_WALLET_ADDRESS.Worker001@pool-core-testnet.inichain.com:32672 
```
Replace ur YOUR_WALLET_ADDRESS with ur actual Metamask Address

For VPS Only
```
PRESS CTRL+A+D (to run ur miner continuously)
```

🔶Check ur Miner(put ur wallet address):- https://genesis-testnet.yatespool.com/

🔶Check ur Rewards(put ur wallet address):- https://genesis-testnet.iniscan.com/

![6296496737283588777](https://github.com/user-attachments/assets/d524dc75-70bd-4936-9c44-9db038d807b2)

Each day ur mining rewards(withdrawable balance) transfer to ur wallet automatically at 1:00(±30min) pm IST near about

For VPS Only (to check ur miner again)
```
screen -r init
```
PRESS CTRL+A+D

## 🔶For Next Day Run This Command (Windows)

#1 Open WSL and Put this Command 
```
./iniminer-linux-x64 --pool stratum+tcp://YOUR_WALLET_ADDRESS.Worker001@pool-core-testnet.inichain.com:32672
```
Replace ur YOUR_WALLET_ADDRESS with ur actual Metamask Address




