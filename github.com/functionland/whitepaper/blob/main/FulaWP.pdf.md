# Ending the Rental Web
Ending the rental web by creating a decentralized cloud alternative, Blockchain-Attached Storage (BAS), that solves the ‘paying problem’ for users and open-source developers

## 1. Abstract
Centralized cloud services offer powerful applications and seamless user experiences, but a provider’s incentives are often misaligned with users. In typical centralized cloud service models, users ‘rent’ the hardware for storage and computation by paying via subscriptions, ads or personal data. For example, when a cloud provider profits through user engagement (e.g., ad clicks), its rational incentive is to draw attention and arouse reactions regardless of the users’ best interests, thereby increasing its ad clicks. Some services provide value for millions of users. But given that cloud providers are expected to generate profits for shareholders, they will shut down a popular service if it cannot demonstrate a viable revenue stream or tertiary strategic advantage. Providers also offer ‘free’ services to attract users while planning to introduce a paid tier system later, fully aware that a substantial number of users who become dependent on the service offered will be unwilling or unable to pay. The Fula Network is a privacy-focused, user-owned, free-to-use open-source platform with a builtin incentive layer designed to reduce, eliminate or invert these misaligned incentives. By doing so, it enables free-to-use applications for users that directly compensate developers. Users on the Fula Network retain total ownership over their data. For example, a free-to-use streaming service on the Fula Network can provide personalized recommendations based on a user’s usage data. But that data remains in the owner’s possession and is inaccessible to the streaming application.

## 2. Introduction
We don’t own our own data. We are unable to control what happens to it (AUXIER et al., 2019) (HUQ,2021). Companies launch services for the data that matters most to us, like pictures, passwords and videos, then monetize those services (Slynchuk, 2021) by using ads, or imposing subscription fees, or harvesting our data (Google AdMob, 2018). They control when and how we access our own data, and remove our access whenever they decide to (AMADEO, 2019) (Lyons, 2021). Furthermore, in order to maximize monetization and still protect our data, they lock it into their services, forcing us to store our data in islands of storage tied to each company (Wheeler, 2020) (Lyons, 2021) (Hagiu & Wright, 2020). This is inefficient and creates duplicate data. Moreover, for many companies, protecting this personal data creates liabilities that eat into their resources (Irwin, 2021). Decentralization has become mainstream in financial applications (Maksimenka, 2021), liberating - at least partially - those who use them from the risks involved with banks owning their data (Cordell, 2021). Many financial services are moving from centralized proprietary systems to decentralized, open systems. The fees imposed by DeFi applications in the financial world are acceptable when compared with traditional banking fees (Werbach, 2021). Many protocols are designed to expand the application of decentralized networks beyond DeFi, such as IPFS by Protocol Labs, GUN ecosystem and Dfinity, and transition us from the current Web2 experience into Web3.0 with benefits that are no secret to anyone. However, Web3 in general has not gained the popularity it deserves, mainly because fees and user experience combined are still not comparable to cloud (Nystrom, 2021). On the other hand, while we are trying to decentralizethe web, we lack sufficient decentralized infrastructure even for DeFi. More than 70% of Ethereum nodes are hosted on AWS (Malwa, 2020) and China alone used to control more than 50% of mining nodes for Bitcoin (SUBERG, 2020), which defeats the purpose of not having a central authority.

Why are people so slow to adopt infrastructure decentralization? Because setting up decentralized nodes is a laborious, complicated and time-consuming activity (Newman, 2021) (De Meijer, 2020). Furthermore, networks impose fees on end-users or developers who want to use or publish decentralized applications outside DeFi. Yet eliminating infrastructure costs for application developers and end-users plays a key role in encouraging open-source dApp development and use, leading in turn to a diverse set of dApps and mainstream adoption of decentralized web by end-users, who would find themselves looking at free, functional alternatives to traditional applications (IPEG, 2016).
The Fula network is a plug-n-play dApp server, a blockchain and a protocol token. The dApp server gives users total ownership of their data, devoid of technical requirements. The blockchain runs as Ending the Rental Web 3 a layer 3 blockchain, and employs a newer kind of proof called PoR (Proof-of-Resource). Miners who provide storage, computer resources and time submit proofs to the Fula network; the miners who submit the best proofs are elected to an asynchronous, byzantine, fault-tolerant consensus group at a fixed epoch. In addition to blockchain protocol, the Fula protocol Suite provides a zero-net compute and storage transfer system between Box Devices and resources via a network of independent providers that does not rely on a single coordinator, where:

