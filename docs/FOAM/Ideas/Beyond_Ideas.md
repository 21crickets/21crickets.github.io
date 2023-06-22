
> NFT Composability
Composability is a system design principle that deals with the inter-relationships of components. A highly composable system provides components that can be selected and assembled in various combinations to satisfy specific user requirements.Composability in Decentralized Finance is the ability of dApps to interact with each other in a permissionless manner.
- [x] Therefore, decentralized financial services can be combined to form novel and complex financial services.
- [x] This is also known as the Money Lego aspect of DeFi, e.g. Zerion uses MakerDAOS CDP tool so users can borrow and lend tokens. Zerion is also connected to Compound so users can earn interest. Zerion is connected to Uniswap and enables participants to swap their tokens with other tokes.
So, composability of NFT services would be a new additional feature in NFT industry.
There are several major types of the relationship: Association, composition, aggregation, generalization (inheritance) and realization.Unique Network NFTs will utilize these types of relationships, as well as additional relationship properties (such as direction and weights, for example) with the goal to enable application developers to create data models to the required complexity.

> Lending FINANCIAL SERVICE
- [x] DApp could use MakerDAO’s borrowing services as infrastructure for its lending protocol.
- [x] Borrowers may take DAI collagenized loans supported by DApp by a fee.
- [x] Lenders can provide with tokens into smart contracts and get rewards in the form of “mfsTokens” which represent an asset that is contributed to the lending pool.
- [x] Lenders can take as a reward mfsDAI which then can be exchanged to the normal DAI token.

> Utility Across Metaverses
There are opportunities to imbue NFTs with enhanced utility by building functionality that can be used across different applications within multiple metaverses. For example, a previously issued NFT can be turned into an asset in a event release or grant access to future NFTs and experiences, thereby increasing the utility and value of the NFT.

> Bimodal Music Subject Classification
This work presents a bimodal music subject classification method that uses two different inputs: lyrics and user interpretations of lyrics. While the subject has been an essential metadata type that the music listeners and providers have wanted to use to categorize their music database, it has been difficult to directly utilize it due to the subjective nature of song lyrics analysis. We advance automatic subject classification technology by employing a context-dependent language model, bidirectional encoder representations from the Transformers (BERT). BERT is a promising solution to reduce the gap between humans and machines’ abilities to understand lyrics because it transforms a word into a feature vector by harmonizing the contextual relationship between that word and its surrounding words. The proposed model employs two BERT modules as an ensemble to control the contribution of the two modalities. It shows significant improvement over the existing context-independent models on both the uni and bimodal subject classification benchmarks, suggesting that BERT’s context-dependent features can help the machine learning models uncover the poetic nature of song lyrics[^11].
More recently, Choi et al. discovered that user-generated interpretation data is more useful than song lyrics and proposed a bimodal system that benefits from both lyrics and interpretations. This kind of approach showed the potential of using people’s interpretation of song lyrics as an alternative source of subject-related information. The bimodal system verified that interpretations are more useful than song lyrics, while the combination of the two only slightly[^11].

