
# TOKENIZATION LLC - An LLC that Mints Tokenized Delaware LLCs

## Abstract

The law is hard, and expensive, to scale.  

Tokenization, LLC makes it as easy as minting an Ethereum Name Service ("ENS") subdomain to "mint" a tokenized Delaware LLC.

It is easy to form 1 limited liability company ("LLC"), but 10? 100? 1000? How about 10000 LLCs?  Delaware filing fees alone for 10000 LLCs would be $1.1M and annual Delaware taxes would be $3M every year thereafter, not to mention any legal and/or registered agent costs.

Using existing laws and blockchain public goods infrastructure, including ENS and CCIP-Read, this project has developed a legal and technical framework to abstract away Delaware fees and scale, on demand, an unlimited number of Delaware LLC's by minting an ENS subdomain that simultaneously generates a LLC Operating Agreement and legally binds the ownership of the Delaware LLC to the ENS subdomain.  

## Benefits of Limited Liability

An immediate benefit that LLCs provide is limited liability legal protections for owners.  In this context, an owner of a self-custody crypto wallet can use a tokenized LLC to minimize the owner's risk of potential liability to the their contributions to the LLC crypto wallet.  

Below are illustrative examples of the legal risks and benefits of limited liability protections in the context of the real world and a example blockchain based counter-part:      

### Real World Example:  
Bob owns a house, a car, a bank account, and crypto wallet wallets. Bob also has a bakery, Bob's Bakery.  Alice slips and falls in Bob's Bakery breaking her bones.  Alice sues Bob personally because Bob did not have an LLC, or other legal entity protecting Bob.  Alice gets a judgment against Bob, which she can collect against Bob's personal assests including his house, car, bank account and crypto wallet.  If Bob had an LLC, then Bob's would not have been a party to Alice's lawsuit, and Bob and his assets would have been protected from the judgment and his liabilities would have beem limited to the amount he invested in Bob's Bakery.

