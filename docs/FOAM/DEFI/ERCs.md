Standards and Interoperability
The Interchain NFT and Metadata Standardization conducted extensive research of NFT token and their Metadata standards. Unique Network aims to comply with this interchain standard and deliver the network protocol that is applicable to and able to describe a wide range of NFT formats known in order to prewire the NFT #interoperability for most if not all known NFT standards, which is explained in detail further.
## ERC-721
ERC-721 is the most popular NFT standard that serves as a base for many standards inheriting its properties. It provides **capability to mint, burn, and transfer tokens**. The methods such as allow and transferFrom enable withdrawing tokens on owner’s behalf. It is also possible to include random data in the transfer transactions and perform safe transfers that verify that the
receiving party (a smart contract) is capable of receiving the NFT token and can handle it by executing a on ERC721 Received #call-back method. All these features are or will be covered by the basic functionality of NFT Pallet, which is in the core of Unique Network.
Also, the ERC-721 standard describes the ERC721 Metadata metadata standard, which includes collection name, token symbol, and token URI. 

> **Collection name, description and symbol (token prefix) are the properties of any Unique collection, and token URI can be set as a part of the #off-chain [[schema]]. Token supply as well as BalanceOf parameters also translate one to one to Unique collection parameters: number of created tokens and balance.**

## ERC-1633
ERC-1633 #Refungible standard is covered by Re-Fungible mode in Unique NFT Pallet.
## ERC-1155
ERC-1155 standard mainly adds batch operations on top of ERC-721. This functionality is not directly changing the data formats for NFT, but is a convenient way to automate and optimize operations on multiple NFTs. Also, even though the batch minting is not explicitly included in ERC-1155, Unique implements this feature as well, and will implement batch transfer operations.
## ERC-994 and ERC-998
Both of them #Delegated_NFT and #Composable_NFT add the relationship layer, e.g. “NFTs are arranged in a federated, tree-like format”. In order to stay efficient while accommodating this functionality, Unique Blockchain will add a pallet that will allow to create directed labeled interconnections between NFTs. The NFT Relations section explains the relationships between NFTs in more detail.
## ERC-809 and ERC-1201
Ownership is a capacious term, which serves as an umbrella for many rights that authorize entities for many different actions. Due to this reason, it is important to create the framework capable of providing granular definitions and enforcements for these authorizations. #Renting_of_NFT described in ERC-809 and ERC-1201 standards are only a small subset of such #authorization s, which will be covered under Advanced Ownership Structure.

### Counterparty
Simple yet flexible Counterparty standard adds the capability similar to ERC-721 to Bitcoin protocol, as well as ERC-1633: #Fractional_Ownership or Re-Fungible. the Unique metadata schemas are fully compatible with [[OpenSea]] standard.

