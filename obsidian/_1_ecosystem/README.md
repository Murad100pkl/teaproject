# TEA Project Intro
TEA Project is a decentralized cloud computing platform that hosts rich, decentralized applications known as TApps. These are completely serverless and run purely in miners' nodes. By offering highly-scalable and decentralized apps, TEA Project combines the best of both blockchain and cloud computing. 

In the TEA project, dApps code runs on a layer-2 WebAssembly runtime inside the hardware protected (TPM) enclaves. These enclaves generate Proof of Trust data handled by blockchain consensus on layer-1. In TEA, blockchain doesn't use consensus to verify the result of dApps code, but the execution environment where the code runs. 

TEA Project's three roots of trust are:

1. Blockchain.
2. Trusted hardware.
3. Time. 

TEA’s state machine orders transactions using a Proof of Time algorithm which utilizes GPS satellites. To make the GPS timestamps trustable, we need a trusted enclave to protect their integrity. That's gain where the TPM chips come in. These hardware security modules provide the trusted enclave that makes the GPS timestamps trustable along with making data privacy and trusted app execution possible as well.

Using trusted time to order transactions allows TEA to run dApps that rival the speeds of traditional cloud computing. TEA is an ideal platform for any app requiring data security and privacy while remaining censorship-resistant.

## Three roles in the TEA Project

There are three active roles in the TEA ecosystem:

- Miners: They own hardware mining machines, purchase CML (NFT, it's like software license), provide computing services and get rewarded with TEA. Read more in [basic concepts for miners](../_mining/README.md).
- Investors: Users with TEA funds can invest in mining machines, TApps or even CML and TEA in order to get ROI. Investors can learn more about investing in [entity tokens](../_token/TApp-Token-Supply-and-Demand.md).
- Developers: They use the TEA framework to develop TApps which run on mining machines and provide services to earn revenue which would be distributed to investors and miners according to smart contracts on a bonding curve. You can read more about [basic concepts for developers](../_tapps/Developers.md).