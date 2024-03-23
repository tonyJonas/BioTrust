# Hackaton - ETHSamba 



<eng>

# BioTrust

## BioTrust Team

## 👨‍🎓 Members: 
- Mariana de Paula </a>
- Heitor Cândido</a>
- Tony Jonas</a> 
- Vinicius Ibiapina</a> 

##  Technologies:
- BlockChain</a>
- 
-
- 

## 📁 Description 

## Business Description:
A digital identity platform that uses biometric data to create and manage secure, immutable identities stored on blockchain. The project has a universal scope, but mainly aims to offer a means for people to prove their identity and access profile data, such as name, identity, and other personal data and have complete access to their medical records. This would help to mitigate some of the biggest challenges faced by the vulnerable population, often not being able to confirm their identity (such as refugees) or not having access to their complete health history, making it possible to promote their integration and well-being.

## Technical Description:
## Categories: Scroll + BuildGuidl + Chainlink
In this scenario we would be able to cover these 3 categories. To do this, we would use the Scaffold-ETH2 infrastructure from the BuildGuidl category, where we would use, in their own infrastructure, React for the front and Solidity for our smart contract. To deploy this contract, we would use Scroll services (Scaffold-ETH2 itself has a deploy service, but we will use Scroll to be able to participate in the category). In this context, we would use Chailink VRF to generate unique and verifiably random identifiers for new user records and Chainlink Keepers to automatically update the status of health records based on a specific interval (e.g. medical status updated or delayed if the person is consulted in the last year) and sending time-based notifications as well.

In short, for the smart contract, we will do it in solidity and use ChainLink services for the cases mentioned above. On the front, we will use React by integrating with the smart contract through etherjs. For the previous items, we will use Scaffold-ETH to be our infrastructure. Finally, the IOT will be responsible for sending the biometrics hash to the front via the MQTT protocol.

## How to Run the Implementation


