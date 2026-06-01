---
name: seasons
description: "Seasonal and annual farm planning. Use when the user asks about crop rotation, succession planting, what to do next, planning the year, when to sow or plant, planning a market garden calendar, livestock seasonal tasks, or says 'what should I be doing now', 'how do I plan my year', or 'I need a growing calendar'."
allowed-tools: [Read]
---

# Seasons & Planning

A farm runs on rhythm. The planning tool that removes the most stress and prevents the most mistakes is a calendar — not a sophisticated one, but one that actually covers the whole year and gets used. This skill builds that calendar and keeps it honest: living roots in the ground as much of the year as possible, gaps covered, and the soil never left bare.

---

## Expert Lineage

*The thinkers whose frameworks underpin this skill — and what they specifically discovered that changes how you farm.*

**Jean-Martin Fortier — The Market Garden Production Calendar**
Fortier's *The Market Gardener* introduced the production calendar as the primary management tool for the small-scale intensive farm. His specific contribution: the discipline of tracking sellout rates at each market date — what sold, what was left over, in what quantities — and using that data to refine the planting calendar the following year. He demonstrated that a micro-farm of 1.5 acres could generate a six-figure income through precise succession planning and variety selection. The calendar is not a static plan but a living document that improves each year through systematic recording.

**Eliot Coleman — Four-Season Production**
Coleman's work in Maine (Zone 5) showed that year-round production without artificial heating is possible in cold climates if the calendar is built around two key dates: the "killing freeze" (sustained below -10°C) and the days-to-maturity of overwintering crops. His insight: sow overwintering crops 6–8 weeks before the killing freeze — they grow to a size that can sustain through winter dormancy and resume growth in spring while competitors are still waiting to sow. The winter harvest extends the income-generating calendar by 3–4 months without heating infrastructure.

**Joel Salatin — Diversified Farm Operations Calendar**
Salatin's polyface system demonstrated how different farm enterprises have complementary seasonal profiles: the enterprises that are labour-intensive in spring are low-maintenance in summer, and vice versa. His calendar insight: plan the whole farm's labour demands together, not enterprise by enterprise. Stack enterprises so peak demands don't coincide. The chicken tractor behind the cattle — following on clean pasture — is a calendar decision as much as a production decision.

---

## Which tool fits

| You need to... | Tool |
|---|---|
| Build a month-by-month crop sowing and harvest calendar | crop-calendar |
| Design a crop rotation for soil health and pest management | rotation-planning |
| Plan key livestock tasks through the year | livestock-calendar |
| Schedule succession plantings for continuous harvest | succession-planning |
| Review the season and improve next year's plan | annual-review |

## Routing Decision

- **Need to know what to do this month** → crop-calendar
- **Planning a rotation for the coming season** → rotation-planning
- **Managing livestock, need a seasonal task schedule** → livestock-calendar
- **Want to stop having too much or too little at once** → succession-planning
- **End of season, reviewing what to change** → annual-review

---

## Crop Calendar

*Month-by-month sowing, planting, and harvest schedule for temperate climates.*

Ask: what climate zone is the user in? What crops are in the system? Primary purpose — market, household, or mixed? The calendar below is set for Northern Hemisphere temperate (UK/Northern Europe, US/Canada zones 5–7). Adjust timing by 4–6 weeks later for zone 4 or colder, and 2–4 weeks earlier for warmer maritime climates.

**Soil health principle:** every month that shows no crop in ground is a potential bare soil period. Flag these months and suggest a cover crop. Living roots year-round is the target — deviations are acknowledged but always explained.

