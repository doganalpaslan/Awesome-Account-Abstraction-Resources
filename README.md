# Awesome Account Abstraction Resources
![](https://i.imgur.com/FAdi9z9.jpg)


**TL;DR**

Account Abstraction is a hot topic and everyone is talking about it but what is Account Abstraction and why we need it? Is it just a new topic for vc's to cash grab?

If you have questions like this, you have found the right place for your answers.Account Abstraction is popular in nowadays but it has been discussing since like Ethereum's first day. [As Vitalik said:Account Abstraction has been a topic i have been trying to push almost since beginning. When Ethereum launched we wanted people to use Contract Accounts by default ](https://www.youtube.com/watch?v=WsZBymiyT-8) 

So yes, Here is a full list of Account Abstraction resources. 

:::info
:bulb: This document is under development. Last update: D/M/Y
:::


:::info
:video_game: **Hint:** This note is yours, feel free to play around on Github   
:::


### Topics:
* Basic Consepts for understandting how do Ethereum Wallets work
* History of Account Abstraction
  * EIP86
  * EIP 2938
  * EIP 3074 
* EIP 4337 - the last proposal for Account Abstraction
*  Developer Resources for building smart contract wallet with EIP4337
* Protocol level solutions
  * Starknet, Zksync
  * Fuel
  * Near - Sui (They have some solutions at account model instead of having AA at protocol level)
* Youtube, podcast resources
* Other Resources (Threads, discussions)

## Basic Concepts

I highly recommend to read first 8 section of [Mastering Ethereum](https://github.com/ethereumbook/ethereumbook) for understanding Ethereum's account model. 

Learn the validity rules of a single transaction - [Ethereum.org](https://ethereum.org/en/developers/docs/transactions/) 
These two resources are enough for understanding fundamental concepts. 

## History of Account Abstraction

* [A perfect summary written by Nethermind Team](https://medium.com/nethermind-eth/the-history-and-future-of-account-abstraction-10cb097ebdc8 )
* [EIP 86 - Abstracting the transaction origin and signature ](https://github.com/ethereum/EIPs/blob/master/EIPS/eip-86.md)
* [EIP 2938 - Account Abstraction via protocol changes: ](https://eips.ethereum.org/EIPS/eip-2938)
* [Understanding the EIP 2938](https://hackmd.io/@SamWilsn/ryhxoGp4D)
* [EIP-3074 - add AUTH and AUTHCALL opcodes to enable EOA programmability ](https://eips.ethereum.org/EIPS/eip-3074)
* [A case for a simpler alternative to EIP 3074 ](https://ethereum-magicians.org/t/a-case-for-a-simpler-alternative-to-eip-3074/6493)
* [EIP 3074 Impact Study](https://docs.google.com/document/d/1itvPn7BhZ9N8h27d1Ig5C86_FZpyG5_cdpsuPJYmb-o/edit)
* [Ethereum wallets today and tomorrow — EIP-3074 vs. ERC-4337](https://medium.com/nethermind-eth/ethereum-wallets-today-and-tomorrow-eip-3074-vs-erc-4337-a7732b81efc8)


## EIP 4337 - Account Abstraction Using Alt Mempool
* [ERC 4337](https://eips.ethereum.org/EIPS/eip-4337)
* [Account Abstraction Roadmap ](https://notes.ethereum.org/@vbuterin/account_abstraction_roadmap)
* [EIP 4337 ](https://medium.com/infinitism/erc-4337-account-abstraction-without-ethereum-protocol-changes-d75c9d94dc4a)
* [WTF is Account Abstraction Part 1 -  by Argent team](https://www.argent.xyz/blog/wtf-is-account-abstraction/
)
* [WTF is Account Abstraction Part 2 -  by Argent team](https://www.argent.xyz/blog/part-2-wtf-is-account-abstraction/
)
* [WTF is Account Abstraction Part 3 -  by Argent team](https://www.argent.xyz/blog/part-3-wtf-is-account-abstraction/
)
* [Account Abstraction everything you need to know -  by Panther Protocol ](https://blog.pantherprotocol.io/ethereum-account-abstraction-everything-you-need-to-know/
)
* [Account Abstraction The new shiny object in crypto - by Danajwright](https://danajwright.medium.com/account-abstraction-the-new-shiny-object-in-crypto-c94289bd1475)
* [Openzeppelin Account Abstraction Audit ](https://blog.openzeppelin.com/eth-foundation-account-abstraction-audit/)
* [Smart Contract Wallets - by 1kx Team ](https://medium.com/1kxnetwork/wallets-91c7c3457578)
* [The Current state of Account Abstraction - by Garvit Khatri](https://mirror.xyz/0x6C2265693900a68b9c9CBE2d6Eae3bd9336060db/MIThq8Ford5O3b0hDA4LR_tsRteDfazRfpVQXOR3Euk)
* [ERC-4337: Account Abstraction is already here - by Nethermind Team](https://medium.com/nethermind-eth/erc-4337-account-abstraction-is-already-here-e9588b789e15)
* [Account Abstraction Potential with ERC-4337 - by Candide Labs](https://medium.com/@candidelabs/account-abstraction-potential-with-erc-4337-6bf6bf8ab0bf)
* [The power of account abstraction - by Raise Finance](https://raisefinance.medium.com/the-power-of-account-abstraction-technical-overview-of-the-raisepay-wallet-8e8c43dee64f) 
* [Account Abstraction Will Evolve Wallets - by Robert McTague, Amber Research](https://amberlabs.substack.com/p/account-abstraction-will-evolve-wallets)

## Developer Resources for building smart contract wallet with EIP4337
* [Alcemy's Account Abstraction Docs - Part 1  (for me the best resource for developers to start with)](https://www.alchemy.com/blog/account-abstraction)
* [Alcemy's Account Abstraction - Part 2: Paymasters](https://www.alchemy.com/blog/account-abstraction-paymasters)
[Alcemy's Account Abstraction - Part 3: Wallet Creation](https://www.alchemy.com/blog/account-abstraction-wallet-creation)
* [Alcemy's Account Abstraction - Part 4: Aggregate Signatures](https://www.alchemy.com/blog/account-abstraction-aggregate-signatures)
* [EIP 4337 Core Team's 4337 Implementation](https://github.com/eth-infinitism/account-abstraction/tree/develop/contracts)
* [Stackup's 4337 Implementation](https://github.com/stackup-wallet)
* [Biconomy's 4337 Implementation ](https://github.com/bcnmy/scw-contracts/tree/master/contracts/smart-contract-wallet/aa-4337)
* [Candide Wallet's 4337 Implementation](https://github.com/candidelabs/CandideWalletContracts)
* [Soul Wallet's 4337 Implementation](https://github.com/proofofsoulprotocol)

## Protocol level solutions
* **Starknet** (This part is inspired from sylve.eth's article - shoutout to him)
  * [Random thoughts on Account Abstraction - by sylve.eth](https://mirror.xyz/sylve.eth/Un2EYccIpfE3BDevwOf9hWWcSn2NsiRIivZlBLNX7Ag) 
  * [Perama's Notes About Accounts At Starknet](https://perama-v.github.io/cairo/account-abstraction/)
  * [Argent X - Supporting On-chain Games ](https://www.notion.so/argenthq/Argent-X-Supporting-On-chain-Games-1ec71fc2b6ad4fe19b8f22cc677838b9)
  * [Ethereum's broadband moment - by proofedloaf.eth](https://mirror.xyz/proofedloaf.eth/uJYBCOXoq0YfhKh0HrfwbA4yNV-jbvoeFiOnXDhs2Gc) 
  * [Starknet's Account Abstraction Part 1](https://community.starknet.io/t/starknet-account-abstraction-model-part-1/781)
  * [Starknet's Account Abstraction Part 1](https://community.starknet.io/t/starknet-account-abstraction-model-part-2/839)
* **Zksync**
  * [Introducing Account Abstraction by Matter Labs ](https://matterlabs.medium.com/introducing-account-abstraction-l2-l1-messaging-and-more-760282cb31a7)
  * [RaisePay wallet, a native smart contract-based wallet built on account abstraction](https://raisefinance.medium.com/introducing-raisepay-wallet-a-native-smart-contract-based-wallet-built-on-account-abstraction-b724ae4a5dd3)
* **Fuel**
  * [Cami's Account Abstraction article - TBH one of the best resources so far ](https://camiinthisthang.substack.com/p/account-abstraction-for-everyone)
  * [The Power of Predicates: A Purpose-Built Mechanism for Transaction Authorization](https://medium.com/blockchain-capital-blog/the-power-of-predicates-73f874cfa9a5)
  * [Predicates - SwayBook](http://rust.fuel.network/v0.35.1/getting-started/predicates.html) 
* **Near - Sui** (They have some solutions at account model instead of having AA at protocol level)
  * Near's Approach: [A thread by Altan ](https://twitter.com/altanboost/status/1618546846452023297
)
  * Sui's Approach : [A forum discussion](https://forums.sui.io/t/support-for-multisig-and-account-abstraction/244)
* **Polkadot's Approach**: [A forum dicsussion](h[ttps://](https://forum.polkadot.network/t/multichain-friendly-account-abstraction/1298))
* **Cosmos's AA wallet**: [Abstract_os ](https://twitter.com/abstract_os)
## Youtube, Podcast & Resources
* [Starknet CC's Account Abstraction Panel](https://www.youtube.com/watch?v=sbbVCAB--i4&t=20741s)
* [Account Abstraction Panel | Devcon Bogotá](https://www.youtube.com/watch?v=WsZBymiyT-8)
## Other Resources 
* [A twitter Thread by Petejkim](https://twitter.com/petejkim/status/1529604590882234368)
* [An Another Twitter Thread by Petejkim](https://twitter.com/petejkim/status/1527027583254241280)
* [A Twitter Thread by SolomonCrypto](https://twitter.com/SalomonCrypto/status/1612587312638234626)



---


- [ ] [Follow me on Twitter](https://twitter.com/DoganEth)
- [ ] [Support & give praise](https://etherscan.io/address/0x8958d0c419bcdfb8a86b8c0089552be015fbe364)