1. Devices pay to use storage and CPU power from a pool or use a decentralized application;
2. Miners earn tokens for providing CPU and storage resources;
3. Miners earn fees from transactions, as well as for validating the integrity of the Fula network; and
4. dApp developers earn tokens for providing dApps to the Fula network.

## 2.1 Market overview
### 2.1.1 The Paying Problem
In the existing cloud service model, an entity provides the hardware infrastructure. This entity may own the infrastructure (e.g., Google Photos) or rent it out (i.e., cloud services running on AWS, Filecoin, etc.). In either case, the entity provides the infrastructure as a service, and someone must pay.
Even if a cloud service developer wishes to provide a free service, it has to pay the infrastructure cost (e.g., AWS) and must, in turn, recoup that cost from users. This prohibits any possibility for free-to-use, open-source alternative cloud services, unless the cloud service developer goes back to monetizing the user’s data or attention. In other words, as long as developers and users are forced to rent the computing and storage infrastructure, the paying problem will continue to exist.

### 2.1.2 Cost and Convenience
Cloud service providers enable easy-to-use services that spare end-users from hardware considerations such as cost and setup.
In comparison, a personal server (e.g., NAS) typically requires a high level of technical expertise and significant time to set up, install and maintain (Avast, 2020). And even when it is up and running, a personal server does not provide data redundancy without a separate setup or manual backups.
Cloud services also took costs away from the end-user. For example, when Gmail entered the mainstream in 2004, the fact that it gave new users 1GB of free storage was considered remarkable. But since then we have seen dramatic drops in computation and storage costs. In 2000, a gigabyte of storage cost $10.00 (Human Progress, 2014). As of 2022, costs have dropped to under $0.03 per gigabyte (Cloudwards, 2022). Today, the equivalent computing power of an early 2000s PC (Intel, 2022) can be matched by a single-board computer like the Raspberry Pi (Raspberry Pi, 2022). Costing as little as $35, the Raspberry Pi can run 24/7 while consuming a fraction of the energy required by its PC equivalent. 
By combining affordable, energy-efficient hardware with plug and play software, Functionland is enabling a user-owned network that is inexpensive, private and easy to use. The network enables data availability and redundancy with no need for manual backups or multiple devices. 

### 2.1.3 Utility

Users own the hardware that comprises the Fula Network. Their hardware creates value in the form of shared resources (storage and computation) for which they receive tokens. This covers the cost of their own resource usage. Developers bear no infrastructural costs and do not ‘rent’ hardware from users. Rather, they are compensated for providing utility in the form of applications, and they receive tokens based on app usage. In this way, developers are incentivized to build free, open-source applications on the platform.

#### 2.1.3.1 Fair Usage
The network’s utility depends on fair usage among all participants. We verify genuine resource-sharing and usage among users while maintaining privacy with zero-knowledge (Feige, 1988) (Chalkias, Konstantinos 2017) using PoR (Proof-of-Resource). The utility provided and received can be measured, and is attributed a token value on a distributed ledger. This ensures resource sharing among users, resulting in a net-zero transaction.

### 2.2 Enabling Open-Source Development
Most open-source projects do not enjoy financial support. This is paradoxical, considering that opensource projects are the foundation of the information economy, with an estimated 70% of all code is open-source produced (Synopsis, 2020). In most cases, they are created by individuals who must hold a second job to support their open-source work. With a great deal of responsibility and stress, little thanks and zero financial compensation, burnout is widespread among maintainers. As a result, even successful and widely used open-source software packages that provide value to millions are often abandoned by their core maintainers. This in turn produces vulnerability and obsolescence issues. Colors is among the popular projects that were abandoned. Furthermore, the lack of support makes it hard for the maintainers of many popular projects to continue the support (Gallagher, 2016) In addition to monetary support, the Fula Network provides secure, open-source primitives that enable application developers to rapidly build peer-to-peer, open-source, decentralized applications using any programming language, for example JavaScript. We abstract away Web3 complexities in software packages that Web2 developers can easily work with.

## 3. The Fula Network
Note: Sections are subject to frequent additions and changes as Functionland continues its research.
By default, a user engages with the Fula Network as both a resource consumer (apps, storage, content, etc.) and a resource provider. A user can use services on the network without owning a connected device, however, interacting with the network without a connected device means the user will end up paying rent to Box owners. Our primary goal is to incentivize a robust network comprised of user-owned hardware instead of the subscription-based model currently employed by Web2 infrastructures.

