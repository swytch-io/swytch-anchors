# swytch-anchors

In Swytch we combined the best of the capabilities, while bypassing the drawbacks. We do so by using a multistage process. First, the platform creates a hash of the data you submitted (if needed) and builds a Merkle Tree of all the data that you sent to the platform. The root of the Merkle Tree is the Merkle Root, a hash of all the hashes of the individual data items sent to the platform.

Every hour seconds the platform seals that Merkle Root on the Ethereum mainnet.

Since you can verify that an individual hash is part of a Merkle Root, you can prove that an individual data item is part of the Root in a transaction on the blockchain.

For each data item, a data structure is available on the platform that has all the information to reach the proof of existence, the proof of integrity and, if someone signed the data item, the proof of signature.


