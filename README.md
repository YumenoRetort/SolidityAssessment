# Create A Token

The purpose of this program is to comply with the ETH PROOF: Beginner EVM Course of Metacrafters

## Description

This code accomplishes the following requirements:

    1. The contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
    2. The contract will have a mapping of addresses to balances (address => uint)
    3. The will have a mint function that takes two parameters: an address and a value. 
       The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
    4. The contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
       It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
    5. The, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned.

## How/where to download your program
You can download my program directly from GitHub via the download button in the upper right.


## Executing program
This program can be run using the website Remix, linked here: https://remix.ethereum.org/

Once on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the code on this repository to the page.


## How to run the program
- Within Remix you can run the program by clicking the "Deploy & Run Transactions" button.
- After this, you will be able to interact with the mint and burn functions and call on the variables.
- Once the contract is deployed, you can interact with it and mint and burn tokens.

## Authors

Erin Beatrice Micaela G. Reyes


## License

This project is licensed under the MIT License - see the [LICENSE.md](https://github.com/YumenoRetort/SolidityAssessment/blob/main/LICENSE) file for details 
