# Initverse-Node-Run-Full-Guide

1. sudo apt-get update
2. apt install screen

press y if ask

3. wget https://github.com/Project-InitVerse/ini-miner/releases/download/v1.0.0/iniminer-linux-x64
4. chmod +x iniminer-linux-x64
5. screen -S Inichain
Add your wallet address in below command

6. ./iniminer-linux-x64 --pool stratum+tcp://<YOUR_WALLET_ADDRESS>.Worker001@pool-core-testnet.inichain.com:32672 

PRESS CTRL+A+D
Check your miner
https://genesis-testnet.yatespool.com/
Check your rewards
https://genesis-testnet.iniscan.com/

7. screen -r Inichain
PRESS CTRL+A+D

Miner Dashboard : https://genesis-testnet.yatespool.com/

Inichain explorer : https://genesis-testnet.iniscan.com/

