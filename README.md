**Simple Blockchain Implementation with Flask**
This is a basic implementation of a blockchain using Python and Flask. It demonstrates the fundamental concepts of blockchain technology, including blocks, proof-of-work, and validation.

**Prerequisites**
Python 3.x
Flask

**Getting Started**
Clone the repository:
bash
Copy code
git clone https://github.com/Prisha_C/Blockchain.git

**Navigate to the project directory:**
bash
Copy code
cd Blockchain
Install dependencies:
bash

**Run the Flask application:**
bash
Copy code
python blockchain_app.py
Endpoints
Mine Block: /mine_block
GET request to mine a new block.
Get Full Blockchain: /get_chain
GET request to retrieve the full blockchain.
Check Blockchain Validity: /is_valid
GET request to check the validity of the blockchain.

**How it Works**
Each block contains an index, timestamp, proof-of-work, and the hash of the previous block.
Proof-of-work involves finding a nonce (proof) that generates a hash with a specific number of leading zeros.
The blockchain is validated by checking the hashes and proofs of consecutive blocks.

Contributors
Prisha C