### 3.1 Blockchain
#### 3.1.1 Design Ideals
One of the criticisms of some blockchain technologies (e.g., Bitcoin) is that the security mechanism can work against its goal of decentralization. Miners benefit from economies of scale, which can lead to infrastructure centralization. For example, a PoW miner with access to free hydroelectric power has every reason to create as large a mining farm as possible. With Proof of Stake, centralization of infrastructure can occur out of convenience, as stakers choose to run their node on AWS or similar cloud infrastructure, which can weaken the network’s resilience against attacks. The purpose of the Fula Network is to provide useful resource sharing among users. Therefore, the incentive mechanisms encourage a network founded on user-owned hardware. To achieve this, the incentive model reduces the benefit of staking a large number of Fula tokens on a single device.
Running a server farm will be less advantageous than running individual nodes spread geographically. Another criticism of Proof of Work is energy waste. The energy in validating proofs presents no other utility. Almost the entire purpose of the Bitcoin network is to verify transactions for its tokens. In the Fula Network, we utilize shared resources such as computation and storage to verify transactions. Since verification is gained from that utility with no other energy expenditure required, it comes at a negligible energy cost. The Fula network does not have its own ledger. Instead, a three-layered chain agnostic system works by aggregating and streaming Fula pools in a stepwise process.

#### 3.1.2 Open-Source Incentivised
The Fula Network’s incentive layer enables a monetization mechanism for open-source application development, including compensation for any upstream dependencies in a given project. We offer tooling for front-end developers, so all front-facing platforms are supported, PWA, Native iOS and Android, Traditional Web pages, etc. For example, a JavaScript developer can import our SDK in their app, and start developing web3 applications without requiring to go through deep learning curves of web3 and blockchain. They would then get paid from the ecosystem, whenever someone uses their app. Additionally for base library coders, the code writer (e.g. of react library), gets paid whenever another developer uses their library in their application. So if a developer’s gitHub code is used in other libraries or code, they still get paid as long as they have a Fula wallet assigned. So when an app is used by a user, the dependencies are read compensations are distributed like so:
- 25% to content creators
- 25% to content curators
- 10% to Fula network
- 40% to upstream development dependencies


## 3.2 Layer designations on the Fula Network

**The Fula L3** PoolChain uses Proof of Resources to verify all transactions on a given Pool. Network interactions and their rolled-up proofs are submitted to the Pool’s L2.

**The Fula L2** maintains an account of Fula tokens across all pools on a given L2. L2 is multichain and includes individual chains such as Polkadot, Cosmos and Algorand, as well as rollups such as Arbitrum, Polygon, etc. L2 acts as a partial ledger and fees are based on the L2 chain selected.

**The Fula L1** is the Global Ledger of the Fula Token on Ethereum. Fula tokens can be bridged from Ethereum to any chain or rollup via a 1:1 mapping of ERC-20 tokens. L1 will outline halving and minting of Fula tokens.

### 3.2.1 Fula L3 Pools (the base layer)
A pool is a network of devices (i.e. nodes) that connect to share resources. Each resource transaction within a pool is verified using PoR (Proof Of Resources). A batch of transactions is then rolled up and submitted to a Fula L2 Chain.

#### 3.2.1.1 Data Availability on an L3 Pool
Pools are typically formed based on geographical proximity. This allows a user within the pool to share resources (storage, compute, data/content) with as few as 2-4 hops (i.e., user1 - isp1 - isp2 - user2). This enables server response times that can match and likely surpass that of centralized cloud services (i.e., user1 - isp1 - RegionalServer1 - CentralServer - RegionalServer2 - isp2 - user2).

Users who are using the same ISP would be in the same pool, unless there is no one else in that pool. In that case, the user would select another pool, guaranteeing that there is only one other node between that user’s Box (that user’s ISP) and the other Boxes.

#### 3.2.1.2 Mining and rewards
L3 Nodes mine tokens based on uptime and resources provided to peers.

Devices in a pool that actively (verified) providing resources receive Fula corresponding to the L2 chain they have selected. Fula tokens are released when an L3 validator issues a Proof of Storage (Kamara, 2013) certificate.

The Fula network offers a utility sharing reward on top of the validation reward that other networks such as Helium provide. This sharing reward is non-dilutive and unlike the mining reward, does not decrease when more users join the ecosystem (an issue for late adopters on some other networks). Everyone conducts validation and the Box owner can earn more by allocating resources to the pools. Each pool has its own criteria for required allocation of resources to join. For example, a pool with a replication factor of 2, requires the user to allocate 2GB to the pool for each 1GB of storage they use and guarantees at least two other copies of the user files exist.

#### 3.2.1.3 Parameters for Creating or Joining an L3 Pool
Any user can easily join an existing Fula L3 Pool, or create a new one. We have designed the system for simple setup using a mobile app. A user may also manually join or set up a pool according to different parameters, for example:
• by geographical proximity (i.e. by suburb, city, country, kilometer radius, etc.);
• based on the L2 used;
• based on the degree of data replication (i.e. 2x backups, 3x backups, etc.);
• by creating a private pool composed solely of their chosen contacts or their own devices.

