# Fungible Token ERC20

I decided to create a new cryptocurrency called KaseiCoin (“Kasei” means “Mars” in Japanese.). KaseiCoin is a fungible token that is ERC-20 compliant. I launched a crowdsale that  allows people to convert their money to KaseiCoin.

This token was minted by using a ```Crowdsale``` contract from OpenZeppelin Solidity library.

The crowdsale contract that I created manages the entire crowdsale process, allowing users to send ether to the contract and in return receive KAI, or KaseiCoin tokens. This contract will mint the tokens automatically and distribute them to buyers in one transaction.

## Technologies
``` Solidity ```

## Installation Guide

In order to open and run this program you have to follow these steps:

* Go to my repository in GitHub and open the repository called ```fungible_token_21```

* Copy the repository's link.

* Open Git Bash in your computer 

* Clone the repository by typing ```git clone``` and paste the link ```git@github.com:nestor39/fungible_token_21.git```.

* Type ```start .``` in Git Bash and you are going to be able to see the file inside the folder that you downloaded onto your computer.

Open [Remix IDE website](https://remix.ethereum.org/#optimize=false&runs=200&evmVersion=null&version=soljson-v0.8.4+commit.c7e474f2.js) , load the file onto the current workspace, compile and deploy the file.


### Usage

Create and compile the KaseiCoin Token Contract 

![image](https://user-images.githubusercontent.com/80844686/129801793-094338f9-f803-4786-afd5-58b33d9bbead.png)

Create and compile the KaseiCoin Crowdsale Contract

![image](https://user-images.githubusercontent.com/80844686/129805030-38766d18-14d4-4508-b5e1-2b52f26e7069.png)

Create the KaseiCoin Deployer Contract

![image](https://user-images.githubusercontent.com/80844686/129819867-c18b4875-628e-4031-abc5-9cbd1726ea5c.png)

Deploy the Crowdsale to a Local Blockchain 

https://user-images.githubusercontent.com/80844686/130007478-3bba2828-a64b-431a-a520-060955cd8083.mp4

![image](https://user-images.githubusercontent.com/80844686/131054310-feb9c963-f495-48ae-8fba-8feac8b53666.png)

![image](https://user-images.githubusercontent.com/80844686/131054212-becaa51f-2111-4289-8f11-320276be2d57.png)

Test the functionality of the crowdsale by using test accounts to buy new tokens


https://user-images.githubusercontent.com/80844686/131056570-52c8158b-006c-45dd-8627-199401d578c2.mp4


https://user-images.githubusercontent.com/80844686/131056574-f573f9f3-31d8-4494-a835-eb385e9c899f.mp4


Check the balances associated with those accounts.

![image](https://user-images.githubusercontent.com/80844686/131055583-5ad8f738-5849-464b-83a3-6898fd4a0d7a.png)

![image](https://user-images.githubusercontent.com/80844686/131055499-4830b8b0-35c6-41ba-b786-2dc2b9659485.png)

Optional: Extend the Crowdsale Contract by Using OpenZeppelin

![image](https://user-images.githubusercontent.com/80844686/131057091-c5cbdd55-8b46-46cb-862a-0e8e396f1508.png)


## Contributors
Brought to you by [Nestor Ramirez Cuadro](https://www.linkedin.com/in/nestor-ramirez-cuadro-375654209/)

e-mail: nestorramirez3994@gmail.com



## License
[MIT](https://github.com/nestor39/fungible_token_21/blob/main/LICENSE)
