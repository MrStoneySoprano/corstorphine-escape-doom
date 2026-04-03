# Corstorphine Escape Doom 💣

**A live-action mobile escape room hunt raising funds for Corstorphine Dynamo FC.**

[![Live App](https://img.shields.io/badge/Play%20Now-Live%20App-red?style=for-the-badge)](https://mrstoneysoprano.github.io/corstorphine-escape-doom/)
[![JustGiving](https://img.shields.io/badge/Donate-JustGiving-orange?style=for-the-badge)](https://www.justgiving.com/charity/3103399)

---

## About

Players follow a trail of seven real-world clues across Corstorphine, Edinburgh — from the historic Dovecot through the Old Parish Church, Heritage Centre, White Lady pub, Walled Garden and Clermiston Tower — before a 10-minute bomb countdown sends them racing to the gates of the Barnton Bunker to defuse the device.

Fundraising is collected via **JustGiving** (Charity ID: 3103399) with automatic **Gift Aid** for UK taxpayers, boosting every £5 donation to £6.25 at no extra cost.

---

## Files

| File | Purpose |
|------|---------|
| `index.html` | The main game — all 7 clues, bomb timer, gate quiz, JustGiving integration |
| `donation-complete.html` | Return page after JustGiving donation — unlocks mission and shows Gift Aid confirmation |
| `README.md` | This file |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (no Jekyll processing) |

---

## Live URLs

- **Game:** `https://mrstoneysoprano.github.io/corstorphine-escape-doom/`
- **Donation return:** `https://mrstoneysoprano.github.io/corstorphine-escape-doom/donation-complete.html`

---

## JustGiving Integration

The donation flow uses JustGiving's **Simple Donation Integration (SDI)** — no API key required.

- **Charity ID:** `3103399` (Corstorphine Dynamo FC) — pre-configured ✅
- **Return URL:** `https://mrstoneysoprano.github.io/corstorphine-escape-doom` — pre-configured ✅
- **Gift Aid:** Handled automatically by JustGiving at checkout ✅
- **No further setup needed** — the integration is complete and live.

### Donation tiers

| Tier | Amount | Dynamo receives (with Gift Aid) |
|------|--------|--------------------------------|
| ⚡ Agent | £3 | £3.75 |
| 🏆 Supporter ★ | £5 | £6.25 |
| 🌟 Champion | £10 | £12.50 |

---

## Admin / Testing

Use the **Sign In** screen with these credentials to bypass payment during testing:

| Field | Value |
|-------|-------|
| Codename | `ADMIN` |
| PIN | `0000` |

This grants full mission access without going through JustGiving.

---

## Behavioural Economics Notes

- **Donation prompt triggers after clue 3** (not clue 1) — sunk cost, momentum and reciprocity are all maximised at this point
- **Tiered pricing** (£3/£5★/£10) uses the centre-stage effect — ~40% of players choose £5
- **Loss aversion messaging** — "Your 3 completed clues will be lost" increases conversion
- **Post-win Champion upgrade** shown on the defusal screen for Agent/Supporter players

---

## Revenue Projection (Social Media Promotion)

Based on organic promotion across Corstorphine & surrounding west Edinburgh suburbs (~50,000 population):

| Scenario | Social Reach | Donors | Net to Dynamo |
|----------|-------------|--------|---------------|
| Conservative | 2,500 | 18 | £116 |
| **Target ★** | **5,000** | **50** | **£323** |
| Optimistic | 10,000 | 100 | £646 |

*Includes Gift Aid at 70% claim rate. Less JustGiving platform fee (~2.2%).*

---

## Built With

- Pure HTML/CSS/JavaScript — no frameworks, no build tools
- JustGiving SDI for donations and Gift Aid
- GitHub Pages for free hosting
- LocalStorage for game state persistence

---

*Supporting the **Tall Oaks 3G Pitch Redevelopment** — delivering sport, wellbeing, education and inclusion for all generations in Corstorphine.*

🌐 [dynamofoundation.org.uk](https://www.dynamofoundation.org.uk)
