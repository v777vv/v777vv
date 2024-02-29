- 👋 Hi, I’m @v777vv
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
v777vv/v777vv is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
const data = {
    //1
    "Which of the following is NOT a consensus mechanism used in typical blockchain networks?":"Directed Acyclic Graph (DAG)",
    "What type of digital ledger and database is blockchain technology?":"Permissionless/Decentralized & DLT",
    'Which of the following best describes a "block" in a blockchain?':"A group of transactions ordered, validated, confirmed and added to a blockchain",
    'Which of the following is a layer 1 blockchain platform/network?':'Ethereum',
    'What is the unique identifier for a block in a blockchain called?':'Block Hash',
    'What is the purpose of a merkle tree in a blockchain?':'All of the above',
    'What is the core problem that blockchain solves?':'Secure data validation and storage without a 3rd party',
    'Which of the following is not a decentralized/public blockchain network?':'Hyperledger Fabric',
    'Nonces in ____  network are used to create unique identifiers for transactions to prevent double-spending/replay attacks but are NOT used to determine the selection of validators.':'All of the above',
    'Which of the following represent the bedrock principles of a public blockchain?':'Decentralization, Security, Immutability & Transparency',


    //2
    'What is the benefit of decentralization in blockchain networks?':'All of the above',
    'Which decentralized technology allows users to access web content and services without relying on traditional domain names and centralized DNS?':'IPFS (InterPlanetary File System)',
    'Which of the following best describes how decentralization operates in blockchain networks?':'By distributing control and resources among many unrelated nodes across the world',
    'Which of the following is what makes it possible for a group of strangers to work together to build and maintain a shared database like blockchain, without needing to trust each other?':'Consensus mechanism',
    'Which of the following best describes a blockchain “client”?':"Software that enables interaction with a blockchain while upholding the network's operational protocols",
    'Which of the following does NOT represent decentralization in the Decentralized Finance or DeFi industry?':'Stability and security enabled by banks',
    'Which is the most significant indicator of a highly decentralized blockchain/Web3 network?':'Network with several independent nodes spread across the world',
    'Which of the following is the primary benefit of decentralization in the context of censorship resistance?':'Reduced reliance on intermediaries',
    'What are three primary types of blockchain clients?':'Lightweight or SPV clients, Full clients, and Archive client',
    "Which blockchain consensus mechanism promotes decentralization by allowing any participant to contribute to the network's security and governance, albeit, by using expensive and powerful hardware?":'Proof of Work (PoW)',


    //3
    'How can Proof-of-Stake (PoS) networks, such as Ethereum, achieve a security level comparable to that of Proof-of-Work (PoW) networks like Bitcoin?':'Through a system where validators stake assets as collateral',
    'Which is the most battle-tested, highly secure hashing algorithm used by various blockchain networks to handle transactions and record data?':'SHA-2 and SHA-3',
    'As modern blockchain networks strive to reduce transaction fees, which attack type lets attackers cheaply flood the network with low cost requests to slow/disrupt it?':'DDoS attack',
    'Asides from hashing, which other key cryptographic method does blockchain technology employ to ensure that data doesn’t change during the broadcast of validated transactions between nodes and throughout all blockchain transactions for that matter?':'Digital signatures',
    'Beyond the consensus mechanism, which of the below is the most ideal technique sharded blockchains can employ to maintain the high security levels that public blockchains are known for?':'Auto-rotation of nodes',
    "Consider a malicious attacker creating multiple pseudonymous identities by taking control over a node or group of nodes. These nodes are then used to spread misinformation, disrupt consensus, or attempt to influence the network's decisions. What is the nefarious act known as in the context of blockchain?":'Sybil attack',
    'Which term is commonly associated with the practice of prioritizing certain transactions on a blockchain by reordering them for potential financial gains, especially in the context of DeFi platforms?':'MEV (Miner Extractable Value)',
    'Safe deposit boxes (or bank lockers) are secured by a key that only the owner (custodians like banks) have access to. Similarly, what protects digital assets owned by users themselves on a blockchain?':'A pair of public and private keys',
    'Why do experts often emphasize addressing security issues at Layer 1 of a blockchain rather than relying solely on Layer 2 blockchains and other scaling solutions?':'Layer 1s is the foundational layer known to provide a very high level of security and decentralization, benefitting the entire network and all dapps built upon it',
    'What is the primary reason for keeping a safe backup of your passphrase (or seed phrase/backup codes) when using blockchain wallets, even though other security measures mentioned here may also apply?':'To recover your account if you lose your private keys',



    //4
    'What is the primary purpose of improvement proposals or blockchain standards like EIP or BIP (Ethereum/Bitcoin Improvement Protocols) in the Ethereum/Bitcoin ecosystem?':'B & C',
    'In the Ethereum blockchain, if someone were describing the overall structure and various levels of data organization, which of the following statements is accurate?':"The 'Global State' represents the entire state of the blockchain at a given moment, the 'Current State' emphasizes its latest status, the 'Account State' pertains to individual balances, nonces, and related data for Ethereum addresses, and the 'Contract State' refers to the specific code and storage for smart contracts",
    'What type of blockchain network or platform allows anyone to participate in running nodes, anyone can read from or write to and is permissionless?':'Public blockchain',
    'Which of the following reasons explains why specialized sandbox environments called testnets or test networks are crucial for blockchain platforms?':'They provide environments to simulate the blockchain network for testing purposes before deploying on the mainnet, which involves real world value',
    'In which layer of blockchain architecture do smart contracts and dapps primarily operate while the end users directly interact with?':'Application Layer',
    'Which statement accurately describes the relationship between ERC standards (Ethereum request for Comments) and EIPs in the Ethereum ecosystem?':'ERC standards, like ERC-20 and ERC-721, are types of EIPs that specifically define token standards on Ethereum',
    'What is the role of Virtual Machines like Ethereum Virtual Machine (EVM) in blockchain architecture?':'All of the above',
    'Which key property in blockchain helps it to achieve both these desired outcomes - high fairness and prevent double-spending?':'Timestamp',
    'Choose the correct answer. Which consensus algorithms are used by L1 blockchains, Bitcoin and Ethereum respectively?':'Bitcoin - Proof of Work (PoW), Ethereum - Proof of Stake (PoS)',
    'What is the primary purpose of a smart contract in a blockchain network?':'Automatically executing predefined instructions when specific conditions are met',



    //5
    'In public blockchains, what permanent consequence occurs when validators fail to achieve consensus on the upcoming blocks or transactions to be appended?':'The blockchain splits into two separate chains (hard fork)',
    'Which feature of blockchain and smart contract platform represents this statement “A decentralized exchange (DEX) can be combined with a decentralized lending protocol to create a new application that allows users to borrow and lend assets while also trading them.”':'Atomic Composability',
    'What is a primary consequence of a blockchain network relying on high staking requirements and increased processing power (vertical scalability) while having limited throughput and scalability?':'Network congestion leading to high and unpredictable fees for end users',
    'Which feature ensures that transactions on the blockchain are processed quickly?':'Throughput',
    'Which feature addresses the potential of a public blockchain to handle increased transaction loads?':'Scalability',
    'Why is high fairness important in a blockchain network?':'It prevents certain participants from gaining undue advantage by manipulating transaction order',
    'Which of the following best describes the average transactions per second (TPS) comparison between a centralized network like Visa and typical public blockchain networks?':'Visa processes significantly more transactions per second than public blockchain networks',
    '"Blockchain trilemma” or “Scalability trilemma," is a longstanding issue that hinders the mass adoption of blockchain networks. Which three features are encompassed by this trilemma in public blockchains?':'Security, decentralization and scalability',
    'Which feature in blockchain ensures that once a transaction is confirmed, it cannot be reversed?':'Finality',
    'Which of the below is an ideal and a highly decentralized solution for scalability issues in public blockchains?':'Adding more low end machines/nodes',




    //6
    'Which nodes are primarily responsible for actively participating in the process of ordering and validating transactions, forming consensus, proposing a block, and securing the network in PoS networks?':'Validator nodes',
    'What type of nodes typically store the complete blockchain transaction history while maintaining the current state of the ledger?':'Full nodes',
    'In Filecoin, a decentralized storage platform, which type of nodes offer storage capacity, furnish cryptographic evidence of their reliable data storage, and swiftly deliver stored data to users when requested?':'Storage & Retrieval nodes',
    'What are nodes in a blockchain network?':'Participants or computers that order, validate, relay, and store transactions and blocks in the network',
    'What type of nodes provide an interface between traditional web browsers and IPFS (InterPlanetary File System), a decentralized storage network?':'Gateway nodes',
    'What type of nodes typically store the complete blockchain transaction history while maintaining the blockchain’s historical data as well?':'Archive nodes',
    'What is the most accurate statement with respect to consensus mechanisms in sharded blockchain networks?':'Each shard reaches consensus on its own transactions',
    'Which nodes are known to facilitate data transmission and propagation across PoS networks including sharded and cross-chain networks?':'Relay nodes',
    'Which of the following best describes the role of blockchain client software for nodes?':'Allows nodes to operate, validate transactions, and maintain consensus on the blockchain network',
    'In a blockchain network, which type of nodes provides interfaces for querying and interacting with the blockchain without the need to store the full transaction history?':'RPC Nodes',



    //7
    'Which of the following best describes the difference between on-chain and off-chain solutions in the context of blockchain technologies?':'On-chain solutions pertain to data and transactions stored directly on the main blockchain, while off-chain solutions involve data and transactions processed outside of the blockchain',
    'What is the primary role of a wallet in blockchain?':'Acting as a bridge between users and the blockchain network',
    'Which of the following popular software clients are used for interacting with the Bitcoin and Ethereum blockchains respectively?':'Bitcoin - Bitcoin Core, Ethereum - Geth',
    'In the evolving landscape of blockchain infrastructure, how do decentralized storage networks differentiate themselves from traditional data storage mechanisms?':'By fragmenting data into chunks and distributing them across nodes, ensuring redundancy and resistance to censorship without centralized control',
    'How does a “wallet” primarily interface with the blockchain network':'By allowing users to create and broadcast transactions using cryptographic keys',
    'What necessitated layer 2 blockchains and solutions on top of layer 1 blockchains?':'All of the above',
    'Why are development tools/frameworks like Truffle, Hardhat and Anchor essential for blockchain development':'They are back-end tools for developers to test/deploy smart contracts and dapps seamlessly to deliver decentralized products and services for end users',
    'In the context of blockchain technology, what primary role do websockets play?':'Real-time event listening and data updates',
    'Which of the following is not considered a layer 2 solution in blockchain?':'Sharding',
    'Which of the following are considered to be part of blockchain infrastructure?':'All of the above',


    //8
    'What is the term used to refer to the fee paid by end users to execute a function in a smart contract such as transferring tokens, voting in a DAO or minting an NFT?':'Gas Fee',
    'Which of these is NOT a use case for smart contracts?':'Real-time weather updates',
    'How are smart contract vulnerabilities typically exploited?':'By taking advantage of poorly written contract code',
    'What are the benefits of using smart contracts to manage supply chains?':'All of the above',
    'Which of the following options represent the primary challenge for smart contracts and the larger blockchain industry as a whole?':'Smart contracts are vulnerable to bug and other flaws in the code resulting in security breaches and loss of funds',
    'How exactly did Ethereum elevate the potential of blockchain technology pioneered by Bitcoin? Choose the correct answer.':'Ethereum revolutionized the way real-world applications function by introducing smart contracts and decentralized applications, eliminating the need for intermediaries',
    'What is the significant advantage of using oracles in smart contracts?':'Allow contracts to retrieve external world data',
    'Which of the following is the MOST accurate definition of gas estimate and gas limit?':'Gas estimate is the estimated amount of gas that a transaction will require, while gas limit is the maximum amount of gas that a user is willing to spend on a transaction',
    'Which of the following best describes a complex smart contract?':'A contract that autonomously performs a series of actions based on external data inputs and has multiple conditional outcomes.',
    'In the context of Ethereum dapp development, how is the Solidity programming language best characterized?':'Smart contract programming language',

    //9
    'Which term refers to a collection of smart contracts that act as a back-end with a front-end user interface?':'Decentralized Application (Dapp)',
    "On which of the following factors does a dapp's performance primarily depend?":'Performance of the underlying (L1) blockchain',
    'Which of the following is a use case of decentralized application (Dapp)?':'Automated Market Maker (AMM)',
    'Which layer on a L1 blockchain does smart contracts and dapps typically reside?':'Smart Contracts and dapps reside in the same application layer since smart contracts are simply the backend logic for dapps',
    'What is the main distinction between smart contracts and dapps (Decentralized Applications)?':'Smart Contracts facilitate, verify, or enforce the negotiation or performance of a contract, while dapps are the front-end interface of smart contracts',
    'Which component in a dapp ensures that it can operate without a central authority?':'Smart Contracts',
    'Which of the following platforms does NOT function both as a Layer 1 (L1) blockchain and as a smart contract platform enabling decentralized solutions and applications for end users?':'Bitcoin',
    "In a dapp, what is the role of a 'token'?":'All of the above',
    'How can dapps be described in terms of governance?':'They are usually governed by consensus among network participants',
    'Which of the following does not operate as a decentralized application (dapp)?':'iPhone App Store',


    //10
    'Why are oracles considered an important blockchain interface?':'They allow blockchains and its smart contracts to interact with external data sources',
    '_____  are blockchain systems that run parallel to a “mainchain" or L1 blockchain providing a mechanism to offload transactions from the mainchain, while performing their own consensus mechanism to reduce congestion and allow for faster processing times and interoperability.':'Sidechains',
    'What is the use case of Zero-Knowledge Proofs (zk-proofs) technology in blockchain?':'All of the above',
    '_____ platforms aggregate and interpret vast amounts of on-chain data to produce useful metrics and insights about network health, economic activity, market sentiment, and more.':'On-chain Analytics',
    'Which Ethereum Layer-2 scaling solution processes transactions off-chain assuming them to be correct unless proven otherwise requiring a dispute resolution window?':'Optimistic Rollups',
    'What is the common objective that blockchain bridges, atomic swaps, and synthetics aim to achieve in the Web3 ecosystem?':'Facilitate seamless interactions or value transfer across different blockchains',
    'Which statement best describes the differences among lightweight wallets, full-node wallets, and third-party wallet applications in the context of blockchain?':"Lightweight wallets don't store the entire blockchain but allow transactions, full-node wallets store and verify the entire blockchain, and third-party wallets are applications developed by external entities to manage keys and transact.",
    "Which (Ethereum) Layer-2 scaling solution utilizes zero-knowledge proofs to cryptographically ensure every transaction's correctness without requiring fraud verification windows or challenge periods?":'zk-Rollups',
    'What role does a blockchain explorer play in the blockchain ecosystem?':'It enables users to view detailed information about blocks, transactions, and addresses',
    'Which of the following best describes the primary function of the MetaMask web browser extension?':'A wallet interface for interacting with Ethereum-based dapps',
    
  }
  function test(){
    let arr = document.querySelectorAll('.active-step .ays_position_initial') 
    let ask = document.querySelectorAll('.active-step .ays_quiz_question')[0]
    // let index = document.getElementsByClassName('ays-live-bar-percent ays-live-bar-count')[0].innerText
    for(let i = arr.length-1; i < arr.length; i--){
      console.log(data[ask.children[0].innerText])
      if(arr[i].innerText.indexOf(data[(ask.children[0].innerText).trim()]) > 0){
         arr[i].click()
        break
      }
    }
    }

    
