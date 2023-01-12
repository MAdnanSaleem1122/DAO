# DAO (Decentralized Autonomous Organization)

![dao](https://user-images.githubusercontent.com/121422342/212003068-d9412654-35d9-4786-8a1f-fc1c6cc6238a.PNG)

Create a folder for this project named DAO-Tutorial, and open up a Terminal window in that folder.
Setup a new hardhat project by running the following commands in your terminal:
```
mkdir hardhat-tutorial
cd hardhat-tutorial
npm init --yes
npm install --save-dev hardhat
```
In the same directory where you installed Hardhat run:
```
npx hardhat
```
Make sure you select Create a Javascript Project and then follow the steps in the terminal to complete your Hardhat setup.
Now, let's install the @openzeppelin/contracts package from NPM as we will be using OpenZeppelin's Ownable Contract for the DAO contract.
```
npm install @openzeppelin/contracts
```
Let's make sure everything compiles before we start writing the DAO Contract. Run the following command inside the hardhat-tutorial folder from your Terminal.
```
npx hardhat compile
```
Install the dotenv package from NPM to be able to use environment variables specified in .env files in the hardhat.config.js. Execute the following command in your Terminal in the hardhat-tutorial directory.
```
npm install dotenv
```
Let's make sure everything compiles before proceeding. Execute the following command from your Terminal within the hardhat-tutorial folder.
```
npx hardhat compile
```
Let's deploy! Execute the following command in your Terminal from the hardhat-tutorial directory
```
npx hardhat run scripts/deploy.js --network goerli
```
Let's get started by creating a new next app. Your folder structure should look like this after setting up the next app:
```
- DAO-Tutorial
    - hardhat-tutorial
    - my-app
 ```
 To create my-app, execute the following command in your Terminal within the DAO-Tutorial directory
```
npx create-next-app@latest
```
and press Enter for all the question prompts. This should create the my-app folder and setup a basic Next.js project. Let's see if everything works. Run the following in your Terminal
```
cd my-app
npm run dev
```
Let's run it! In your terminal, from the my-app directory, execute:
```
npm run dev
```
