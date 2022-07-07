Requirements
There should be a max of 10,000 CD tokens.
Every Crypto Dev NFT holder should get 10 tokens for free but they would have to pay the gas fees.
The price of one CD at the time of ICO should be 0.001 ether
There should be a website which users can visit for the ICO.

To setup a Hardhat project, Open up a terminal and execute these commands

mkdir ICO
cd ICO
mkdir hardhat-tutorial
cd hardhat-tutorial
npm init --yes
npm install --save-dev hardhat
In the same directory where you installed Hardhat run:

npx hardhat
Select Create a basic sample project
Press enter for the already specified Hardhat Project root
Press enter for the question on if you want to add a .gitignore
Press enter for Do you want to install this sample project's dependencies with npm (@nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers ethers)?
Now you have a hardhat project ready to go!

If you are not on mac, please do this extra step and install these libraries as well :)

npm install --save-dev @nomiclabs/hardhat-waffle ethereum-waffle chai @nomiclabs/hardhat-ethers ethers
In the same terminal now install @openzeppelin/contracts as we would be importing Openzeppelin's ERC20 Contract and Openzeppelin's Ownable Contract in our CryptoDevToken contract

npm install @openzeppelin/contracts