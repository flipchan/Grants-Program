## XCMSend

**Team Name:**

*Rust Syndicate x Decentration*

**Payment Polkadot(DOT) Address:**

15iN8aQnPuX4vjcovenu15EtnYfcwbtiXjeKGRN3KkkzNNtt


**Payment terms:**

We request payment for each milestone in DOT on Polkadot. Converting the price from usd to dot at the time of payout using a EMA7 price conversion.

[https://polkadot.subscan.io/tools/price\_converter](https://polkadot.subscan.io/tools/price_converter)

**Funding Level: 2 - 30 000 USD**

**Why XCMSend?**

In a nutshell, XcmSend aims to simplify the process of xcm transaction curation and execution, as a non-partisan, open source project?

-   **Non biassed XCM Transfers**

XCMSend treats all transactions to all chains with the same priority. We do not charge middleman fees and our priority is that the user defined Asset gets properly sent.

-   **Increase XCM transaction volume**

By enabling more users to utilize easy to send XCM asset transfers, we aim at providing a peak in XCM transaction traffic.

-   **Not a DEX**

XCMSend does not manage liquidity pools, no limit orders, we only send assets from chain A to B with XCM.

-  ** Enable non-custodial, easy to use XCM Transfers/Make XCM transfers user friendly**

- **The need for simplification and real-time updates**
  
XCM has a growing share of all transactions in the ecosystem. The added complexity of curating calls, and the longer waiting times than single chain transactions, means that there must be a focus on user experience. In this context, experience can be improved:

 - **Before sending:** By abstracting away the complex and painful process that goes into curating an xcm call. A user does not manually need to draft the extrinsics needed for a XCM Transfer, with XCMSend we want to bring a seamless DeFi experience for anyone that wants to send assets with XCM.

 - **At execution**: by providing real-time dynamic status updates when executing the call, all in one place.


-   Easily test XCM asset transfers between chains
-   More liquidity to the ecosystem/empower DeFi users
-   OpenSource with MIT License

Once XCMSend has delivered the first milestones, it will be available publicly for anyone to use under the MIT license. Anyone will be able to clone the repository and spin up their own local XCMSend instance.

## **Project Overview 📄**

#### What is XcmSend?

XcmSend is a public Xcm asset transfer app that is open source and serverless, which interfaces with blockchains, making it simple for users to send assets between chains.

"Does what it says on the tin". Powered by the XCM protocol, our platform simplifies the process of cross-chain transfers.

Anyone can create their own instance, and XCMSend.com will also host an official instance. 

### **Project Details**

**Mock interface:**

1: (V0)Send asset![](https://lh3.googleusercontent.com/P-yFl3Mh6cyg5uXQJD8Q8J4f9K16JamfIV7Cwa8rY6H2jVAPIUoz8xl1uyiyf9BysMXK5d4_YoV53tpTjPHxzlVsJqGatk13KEoPijQWc1ziW15MbM-oSkxOVx791aAliAKjaBFTa_pQXqxBKryu2Qg)

2:  (V0) Transaction Broadcasted and Completed![](https://lh6.googleusercontent.com/OcNgY37AQHfw1kpGPZiNoAnwM93wlgbURtPJc8Xa_6foezh_h5lA3u9DmmuQ49XJk2AksSgmnd40u6q39uhQTiktaIrF66Ws6AfbS1biJxuBZV1A8YgN5otnFGlrtDx6N0x15R7GRXwXs_f-CBf62OM)

3: (V1) Transaction Broadcasted and Completed

![](https://lh3.googleusercontent.com/d7Ce03UkdiNqylBQdfjnz1c-l5WXClpDeAfOtSeh9_9NBVUUWF95s2AN496yYOpAD7A9ui0iyc2tR31z4Roelpz5FvS-UzXQ_4LtlKmu7GCdR7U673d9EoRfyUhSxAiH9ZKwuik_jPUhbCV4gEC6f0g)

As XCM transactions are more complex than a simple balance transfer on a single chain, the average time of a transaction is higher and more “moving parts” means there is an increased chance for errors during the transaction life cycle. This is why it is pertinent that the user is informed of the transaction status. We will enable real-time dynamic updates. As shown in the above screenshots. V0 for Milestone 1 and V1 for Milestone 2.

We will use the web3 foundation funded project “Polkaholic” as block explorer, as it supports viewing XCM transfers.

### **Ecosystem Fit**

As of the present composition, sending asset transfers across distinct parachain connected networks remains a task that lacks inherent user-friendliness. A relatively modest array of decentralized exchanges, including entities such as HydraDX and Polkaswap, are available to address this challenge. Notably, the proliferation of XCM adoption within the DotSama ecosystem is exhibiting a notable and continuous expansion. We want a bring a a user-friendly way for anyone to send assets from one parachain to another. Opening up XCM transfers for everyone.

Xcm Adoption in the Dotsama ecosystem is growing and growing:

![](https://lh6.googleusercontent.com/Qj9NNiG_YQk__eaLh2Q_BOpuX7xe0uU19ipJ0fumFAMLAW2cjfI4PDNkqea0V30Dzsm_BdQJ0d536JyvbCuGn049489sFSu4SYjlcDaydQN-QRId9vwlYT4DRUIeKzAV3RLWOqcUoYd74m9S4a84AM0)

XCM Traffic chart from  2021/04/12 to 2023/05/07.

We want to enable everyone to be able to spin up their own ;lightweight instance of XCMSend and easily be able to send assets from one chain to another.

Data Source:

Polkaholics: [https://github.com/colorfulnotion/substrate-etl](https://github.com/colorfulnotion/substrate-etl)

Replicate data:

```shell
$ git clone https://github.com/colorfulnotion/substrate-etl && cd substrate-etl

$ ./generateNetworksSummary

$ cat SUMMARY.md
```

Note:

If your getting curl connection timeout errors, we have added a pr to fix this:

https://github.com/colorfulnotion/substrate-etl/pull/10

### **Legal Structure**

-   Registered Address: Vakhtang Gorgasali Street Nr 14, Office Door number 30, Tbilisi, Georgia
-   Registered Legal Entity: Rust Syndicate LLC

## **Team 👥**

### **Team's experience**

**Filip "flipchan" Kalebo** - Rust Syndicate  - Developer, DevSecOps, Previously worked on early stage Picasso chain, Edgeware Solo chain and recently “Uptest” that is funded by the Polkadot Treasury.

**Ramsey Ajram** - Decentration - Substrate Developer, Product, Frontend, took a parachain into production on Kusama, W3F funded for Supersig (pallet and UI) [https://subverse.decentration.org](https://subverse.decentration.org). Polkadot Blockchain Academy alumni.

**Ace Salazar** - Rust Syndicate  - Project coordination, Previous experience working on projects for the Rust programming language’s ecosystem.  


**JelliedOwl(Paul)** - Substrate based chain rpc provider, trusted community member, Moderator of the Polkadot Multisig.


### **Team Code Repos**

-   [https://github.com/uptest-sc/](https://github.com/uptest-sc/)
-   [https://github.com/decentration](https://github.com/decentration)
-   [https://github.com/kabocha-network/](https://github.com/kabocha-network/)
-   [https://github.com/flipchan](https://github.com/flipchan)

#### Proven Track Record:

The team has delivered previous projects in the substrate ecosystem:
- Flipchan migrated Edgeware from an old version of substrate to the new version, which required complex refactoring and storage migrations. 
- Based on the above experience, Flipchan was then grant funded by the polkadot treasury to build Uptest, a library to test runtime upgrades.
- Ramsey launched an experimental parachain on behalf of Edgeware called, Kabocha. 
- Decentration (lead by Ramsey) was grant funded by W3F to create organisations (pallet and UI) called supersig.  

## **Contact:**

Contact name:

Filip Kalebo - Rust Syndicate

Contact email:

[blockchain@firosolutions.com](mailto:blockchain@firosolutions.com)

Contact name:

Ramsey - Decentration

Contact email:

[ramsey@decentration.org](mailto:ramsey@decentration.org)

https://decentration.org

## **Development Status 📖**

## **Development Roadmap 🔩**

### Overview

- **Total Estimated Duration:** 9 weeks

- **Full-Time Equivalent (FTE):**  2 FTE

- **Total Costs:** 30 000 USD to be converted into DOT(Polkadot)

**Milestone 1: XCM SEND MVP**

FTE: 2

Duration: 5 weeks

Costs: 15000 USD




| Number | Deliverable |Specification |
|--------------|-----------|------------|
| 0a.    |  License | MIT |
| 0b | Documentation | We will provide tutorials and usage examples of all features and milestones delivered. |
| 0c      | Testing and Testing Guide  | In our published documentation and articles we will cover the steps needed to test XCMSend       |
| 0d      | Docker  | We will publish a docker image that users can use to test XCMSend locally       |
| 0e      | Article  | We will publish an article that walks the end user hand in hand on how to use XCMSend       |
| 1      | XCMSend UI (MVP)  | Build the first version of the XCMSend UI which begins with teleporting assets.        |
| 2      | Polkadot.js browser wallet integration  | Supporting polkadot.js browser wallet       |
| 3      | Public beta instance  | We will deploy a version of XCMsend publicly on XCMSend.com       |
| 4      | Rococo XCM Transfers | We will enable teleporting of assets across chains within the Rococo network. Such as ROC from Rococo to AssetHub.       |



Milestone 2:

FTE: 2

Duration: 4 weeks

Costs: 15000   


| Number | Deliverable |Specification |
|--------------|-----------|------------|
| 0a.    |  License | MIT |
| 0b | Documentation | We will provide tutorials and usage examples of all features and milestones delivered. |
| 0c      | Testing and Testing Guide  | In our published documentation and articles we will cover the steps needed to test XCMSend |
| 0d      | Docker  | We will publish a docker image that users can use to test XCMSend locally       |
| 0e      | Article  | We will publish an article that walks the end user hand in hand on how to use XCMSend       |
| 1      | Support 3 chains or more  | Support at least 3 different parachains as source chains to send assets from       |
| 2      | Json-rpc api  | We want to enable users to send XCM Transfers in a high level way and we will provide a basic api that can be used by client libraries, to seamlessly broadcast XCM asset transfers.       |
| 3      | Parachain discovery  | XCMSend will track which parachains are currently connected and filter the selection based on that. The lease times of each parachain needs to be accounted for as well.        |
| 4      | Auto index XCM channels  | Filter the options for source and destination chain based on the open channels that are available       |





## Future Plans:

-   We aim to build and maintain XCMSend publicly, after the first version of XCMSend is live and we have gathered enough community feedback. We plan on deploying a version for Kusama. Allowing parachains connected to Kusama to send assets using XCM. (And thereafter, Polkadot.)
-   For more experienced users we also want to add an “Advance” tab where the “power user” can customize the transaction after its needs.
-   This advanced tab may sprout into building a  low code app containing all substrate blockchains, pallets, and relevant APIs that can be dragged and dropped and connected into workflows to build the next generation of DApps (enabled by XCM and bridges).
-   Remark NFT integration
-   We also want to support Pallet-supersig, allowing DAO’s and groups to send XCM Transfers to and from pallet-supersig origins.

## **Additional Information ➕**

How did you hear about the Grants Program? The team is familiar with the web3 foundation from previous projects.
