---
title: What Is A Blockchain? - Understand Bitcoin Mining
post_status: publish
post_excerpt: I break down how SHA-256 works and why it’s essential to Bitcoin’s mining and blockchain security.
featured_image: /_images/WhatIsABlockchain-Mystery-Solved.jpeg
taxonomy:
 category:
  - Tech-Deepdives
  - Bitcoin-Mining
---

<iframe src="https://player.vimeo.com/video/1033158997?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media" title="What Is A Blockchain? Mystery Solved - Understand Bitcoin Mining"></iframe>

<div style="margin-bottom:30px;"></div>

## Excerpt

I explain how the SHA-256 algorithm works and why it’s crucial for Bitcoin’s hashing and mining processes. You’ll see how hashes create unique digital fingerprints and how miners work to add new blocks to the blockchain. Watch to understand the tech behind Bitcoin's security!

## Transcript

In general, Bitcoin is built on a foundation of mathematics and cryptography. Bitcoin is basically mathematics, and it's using several key concepts and technologies from cryptography and mathematics. One very important part of that for Bitcoin is public key cryptography, which is generating public and private key pairs that are being used in transactions and for the creation of Bitcoin addresses and the private keys that manifest the ownership of Bitcoin.

So, if you own the private keys, you own the Bitcoin, and you are the only one who can send it. And another big part of Bitcoin's foundations is cryptographic hash functions, and this is where the SHA-256 algorithm comes in. It's creating unique, fixed-size outputs from variable-size inputs, so it's basically a digital fingerprint.

### Understanding SHA-256 with a Demo

I'm going to show you now in a demo how this works, because I think you can much better understand what I'm talking about if you see it. So let me just share my screen with you. Now, also a tip from me: this tool is really fantastic if you want to show someone how Bitcoin works, and what a blockchain is, and why it's secure. Go to this website, show them what I'm doing now, or maybe show them that video on YouTube when it will be there. It's from a guy called [Anders Brownworth](https://andersbrownworth.com/blockchain/), and I found it a couple of years ago, and it was really important for me personally to understand what a blockchain is because everyone was talking about it. It's the most important thing in Bitcoin and the most important invention, to be honest.

### Blockchain and Mining Principles

