[![Litewallet](/images/header-ios.png)](https://itunes.apple.com/us/app/loafwallet/id1119332592)
======================================= 

[![Release](https://img.shields.io/github/v/release/litecoin-foundation/loafwallet-ios?style=plastic)](https://img.shields.io/github/v/release/litecoin-foundation/loafwallet-ios) 
[![MIT License](https://img.shields.io/github/license/litecoin-foundation/loafwallet-ios?style=plastic)](https://img.shields.io/github/license/litecoin-foundation/loafwallet-ios?style=plastic)

![screenshots](/images/screenshots.jpg)
=======================================

## Easy and secure
Bstywallet is the best way to get started with GlobalBoost. Our simple, streamlined design is easy for beginners, yet powerful enough for experienced users. This is a free app.

## Donations
The Bstywallet Team is a group of global volunteers that work hard to promote the use of GlobalBoosts(BSTY). Bstywallet takes alot of time and resources to improve and test features but we need your help.  Please consider donating to one of our addresses:
|                                   Hardware Campaign                                   	|                              General Litecoin Foundation                              	|
|:-------------------------------------------------------------------------------------:	|:-------------------------------------------------------------------------------------:	|
| [QR Code](https://bstyexplorer.globalboost.info/address/Y2bVk5gmxYHMt4Qkw8VSV5ewrgAi6nBjjj) 	| [QR Code](https://bstyexplorer.globalboost.info/address/Y2bVk5gmxYHMt4Qkw8VSV5ewrgAi6nBjjj) 	|

## Completely decentralized

Unlike other iOS GlobalBoosts wallets, **Bstywallet** is a standalone GlobalBoost client. It connects directly to the GlobalBoost network using [SPV](https://en.bitcoin.it/wiki/Thin_Client_Security#Header-Only_Clients) mode, and doesn't rely on servers that can be hacked or disabled. Even if Bstywallet is removed from the App Store, the app will continue to function, allowing users to access their valuable GlobalBoosts at any time.

## Cutting-edge security

**Bstywallet** utilizes AES hardware encryption, app sandboxing, and the latest iOS security features to protect users from malware, browser security holes, and even physical theft. Private keys are stored only in the secure enclave of the user's phone, inaccessible to anyone other than the user.

### Designed with new users in mind

Simplicity and ease-of-use is **Bstywallet**'s core design principle. A simple recovery phrase (which we call a paper key) is all that is needed to restore the user's wallet if they ever lose or replace their device. **Litewallet** is [deterministic](https://github.com/bitcoin/bips/blob/master/bip-0032.mediawiki), which means the user's balance and transaction history can be recovered just from the paper key.

## Features:

- ["simplified payment verification"](https://github.com/bitcoin/bips/blob/master/bip-0037.mediawiki) for fast mobile performance
- no server to get hacked or go down
- single backup phrase that works forever
- private keys never leave your device
- import [password protected](https://github.com/bitcoin/bips/blob/master/bip-0038.mediawiki) paper wallets
- ["payment protocol"](https://github.com/bitcoin/bips/blob/master/bip-0070.mediawiki) payee identity certification


## Localization

**Bstywallet** is available in the following languages:

- Chinese (Simplified and traditional)
- Danish
- Dutch
- English
- French
- German
- Italian
- Japanese
- Korean
- Portuguese
- Russian
- Spanish
- Swedish
 
---
## Bstywallet Development:
[![GitHub issues](https://img.shields.io/github/issues/litecoin-foundation/loafwallet-ios?style=plastic)](https://github.com/litecoin-foundation/loafwallet-ios/re-frame/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/litecoin-foundation/loafwallet-ios?color=00ff00&style=plastic)](https://github.com/litecoin-foundation/loafwallet-ios/pulls)

### Building & Developing Bstywallet for iOS:
***Installation on jailbroken devices is strongly discouraged.***

Any jailbreak app can grant itself access to every other app's keychain data. This means it can access your wallet and steal your GlobalBoosts by self-signing as described [here](http://www.saurik.com/id/8) and including `<key>application-identifier</key><string>*</string>` in its .entitlements file.

1. Download and install Cocoapods to your Mac computer: `sudo gem install cocoapods`
2. Download and install the latest version of [Xcode](https://developer.apple.com/xcode/)
3. Clone this repo & init submodules
```bash
$ git clone https://github.com/mendozg/bstywallet-ios
$ git submodule init
$ git submodule update
```
4. From the root where the Podfile is located, install the pods: `pod install`
5. From the root where the *Xcode Workspace* is located, open the project: `open bstywallet.xcworkspace`
 
### Bstywallet Team:
* [Development Code of Conduct](/development.md)
---
**GlobalBoost** source code is available at https://github.com/mendozg/GlobalBoost
