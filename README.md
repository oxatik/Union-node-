# Union node
Zero-knowledge infrastructure layer

![image](https://github.com/user-attachments/assets/02c77029-b0eb-4f35-bbef-ad0ea0b4b32e)


# overview
 Zero-Knowledge Cryptography: Union leverages advanced ZK cryptography and BLS signatures to enable fast and secure inter-blockchain communication

Consensus Verification: The system is built on consensus verification principles, eliminating dependencies on trusted third parties, oracles, multi-signatures, or MPC schemes

Inter-Blockchain Communication (IBC): Union brings IBC capabilities to multiple chains using its core technology

Scalability: Designed to be a scalable powerhouse with fast transaction generation and settlement

Security: Adheres to fork-choice rules for enhanced security 
Future-proof Architecture: Built with future scalability in mind

Developer-Friendly API: Provides a high-level API usable across different ecosystems

Real-time Messaging: Supports unlimited connections and real-time messaging

Cross-Chain Compatibility: Works with EVMs, SVMs, and altVMs by integrating with various execution environments

GraphQL API: Offers a hosted indexing service at graphql.union.build, allowing developers to query blockchain data efficiently

Caching Mechanism: Implements caching to improve performance for frequently accessed queries

# Team and Investors
Union’s powerhouse team is led by Karel Kubat, the founder and CEO, with a background in building decentralized systems. The project has attracted seed funding of $4 million from investors such as Nascent, Chorus One, and Tioga Capital, signaling strong industry support for its ambitious goal of making blockchain interoperability secure and scalable.

![image](https://github.com/user-attachments/assets/3a8922bf-3702-4863-ba1a-027b9926c3c6)


# Node Setup
# System Requirements
OS: Linux (Ubuntu 20.04 or later)

CPU: 4 cores (we’re serious about performance here)

RAM: 16 GB (because blockchain nodes like their memory)

Storage: 500 GB SSD (plenty of space for all that chain data)

Network: 100 Mbps (you’ll need some speed)

## Installation
# Install Dependencies
Fire up your terminal:



```bash
sudo apt-get update
sudo apt-get install curl git build-essential docker-compose -y  
```
And of course, Docker — because we can’t live without it:
```bash
curl -fsSL https://get.docker.com -o get-docker.sh
sh get-docker.sh  
```
# Clone the Repository
Get ready to clone the Union repo like you’re starring in a hacker movie:
```bash
git clone https://github.com/unionlabs/union.git
cd union  
```
# Build and Initialize Node
Time for some real magic:
```bash
make install  
```
# Initialize your node:
```bash
union-core init "YourCoolNodeName" --chain-id union-testnet  
```
# Start and Monitor the Node
Let’s get things running:
```bash
docker-compose up -d  
```
Keep an eye on it with logs:
```bash
docker logs -f union-node
```

# Validator Setup
Feeling like a blockchain VIP? You can even set up a validator node and start earning rewards for helping secure the network. Stake your tokens and follow the validator instructions in the https://docs.union.build/joining-testnet/creating-validators/

# Optional: Setup Union Account and Mnemonic
To create a new Account and mnemonic, use the following sub-command of the uniond binary.
```bash
uniond keys add $KEY_NAME
  
```
WhereKEY_NAME is the name you would like to use when referencing your key.

Make sure to securely store the new mnemonic phrase that was outputted by the command.

# learn aboute Union

https://union.build/

https://docs.union.build/

https://discord.com/invite/union-build




