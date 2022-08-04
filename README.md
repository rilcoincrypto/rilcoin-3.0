# rilcoin 3.0
(Spanish version click here https://github.com/rilcoincrypto/rilcoin-3.0/blob/main/ES-README.md)

New version of Rilcoin, faster, secure and simple

We believe that rilcoin is a cryptocurrency designated to facilitate commercial interaction

Our team has been focused in create the most friendly form of payment

Rilcoin 3.0 bring more security and transparency to our users

Additionally we solved the energy problem, been more Eco friendly, with our SPoW consensus

SPoW (Subsecuente Proof of Work) will reduce the intensity of power dedicated to mine a block and keep the network secure

Every node and every wallet will have the option to mine and get rewards based in transactions, without dedicated equipment

Rilcoin 3.0 is open to be used  as form of payment in any development, it is universal and doesn't responde to any Goverment or Entity

Visit us in https://rilcoin.org/

Getting started

1)Download the wallet based in your operating system

-Open your wallet, and make sure your wallet is connected with a node.
-Your wallet is connected when you see the icon Wallet connections in the lower right corner of your wallet.

2)Use the following instructions to mine a block.

-Close your wallet and create the file rilcoin.conf in the folder “%APPDATA%\rilcoin\”.

-Paste the following text into rilcoin.conf and save the file.

rpcuser=rpc_rilcoin

rpcpassword=50438c6bdd47af5d887e9fc81

rpcallowip=127.0.0.1

rpcport=26579

listen=1

server=1

addnode=ril.99usa.com

addnode=ril2.99usa.com

-Open your wallet.

-Create a .bat file named mine.bat in the same folder where you extracted rilcoin-cli.exe and paste the following text into mine.bat.

@echo off

set SCRIPT_PATH=%cd%

cd %SCRIPT_PATH%

echo Press [CTRL+C] to stop mining.

:begin

 rilcoin-cli.exe generate 1
 
goto begin

Save the file.

-Execute mine.bat to start mining.

It will take about +/- 30 minutes to mine your first block, depending on your computer hardware.

Note that your blocks will give 0 rewards, when transactions come and tx's are generated rewards start showing, it is random.
