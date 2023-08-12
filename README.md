# CrowdFunding Smart Contract

This Solidity smart contract implements a basic crowdfunding platform, allowing users to contribute to a campaign and vote on payment requests. The contract is deployed on the Ethereum blockchain and provides functionalities for contributors, campaign management, and request approval.

## Features

- Contributors can contribute to the campaign with a minimum contribution.
- Campaign manager can create payment requests for campaign expenses.
- Contributors can vote on payment requests to approve or reject them.
- Approved requests can be finalized to transfer funds to recipients.

## Prerequisites

- Ethereum Wallet or Browser Extension (e.g., MetaMask) to interact with the smart contract.

## Getting Started

1. Deploy the `CrowdFunding` smart contract on the Ethereum blockchain.
2. Interact with the contract through Ethereum Wallets or Browser Extensions.
3. Contribute to the campaign by sending ETH.
4. Vote on payment requests to support or reject them.
5. Campaign manager can finalize payment requests after obtaining majority votes.

## Contract Deployment

1. Deploy the smart contract with the desired target and deadline parameters.
2. Specify the minimum contribution required from contributors.
3. Set the campaign manager's address.

## Usage

- `sendEth()`: Contribute ETH to the campaign before the deadline.
- `refund()`: Refund contributed ETH if the campaign deadline has passed and target is not met.
- `createRequests()`: Campaign manager can create payment requests.
- `voteRequest()`: Contributors can vote on payment requests.
- `makePayment()`: Campaign manager can finalize and make payments for approved requests.

## Contributors

- [Your Name](https://github.com/yourusername)

## License

This project is licensed under the [UNLICENSED](LICENSE) License.

## Disclaimer

This smart contract is provided for educational and demonstration purposes. Use it at your own risk. The contract may contain vulnerabilities and should not be used in production without proper security auditing.