### Crypto Wallet Example:  
Bob owns a house, car, a bank account, and crypto wallet.  Bob purchased the Defi DAO token.  Alice used DeFi DAO DeX to swap some tokens and due to an exploit her wallet was drained of 10 cryptopunks and 100ETH.  Alice sues and in the lawsuit Alice and names everyone with a cryptowallet that holds DeFi DAO token a personal defendant, alledging DeFi DAO was legally a General Partnership and holders of the DeFi DAO token could be subject to joint and several liablity for her damages.  This was the legal issue in [Sarcuni v. bZx DAO](https://storage.courtlistener.com/recap/gov.uscourts.casd.732409/gov.uscourts.casd.732409.49.0.pdf), where the US Disctrict Court ruled the holders of DAO tokens could be subject to joint and several liablility for DAO losses.  This means each if Bob were doxxed or identifiable, he could be personally named in Alice's lawsuit and Alice could then collect the entire judgment against Bob and Alice could even attach Bob's house, car, bank account and crypto wallet to satisfy the judgment.  Then it would be Bob's responsibility to get the other defendants to pay him for their share of the judgment.

In both cases Bob could have used one or more LLCs to protect his assets, minimizing risk for any potenital liabilities.  

![image](https://github.com/ENSpunks/LLC/assets/109005555/a2e8d8fd-f2ce-4e34-ad22-3973c3b208f6)



![image](https://github.com/ENSpunks/LLC/assets/109005555/f43901a2-300e-4358-8fb1-4f5c3a0bdbc4)



## LLC Tokenization

Tokenized LLCs are unique in many ways as an asset, not only do LLCs provide owners limited liability protections where most assets create potential liabilities, they also expand the generally accept definition of asset tokenization.  For example, Chainlink provides the following definition of asset tokenization:

>Asset tokenization involves representing the ownership rights of real-world assets as digital tokens on a blockchain.

If ⬛ were to represent Bob's Bakery and ⬜ were to represent a digital asset like a token, how can ⬜ represent ownership of ⬛ on chain and in the real world?  Is it enough for Bob to say ⬜ represents ownership of ⬛? What if Alice buys ⬜ from Bob, does that really give Alice ownership of ⬛ in the real world?  What if Alice goes to take possession of Bob's Bakery in the real world but Bob doesn't relinquish possession of ⬛, can Alice enforce ⬜ in Court?  Ideally there is a legally enforcable agreement that binds the RWA ⬛ ownership rights to ⬜ on chain, which a court of law would recognize as 🔳.  

What makes LLCs truely unique as an tokenized RWA is not only that ⬛ can provide crypto wallets limited liability protections, as discussed above, but: 1) 🔳 can legally own other assets, both on chain and off chain, represented as 🟦🟩🟧🟥, and 2) 🔳 can otherwise give on chain digital assets legal personhood in the real world, or legal vehicle to enter into legal agreements while providing the owner with the same beneficial limited liability protections.

Lets give a example. Alice owns a NFT 🟦.  🟦 is extremely valuable and as the owner of 🟦 Alice has commerical IP rights for 🟦.  On its own 🟦 can not enter into license agreements in the real world, but as the owner of 🟦, Alice can enter into license agreements for 🟦, but now Alice becomes personally liable for any damages or breaches of said license agreements.  A tokenized LLC ⬛ represented on the blockchain as ⬜ can take legal ownership of 🟦, and now 🟦 has real world personhood represented as 🔲 that can enter into legal agreements such as 🟦 license agreements, protecting Alice from legal risks and potential liabilities.      

In the initial iteration, the purpose of the tokenized LLC is to provide users with limited liability protections for the activities of the LLC wallet.  In future iterations, this framework can scale from millions of existing users, to bringing millions of small businesses on chain, to a the foundational legal and technical framework to help bridge billions of assets between the real world and blockchain.

### Minting a Tokenized Delaware Protected Series Represented by ENS Subdomains

We want to make it as easy for Alice and Bob to mint a LLC as visiting a website and minting an ENS subdomain.  For many users this may be their first experience owning an LLC and owning a real world asset ("RWA") on chain, for others this may be the first experience with a crypto wallet, ENS or token of any kind. Alice and Bob don't need to know any more about about ENS smart contracts and L2, as they do about the Delaware LLC Act, it will just work.

### Oracle - The State of Delaware

In 2017, Delaware enacted amendments to the Delaware General Corporation Law ("DGCL") and the Delaware Limited Liability Company Act ("DLLCA"), allowing corporations and LLCs to use electronic databases, or blockchains, for business records.  Pursuant to the Delaware LLC Act, Tokenization, LLC, shall have the legal right to create one or more protected series with ownership records managed on chain. 

Tokenization of real world assets ("RWAs") presents the Oracle Problem.  Chainlink defines the Oracle Problem as:

>The blockchain oracle problem refers to the inability of blockchains to access external data, making them isolated networks, akin to a computer with no Internet connection. Bridging the connection between the blockchain (onchain) and the outside world (offchain) requires an additional piece of infrastructure—an oracle.

In the initial iteration the State of Delaware, Department of State: Division of Corporations shall serve as the oracle for Tokenization, LLC, a Delaware Series Limited Liability Company. Further, each Series shall have an generative Series Operating Agreement, that may be recorded on chain or stored off chain, using centralized or decentralized storage, and said series Operating Agreements shall act as legal oracles that, in part, legally bind ownership of each series to a ENS subdomain representing the series ownership and govern the series.   

![image](https://github.com/ENSpunks/LLC/assets/109005555/c30b130f-692a-405f-9d70-674033f3b7d6)

## Future

This project establishes a scalable legal and technical framework that may be open-sourced along from the legal contracts to the smart contracts. 

For many users this will be their first experience owning an LLC and a real world asset ("RWA").  In the initial iteration, the LLC can provide users with limited liability protections for the assets and activities of the LLC wallet.

In future iterations, this framework can go meta and scale exponentially and be used to mint ENS subdomaians that mint LLCs that take ownership to RWA's to bring RWA legal title onchain, helping onboard a billion RWAs.   

## Disclosures/Disclaimers

Each series shall be subjected to a Series Operating Agreement, the Delaware Limited liability Company Act, and all other applicable laws.

Each series shall be formed with the express purposes of conducting any and all legal activities.  However, for practical purposes each LLC/Series shall be contractually prohibited from obtaining an EIN from the IRS, opening business bank accounts, or having multiple owners simultaneously. 

As a single-member LLC, by default each LLC/Series is treated by the IRS as a disregarded entity for tax purposes.[1] This means the LLCs/Series generally do not need to file a separate tax return and income or losses are reported on Form Schedule-C of the owner's personal tax returns.

Selling of a LLC, in this case the ENS subdomain, will generally be considered a taxable event and subject to capital gains taxes.  Moreover, it is solely the responsibility of the owner of a Series to retain legal counsel and/or a tax professional, report and pay any and all taxes related to the Series.

*These disclosures and disclaimers are not legal or tax advice but are provided for informational purposes only. Each owner of a LLC/Series should consult with a licensed attorney and tax professional.*

[1] Internal Revenue Service, Private Letter Ruling: 200803004. https://www.irs.gov/pub/irs-wd/0803004.pdf
