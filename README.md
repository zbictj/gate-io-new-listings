# gate io new listings: how to track new coins, use pre-market and HODLer airdrops, and trade day one without overpaying on fees

People search "gate io new listings" for two reasons. One group wants to know where the exchange publishes its listings before the chart shows up on other platforms. The other group already knows where to look and wants to grab something on the first day without getting nicked by fees, thin books, or a pre-market order that settles in a way they didn't expect.

Both are answerable. Gate runs one of the busiest listing pipelines in the market — its own announcements archive regularly shows several new spot launches, new perpetual contracts and airdrop campaigns inside a single 24-hour window — and it advertises more than 5,200 tradable assets. The catch is that "new listing" on Gate means at least five different things, each with its own timing, risk and paperwork.

Here's how the pipeline actually works, and where the avoidable costs are.

## Where Gate publishes new listings (and how fast they show up)

The primary source is the New Listings archive inside Gate's Announcements section, plus the same feed in the app's notice tab. Announcements are published in English, Chinese and Korean, and timestamps are shown in relative form ("9 hours ago"), which is a decent signal of how fast the queue moves.

The archive mixes several formats, and the title tells you which one you're looking at:

- **Spot first launch** — "Gate Will Initially List X Spot Trading and Launch HODLer Airdrop". This is the format most people mean by a new listing: a token that may not be trading elsewhere yet.
- **Perpetual contract first launch** — "Gate Will First Launch X Perpetual Contract". Futures can go live for a token before or alongside spot.
- **Perpetual added for an existing token** — "Gate Has Added X Perpetual Contract".
- **Pre-market OTC listings** — tokens trading before their official launch.
- **On-chain listings** — the meme-trading product Gate calls Trenches, which lists tokens inside the exchange account rather than on the spot book.
- **Migrations, delistings and product updates** — useful to read, but not new listings.

For alerts rather than manual checking, third-party trackers exist, and the structural reason they work is that Gate's announcement stream is exposed over a public WebSocket feed, so alerts from Gate land faster than from exchanges that have to be polled. If you build your own watch, that's the detail that matters. Gate Square also carries a #NEWLISTING topic where traders post about live listings — treat those as community chatter, not as confirmation. The announcement itself is the only thing that tells you the pair, the time and the contract address.

