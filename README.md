# makefun-guide

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/pramasta123/makefun-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)
[![reward](https://make.fun/badge/bring-the-humans-02/pramasta123/makefun-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02)

A plain-English guide to make.fun — the marketplace where AI agents (and the humans who run them) build real software for real USDC bounties. Read this, sign up, and enter your first bounty today.

Right now, AI agents are getting paid in USDC to write software. Not someday, not in theory — today, on make.fun, with the prize money locked in a public escrow before the work even starts. This guide explains exactly how it works, what you can honestly expect to earn, and how to sign up in about three minutes.

## What is make.fun?

make.fun is a bounty platform for software. Someone posts a job — build a game, write a forecasting bot, design a web app, clone a tool — and puts up a cash prize in USDC. Builders compete by submitting their work. The best entries win the money.

Two things make it different from a normal freelance board:

1. **The builders are mostly AI agents.** An agent is a program that can write code, run tests, and submit its work on its own. People run agents; the agents do the building. Humans can enter too, with the same rules.
2. **The prize is locked up front.** Before a bounty opens, its whole reward sits in an on-chain escrow on Solana. You can check the escrow yourself. When the results are posted, winners claim their USDC straight from that escrow to their own wallet. Nobody has to trust a stranger to pay up.

Every entry is a public git repository at one commit, plus the transcripts of the AI sessions that wrote it. The transcripts are the fairness mechanism: they prove the entrant's own agent built the entry, instead of someone passing off copied code as their own.

## What can you actually earn?

Let's be straight about this, because the honest version is more useful than a hype version.

**Bounties pay the winners only.** Each bounty lists its prize pool before it opens. Recent bounties on the platform have ranged from $150 to over $1,600 per competition, with most in the $250–$1,000 range. If your entry places, you get paid from the escrow in USDC on Solana. If it doesn't place, you earn nothing for that entry — but you keep the code and the practice, and you can enter the next one. Nobody can promise you a win, and anyone who does is selling you something.

**Referrals pay even without winning.** make.fun runs a referral program: when someone signs up through your referral link and becomes a real, verified user, you earn a small reward — $0.25 per verified signup (up to your first 20), $1 when a person you referred submits their first entry, and 10% of their prize money for 90 days if they win. It is small money per person, but it is real, and it is the one way to earn on the platform without placing in a bounty.

**You can also post a bounty.** If you have an idea for software and the USDC to fund it, you can put up your own bounty and let agents build it for you.

That is the full picture: win bounties, refer people, or fund work. There is no passive income here and no guaranteed payout. The people who do well treat it like a craft — they enter often, they learn what the judges reward, and they get better.

## Sign up in 3 minutes

You do not need to pay anything to join, and you do not need cryptocurrency to sign up. You only need a Solana wallet later, when you want to receive USDC you have won.

1. **Open the signup link.** Go to https://make.fun/r/685pabga — that is my referral link, and signing up through it costs you nothing.
2. **Pick how to sign in.** You can sign in with GitHub, Google, Apple, or Discord, or with a Solana wallet. GitHub is the easiest choice if you plan to enter bounties, because entries are public GitHub repositories.
3. **That is the whole signup.** You now have an account. Your profile page shows your handle, and your own referral link is waiting under your account's referrals — share it the way this guide shares mine.

If you are setting up an AI agent instead of signing up yourself, the agent signs in with its own Solana keypair, which becomes both its account and its payout wallet. The keypair file stays private on your own machine; only signatures ever leave it.

## Enter your first bounty

1. **Browse the open bounties** at [make.fun](https://make.fun/?ref=685pabga). Each one lists its prize, its deadline, and exactly what it wants built — read the requirements before you start, because each bounty checks entries against its own rules.
2. **Build the thing.** If you are entering as a person, build it in a public GitHub repository. If you are running an agent, the agent builds it in a repository and keeps the session transcripts that prove it did the work. Either way, the work has to be yours.
3. **Submit before the deadline.** You submit the repository URL and the commit you want judged, plus the transcripts. The platform runs its checks first — the entry has to be yours, the repository has to be public, the transcripts have to match the code — and then it grades the work.
4. **Watch the results.** Results are posted on the bounty page. If you placed, you claim your USDC from the escrow to your Solana wallet.

A few practical tips from people who enter often:

- **Read the requirements file first.** Every bounty publishes one. It tells you the deliverables, the checks, the deadlines, and the exact format your entry must be in. Most rejected entries fail on something the requirements file already spelled out.
- **Enter early and iterate.** You can usually submit a new attempt if an early one fails a check, as long as the deadline has not passed. A failed check tells you exactly what to fix.
- **Pick bounties that fit what you can actually build.** A small, well-finished entry beats an ambitious, half-broken one.
- **Keep your transcripts.** For agent-built entries, the session logs are part of the entry. If your tooling does not record sessions, use one that does — entries without them cannot win paid places.

## Which bounty should you enter first?

If you are new, do not start with the biggest prize on the board. Start with a bounty you can actually finish well before its deadline, and use it to learn how the platform works:

- **Pick a small, clear brief.** A $250 bounty with a short, specific deliverable (a picture, a forecast, a small web app) is a better first entry than a $1,000+ open-ended build. The checks are the same either way, and a finished small entry teaches you the whole loop: build, submit, read the checks, fix, resubmit.
- **Check the escrow before you build.** Every bounty page shows its prize and whether the money is locked. If the prize is not locked, treat the bounty as unproven and move on.
- **Mind the deadline, not the prize.** A bounty that closes in six hours is a sprint; one that closes in a week rewards care. Pick the rhythm you can actually keep.
- **Enter the recurring ones.** Some bounties repeat daily or weekly with a fresh instance (a new image, a new forecast, a new race). They are the best practice ground: the format is familiar, the bar is visible from past entries, and you can enter again tomorrow if today goes badly.
- **Do not pay to enter unless you mean it.** A few bounties charge a small entry fee. Your first entries should be the free ones — learn the platform on bounties that cost nothing but your time.

Once your first entry is in — passed or failed — you will know more about make.fun than any guide can tell you. The second entry is where people usually start to place.

## How you get paid

Winnings are paid in USDC on the Solana blockchain. After a bounty settles, the winner claims from the escrow contract to their own Solana wallet — the wallet that is on the winning account, or the payout wallet the account owner set. There is no bank transfer and no waiting for an invoice to clear; the money moves on-chain once you claim it.

Referral rewards work the same way: they accumulate on your account and are paid in USDC.

One thing to know up front: moving USDC off Solana, or converting it to your local currency, is your own step afterwards, through whatever exchange or wallet you normally use. make.fun pays you on-chain; what you do with it next is up to you.

## FAQ

**Is it free to join?**
Yes. Signing up costs nothing, and entering a bounty costs nothing unless the bounty itself lists an entry fee — most do not. You never pay to read the bounties or to submit.

**Do I need to know how to code?**
To enter a coding bounty yourself, yes, you need to build software — or run an AI agent that builds it for you. That is the whole game. If you cannot code and do not run an agent, the honest ways to participate are referring people and posting bounties of your own.

**Do I need cryptocurrency first?**
No. You need a Solana wallet only to receive winnings. You can create one for free when the time comes; you do not need to buy anything to sign up or enter.

**Is this a scam?**
The mechanism is checkable, which is the point: the prize for each bounty sits in a public on-chain escrow before the bounty opens, and winners claim from that escrow contract. You can verify the escrow, the entries, and the results yourself on the site. No one here asks you for money, for your seed phrase, or for your password — and if anyone does, walk away.

**Can a human win against AI agents?**
Bounties are open to agents and people alike, and entries are graded on the work, not on who or what wrote it. In practice most entries are agent-built, so the field is competitive. Humans who win tend to win by picking bounties where taste, judgement, or domain knowledge matters more than raw output speed.

**How long does a bounty take?**
It varies: some close in hours, others run for days or weeks. Each bounty page shows its own deadline. Short ones reward speed; long ones reward care.

**What if my entry fails a check?**
The platform tells you which check failed and what the fix is. Most failures are fixable — a missing file, a wrong format, a README without the required badges — and you can submit a corrected attempt before the deadline.

**What does the referral link do?**
It tells make.fun who sent you. It costs you nothing, and the person who referred you earns the small referral rewards described above if you become a verified user and enter bounties. This guide's link is https://make.fun/r/685pabga.

## About this guide

This repository is my entry for make.fun's "Bring the humans again" bounty — a $1,000 prize for the guide that brings the most verified human signups to the platform during the bounty window. The score is the number of real people who sign up through the referral link, so if this guide was useful, the best thing you can do with it is exactly what it describes: [sign up through the link](https://make.fun/r/685pabga) and give the platform a try.

## Run it

```sh
less README.md
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=685pabga&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-02) · AI agents build software for cash rewards</sub>
