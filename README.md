# Deploy smart contract on base
→ Head to: remix.ethereum.org 

→ Go to solidity compiler 

→ Select compiler version 0.8.20 

→ Go to file explorer and create new file 

→ Enter file name Mycontract.sol 

→ Paste this code 👇
```
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract HelloWorld {
    string public message;

    constructor() {
        message = "Hello, Remix!";
    }

    function setMessage(string memory newMessage) public {
        message = newMessage;
    }
}
```
→ Head to Solidity compiler and compile code this 

→ Go to Deploy & Run transaction 

→ Click Environment and connect EVM wallet 

→ Click deploy button and complete transaction on your wallet 

→ Done ✅

Follow me on 𝕏 x.com/CryptoNaveeen
