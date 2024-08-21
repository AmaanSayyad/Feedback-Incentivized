# Feedback-Incentivized

## Inspiration
While browsing Amazon for shoes, we discovered a significant price discrepancy of $100 for the same product. Realizing the importance of reporting such discrepancies, we found existing feedback forums lacked incentives for users. Thus, FI-Protocol was born, a solution that empowers users to provide valuable feedback through token incentives, ensuring their voices are heard and fostering transparency in the marketplace.

## What it does
FI-Protocol offers a user-friendly bug-reporting platform that incentivizes users with tokens for reporting errors. This facilitates direct communication between users and companies, providing actionable feedback for swift issue resolution and platform enhancement. By leveraging Chainlink Cross-Chain Interoperability Protocol (CCIP), the platform ensures secure, transparent, and reliable operations across multiple blockchains.

## Features and Functionality
- Confidential Bug Reporting: Users can submit bug reports encrypted with Fully Homomorphic Encryption (FHE), ensuring their sensitive information is protected from unauthorized access.
- Incentive Mechanism: Users are rewarded with Feedback Incentivized (FI) tokens and AI-generated NFTs for submitting valid bug reports, incentivizing active participation.
- Verification and Credibility: Each bug report, once validated, generates a timestamped NFT, enhancing the credibility of the reporter and providing proof of submission.
- AI-Driven Recognition: Accepted bug reports trigger the creation of an AI NFT, boosting the reporter's standing on the leaderboard and increasing their reward multiplier.
- Stake and Earn: Users can stake ANY tokens as collateral to receive FI tokens, creating a seamless integration with the Chainlink - EVM Chains and expanding the ecosystem's token utility.

## How we built it
- Design Architecture: Structured the platform with a clear and robust architecture.
- Flow Chart: Created detailed flow charts to map out user interactions and system processes.
- Integration: Integrated various components to ensure seamless operation.
- Testing: Conducted extensive testing to ensure functionality and reliability.
- Chainlink CCIP: Implemented Chainlink CCIP for cross chain transfers and communication across chains to make it convenient for users and ease their struggle of jumping between chains.
- Polygon Amoy: FI-protocol is deployed on the Polygon PoS network, utilizing its high throughput and low transaction fees to revolutionize financial services within our platform.
- Avalanche Fuji C-Chain: Deployed Contracts and Utilized Avalanche's Fuji testnet for its high throughput and low latency, deploying parts of our platform to leverage these features for a seamless user experience.

## Challenges we ran into
- Smart Contract Integration: Encountered difficulties while navigating through chainlink supported networks and routers.
- Web3 to Web2 Integration: Experienced challenges in integrating Web3 elements with Web2 components.
- Cross-Chain Functionality: Ensuring seamless interoperability across different blockchain networks using Chainlink CCIP.

## Accomplishments that we're proud of
All Contracts Tested, Deployed and Verified.

## What's next for FI-Protocol
- Applying for Grants: Seeking funding to further develop and expand the platform.
- Mainnet Launch: Deploying FI-protocol on the mainnet for real-world use.
- User Testing: Conducting extensive user testing to refine the platform.
- Promoting the Product: Marketing FI-protocol to attract a wider audience.
- We also aim to implement gasless transactions to enhance user convenience.
- Support 10+ new tokens and 10+ new chains within the next few months using Chainlink CCIP after the end of the hackathon.
- The users and companies will stake LINK Network tokens as a collateral to get FI tokens which they will use to report bugs and resolve bugs.
- The bugs reported by the users if accepted by the company, then the bug report will get generated into NFT's which will have a timestamp that will help to prove if two or more users have reported the bugs at same time and the model will trigger function to reward the early submitter.
- The reported bugs if accepted by companies then a function triggers that will automatically generate a AI NFT to the user which will increase the credibility of the bug reporter in the leaderboard and provide a booster multiplier to receive more Tokens.
- The model can easily adapt the layer.xyz / zealy kind of model functionality.