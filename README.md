![Test Badge](assets/logo.svg "Test")

Unlock the true potential of blockchain data with EverLog's cutting-edge tools powered by dRPC, and take your exploration to new heights beyond the limits of JSON RPC.

<a href="//lukso.network">![dRPC Badge](assets/badge-drpc.svg "dRPC")</a>
<a href="/test">![Test Badge](assets/badge-test.svg "Test")</a>
![Prettier Badge](assets/badge-prettier.svg "Prettier")

### Workflow
![Workflow](assets/workflow.png "EverLog Workflow")

## Overview

An indexer extracts transaction data from a blockchain node, transforms it into a readable format, and loads it into a database for easy querying. On-chain data is not searchable by default, which is a challenge for developers building dApps that can interact with on-chain data. The ability to query on-chain data is crucial for efficient and user-friendly dApps.

### What EverLog offers

- **Effortless Event Retrieval:** No more sifting through raw blockchain data. EverLog categorizes and indexes events, making them readily accessible for exploration and analysis.

- **Seamless Integration:** Integrate EverLog with your existing dApps or applications to gain valuable insights from past and ongoing blockchain activity.

- **Powerful Querying:** Utilize an intuitive interface to filter and search through logged events, allowing you to pinpoint specific information with ease.

- **Secure Storage:** Rest assured that your data is protected. EverLog leverages a robust database to ensure the safe and reliable storage of collected blockchain events.

### DB
``eventbridge.sql`` is the DB, runned locally to store the event about Transfer for USD token ``0x7f11f79dea8ce904ed0249a23930f2e59b43a385`` - (120032 total, Query took 0.0103 seconds.)

### Deployed Contract (Testnet)
A sample of an event in a contract:

Sepolia Testnet: contract address `0x34e58A8dC9b869D47AC9EC043e280B5a4D598B76` [view on explorer](https://sepolia.etherscan.io/address/0x34e58a8dc9b869d47ac9ec043e280b5a4d598b76)


### Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

Distributed under the [MIT](https://choosealicense.com/licenses/mit/) License.
