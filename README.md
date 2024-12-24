# Initverse-Node-Run-Full-Guide

Step 1 : Setting up a VPS

You can choose CLOUP VPS 2 on Contabo : https://www.tkqlhce.com/click-101114590-13484397


Select Ubuntu 22.04


Step 2: Connect to your VPS

ssh root@<IP_OF_YOUR_VPS>
Step 3: Configure your node

Update your system

sudo apt-get update
Install Screen

apt install screen
Downlad inichain file

wget https://github.com/Project-InitVerse/ini-miner/releases/download/v1.0.0/iniminer-linux-x64
Give permission to the file

chmod +x iniminer-linux-x64
Create a new screen session

screen -S Inichain
Launch the InitVerse miner

./iniminer-linux-x64 --pool stratum+tcp://<YOUR_WALLET_ADDRESS>.Worker001@pool-core-testnet.inichain.com:32672 

Leave the screen

CTRL+A+D
Step 4 : Check your miner activity

Go to https://genesis-testnet.yatespool.com/


Past your wallet address


The rewards are automatically sent to your address.
You can check them on the explorer : https://genesis-testnet.iniscan.com/


Check logs

screen -r Inichain
Don’t forget to leave it with CTRL+A+D

Thank’s for reading


Miner Dashboard : https://genesis-testnet.yatespool.com/

Inichain explorer : https://genesis-testnet.iniscan.com/

