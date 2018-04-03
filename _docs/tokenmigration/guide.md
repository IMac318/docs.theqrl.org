---
title: QRL Token Migration How-To
categories: Token Swap
tags: Token Swap
---

This guide will outline, step-by-step, how to migrate your QRL ERC20 tokens, using our web app, and end up with Main Network QRL coins (Quanta).

> Those with unclaimed ERC20 tokens will be contacted separately in order to assist them in receiving MainNet Quanta (We ❤ Our HODLers)
{: .info}


## Step 1 — Make Your QRL Wallet

![QRLWeb Wallet](/assets/wallet/web/qrlWallet2.png)

### Create QRL Wallet

Make a new QRL address using one of these three methods:
* The **Web Wallet** is the easiest way to generate a new wallet using your web browser. See the <a href="https://wallet.theqrl.org" target="_blank">QRL Web Wallet</a> to get started.
* Run a **Full QRL Node** to generate a new wallet via the CLI tools. This is a more advanced way. Follow the [Full Node Setup Guide](/mining/full-node) to get started.
* Run the **QRL Wallet App** in a local environment. Download and run the QRL wallet software from [GitHub](https://github.com/theQRL/qrl-wallet). See the guide here: [QRL Wallet App](/developers/QRLwallet-app)

> &#x0021; Make sure to back up and secure your new QRL wallet. Funds will not be recoverable if you lose the mnemonic, hexseed or wallet.json file for your QRL wallet.
{: .info}


#### Verify Private Keys

> &#10071; Make certain your private key is valid and will open the wallet. It is your responsibility to verify your wallet backup method works *BEFORE* transferring any QRL to the address.
{: .warning}

Simply open the wallet using your backup method to verify the key is correct.

Compare the wallet address shown in the web wallet you just opened with the address you created before. Once you have a valid and verified QRL wallet generated via one of the above steps, continue with the steps below. 


## Step 2 — QRL Token Migration Page

Once you have a QRL Address of your own, you can open the [Token Migration App.](https://www.youtube.com/watch?v=oHg5SJYRHA0) This is the interface between ERC20 Tokens and real QRL coins.

![QRL Token Swap Page](/assets/tokenswap/swap/migrationPage.png)

The migration app will take the newly created QRL address you enter to generate a new ETH address. This ETH address is connected to the QRL address you just created. 

We call this the **burn** address. Any ERC20 QRL sent to the ETH address the migration app spits out will be automatically converted into QRL upon genesis block and the beginning of the QRL network.

#### Generate a Burn Address

Paste in the QRL address generated in *Step 1*. This is the new address your QRL coins will be sent to when the main network goes live.

![Filled In Token App](/assets/tokenswap/swap/migrationPageFilled.png)

Enter an email address into the next field if you want to receive updates when tokens are swapped. All QRL ERC20 Burn Addresses are monitored and emails will be sent periodically when new transactions are detected to confirm QRL MainNet Wallet balance.

Click “Submit” and an Ethereum address will be generated and displayed to you:

![ETH address](/assets/tokenswap/swap/migrationPageAddress.png)

This is your Burn Address. Each QRL ERC20 token sent to this address will be credited in a 1:1 ratio with QRL coins (Quanta) credited to the QRL Wallet address you entered on MainNet launch.

> &#x0021; If you should lose, forget, or for any reason need to re-generate your QRL ERC20 Burn Address, simply re-enter your QRL wallet address into the token migration app.
{: .info}


## Step 3 — Swapping Tokens

![Sending to burn address](/assets/tokenswap/swap/tokenSwap.png)

Every time you send QRL ERC20 tokens from anywhere *(exchange, myetherwallet, etc.)* to the burn address, your QRL wallet balance will be updated. 

If you entered an email address, you will receive a confirmation message.


#### Check Burn Address

Use the button on the QRL Token Migration page to check the burn address. Enter your burn address into the search field and it will print the details.

![Check Burn Address](/assets/tokenswap/swap/BurnAddressCheck.png)

Verify your burn address and your QRL wallet address match what you've setup. This is where your real QRL will go.

Once you have deposited QRL into the burn address, you will also see the balance awaiting MainNet release. Once live, the address shown will be credited with QRL.

![Check Burn Address](/assets/tokenswap/swap/BurnAddressBal.png)


#### Burn Instructions

Open the ETH wallet that contains your QRL ERC20 tokens and send them to the new burn address you created. 

![Sending to burn address](/assets/tokenswap/swap/SendToBurn-first.png)

It is recommended that you send a small amount of QRL tokens first, and verify they make it through the system. This ensures all steps have been followed correctly. Once you have verified the details are correct and you see the pending balance in the migration app,  continue by sending the remaining balance.

![Sending to burn address](/assets/tokenswap/swap/SendToBurnComplete.png)



## Other/FAQ

Once you have your QRL ERC20 Burn Address, you can send QRL ERC20 tokens to that address, and they will be credited with Main Network QRL coins (Quanta) at launch.

If launch has already occurred, they will be deposited into the QRL Wallet address you provided via a normal transaction on the QRL Network.

If you have any questions, we are available on Discord (Channel #Migration_Support, or send an email to info@theqrl.org

> &#x0021; Those with unclaimed ERC20 tokens will be contacted separately in order to assist them in receiving MainNet Quanta.
{: .info}
