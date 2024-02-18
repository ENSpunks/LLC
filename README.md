
# ENS Subdomains for Owning & Managing Limited Liability Companies 

## Abstract

The law is hard to scale.  It is easy to organize 1 LLC, but 10, 100, 1000, how about 10000 limited liability companies?  

Using existing laws and blockchain infrastructure, including the Ethereum Name Service ("ENS"), this project has developed a legal and tehcnical framework to scale an unlimited number of Delaware LLC's that are individually owned and managed onchain using ENS subdomains.  

We will make it as easy as minting a subdomain to create and "import" the ownership of a Delaware limited liability company ("LLC") into ENS.

## Benefits and Use Cases

### Limited Liabilty

One of the benefits that LLCs provide owners is limited liability protections.  Limited liability protects the owners of a business from the risks of personally liablity for the liabilities of an LLC.  In practice limited liability can protect owners personal assets and minimize their potential loses to the amount they contributed to the business.  Self-custodied assets and accounts effectively turns every wallet address into a business and legal risk, we will illustrate those risks in the context of the real world and a blockchain based counter-part:      

Real World Example:  Bob owns a house, car, a bank account, and crypto wallet. Bob also has a bakery, Bob's Bakery.  Alice slipped and fell in Bob's Bakery breaking her bones.  She sues Bob personally because Bob did not have an LLC, or other legal entity protecting Bob.  Alice gets a judgement against Bob, which she can collect against Bob's personal assests including his house, car, bank account and crypto wallet.  Has Bob had an LLC, Bob's would not have been have been a party to Alice's lawsuit, and Bob would have been personally protected from the judgment above and beyond the amount he invested in Bob's Bakery.

Crypto Wallet Example:  Bob owns a house, car, a bank account, and crypto wallet.  Bob purchased a the Defi DAO token.  Alice used DeFi DAO Dex to swap some token and due to an exploit in the contract her wallet was drained of 10 cryptopunks and 100ETH.  She sues and in the lawsuit names every cryptowallet that holds DeFi DAO token, naming DeFi DAO token holders that are doxxed including Bob and listing John Doe for the undoxxed wallet owners.  This was the legal issue in [Sarcuni v. bZx DAO](https://storage.courtlistener.com/recap/gov.uscourts.casd.732409/gov.uscourts.casd.732409.49.0.pdf), where the US Disctrict Court ruled the holders of the DAO token all had fiduciary duties, the duty of care, and joint and several liablity.  This means each personal can be named peronally and held jointly and serverly liable worth the entire judgment, and in the actual case the alleged loses were in the 10's of millions.  For Bob this means Alice would attach his personal assets to collect 100% of any judgment for the acts of DeFi DAO, and he would be responsible for trying to get the other defendants to reimburse him.



### Limited Liabilty

One of the benefits of LLCs provide owners is limited liability.  In practice limited liability generally means the owner(s) of an LLC are not personally liable for the liabilities of an LLC beyond the amount the owner has invested into the LLC.  Moreover, the LLC can provide limited liability protections to the owner's personal assets from debts and liabilities of the business. The aim of limited liability protection is to encourage greater investment into businesses by minimizing risk and potential liabilities to potential investors.

## Delaware Series LLC

In 2017, Delaware enacted amendments to the Delaware General Corporation Law ("DGCL") and the Delaware Limited Liability Company Act ("DLLCA"), allowing corporations and LLCs to use electronic databases like blockchains for business records. This legislation sets the groundwork for greater security, reliability, transparency, and efficiency and specifically anticipates onchain ownership.  

This project shall utilize the Delaware Series LLC structure, specifically using "protected Series" which do not need to be filed, or recorded, with the State of Delaware, file Delaware annual reports, nor pay Delaware annual franchise taxes.

## ENS as Legal Title

Each Series/LLC shall be created through the a written Series Operating Agreement which shall memorialize and codify the Membership Interest, or ownership, of each Series/LLC as a unique ENS subdomain.  Therefore, legal title of each LLC/Series shall be managed onchain as an ENS subdomain providing a unique and immutable identifier for ownership and management purposes.

## Future

This project establishes a legal framework that may be open-sourced along with the legal documentation. 

This framework could be utilized in the future in combination with oracles like Chainlink using CCIP to take ownership of real-world assets (RWAs) and put legal title on-chain.  In practice this framework can provide the foundation for T-0 settlements as well as the base layer for codifying more complex transactions such as options and drag-along or tag-along rights.

## Disclosures/Disclaimers

Each series is created with the express purposes of conducting any and all legal activities.  However, for practical purposes each LLC/Series shall be contractually prohibited from obtaining an EIN from the IRS, opening business bank accounts, or having multiple owners simultaneously. Effectively, each LLC/Series may be considered a holding company for digital onchain assets, providing owners limited liability protections.

As a single-member LLC, by default each LLC/Series is treated by the IRS as a disregarded entity for tax purposes.[1] This means the LLCs/Series generally do not need to file a seperste tax return and income or losses are reported on Form Schedule-C of the owner's personal tax returns.

Selling of a LLC, in this case the ENS subdomain, will generally be considered a taxable event and subject to capital gains taxes.

*These disclosures and disclaimers are not legal or tax advice but are provided for informational purposes only. Each owner of a LLC/Series should consult with a licensed attorney and tax professional.*

[1] Internal Revenue Service, Private Letter Ruling: 200803004. https://www.irs.gov/pub/irs-wd/0803004.pdf
