---
title: "{{Paying in Batumi: A Traveller's Guide to Georgian Lari (and the Ghost Currencies on Your Statement)}}"
date: {{2026-09-29}}
author: "{{Dawid Lisowski}}"
location: "{{Batumi, Georgia}}"
lang: "{{en}}"                      # swap to "pl" for a Polish edition
tags: [georgia, batumi, currency, gel, travel-money, dcc, payments, iso-4217]
description: "{{How money actually works in Batumi — cash vs card, the three traps that cost you lari, and why a '1,00 TWN' line on my bank app was a firmware bug, not fraud.}}"
image: "{{/assets/img/batumi-frontier.jpg}}"
canonical: "{{https://github.com/dawidmillenium-design/Newtaiwandollargeorgia}}"
---

<!-- ============================================================
     TEMPLATE USAGE
     • Replace every {{token}} with your own values.
     • The "WORKED EXAMPLE" callout is pre-filled with the real
       Batumi/TWN incident — delete it or keep it as the anchor post.
     • Section order is the recommended narrative arc:
       HOOK → GROUND TRUTH → CURRENCY 101 → THE 3 TRAPS →
       WORKED EXAMPLE → CHECKLIST → BATUMI-SPECIFIC TIPS → CLOSE.
     ============================================================ -->

## The hook {{one vivid sentence — e.g. "I bought a coffee for one lari and came home to a bank line in a currency that does not exist."}}

{{2–3 sentences. Open with the sensory detail of the place (humid Black Sea air, the colonnaded boulevard, the smell of khachapuri from a bakery on the old town side), then drop the money problem. Make the reader feel the confusion before you explain it.}}

---

## 1. Ground truth: where you (and your card) actually are

Before you trust a statement line, trust your **body** and your **passport**. Money bugs feel like fraud; geography feels like boring paperwork — but geography is the lie detector.

> **Diagnostic rule #1:** a charge is suspicious only if the *merchant descriptor* and your *physical location* disagree. When they agree, you have a metadata bug, not a thief.

In my case the paper trail was unambiguous:

| Evidence | Says |
|---|---|
| 🇹 Suvarnabhumi stamp — `DEPARTED 14 SEP 2026` | I left Thailand by air |
| 🇬 Batumi stamp — `GE ✈ ENTRY 15 09 2026 · 0387` | I landed in Georgia the next day |
| Incident date `29 SEP 2026` | 14 days already inside Georgia |
| App greeting `"Hello, Dawid!"` + card `*2673` | My own logged‑in account, my own activated card |
| Merchant `georgian vending group` | A Georgian acquirer, not a Taiwanese one |

A cloned card fed through a terminal in Taipei would carry a **TW** merchant and a **TWD** amount unrelated to my latte. It would not greet me by name on my own app. The stamps, the descriptor, and the greeting all point the same direction: *I was in Batumi, paying with my own card, locally.*

{{Replace the table with your own stamps / boarding passes / geolocation. The point of this section is to teach the reader to *collect* this evidence *before* panicking.}}

---

## 2. Currency 101 — what you're actually holding in Batumi

Georgia's money is the **lari**, code **GEL**, divided into **100 tetri** (coins come in 1, 2, 5 lari and 1, 2, 5, 10, 20, 50 tetri; notes 1, 2, 5, 10, 20, 50, 100, 200). Tetri sound tiny but they are not optional — markets, marshrutkas (shared taxis), tips and small cafés will expect exact-ish change, and a wallet full of un‑spent tetri is the universal souvenir of a Georgia trip.

**Cash vs card, the honest split:**

- **Card (Visa/Mastercard) is everywhere tourists go** — hotels, proper restaurants, supermarkets (the big local chains), pharmacies, ride‑apps, parking machines, and the new wave of **self‑service vending** (coffee/food kiosks) that dotted Batumi's boulevard. Contactless works almost without fail.
- **Cash still wins** at the beach‑side stalls, the old‑town bakeries that won't open a terminal for 3 lari, marshrutka drivers, market vendors, and tips. Carry small lari + a pouch of tetri.
- **ATMs** are plentiful and usually fine; prefer a bank‑owned ATM over a random standalone box, and *always* decline the on‑screen "charge me in your home currency" offer (see Trap #1).

**Indicative exchange sense** (rates move daily — *verify live before you rely on these*):

| From → To | Rough feel |
|---|---|
| 1 GEL → PLN | ≈ 1.4–1.5 zł |
| 1 GEL → EUR | ≈ 0.35–0.40 € |
| 1 GEL → USD | ≈ 0.35–0.40 $ |
| 1 GEL → tetri | exactly 100 |

> ⚠️ These are *ballpark* figures for orientation only. Lari, złoty, euro and dollar all float. Check a live rate (your bank's app, a central‑bank page, or a reputable converter) the day you exchange — never quote a stale number as fact in a money post. {{update the table or replace with a "live rate widget" shortcode if your SSG supports one}}

Where to exchange cash in Batumi: dedicated **exchange bureaus** and **banks** post visible buy/sell boards; compare two or three on the main avenue before committing, and avoid the "no commission" street offers that hide the margin in the rate. Receipts matter — keep them if you might re‑convert leftover lari at the airport.

---

## 3. The three traps that quietly eat your lari

### Trap #1 — Dynamic Currency Conversion (DCC)
A terminal asks: *"Charge you 1.45 zł instead of 1.00 GEL?"* That looks helpful and is almost always a worse rate plus a markup. **The rule: always pay in the local currency (GEL).** Let your *own* bank do the conversion at its (usually better) wholesale‑plus‑small‑fee rate. Declining DCC is the single highest‑ROI habit a traveller can build.

### Trap #2 — Informal USD/EUR pricing
Near the beach, in real‑estate viewings, on some tours and boat hires, you'll hear prices quoted in **dollars or euros** even though you're in Georgia. That's a legacy habit, not the law of the land. Before you tap, ask explicitly: *"GEL or dollars?"* A "50 dollar" tour paid by card in GEL at the terminal's chosen rate can silently cost you more than paying cash in the currency they named.

### Trap #3 — The ghost code on your statement
Sometimes neither the merchant nor your bank is lying, and the line is *still* nonsense — because the **currency field got corrupted** somewhere in the chain *terminal → acquirer → network → issuer → app*. The amount is right; the three‑letter tag next to it is a hallucination. This is exactly what happened to me, and it's the reason this whole post exists.

---

## 4. WORKED EXAMPLE — the "New Taiwan Dollar" that never was 🇬☕

> *Keep this block as the anchor story, or swap it for your own incident. It demonstrates Trap #3 end‑to‑end.*

I tapped for a coffee at **ALLIANCE PALACA** in Batumi. **1 GEL.** The terminal beeped, I walked out thinking about the sea. Later, the Erste app showed:
