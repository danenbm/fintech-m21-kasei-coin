# Kasei Coin

This repo contains the following three Solidity smart contracts:
1. An ERC-20 compliant token called Kasei Coin (KAI).
2. A crowdsale contract from the OpenZeppelin Solidity library that can mint the Kasei Coins.
3. A deployment contract that deploys both the token and and the crowdsale contract.

---

## Technologies

The smart contracts are written in Solidity and compatible with Ethereum-based blockchains.

The contracts were developed and tested using the following tools:
* The OpenZeppelin Solidity library was used to import ERC-20 and crowdsale functionalities. 
* The Ethereum Remix IDE was used to develop, compile, and deploy the code.
* Genache was used to create a local Ethereum blockchain to which the contracts were deployed.
* MetaMask is a digital wallet for Ethereum and was used to link the Remix IDE to the local blockchain.
 * Injected Web3 was used to create a link between Remix and MetaMask.
 * MetaMask was connected to the network created by Genache, and test accounts from Genache were imported into MetaMask.

---

## Evaluation Evidence

Ethereum Remix IDE after compiling KaseiCoin contract:

![KaseiCoin_compiled](Images/KaseiCoin_compiled.png)

Ethereum Remix IDE after compiling KaseiCoin crowdsale contract:

![KaseiCoinCrowdsale_compiled](Images/KaseiCoinCrowdsale_compiled.png)

Ethereum Remix IDE after compiling KaseiCoin crowdsale deployer contract:

![KaseiCoinCrowdsaleDeployer_compiled](Images/KaseiCoinCrowdsaleDeployer_compiled.png)

Genache local Ethereum blockchain:

![Genache_local_network](Images/Genache_local_network.png)

First Genache test account imported into MetaMask:

![First_Genache_account_imported](Images/First_Genache_account_imported.png)

Second Genache test account imported into MetaMask:

![Second_Genache_account_imported](Images/Second_Genache_account_imported.png)

Third Genache test account imported into MetaMask:

![Third_Genache_account_imported](Images/Third_Genache_account_imported.png)

Ethereum Remix IDE after deploying KaseiCoin crowdsale deployer contract:

![KaseiCoinCrowdsaleDeployer_deployed](Images/KaseiCoinCrowdsaleDeployer_deployed.png)

Ethereum Remix IDE showing KaseiCoin contract and KaseiCoin crowdsale contract addresses linked:

![KaseiCoinCrowdsale_and_KaseiCoin_addresses_linked](Images/KaseiCoinCrowdsale_and_KaseiCoin_addresses_linked.png)

Genache local Ethereum blockchain after deployment:

![Genache_after_deployment](Images/Genache_after_deployment.png)

Record of contract creation in Genache

![Record_of_contract_creation_in_Genache](Images/Record_of_contract_creation_in_Genache.png)

Buying KaseiCoin tokens and sending to second Genache account:

![buying_tokens_and_sending_to_second_account](Images/buying_tokens_and_sending_to_second_account.png)

Balance of second Genache account shown in Remix after receiving tokens:

![balance_of_second_account_after_receiving](Images/balance_of_second_account_after_receiving.png)

Balance of second Genache account shown in MetaMask after receiving tokens:

![metamask_balance_of_second_account_after_receiving](Images/metamask_balance_of_second_account_after_receiving.png)

Buying KaseiCoin tokens and sending to third Genache account:

![buying_tokens_and_sending_to_third_account](Images/buying_tokens_and_sending_to_third_account.png)

Balance of third Genache account shown in Remix after receiving tokens:

![balance_of_third_account_after_receiving](Images/balance_of_third_account_after_receiving.png)

Balance of third Genache account shown in MetaMask after receiving tokens:

![metamask_balance_of_third_account_after_receiving](Images/metamask_balance_of_third_account_after_receiving.png)

Total supply of KaseiCoins after sending to second and third Genache accounts:

![total_supply_after_sending_to_third_account](Images/total_supply_after_sending_to_third_account.png)

Total amount of wei raised after sending to second and third Genache accounts:

![wei_raised_after_sending_to_third_account](Images/wei_raised_after_sending_to_third_account.png)

---

## Contributors

Michael Danenberg

---

## License

MIT