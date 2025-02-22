# Cryptocurrency-Blockchain-Simulator
This is a simple cryptocurrency blockchain simulator built using C++. It includes essential blockchain functionalities such as transactions, mining, and balance tracking. The project demonstrates key blockchain principles, including hashing, proof-of-work mining, and Merkle trees for transaction verification.

FEATURES:

✅ Transaction Handling – Users can add transactions, ensuring that the sender has a sufficient balance.

✅ Proof of Work (Mining) – New blocks are mined using a configurable difficulty level.

✅ Merkle Tree for Verification – Transactions are secured using a Merkle root.

✅ Blockchain Integrity – The chain validates its integrity with hashes.

✅ Wallet Balances – Users can check balances of different wallets.

TECHNOLOGIES USED:

🔹 C++ – Core programming language

🔹 Data Structures – Used for blockchain management (vector, map, queue)

🔹 Hashing – std::hash for transaction and block verification

🔹 Merkle Tree – Secure verification of transactions

🔹 Proof of Work – Implemented mining using the nonce mechanism

How to Run the Code

Step 1: Download the Source Code

Clone this repository using the command:

https://github.com/timetogetdestroy/Cryptocurrency-Blockchain-Simulator.git

Input / Output

1. Adding a New Transaction

INPUT 1:


Enter sender's wallet: Alice  

Enter receiver's wallet: Bob  

Enter amount: 10  

OUTPUT 1:

Transaction added to pending pool  

INPUT 2:

2. Mining Pending Transactions
   
INPUT 2:

Enter miner's wallet: Charlie  

OUTPUT:

Mining block...  

Block mined! Hash: 0000abcd1234...  

Block successfully mined!  

3. Displaying Blockchain

Output:

=== BLOCKCHAIN STATE ===  

Block #0  

Timestamp: ...  

Previous Hash: 0  

Hash: 0000abcdef...  

Transactions:  

  Genesis -> System: 0 coins  
...
Block #1  

Transactions:  

  Alice -> Bob: 10 coins  

4. Displaying Wallet Balances

Output:

=== WALLET BALANCES ===  

Alice: 90 coins  

Bob: 110 coins  

Charlie: 10 coins (mining reward)  

FUTURE IMPROVEMENT:


🔹 Implement a real cryptographic hash function (SHA-256 instead of std::hash).

🔹 Add P2P Networking for multiple users.

🔹 Introduce Smart Contracts for more complex transactions.
OOUTPUT
