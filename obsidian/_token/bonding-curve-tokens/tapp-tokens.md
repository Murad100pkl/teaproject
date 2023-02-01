# TApp Tokens
Each TApp has a token associated with it that's issued along a bonding curve, and buying a TApp's token is just like staking to it. Using TEA to "stake" to a TApp is just like owning stock in a TApp. When a user stakes their TEA in a TApp in return for its TApp token, they can then earn financial benefits in a couple of ways:

1. The TApp token itself is issued along a bonding curve. As supply increases, the price increases with it.
2. As consumers use the TApp, a consume action injects TEA into a TApp, only some of which goes to the developer. The rest of the TEA is exchanged for the TApp's tokens and then distributed proportionally to the TApp token holders.

TApp tokens play an important role in the TEA Project ecosystem as it helps developers bootstrap their projects by enticing investors and other interested users to purchase its TApp token in the hopes of price appreciation (with the developer getting a share of every purchase).

## Bonding curve mechanism
When we say that TApp tokens are issued along a bonding curve, that gives a mathematical formula correlating the total TApp token supply and its price, e.g. **price = sqrt(supply)**.

![Bonding-Curve](https://user-images.githubusercontent.com/86096370/167538641-45c498a2-7ab1-428a-9ecd-b37a051bb9d2.png)

You'll notice in the graph above that there are two curves which determine a buy and a sell price. The difference between these two curves comes from the value of **theta**, which is the percentage of every bonding curve augmentation (increase) that goes directly to the developer. Theta can be thought of as the amount of every token purchase or consume action that goes to the TApp developer. Someone who buys a TApp token and then immediately sells it will only get (1-theta) * (TEA amount they used to purchase TApp tokens), which is exactly what the two curves are depicting. 

It's important to note that while the buy curve is hypothetically what one would pay if they were to purchase a TApp token, the sell curve shows you exactly how much TEA is underlying one TApp token at that supply level. This means that the TEA really is locked in the bonding curve, and selling TApp tokens into a bonding curve essentially releases the underlying TEA while burning the supply of the TApp token. The sell action will also lower the TApp token price along the bonding curve. Mathematically, the sell price is always (1 - theta) * (buy price) anywhere along the bonding curve.

## Consume action
Each time a TApp is used it initiates a consume action. The developer gets their share (**theta**) of the TEA entering the bonding curve, and the rest of the consume revenue is converted to TApp tokens and distributed proportionally to TApp token holders. This is considered the dividend reward for being a TApp token holder.

Because consume actions introduce a new supply of TApp tokens minted along the bonding curve, this means that not only will TApp token holders earn dividends, their token values will also go up at the same time.

## Developers are paid from the bonding curve, not directly from consumers
Although it might make sense to think that a developer gets paid when consumers use their TApp, that's not technically correct. The developers aren't technically paid until the TEA enters the TApp token bonding curve through either consumers using the TApp or investors purchasing its token. You can say that developers are rewarded for both the utility their app brings to consumers and for any bullishness in the eyes of investors.

Developers always gets their **theta** percentage share anytime TEA tokens enter the bonding curve. Let's take a look at the two scenarios where money enters the bonding curve:

#### 1. If an investor purchases TApp tokens,

- theta (%) of the purchase amount goes to the developer.
- the rest of the TEA goes to mint TApp tokens which go to the wallet of the user who purchased the TApp token. 

#### 2. If a consumer uses the TApp,

- theta (%) of the TEA the consumer uses goes to the developer.
- The new tokens generated by this injection of TEA doesn't go to the consumer of the TApp - they already got the TApp's utility since that's what they paid for. But TEA is being injected into the bonding curve which creates new TApp tokens, and these tokens have to go somewhere. These newly minted TApp tokens are distributed proportionally as dividends to existing TApp token holders.



