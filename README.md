# CryptoPi-Hardware
This repository contains the hardware component of the CryptoPi ethereum wallet.

Below is copied from the README of the main repository (https://github.com/ZhouJas/CryptoPi): 

# CryptoPi 
### Overview: 
In recent years, advances in Blockchain technology have resulted in exciting applications such as novel digital asset classes, smart contracts and more.

The purpose of this idea is to make it easier for people to enjoy the benefits of digital currencies – anonymity, privacy, decentralization, while also being easily able to send and receive money. We believe that participating in the cryptoeconomy is a catalyst for freedom and economic progress and wish to make it as convenient as possible.

We wanted CryptoPi to be as convenient and easy to use as possible, which is why we decided on a physical wallet that would allow for two users to initiate a transaction with just a tap between the two devices. To achieve this, the wallet utilizes a NFC hat capable of reading MIFARE NFC tags containing relevant wallet and transaction data. To further bring convenience, we created an accessible graphical user interface that allows the user to view and manage their cryptocurrency holdings from a web browser, or mobile companion app. 

As a sensitive financial related platform, we also want to ensure that our product has the highest level of security possible. This is why we implemented facial recognition, using OpenCV and Azure's Facial Recognition API to authenticate transactions, to ensure that users are in control of their cryptocurrency

### Features:
  - Hardware wallet that allows users to initiate an ethereum transfer with just a tap between wallets
  - Node.js backend that processes wallet transactions and interacts with the blockchain to transfer Ethereum between participant
  - Wallet supports facial authentication to further improve transaction security 
  - Use of NFC technology to allow for the entire cryptocurrency payment process to be as simple as tapping a debit/credit card
  - Companion web and mobile app that allows users to view their balance and transactions
