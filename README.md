// SPDX-License-Identifier: MIT
pragma solidity ^0.8.24;

contract MyFirstContract {
    string public message = "Hello Base!";

    function setMessage(string memory newMessage) public {
        message = newMessage;
    }

    // ✅ Aggiunto nella seconda versione
    function sayHello() public pure returns (string memory) {
        return "Hello from version 2!";
    }
}