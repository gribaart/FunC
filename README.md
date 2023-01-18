# FunC
FunC Playground

Objective: To create a calculator smart contract on FunC language that can perform basic mathematical operations such as addition, subtraction, multiplication and division. The calculator contract should be able to accept incoming messages containing the desired operation and two operands, perform the operation and return the result.

Prerequisites:

Familiarity with the FunC programming language
Knowledge of basic mathematical operations and how to implement them in code
Implementation Steps:

Define the function signature for the smart contract that will handle the incoming messages. This function should accept the message body as a slice, the balance and the message value as integers, and the full message as a cell.

Extract the operation and operands from the message body. The operation should be a 32-bit unsigned integer, and the operands should be 64-bit unsigned integers.

Perform the specified operation on the operands and store the result in a variable.

Prepare the response message to be sent to the sender of the incoming message. The message should contain the result of the operation as a 64-bit unsigned integer, the operation performed as a 32-bit unsigned integer and the query_id as a 64-bit unsigned integer.

Send the response message to the sender of the incoming message.

Handle any errors that may occur during the execution of the smart contract, such as division by zero or invalid operations.

Test the smart contract using test cases that cover a variety of operations and operands.

Deploy the smart contract on the TON blockchain.

Note:

The contract should check if the number of operands passed to it is correct.
The contract should check if the operation is valid.
The contract should check if the operands passed to it are non-negative
The contract should check if the query_id is unique.
