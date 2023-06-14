One important property of a collection is the #off-chain Schema. This schema describes the #metadata that is associated with each token and can be accessed by the #token_id. It can be an image, track or a more complex and structured data. For additional protection of token authenticity, the off-chain metadata hash can be recorded in the immutable token metadata. 
Besides the off-chain schema, it is possible to set the similar schemas for #mutable and #immutable NFT metadata that are stored #on-chain. 
The main purpose of the off-chain and on-chain schemas is allowing the **standardised definition of application specific token data**[^1].
Standardization is important in order to set the grounds for #interoperability between multiple chains, but also is flexibility. Unique Network sets the goal to support many standards to stay interoperable and at the same time flexible enough to accommodate new schema standards as they appear. Thus, the Network does not restrict the schema to any format, but allows to select the format out of existing known standards to the moment: ERC-721, OpenSea, or Tezos. The #NFT_wallet s will be able to read the schema #version that is stored #on-chain and display the NFTs appropriately[^1]. 


|   type of metadata  |  off-chain | on-chain | mutable |immutable|
|---------------------|------------|----------|---------|---------|
|          NFT        |            |     *    |    *    |    *    |
| Token of collection |     *      |          |         |     *   |

the #NFT-pallet allows storing the NFT metadata in order to allow more authentic definitions of NFT items, while staying agnostic of this metadata format.