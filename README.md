# variables.sol
//state variable and local vareable  


// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract variableDemo{
    

    //satatevariable
    uint public stateNumber = 500;

    function localtest() public pure returns (uint){
        uint localNumber = 100;
        return localNumber;
    }

}
