---
title: "Common Pool Resources"
date: 2019-09-10T15:26:15Z
draft: false
weight: 160
---
![](/common-pool-resources.jpg)

A [Common Pool Resource](https://en.wikipedia.org/wiki/Common-pool_resource) (CPR) is one which is naturally open for consumption ("size or characteristics make it difficult to exclude potential beneficiaries from obtaining benefits of use") but which is subtractable (faces problems of congestion or overuse) - the latter point is the key differentiator to public goods. 

The [tragedy of the commons](https://en.wikipedia.org/wiki/Tragedy_of_the_commons) is a term [popularized by Garrett Hardin](http://science.sciencemag.org/content/sci/162/3859/1243.full.pdf)[^1] - it refers to a scenario where an open resource is over-exploited because that is in the best interests of individual consumers, while they have no individual imperative to maintain or preserve the resource. Where the group of resource consumers fail to act collectively to preserve or maintain the resource, the tragedy of the commons unfolds and that resource is spoiled for all.

Some examples of common pool resources are irrigation waters and grazing land, more recently the concept has been stretched to include global resources such as the environment and free digital software/media.

Ostrom was awarded the Nobel Economic prize for observing that the tragedy of the commons can often be avoided through effective governance of the common pool resource. Ostrom looks specifically at self-governance of common pool resources by their users, distinct from state or market-based approaches. She identified a number of characteristics of successful governance of CPRs, some of which are relevant to blockchains.

Public blockchains are commons-based, in that they are openly accessible and any new node can join the network - but there is a cost to running the network. Bitcoin full nodes must download and process the entire ledger of transactions from Bitcoin's history, and so the data representing an individual transaction has a cost that must be borne by all full nodes into the future. The ability to write to the distributed ledger must be restricted, because otherwise it would be subject to the free rider problem and over-exploited - the blockchain would become so large that high powered servers are required to run full nodes. Bitcoin [restricts the size of each block to 4mb](https://medium.com/@jimmysong/understanding-SegWit-block-size-fd901b87c9d4)[^2], to keep the cost of running a full node low and encourage more people to do so. People who wish to make transactions must include fees with their transactions that the miners can collect, miners tend to process the transactions with the highest fees.

Blockchains have one big advantage as compared to other CPRs - they allow for the rules of the network to be reliably enforced by participants at minimal expense. Cryptography is key to this capacity, because it makes it much easier for defenders of the network to verify the authenticity of information than it is for attackers to introduce corrupt information.

It is Bitcoin's consensus rules that allow order to be imposed on an open permissionless network. The use of transaction fees to solve the problem of deciding who can make transactions using the limited available block space is a good example of this. It effectively creates an open fee market for block space, which is a robust low-complexity solution. Determining the block size limit is a key decision for the people producing the Bitcoin resource, it's akin to a community deciding how big a fence they want to build around their commons grazing land - bigger might be more profitable, but it's harder to maintain. The mining constituency were keen  on the whole keen to expand the area during the "scaling debate", but the developers as a constituency, who are responsible for long term maintenance, were less keen to expand as this would make it harder for regular users to run a node and "tend to the commons".

The use of hashpower competition to determine who can produce blocks (and collect rewards) is another good example of a rule which imposes order on open access for cryptocurrency.

For physical CPRs it is important to define and know the group of participants or users of the resource, and status can be an important factor in resolving disputes. Ostrom found that it was important to ensure that the community can monitor members' behavior to ensure that the rules are being followed. Bitcoin must operate in an environment where the identity of participants is often unknown, so the rules must be enforced in the same way for all participants.

The consensus rules can be enforced but they must cover every eventuality as they are the only recourse for dispute resolution. There is, by design, no way to exclude a particular entity from using the resource, so the set of possible participants includes everyone. 

Ostrom calls for an accessible low-cost means of dispute resolution - Bitcoin opts to exclude any dispute resolution function beyond the consensus rules.

Ostrom also finds it important that those affected by the rules can participate in modifying the rules. Bitcoin opts to exclude this function in favor of a socially enforced understanding that the rules cannot be changed in any significant way - while allowing the developers (with miner support) leeway to implement backwards compatible changes (soft forks) that add new rules. 

It is the nature of software that makes it impractical to set Bitcoin's rules in stone for eternity. Software must be continually maintained, addressing exploits as they are identified at a minimum. For FOSS projects a lack of updates signals death, as failure to patch weaknesses in dependencies as they are exposed will render the software vulnerable to attack.

The changing of the consensus rules presents a particular problem for public blockchains, as membership or participation is determined exclusively by whether one is following the same rules as the rest of the network. If the rules related to the common pool resource are to change, the rule change must be adopted by all participants at the same time, or they will cease to recognize each other as participants on the same network, reading from and writing to the same distributed ledger.

Bitcoin's consensus rules cover the use of the common pool resource well, otherwise it would not have survived and thrived for 10 years. They do not however address how the common pool resource should be further developed. This creates problems, because everyone agrees that the resource does need further development of some sort or other. 

## References

[^1]: Hardin, G. (1968). The Tragedy of the Commons. *Journal of Natural Resources Policy Research*, *1*(3), 243–253. https://doi.org/10.1080/19390450903037302
[^2]: Song, J. (2017, August 12). *Understanding Segwit Block Size*. Medium. https://jimmysong.medium.com/understanding-segwit-block-size-fd901b87c9d4