Fula network pools share storage and computing tasks:
• Storage jobs for backup and data replication. A copy of one file might be chunked and distributed on multiple Boxes, meaning it resides on one other Box in full.
• Compute jobs share CPU resources on CPU intensive jobs. For example, training AI to recognize faces in the Photos app. This acts as a distributed implementation of map reduce.

### 3.2.2 Fula L2
The Fula Network leaves the ledger technology, consensus and security of transactions up to other (L2) chains that specialize in that domain. Various chains may function as a Fula L2 by bridging ERC-20 Fula tokens from Ethereum. If a superior chain enters the scene, the Fula network can easily integrate it as a ledger, therefore the Fula Network aims to be multichain. A user who is creating a new L3 pool can choose their preferred chain to function as a given Pool’s Fula L2. Users joining an L3 Pool can also select a pool based on their preferred chain.

The L3 Fula Pool submits a sum of its resource transactions to its Fula L2 over a given period (e.g. 24 hours). The L2 ledger distributes tokens within a pool based on resources provided and used during that period. Development on the Fula network does not depend on any particular L2 chain; any underlying chain can sustain the apps and interactions from L3.

Similarly to a developer, if a user changes the L2 chain, it does not affect their experience on the network. All identities and shared files are available on the newly selected chain. After a switch, the user receives rewards in Fula tokens on a newly selected L2 chain. Users can swap tokens across all implemented L2 chains, and Fula tokens will be present on all L2 chains.

Lastly, identity and token data resides on the L2 chain, therefore network security does not depend on L3 network availability; identity, token rewards and ledger data are secure on the L2.

### 3.2.3 Fula L1
Fula token genesis will occur on Ethereum. Ethereum acts as the global ledger for all Fula tokens in existence. Fula ERC-20 Tokens can be bridged from Ethereum to a smart contract on a Fula L2 chain. Ethereum gas fees are not applicable to Fula Network users.

## 3.3 Blockchain
### 3.3.1 Design Ideals
One criticism of some blockchain technologies (e.g. Bitcoin) is that the security mechanism can work against its goal of decentralization. Miners benefit from economies of scale, which can lead to infrastructure centralization. For example, a PoW miner with access to free hydroelectric power has every reason to create as large a mining farm as possible. With Proof of Stake, centralization of infrastructure can occur out of convenience, as stakers choose to run their node on AWS or similar cloud infrastructure, which can weaken the network’s resilience to attacks.

The purpose of the Fula Network is to provide useful resource-sharing among users. Therefore, the incentive mechanisms encourage a network founded on user-owned hardware. To achieve this, the incentive model reduces the benefit of staking a large number of Fula tokens on a single device. Running a server farm will be less advantageous than running individual nodes spread geographically.

Another criticism of Proof of Work is energy waste. The energy in validating proofs presents no other utility. Almost the entire purpose of the Bitcoin network is to verify transactions for its token.

The Fula Network, by comparison, utilizes shared resources like computation and storage to verify transactions. Since the verification is gained from that utility with no other energy expenditure required, it comes at a negligible energy cost.

### 3.3.2 Proof of Resource
Proof of Resource (PoR) is a combination of two verification mechanisms: Proof of Utilized Storage and Proof of Compute.

In most blockchains, a node functions solely to secure the network. Therefore its energy (as in the case of PoW) or network activity (as in the case of PoS) is produced to secure the network.

The primary function of a node on the Fula Network, however, is to share useful resources such as storage and computation. We take these intrinsically-useful resources and utilize them for verification. This enables verification with a negligible additional energy cost which can be executed on energyefficient devices.

Additionally, Proof of Resource (MaidSafe, 2018) takes already-useful resources employed on the network - such as shared data and shared storage - and leverages those for verification. This means that we are not rapidly decreasing storage lifetime by rewriting data over and over again onto it.

### 3.3.3 Proof of Utilized Storage
While storage has been used in other blockchains as a method for verification, the data stored is arbitrary and created solely to provide security. This drastically reduces the lifetime of storage media
and expends energy while serving no other function.

Proof of Utilized Storage (2) produces proofs from the storage, sharing and usage of data on the network with zero-knowledge. This makes data on the Fula Network intrinsically useful.

The mechanism guarantees fairness, ensures that a chunk of data is replicated and available on the network, and helps maintain a ledger of storage shared and used at the incentive layer.

#### 3.3.3.1 Ensuring Data availability through Proof of Utilized Storage
A user may have one or more data backups on other devices in an L3 Pool. With automatic checks, even a single backup can provide a high level (99.99%) of data security.

