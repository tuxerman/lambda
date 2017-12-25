---
layout: post
title: "Blockchain"
description: "Notes and resources on blockchains, cryptocurrency, etc."
thumb_image: "documentation/sample-image.jpg"
tags: [tech, blockchain]
---

### Why
- [What money is today, and what Bitcoin wants to be](https://www.youtube.com/watch?v=l1si5ZWLgy0): A crisp, everyman's introduction to the motivation behind the whole project.
- [Engineering the properties of Money](https://www.youtube.com/watch?v=MxIrc1rxhyI)

### How
- [How Bitcoin works under the hood](https://www.youtube.com/watch?v=Lx9zgZCMqXE)
- Building a tiny blockchain with Python
  - [Part 1](https://medium.com/crypto-currently/lets-build-the-tiniest-blockchain-e70965a248b), [Part 2](https://medium.com/crypto-currently/lets-make-the-tiniest-blockchain-bigger-ac360a328f4d)

### Scaling 
#### Delivering Liberty, at Scale - Andreas Antonopoulos
- <iframe width="560" height="315" src="https://www.youtube.com/embed/AecPrwqjbGw?rel=0" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
- How do we scale to transaction counts many orders of magnitude higher than we have today?
- Increase block size? We may need blocks EIGHT orders of magnitude larger if we wanted to support micro-nano-transactions in a world where Bitcoin is used by a billion people. That's a petabyte of data being downloaded, verified and processed every ten minutes. Nope.
- We didn't put enough privacy, security in the base layers in the internet. That led to them being compromised. Five companies route > 90% of internet traffic worldwide. Every single intelligence agency legally spies on everyone (except its own people) via these. Tor and friends can only do so much on L2 when L1 is weak in security.
- So, how do we scale while retaining decentralization, independence, privacy, security, autonomy and liberty in the base layers of these cryptocurrencies?
- One solution: Move to additional layers. Move a large chunk of everyday, micro-transactions off the primary chain, while making sure that the primary chain is robust when it comes to the key principles we want to uphold.

#### Lightning Network
- [Official Site](http://lightning.network)
- [Reddit ELI5](https://www.reddit.com/r/Bitcoin/comments/7czwtx/can_someone_explain_the_lightning_network_to_me/dptzzgo/)
- In progress..

#### Segwit