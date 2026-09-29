
**`TWN` is not a currency.** It is not in ISO 4217. Taiwan's real code is **TWD**; Georgia's is **GEL**; mine at home is **PLN**; where I'd been two weeks earlier was **THB**. `TWN` belongs to *nowhere*. The table of suspects:

| Code | Real? | Belongs to | In my story |
|---|---|---|---|
| **GEL** | ✅ | Georgia | what I actually paid (1,00) |
| **TWD** | ✅ | Taiwan | the *real* Taiwan code — never touched my coffee |
| **PLN** | ✅ | Poland | my home currency |
| **THB** | ✅ | Thailand | where I was 15 days prior |
| **TWN** | ❌ |  nowhere | the ghost in the terminal's firmware |

And the number gives it away: **1,00** is my lari, digit for digit. Run the FX sanity check — 1 GEL ≈ 11–12 TWD, so a *genuine* 1‑TWD charge would be ~0.12 zł, pocket change, **not** a coffee. The amount field survived the trip intact; only the currency tag got mangled between the vending terminal, the Georgian acquirer (registered in **Tbilisi**, hence the city mismatch with my **Batumi** tap — normal acquirer noise, not a red flag), and my bank's parser.

**Verdict:** a real, local, legitimate 1 GEL sale. No clone, no Taipei, no fraud report needed. Just a label that detached from the thing. The fix was mundane: keep the receipt, watch the *settled* zł amount, and ask the bank to relabel the line **GEL** and confirm the FX rate — because a non‑existent code can break reconciliation and trip a *false* fraud flag later.

> **Diagnostic rule #2 (the lesson):** when a statement line shows a currency you've never heard of, *don't reach for "block card" first — reach for your passport.* Cross‑check geolocation and merchant descriptor against the amount. Nine times in ten, the drama is metadata, not theft.

---

## 5. Pre‑flight checklist — paste this into every Batumi/money post

- [ ] I know whether this vendor quotes **GEL or USD/EUR** (asked out loud).
- [ ] At the terminal I chose **local currency (GEL)**, declined DCC.
- [ ] I carry **small lari + tetri** for cash‑only spots.
- [ ] I kept the **receipt / screenshot** for anything over a few lari.
- [ ] If a statement line looks foreign, I checked **merchant descriptor + my location (stamps/boarding pass)** *before* assuming fraud.
- [ ] I verified the **live FX rate** today rather than trusting a remembered number.
- [ ] Leftover lari: I either spent the tetri or kept the **exchange receipt** for airport re‑conversion.

---

## 6. Batumi‑specific notes (the texture no generic guide has)

- **The boulevard & beach strip** is the most card‑friendly part of the city; the **old town** backstreets and the **botanical‑garden** approach cafés are where cash suddenly matters.
- **Parking meters and the new vending kiosks** are card‑first and *exactly* where weird statement metadata (see Trap #3 / the TWN ghost) tends to surface — they're cheap terminals with thin firmware, often operated by Tbilisi‑registered processors, so the descriptor city won't match where you stand. Don't let that spook you; check the *amount*.
- **Marshrutkas** to nearby towns pay **cash**, small notes, no change for big bills.
- **Tips**: round up or leave ~10% in cash at sit‑down places; card tips aren't always passed on.
- **Beach‑side umbrellas/loungers** frequently want cash and may quote a "season price" in GEL that surprises you — agree the number *before* you sit.

{{swap these bullets for your own neighbourhood notes; the value of a Batumi post is precisely this local granularity, not the generic "Georgia is cheap" line}}

---

## Close

We hand our trust to a chain of invisible boxes — terminal, acquirer, network, issuer, app — each one re‑typing what the last said, each one allowed a small error that compounds into a headline like *"New Taiwan Dollar"* on a Georgian coffee. The lari was real, the coffee was real, the stamps were real; only the three letters were a ghost. So the next time your statement shows a currency you've never heard of, breathe, look at your passport, look at the amount, and *then* decide whether you have a thief or just a machine that forgot what world it lives in. Sometimes the scariest line on the screen is the boringest one in the room.

*— {{author}}, {{location}}, {{date}}. Case file: `Newtaiwandollargeorgia`.*

<!-- END OF TEMPLATE -->