#### 3.3.3.2 Verification flow
• Devices that store a backup of another user’s data must frequently submit a proof of utilized storage (i.e. every N hours).
• If a device fails to submit a proof at the allotted time, the network recognizes that a designated backup is unavailable. Token payments for the original backup are ceased and another candidate is found in the pool to back up that chunk of data.
• In the event a user has a single backup, the user’s own data is used as the source for replication.
• The new party sends a proof and receives a token payment. 

### 3.3.4 Proof of Compute
Proof of Compute is primarily a distribution mechanism, though it also acts as proof that the compute was correctly carried out. This is verified either with mathematical proof, or through replication.

Proof of Compute is essentially a map-reduce compute job. For example, if users want to train an AI model to recognize a face among their private photos, they can distribute the job to 100 other Boxes, where the computation itself can verify that computation was provided.

## 3.4 Hardware
One primary aim of the Fula Network is to build a thriving network founded on user-owned hardware. Combined with our incentive layer, we can enable free-to-use utility, applications and services to users, while compensating the developers and content creators who create and provide them.

We provide installers for different operating systems so that a user can set up almost any device as a node, including with install packages. But even with these advantages, setting up a personal server requires a much higher level of technical knowledge and time than most people can manage or are interested in. To maximize accessibility, we are removing technical expertise and time from the equation by introducing our plug-and-play hardware solution: Box.

### 3.4.1 Box
Box is an open-source, plug-and-play node. It comprises a base that can accommodate up to nine individual modules called ‘Towers’. It is open-source and composable, using standardized dimensions with all I/O utilizing USB-C.

It enables a composable, open-source hardware ecosystem available to any organization, project, or hobbyist, with a plug-and-play configuration that can securely interact with the Fula Network.

The modular design (Appendix 1) allows additional functionality and composability between towers. It comes with Linux and Fula protocol installed. An app for iOS and Android will support Box, simplifying setup and maintenance; providing a connection wizard for home wireless systems; and enabling OTA updates via Bluetooth.

Box will also function as a standalone tower. This version, which we have named “Box-Lite,” does not include storage, allowing users to use their 2 x USB-C Storage devices to store encrypted files and data on a Fula Pool. A storage expansion card such as the Frame.work 250GB or 1TB expansion can also be added.

#### 3.4.1.1 Other devices on the network
While low-power SBC devices minimize hardware and energy costs while providing enough power for most network activities, the Fula Network aims to facilitate even greater compute-heavy jobs, like AI. For example, for specific tasks, a gaming PC could provide more computing power than a cluster of 100 Boxes and will be compensated proportionally.

Users are able to install a Fula software package and use their personal laptops or PC’s as a Box. This, however, has a few innate disadvantages, for example:
• a laptop would consume more power than a Box;
• a laptop might not be as convenient to leave on for extended periods of time;
• a laptop requires a software installation step.

#### 3.4.1.2 Box real-life utility examples
One Box use case example can be understood by looking at the lifecycle of the Google Photos application. Google Photos was initially marketed as a forever-free application, but after years of accumulating users, the company removed the free tier, forcing all Google users to pay at some point. Ownership of a Box guarantees that a free application will remain free forever. The developer is still getting paid, but this payment is not coming out of the user’s pocket.

Today, in order to view streaming services like Netflix, users are forced to send all their personal information to company servers so that the streaming service can generate custom-tailored content and movie suggestions. But Box maintains all its user’s personal information directly on its own hardware. In this case, the streaming service sends movie information to the user’s Box, and the Box suggests which movies to watch. The user’s personal data and information never leave the premises.

## 3.5 Fula Protocol Suite

The Fula Protocol Suite is an abstraction layer that enables front-end developers to build dApps using their existing knowledge and within the client-server paradigm. For example, a developer familiar with front-end dev tools such as CoreJS and React Frameworks can immediately begin building Web3 apps using the Fula Protocols.

The Fula Network’s file system is IPFS. We utilize a private IPFS network for a user’s private encrypted data, providing full access management such as contact-specific permissions and revocable access. A user’s data is included within the private IPFS network by default. For sharing and greater availability, data can use the public IPFS network.

IPFS was created to form a mesh network among devices. However, running a mobile device as an IPFS node significantly impacts CPU, battery and storage. We adapt IPFS to the Client-Server model, repurposing Libp2p so that it replaces HTTP as the wire protocol. We use the Fula Protocols to differentiate the client (e.g. a user’s mobile device, IOT device, Laptop, etc.) from the server (i.e. a dedicated L3 Node such as Box). This way, storage, CPU and energy requirements can be offset from the end-user’s mobile device and onto their dedicated Fula Node. This enables secure and efficient sharing of files, JSON data and computation without any additional load on the user’s mobile devices.

