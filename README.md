# kikichain

## Steps
* Open a shell window and run the following command to start the first “node”:
dotnet ./bin/Debug/netcoreapp3.1/kikichain.dll 6001 Edgar

* Open anther shell window and run the following command to start the second “node”:
dotnet ./bin/Debug/netcoreapp3.1/kikichain.dll 6002 Alberto

* Switch back to the first “node”, display Blockchain on-screen by select #3 first
The display shows there is only one block in the Blockchain, Genesis block.

* Switch to the second “node”. Connect the second “node” to the first “node” by select #1 and enter the Url of the first “node”. The first “node” received a handshake message from the second “node”

* It returns with a handshake message to the second “node”

* Display Blockchain on the second “node” by select #3
Same as the first node, there is only one block, Genesis block.

* Add Transaction. Add a new transaction for the second “node” by choose option #2 and provides a receiver name and amount.

* From the display of the Blockchain on the second “node”, you can see a new block is created to contain the new transaction.

* Switch to the first “node” and display the blockchain. You can also see a new node and a new transaction in the new node.

## Final note
This is because nodes in the network broadcast changes in their blockchain. Nodes receive the broadcast will compare the received Blockchain with their local Blockchain. If the received Blockchain is valid and has a longer chain than the local chain, then it will replace the local Blockchain with the received Blockchain.

# url
https://www.c-sharpcorner.com/article/blockchain-basics-building-a-blockchain-in-net-core/
https://www.c-sharpcorner.com/article/building-a-blockchain-in-net-core-proof-of-work/
https://www.c-sharpcorner.com/article/building-a-blockchain-in-net-core-transaction-and-reward/
https://www.c-sharpcorner.com/article/building-a-blockchain-in-net-core-p2p-network/