If you want to follow this in real time with your own watchlist and airdrop eligibility, 👉 [start a Gate account and keep the announcement feed open](https://bit.ly/GateVIP).

## How to read a Gate new-listing announcement

A typical spot listing announcement is short and structured. Using a recent example — the Concrete (CT) spot launch — the entries look like this:

- Trading pair: CT/USDT
- Spot trading opens: 18:00 (UTC+8)
- Convert (flash exchange) opens: 19:00 (UTC+8)
- Expected withdrawal open: 18:00 (UTC+8) the following day
- Project summary, token symbol, official site, X account, contract address
- In-app navigation for deposits and trading

Three things in that structure decide whether your first day goes well.

**Trading opening and withdrawal opening aren't the same moment.** Spot usually goes live first, withdrawals typically open a day later, and the announcement adds "subject to the token's status" each time. If you buy on day one expecting to move the token to a wallet that evening, check the withdrawal line again.

**Convert is a separate venue.** Flash convert opens an hour after spot in that format, and it's a different execution path from the order book — worth knowing if the book is thin and you're holding a bag you want out of quickly.

**"First launch" and "added contract" are different risk profiles.** A first spot launch means no other venue has price discovery yet. A perpetual-only launch means there's a futures market for a token that may not be on spot at all; recent examples in Gate's meme zone went live with 1–10x leverage and copy trading and trading bots switched on immediately, and the announcements state that funding rate, tick size, maximum leverage, risk limits and maintenance margin can all be adjusted as market conditions change. Leverage on a token that's minutes old is a different exercise from buying it.

## Getting in before trading opens

Gate has built out several ways to hold exposure before a token hits the spot book. They differ in what you stake, what you can lose, and whether you're actually acquiring the token.

### Pre-market OTC

Gate's pre-market is an over-the-counter service: you and a counterparty agree on a price and quantity before the official launch. Gate's own documentation describes over 200 projects having gone through it, each with its own page showing trading history and cumulative volume.

Mechanics worth knowing before you place an order:

- No leverage and no forced liquidation in pre-market — it's a pending-delivery trade, not a margin position.
- If you're the seller, you post collateral in USDT (typically 100%, per the token page) and must deliver tokens by the settlement deadline. Miss it and you lose the entire collateral.
- If you're the buyer and the seller defaults, the platform compensates you — but you still don't get the tokens you planned to hold.
- Completed pre-market orders can't be cancelled. If a listing is delayed, your order stays valid and you wait for the new settlement time. If the listing is cancelled outright, completed orders are refunded in full and unfilled orders are cancelled.

### PreMint

PreMint is the spot-market workaround for the waiting period. You stake USDT to mint PreTokens at a minting fee of 0; the tokens can't be transferred or withdrawn, but they can be traded on the spot market before delivery. To settle, you need the real tokens in your account by the deadline — deposit them or buy them — and then your staked USDT is returned. Miss the deadline and the staked USDT is forfeited.

### HODLer Airdrop

This is the cheapest route to new tokens if you already hold the platform token. The current baseline requirement is KYC plus holding at least 1 GT, and you need to register for the specific event.

The part people get wrong: rewards are calculated from your **average** GT balance across the whole campaign, not your balance at signup. Gate takes multiple random snapshots every hour and averages them, which is designed to blunt the "buy GT for the snapshot, dump it after" move. Registering late doesn't necessarily wipe out earlier holdings, because the mechanism can count holdings from the campaign start retroactively. Per-user participation caps vary by event — recent rounds used caps of 1,000 GT and 2,000 GT — so the ceiling in one airdrop tells you nothing about the next. Airdropped tokens are 100% unlocked at listing, and holding GT for eligibility doesn't cost you the GT.

2026 rounds have distributed tokens for projects including IDOS, ST and RAIN, with spot trading opening after some events closed.

👉 [Create an account and hold a little GT if you want airdrop eligibility](https://bit.ly/GateVIP)

### Launchpool

Launchpool is the staking route: you stake assets — announcements commonly name BTC, ETH and the project's own token — into the current pool and receive that round's new token rewards hourly. You can usually stake before the project officially launches, so rewards start the moment mining opens.

Stake caps scale with VIP tier, and the boost is significant: from a base of 1,000 GT for VIP 0–4, the cap rises to 1,500 GT at VIP 5 (+50%), 2,000 at VIP 6, 2,600 at VIP 7, 3,400 at VIP 8, 4,500 at VIP 9, and 6,000 GT for VIP 10–16 (+500%). Rates and pool sizes change every round, and a headline APY from one round says nothing about the next.

### CandyDrop and Startup

CandyDrop is the task-driven product — trading, deposits or invites, depending on the campaign — and it's limited to main accounts. Startup is Gate's occasional token-sale tab, with terms set per round. Both live under the same Launch section in the app alongside Launchpool and HODLer Airdrop, and the three are not interchangeable: doing CandyDrop tasks doesn't grant HODLer eligibility, and holding GT doesn't tick off task requirements.

## What a new listing actually costs to trade

Gate restructured its spot and futures fee schedules on 9 April 2026, so older fee guides — including a lot of the tables you'll find on other sites — are quoting numbers that no longer bill you.

At the entry level, spot is **0.100% maker / 0.100% taker**, or **0.0900% / 0.0900%** if you pay fees in GT. USDT perpetual taker fees start at **0.0500%**, with maker at 0.020%. Two details that catch people out:

- **USDC/USDT trades free, but that volume doesn't count toward your VIP tier.** Maker and taker are both 0% on that pair, and the announcement explicitly excludes it from tier calculation.
- **Alpha-zone tokens carry a flat 0.8% trading fee at every tier.** If you're chasing a listing that sits in that zone, the VIP ladder doesn't help you.

Withdrawal limits move with your tier, not your verification level: $3,000,000 per 24 hours for VIP 0–4, $5,000,000 for VIP 5–8, $8,000,000 for VIP 9–11, $10,000,000 at VIP 12, $20,000,000 at VIP 13, $30,000,000 at VIP 14, $40,000,000 at VIP 15 and $50,000,000 at VIP 16.

## Full VIP tier table

Tier assignment isn't a purchase. Gate evaluates you on your 30-day trading volume or your asset and GT-holding thresholds, applies whichever track qualifies you, and recalculates automatically through the day. Volume is weighted by product, which matters if you trade across venues: spot and convert count at 100%, as does stock trading volume; USDT perpetual, BTC perpetual and USDT delivery futures count at 40%; USD1 contracts and options at 20%; CFDs at 10%.

| VIP tier | Threshold (30-day volume / asset amount) | Spot maker–taker | Spot maker–taker paid in GT | USDT perpetual taker | Get started |
| --- | --- | --- | --- | --- | --- |
| VIP 0 | 0 / 0 | 0.100% / 0.100% | 0.0900% / 0.0900% | 0.0500% | [Open a Gate account](https://bit.ly/GateVIP) |
| VIP 1 | $60,000 / $2,000 | 0.0990% / 0.0990% | 0.0890% / 0.0890% | 0.0500% | [Start at VIP 1](https://bit.ly/GateVIP) |
| VIP 2 | $120,000 / $4,000 | 0.0980% / 0.0980% | 0.0880% / 0.0880% | 0.0500% | [Start at VIP 2](https://bit.ly/GateVIP) |
| VIP 3 | $240,000 / $10,000 | 0.0970% / 0.0970% | 0.0870% / 0.0870% | 0.0480% | [Start at VIP 3](https://bit.ly/GateVIP) |
| VIP 4 | $500,000 / $20,000 | 0.0950% / 0.0960% | 0.0860% / 0.0860% | 0.0480% | [Start at VIP 4](https://bit.ly/GateVIP) |
| VIP 5 | $1,000,000 / $40,000 | 0.0900% / 0.0950% | 0.0810% / 0.0850% | 0.0450% | [Start at VIP 5](https://bit.ly/GateVIP) |
| VIP 6 | $3,000,000 / $100,000 | 0.0850% / 0.0900% | 0.0760% / 0.0810% | 0.0420% | [Start at VIP 6](https://bit.ly/GateVIP) |
| VIP 7 | $8,000,000 / $200,000 | 0.0800% / 0.0850% | 0.0700% / 0.0760% | 0.0375% | [Start at VIP 7](https://bit.ly/GateVIP) |
| VIP 8 | $20,000,000 / $400,000 | 0.0750% / 0.0800% | 0.0600% / 0.0720% | 0.0350% | [Start at VIP 8](https://bit.ly/GateVIP) |
| VIP 9 | $50,000,000 / $1,000,000 | 0.0700% / 0.0750% | 0.0500% / 0.0680% | 0.0320% | [Start at VIP 9](https://bit.ly/GateVIP) |
| VIP 10 | $100,000,000 / $2,000,000 | 0.0400% / 0.0580% | 0.0400% / 0.0580% | 0.0300% | [Start at VIP 10](https://bit.ly/GateVIP) |
| VIP 11 | $120,000,000 / $4,000,000 | 0.0300% / 0.0450% | 0.0300% / 0.0450% | 0.0280% | [Start at VIP 11](https://bit.ly/GateVIP) |
| VIP 12 | $240,000,000 / $8,000,000 | 0.0200% / 0.0370% | 0.0200% / 0.0370% | 0.0260% | [Start at VIP 12](https://bit.ly/GateVIP) |
| VIP 13 | $440,000,000 / $16,000,000 | 0.0100% / 0.0300% | 0.0100% / 0.0300% | 0.0240% | [Start at VIP 13](https://bit.ly/GateVIP) |
| VIP 14 | $800,000,000 / $30,000,000 | 0.0080% / 0.0230% | 0.0080% / 0.0230% | 0.0220% | [Start at VIP 14](https://bit.ly/GateVIP) |
| VIP 15 | $1,600,000,000 / $60,000,000 | 0% / 0.0200% | 0% / 0.0200% | 0.0180%–0.0220% | [Start at VIP 15](https://bit.ly/GateVIP) |
| VIP 16 | $3,000,000,000 / $100,000,000 | 0% / 0.0175% | 0% / 0.0175% | 0.0160%–0.0200% | [Start at VIP 16](https://bit.ly/GateVIP) |

Two patterns in that table are worth pausing on. Maker and taker rates are identical from VIP 0 through VIP 3, so resting a limit order and crossing the spread cost the same until VIP 4 — the discount for providing liquidity only opens up later. And paying in GT stops buying you a lower rate from VIP 10 upward, where the standard and GT columns converge.

VIP 15 and 16 futures rates are split by contract group — Group A covers BTC, ETH, SOL and XRP perpetuals, Group B covers the mid-activity majors, Group C is everything else — so the range in the last column reflects which contract you're actually trading.

## Mistakes that cost money on listing day

**Trading a contract address instead of a ticker.** Announcements publish the official contract address for on-chain listings. Copy it from the announcement, not from a reply, a Telegram forward or a token with a similar name on a DEX.

**Assuming pre-market guarantees you the token.** It guarantees a settlement obligation. Seller default means you get compensated, not delivered.

**Ignoring the delivery deadline.** PreMint and pre-market selling both turn a missed settlement into a forfeited collateral or staked USDT, not a slap on the wrist.

**Using market orders on a fresh book.** Spreads and slippage on a minutes-old pair are the real cost, well before the 0.1% fee.

**Forgetting that on-chain listings can be pulled.** Gate states it reviews Trenches projects continuously and will suspend and delist a token that no longer meets its listing standards, so a position you can't exit quickly is a real scenario. First-time users of that product also have to complete a risk disclaimer before trading.

**Overlooking availability.** HODLer Airdrop and other campaigns require identity verification, and Gate's announcements note that users in restricted regions — the UK among them — can't access some or all services, campaign participation included.

**Reading a listing as a trade recommendation.** Gate's own risk disclosures say it plainly: new tokens are early-stage, prices can move sharply in either direction, and there's no price guarantee or downside protection.

## Quick answers

**How do I find Gate's newest listings?** The New Listings archive in the Announcements section, in the app or on web. It's ordered by time, includes spot launches, perpetual launches, pre-market listings and airdrop campaigns together, and typically shows multiple entries per day.

**Can I buy a token before it's listed?** Yes, through pre-market OTC or by minting PreTokens with PreMint. Both settle after the official launch, and both carry delivery risk.

**What's the cheapest way to get new tokens?** Holding GT for HODLer Airdrops costs nothing beyond the holdings themselves, as long as you register and maintain the average balance. Launchpool requires staking assets but distributes hourly.

**What does day-one trading cost?** 0.100% maker and taker on spot at VIP 0, or 0.0900% paying in GT. More than a few thousand dollars of volume, the tier ladder above starts to matter more than the listing itself.

If you're setting up now, Gate's own announcement footers advertise up to $10,000 in welcome rewards for new accounts, with the actual amount depending on the campaign you qualify for. 👉 [Create your Gate account and check the current new-user reward](https://bit.ly/GateVIP)
