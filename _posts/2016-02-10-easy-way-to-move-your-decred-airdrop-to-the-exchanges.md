---
layout: single
title: Easy Way to Move your Decred Airdrop to the Exchanges (Windows)
categories: [altcoins]
tags: [decred]
toc: true
---

It's quite frustrating for people who aren't techie enough and must rely on third-party services to provide a crypto wallet; especially for this recently
launched [Decred Network](https://decred.org/). Take for example, the official Decred web wallet, which is already suffering frequent outages.
I feel for some of you, who are eager to cash out your free coins (note: some 874,200 coins have been given away).

## How?

First, you need to have your generated wallet seed which is a total of 32 space-separated words. Otherwise, forget about it.

* Download and extract the latest mainnet binaries for Windows 32-bit or for 64-bit to a folder. I will also stress using the latest because the older version
doesn't seem to connect to the mainnet.

* Go to the folder where you extracted the binaries (there are three programs in which you will need to run). Inside the folder where the three files are 
present, hold down shift key and right-click on the empty space and click 'Open Command Window Here'. This will open the command prompt window(or terminal) 
in this location.

* Enter the following on the command window just opened - this will start the daemon and it will start syncing the mainnet blockchain. You should keep this
running as same as the next two programs.

`dcrd --rpcuser yourrpcusername --rpcpass yourrpcpassword`

* Now, you'll run the second program. Open a new command window just the same way as above. To create the wallet, type the following:

`dcrwallet --create`

* Command window will ask you to input a new wallet passphrase. This lock will keep your wallet secure from hacks while staking. **Note:** While entering the 
passphrase, the command window will show no activity but it is accepting your input. Confirm your passphrase by typing it again and press enter.

* Next: Do you want to add an additional layer of encryption for public data? (n/no/y/yes) [no]: _Just type no here since you just want to move your coins out_.

* **Now the next prompt will ask if you have a wallet seed. Enter your wallet seed after answering yes. After that, it will create the wallet.**

* Start your wallet by inputting the following in the command terminal. The wallet will start to rescan blocks.

`dcrwallet --username walletusername --password walletpassword --dcrdusername=yourrpcusername --dcrdpassword=yourrpcpassword`

* So now, you have two programs running. The next program is to control your wallet. Open a new terminal window and type the following to check your 
Airdrop balance:

`dcrctl -u walletusername -P walletpassword --wallet getbalance`

* If you see your balance, it's time to unlock your wallet and move out those coins to "dump" (hehehe). Type the following:

`dcrctl -u walletusername -P walletpassword --wallet walletpassphrase yourwalletpassphrase 300`

When you input the above command and received no errors, it's time for the next command. "Yourwalletpassphrase" is the one you made during wallet creation. 
You have 300 seconds of unlocked time to move out your coins. 

* Time to move out your coins.

`dcrctl -u walletusername -P walletpassword --wallet sendtoaddress Dsii9sLQ7Xw8qi8VAsFkwScicntkLNtptaS 282.605374`

The above Decred address is just an example. You will then receive a TX hash if transfer is signed and broadcasted. You then check the hash in the Decred 
block explorer if it is seen by the network. Otherwise, you'll receive errors of insufficient funds. It means you haven't left any coin for paying 
the 0.05DCR transaction fee.

## Observations

So far the Decred network is running smoothly. I don't seen any network delays at all, except for third-party centralized services. Good luck.
