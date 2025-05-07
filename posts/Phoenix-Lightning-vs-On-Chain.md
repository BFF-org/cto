---
title: Phoenix Wallet - When To Use Lightning or On-Chain Bitcoin
post_status: publish
post_excerpt: Learn when to use the Lightning Network and when to choose bitcoin on-chain inside the Phoenix wallet.
featured_image: /_images/PhoenixWalletWhenToUseLightningorOnChainBitcoin.jpg
taxonomy:
 category:
  - wallets
  - self-custody
  - lightning-network
---

<iframe src="https://player.vimeo.com/video/1021224038?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media" title="Phoenix Wallet: When To Use Lightning or On-Chain Bitcoin"></iframe>

<div style="margin-bottom:30px;"></div>

## Excerpt

I clarify the different payment formats when using the Phoenix wallet, a self-custody Lightning wallet that also lets you use Bitcoin on-chain by swapping out your funds. Learn when to use the Lightning Network and when to choose bitcoin on-chain. Watch now to understand the difference, to see how you can open channels easily, and save money on fees!

## Transcript

The Phoenix wallet is a pure self-custody Lightning wallet which also offers the possibility to send and receive on-chain bitcoin through swaps. But it's first and foremost a native Lightning wallet. It gives you the opportunity to easily open a channel that connects you with the Lightning Network and it doesn't hold on-chain bitcoin. So you're using Phoenix only for Lightning, not for on-chain bitcoin. For on-chain Bitcoin you can use wallets that are dedicated towards that like the Blockstream Green, Aqua or, which I like because it offers coin control, the BlueWallet. And when you are starting to use the Phoenix wallet it first needs to open a channel for you. For this you need to send bitcoin to Phoenix, you can either send Lightning bitcoin or on-chain bitcoin and this is where the different formats come into place. The cheaper and fastest option to open a channel on Phoenix is to send Lightning funds to the Lightning invoice that Phoenix shows you. The Bitcoin address you can also use that to send on-chain bitcoin to Phoenix. The money will then be swapped from on-chain into your new Lightning channel but as that is coming from on-chain, from the blockchain, you'll need to pay the first on-chain transaction fee and then the transaction needs to reach 3 confirmations before Phoenix can open a channel for you. To open that channel Phoenix has to conduct another on-chain transaction and is deducting the transaction fees for that one from the funds you sent, that means that in times of congestion on the blockchain, the transaction might be expensive and the opening of the channel might take some time if you haven't set a fee that pushes your transaction into one of the next blocks. You can find more details about Phoenix and other self-custody Lightning wallets in my wallet test which I conducted in January this year in a rural area of Zimbabwe and as I always say: If Bitcoin works there or a wallet works there, it will work everywhere. It's also important and interesting to save money. You can set the maximum fee you want to pay for an on-chain transaction in the Phoenix settings in Channel Management but, of course, if you set it too low the channel cannot be opened because then the transaction will never be confirmed. Only send Lightning funds from within Phoenix to on-chain if it's really really necessary. Maybe because you want to close the wallet because it reduces the size of your channel that means the liquidity and the possibility to receive new bitcoin is shrinking, you need to pay another fee when you need to make the liquidity higher again, so better send funds from your Phoenix wallet that you want to have on chain on-chain with Lightning to boltz.exchange and there swap it into on-chain. So that was the first part of this question. So to conclude, yes the best is to send Lightning funds to Phoenix if you open it the first time to open a channel because it's much cheaper and faster than with on-chain bitcoin and the on-chain bitcoin address is only for you if you want to close the bitcoin or if you want to swap in via on-chain which I don't recommend.