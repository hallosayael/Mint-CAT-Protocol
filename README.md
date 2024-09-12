# Mint-CAT-Protocol
Mint Prerequisites : $FB, a Linux server (2 cores CPU 4 GB memory) <br>
Official documentation https://github.com/CATProtocol/cat-token-box/blob/main/packages/tracker/README.md#prerequisite

### Installation
```
bash <(curl -s https://raw.githubusercontent.com/hallosayael/Mint-CAT-Protocol/main/cat20-oooooyoung.sh) chmod +x cat 20-oooooyoung.sh
```
### Run menu
```
bash ~/cat 20-oooooyoung.sh
```
### Enter 1
### Open port 5432, 3000, 8332
```
sudo ufw allow 5432
sudo ufw allow 3000
sudo ufw allow 8332
```
After finish, back to command menu
```
bash ~/cat 20-oooooyoung.sh
```
### Enter 4
PS: Continue to the next step after confirming that it is consistent with the latest block height of the Fractal Network https://explorer.unisat.io/fractal-mainnet/block

### Create new wallet
```
bash ~/cat 20-oooooyoung.sh
```
### Enter 2
PS: to create a new fractal network btc wallet, save the mnemonic and address, and then transfer a little $FB to the address as gas to participate in minting cat 20 tokens

### Mint of $CAT tokens
```
bash ~/cat 20-oooooyoung.sh
```
### Enter 3
Because there are many people calling, the mint may fail and cause a retry. Just hang up. <br>
PS: The default gas fee is set to 30. If you want to set a higher gas fee, the command for a single mint is as follows (the number in –fee-rate 1000 is the current gas fee):
```
sudo yarn cli mint -i 45 ee 725 c 2c 5993 b 3 e 4 d 30884 2d 87 e 973 bf 1951 f 5 f 7 a 804 b 21 e 4 dd 964 ecd 1 2d 6 b_ 0 5 –fee-rate 1000
```
## If you import the created wallet mnemonics into the unisat wallet, the address will not match due to formatting issues, so you dont need to import it. <br> Just enter the newly generated wallet address in the block browser to view the FB balance and the assets you have entered. https://explorer.unisat.io/fractal-mainnet/address/bc1xxxxx
