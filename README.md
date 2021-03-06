Amoveo
==========

```
Bitcoin Donations: 1GbpRPE83Vjg73KFvTVZ4EnS2qNkiLY5TT
Gifts must be less than $10 000 per person.
```

A scalable blockchain for financial derivatives.
Optimized for scalability via smart contracts inside state-channels.
Has a build-in oracle for integration with real-world data.
Written in Erlang.

Non-technical [mission statement](docs/mission_statement.md).

#### Installing dependencies

You will need Erlang and a couple of libraries before you are able to run this software.

[For Linux](docs/getting-started/linux_dependencies.md)

[For Mac](docs/getting-started/mac_dependencies.md)


#### Running the blockchain

If you just want to launch a node and connect to the network, [look at the quick start guide](docs/getting-started/turn_it_on.md)

#### Using the wallet

Included is a wallet. A wallet is for storing your private key, and for making signatures.
Read here about how to secure your private key with a password. That way you can have tokens.
[Secure your keys](docs/api/securing_keys.md)

### Blockchain Commands

[Read about the commands in depth in the docs](docs/api/commands.md) This is how you control the node once it is started. Includes commands for mining, accounts, channels, oracles, and more.

### Testing

We maintain two kinds of tests: unit tests and integration tests. Final test is always syncing fresh node with public testnet node.

Varied scenarions require specific test setup, e.g. multi hop payment requires three node deployment. This is why we prepared number of testing setups.

If you are looking for more detailed explanation on how the nodes are started look at the [advanced notes on installation](docs/getting-started/build_intro.md).

If you want to know more about how the tests are run see [testing](/docs/merging-and-testing/testing.md).

### Else

[Discuss with the community on the Amoveo reddit](https://www.reddit.com/r/Amoveo/)