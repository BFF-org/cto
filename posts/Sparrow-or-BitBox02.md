---
title: Here is How to Manage your Bitcoin UTXOs - Is Sparrow or BitBox02 better for this purpose?
post_status: publish
post_excerpt: I explain why UTXO management is essential for saving on transaction fees, improving privacy, and keeping funds from different sources separate.
featured_image: /_images/HeresHowtoManageyourBitcoinUTXOsIsSparroworBitBox02better.jpg
taxonomy:
 category:
  - wallets
  - self-custody
  - utxo-management
---

<iframe src="https://player.vimeo.com/video/1021730052?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media" title="Here&#039;s How to Manage your Bitcoin UTXOs - Is Sparrow or BitBox02 better?"></iframe>

<div style="margin-bottom:30px;"></div>

## Excerpt

I explain why UTXO management is essential for saving on transaction fees, improving privacy, and keeping funds from different sources separate. You'll also learn the key differences between coin control in BitBox and Sparrow wallets. If you’re looking to optimize your Bitcoin transactions, this video will help you decide which wallet suits your needs best!

## Transcript

### What is UTXO Management?

First, let me explain what UTXO management is. On my YouTube channel, you will find more videos where I'm talking about coin control or [UTXO management](https://www.youtube.com/watch?v=whfUJw1Usko) too, so please go and look them up. UTXO management or coin control is a way to consolidate the on-chain bitcoin that are administered by your wallet. You know that your bitcoin is not inside your wallet; they are recorded on the Bitcoin blockchain, and as long as you haven't spent them, they are technically called UTXOs, where U stands for unspent, TX for transaction, and O for output.

### Why UTXO Management is Important: Fee Considerations

UTXO management is an important thing to do for various reasons. First, if you're having small amounts, for instance, if you have received relatively small amounts like, say, $20 or $1 into your on-chain wallet, then it's important to do UTXO management because we have seen that transaction fees have been spiking as high as $120 for short periods already, like in this year. In the future, when there is more demand for bitcoin on-chain transactions, the fees will rise again, maybe even higher or I'm very sure they will rise higher. At this moment in time, at the end of August 2024, they are as low as 3 satoshis per vbyte, which means that with today's bitcoin price, you would pay 0.25 USD, meaning 25 cents, for one transaction, which is okay. If you, I assume, want to send $20 from Europe to Africa, then 25 cents is actually very cheap. But when the fees rise again, then the transaction fees might be higher than the value of the bitcoin you own. If a transaction fee costs $100, and you have a UTXO worth $20, then this will be wiped out because it will cost you more to send it to someone else than what you own. That's one reason why UTXO management is so important.

### Privacy and Security Considerations

Another reason why UTXO management is important is privacy. For instance, you might not want others to know how much bitcoin you own for security reasons. Imagine you have received a bigger amount of bitcoin, which is sitting on a single UTXO, on the Bitcoin blockchain, and you want to send funds to someone else. Your wallet might just choose this big UTXO and send a part of it. But when you spend bitcoin from that UTXO, the recipient knows the transaction ID and can look up the amount of bitcoin that you own in a block explorer, because each transaction is tracked on the blockchain, the blockchain is public and transparent. So with each, in each block explorer if you know a Bitcoin address from someone who sent you something you can look it up and you see how much is on that address and you might not want to have that because then you might be a target. So, for security reasons it's important to make UTXO management.

### Keeping Funds Separate

And the second thing that you might not want to link funds from different sources together in a new transaction. So you might have different people or organizations that sent you bitcoin, and you might want them to stay separate. Because wallets have their own way to construct transactions if you're sending from your wallet to someone else. Meaning the wallet might choose 3 UTXOs to construct a new transaction to someone else but these 3 UTXOs you might have wanted to take different UTXOs and that you can do with coin control. It's exactly this process of selecting the UTXOs you want to use for a certain transaction.

### BitBox vs Sparrow Wallet Comparison

So coming back to the original question: [BitBox](https://bitbox.swiss/) and [Sparrow](https://sparrowwallet.com/) both have coin control features, that means in general they are having the same function. What they are doing is you can select the coins that you want to use for a certain transaction. It's a great way to do it. So, if you do it on the BitBox it's the same as if you do it on Sparrow. The difference is that Sparrow has more options. In Sparrow I can select, for instance, six, seven, or eight UTXOs and send it to two or three or whatever many new Bitcoin addresses, whereas in the BitBox, I can only send to one new address. So that's as far as I've learned so far and used it so far, that's the only difference between Sparrow and BitBox coin control possibilities
