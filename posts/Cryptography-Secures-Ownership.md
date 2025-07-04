---
title: Behind The Scenes - How Bitcoin's Cryptography Secures Your Ownership
post_status: publish
post_excerpt: I explain what public and private keys are and how they work to secure the ownership of your bitcoin.
featured_image: /_images/BehindTheScenesHowBitcoinsCryptographySecuresYourOwnership.jpg
taxonomy:
 category:
  - tech-deepdives
  - bitcoin-mining
---

<iframe src="https://player.vimeo.com/video/1033155106?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media" title="Behind The Scenes: How Bitcoin&#039;s Cryptography Secures Your Ownership"></iframe>

<div style="margin-bottom:30px;"></div>

## Excerpt

I explain what public and private keys are and how they work to secure the ownership of your bitcoin. You'll learn how Bitcoin addresses are derived from public keys using cryptography. Watch now to understand the basics of Bitcoin’s security and how keys keep your funds safe!

## Transcript

### Viewing a Mined Block in Code

Now you can see how a mined block is looking in the code. This is basically how a block looks in the Bitcoin software. You can see this is the hash of this block; it has a couple of zeros. This block already had 37,371 confirmations, meaning it was... let’s look here; which block do we have now? Now we have 862,239. That's the current block height.

And here, this block was in 277,316 and here you can see this is how the transactions are in a blockchain then when they have been mined. There are hundreds of transactions in that block and these are the SHA256 IDs of IDs or hashes of those transactions. You can also see what the time was, and here is the nonce, and you see the difficulty that has been used at the time of mining that block. And what we also have here is the previous block hash and the next block hash.

### Public and Private Key Cryptography

So, I also talked about public and private key cryptography; this is also very important in Bitcoin. And you know a key pair is controlling access to your bitcoin. You have a private key, which is used to sign transactions and to spend funds, and there is a public key, which is used to receive funds because then it represents the Bitcoin address or it is basically a Bitcoin address or your addresses.

### Bitcoin and Ownership

So Bitcoin is basically ownership. It gives you total ownership if you self-custody. And how does this work? Well, you have a Bitcoin wallet. As soon as you install a new wallet, the wallet gives you a seed — the mnemonic seed phrase — which has 12 or 24 English words in a certain order, and you need to write down the correct order on a sheet of paper or something which is not digital.

### The Seed, Private Keys, and Addresses

The wallet at the same time, from the mnemonic seed (you can imagine the seed being the seed of a tree), it grows private keys. You have the mnemonic seed that basically are the seed for a tree, and the tree has branches, which could be the private keys, and the private keys have leaves, which are then basically your Bitcoin addresses.

And how are those being created? The seed gives you or includes the private key. From the private key with a so-called elliptic curve multiplication, from a public key with the elliptic curve multiplication a public key is being derived. And from the public key, with hashing functions like RIPEMD-160 and the SHA-256, we are talking about, the Bitcoin address is being generated.

### Irreversibility and Security

And what's very important to know for the security of your funds and in general to know is that it's not possible to reverse-engineer the private key from a Bitcoin address or from a public key. So you can give your Bitcoin address to someone because no one can retrieve your private key from it. Nonetheless your seed. And that's why hashing function private key cryptography is so important in Bitcoin.

### The Importance of Hashing

And I think it's very important to understand these concepts on that level. It's enough to understand that level to be able to grasp how secure Bitcoin is built. And this is exactly the start where I wanted to tell you what a hash is. It compresses any amount of data into a fixed-length fingerprint, basically, as we saw in the demonstration. And it's called SHA (Secure Hash Algorithm). It always has 64 characters, and it's being used in Bitcoin for proof-of-work and for the transaction IDs.
