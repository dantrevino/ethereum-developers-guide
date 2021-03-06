## Common Bugs/Attacks and Best Practices

###### [Subtleties](https://github.com/ethereum/wiki/wiki/subtleties) - Vitalik Buterin, Ethereum GitHub, 2014 \[4 min read\]

An explanation of the subtleties of Ethereum. Black hats don't often lurk in the daylight of the obvious, but in the darkness of subtleties where much fewer white hats roam. For example, one of the DoS attacks used “note: there is a difference between zero-balance and nonexistent!”

###### [Ethereum Smart Contract Best Practices](https://consensys.github.io/smart-contract-best-practices/) - ConsenSys GitHub \[20 minute read\]

Smart Contract Best Practices guide compiled by [ConsenSys Diligence](https://media.consensys.net/introducing-consensys-diligence-cf38f83948c). This guide provides numerous security tips, overviews of known attacks, and general engineering techniques.

###### [Smart Contract Security Tips - Joseph Chow](https://www.youtube.com/watch?v=_pqDAMRwkzY) - Joseph Chow, Ethereum Foundation YouTube, 2016 \[16 min video\]

In this talk from dev con 2, Joseph Chow of ConsenSys walks us through some common things to avoid when developing and deploying smart contracts, using illustrative examples.

###### [List of Known Bugs](http://solidity.readthedocs.io/en/develop/bugs.html) - Solidity Documentation \[3 min read\]

Occasionally, a nightly version of the Solidity compiler itself may contain bugs. It is suggested to avoid using any compiler version that is known to be faulty in some way.  This page from the [Solidity docs](http://solidity.readthedocs.io/en/develop/index.html) has a list of some of the known compiler bugs.

###### [Contract Safety and Security Checklist](https://www.kingoftheether.com/contract-safety-checklist.html) - King of the Ether \[8 min read\]

This list compiled by [King of the Ether](https://www.kingoftheether.com/thrones/kingoftheether/index.html) records some of the most common known bugs and attack vectors found in Ethereum smart contracts.  Read through this list and then in the following resources, as the following articles will explore some of these in greater depth. Also, explore the bugs within the King of the Ether app via the [Post-Mortem Investigation](http://www.kingoftheether.com/postmortem.html), which lead to the creation of the Contract Safety Checklist.

###### [Analysis of the DAO Exploit](http://hackingdistributed.com/2016/06/18/analysis-of-the-dao-exploit/) - Phil Daian, 'Hacking, Distributed', 2016 \[4 min read\]

This article by Phil Daian explains the reentrancy attack that affected the DAO and cost over $150 million USD.

###### [Tx.Origin and Ethereum Oh My!](http://vessenes.com/tx-origin-and-ethereum-oh-my/) - Peter Vessenes, 2016 \[5 min read\]

Often times, contracts mistakingly use the tx.origin to test for who is calling a function, when they mean to use msg.sender.  This article by Peter Vessenes explains why this is dangerous and can, and has, lead to malicious behavior.

###### [An In-Depth Look at the Parity MultiSig Bug](http://hackingdistributed.com/2017/07/22/deep-dive-parity-bug/) - Lorenz Breidenbach, Phil Daian, Ari Juels, and Emin Gün Sirer, 'Hacking, Distributed', 2017 \[7 min read\]

This article by Lorenz Breidenbach, Phil Daian, Ari Juels, and Emin Gün Sirer explains the exploit that affected allowed hackers \(combination of blackhat and whitehat\) to drain over $200 million USD from Parity Multisignature Wallets v1.5 and above.

###### [Live example of "underhanded solidity" coding on mainnet](https://www.reddit.com/r/ethereum/comments/4e5y30/live_example_of_underhanded_solidity_coding_on/) - Vitalik Buterin, Reddit, 2016 \[2 min read\]

In this reddit post, Vitalik Buterin exposes underhanded code \(code that is written to appear simple, but contains a hidden bug or exploit\) that tried to steal money by naming variables slightly different things so as to be missed by a quick reader.

###### [An Ethereum Roulette](http://martin.swende.se/blog/Breaking_the_house.html) - Martin Swende, 2015 \[10 min read\]

This article by Martin Swende gives an account of his attempt to crack the pseudo-random generation of a roulette smart contract, and eventually being beaten to it.

