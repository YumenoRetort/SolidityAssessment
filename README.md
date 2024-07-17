# Create A Token

The purpose of this program is to comply with the ETH PROOF: Beginner EVM Course of Metacrafters

## Description

This code accomplishes the following requirements:

    1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
    2. Your contract will have a mapping of addresses to balances (address => uint)
    3. You will have a mint function that takes two parameters: an address and a value. 
       The function then increases the total supply by that number and increases the balance 
       of the “sender” address by that amount
    4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. 
       It will take an address and value just like the mint functions. It will then deduct the value from the total supply 
       and from the balance of the “sender”.
    5. Lastly, your burn function should have conditionals to make sure the balance of "sender" is greater than or equal 
       to the amount that is supposed to be burned.

## How/where to download your program
You can download my program directly from GitHub via the download button in the upper right.


## Executing program
This program can be run using the website Remix linked here: https://remix.ethereum.org/


## How to run the program
- Within Remix you can run the program by clicking the "Deploy & Run Transactions" button.
- After this, you will be able to interact with the mint and burn functions as well as call on the variables.

## Authors

Erin Beatrice Micaela G. Reyes


## License

This project is licensed under the MIT License - see the (LICENSE.md){https://github.com/YumenoRetort/SolidityAssessment/blob/main/LICENSE} file for details 
