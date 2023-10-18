# BLOCKCHAIN-FOR-PRODUCT-SALES-AND-MANAGEMENT
Supply Chain Management System with Blockchain
Introduction:
This project is a Supply Chain Management System built using blockchain technology. It aims to improve transparency and security in product distribution by tracking transactions from the manufacturer to the end client. The system incorporates features like transaction registration, proof-of-work consensus, Merkle tree-based hashing, and QR code generation. It also addresses common distribution issues by resolving disputes and managing security deposits.

Table of Contents:
●Technology used
●Features
●Prerequisites
●Installation
●Usage
●File Structure
●Sample Scenarios
Technology used:
●Python


Features:
1.Participant Registration: Register manufacturers, distributors, and clients with security deposits.
2.Blockchain Implementation: Use a basic blockchain with proof-of-work consensus.
3.Merkle Tree: Calculate the Merkle root of transactions in each block.
4.QR Code Generation: Generate QR codes to check product status in the supply chain.
5.Delivery Management: Ensure that product deliveries are confirmed by both distributors and clients.
6.Issue Resolution: Handle issues where either the distributor or client claims a different delivery status.

Prerequisites:
Before running the system, ensure you have the following prerequisites:
●Python (version 3.x)
●PIL (Pillow) library for QR code generation (pip install Pillow)

Installation:

Usage:
1.Participant Registration: Run the system and register manufacturers, distributors, and clients with their respective security deposits.
2.Transaction Registration: Add transactions to represent product movements within the supply chain.
3.Blockchain Management: Mine blocks to secure transactions using the proof-of-work consensus algorithm.
4.QR Code Generation: Generate QR codes to check the status of a product in the supply chain.
5.Delivery Confirmation: Ensure that both distributors and clients confirm product deliveries.
6.Issue Resolution: Handle issues where there are discrepancies between distributor and client claims regarding product dispatch and receipt.
7.Balance Checking: Check the security deposit balance of registered participants.


File Structure:

Sample Scenarios:
To understand how the system works, consider these sample scenarios:
1.Participant Registration: Register a manufacturer, distributors, and clients.
2.Transaction Registration: Add transactions representing product movements.
3.Blockchain Management: Mine blocks to secure transactions.
4.QR Code Generation: Generate QR codes to check product status.
5.Delivery Confirmation: Ensure distributors and clients confirm product deliveries.
6.Issue Resolution: Handle issues when disputes arise regarding product dispatch and receipt.
7.Balance Checking: Check participant security deposit balances.