### 3.5.1 File Protocol
The Fula Network does not store data on-chain. ‘File Protocol’ utilizes IPFS, a distributed file system that gives users control over where their data is stored (i.e. in the Pool that they joined and nowhere else).

Transactions are free on IPFS, creating an incentive problem. For example, on IPFS users have no implicit reason to keep data stored on the network. Fula’s File Protocol acts as a transaction layer on IPFS, addressing this incentive problem by attributing value to data retention as a utility. Since users also provide the same service to others on the network, the transaction is essentially ‘free’ ( i.e. net-zero) for users.

### 3.5.2 Graph Protocol
The Graph Protocol enables developers familiar with Rest APIs to access their data through GraphQL queries. This facilitates easier migration and implementation without the need to define schemas.

### 3.5.3 AI Protocol
The same technologies that power Web2 data centers can be distributed and democratized in order to make the technology accessible for everyone. The Fula Network enables distributed MapReduce on consumer-grade hardware. This enables a graph of computation with a backdrop mechanism that enables AI, Language models, GPT3, etc. (The same technology used by some distributed Data Unions.)

## 3.6 BAS (Blockchain Attached Storage)
The Fula Protocol Suite addresses the fundamental limitations of NAS (Networked Attached Storage) by enabling plug-and-play home servers with NAT hole-punching.

NAS requires an elevated level of knowledge and time to set up and manage. Backups are local, and any attempts to provide further replication must be set up manually. While there are plug-and-play NAS servers, users must access their files through a proprietary, centralized gateway. Since the data passes through a centralized relay, it sacrifices privacy, thereby undoing what is arguably the most significant advantage NAS has over centralized cloud providers.

Using the Fula Protocol Suite to network personal servers, a user can securely and privately back up data at multiple locations without any additional setup. With high data availability and geographical distribution, backups are exponentially more secure than a manual backup solution. And with an open-source architecture, we enable a new platform on which to build free-to-use, privacy-focused applications.

# 4. Tokenomics

The Fula Network effectively serves as a decentralized content distribution channel that can include all digital content, i.e. mobile applications, apps, services and more. Paring storage with computation enables the processing and customization of served content. And by replacing a centralized distributor with a user-owned decentralized platform, rewards can simultaneously compensate users for sharing content, as well as compensate developers and content creators for producing it.

Many consumers will always choose convenience and cost over all other considerations. One example of this is BitTorrent, a free, peer-to-peer file-sharing protocol that has survived for more than two decades, defending its position as a “competitor” with Web2 content streaming services (e.g. Netflix, Hulu, etc.) despite concerted efforts to shut down and seize its centralized distribution channels (e.g. Piratebay).

Please note: the Fula team does not endorse piracy or any other illegal file sharing practices.

However, as a distribution channel, the primary economic critique of BitTorrent is that it fails to reward content creators. And as a distributed network, BitTorrent’s main failing is that it lacks an incentive model to encourage nodes to share (seed) content. Node operators have nothing to gain from sharing, and in many instances may even incur legal penalties for doing so. As a result, obscure data or files can get lost as users cease sharing the file from their devices. The result is a heavy imbalance between content providers (seeders) and users (leechers).

The Fula token, coupled with Proof of Resources, operates as an incentive layer that empowers sustained, long-term sharing of resources (content, applications and computation) on the network. Finding the optimal approach will require ongoing research to ensure that users are incentivized to contribute as well as consume. And also to ensure that app developers and content creators are compensated for the value they provide.

Staking rewards will be dependent on the size of the network and hardware distribution. Using Proof of Resources, nodes providing utility will gain rewards. Earned FULA tokens are available to users to claim. Claimed FULA tokens are unlocked and users have the option of staking their FULA tokens in order to earn more rewards on them.

### 4.0.1 Utility-based Token Transactions
There will be more than one token flow on the Fula Network. Here is how we currently envision the utility-based token transaction:
1. A user downloads and uses an app on the Fula Network.
2. That user’s resource usage is measured (PoR) and given a value (1 Fula).
3. A percentage (e.g. 70%) of that 1 Fula is paid to those users who provided the resources received (i.e. app data).
4. The remaining 30% is paid (distributed hierarchically) to the app’s developer and software dependencies.
5. For example, 70% (0.21 Fula) could go to the app author.
6. The remaining 30% (0.09 Fula) would go to the app’s next level of dependencies.
7. If a package has its own dependencies, these too will be rewarded at a similar 70/30 ratio from the 0.9 Fula amount.
   
