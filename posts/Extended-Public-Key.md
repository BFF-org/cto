---
title: Phoenix Wallet - Sharing the Extended Public Key for Auto DCA?
post_status: publish
post_excerpt: I discuss if you can securely share your Phoenix wallet's extended public key (XPub) for dollar-cost averaging (DCA) purposes.
featured_image: /_images/PhoenixWalletSharingtheExtendedPublicKeyXPubforAutoDCA.jpg
taxonomy:
 category:
  - wallets
  - self-custody
  - lightning-network
---

<iframe src="https://player.vimeo.com/video/1021226679?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media" title="Phoenix Wallet: Sharing the Extended Public Key (XPub) for Auto DCA?"></iframe>

<div style="margin-bottom:30px;"></div>

## Excerpt

I discuss if you can securely share your Phoenix wallet's extended public key (XPub) for dollar-cost averaging (DCA) purposes. I highlight the wallet's Lightning-only design and explain why combining it with on-chain DCA services is not the best idea. I also provide insights into DCA strategies and how to navigate the changing landscape of transaction fees.

## Transcript

"There is an extended public key on my device in the Phoenix wallet. Is it safe to share it with the exchange for DCA so they send every month the sats to a new Bitcoin address?" As I just mentioned the Phoenix wallet is Lightning only. It does not offer an on-chain wallet and it also doesn't show an on-chain balance. The master public key that you're speaking of that you found in the wallet info is only used for the final wallet, meaning in case your Lightning channel gets closed which can happen sometimes, then your funds are being sent to this master public key, to this Bitcoin address automatically. So I would not use this master public key for any other service, for instance, a DCA service because it conflates the purposes and meaning and what it is actually. And also you would need another Bitcoin wallet, import the seed there to be able to see and manage the funds that are being sent via DCA. So in theory, yes you could use the master public key which is derived from the 12 seed words of your Phoenix wallet and you could also import the 12 seed words into another Bitcoin wallet but this first makes the seed less secure because you have another online device now and I just wouldn't do it. No, don't do that. So this is not for DCA and another thing regarding DCA which means Dollar-Cost-Averaging for everyone, Dollar-Cost-Averaging is a technique where you acquire bitcoin in periods always like in the same interval over and over again, for instance, every Monday the system automatically sends you a certain amount of bitcoin that you want and then you reach an average price of what you have paid for the bitcoin you received. It's clever because you don't lose out maybe so, for instance, if the price of bitcoin is very high and you spend all your money that you have to exchange it to bitcoin and then three weeks later the price goes down you basically lost a little bit so if you buy bitcoin in regular intervals you have an average price that you paid for it in the end which can be of advantage but the problem with auto DCA is that many people have been doing this with small amounts in recent years which was possible because the fees on-chain fees were low but now when we are having on-chain fees sometimes of $5 or $10 or sometimes the highest was I think $70 then these transactions are getting uneconomical. You basically, if you auto dollar cost average with an amount of $10 a week then you have a lot of single unspent transaction outputs with $10 on it and if you want to spend those the fee is higher than those $10. So if you want to start doing auto DCA use only amounts higher, I would say 300,000 sats for instance. If you can't afford that I suggest you start with stacking sats in Lightning or Liquid because the fees are much lower there.