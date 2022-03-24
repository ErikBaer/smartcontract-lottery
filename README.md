# smartcontract-lottery
smart-contract and back-end to open up a cash-lottery on the Etherium-Blockchain, implemented with brownie.

To deploy the smart-contract and run the lottery, just install brownie and enter the following information into the file sample.env, then rename it to .env :

WEB3_INFURA_PROJECT_ID
ETHERSCAN_TOKEN
PRIVATE_KEY

Then run the command brownie run scripts/deploy_lottery.py to deploy the smart-contract on your selected network. Enter the contract-address in Etherscan, connect your wallet and enter the lottery.
You can also run the unit or integration tests to see the lottery in action.
