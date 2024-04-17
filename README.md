# Building-with-Polygon-Bridge

FxPortal marks the advent of Polygon-Advance. In this maiden project, I've navigated the intricate realm of NFTs, deploying them on the Ethereum sepolia network. Then, with deftness, I traversed the realms, approving and depositing from Ethereum to Polygon using the Polygon Bridge.

## Quick Start

### Running the Program

Begin your journey by downloading the entire repository. This grants you access to a plethora of contents within. Navigate to the ERC721A project directory and execute:

```shell
npm install
```

### Deploying the ERC721A Contract

Prepare for deployment! Ensure to rename ".env.example" to ".env" and furnish your wallet's private key where indicated, like so: "PRIVATE_KEY= 'your wallet private key'". Now, embark on the deployment voyage with the following command:

``` shell
npx hardhat run scripts/deploy.js --network sepolia
```

Witness the contract unfurl before your eyes, as its address materializes both in the console and the "contractAddress.js" file within the metadata folder.

### Batch Mint NFTs

Engage in the mass creation of NFTs! Execute the following command to mint them in bulk, courtesy of the deployed ERC721 contract:

``` shell
npx hardhat run scripts/mint.js --network sepolia
```

Behold, as the specified number of NFTs manifest and find refuge in your address.

### Approve and Deposit NFTs to Polygon Mumbai

Continue your journey by granting approval and seamlessly transporting the minted NFTs from Ethereum to the Polygon Mumbai network, employing the FxPortal Bridge. Execute the following commands:

```shell
npx hardhat run scripts/approveDeposit.js --network sepolia
```

## Author

ayushiverma126822

## License

This project is licensed under the MIT License. For details, refer to the [LICENSE](LICENSE) file.
- - -
