# Timestamp.sol
Timestamp.sol
pragma solidity ^0.8.20;
contract Timestamp {
    function getTime() public view returns(uint) {
        return block.timestamp;
    }
}
