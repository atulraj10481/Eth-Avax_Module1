# Eth-Avax_Module1
ExceptionHandling Smart Contract
The ExceptionHandling smart contract is a Solidity contract that demonstrates the usage of require(), assert(), and revert() statements for exception handling in Ethereum smart contracts.
Contract Details
The ExceptionHandling contract contains the following functions:
setValue(uint _value): This function sets the value of the value variable. It uses the require() statement to validate that the input value is greater than zero. If the condition fails, the function reverts and returns an error message.
getValue(): This function returns the current value of the value variable.
assertExample(): This function demonstrates the usage of the assert() statement. It compares two variables x and y and asserts that they are equal. Since the condition fails, the function execution is halted and an exception is thrown.
revertExample(): This function showcases the revert() statement. It checks if x is not equal to y, and if so, it reverts the transaction and returns an error message.
License
This project is licensed under the MIT License.
Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
