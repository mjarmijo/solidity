# solidity notes

Contracts - starting point of everything
Contracts are fundamental building blocks of ethereum apps.
Solidity code is encapsulated in contracts.
All variables and functions belong to a contract

Pragma - compiler version to use
All solidity source code start with a version pragma
prevents breaking changes from future compilier versions

```solidity
pragma solidity >=0.5.0 <0.6.0;

contract HelloWorld {

}
```

State Variables
Permanently stored in contract storage, which means they are written to the blockchain. It is like writing to a DB. 

```solidity
contract Example {
  // This will be stored permanently in the blockchain
  uint myUnsignedInteger = 100;
}
```

uint - unsigned integer, meaning it must be positive. actually is uint265, also have uint8, uint32, etc. 

structs - more complex datatypes with multiple properties.
