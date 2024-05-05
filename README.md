# how to make your firest Dapp

### chai-dapp
## First we need to make our smart contract in my case I use remix editor for making my smart contract and I use the solidity language because it is the best blockchain  language for application hear's is my smart contract
<img width="1440" alt="Screenshot 2024-05-04 at 9 42 15 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/1d8679c5-1473-4b51-aa85-e6f84dc9a8d3">

## After go to your dashboard and make a file for deploying your smart contract using vs code and open in your vs code
<img width="1440" alt="Screenshot 2024-05-04 at 9 41 33 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/3674b3e2-ce26-43f6-95ca-6b6983259e43">

## After open your file in vs code you need to install hardhat by the command in the following
    npm install hardhat
<img width="1440" alt="Screenshot 2024-05-04 at 9 42 50 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/ac275fee-7372-4cf1-825f-0c506f38e41f">
<img width="1440" alt="Screenshot 2024-05-04 at 9 44 04 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/92385fb2-d22f-4098-8670-ceea8f95f220">

## And then install the dependency for heart hardhat by this command
    npm install --save-dev "hardhat@^2.22.3" "@nomicfoundation/hardhat-toolbox@^5.0.0"
<img width="1440" alt="Screenshot 2024-05-04 at 9 44 24 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/04544277-f4e1-445e-82ae-2efa720d8e6e">

## after compile your hardhat by this command
    npx hardhat compile
<img width="1440" alt="Screenshot 2024-05-04 at 9 46 54 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/9db2cb86-77bc-4123-aaed-0d6820c23a68">
<img width="1440" alt="Screenshot 2024-05-04 at 9 47 02 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/6ce8a2ed-2640-4cbf-b6f9-4dbd575f6d06">

## After compile your hardhat you need to know your deployment address for that you use this command
    npx hardhat ignition deploy ./ignition/modules/lock.js
  <img width="1440" alt="Screenshot 2024-05-04 at 9 48 01 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/9bfb8662-38b3-480b-b6df-0d6ad55635b7">

## After that you need to create your vite in your decentralized application by this command
    npm create vite@latest
  <img width="1440" alt="Screenshot 2024-05-04 at 9 48 49 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/edc72bf5-f0ea-4f6c-a32a-0cd32582274b">

## This is your opinion what you choose like Vanilla,vue I choose react After after that you choose JavaScript and then your vite project is launch

## After that running this command a new file by the name vite-project is created in my case I change the name of this file with client
<img width="1440" alt="Screenshot 2024-05-04 at 9 49 30 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/fc7b8ad5-c690-4be4-885b-a858737c7f48">

## After that I go to my client folder by this command
    cd client
## After that I install all the dependency by the command 
    npm install

## After that your work is finish if you want to check your application is deployed or not then you put this command the TerminalAnd you got a local http local host link by putting this link in your Chrome search bar you see your application running on localhost 
    npm run dev
<img width="1440" alt="Screenshot 2024-05-04 at 9 50 18 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/81c91241-f817-4c57-a930-3ebc0aee1eff">
<img width="1440" alt="Screenshot 2024-05-04 at 9 50 29 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/21fd6814-8fd2-4953-a707-df087a5e49c3">

## Okay this is the common step for creating a decentralized application after that you need to diploy your smart contract and create your application

## Okay so here is the important part for making your decentralized application first you go to your client folder and then go to the src folder and click on app.jsx after making some changes you completed your app.jsx fine
<img width="1440" alt="Screenshot 2024-05-04 at 9 53 38 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/2e8cf37c-8d21-4f14-b9c6-dec7a91fd5d8">

## After making changes in your app.jsx file you go to your hardhat.config.js file and make some changes in it also in my case I copy from some external website
<img width="1440" alt="Screenshot 2024-05-04 at 9 54 02 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/5bc9e0c7-9019-4e05-8bde-197a0c28d73d">

## After that you need two things first one is goerli_URL and the second one is private_key for store this to thinks you need to create your one separate file like.env and save it there

  ### 1.if you want your Goerli_URL you need to create a app in my case I use Alchemy for creating app after that creating your app you go to your API key and copy paste the https link in the Goerli_URL
  <img width="1440" alt="Screenshot 2024-05-04 at 9 54 19 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/bf08022a-f5a3-4d29-914e-ccfc71703a6e">
 <img width="1440" alt="Screenshot 2024-05-04 at 9 54 24 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/4f51eecf-def2-46e5-b8e0-68e63d79b2fd">

 ### 2.If you want your private key then you make your account in metamask after that creating your account in metamask you click on thetop right side and go to the account details and then create your private link and copy and paste it in .env file
 <img width="1440" alt="Screenshot 2024-05-04 at 9 55 22 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/8dd69a1a-6aca-46db-9910-3bc9f0df63a0">
<img width="1440" alt="Screenshot 2024-05-04 at 9 57 03 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/6f14c49b-ee36-4f68-a498-410f2d89db5c">

## After that your application is deployed for see your application you need to go to your client folder and type this command

    npm run dev

## After paste the link in the search bar you saw your application
<img width="1440" alt="Screenshot 2024-05-04 at 10 08 40 PM" src="https://github.com/dhirukumar/chai-dapp/assets/146316525/d6517772-b86c-4be4-a674-a90593294f67">

## References

- [Hardhat Tutorial](https://hardhat.org/tutorial)
- [Hardhat Docs](https://hardhat.org/hardhat-runner/docs/getting-started#overview)

 
 


     













