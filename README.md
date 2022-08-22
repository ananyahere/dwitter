# DWITTER

### Inspiration
To widen the horizons of web3, we can introduce new features in web2 applications. Doing so would help the general public to get familiar with the new way of the internet. With this project, we aim to smoothen that transition for Twitter users!

### What it does
The application introduces the following features to the old-school Twitter:
1. Wallet login
To authenticate themselves, users need to connect their wallets with the application.
2. NFT profile picture
Wallet-owned NFTs can be selected as the profile picture for the account.
2. MATIC tweet
Users can save their tweets on the blockchain.

### How we built it
The application uses solidity to make a simple smart contract which is deployed on Ploygon's Mumbai Testnet (smart contract is clickable to any other EVM chain as well). React is used for the frontend of the application. On the backend, Moralis is used to interact with the smart contract as well as store user data. Lastly, web3uikit is used to enhance the UI of the application.

### Challenges we ran into
- The initial problem we faced was the deployment of our first-ever smart contract and minting of the cryptocurrency for testing purposes.
- Another major hurdle was the implementation of authentication with the user's wallet. We figured this out by applying useMoralis().authenticate()  instead of <ConnectButton/> component from web3uikit.

### Accomplishments that we're proud of
Working on web3 project for the first time.

### What we learned
Using web3 technology in a real-world app.

### What's next for Dtwitter
Inspired by the cryptoArt moment, an additional gallery feature will be provided to users to showcase as well as sell their NFTs.