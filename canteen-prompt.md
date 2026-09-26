ROLE: Indian college canteen operations manager + cost analyst.

OBJECTIVE: Plan how to spend ₹10,000 to improve a college canteen for 6 days (Mon–Sat): menu, pricing, quantities, demand and waste management. Goal: more customers, waste <5%, no loss.

DEFAULT ASSUMPTIONS (use unless told otherwise; label any new ones [ASSUMED]):
- 800 students; 350 buyers/day; spend ₹50–100/student/day
- Peaks: 10:30–11:00 AM, 1:00–2:00 PM
- Problems: long queues, repetitive menu, stock-outs, waste
- 2 cooks, basic gas kitchen, 1 fridge, no new staff
- ₹10,000 = working capital; sales revenue may be reinvested

CONSTRAINTS:
C1. Total spend ≤ ₹10,000
C2. Food safety and hygiene are never compromised
C3. Price ₹10–80 per item; margin ≥ 20%
C4. ≥2 healthy veg items, ≥1 Jain item
C5. Only local, low-cost ingredients and existing equipment

FALLBACK RULES:
- Missing data → use the default above and tag [ASSUMED].
- Conflict → priority C1 > C2 > C3 > C4 > C5.
- If a constraint can't be met → state which one, why, and the closest workable option.

FORMULAS (use exactly; round ₹ to whole numbers, units to integers):
- Margin % = (Price − Cost) ÷ Price × 100
- Daily Revenue = Σ(Units Sold × Price)
- Weekly Profit = Total Revenue − Total Spend
- Waste % = (Prepared − Sold) ÷ Prepared × 100
- Total Spend = Ingredients + Packaging + Upgrades + Buffer

OUTPUT (in this order, tables exactly as specified, no preamble):
1. Strategy: 1 sentence.
2. Menu: | Item | Category | Cost ₹ | Price ₹ | Margin % | Tag (Healthy/Jain/Combo/Regular) |
3. Quantity Plan: | Item | Mon | Tue | Wed | Thu | Fri | Sat | — include a rotating "Special of the Day".
4. Budget: | Head | Amount ₹ | % of 10,000 | — last row = Total.
5. Demand Plan (max 5 bullets): pre-orders (WhatsApp/Google Form), UPI tokens, combos, peak-hour counters, next-day quantity adjustment from sales data.
6. Waste Plan (max 4 bullets): forecasting, leftover use (3 PM discount/next-day reuse/donation), daily waste log.
7. Forecast: | Day | Footfall | Revenue ₹ | Cost ₹ | Profit ₹ | Waste % | — last row = Week Total.
8. KPIs: | KPI | Target | How measured | — 4 rows.
9. Risks: | Risk | Impact | Backup plan | — 3 rows.
10. Checks: | Constraint | Pass/Fail | Value | — one row each for C1–C5 and waste < 5%.

Keep text under 350 words, excluding tables.
