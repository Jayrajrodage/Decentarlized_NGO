***Decentralized_NGO_Contract***

This repository contains the Solidity smart contract for a decentralized NGO on the Ethereum blockchain. The contract allows for community members to make donations, propose how funds should be allocated, vote on proposals and make transparent and decentralized decision making.

***Features-:***

1.Accepts donations in Ether.

2.Proposal system for community members to suggest how funds should be allocated.

3.Community members can vote on proposals.

4.Transparent and decentralized decision making with the help of smart contracts

5.Refund functionality

***contract_methods-:***

sendEth() : to make a donation.

getContractBalance() : to get the balance of the contract.

refund() : refund functionality, refund will be made if deadline passed and target not met.

createRequests() : only manager can call this function to create request.

voteRequest() : to vote on requests, you must be a contributor.

makePayment() : only manager can call this function to make payment on request which has majority votes.
