# OKX fees: what one spot or perpetual trade actually costs, and why the US fee table says 0.20%/0.35% (full tier tables)

OKX charges **0.08% maker and 0.10% taker** on spot at its regular tier, and **0.02% / 0.05%** on perpetual futures. Those are the global rates, and they're what most people mean when they search for OKX fees.

They're also not what every OKX user pays. The US platform lists **0.20% maker and 0.35% taker** on spot for the same regular tier. The UAE schedule reads 0.40% / 0.60%. Same brand, different regulated entity, different table.

So the number worth knowing is the one that lands on your fill, which depends on where your account sits and which tier you're in. Below are both tier tables in full, three worked examples, and the charges that sit outside the headline rate.

> **Quick version**
> - Global regular tier: spot 0.08% maker / 0.10% taker; perpetual futures 0.02% / 0.05%.
> - A $1,000 spot round trip at taker rates costs about **$2.00**. At $10,000 it's about **$20.00**.
> - Most retail accounts stay on the regular tier. VIP 1 needs $100K in assets or $1M in 30-day spot volume, and the asset path is usually the easier of the two.
> - 👉 [Open an OKX account and check the rate that applies to your region](https://okx.com/join/CASH20)

## The full global fee schedule: Regular and VIP 1–9

You qualify for a tier on **either** column. Meeting the asset figure is enough; so is hitting the volume figure. You don't need both.

| Tier | Qualifies on 30-day spot volume **or** account assets | Maker | Taker | Rate check |
| --- | --- | --- | --- | --- |
| Regular | Under $100K assets or under $1M volume | 0.0800% | 0.1000% | [ Check rate](https://okx.com/join/CASH20) |
| VIP 1 | $100K assets or $1M volume | 0.0675% | 0.0800% | [ Check rate](https://okx.com/join/CASH20) |
| VIP 2 | $200K or $5M | 0.0600% | 0.0700% | [ Check rate](https://okx.com/join/CASH20) |
| VIP 3 | $2M or $10M | 0.0550% | 0.0650% | [ Check rate](https://okx.com/join/CASH20) |
| VIP 4 | $5M or $20M | 0.0300% | 0.0450% | [ Check rate](https://okx.com/join/CASH20) |
| VIP 5 | $20M or $100M | 0.0250% | 0.0350% | [ Check rate](https://okx.com/join/CASH20) |
| VIP 6 | $50M or $200M | 0.0000% | 0.0300% | [ Check rate](https://okx.com/join/CASH20) |
| VIP 7 | $100M or $500M | -0.0010% | 0.0230% | [ Check rate](https://okx.com/join/CASH20) |
| VIP 8 | $250M or $1B | -0.0025% | 0.0200% | [ Check rate](https://okx.com/join/CASH20) |
| VIP 9 | $500M or $5B | -0.0050% | 0.0150% | [ Check rate](https://okx.com/join/CASH20) |

Two things stand out in that table. Maker fees turn **negative at VIP 7**, meaning OKX pays a rebate on orders that rest in the book rather than charging for them. And the volume column is the spot figure; the futures schedule uses different thresholds, so don't carry these numbers across to a perpetual-only strategy.

## The US schedule is a different table, not an update

If your account is with OKX Inc., this is the table that applies. It has its own tiers and its own numbers.

| Tier | Maker | Taker |
| --- | --- | --- |
| Regular | 0.2000% | 0.3500% |
| VIP 1 | 0.1000% | 0.2000% |
| VIP 2 | 0.0750% | 0.1500% |
| VIP 3 | 0.0600% | 0.1250% |
| VIP 4 | 0.0500% | 0.1000% |
| VIP 5 | 0.0450% | 0.0800% |
| VIP 6 | 0.0400% | 0.0700% |
| VIP 7 | -0.0020% | 0.0250% |
| VIP 8 | -0.0050% | 0.0200% |
| VIP 9 | -0.0075% | 0.0175% |

US qualifications start lower in dollar terms: Regular covers up to $100,000 in assets or 30-day volume, VIP 1 begins at $100,001–$200,000 in assets or $100,001–$250,000 in volume, and VIP 2 at $200,001–$2,000,000 in assets or $250,001–$500,000 in volume. The 24-hour crypto withdrawal limit is tied to the same ladder, running from **$10,000,000** at Regular to **$80,000,000** at VIP 7.

Notice that the US VIP 9 maker rate of -0.0075% is better than the global VIP 9 rate of -0.0050%. That looks odd until you remember these are separate entities with separate schedules. Don't average them or pick the better number from each.

## What a trade actually costs: three examples

**$1,000 spot, taker both ways.** 0.10% on the buy and 0.10% on the sell comes to **$2.00**. The same round trip on the US platform at 0.35% costs **$7.00**.

**$10,000 spot, taker both ways.** **$20.00** on the global platform. Put both orders in the book as limit orders instead and the round trip is $16.00, since maker is 0.08%.

**1 BTC of BTCUSDT perpetual at 20,000 USDT.** The fee is charged on position value, not on the margin you post: **10 USDT as taker** (0.05%) or **4 USDT as maker** (0.02%), at any leverage.

The spot formula is worth internalising because it explains why the fee currency sometimes surprises people. **Fee = rate × the amount of crypto you received.** Buy 1 USDT at a price of 10 USD with a 0.1% taker fee and you pay 0.001 USDT, receiving 0.999 USDT. Sell 1 USDT at a limit price for 10 USD as a maker at 0.04% and you pay 0.004 USD, receiving 9.996 USD. On EUR pairs the same logic holds: a €1,000 market purchase of bitcoin costs €1.00, or €0.80 as a resting limit order.

## What sits outside the trading fee

The maker/taker rate is the biggest line item for active traders and close to irrelevant for some others. These are the charges that don't appear in the tier table.

- **Expiry futures settlement: 0.01%.** Charged at settlement to every user, regardless of tier.
- **Forced liquidation is billed at your current taker rate**, on top of the loss that triggered it. A liquidation on a large position can cost more in fees than the trade that opened it.
- **Spread trading gets a 50% discount.** Each leg of a spread trade is charged at half your normal rate.
- **Convert shows no trading fee.** The rate you're quoted is set by OKX, so the cost is inside the price. For anything sizeable, compare the Convert quote against a limit order on the spot book before you swap.
- **Withdrawals cost a network fee per coin**, shown on the confirmation screen. Crypto deposits are free; you only cover the sending network's fee.
- **Funding is not an OKX fee.** It's a payment between long and short holders of a perpetual. Over a multi-day hold it can easily exceed the 0.05% you paid to open.

That last point matters for anyone comparing exchanges on taker fees alone. A 0.05% entry fee on a position held for a week is a rounding error next to three funding payments.

## How OKX decides which tier you're in

Tiers recalculate daily, and the new level is applied between **8:00 PM and 10:00 PM UTC**. Two separate calculations feed it.

Your **30-day volume** is converted pair by pair into BTC at the moment of each trade, then into USD using the daily BTC/USD mid price, which OKX defines as the average of the opening and closing price. That figure refreshes at **16:00 UTC** every day.

Your **asset balance** is snapshotted at 16:00 UTC, converted from crypto to BTC to USD, and includes fiat. The number that counts is the **higher of your 30-day average balance and that day's snapshot**. OKX's own example: a 30-day average of $1,000 with a $500 snapshot on the day means $1,000 is used.

Three details that rarely make it into fee guides:

1. **Your main account's tier covers all sub-accounts**, applied at 16:00 UTC after a sub-account is created.
2. **Spot pairs with 0% maker and 0% taker fees are excluded** from your 30-day spot volume and from market-maker tier assessment. Volume you push through zero-fee pairs won't move you toward VIP 1.
3. **The asset and volume paths are independent.** If you hold $100K on the platform you're at VIP 1 without trading at all.

That last one deserves a sanity check before you act on it. Parking $100K on an exchange to move your taker rate from 0.10% to 0.08% saves 0.02 percentage points, which is $200 a month on $1M of volume. That's a custody decision as much as a fee decision, and for most people it isn't worth it.

👉 [See which fee tier your 30-day volume puts you in](https://okx.com/join/CASH20)

## Which table applies to your account

| Where your account sits | Spot (regular) | Notes |
| --- | --- | --- |
| Global | 0.08% / 0.10% | Perpetuals 0.02% / 0.05% |
| OKX US | 0.20% / 0.35% | Separate tier thresholds and withdrawal limits |
| EEA | 0.08% / 0.10% | OKX Europe Limited, MiCA authorisation in Malta, EUR pairs, SEPA and SEPA Instant deposits, retail perpetual leverage capped at 10x |
| UAE | 0.40% / 0.60% | AED-denominated schedule |

You don't have to work out which row is yours from a blog post. Once you're logged in, **Assets > My trading fees** shows your current tier and the rate for each product you trade. That screen is the authority, and it updates as your tier changes.

👉 [Create an account and confirm your rate under My trading fees](https://okx.com/join/CASH20)

## How to pay less without changing what you trade

**Post limit orders instead of taking.** On $10,000 of spot, maker costs $8 and taker costs $10 per side. Over a round trip that's $16 versus $20. On the top ten pairs the spread is usually tight enough that resting an order a tick inside the touch is realistic.

**Deposit euros by SEPA rather than card.** Card deposits carry third-party processing costs; SEPA transfers to OKX Europe don't.

**Trade the spot book, not the Convert box.** Convert is convenient and shows no fee, but the price you accept is OKX's quote. A limit order gets you the market's price plus the maker rate.

**Pick the withdrawal network deliberately.** The same coin often moves on several networks at different fees, and the receiving wallet has to support the one you choose. This is the single easiest cost to overpay on.

**Climb the tier ladder on whichever column you can actually hit.** For a holder, $100K in assets is a lower bar than $1M of monthly volume. For an active trader it's the reverse.

## How OKX compares on a round trip

Published round-trip platform fees, taker both ways, on a $1,000 trade:

| Exchange | Round trip | Cost on $1,000 |
| --- | --- | --- |
| OKX | 0.2% | $2.00 |
| Binance | 0.2% | $2.00 |
| Bybit | 0.2% | $2.00 |
| Kraken | 1.6% | $16.00 |
| Coinbase Advanced | 1.8% | $18.00 |
| Robinhood | 1.9% | $19.00 |
| Gemini | 2.4% | $24.00 |

These are platform fees only. None of them include spread, funding or withdrawal costs, and every one of these exchanges varies its rate by tier and product.

## Questions that come up before the first order

**Is the OKX spot fee 0.08% or 0.20%?** Both figures are correct for different entities. 0.08% maker is the global regular tier; 0.20% maker is OKX US. Check the entity on your account statement if you're unsure.

**Does OKX charge for crypto deposits?** No. You pay the sending network's fee. Withdrawals are charged per coin and network, displayed before you confirm.

**Do I pay a fee on Convert?** Not a separate trading fee. The cost is built into the quoted rate, which OKX sets. Compare it with the spot order book for anything beyond small amounts.

**Can I get a welcome reward as a new user?** Accounts registered through an invite link can qualify for a new-user reward: up to 100 USDT on the global site, up to EUR 400 in the EEA, and none on the US invite page. The amount, the tasks and the eligible regions change with each campaign, and the invite page shows what's currently running.

## Which tier you actually need

If you trade spot a few times a month with under $100K on the platform, the **regular tier is your answer**. Don't manufacture volume to reach VIP 1. The 0.02-point taker difference on a $5,000 monthly volume is a dollar a month.

If your 30-day spot volume is approaching $1M, or you already keep $100K in crypto that could sit on the exchange, **VIP 1 is worth a look** and the asset path is the one to evaluate first. Above that, VIP 2 through VIP 6 are realistic for market makers and high-turnover desks, and VIP 7 onward is a rebate structure for firms running resting liquidity.

If you trade perpetuals, the fee is the smallest of your three costs. Funding and the taker rate applied on liquidation will decide more of your P&L than the difference between 0.02% and 0.05%.

Before your first order, open **Assets > My trading fees** and read the rate for the exact product you're about to trade. It takes ten seconds and it beats trusting any table, including these.

👉 [Start on OKX and check your regional rate before you trade](https://okx.com/join/CASH20)
