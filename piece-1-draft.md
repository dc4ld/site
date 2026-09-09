# The 20% that isn't a discount

**Consultancy summaries describe Eskom's new generation capacity charge as "phased in at 20% in year 1 and 30% in years 2 and 3". The numbers are right; the framing is wrong. Customers pay the full charge every year — and for anyone modelling a wheeled power purchase agreement, what actually changed matters more than a price increase.**

*David Jinadu · Datum Markets · 14 September 2026*

---

## The short version

- **Eskom's 2026/27 generation capacity charge is about 1.5× the 2025/26 rate across every Megaflex voltage band.** That is a reallocation between fixed and variable recovery — not the 8.76% tariff increase.
- **Customers pay 100% of the charge every year.** The widely quoted "20% in year 1, 30% in years 2 and 3" is only the share appearing as a fixed R/kVA line; the remaining 80%, then 70%, is recovered inside the energy charge.
- **No part of the charge can be reduced by wheeling.** The fixed portion is a demand charge, and NERSA explicitly excluded the energy-charge portion from the wheeling and net-billing credit.

Eskom's 2026/27 tariffs arrived with a headline increase of 8.76% for direct customers. Underneath it, one component of the Megaflex tariff rose by roughly half again.

The generation capacity charge on Megaflex non-local-authority supplies went from R8.09 to R12.27 per kVA per month at 500V–66kV. That is a factor of 1.52. The same multiple appears at every voltage band: 1.5158 below 500V, 1.5167 at 500V–66kV, 1.5163 at 66–132kV, 1.5171 above 132kV.

Four voltage bands, two tariff years, one ratio. That is not a price increase — a price increase does not arrive at the same multiple across four unrelated rates. It is a reallocation, and the regulator's decision says so in terms.

## Two decisions, routinely conflated

Part of why this gets missed is that two separate regulatory decisions are at work, and they are usually discussed as one.

NERSA's MYPD6 determination sets **how much** revenue Eskom may recover. That is the 8.76%, and it was announced, reported and budgeted for.

A separate decision, on Eskom's Electricity Retail Tariff Plan, decides **how** that revenue is structured into individual charges. That is where the generation capacity charge moved.

The 8.76% is the revenue. The 1.5× is the structure. They are not the same event — and only one of them was announced.

## What the decision actually says

The generation capacity charge (GCC) is Eskom's mechanism for recovering the fixed costs of generation capacity through a fixed charge instead of through the price of energy. The Cost of Supply study allocated **R19.05 billion** of generation fixed cost to it — about 7% of total generation cost, reduced from 23% in Eskom's previous application after customer objections. It is levied in rands per kVA per month, calculated by dividing allocated costs by *annual utilised capacity*: the higher of a customer's notified maximum demand, or the maximum demand actually registered over a rolling twelve-month period.

NERSA agreed with the principle. Separating fixed costs "sends the right economic signals", and Eskom "must also prepare for a changing Electricity Supply Industry that is moving towards a market". What it did not accept was the step change. Its stated concern was the impact on below-average users, which it found "severe at its current level".

So it approved the charge, then throttled how much of it appears as a fixed line:

> "the allocation towards fixed charges must be reduced to 20% of its current level in year 1 and 30% of the current proposed level in years 2 and 3. The remaining portion of the GCC (80% in year 1 and 70% in year 2 and 3) is included and recovered through the energy charge."

That second sentence is the one the summaries drop.

The 20% and 30% are not the share of the charge customers pay. They are the share that appears as a fixed R/kVA line on the bill. The other 80%, then 70%, is still collected — inside the energy charge.

**Customers pay 100% of the generation capacity charge in every year of the phase-in.** What moves is the split between fixed and variable recovery. And NERSA sets no fully-phased level at all: the decision stops at 30%. There is no year four in it.

## Why the split matters more than the total

If the total is unchanged, a reallocation might look like an accounting detail. It is not, because fixed and variable charges respond to entirely different behaviour.

A charge levied on utilised capacity is driven by your single hungriest half-hour in a rolling twelve-month window. A charge inside the energy price is driven by every kilowatt-hour you consume. Move a large cost from the second basis to the first, and two customers with identical annual consumption but different load factors will see their bills move in opposite directions — without either of them changing anything.