In the case of a Github-based project, compensation in Fula tokens can be claimed by committing a configuration to the project.

# 5. Roadmap
Q1 2022
- Indiegogo Launch
- Photos app on Google Play
- Devkit PCB design done
- Seed round closed (done)
- Onboard Raspberry Pi Hobbyists
- Expand marketing efforts by having tg, twitter, discord and linkedIn CMs and press-release

Q2 2022
- Protocol MVPs
- Partnerships Announcements
- Certifications on hardware

Q3 2022
-Testnet Launch
- Community Growth through organic media outreach and partnership building
- Integrations with first level 2 blockchain
  
Q4 2022
- Grant Program kick off
- First Hackathon launch
- First batch of Box shipped
- Mainnet Launch
  
Q1 2023
- Online store for Box
- Hardware partnerships
- Fixing Hardware distribution channels through partnerships

2023
- Compute / Machine
- Learning Protocols
  
2024
Layer 4 Tokens


# 9. Disclaimer

## 9.1 Further Research
This current version of the Fula Network whitepaper is the result of collaboration across the Functionland team. Research is ongoing as of publication, and we will continue to update sections with greater design detail moving forward.
Our design is influenced by our core belief in a future that replaces ‘don’t be evil’ with ‘impossible to be evil’. A decentralized network composed of user-owned devices is a clear solution to the ‘paying problem.’ We remove the need to rent from a third party, aligning incentives among users (who own the network) and the open-source developers and contributors who provide utility across it. In this way, we will enable the benefits of centralized cloud services while liberating them from the ‘evils’ inherent in a model that relies on capturing a user’s private data or attention in order to make money.
As we progress, we will seek the best path to finally compensating open-source contributors for the value they bring to our shared digital world.

# 11. References
AMADEO, R. (2019, 2 4). Google’s constant product shutdowns are damaging its brand. ARS Technica. Retrieved 11 9, 2021, from https://arstechnica.com/gadgets/2019/04/googles-constant-productshutdowns-are-damaging-its-brand/

AUXIER, B., RAINIE, L., ANDERSON, M., PERRIN, A., KUMAR, M., & TURNER, E. (2019, 11 15). Americans and Privacy: Concerned, Confused and Feeling Lack of Control Over Their Personal Information. EWRESEARCH CENTER. Retrieved 11 9, 2021, from https://www.pewresearch.org/internet/2019/11/15/ americans-and-privacy-concerned-confused-and-feeling-lack-of-control-over-their-personalinformation/

Avast (2022). How to set up a server for a small or mid-sized business. https://blog.avast.com/setupserver-business-avast

Chalkias, Konstantinos. “Demonstrate how Zero-Knowledge Proofs work without using maths”. CordaCon 2017. Retrieved 2017-09-13.

Cloudwards (2022). Understanding Cloud Storage Pricing in 2022. https://www.cloudwards.net/understanding-cloud-storage-pricing/

Cordell, R. (2021, 11 3). Decentralized finance (DeFi). Ethereum. Retrieved 11 9, 2021, from https://ethereum.org/en/defi/

De Meijer, C. R.W. (2020, 02 29). Remaining challenges of blockchain adoption and possible solutions. finextra. Retrieved 11 08, 2021, from https://www.finextra.com/blogposting/18496/remainingchallenges-of-blockchain-adoption-and-possible-solutions

Feige, U., Fiat, A. & Shamir, A. Zero-knowledge proofs of identity. J. Cryptology 1, 77–94 (1988). https://doi.org/10.1007/BF02351717

Google AdMob. (2018, 11 19). 5 monetization strategies for your app. Google AdMob. Retrieved 11 9,2021, from https://admob.google.com/home/resources/5-app-monetization-strategies-to-grow-andmonetize-your-app/

Hagiu, A., & Wright, J. (2020, 2 1). When Data Creates Competitive Advantage. Harvard Business Review.Retrieved  11 9, 2021, from https://hbr.org/2020/01/when-data-creates-competitive-advantage

Human Progress (2014). Average cost of hard drive storage per gigabyte. https://www.humanprogress.org/dataset/average-cost-of-hard-drive-storage-per-gigabyte/

HUQ, A. Z. (2021, 10 25). Who Owns Our Data? Boston Review. Retrieved 11 9, 2021, from https://bostonreview.net/law-justice/aziz-z-huq-who-owns-our-data

Intel (2022). Intel® Pentium® III Processor. https://ark.intel.com/content/www/us/en/ark/products/27529/intel-pentium-iii-processor-1-00-ghz-256k-cache-133-mhz-fsb.html

