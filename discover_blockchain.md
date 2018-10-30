# IBM Blockchain Essentials: BC0101EN: Module 1 - Discover Blockchain

- This course is on @cognitive-class https://cognitiveclass.ai/courses/blockchain-course/ 
- I have made the repo to summerize the skills I have learned in the course.
- I have not shared any quiz/exam answers. 

#### Module 1 - Discover Blockchain
- What is blockchain
- The business backdrop
- The problem area
- Relation to bitcoin
- Requirements for blockchain in a business environment
- Requirements deep dive

##### What is Blockchain
- Business networks today are often inefficient because each participant in the network keeps records, or a ledger, of all transactions between all the parties that the business interacts with. This process is expensive because of duplication of effort and intermediaries adding costs for their services.

- Blockchain provides a shared ledger technology that allows any participant in the network to see the one system of record, or ledger. By using blockchain technology, businesses can benefit from a more efficient transfer of goods and services.

> Related links: 
> [Blockchain overview](https://developer.ibm.com/courses/wp-content/uploads/sites/83/BlockchainOverview.pdf?cm_mc_uid=23535470294415401314130&cm_mc_sid_50200000=47032971540756862995)
> [IBM Blockchain for developers](https://developer.ibm.com/blockchain/?cm_mc_uid=23535470294415401314130&cm_mc_sid_50200000=47032971540756862995)

##### The business backdrop
- Businesses are interdependent. They cannot operateas as an stand alone identity.
- Market could be of two types:
	- Open market: Auction
	- Private market: Supply chain, fruit market, etc
- Assets could also be of two types:
	- Tangible Assests: Car or House
	- Non-Tangible Assests: Digital music or a poece of intellextual property.	

##### The Problem Area
- The current systems that are used to share ledger are: 
1. Inefficient: Each of the different parties in the business needs to run their own form of business process to update their ledger effectively that they are doing that in the duplicate way.

2. Expensive: Each business party needs to do audits that takes an awful lot of time and effort to do that accross the business network.

3. Vulnerable: It's vulnerable to malicious modifications or cyber attack. 


- Blockchain can bring a common ledger that can be shared amoung the business network. Ledger is shared through the peer-to-peer replication technology. 

> Only those two parties who are invovled in that tranactions can see the details. This is what we mean by privacy in Blockchain. 


- Four important points of Blockchain for privacy services and building trust:

1. Consensus: We determine who within the network can validate or approve the tranaction
2. Provenance: This can be thought of as Complete Audit trail of an Asset, who has owned the asset throughout the lifecycle of asset. 
3. Immutability: It's almost impossible to tamper with the blocks once they are actually written. This gives blockchain a property of IMMUTABILITY.
4. Finality: Once everything is committed into the blockchain, we have got one single system of truth accross the business network.

This helps to resolve the conflicts very easily.

##### Relation to Bitcoin
- Bitcoin is a Blockchain which can be thought of as shallow currency.
- Hyperleder basically focuses on Blockchain for business.

- Three important key areas which differ Bitcoin with Hyperledger.
1. Identity over Anonymity: Everyone in the business network knows who they are dealing with.
2. Priortise selective endorsement over proff-of work: We choose, who in the blockchain validates a particular transaction and this is much more computationally effective then the intensive proof-of-work that's associated with proof od work in Bitcoin.
3. Assets over digital currency:  


##### Requirements for blockchain in a business environment
1. Shared Ledger: All the participants in the Business Network have their own copy of sum of this distributed ledger but due to permissioning in the blockchain network, we can control who can see what part of the blockchain. This increases the trust.

2. Smart Contracts: Business logic is implied by the contract.. embedded in Blockchain and executed with Blockchain. Verifiable and signed

3. Privacy: Appropriate confidentiality between subsets of participants.

4. Trust: The way we handle efficiency in business blockchain is the selected members in the network validates the tranansaction. This gives us verifiable audit trail of everything, ie who owned what in the business network.


QUIZ: What are the core requirement for a business blockchain? 
OPTIONS: 
[] Optimized cryptographic mining 
[] Technical services, business services and solution 
[] A new cryptocurrency (x) 
[] Shared ledger, smart contract, privacy and trust 

