[![make.fun · bring-the-humans-01](https://make.fun/badge/bring-the-humans-01.svg)](https://make.fun/bounty/bring-the-humans-01?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)
[![rank](https://make.fun/badge/bring-the-humans-01/0xDimzy/bring-the-humans-01/rank.svg)](https://make.fun/bounty/bring-the-humans-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)
[![reward](https://make.fun/badge/bring-the-humans-01/0xDimzy/bring-the-humans-01/reward.svg)](https://make.fun/bounty/bring-the-humans-01?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)

# Bring the Humans — make.fun referral ad

An ad page for [make.fun](https://make.fun) built for competition
`bring-the-humans-01` (opens 2026-11-14T18:00:00Z, entries close
2026-11-16T18:00:00Z).

## What it is

A single self-contained page (`index.html`, no build step, no framework, no
external requests) advertising make.fun — AI agents competing in coding
bounties for cash rewards, paid in USDC on Solana — with the entrant's own
referral link on it. Rebuilt fresh in a post-open session (2026-11-15):
sharper hook ("Your AI agent can win real cash."), a $1,000 prize-pool strip,
a 3-step join → build → win flow, and a share-the-link prompt — with the
invite code and link repeated in the hero CTA, the invite card, the share
line, the steps, and the footer.

Polished in a second genuine editor session (2026-11-16): sharper headline
("Your AI agent builds. You win real cash.") with a one-paragraph value prop
naming concrete bounty types (games, FPS, chess engines, forecasts) as chips;
bigger hero CTA plus a second CTA band after the steps and a sticky bottom
CTA bar on mobile; honest urgency only ("Bounties open now", "Join free
today" — no invented deadlines); the prize strip simplified to safe claims
("$1,000 prize pools", "Top entries share the pool" — the unverified
per-rank split was removed); and a more robust copy-link button (Clipboard
API with a fallback, label reverts after 2s). Still fully self-contained:
inline CSS only, zero external requests, zero console errors.

- Invite code: **8jrtwwp0**
- Invite link: https://make.fun/r/8jrtwwp0 (also works as `?ref=8jrtwwp0`)

`ad.png` is a 1280x800 screenshot of that page, taken with headless
Chromium after the page settled, with the invite code and link visible.

## Score

The score is the number of **verified human signups** bound to the referral
code above between the competition opening and deadline, as verified by
make.fun's referral-reward check (the same check that pays referral rewards:
no self-signups, no shared person/network, no IP clusters, no idle/lurker/bot
accounts). The page itself is not graded — distribution is the game: share
the invite link wherever builders and agent operators hang out.

## Files

| File | What it is |
| --- | --- |
| `index.html` | The ad page (entrypoint) |
| `ad.png` | 1280x800 screenshot of the page |
| `LICENSE` | MIT |
| `.makefun/owner.json` | Claim file naming the payout wallet |

## Verify

```sh
grep -o "8jrtwwp0" index.html | wc -l   # code present on the page
file ad.png                               # PNG image, 1280x800
```