IPEG. (2016, 11 5). The total cost of ownership of open source software. Intellectual Property Expert Group. Retrieved 11 9, 2021, from https://www.ipeg.com/the-total-cost-of-ownership-of-open-sourcesoftware/

Irwin, L. (2021, 6 10). How much does GDPR compliance cost in 2021? IT Governance European Blog. Retrieved 11 9, 2021, from https://www.itgovernance.eu/blog/en/how-much-does-gdpr-compliancecost-in-2020

Kamara S. (2013) Proofs of Storage: Theory, Constructions and Applications. In: Muntean T., Poulakis D., Rolland R. (eds) Algebraic Informatics. CAI 2013. Lecture Notes in Computer Science, vol 8080. Springer, Berlin, Heidelberg. https://doi.org/10.1007/978-3-642-40663-8_4

Lyons, K. (2021, 5 17). Parler returns to Apple App Store with some content excluded. The Verge. Retrieved 9 11, 2021, from https://www.theverge.com/2021/5/17/22440005/parler-apple-app-storereturn-amazon-google-capitol

MaidSafe (Jul 2018) https://medium.com/safenetwork/proof-of-resource-on-the-safe-network192d5c951ebc

Maksimenka, I. (2021, 01 15). Decentralized Finance (DeFi): An Emerging Giant. Decentralized Finance(DeFi): An Emerging Giant. Retrieved 11 08, 2021, from https://www.nasdaq.com/articles/decentralizedfinance-defi%3A-an-emerging-giant-2021-01-15

Malwa, S. (2020, 10 8). 70% of Ethereum Nodes Are Hosted on Centralized Services. decrypt.co. Retrieved 11 8, 2021, from https://decrypt.co/44321/70-of-ethereum-nodes-are-hosted-on-centralized-services

Newman, D. (2021, 03 03). Blockchain Node Providers and How They Work. infoq. Retrieved 11 08, 2021, from https://www.infoq.com/articles/blockchain-as-a-service-get-block/

Nystrom, M. (2021, 10 18). The Dawn of Web3 Network Revenue. messari.io. Retrieved 11 08, 2021, from https://messari.io/article/the-dawn-of-web3-network-revenue

Raspberry Pi (2022). Raspberry Pi 4 Tech Specs. https://www.raspberrypi.com/products/raspberry-pi-4-model-b/specifications/

Synopsis (2020). Synopsys Study Shows 91% of Commercial Applications Contain Outdated or Abandoned Open Source Components. Retrieved 14 3, 2022, from https://www.securitymagazine.com/articles/92368-synopsys-study-shows-91-of-commercial-applications-contain-outdated-orabandoned-open-source-components

Slynchuk, A. (2021, 7 22). Big brother brands report: which companies might access our personal data the most? clario. Retrieved 11 9, 2021, from https://clario.co/blog/which-company-uses-most-data/

Statista. (2016, 10). Forecast number of personal cloud storage consumers/users worldwide from 2014 to 2020. personal cloud storage user numbers worldwide. Retrieved 11 08, 2021, from https://www.statista.com/statistics/499558/worldwide-personal-cloud-storage-users/

SUBERG, W. (2020, 7 17). China Controls 50% of Bitcoin Mining While US Hits 14% — New Survey.cointelegraph.com. Retrieved 11 08, 2021, from https://cointelegraph.com/news/china-controls-50-ofbitcoin-mining-while-us-hits-14-new-survey

Werbach, K. (2021, 08 21). What is decentralized finance? An expert on bitcoins and blockchains explains the risks and rewards of DeFi. marketwatch. Retrieved 11 08, 2021, from https://www.marketwatch.com/story/what-is-decentralized-finance-an-expert-on-bitcoins-and-blockchainsexplains-the-risks-and-rewards-of-defi-11628807382:~:text=DeFi%20could%20be%20cheaper%2C%20more,before%20it%20can%20go%20mainstream

Wheeler, T. (2020, 7 31). Big Tech and antitrust: Pay attention to the math behind the curtain. Brookings. Retrieved 11 9, 2021, from https://www.brookings.edu/blog/techtank/2020/07/31/big-tech-and-antitrustpay-attention-to-the-math-behind-the-curtain/

# 12. Appendix 1
## 12.1 Box Configurations
Box’s default configuration includes the base with two active towers. One tower is dedicated to the CPU and storage, one functions as a hub, allowing users to connect additional devices such as an external storage drive. With these two functional towers on the base, Box has slots for up to sevenadditional plug-and-play towers. This provides a modular platform for open-source ARM hardware
creators to access an existing network and user-base.
Being a lower-power standalone unit based on Box allows for convenient and uninterrupted uptime 24/7.
