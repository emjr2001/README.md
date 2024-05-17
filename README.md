# HELLO WORLD

The Solidity program is a simple "Hello World" program that demonstrates the basic syntax and functionality of the Solidity programming language.

## Description

This is a simple "Hello World" contract in Solidity that demonstrates the basic syntax and functionality of the language. The contract allows users to set and retrieve a message. The contract has a constructor that sets the initial message, and two functions: changeMessage to update the message, and getMessage to retrieve the current message.

The contract can be used to create a simple decentralized application (dApp) that stores and retrieves a message. The contract can be deployed on the Ethereum blockchain, allowing users to interact with it through a frontend application.

## Getting Started

### Executing program

```
pragma solidity ^0.8.0;

contract HelloWorld {
    // Variable to store the message
    string public message;

    // Constructor to set the initial message
    constructor(string memory _message) {
        message = _message;
    }

    // Function to change the message
    function changeMessage(string memory _newMessage) public {
        message = _newMessage;
    }

    // Function to get the current message
    function getMessage() public view returns (string memory) {
        return message;
    }
}
```

In this contract, we have a message variable that stores the current message. We have a constructor that sets the initial message, and two functions: changeMessage to update the message, and getMessage to retrieve the current message.

## Authors

Datu Benladin Embag Jr, 
8202138@ntc.edu.ph
