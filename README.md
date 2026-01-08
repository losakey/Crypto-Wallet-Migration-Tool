This Python repository contains a script designed to automate the transfer of assets (specifically ETH) from an existing cryptocurrency wallet to a newly generated wallet. This tool utilizes the web3.py library to interact with the Ethereum blockchain, enabling programmatic generation of new addresses and the execution of transactions to move funds between them.

## Features

- Automated Wallet Generation: Uses eth_account to create new Ethereum wallet addresses and corresponding private keys on the fly.
- Balance Transfer: Automatically constructs, signs, and broadcasts transactions to move specified amounts of Ether from a source wallet to a destination wallet.
- Network Integration: Connects to the Ethereum blockchain via RPC endpoints (configured for testnets like Sepolia by default).
- Gas Management: Dynamically fetches current gas prices and manages nonces to ensure transactions are processed correctly.

## Use Case

This script is useful for:

- Rotating wallet addresses for security purposes.
- Consolidating funds from multiple temporary wallets into a single master wallet.
- Developers testing transaction flows on testnets without manual intervention.
