# INS_Project_BlockChain
<h2>Blockchain Demo</h3>

<h3>What is Block Chain?</h3>
A blockchain is a growing collection of documents, known as blocks, that are cryptographically connected together. A cryptographic hash of the previous block, a clock, and transaction data are all included in each block (generally represented as a Merkle tree). To get into the hash, the timestamp proves that the transaction data occurred when the block was written. Each additional block reinforces the ones before it by including the hash of the previous block, creating a chain. As a result, blockchains are immune to code manipulation because the data in any given block, once registered, cannot be changed retroactively without affecting all subsequent blocks.

<h3>How Does Block Chain Work?</h3>
<h5>Body</h5>
Every chain consists of multiple blocks and each block has three basic elements:
The data in the block.
A 32-bit whole number called a nonce. The nonce is randomly generated when a block is created, which then generates a block header hash.
The hash is a 256-bit number wedded to the nonce. It must start with a huge number of zeroes (i.e., be extremely small).
When the first block of a chain is created, a nonce generates the cryptographic hash. The data in the block is considered signed and forever tied to the nonce and hash unless it is mined.
<h5>Miners</h5>
Miners create new blocks on the chain through a process called mining.
In a blockchain every block has its own unique nonce and hash, but also references the hash of the previous block in the chain, so mining a block isn't easy, especially on large chains.
Miners use special software to solve the incredibly complex math problem of finding a nonce that generates an accepted hash. Because the nonce is only 32 bits and the hash is 256, there are roughly four billion possible nonce-hash combinations that must be mined before the right one is found. When that happens miners are said to have found the "golden nonce" and their block is added to the chain.
Making a change to any block earlier in the chain requires re-mining not just the block with the change, but all of the blocks that come after. This is why it's extremely difficult to manipulate blockchain technology. Think of it is as "safety in math" since finding golden nonces requires an enormous amount of time and computing power.
When a block is successfully mined, the change is accepted by all of the nodes on the network and the miner is rewarded financially.
<h5>Nodes</h5>
One of the most important concepts in blockchain technology is decentralization. No one computer or organization can own the chain. Instead, it is a distributed ledger via the nodes connected to the chain. Nodes can be any kind of electronic device that maintains copies of the blockchain and keeps the network functioning.
Every node has its own copy of the blockchain and the network must algorithmically approve any newly mined block for the chain to be updated, trusted and verified. Since blockchains are transparent, every action in the ledger can be easily checked and viewed. Each participant is given a unique alphanumeric identification number that shows their transactions.
Combining public information with a system of checks-and-balances helps the blockchain maintain integrity and creates trust among users. Essentially, blockchains can be thought of as the scaleability of trust via technology.
