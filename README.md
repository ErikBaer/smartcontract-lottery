# smartcontract-lottery
This project is a demo of a smart-contract written in Solidity in combination with a back-end written in python / brownie to open up a cash-lottery on the Etherium-Blockchain. It accesses the VRF-Coordiator contract to utilize the Oracle provided by Chainlink for a verifyably random number, in order to determine the winner of the lottery.

To deploy the smart-contract and run the lottery, just install brownie and enter the following information into the file sample.env, then rename it to .env :

WEB3_INFURA_PROJECT_ID,
ETHERSCAN_TOKEN,
PRIVATE_KEY

Then run the command ```brownie run scripts/deploy_lottery.py``` to deploy the smart-contract on your selected network. Enter the contract-address in Etherscan, connect your wallet and enter the lottery.
You can also run the unit or integration tests implemented with pytest to see the lottery in action.

This demo is based on the chainlink-mix repo as presented in these tutorials:
https://www.youtube.com/playlist?list=PLVP9aGDn-X0QwJVbQvuKr-zrh2_DV5M6J
