# crypto.com-test
Crypto.com take home assignment

Part 1 answers:
1. https://explorer.solana.com/address/GKN45uFdG7WjhyZ4f7BmrXorSbxG7QJtDzGehWkywZLW?cluster=testnet

2. By default, all Solana transactions will expire if not committed in a certain amount of time. A confirmed transaction is when a transaction is when the transaction is committed in to their produced block, a transaction is expired when it has not been commited in to the block after some time.


Part 2 answers:
1. After installing chain-maind, I ran these commands (windows machine)
     .\chain-maind init benjamin8642 --chain-id crypto-org-chain-mainnet-1
     Downloaded https://raw.githubusercontent.com/crypto-org-chain/mainnet/main/crypto-org-chain-mainnet-1/genesis.json manually
     Verified the checksum of the downloaded genesis.json file using
     certutil -hashfile .\genesis.json SHA256

2. 

3. 0.09383145 CRO .\chain-maind.exe query account cro1hsr2z6lr7k2szjktzjst46rr9cfavprqas20gc

4. 6665D5883A7F029B37AE37D8ACDCC5B7BE6982018BB9280814A826CE2D494DDA .\chain-maind.exe query block 13947398
