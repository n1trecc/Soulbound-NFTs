**Context**

The basis of this research and consequential coding project stems my following of Vitalik Buterin's online blog, where in one of his posts of early 2022 he discussed the concept of Soulbound, translated from a World of Warcraft mechanic. 

Being interested in tokenization and the real life application potential of NFTs further than being a collectable, I decided on creating my own Soulbound NFT for a first coding project. Although the hype of NFTs has died out in recent years, my subjective 	opinion has always been that of a lack of  infrastructure being available to harness the possibilities of NFTs to the real world.

What spurred me on in the end to finally try my own project in this regard was his post about WorldCoin, which made use of biometric proof of personhood to access ones wallet. This idea of having a linkage between a singular wallet and person ofcourse already exists with KYC, but still adding the biometric aspect ensured there would be one wallet only per person (per chain). This opened the possibility for me of what real life use cases there could be that would make different processes such as applying for jobs, having your work history and similar all stored on-chain linked to your biometric data.
Aside from the obvious lack of infrastructure and regulation for this and all its data (as discussed in Vitaliks post regarding WorldCoin), the bureaucratic processes it could eradicate seemed endless to me, making it an enticing project.

**Primary Application Process**

Specifically for this project, my use case had come from the many application processes for top tier companies in finance.
When applying, all you details are filled in, although no proof is usually required from the employers side.
A submission of a wallet address in the application process could allow for the companies to instantly have a trustworthy source of the aplicants achievements without there being any doubt of if any documents or achievements are faked. This is thanks to the visibility of who minted the Soulbound NFT to the applicant on-chain.

The draft of the roadmap for this project is detailed below:


**Coding**

After doing research on how to mint my own NFT, I used the help of multiple youtube videos to create the code on OpenZeppelin, making use of their ERC721 token libraries being integrated into their coding tool on their website without having the need downloading any packages.


Goal: Mint an Non Transferable NFT (aka SoulBound token) of an Academic Achievement for myself

**Step 1: **

Videos on how to mint NFTs
https://www.youtube.com/watch?v=90vWC4Z8aPo

After copying all code, some struggles with corrections of which testnet to use and having all relevant tokens to mint.
Post figuring this out and deciding on sepolia, I managed to mint my first Souldbound NFT.
Attempted to send NFT to another address, which failed, according to design.
The minting was done on the Sepolia testnet, with the NFT then being visible on the OpenSea testnet.
https://testnets.opensea.io/assets/sepolia/0x092e36b5409118acd2f043781a3087e39d7fc35b/0/
Wallet Sepolia Etherscan
https://sepolia.etherscan.io/address/0x487B1927Af4470102D9022Ba96308c5F4214A6e8

**Step 2:** 
Adding a visual to the NFT, either through PDF or png entry.
Add description, name, etc.

**Step 3:** 
Create new addresses, one for my university, one with biometric access / KYC.
Then mint a Soulbound NFT from the address given to the Universiy to myself alongside a visual of my diploma.

**Step 4:** 
Create platform with a preset for PDF entry of diploma/achievement, student information and wallet, minting an NFT through the platform by any user.

