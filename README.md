# SimpleArray.sol
Completely agree with this point.
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract SimpleArray {
    uint256[] public numbers;

    function addNumber(uint256 _num) public {
        numbers.push(_num);
    }

    function getLength() public view returns (uint256) {
        return numbers.length;
    }
}
Remove unused code
Optimize gas usage
Update comments and docs
Fix typo in code
Add validation check
