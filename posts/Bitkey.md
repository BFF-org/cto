---
title: Pros and Cons Of Jack Dorsey's Bitkey wallet
post_status: publish
post_excerpt: I explore Jack Dorsey's Bitkey, a new Bitcoin hardware wallet that aims to combine convenience and security.
featured_image: /_images/ProsandConsOfJackDorseysBitkey.jpg
taxonomy:
 category:
  - wallets
---

<iframe src="https://player.vimeo.com/video/1021222411?badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture; clipboard-write; encrypted-media" title="Pros and Cons Of Jack Dorsey&#039;s Bitkey"></iframe>

<div style="margin-bottom:30px;"></div>

## Excerpt

I explore Jack Dorsey's Bitkey, a new Bitcoin hardware wallet that aims to combine convenience and security by offering two out of three multi-signatures and interesting features such as a mobile transaction limit, social recovery, and more. Join me as I take a closer look and compare its pros and cons with a special focus on security and privacy.

## Transcript

### Introduction to Hardware Wallet

Jack recently introduced [Bitkey](https://bitkey.world/). What are your initial thoughts on this wallet? Thanks. So, with Jack the person means Jack Dorsey, the founder of Twitter and now the founder of Block and Block is the company that's behind Bitkey, which is a new hardware device that aims to give people easy and secure management of their self-custodial bitcoin. So, it's basically a hardware wallet like the Trezor, the Bitbox02, the Blockstream Jade, or the COLDCARD. And it has the goal to separate the device that your are using to sign and send transactions from the internet. That means, for instance, if you're using a mobile wallet or a wallet on your laptop for your bitcoin, then these bitcoin that you're using with that wallet are in so-called hot storage because the wallet is online and connected to the internet and this gives potential attackers and hackers the opportunity to steal your bitcoin because they basically come through the internet into your mobile device or laptop whereas when you're using a hardware wallet or by creating and storing the seed offline, attackers have no possibility to access and send transactions, sign and send transactions, and then it's called cold storage.

### Background and Features

In my online course [[Crack the Orange](https://my.cracktheorange.com/)] I also have a chapter about how to protect your seed and the differences between cold storage, hot storage and which criteria you need to look out for to choose the perfect wallet for yourself. And this question now, like this hardware wallet is new, it was released in a beta version, I think in December 2023. And so there's not, I don't know a lot about it to be honest. I didn't use it myself but I researched the information on the website. This is how the Bitkey looks and they say it's everything you need in one wallet. What are the pros of the Bitkey hardware device? It consists of a mobile app, the hardware device, and it has of course recovery tools, in case you lose the phone or the hardware device or maybe even both.

### Pros of Bitkey

So the pros of the Bitkey as I see them, is that they want to make self-custody easier, more convenient and secure and therefore they have chosen a different setup than other hardware wallet manufacturers are having because the Bitkey is working with a two of three multi-sig setup whereas other hardware wallets are only having a single seed. So you only have 12 words and that's it. You are alone responsible and with a two out of three, you need two signers to be able to send a transaction out of three. So if you lose one, you have the two others to still get access to your own money. So that's a little bit the more convenient way and the way where they think people are more comfortable with because they don't have a single point of failure. But there are different ways to protect your seed. There is no one solution that's the best solution. Everyone has different possibilities and needs and goals.

### Multi-Signature Setup Details

So this two out of three multi-sig set up works with a mobile key on your phone, so you need an app on your phone. Then you have this hardware device, there you have one key, and one key is on the servers of Block, of the company Block. And so the mobile key on your phone initiates and signs payments up to a mobile limit that you can set, so you can even send funds from your mobile wallet without having the hardware device around, and the mobile key on your phone is also having an encrypted backup key which is stored in your cloud, in your Google drive or in your, what is the other thing, Dropbox in case you lose your phone but you cannot sign higher amounts above your limit that you can set yourself without the hardware device.

So then you have the hardware key on the device, it's the second key which co-signs the payment. It also approves changes to your mobile limit, it authorizes your mobile key recovery and it also authorizes changes to your trusted contacts. Trusted contacts is a way of a social recovery tool or method that Bitkey is offering where you can add people to your trusted contacts who can help you in case you lose access to your phone or your hardware device. This is a very interesting setup I think. And then you have as the third key, the server key, which also initiates and signs payment up (no sorry) this is the one that then signs the payments up to the mobile limit you set because when you're on the go and you don't have your hardware with you and you want to send a transaction then the server key is the second key, so the phone and the server key send the payment, sign the transaction.

The server key also helps you recover your money if you lose your phone or hardware or both. It cannot sign payments over your limit without the hardware and it also cannot authorize recovery attempts with your hardware key or mobile key without your hardware key or mobile key. So what I think is great is also that you can use your funds, as I said before, sorry what's also great, what I said before I think is the possibility to spend funds without having the hardware device on you so you don't need a separate mobile wallet. So when you're using Trezor, Bitbox, Jade, COLDCARD and you have that cold storage usually at home or in a safe place, you don't carry it around, that would be silly, so you need to have a separate mobile wallet and you don't need that with Bitkey because you have this possibility to set a mobile limit where you don't need the hardware with you.

### Break Glass Feature and Recovery

Then also they have the so-called break glass feature, to be honest I don't know why it's called break glass feature but I think it's a great idea because in the end it is a it gives us, it gives you a possibility to download the mobile app, sorry I need to go back, it's not right so the break glass feature is that you can restore the app on your phone without the need for Apple store or Google Play store. So I think that's also a great option because it could be that Apple or Google are saying no, no more self-custody apps in our stores and then we are basically all doomed because we can't download and we don't know where to get the apps from anymore and from that perspective I think this is a very forward thinking from Block.

And then they also have, in case you lose the device, they have an inbuilt 7 day waiting period. So when you request the recovery process, it will trigger a 7 day security waiting period until you receive security notifications that you requested a hardware recovery. And social recovery are also already mentioned if you have a trusted contacts they can help you to overcome this 7-day limit and gain access to your funds earlier.

### Cons of Bitkey

So now to the cons, the points that in my view speak against the Bitkey device. So first, when it came out the first time in December as beta version people were very critical because the code was not open-sourced. So just recently a few days ago all the source code is now open and everyone who understands code can look into it but there is a bigger problem and I think that's privacy. They write on their website Bitkeys two of three multi-signature design ensures that the company cannot access or move a users's bitcoin without their explicit consent. Yes hopefully but the problem is and this is also has been confirmed in December by a representative of Block who said on Twitter: "Yes today our multi-sig design is optimized for safety but that means that Block has enough info to see the transaction history. We are exploring a creative technical solution that may allow us to reduce this visibility but with the same safety". But for now there's absolutely a trade-off, so be aware if you're using the Bitkey device, then the company Block has access to your transaction history.

### Target Audience and Pricing Concerns

Another thing from my perspective is that the point of the targeted audience, I don't know what their target audience for this device is. If it's meant to be a tool for less wealthy people, then I don't believe it will work because $150 is the price. That's way too much for people in many African countries and for many people, because for instance, the average income of a doctor in a hospital in Zimbabwe is $400 a month. So buying a hardware device for $150 is difficult and also many people are not using Google Drive or Dropbox so this can also be a hurdle for using the device.

### Security Concerns with Fingerprint and NFC

And then my personal problem with a wallet like that is that it also uses your fingerprint to unlock it and to sign I believe. So to access the money protected by your hardware unlock it with your fingerprint and tap it with your phone, it connects to your phone via NFC so you never have to risk plugging it into a computer, says their website. I believe that unlocking devices with your fingerprint is something which is very insecure and dangerous, because you can be forced to put your finger on a device to open it or even worse if attackers really want to get to your money and they are ruthless then they will do even worse things to get to your fingerprint and so I always say don't use fingerprints to open critical devices or software. It's not a password.

So and also the question is what if the fingerprint sensor doesn't work anymore. My iPad, for instance, I don't know, it's three or four years old now, it doesn't recognize my fingerprint anymore and I'm only using it on the iPad which I always have at home. So it's not used for anything secure or for my money. And the other thing is NFC. I thought about the implications that Bitkey is using NFC to connect to your mobile phone, I mean I use the tab cards, you know for Bitcoin for instance where you can pay with NFC in a store for instance with bitcoin, I love it but there should be a password on it because there are NFC card scanners or readers and people do use them they just walk by you and these scanners read your card and can take all the funds from there.

I suppose that the Bitkey is designed differently, I mean I hope it's designed differently, and a person would need to get very close to you but still you know if you're in an underground or somewhere where there are a lot of people you don't even realize that someone is having this scanning device on them and is trying to rip you off your money I mean. With all the cards with the NFC chips on it now, I do have a wallet that is basically blocking the access to these cards so that no one can steal money from my NFC cards.
