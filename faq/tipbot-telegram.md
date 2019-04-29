---
description: Sirius (SIRX) Telegram TipBot
---

# How do I use the Telegram TipBot?

## Information

Tips, in **Sirius \(SIRX\)**, are an integral part of our community because they allow us to reward members for their contributions - whether that's for sharing something insightful, providing feedback, completing bounties, testing our various apps or helping promote Sirius vision and technology.

You can earn them, share, or transfer them through simple commands on the [**Telegram**](https://t.me/SiriusTipBot) by interacting with the TipBot.

It is important to note that the Sirius stored as a result of a tip is tied to your Discord account username and are stored on Sirius wallet server. It is your responsibility to withdraw the tips to your Sirius Core wallet. If you plan on storing SIRX on the Discord server, it is a good idea to enable [Two Factor Authentication \(2FA\)](https://authy.com) on your account. The Sirius Team takes no responsibility for lost funds due to negligence.

Join our [**Telegram**](https://t.me/SiriusProject) group.

## Help

This displays a list of tip commands and how to use them.

**Example:**

```text
/help
```

## Balance

Displays the balance of your Discord SIRX wallet.

**Example:**

```text
/balance
```

## Deposit

Displays your Telegram wallet address.

Useful if you want to receive Sirius directly to your Telegram wallet.

**Example:**

```text
/deposit
```

or

```text
/address
```

## Withdraw

Use this to withdraw a chosen amount from your Telegram wallet to another Sirius wallet such as the wallet in your desktop, or to an exchange.

**Arguments:**

```text
/withdraw <address> <amount>
```

**Example:**

```text
/withdraw Scewh4WQFDNTc3JvcgNAQwuoRWbRf22NkR 10
```

## Tip

Want to tip someone?

This will send a tip to your chosen username**.**

**Arguments:**

```text
/tip <username> <amount>
```

**Example:**

```text
/tip @demartini 10
```

You can specify amount before tagging the user.

**Arguments:**

```text
/tip <amount> <username>
```

**Example:**

```text
/tip 10 @demartini
```

You can also tip multiple users at the same time, as long as the number of tagged users matches the number of provided amounts.

**Example:**

```text
/tip @Alpha1111 5 @Beta2222 3 @Gamma3333 10
```

In a multi-tip, you can be free to specify amount wherever you want, as long as the amounts and users match.

**Example:**

```text
/tip 8 @Alpha1111 @Beta2222 2 @Gamma3333 @Delta4444 9 30
```

## R**ain**

This command will rain on active users.

**Arguments:**

```text
/rain <amount> <count>
```

If you specify count, the bot will rain on that many members.

**Example:**

```text
/rain 200 12
```

Or if less members are active, on as many active there are.

**Example:**

```text
/rain 300
```

The TipBot will send `amount` to each active member in the queue.

* By default the maximum members count is 30 \(used if the `count` is not specified\); 
* By default the minimum rain amount is 10 SIRX per user; 
* By default the minimum members count is 5.

## Terms

Displays the terms and conditions for using the TipBot.

**Example:**

```text
/terms
```