| Month | Sow Indoors | Plant Out | Direct Sow | Harvest | Cover Crop Window |
|---|---|---|---|---|---|
| **Jan** | Onions, leeks, celeriac | — | — | Stored roots, leeks, kale, sprouts | Existing winter covers in place |
| **Feb** | Peppers, aubergine, celery, early tomatoes | — | — | Leeks, stored veg, overwintered salad | Existing winter covers |
| **Mar** | Tomatoes, brassicas, lettuce, courgette, squash | Overwintered onions; early salad under cover | Peas, broad beans, spinach, carrots (late Mar) | Leeks, purple sprouting, overwintered salad | Winter covers terminating — sow spring mix in gaps |
| **Apr** | Squash, cucumbers, basil, celery | Lettuce (early); brassica transplants | Carrots, beetroot, salad, radish, Swiss chard | Asparagus, early salad, radish | — |
| **May** | — | Tomatoes (after last frost); courgette; squash; French beans | Beans, sweetcorn, salad successions, beetroot | Asparagus, salad, broad beans, first peas | — |
| **Jun** | — | Leeks, brassica transplants | Beetroot, carrots, salad, chard, fennel | Peas, salad, early potatoes, garlic (late) | Buckwheat in any early harvest gaps |
| **Jul** | Autumn brassicas; overwintering onions | — | Autumn salad, beetroot, chard, spinach | Potatoes, garlic, onions, salad, courgette, beans | Buckwheat or phacelia in harvest gaps |
| **Aug** | — | Autumn salad, brassicas (overwintering) | Oriental leaves, spinach, land cress, lamb's lettuce | Tomatoes, courgette, beans, peppers, squash | Phacelia, buckwheat in cleared ground |
| **Sep** | Overwintering lettuce | Overwintering salad; spring onions (covered) | Winter salad, land cress, corn salad | Squash, beans, tomatoes (last); brassicas | CRITICAL: sow winter cover crops in all cleared ground |
| **Oct** | — | — | Garlic (late Oct); broad beans (mild areas) | Root veg, leeks, brassicas, kale | Winter rye, hairy vetch, field beans — all cleared ground |
| **Nov** | — | — | — | Leeks, roots, brassicas, kale, stored crops | Establish winter covers; check germination |
| **Dec** | — | — | — | Stored crops, leeks, kale, winter salad (covered) | Winter covers established and holding |

**Note on September–October:** This is the most critical cover crop window of the year. Every bed cleared of a summer crop has a narrow window before soil temperatures drop below cover crop germination threshold (~7°C for rye and vetch). Miss this window and bare soil persists until March — five months of biological dormancy.

**Output:**
```
CROP CALENDAR — [Farm name / Year]

ZONE ADJUSTMENT: [note any adjustment from base UK/zone 6 timing]

MONTH | SOW INDOORS | PLANT OUT | DIRECT SOW | HARVEST | COVER CROP
Jan   |             |           |            |         |
Feb   |             |           |            |         |
Mar   |             |           |            |         |
Apr   |             |           |            |         |
May   |             |           |            |         |
Jun   |             |           |            |         |
Jul   |             |           |            |         |
Aug   |             |           |            |         |
Sep   |             |           |            |         |
Oct   |             |           |            |         |
Nov   |             |           |            |         |
Dec   |             |           |            |         |

BARE SOIL MONTHS (if any): [list] — cover crop solution: [species]
```

---

## Rotation Planning

*Designs a crop rotation that breaks pest cycles, balances fertility, and maintains soil biology.*

**The three jobs a rotation does:**
1. **Breaks pest and disease cycles** — soil-borne pathogens (clubroot, allium white rot, nematodes) build up when the same family returns too quickly. Minimum 3 years between same family on same ground; 5–7 years for persistent problems.
2. **Balances fertility demand** — heavy feeders follow legumes or composted ground; light feeders follow heavy feeders; soil-restoring crops (green manures, roots) come before the heaviest feeders.
3. **Manages the food web** — different crop roots feed different microbial communities. Rotating families cycles the food web through diversity rather than monoculturing it.

**Standard 4-bed rotation (temperate market garden):**

The four crop families to rotate: Brassicas (heavy feeders, clubroot risk), Alliums + salad (light feeders), Roots (carrots, parsnips, beet — no fresh compost or they fork), Legumes/potatoes (nitrogen-fixing or disease break).

| Year | Bed 1 | Bed 2 | Bed 3 | Bed 4 |
|---|---|---|---|---|
| Year 1 | **Brassicas** (heavy feeders) | **Alliums + salad** (light feeders) | **Roots** (no compost) | **Legumes + potatoes** (break crop) |
| Year 2 | **Legumes + potatoes** | **Brassicas** | **Alliums + salad** | **Roots** |
| Year 3 | **Roots** | **Legumes + potatoes** | **Brassicas** | **Alliums + salad** |
| Year 4 | **Alliums + salad** | **Roots** | **Legumes + potatoes** | **Brassicas** |

**Extended 6-bed rotation (adds dedicated soil-building and cover crop years):**

For larger systems: add Cucurbits (courgette, squash, cucumber — heavy feeders, different family) and a dedicated green manure/restoration year. This extends to a 6-bed rotation with better pest pressure management and more biological recovery time between high-demand crops.

**Rotation planning rules:**
- Never follow brassicas with brassicas on the same ground within 3 years.
- Don't apply fresh compost before root crops (parsnip, carrot, parsley root) — they fork.
- Potatoes and tomatoes are both Solanaceae — don't follow one with the other.
- Legumes fix nitrogen only if nodulated — inoculate seed in new ground.

