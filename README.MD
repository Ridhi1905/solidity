## Project Title

A simple contract to store the details about our coin.

## Description

In this project we have to create a simple contract in which the contract will have public variables which will store the details about our coin (Token Name, Token Abbrv., Total Supply), our contract will have a mapping of addresses to balances (address => uint). And we will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the “sender” address by that amount. Our contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the “sender”. Lastly, the burn function should have conditionals to make sure the balance of "sender" is greater than or equal to the amount that is supposed to be burned.

## Getting Started

### Installing

* To download this program simply download the raw file and open in whichever editor you want.

### Executing program

* To run the program on remix- Ethereum IDE follow the steps:
* Firstly, compile the code.
* After the compilation is done goto 'deploy and run transactions' section and deploy the contract.
* When the contract is deployed, now copy your account and paste it to mint function and enter the amount you want to mint to your account and transact it and you can also check the balance. 
* now to burn enter the account info and amount which you want to burn and transact 
* after this you will be able to see how much amount is remaining and how much you have already taken out.

## Authors
* Any help needed contact me at:
* Ridhima Chauhan 
* Contact : ridhimac2004@gmail.com 

