---
title: Phoenix Wallet - How To Manage Channels and Liquidity
post_status: publish
post_excerpt: I explain how to open a channel and manage liquidity in the Phoenix wallet.
featured_image: /_images/PhoenixWalletHowToManageChannelsandLiquidity.jpg
taxonomy:
 category:
  - wallets
  - self-custody
  - lightning-network
---

<iframe src="https://player.vimeo.com/video/1021755965?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media" title="Phoenix Wallet: How To Manage Your Channel And Liquidity?"></iframe>

<div style="margin-bottom:30px;"></div>

## Excerpt

I explain you how to open a channel and manage your liquidity in the Phoenix Wallet, making Bitcoin transactions through the Lightning Network easier and more efficient. If you’re ready to learn about optimizing your wallet and saving on fees, hit play.

## Transcript

In the [Phoenix wallet](https://phoenix.acinq.co/), you only have one channel, and you don't need to take care of anything. When you open a new Phoenix wallet, try to open it at a time with low on-chain fees, which is right now, for instance. Then open a bigger channel immediately. I will explain why this is important.

### Channel Capacity Explained

Every channel has a certain maximum capacity. Imagine you have a tube that is filled with water. It's filled to the max, and you can't fill more water into the tube. If you take water out of the tube, you can fill it again. The same is true for Lightning channels. And if you open a channel, the channel will have the maximum capacity of the amount you sent into Phoenix. When you send the first payment into Phoenix, Phoenix opens a channel for you.

### Balance and Inbound Liquidity

In Phoenix, if you look up the open payment channel, you will see that it's called "balance" there. The balance is the amount you can spend, and then you have inbound liquidity. Inbound liquidity is how much you can receive without maxing out the capacity of your channel.

### Increasing Channel Size

But this is only important if you want to receive more than you can from the side of the inbound liquidity because then Phoenix will automatically increase the capacity of your channel. For this, it will take a one-time fee from you because the channel has to be increased. This is done by Phoenix for you, but it has to be increased on the blockchain, which incurs an on-chain fee.

### When to Open a Larger Channel

If on-chain fees are very high at that moment, then you will also, of course, pay a higher fee on making the size of your payment channel bigger. So that's why I say, imagine how much you want to receive in Lightning. If you can afford, open a channel that is already as high as that. And then, you take out the satoshis again, and you can put it into Bitcoin, [Liquid](https://www.youtube.com/watch?v=3E12dUnYh90), or any other self-custodial way when you don't need it, you know, to save it for the for long-term.

### Swapping to On-Chain Without Reducing Channel Size

And if you do that, if you want to send satoshis from your payment channel, from your Phoenix wallet to increase the inbound liquidity (so that you don't have to pay the on-chain fee with Phoenix), the best option is to swap your Lightning via [Boltz](https://boltz.exchange). You send the satoshis there, and you can swap them into on-chain Bitcoin or into Liquid to save it for the long term.

### Important Tip

Do not send the satoshis directly from within Phoenix directly to a Bitcoin on-chain address, because this will reduce the size of your channel and this is not what you want. If you send it via [Boltz](https://boltz.exchange), the channel size stays the same, so that's an important distinction there.