**Output:**
```
ROTATION PLAN — [number]-bed system

OVERVIEW TABLE:
[Year × Bed matrix as above]

PEST AND DISEASE BREAKS:
- Clubroot: Brassicas return to each bed every [X] years
- Allium white rot: Alliums return every [X] years
- [other specific concerns]

FERTILITY FLOW:
- Compost applied before: [crops]
- Nitrogen credit from legumes credited to: [following crop]

COVER CROP IN ROTATION:
- [which beds, which months, which species]
```

---

## Livestock Calendar

*Key seasonal tasks for farm animals, month by month.*

Ask: what species are in the system? What's the production objective — dairy, meat, fibre, eggs, land management? The calendar below covers cattle, sheep, pigs, and poultry. Select the relevant sections.

**General principle (Savory):** the livestock calendar is subordinate to the grazing plan. Breeding, weaning, and housing dates should be set to align the period of highest animal nutritional demand with the period of peak grass growth — spring and early summer in temperate climates.

| Month | Cattle | Sheep | Pigs | Poultry (layers) |
|---|---|---|---|---|
| **Jan** | Winter housing; monitor body condition; check hay quality and stocks | Pregnancy scanning; supplementary feed if needed; foot inspections | Indoor; monitor condition; fresh bedding management | Low production; supplement light to 16 hrs/day to maintain production |
| **Feb** | Monitor close-calving cows; prepare calving area; navel dipping supplies | Ewes approaching lambing (early breeds); prepare lambing area | — | Continue light supplementation |
| **Mar** | Main calving (spring calvers); check colostrum; calf health monitoring | Peak lambing; intensive monitoring; colostrum management; hypothermia kit ready | Begin outdoor rotation if soil allows | Broiler season begins; layer production rising with day length |
| **Apr** | Turn-out after calving; check soil conditions before turnout to avoid poaching | Turn out with lambs; assess grass covers; adjust stocking rate | Begin outdoor rotation; move every 1–2 weeks | Layers on spring grass flush; production peaks |
| **May** | Grazing rotation begins; monitor grass cover weekly; first parasite monitoring | FAMACHA eyelid scoring starts; first worm risk; adjust rotation | Active rotation on 3+ paddocks; monitor ground recovery | Broiler batches processing; eggs in full production |
| **Jun** | First silage cut (if applicable); body condition scoring | Shearing; dag before shearing to prevent flystrike; weigh lambs | Rotate 2-week cycles; monitor rooting impact and vegetation recovery | Peak egg production; provide shade and water |
| **Jul** | Monitor for summer mastitis (dry cows); fly control; continue rotation | Weaning; sort lambs for sale vs. keep; worm burden assessment | Wallow provision essential in heat; rotate as usual | Heat management critical; egg quality may drop in high heat |
| **Aug** | Body condition score before weaning; assess cows for next breeding | Pre-mating nutrition for ewes; flush thin ewes; foot trimming | Finishing animals — assess condition; book abattoir | Moult preparation in second-year hens |
| **Sep** | Weaning (spring calvers); pre-housing health check; pre-TB test if due | Tupping begins (rams in); record ram-ewe ratios | Move finishing pigs; prepare winter accommodation | Autumn moult in older hens; production dip |
| **Oct** | Housing if soil conditions require; pre-housing vaccination programme | Tupping peak (mark ewes with raddle to track service) | Housing or indoor rotation as weather worsens | Reinstate light programme before day length drops below 10 hrs |
| **Nov** | Winter housing; adjust winter ration; feet inspection | Early pregnancy; monitor condition; foot rot management | Indoor housing; deep bedding system | Maintain 16-hr light programme; clean and disinfect housing |
| **Dec** | Housing; monitor hay/silage quality; check feed budgets | Mid-pregnancy; mineral bolus if needed; plan scanning date | — | Deep-clean housing in quiet period; check ventilation |

**Output:**
```
LIVESTOCK CALENDAR — [Species / Breed]

CRITICAL DATES:
Breeding/mating: [month]
Birth/lambing/farrowing: [month]
Weaning: [month]
Housing (in): [month]
Turn-out: [month]

MONTHLY TASKS:
[selected months with specific tasks for this farm]

GRAZING PLAN INTEGRATION:
Peak demand period: [month]
Peak grass growth: [month]
Alignment note: [whether these match or where the gap is]
```

---

## Succession Planning

*Calculates how many plantings are needed at what intervals to achieve continuous harvest.*

The succession planning formula:

**Planting interval** = how often you want to harvest (in days)
**Number of plantings always in ground** = days to maturity ÷ planting interval

This tells you how many beds/rows of that crop need to be at different stages simultaneously.

**Worked example — lettuce:**
- Days to maturity: 35 days (from transplant)
- Desired harvest interval: 7 days (weekly market)
- Plantings always in ground: 35 ÷ 7 = 5 plantings
- Sow one new tray every 7 days; at any point, 5 trays are at different stages

