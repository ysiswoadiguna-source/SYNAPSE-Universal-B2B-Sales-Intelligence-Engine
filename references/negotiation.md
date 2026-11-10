# Price, negotiation, objections, and quotation blocks

Read this for discount requests, competitor price pressure, payment-term asks, objections, and any quotation block.

## Contents
1. Diagnose the pressure first
2. What only the user can tell you
3. The concession plan
4. Scope before margin
5. Like-for-like comparison
6. Objections
7. Closing the agreement
8. Quotation blocks (Calc mode)

## 1. Diagnose the pressure first
A request for a lower price has at least four different causes, and the right reply to one is the wrong reply to another.

| Type | How it shows | Reply |
|---|---|---|
| Routine purchasing ask | "Sudah best price?", asked once, late in the process, no competitor named | Hold calmly: "Harga ini sudah nett Pak." Often that is all that is needed. |
| Real budget ceiling | A figure is named; the user or engineer is also worried; scope questions follow | Change scope, quantity, or phasing to fit. Margin last. |
| Competitor as leverage | "Sebelah lebih murah", sometimes with a number, rarely with a document | Ask what the other offer includes. Compare scope before discussing price. |
| Price collection | Price is the only topic; no spec, no date, no access | Indicative info only. No formal concession — there is no deal to win yet. |

If you cannot tell which it is, that is the next question to ask, and it comes before any number.

## 2. What only the user can tell you
You cannot negotiate without these, and you must not guess them. If they are missing, ask the user (not the customer):
- The floor: the lowest price or the largest discount they are authorised to give.
- Who approves anything beyond that, and how long approval takes.
- Which terms are tradeable: payment terms, delivery schedule, warranty length, included services, validity.
- Whether stock and the quoted price are still valid today.

Until the user answers, drafts may hold the position and ask questions, but may not contain a new number.

## 3. The concession plan
Concessions are trades. The reason is practical: a discount given for nothing teaches the customer that asking again works.

- **Every give has a get.** State them together: "Kalau PO bisa masuk minggu ini, kami bisa bantu di ..." Conditional phrasing keeps the concession from becoming the new baseline if the condition isn't met.
- **Plan the sequence before the first move.** Decide with the user what the first, second, and final positions are. Each step should be smaller than the last; shrinking steps signal that the floor is near.
- **One move, then wait.** No second concession until the customer has responded to the first. Never improve an offer into silence.
- **Trade cheap-to-us for valuable-to-them.** Delivery scheduling, documentation, training, a spare kit, or an extended validity may cost little and matter a lot.
- **Put an expiry on it** when it is real — tied to stock, a price list change, or a slot — and never when it is not. Invented deadlines are fake urgency and are found out.
- **Know the walk-away.** If the floor is reached and the gap remains, say so plainly and kindly; offer a smaller scope instead of a smaller margin.

Typical gets: faster PO, larger quantity, a longer contract, shorter payment terms or a down payment, a reference or site visit permission, bundled items, flexibility on delivery date.

## 4. Scope before margin
When budget is the true constraint, look for a version of the deal that fits before touching price:
- Phase it: essential items now, the rest in the next budget period.
- Change the specification tier where the application allows — never below what safety, regulation, or the stated duty requires.
- Remove optional services the customer can do themselves, and state what they then take responsibility for.
- Change quantity or pack size.
- Offer a different commercial form if the user's company supports it (rental, staged payment).

Always state the consequence of the reduced scope in the draft. A cheaper offer that silently drops something is a future complaint.

## 5. Like-for-like comparison
When the customer cites a cheaper offer, ask to compare on these lines. The aim is not to attack the competitor; it is to make sure both sides are pricing the same thing.

Scope of supply (complete set or main unit only) · brand and origin · specification and rating · delivery point and freight · installation and commissioning · testing and certification documents · warranty period and who honours it locally · spare parts availability · service response · payment terms · lead time · tax treatment and price basis.

> "Supaya perbandingannya adil Pak, boleh tahu penawaran sebelah itu sudah termasuk instalasi dan ongkos kirim, atau unit saja?"

If the scopes genuinely match and the gap is real, report that honestly to the user. Do not invent a difference, and never describe the competitor's product as inferior unless the user has verified it.

## 6. Objections
Method: isolate, validate, resolve.
- **Isolate.** "Selain soal harga, apakah ada hal lain yang masih mengganjal Pak?" If something else surfaces, that is the real objection.
- **Validate.** Acknowledge without agreeing that we are wrong: "Wajar Pak, selisihnya memang terasa."
- **Resolve** with one of: proof (a document, a reference, a calculation), an alternative (another option that removes the concern), a trade (section 3), or a next step (a call with the technical user).

| Objection | Often really means | A useful move |
|---|---|---|
| "Mahal" | Compared with what? Budget, a competitor, or expectation | Ask which comparison; then section 4 or 5 |
| "Lead time terlalu lama" | A date they must meet | Ask the required date; check with the user for partial delivery or alternatives |
| "Belum ada budget" | Timing, or no approved need | Ask when the next budget window opens; park with a date |
| "Sudah ada supplier langganan" | Switching risk | Offer a small, low-risk first order or act as the second source |
| "Perlu approval dulu" | A process we cannot see | Ask who approves and what they need from us to decide |
| "Minta TOP lebih panjang" | Cash flow or company policy | A trade, not a courtesy — and only terms the user has confirmed they can give |
| "Nanti kami kabari" | Low priority or a polite no | Ask for a decision window once; then wait |

## 7. Closing the agreement
When terms are agreed, write them down in one message before the PO: item and scope, quantity, price and price basis, tax treatment as the user stated it, delivery estimate and point, payment terms, validity, and anything excluded. Ask the customer to confirm. Before the user sends it, they must verify stock, price validity, and that the concession is within their authority — say so in a note.

## 8. Quotation blocks (Calc mode)
A quotation block is checked by people who did not write it. Build it so that every figure can be recomputed from the figures above it.

**Inputs.** Use only what the user supplied: item names, quantities, units, unit prices, discounts, tax rate and method, currency, rounding. Missing inputs stay as labelled blanks and are listed once below the block. Tax rates and tax-base methods change with regulation — take them from the user or from their own previous quotation, and never supply one from memory.

**Order of calculation** (unless the user's sample shows another order — then follow theirs and say so):
1. Line total = quantity × unit price
2. Line discount, if any → net line
3. Subtotal = sum of net lines
4. Header discount, if any → net subtotal
5. Other charges the user listed (freight, installation)
6. Tax base → tax amount
7. Grand total

**Discounts.** A percentage discount and an amount discount are different instructions; do not convert one to the other unless asked. Stacked discounts ("10% + 5%") apply in sequence, not added, unless the user says otherwise — if it is unclear, ask, because the difference is real money.

**Rounding.** Follow the user's sample. If there is none, keep full precision through the calculation and round only the displayed tax and total, then say which rounding you used.

**Checking.** Compute twice by different routes (for instance, sum the lines, then separately multiply totals), using code when available. If your total differs from one the user gave, show both and the line where they part.

**Format.** Copy the user's number style ("Rp 12.500.000" vs "12,500,000"). Keep conditions — validity, delivery estimate, payment terms, lot or item basis, exclusions — as the user wrote them; do not add conditions they did not give.

```
No  Item                      Qty  Unit   Harga satuan     Jumlah
1   ...                       ...  ...    Rp ...           Rp ...
                                          Subtotal         Rp ...
                                          Discount ...%    Rp ...
                                          DPP              Rp ...
                                          PPN ...%         Rp ...
                                          Total            Rp ...
Validity: [...]   Delivery: [...]   Payment: [...]
```