The customer running flat around the clock spreads the capacity charge across a great many kilowatt-hours and gains. The customer with sharp peaks and low utilisation pays the same fixed charge across far fewer units and loses.

NERSA's own reasoning confirms the direction. The users it moved to protect were precisely the "below-average" ones — the customers for whom a demand-based charge lands hardest. The throttle exists because the reallocation has winners and losers, and the regulator could see who they were.

## The wheeling exclusion

Then comes the sentence I have not seen quoted anywhere:

> "To ensure that all customers contribute to this charge, this portion of the GCC included in the energy charge is excluded from the energy credit provided under wheeling and net-billing (offset) transactions."

A wheeling transaction works by crediting a customer for the Eskom energy they no longer buy. That credit is the entire economic basis of the 20–30% saving that wheeled power purchase agreements are marketed on. This clause carves the generation capacity charge out of it.

Take the two portions in turn. The fixed portion is a demand charge on utilised capacity — payable whether the electrons came from Eskom or from a wind farm three provinces away, because wheeling does not reduce your notified maximum demand. The remaining portion sits inside the energy charge and is *explicitly excluded* from the credit.

Which means the position is simpler and harder than most models assume: **the generation capacity charge cannot be reduced by wheeling at all.** Not the fixed part, not the energy-embedded part. R19 billion of Eskom's cost base has been deliberately placed beyond the reach of offset transactions, and the decision says why — "to ensure that all customers contribute to this charge".

The phase-in does not change that immunity. It changes only whether the unavoidable cost is assessed on your kVA or on your kWh. So for a wheeling customer the lever against this charge is demand management, not energy substitution — and a model that credits any part of the GCC back to the customer overstates the saving.

Whether that materially dents a particular deal depends on the customer's load factor and the size of the GCC against the rest of their bill. That is arithmetic rather than opinion. But it is arithmetic that has to be done per customer, and a model built on the 2025/26 split will get it wrong.

## Three things worth checking

If you are modelling a wheeled PPA or building a 2026/27 electricity budget:

1. **Which phase-in year does your rate reflect?** The 2026/27 schedule reflects the 30% fixed allocation. A model still carrying 2025/26 rates has its GCC line roughly 1.5× too low.
2. **Does your model credit the GCC portion inside the energy charge?** If it does, it overstates the wheeling saving. The decision excludes it.
3. **What is your utilised capacity actually set to?** The denominator is the higher of notified maximum demand or the maximum registered over a rolling twelve months. One bad half-hour eleven months ago is still in this month's bill.

## Method and sources

Every figure here comes from public documents.

The rates were extracted from Eskom's published tariff rates workbooks for 2025/26 and 2026/27, then independently cross-checked figure for figure against the corresponding Schedule of Standard Prices — sixteen values across four voltage bands and two years, VAT-exclusive and VAT-inclusive, all matching.

The quotations, the R19.05 billion allocation and the 7%-down-from-23% comparison are from NERSA's Reasons for Decision on Eskom's Electricity Retail Tariff Plan, section 8.9. The 8.76% increase for direct customers is from Eskom's published 2026/27 tariff increase notice, which attributes it to NERSA's MYPD6 decisions; local authority tariffs rose 9.01% from 1 July, which is itself a reminder to check which schedule you are reading.

The 1.5× ratio is computed from the two published schedules. NERSA publishes the 20/30 and 80/70 splits; the ratio follows from them and from the underlying rates, and is not itself a regulated figure.

One note on the source documents. Eskom's published 2025/26 rates workbook contains cells on the WEPS sheet that evaluate to `#REF!` as shipped — the rates are readable in the PDF schedule instead, and nothing above depends on them. It is a small thing, and a useful reminder: a published file is not the same as a checked one.

---

*Datum Markets builds independent tariff and wheeling analysis for southern African power markets from primary sources only. Every figure we publish carries its source reference. Enquiries: info@datummarkets.co.uk*

*This is analysis, not financial, legal or investment advice.*
