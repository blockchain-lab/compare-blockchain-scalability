# Compare blockchain scalability
Below you can find a table with a big amount of projects currently out there. For comparing the scalability of the projects, the columns 'theoretical throughput' and 'algorithmic complexity' are the most important. If the algorithmnic complexity is that of O(1), it means that the project is not scalable, other than scaling it by parameter tweaking (lower difficulty, larger block size, etc.). If the algorithmic complexity is that of O(n), it says that it is in some way scalable when for example new nodes are added, or in the case of sharding, new shards are created.

| Project                | Founded | Deployed | Consensus  algorithm               | Theoretical  throughput  (tx/s) | Algorithmic complexity | Market  capitalization  ($) | Sources   |
|------------------------|---------|----------|------------------------------------|---------------------------------|------------------------|-----------------------------|-----------|
| Bitcoin                | 2009    | Yes      | Proof of Work                      | 7                               | O(1)                   | 146,304,424,888             | [1]       |
| Ripple                 | 2012    | Yes      | Variation of PBFT                  | 1500                            | O(1)                   | 24.844.146.883              | [2],[3]   |
| Peercoin               | 2012    | Yes      | Hybrid PoW and PoS                 | 10                              | O(1)                   | 38.530.630                  | [4]       |
| Bitshares              | 2014    | Yes      | Delegated Proof of Stake           | 3300                            | O(1)                   | 428.841.437                 | [5],[6]   |
| IOTA                   | 2014    | Yes      | Tangle                             | O(txs)                          | O(txs)                 | 3.607.191.015               | [7]       |
| BurstCoin              | 2014    | Yes      | Proof of Capacity                  | 4                               | O(1)                   | 23.729.199                  | [8]       |
| Ethereum               | 2015    | Yes      | Proof of Work                      | 20                              | O(1)                   | 51,789,793,136              | [9]       |
| Dash                   | 2015    | Yes      | Proof of Work                      | 56                              | O(1)                   | 2.527.063.671               | [10]      |
| BigchainDB             | 2016    | Yes      | PBFT                               | 1+ million                      | O(1)                   | -                           | [11]      |
| Waves                  | 2016    | Yes      | Leased Proof of Stake + Bitcoin-NG | 100                             | O(1)                   | 356.583.000                 | [12],[13] |
| Byteball               | 2016    | Yes      | Tangle                             | O(txs)                          | O(txs)                 | 120.109.376                 | [14],[15] |
| EOS                    | 2017    | No       | Delegated Proof of Stake           | O(n)                            | O(n)                   | 5,212,634,519               | [16]      |
| Cardano                | 2017    | Yes      | Proof of Stake                     | 7                               | O(1)                   | 4.299.615.743               | [17]      |
| Bitcoin Cash           | 2017    | Yes      | Proof of Work                      | 61                              | O(1)                   | 17,104,181,863              | [18]      |
| Bitcoin Lightning      | 2017    | Yes      | Proof of Work                      | O(n)                            | O(n)                   | 146,304,424,888             | [1],[19]  |
| Ethereum with Sharding | 2017    | No       | Proof of Stake                     | O(shards)                       | O(shards)              | 51,789,793,136              | [9],[20]  |
| Tribler                | 2017    | Yes      | Implicit consensus                 | O(n)                            | O(n)                   | -                           | [21],[22] |
| Zilliqa                | 2017    | No       | PBFT                               | O(shards)                       | O(shards)              | 306.444.816                 | [23],[24] |

Sources:
[1] - S. Nakamoto, “Bitcoin: A peer-to-peer electronic cash system.” 2008.
[2] - D. Schwartz, N. Youngs, A. Britto et al., “The ripple protocol consensus algorithm.” [Online]. Available: https://ripple.com/files/ripple_consensus_whitepaper.pdf
[3] - M. Castro and B. Liskov, “Practical byzantine fault tolerance,” OSDI, vol. 99, pp. 173–186, 1999.
[4] - S. King and S. Nadal, “Ppcoin: Peer-to-peer cryptocurrency with proof-of-stake,” 2012. [Online]. Available: https://peercoin.net/assets/paper/peercoin-paper.pdf
[5] - D. Larimer and F. Schuh, “Bitshares 2.0: Financial smart contract platform,” 2015.
[6] - Delegated proof-of-stake consensus. [Online]. Available: https://bitshares.org/technology/delegated-proof-ofstake-consensus/
[7] - S. Popov, “The tangle,” 2017.
[8] - S. Gauld, F. von Ancoina, and R. Stadler, “The burst dymaxion an arbitrary scalable, energy efficient and anonymous transaction network based on colored tangles,” 2017. [Online]. Available: https://dymaxion.burst.cryptoguru.org/The-Burst-Dymaxion-1.00.pdf
[9] - A next-generation smart contract and decentralized application platform. [Online]. Available: https://github.com/ethereum/wiki/wiki/White-Paper
[10] - Whitepaper dash. [Online]. Available: https://github.com/dashpay/dash/wiki/Whitepaper
[11] - Bigchaindb. [Online]. Available: https://www.bigchaindb.com
[12] - Waves whitepaper. [Online]. Available: https://blog.wavesplatform.com/waves-whitepaper-164dd6ca6a23
[13] - Waves-ng stress test: results in! [Online]. Available: https://blog.wavesplatform.com/waves-ng-stresstest-results-in-44090f59bb15
[14] - A. Churyumov, “Byteball: A decentralized system for storage and transfer of value.” [Online]. Available: https://byteball.org/Byteball.pdf
[15] - Byteball — smart payments made simple. [Online]. Available: https://byteball.org/
[16] - Eos.io technical white paper. [Online]. Available: https://github.com/EOSIO/Documentation/blob/master/TechnicalWhitePaper.md
[17] - Cardano. [Online]. Available: https://www.cardano.org/en/home/
[18] - Bitcoin cash. [Online]. Available: https://www.bitcoincash.org/
[19] - J. Poon and T. Dryja, “The bitcoin lightning network: Scalable off-chain instant payments.” 2016.
[20] - Sharding faq. [Online]. Available: https://github.com/ethereum/wiki/wiki/Sharding-FAQ
[21] - P. Otte, M. de Vos, and J. Pouwelse, “Trustchain: A sybil-resistant scalable blockchain,” Future Generation Computer Systems, 2017. [Online]. Available: http://www.sciencedirect.com/science/article/pii/S0167739X17318988
[22] - Tribler - privacy using our tor-inspired onion routing. [Online]. Available: https://www.tribler.org/
[23] - Z. team, “The zilliqa technical whitepaper,” 2017. [Online]. Available: https://docs.zilliqa.com/whitepaper.pdf
[24] - Faq - zilliqa. [Online]. Available: https://www.zilliqa.com/faq.html