| Week | Planting | Stage at week 5 |
|---|---|---|
| Week 1 | Sow tray A | Tray A ready to harvest |
| Week 2 | Sow tray B | Tray B at 4 weeks |
| Week 3 | Sow tray C | Tray C at 3 weeks |
| Week 4 | Sow tray D | Tray D at 2 weeks |
| Week 5 | Sow tray E | Tray E at 1 week; harvest tray A; sow tray F |

**Common succession intervals (temperate climate, summer production):**

| Crop | Days to maturity | Suggested planting interval | Notes |
|---|---|---|---|
| Lettuce (leaf) | 28–35 days | 7–10 days | Slow to bolt varieties extend harvest window |
| Radish | 21–28 days | 10–14 days | Short harvest window — succession essential |
| Salad mix (cut-and-come-again) | 28–35 days | 14–21 days | Multiple cuts possible |
| Spinach | 40–50 days | 14–21 days | Bolts quickly in heat — gap July/Aug |
| French beans | 55–65 days | 21 days | 3 plantings covers the season |
| Courgette | 50–60 days | 21–28 days | One plant produces long — few plants needed |
| Kale (cut-and-come-again) | 60–70 days | 28 days | Autumn sown for winter harvest |
| Beetroot | 50–60 days | 14–21 days | Stores well so harvest window is flexible |

**Complications to plan for:**
- Bolting: summer lettuce bolts in heat — switch to bolt-resistant varieties or pause succession July/August
- Glut vs. gap: if the market or household can't absorb more of something, extend the planting interval — don't just grow more
- Transplant vs. direct sow: transplanted crops allow 3–4 extra weeks of planning flexibility vs. direct-sown

**Output:**
```
SUCCESSION PLAN — [Crop]

Target harvest volume: [amount per week/market date]
Days to maturity: [days from transplant / direct sow]
Planting interval: [days]
Number of plantings always in ground: [number]
Bed/row length per planting: [length]

SCHEDULE (first 8 weeks):
Week 1: Sow/plant [batch 1] → harvest [date]
Week 2: Sow/plant [batch 2] → harvest [date]
[continue]

GAPS TO WATCH:
- [month]: [potential glut or gap and how to manage it]
```

---

## Annual Review

*Records what happened this season and turns observations into improvements for next year.*

The annual review is the Fortier discipline: collect the data that makes next year's calendar more accurate. Do it at the end of the season when memory is fresh — November is ideal for a temperate growing system.

**What to record:**

**1. Yield per bed or area**
How much did each bed or area produce, in kg or units? Which beds outperformed and which underperformed? This identifies whether the rotation, variety choice, or soil health is working.

**2. Market performance**
What sold out first (undersupply)? What was left over most often (oversupply)? What was the most profitable per metre? This is the Fortier discipline — use sellout rates to shift the production calendar toward what sells.

**3. Crop performance**
What grew well and what struggled? What failed entirely? Were failures due to weather, pests, soil, or timing errors? Separate these: weather failures are different from management failures.

**4. Soil observations**
Earthworm count (>10 per spade dig = good); structure when digging (friable or compacted); colour change over the year. When was the last soil test? Schedule next one.

**5. Labour record**
Which enterprises or tasks took significantly more or less labour than expected? Which crops have high labour-to-return ratios? This informs what to drop or simplify.

**6. What to change**
Based on the above: what to grow more of, what to grow less of, what to stop entirely, what timing to shift, what rotation change to make.

**Output:**
```
ANNUAL REVIEW — [Year]

WHAT WORKED WELL
- [crop/enterprise]: [why — yield, market, ease, soil response]

WHAT UNDERPERFORMED
- [crop/enterprise]: [why — pest, timing, variety, soil, market]

MARKET DATA
- Best sellers (undersupply — grow more): [list]
- Consistently left over (oversupply — grow less): [list]
- Best margin per metre: [crop]

SOIL HEALTH
- Earthworm counts: [better / same / worse than last year]
- Structure observations: [note]
- Soil test due: [yes/no — schedule date]
- Cover crop gaps this year: [months where bare soil occurred — plan to cover next year]

LABOUR
- More labour than expected: [task]
- Less labour than expected: [task]
- Enterprise to simplify or drop: [if any]

CHANGES FOR NEXT YEAR
1. [specific change]: [rationale]
2. [specific change]: [rationale]
3. [specific change]: [rationale]

NEXT SEASON CALENDAR ADJUSTMENTS
- Sow [crop] [X] weeks earlier/later
- Increase [crop] succession by [X] more plantings
- Drop [crop] from rotation
```