<figure markdown>
![BERT model](../assets/Classification-Lyrics.JPG){ width="800" height=600" align=center }
<figcaption>Fig 10. The proposed bimodal classification framework using two BERT classifiers on the lyrics and interpretation input streams. The fusion of the modalities is performed as a part of the training process by defining the ensemble weight α as a trainable parameter[11].</figcaption>
</figure>

> Engagement and Usability of Conversational Search
conversations consisted of a searcher, who was given a search task, and an intermediary who had access to the internet and was tasked to follow the searcher’s directions and provide feedback only via voice. These conversation recordings are created to help to establish requirements for an optimal conversational search system and demonstrate users’ desires for an aligned discourse with conversational interfaces. Alignment means that the user and the system can match each other’s style of communication in terms of involvement (chit-chattiness, verbosity, enthusiasm) or considerateness (more listening, hesitance,independence). If alignment succeeds, then task execution becomes more efficient[^12].

![Search-Data collected](../assets/Search.jpg)

Fig. 1. Experimental setup: the measurement tools used and the type of data collected

> The Moderating Effect of Active Engagement on Appreciation of Popularity in Song Recommendations
Research has demonstrated that different types of users have different needs when it comes to personalized systems. Factors that have been argued to play a role are user traits and characteristics, such as personality and domain expertise. Within this work we explored the influence of listeners’ active engagement with music, or the extent to which people invest in enjoying music, on the relationship between item popularity and satisfaction with lists of recommendation. Using an online survey built on top of the Spotify API functionality we gathered participants’ most listened tracks and used those to compile playlists containing either popular or non-popular tracks. Our results show that active engagement plays a moderating role on the relationship between popularity and satisfaction, which can more specifically be explained by the extent to which popular songs allow people to discover their musical taste. Where listeners with low active engagement are limited in their discovery by tracks they are familiar with, those with high active engagement can actually use music they are familiar with to further discover their taste. Hence, for low active engagement listeners the most attractive recommendation lists are lists that strike a balance between familiar items and items that enable people to refine their musical taste[^13].
The results showed differences between low and high active engagement listeners in terms of how popularity affects satisfaction with the playlist and how this effect can be explained through familiarity and discovery. For listeners with low active engagement, familiar music prevented them from reflecting on their musical taste (i.e., broadening and/or deepening), so popular music is concluded to only contribute to discovery when low engagement listeners are unfamiliar with the tracks. For them, no effect was found of familiar tracks on the discovery their musical taste. This implies that experts are better able to disregard their familiarity with songs when using them to discover their own personal musical taste[^13].

![Search-Data collected](../assets/Active-Engagement.JPG)

Fig. 1. Multigroup SEMs for participants with high (upper figure) and low (lower) active engagement. Numbers next to the arrows describe standardized coefficients and standard error (between parentheses). Significance is included (∗p < 0.05; ∗∗p < 0.01;∗∗∗p < 0.005). Subjective factors in the models represent: Perceived Popularity, Familiarity, Discovery, and Satisfaction.

> Knowledge Graph

Two key requirements necessary for such Web3 infrastructure are the ability to ensure trust via decentralized consensus and utilize semantic, verifiable asset data for representing complex real world relationships and characteristics (such as ownership, location, business context, etc). Knowledge graphs on the other hand are semantic data networks. Powering systems of Google, NASA, Amazon and others, knowledge graphs are connected graph data structures, best for representing complex assets and their relationships in the real world[^5].

![NFT Knowledge-Graph](../assets/knowledge-graph-finale.png)

The knowledge graphs’ key characteristics[^5].

1. Focus on data connections as "first class citizens" (linked data)
2. Designed to ingest data from multiple sources, usually in different formats
3. Flexible data models, easily extendable

These distinct requirements require two distinct types of technology mentioned above  - blockchains and knowledge graphs.
A knowledge graph is a combination of two things: business data in a graph, and an explicit representation of knowledge. Businesses manage data so that they can understand the connections between their customers, products or services, features, markets, and anything else that impacts the enterprise.Knowledge graphs play a role in anything 360, really: product 360, competition 360, supply chain 360, etc. It is quite common in a large enterprise to have a wide variety of data sources that describe customers[^9].
Here are approaches and movements that represent
cutting-edge thinking about this topic:
>  Data fabric
As we’ve discussed in this report, a data fabric is a design concept for enterprise data architecture, emphasizing flexibility, extensibility, accessibility, and connecting data at scale[^9].
>  Data mesh
This is an architecture for managing data as a distributed network of self-describing products in the enterprise, where data provisioning is taken as seriously as any other product in the enterprise[^9].
>  Data-centric revolution
Some data management analysts2 see the issues with enterprise data management we have described here, and conclude that there must be a significant change in how we think about enterprise data. The change is so significant that they refer to it as a revolution in data management. The fundamental observation of the data-centric revolution is that business applications come and go, but the data of a business retains its value indefinitely.Emphasizing the role of durable data in an enterprise is a fundamental change in how we view enterprise data architecture[^9].
>  FAIR data
Going beyond just the enterprise, the FAIR data movement (findable, accessible, interoperable, reusable data) outlines practices for data sharing on a global scale that encourages an interoperable data landscape[^9].