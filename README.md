# ethavaxmod1
#  Error Handling in solidity
This repository is made for my ethereum intermediate avax project which is used to execute Error Handling process in Solidity. 

## Problem Statement

create a contract  to  deploy error handling process in solidity by using revert(), assert() and require() statement.


## Description

1) Create a contract named contract3
2) now in order to show the working of the assert, revert and require conditions we have created three functions.
3) for the require condition we have created a function named climatetemperature and passsed temp as parameter, if the temperature is less than zero than the temperature
will be in freezing point and if not it will display that it is not in freezing point.
5) now for the assert condition we have created a function named normaltemp and passed temp as parameter, the temperature should be less than or equal to 20 inorder to be normal temperature.
6) lastly to demonstrate the revert fuction create a function named boilingpoint and pass temp as parameters, and for the revert function set a condition where
     the temp should not be less than or equal to 100.
7) now click on deploy option and deploy the contract created.
    
## Getting Started

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at (https://remix.ethereum.org/.)

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., error.sol). Copy and paste the following code written by me into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set heigher to "0.8.1" (or another compatible version), and then click on the "Compile error.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyContract" contract from the dropdown menu, and then click on the "Deploy" button.

After deployment of  the contract call the function addition() , subtraction() and sulo() by providing value, it perform error handling process by  using revert, assert, require statement. 


## Author
SHRESHTHA PAL

## License

This project is licensed under the MIT License - see the LICENSE file for details
