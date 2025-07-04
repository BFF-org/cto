---
title: Can Bitcoin and Lightning Wallets Be Used On Multiple Devices?
post_status: publish
post_excerpt: I explain if you can use the same Bitcoin wallet with the same seed on multiple devices.
featured_image: /_images/CanBitcoinandLightningWalletsBeUsedOnMultipleDevices.jpg
taxonomy:
 category:
  - wallets
  - self-custody
---

<iframe src="https://player.vimeo.com/video/1019656067?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media" title="Can Bitcoin and Lightning Wallets Be Used On Multiple Devices？"></iframe>

<div style="margin-bottom:30px;"></div>

## Excerpt

I explain if you can use the same Bitcoin wallet with the same seed on multiple devices (i.e. synchronize it across your devices).

Lightning Self-Custody Wallets: These can't be operated on multiple devices simultaneously. They function as nodes and are connect to Lightning payment channels, necessitating exclusive operation on a single device.

Bitcoin On-Chain Wallets: Synchronization across devices is theoretically feasible but not recommended due to security concerns. Entering your seed into another online device poses significant security risks, compromising the safety of your wallet.

## Transcript

### Syncing Wallets Across Devices

Most apps can sync with other devices. Can any secure wallet do that, or do I need a different wallet (a different seed) for each device?

### Limitations with Lightning Wallets

So for Lightning wallets like Lightning self-custody wallets like [Phoenix](https://phoenix.acinq.co) or [Breez](https://breez.technology), you cannot run those on both, on two devices at the same time. That's simply not possible because these wallets are running nodes basically on your device and these nodes are connected to one or more Lightning payment channels, meaning you can't just synchronize those between two devices, because they are running on one device. So this with Lightning, you can't do that.

### Possibilities with On-Chain Wallets

With Bitcoin on-chain wallets it is possible but, to be honest, I'm not doing it because each device that you import the seed, so let's say you have a smartphone wallet on which you install a Bitcoin wallet and the wallet gives you a seed, as soon as you import that seed into another device, maybe a second smartphone or into your laptop, you are typing the seed words into an online device, so that makes it a little bit more insecure again. But in theory it's possible. I'm not doing it as I said but you can do it.

### Using Blockstream Green on Multiple Devices

So you can, for instance, use the [Blockstream Green Wallet](https://blockstream.com/app/) on your smartphone and use the same seed in the Blockstream Green software for the desktop. So it's possible but with Blockstream Green there's another thing, you know? You have single-sig wallets, so you get 12 words but then you also have multi-signature options in the Green Wallet which is actually a great security mechanism but you need a 2FA application then for it, meaning you receive a code and you have to enter it and I'm not sure if this is possible on two devices at the same time.

### Personal Recommendation

So personally I'm not using it. You can do it but I think it compromises security and I don't really need it, let's say it that way. So you need to decide yourself how you want to do this.
