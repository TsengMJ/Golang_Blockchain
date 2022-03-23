# Golnag Blockchain
Currently I have achieve the following blockchain  mechanisms:

- Blockchain
- Transaction (UTXO):
  - MerkleTree
  - Store Outpus only as SVP Node
- Consensus (POW)
- Wallet 
  - Generate Private Key (Elliptic Curve Cryptography)
  - Generate Public Key from Private Key
  - Generate Address from Puolic Key
  - Wallet management
- Node Connections, include thress type of nodes:
  - Full Node (Record all data of the blockchain as a backup)
  - Miner Node (Calculate POW and update blockchain)
  - SVP Node (Submit transactions only, update to latest state from full node) 