A blockchain is just a dumb database of transactions; that's all it is. And the SHA-256 hash is a tool in the whole Bitcoin stack of technologies that helps us, and it's creating transaction IDs in Bitcoin and is being used in the proof-of-work system in mining. So let me show you what a hash is. Here, you see a data field, and SHA means Secure Hash Algorithm. With this algorithm, from a set of data, which is text in this sense (you see I'm typing text in there), and you can also see that the hashing function is giving you a hash, which always has 64 characters, meaning numbers and letters, and they are unique for the content in the data field.

So if I change the data, you see that the hash is also changing; if I change it back, it's the same as before. So you see here, "crack the orange" with "e," it's 4638e. If I delete the "e" at the end, it's 37d, and the thing about this hash algorithm is you can copy, well, you can have a huge amount of data inside of this data field, but your hash, your unique fingerprint, always has these 64 characters. And as I said before, it's the same for the same data content, and that's important.

### Blocks and Proof-of-Work

So we're going to use that, or Bitcoin is using it in the building of blocks. So the hashing algorithm not only hides the real content - because what you see, maybe if you give someone the hash or a transaction ID, what you see is this long character line, but you don't know what's inside the data - but you can verify that the data is the correct data with the hash. So that's one function. And the second function is it reduces the amount, of course, of data that has to be stored on the computers when you only save the hashes, which is happening in Bitcoin, I think in the Merkle trees.

Okay, the next thing, so now I have this hash algorithm. This is a block, it's a scheme of a block on the Bitcoin blockchain; it's the first block. It has a so-called nonce, and you see the data field again, and here I have the same SHA-256 hash result. I have a button that's called "mine."

Now it's getting interesting. So you know, my computer is running this website, or when I click, my computer is running this calculation here to result in the hash. So I do the same thing as before; I put in some text, you see this hash has changed, and also the color of the block has changed because now I changed the content. Now I want to mine it; I want to basically put in work to prove, proof-of-work, that my computer has done the work and it mined that block.

### Mining and Hashing Difficulty

The goal of mining is, you always hear about the calculations that the Bitcoin miners have to run, and the one who solves the puzzle as the first can put the block onto their blockchain and will gain their reward for mining that block. And the whole race is being the fastest in this mining race to find a hash that starts with a series of zeros. So I mine, now you see it taking time; now it has finished because it found a hash that has four zeros at the beginning.

So I put in the data, and what did the computer do? It was changing the nonce. The nonce is basically just a number that the computer is using. It's adding one, one, one, one, and it's using it to find a hash result that has four zeros at the beginning. So if I change the nonce, here it's broken, it's not mined in that sense, it's not valid anymore because it doesn't have four zeros at the beginning. So I put back the nonce that we had before; okay, everything is correct again.

If I want to change a transaction because I'm malicious, I want to double spend to myself, then it's broken again, and I would need to mine again, and now here I have my four zeros again.

### Live Blockchain and Mempool Explorer

I want to show you, I'm switching to the Mempool explorer ([mempool.space](https://mempool.space)). You know, there's a block explorer that is showing the blocks at the moment in time on the Bitcoin blockchain. And if I go here, this is the last block that has been mined, and I can click on it, and you will see here it says "hash." So this block has a hash, and you can see it here on top in the address line, it has a lot of zeros, so much more than the four we have. That means that the computation is much more difficult because you have to be lucky to find a zero.

### How Blockchain is Chained

Okay, so now you've basically seen what mining is, and now let's go to the demonstration of a blockchain. So you not only have one block, you have a second block, you have a third block, you have a fourth, and a fifth block, and they all already have been mined. How do you know that? You know it because you can see here in the hash we have four zeros.

And the most interesting thing, and that's how a blockchain is chained together, is that in the first block you have, or in each block, let's say it that way, in each block you have a previous hash and a hash. So it has to be zero because there is no previous block, but in the second block you can see the previous hash here is exactly that one that is the result of the calculation of this block, 00157. And then you have the result of this block, 0012fa, and what do we have here? 0012fa. This is how the blocks are being chained together.

### Mining Difficulty Adjustment

So now let's put in some data in the first block of a new blockchain. Let's say it's totally new, and you can see it only starts with one zero, not with four. So I'm going to mine this block now. You see the nonce has changed, and it has found four zeros at the beginning. Okay, so now in the second block I have some different data because there are other transactions inside of it.

So this block, the miner takes the so-called block template, the miner takes the hash, puts it in its own block template as previous hash, and collects transactions from the Mempool into their block, and now they mine. Okay, now they found a hash with four zeros, so it's valid, it's very, it's okay. Okay, a couple of minutes later, the next block is being mined, and on and on it goes. This is how one block follows another, always around 10 minutes.

This is secured by the zeros in this hash result that I need to have, meaning if the mining power in the Bitcoin network is so high that the blocks are being mined faster, for example, every five minutes, then the hashing difficulty is being increased by the system itself.

### How Attacks are Prevented

So now what I want to then show you, now this has been mined, so maybe there is some malicious attacker who wants to change their own transactions in a block they have mined before, so they change this transaction to "Hi ho," and you see, of course, the block is red now, so you can see something is wrong, someone tampered with it, and you also can see that all the following blocks are broken too, so this is not a valid chain anymore.

That means the nodes would reject it. That also means that the attacker has to start mining again, and they have to mine faster than the original chain because otherwise they will never be able to overtake them. But the original Bitcoin chain is still being worked on, so you can see that it's really, really difficult to attack a blockchain, and even more so if it's distributed and very well distributed like the Bitcoin blockchain.

### Network Distribution and Node Consensus

What does it mean that it's distributed? It means that you have peer A, so that’s miner A, miner B, miner C, or even your own Bitcoin full node on your computer, which is peer A or B, and there are thousands, hundreds of thousands of these nodes and copies of the Bitcoin blockchain globally stored on many, many different computers from companies, from private people, and so on.

So here we have the same principle as we had before: we have blocks with numbers and nonces, we have data in it, and we have the previous hash and the hash of this mined block. Okay, so what we can see is that in this hash field they are exactly the same. You can also see here in block three, this should be block three now, yes, you see 001200B9, it's exactly the same here as well, 001200B9.

### Real-World Transaction and Fees

Okay, now if I'm going to the right, to the end, let's say where we are at the fifth block at the moment, someone comes in and wants to change Bitcoin, attack it, so you can see this is the attacker and their blocks are broken now, but on the other nodes, the data is still correct, and this is the way how the network, Bitcoin software, finds out that there is someone who is trying to do malicious things and tampering and changing the blocks and trying to change something, but the others know that this isn't true, and that's the reason why the system by itself kicks out this peer for a certain amount of time. I don't know, I can't remember how many blocks, maybe a thousand blocks or something, they are not allowed to be part of the network for that amount of time.

So it doesn't really make sense to start an attack on Bitcoin, and I hope now you also have understood how a blockchain works. Take a look on the Mempool space; I want to show you this is the most recent block. It has a hash, it has a block number, and you can also see it had 7,948 transactions inside of this one block, and here you can see all the transactions.

The Coinbase transaction is the first transaction that the miners put in their blocks, and the oinbase transaction is basically the transaction where they say, "Okay, if I am the fastest in mining that block and I earn the block reward, that is where the block reward is being created." So when they successfully mine a block, they are the first ones to push it onto the blockchain, then in a hundred blocks' time, they will earn the coinbase transaction, the very first transaction in a block.

You can see that's the Bitcoin address from which this transaction was coming, and it's going to these two addresses. One of the addresses, and I assume it's this address, is the target, like the recipient's address, and the other one is a change address. In Bitcoin, every transaction basically has two ends basically. Like yeah UTXOs - outputs: the target, like the recipient, and the change in your own wallet.

Here someone sent 0.003387714 Bitcoin, and I think the recipient was getting 0.003, so the change has to go back to the owner, of course, because the UTXO was too big for this target transaction. Here you can see the fee that was being paid; it was 11.4 sats per VB, in total 1,614 satoshis, which was, at the time, $1 and 2 cent.

To be honest, this person could have saved a little bit because, at the moment, the price for a Bitcoin transaction is three satoshis per vByte, which is only 27 cents, so they overpaid for this transaction. That's why it's always so important if you're doing an on-chain transaction to go into the website called [mempool.space](https://mempool.space) and look at the current fee rate, the current fees you need to pay for your transactions because the wallets sometimes overpay so that they are sure to be in the next block or the block after that.

But if you know a payment isn't urgent, you can send it with [RBF (Replace by Fee)](https://anitaposch.com/rbf) active, and then, if it takes too long for you until it’s settled because you had a too-low fee, you can increase the fee and send the transaction again.
