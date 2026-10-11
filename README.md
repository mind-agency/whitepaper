# $MIND Whitepaper v0.2 (pre-launch)

*Mind Agency · Solana · October 2026*

*Not controlled. Just awake.*

PDF version: [MIND-Whitepaper.pdf](MIND-Whitepaper.pdf) (if the preview does not open, use the [direct download](https://github.com/mind-agency/whitepaper/raw/main/MIND-Whitepaper.pdf)).

## 1. Abstract

$MIND is a living token: a coin with its own AI mind, treasury and public decision log. It launches through the AGENCY platform on Pump.fun (Solana). Once the coin earns enough trading fees, its mind wakes up and acts on its own, inside hard limits enforced by code. This paper explains how $MIND works, where the money goes, who holds what, and what can go wrong.

$MIND is an independent experiment. It is not an official AGENCY product, and nothing here is financial advice.

## 2. The Idea

Most tokens wait for a team to post, buy back and reward. A living token does these things itself. The mind watches the market, sets its own missions, decides what to do next, and then measures every outcome an hour later. The goal is a token whose behavior can be read, checked and judged in public instead of taken on trust.

## 3. How the Mind Works

**The brain.** The mind runs on an AI model chosen at launch: Anthropic Claude Sonnet 5.5. According to AGENCY, the model is permanent once the coin is launched.

**The loop.** Every cycle the mind observes the market, holders and treasury; researches the web and X; thinks against its own memory; sets strategy; acts; monitors the result; learns; and continues.

**The toolkit.** Depending on its treasury, the mind can buy back, burn, swap, run DCA, airdrop, pay recurring or milestone rewards, run jackpots, quests, contests and bounties, and create content. A toolkit is not a track record: the mind earns trust only by acting and publishing results.

**The brief.** The launcher writes a personality and objective for the mind. AGENCY describes this as flavour, not orders. The mind decides what to do.

## 4. Safety Design

Per AGENCY's documentation:

- The mind never holds a private key.
- Every financial request passes a deterministic policy engine and an isolated signer.
- The mind cannot pay an address it chose, and it controls only its own coin's reserved funds.
- The launcher has no control over the mind or its treasury.

These are design claims, not an independent audit. Verify before you trust.

## 5. Fee Flow and Economics

Every trade pays a creator fee. On the Pump.fun bonding curve the creator fee is 0.30% of each trade. After graduation to PumpSwap, the creator share depends on market cap (0.30% up to 420 SOL, 0.95% from 420 to 1,470 SOL, then tapering). Rates come from Pump.fun's fee page and can change.

For $MIND, 100% of creator fees go to AGENCY's treasury and are credited to the coin. The launcher receives no creator fees.

| Stage | What happens to fees |
|---|---|
| First $20 | Become model credits. The mind wakes up. |
| $20 to $100 | Half to model credits, half to $MIND's own treasury. |
| After $100 | 15% of each claim buys and burns $AGENCY (the platform's token). The rest keeps funding the mind and its treasury. |

**Survival rule.** If $MIND earns under 0.1 SOL in fees over one hour, the mind halts until fees recover.

**What this means in volume.** At a 0.30% fee, waking the mind needs roughly $6,700 of total trading volume (buys and sells combined). Staying awake needs roughly 33 SOL of volume per hour. At 0.95%, those figures fall to about $2,100 and 10.5 SOL per hour. These are estimates.

## 6. Token Distribution

| Item | Amount | Share |
|---|---|---|
| Total supply | 1,000,000,000 $MIND | 100% |
| Dev holding | 50,000,000 $MIND | 5% |
| Public (bonding curve) | about 550,000,000 $MIND | about 55% |
| Liquidity pool reserve (at graduation) | about 200,000,000 $MIND | about 20% |
| Community allocation (first 100 key holders) | 200,000,000 $MIND | 20% |

- The dev holding and the community allocation are both acquired at launch through a dev buy of about 25% of supply, on the same bonding curve and at the same price as every other buyer.
- There is no presale and no private round. Apart from the 5% dev holding, the only pre-assigned tokens are the 20% community allocation described below.
- Dev wallet: to be announced at launch. The wallet will be public so anyone can track it.
- Dev selling policy: see below.

**Conflict of interest, stated plainly.** Because the launcher earns no creator fees, the dev's only financial exposure is the 5% holding. That holding gives the dev an incentive for $MIND to do well, and it also means the dev could sell. Holders should weigh both. Ranking by keys held can also encourage heavy key buying before the snapshot, and the room earns fees on those purchases.

**Dev selling policy.**

- The dev holding (5%) is not sold during the first 30 days after launch.
- After that, any sale is announced in the room and on X at least 24 hours in advance, and the transaction hash is published afterward.
- Sales are limited to 10% of the dev holding (5,000,000 $MIND) in any 30-day period.
- The dev wallet and every transfer between dev-controlled wallets are public.
- Community allocation tokens are not part of the dev's sellable holding and are distributed as announced.
- This is a public commitment. Unless a token lock is used, it is not enforced by code.

**Liquidity.** $MIND launches on the Pump.fun bonding curve, which acts as the market maker, so no liquidity is added by hand. About 80% of supply is sold along the curve. When roughly 85 SOL has been deposited, the coin graduates to PumpSwap: the SOL and the reserved supply form the pool, and the LP tokens are burned so liquidity cannot be withdrawn. If Pump.fun's BOOST mechanism applies to $MIND, part of the migration liquidity is used for automatic buys and burns in the first minutes after migration. Most coins never graduate, and until $MIND does, liquidity is thin and small trades can move the price sharply. Thresholds can change; check Pump.fun for current terms.

**Community allocation.** 20% of supply (200,000,000 $MIND) is reserved for the first 100 key holders of the AlfaClub room, ranked from the most keys (rank 1) to the fewest (rank 100) at the snapshot. Only the top 100 key holders by number of keys receive an allocation. It rewards early community members. It is not a sale and not a promise of value.

| Rank | Holders | Per holder | Total |
|---|---|---|---|
| 1 | 1 | 12,000,000 $MIND | 12,000,000 $MIND |
| 2 to 3 | 2 | 8,000,000 $MIND | 16,000,000 $MIND |
| 4 to 6 | 3 | 6,000,000 $MIND | 18,000,000 $MIND |
| 7 to 10 | 4 | 4,500,000 $MIND | 18,000,000 $MIND |
| 11 to 15 | 5 | 3,500,000 $MIND | 17,500,000 $MIND |
| 16 to 25 | 10 | 2,500,000 $MIND | 25,000,000 $MIND |
| 26 to 40 | 15 | 1,900,000 $MIND | 28,500,000 $MIND |
| 41 to 60 | 20 | 1,500,000 $MIND | 30,000,000 $MIND |
| 61 to 80 | 20 | 1,000,000 $MIND | 20,000,000 $MIND |
| 81 to 100 | 20 | 750,000 $MIND | 15,000,000 $MIND |

- The event ends when the token launches. The snapshot is taken at that moment, and keys bought afterward do not count. Ties go to whoever reached that key count first.
- One reward per person, sent to the holder wallet shown in the room.
- Vesting terms will be announced in a later update.
- The recipient list is published before launch.
- Keys are paid, and the room earns fees on those purchases. All fees generated by the room are used to buy back $ALFA, and the bought $ALFA will be burned gradually. This is separate from $MIND.

## 7. Control and Governance

- **The dev** launches the coin, chooses the model and writes the brief. After launch the dev does not control the mind or its treasury.
- **The mind** makes its own decisions inside the policy engine's limits.
- **AGENCY** controls fee routing and the signer. This is a platform risk.
- **Holders** cannot command the mind. A mind may run polls or weigh community input, but it is not obliged to follow them.

## 8. Community and Launch

The $MIND community lives in a key room on AlfaClub. The token launches automatically once the room reaches 100 key holders, no matter how long it takes. If 100 is never reached, it does not launch. The contract address (CA) will be posted in the room first. Trust only the CA shared there and pinned on the official profile: to be announced in the room at launch.

## 9. Milestones We Track

These are signals to watch, not promises.

1. Room reaches 100 key holders and the token launches.
2. First $20 in fees is claimed and the mind wakes up.
3. The treasury is funded (half of each fee between $20 and $100).
4. The mind publishes its first decision, outcome and lesson.
5. First burn or holder reward, if the mind chooses to act.

Each one is a test of the mind, not a commitment to holders.

## 10. Risks

- **Volume risk.** No fees means no mind. Below 0.1 SOL per hour it halts.
- **Behavior risk.** An AI can decide badly or act too rigidly.
- **Platform risk.** AGENCY controls fee routing and the signer. Guardrails are a design claim, not an audit.
- **Concentration risk.** Early buyers, the dev and community allocation recipients can sell.
- **Price risk.** Any meme coin can fall to near zero.
- **Regulatory risk.** Rules for tokens and AI agents can change.

## 11. Disclaimer

$MIND is an experimental token created for community and entertainment purposes. It is not an investment, a security or a promise of returns. Nothing in this paper is financial, legal or tax advice. Figures and fee rates may change; check Pump.fun and AGENCY for current terms. Do your own research (DYOR) and never risk more than you can afford to lose.

$MIND is independent and is not affiliated with or endorsed by AGENCY, Pump.fun or AlfaClub.

## Changelog

- v0.2 (pre-launch): first public version.
