# Private Keys

As we covered earlier, genuine cryptocurrency wallets store cryptographic keys that control a certain amount of cryptocurrency. From this cryptographic key, the wallet app can determine the amount of cryptocurrency a user owns and derive past transactions associated with the wallet. This cryptographic key is usually referred to as a private key.

> **The wallet app essentially stores your private key, which gives you control over a certain amount of cryptocurrency.**
>
> **A non-custodial wallet app uses the private key to retrieve cryptocurrency balances and past transactions from the blockchain.**

We won't delve into the technical workings of private keys. Just know that a private key refers to the cryptographic key we discussed earlier. Let's explore the security aspects of private keys and related considerations.

## 1. Keep Your Key Private

Scammers often impersonate wallet support teams to trick users into sharing their private keys. If you share your key, scammers can steal your funds.

> **There is absolutely no valid reason to share your private keys with anyone. This applies to all wallets.**
>
> **Never reveal your private key, even when communicating with people who built your wallet app.**

You may reveal your private key only when you intentionally want to transfer ownership of your funds to someone else. Almost all non-custodial wallets provide a way to access and view your private key from within the app.

## 2. Backup Your Private Key

Most non-custodial wallet apps display the private key during setup and prompt users to write it down and store it safely offline.

> **The private key is the only way to restore access to your wallet if the device with the wallet app becomes inaccessible, such as if it is stolen or stops working.**

To simplify backing up the private key, blockchain engineers devised a method to convert it into a set of 12 or 24 regular words. Most non-custodial wallets display the private key in this human-readable form.

Backup your private key carefully, ensuring no typos. The correct order of the words is crucial.

> **If you lose or expose your private key, others can control your cryptocurrency.**

Non-custodial wallets may warn you if you make a typo, but incorrect word order will restore a different, random wallet—not yours.

## 3. Private Key Generation

When you set up a non-custodial wallet, the app randomly generates a secure private key. For the key to be truly secure, it must be truly random.

> **If a non-custodial wallet does not generate a truly random key, it is not safe.**

This is why non-custodial wallets keep their code open for third-party scrutiny. Websites like [WalletScrutiny.com](https://walletscrutiny.com) ensure that wallets on Google Play use the same code as the publicly shared version.

Any good non-custodial wallet should adhere to publicly documented security guidelines and wallet standards.

## 4. One Key, Many Coins

A single private key can control balances for multiple cryptocurrencies. Wallet apps can automatically locate balances for all supported cryptocurrencies using one key.

For example, when creating a wallet on [Deus Wallet](https://deuswallet.com), users get a single private key for all supported cryptocurrencies.

The same private key controls multiple cryptocurrencies, each with its own balance and transactions.

## 5. Balances & Transactions

There are standards designed by engineers to handle private keys for multiple cryptocurrencies. These standards define how wallet apps manage private keys.

> **The wallet uses your private key to derive your payment address for each cryptocurrency. The payment address is what you share with others to receive cryptocurrency.**

By looking at your private key, the wallet app can derive your addresses for Bitcoin, Ethereum, and other cryptocurrencies. Each cryptocurrency has a different address.

When you import the private key to another standard-compliant wallet, it will derive the same addresses.

> **If a private key is generated in a standard-compliant manner, any other standard-compliant wallet should correctly derive payment addresses and past transactions for each supported cryptocurrency.**

Once the app knows the addresses, it connects to the relevant blockchain to retrieve transactions involving those addresses, displaying balances and past transactions.

## 6. Moving Between Wallets

Good non-custodial wallets allow for private key migration between wallets. A private key created in one non-custodial wallet app should be compatible with others.

> **Users should not be restricted to a single wallet provider and should be able to migrate easily to other non-custodial wallet apps.**

If your phone breaks or the wallet app stops working, your funds are safe; you can restore access to your cryptocurrency using the private key, even years later.

When choosing a wallet, look for one that is standard compliant and supports the import/export of private keys.

> **Note: When migrating your private key, the destination wallet must support all the cryptocurrencies controlled by that key.**

If your private key has balances in Bitcoin and Ethereum, but the destination wallet supports only Bitcoin, your Ethereum balance won't be visible. It will still be yours and accessible from another wallet.