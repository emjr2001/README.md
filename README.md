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

In this contract, we have a message variable that stores the current message. We have a constructor that sets the initial message, and two functions: changeMessage to update the message, and getMessage to retrieve the current message.
