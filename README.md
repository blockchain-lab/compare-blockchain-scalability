# Compare blockchain scalability
Below you can find a table with a big amount of projects currently out there. For comparing the scalability of the projects, the columns 'theoretical throughput' and 'algorithmic complexity' are the most important. If the algorithmnic complexity is that of O(1), it means that the project is not scalable, other than scaling it by parameter tweaking (lower difficulty, larger block size, etc.). If the algorithmic complexity is that of O(n), it says that it is in some way scalable when for example new nodes are added, or in the case of sharding, new shards are created.

| Project                | Founded | Deployed | Consensus  algorithm     | Theoretical  throughput  (tx/s) | Algorithmic complexity | Market  capitalization  ($) | Sources |
|------------------------|---------|----------|--------------------------|---------------------------------|------------------------|-----------------------------|---------|
| Bitcoin                | 2009    | Yes      | Proof of Work            | 7                               | O(1)                   | 146,304,424,888             |         |
| Ripple                 | 2012    | Yes      | Variation of PBFT        | 1500                            | O(1)                   | 24.844.146.883              |         |
| Peercoin               | 2012    | Yes      | Hybrid PoW and PoS       | 10                              | O(1)                   | 38.530.630                  |         |
| Bitshares              | 2014    | Yes      | Delegated Proof of Stake | 3300                            | O(1)                   | 428.841.437                 |         |
| IOTA                   | 2014    | Yes      | Tangle                   | O(txs)                          | O(txs)                 | 3.607.191.015               |         |
| BurstCoin              | 2014    | Yes      | Proof of Capacity        | 4                               | O(1)                   | 23.729.199                  |         |
| Ethereum               | 2015    | Yes      | Proof of Work            | 20                              | O(1)                   | 51,789,793,136              |         |
| Dash                   | 2015    | Yes      | Proof of Work            | 56                              | O(1)                   | 2.527.063.671               |         |
| BigchainDB             | 2016    | Yes      | PBFT                     | 1+ million                      | O(1)                   | -                           |         |
| Waves                  | 2016    | Yes      | Leased Proof of Stake    | 100                             | O(1)                   | 356.583.000                 |         |
| Byteball               | 2016    | Yes      | Tangle                   | O(txs)                          | O(txs)                 | 120.109.376                 |         |
| EOS                    | 2017    | No       | Delegated Proof of Stake | O(n)                            | O(n)                   | 5,212,634,519               |         |
| Cardano                | 2017    | Yes      | Proof of Stake           | 7                               | O(1)                   | 4.299.615.743               |         |
| Bitcoin Cash           | 2017    | Yes      | Proof of Work            | 61                              | O(1)                   | 17,104,181,863              |         |
| Bitcoin Lightning      | 2017    | Yes      | Proof of Work            | O(n)                            | O(n)                   | 146,304,424,888             |         |
| Ethereum with Sharding | 2017    | No       | Proof of Stake           | O(shards)                       | O(shards)              | 51,789,793,136              |         |
| Tribler                | 2017    | Yes      | Implicit consensus       | O(n)                            | O(n)                   | -                           |         |
| Zilliqa                | 2017    | No       | PBFT                     | O(shards)                       | O(shards)              | 306.444.816                 |         |
