---
title: WTF Are Bitcoin, Lightning, Liquid, and E-Cash?
post_status: publish
post_excerpt: Get a clear, easy-to-understand overview of Bitcoin, Lightning, Liquid, and E-Cash.
featured_image: /_images/WTFAreBitcoinLightningLiquidandECash.jpg
taxonomy:
 category:
  - lightning-network
  - liquid
  - ecash
---

<iframe src="https://player.vimeo.com/video/1019660763?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media" title="WTF Are Bitcoin, Lightning, Liquid, and E-Cash？"></iframe>

<div style="margin-bottom:30px;"></div>

## Bitcoin, Lightning, Liquid and E-Cash Explainer

Get a clear, easy-to-understand overview of Bitcoin, Lightning, Liquid, and E-Cash in this non-technical explainer video. I use simple analogies to explain complex concepts. Discover the secure Bitcoin blockchain, learn about faster and cheaper payments via the Lightning Network, understand Liquid's sidechain, and explore E-Cash tokens used by Fedimint and Cashu that make offline transactions possible.

## Transcript

### What is Liquid? Is it a Token?

**User Question:** Can you explain what Liquid is? Is it a token?

Okay, let me try to find a descriptive analogy to explain the differences between Liquid, Lightning, and also eCash tokens which are being used by [Fedimint](https://fedimint.org/) and [Cashu](https://cashu.space/) in a hopefully non-technical manner because I believe you don't need to understand all the technicalities behind Bitcoin. Even I don't understand them in the total depth but it's important to at least know the differences between and the tradeoffs between Bitcoin like Liquid, Fedimint, Lightning and all these kinds of things.

So what I'm saying now will definitely not be technically correct. I'm just trying to paint the picture here so that non-technical people, for example my mom, can understand what a side chain is and what the differences between [Liquid, Lightning and eCash tokens](https://www.youtube.com/watch?v=3E12dUnYh90) are.

### What is the Bitcoin Blockchain?

So let's start with Bitcoin. The Bitcoin blockchain is a database consisting of blocks that are chained together and those blocks are filled with the transactions that we're doing and each of these transactions has an end point which is the UTXO, like the amount is the UTXO and the address is where the bitcoin, the asset, your money is sitting.

### A Visual Analogy for the Bitcoin Blockchain

Okay now let's paint another picture of the Bitcoin blockchain. Imagine it is a set of transparent and hollow bricks that are connected to each other by or with cement and their holes are filled with orange sand and each grain of that sand represents a satoshi. As you might know, one satoshi is the smallest unit of a bitcoin and 100 million satoshis are one bitcoin.

In such a wall of bricks your satoshi, your grain of sand, is inside a brick and you cannot easily move the ownership of that grain as it is stuck inside the brick. You can access the grain of sand of course by unlocking it with your private keys. Basically you're digging a hole into the brick wall and sending the grain to someone else and that grain and that end point of that payment is within a new brick.

So you can imagine this is a lot of work and that's why Bitcoin is so secure and why you need to pay transaction fees to move the orange sand grains because that fees are used to secure the wall and the house and the blockchain.

### Lightning Network Explained

Okay let's go on with that example of the house made of bricks with orange sand. To move the sand faster you could for instance drill a hole into a brick and stick a tube into it and it's not only you who is doing this, other people are drilling holes themselves and are putting tubes into it and now they are connecting these tubes all together resulting in a network of tubes and now the grains of orange sand can float freely inside the tubes from one person or one wallet to the other.

They can move faster and cheaper and each grain is a satoshi and that's of course an analogy for the Lightning Network. It is bitcoin, it is exact the same asset, it's an orange grain of sand that is fungible. But the Lightning Network is not a blockchain. It doesn't need a blockchain, it's a network of payment channels.

### Liquid Sidechain Explained

Okay let's move to Liquid. Liquid is a side chain of Bitcoin and that means it also has a database of blocks. It's a blockchain, it's like the bricks for the Bitcoin blockchain but it has different characteristics.

New blocks in the Liquid side chain are connected every minute as opposed to Bitcoin where it's around every 10 minutes and the size of each brick is the same but more transactions can be done on Liquid because Liquid produces 60 blocks per hour whereas Bitcoin only produces 6 blocks per hour.

And at the moment there's much less demand for Liquid and as such the transaction fees are far less than in Bitcoin. Also the Liquid bricks are not transparent like the Bitcoin bricks, you can't look up the amount of a grain that has been sent as transactions in Liquid are confidential.

Of course, if more people are starting to use Liquid then the transaction fees will rise there too but I think this is some years ahead of us.

### Security and Storage in Liquid

So now how do you secure your Liquid satoshis? You can do that with a hardware wallet, the same way you do it with Bitcoin. That's something, for instance, that you can't do with Lightning. There is no cold storage possibility for the Lightning satoshi. You can't have a cold storage to back up your Lightning channels but you can do that with Liquid and that's the reason also why I would not store very large amounts in Lightning.

### Liquid Bitcoin: Blue Grains of Sand

Okay so the Liquid chain of bricks is being filled with blue grains of sand, they are not the same, they are not orange grains, they are not fungible with the orange Bitcoin grains, but they are 1:1 backed by orange grains.

Okay so as an example, how does this work? Also in this image of course that I'm painting. Imagine you own (excuse me, sorry okay) as an example, as a picture, an image of that, you own some orange grains and want to pay less transaction fees over time, so you swap your orange grains from the Bitcoin wall, the Bitcoin blockchain and exchange them for the exact same amount of blue grains which have exactly the same value as your bitcoin had because if you owned, for instance, one bitcoin you now own one L-BTC, a Liquid bitcoin, and the price of a Liquid bitcoin is always the same as the price of bitcoin.

So if your one bitcoin had a value of let's say \$40,000 US, your one Liquid bitcoin has the same value and if the Bitcoin price goes up, your Liquid price goes up exactly the same way.

### Bitcoin vs Liquid vs Lightning

So Bitcoin and Liquid are using blockchains, they are operating with a database with transactions in their blocks. So if you own Liquid bitcoin, it represents bitcoin but in a different way than if you own Lightning bitcoin.

In the Lightning Network, you really own the original orange grains of Bitcoin, on the Liquid blockchain you own blue grains. And the big difference between that is that Liquid is not fully permissionless like Bitcoin or Lightning because the lockup of the orange grains and the issuance of the blue grains is done by a federation of 15 signers.

It's 15 at the moment which are independent and geographically distributed companies. In the Liquid federation, it's basically a federated organization. And 11 out of 15 signers would need to collude to stop you from using Liquid and as long as nothing dramatically happens you can swap your Liquid bitcoin anytime back to bitcoin or swap them to Lightning via the same tool I mentioned before [boltz.exchange](https://boltz.exchange) or with a wallet like [Sideswap](https://sideswap.io) or [AQUA](https://aqua.net/)).

### What are eCash Tokens?

So I hope you understand a little bit better now the differences and the same properties, the tradeoffs between Liquid, Lightning and Bitcoin. So now last but not least I want to mention eCash, eCash tokens. For example, Fedimint or Cashu these are two different new protocols for eCash tokens.

You can imagine that such an eCash token is also a grain of sand but they don't need a blockchain to work, they need mints which are issuing the tokens. A Fedimint, for instance, is a federation that can be made up by companies or individuals who have collaborative custody over the bitcoin that are held in their federation.

### Offline Bitcoin with eCash

But those eCash tokens are neither orange nor blue, let's assume they are black, and imagine there is a community in a village of 100 people. Seven of those people are guarding the federation by safeguarding the community mint. If you are one of the villagers you can take your orange grains, your bitcoin and lock it up with the help of the federation and the mint issues the same amount of black grains for you as an I O U.

So the federation then owes you the orange grains that you've locked up in their custody and in exchange you get eCash tokens that you can use. And to use them to pay for something you don't need a wall of bricks, you don't need a blockchain, you don't need tubes, you don't need a Lightning Network.

You can use them even without the internet so when you're offline as they are only a representation of your orange grains and that is fantastic actually for areas where you have a low internet connection, like maybe in Zimbabwe or in any other African country or if you're sitting in Austria in an area called Waldviertel where you also have very slow internet connection.

So it's not only African countries and so these eCash tokens could be or can be hopefully in the future a great tool to use Bitcoin offline.

### Privacy Benefits of eCash

So in the end, it's also privacy preserving. Why? Because the federation that is securing and holding the mint basically for you knows nothing about how many grains you have spent or to whom you have spent it. And if you want to redeem your orange grains, if you want to have back your bitcoin, you give back, pay back the black grains to the federation and receive your bitcoin.

And the mint doesn't even know if you redeem the grains yourself or if you send someone else or you've sold it to someone else, whatever.

### Final Thoughts

So that was a long and winding but hopefully helpful picture or image, analogy of Liquid, Lightning, Bitcoin and eCash tokens.
