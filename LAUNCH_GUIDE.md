# SaloneServe — MVP Launch Guide (Freetown Super App)

## What you have now
A working installable app prototype (PWA) with 4 services:
1. Okada ride booking (fare estimate + rider matching)
2. EDSA light tokens + airtime
3. Market delivery
4. Pharmacy delivery
5. Rental & property listings (with broker subscriptions)
6. SME bookkeeping + invoicing
7. Diaspora remittance vouchers (2.5% fee)
Wallet, order history, and mobile-money-style checkout are all functional in demo mode (data saved on the phone).

## Install on an Android phone (testing today)
1. Host the folder on any HTTPS host (Netlify / Vercel / GitHub Pages — free),
   or for local testing run:  python3 -m http.server 8080
2. Open the URL in Chrome on the phone
3. Menu (⋮) → "Add to Home screen" / "Install app"
4. It launches fullscreen like a native app, and works offline.

## To launch for real customers
| Step | What | Est. cost (USD) |
|---|---|---|
| 1 | Convert PWA → Play Store app (bubblewrap/TWA) + $25 dev account | 25 + 1 wk |
| 2 | Backend (orders, users, riders, dispatch) — Firebase or a developer on contract | 1,500–4,000 |
| 3 | Orange Money / Africell Money API integration (via aggregators like Lean or direct bank/API partner) | 500–1,500 |
| 4 | Onboard 10–20 okada riders in ONE zone (e.g., Lumley–Aberdeen), print their rider IDs, run 2-week pilot | 200–400 |
| 5 | Sim registration compliance + terms/privacy pages (NatCA rules) | 100–300 |

## Why one super app, not ten apps
Your okada, market-trader, and pharmacy networks all feed one dispatch system, one wallet, one user base. Ten apps = ten marketing budgets. One app = one habit.

## Revenue model in this prototype
- Okada: ~15% commission per fare
- Bills: SLE 2 fee per transaction (high volume, daily use)
- Rentals: SLE 50/mo broker subscription per listing
- Remittance: 2.5% per transfer (paid by sender)
- SME Books: free to grow trust → future credit-scoring partnerships
- Market/pharmacy: delivery fee + 5–10% merchant margin
