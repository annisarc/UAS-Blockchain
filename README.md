# Simple Storage Dapp
This project is for Abhista and Annisa Blockchain Final Task
# Team Members
- Abhista Rizky Pratama Wibowo (1103184108)  
- Annisa Risqika Camelia (1103184175)
# About our Project
This project is using Solidity,Python,Javascript, Brownie Framework for testing our smartcontract using Python and Ganache for our personal blockchain testing.  
In this Dapp, user can upload and save their document on the blockchain. The Document will stored on the IPFS and the document buffer will be stored on the Blockchain. With this Dapp, the user will always have their document stored on the Blockchain and have a backup document if the main document on the user device is corrupt or deleted. The user only use one Metamask Account and with one account they can store the document on our Dapp.
# How to Run this code
- Install dependencies :
  > npm install
- Install Brownie
  > pip install eth-brownie
- Deploy Smartcontract
  > brownie run scripts/deploy.py --network=ganache-local
- Reset Smartcontract
  > brownie run scripts/reset.py
- Update the frontend
  > brownie run scripts/update_front_end.py
