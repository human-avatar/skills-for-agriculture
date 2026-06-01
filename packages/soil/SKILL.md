---
name: soil
description: "Entry point for soil health decisions. Use when the user mentions soil tests, fertility, amendments, cover crops, compaction, soil biology, carbon, drainage, or says anything like 'my soil is', 'what should I add', 'soil test results', or 'how do I improve my soil'."
allowed-tools: [Read]
---

# Soil

Applies structured thinking to soil health decisions. Diagnoses what kind of soil work is needed and routes to the right approach.

---

## Expert Lineage

*The thinkers whose frameworks underpin this skill.*

**Elaine Ingham — Soil Food Web**
Ingham is the defining authority on soil biology. Her work mapped the complete trophic structure of living soil and established the foundational principle: *a healthy soil food web produces all the nutrients plants need — your job is to feed the food web, not the crop.* Her fungi-to-bacteria ratio framework is the diagnostic lens that explains why certain management approaches work and others fail. Bacteria-dominated soils suit annual crops; fungi-dominated soils suit perennials and trees. Most soil problems that appear to be nutrient problems are actually food web problems — the biology to cycle nutrients has been damaged. Before adding any input, ask: does this feed or kill the food web? Soluble synthetic fertilisers bypass the food web and slowly collapse it. Composts, cover crops, and reduced disturbance feed the food web and let it do the work.

**William Albrecht — Mineral Balance as the Foundation of Health**
Albrecht at the University of Missouri spent forty years correlating soil mineral content with crop nutritional quality, animal health, and ultimately human health. He developed the cation saturation ratios — calcium at 60–75% of CEC, magnesium at 10–15%, potassium at 2–5% — that define balanced soil mineral chemistry. His central insight: *yield and nutritional density are separate variables.* High-yield soils with imbalanced minerals produce high-yield nutritionally hollow food. Mineral balance cannot be bypassed by inputs; it must be built.

**Neal Kinsey — Albrecht System in Practice**
Kinsey refined the Albrecht method into a practical consulting system through decades of farm-level soil work. His *Hands-On Agronomy* is the practitioner's manual for reading soil tests through the Albrecht lens. Key contribution: *the relationship between minerals matters more than the absolute levels.* A soil with adequate calcium but excessive magnesium behaves as if calcium-deficient because Mg displaces Ca on exchange sites and tightens soil structure. Read ratios, not just numbers.

**Jeff Lowenfels & Wayne Lewis — Teaming with Microbes**
Their accessible framework for the soil food web introduced the rhizosphere concept to practical growers: *90% of soil biological activity happens in the few millimetres immediately surrounding plant roots.* Every plant species has a unique microbial signature in its rhizosphere — selecting for specific bacteria and fungi through root exudate chemistry. This means plant diversity directly drives microbial diversity, and monocultures impoverish the biology as surely as pesticides do.

**Christine Jones — Liquid Carbon and Mycorrhizal Priority**
Jones' research on the liquid carbon pathway established that living, photosynthetically active plants are the fastest pathway for moving carbon into deep soil layers — via root exudates pumped into mycorrhizal networks. Her implication for soil management: *fungicide use is the most damaging input for soil carbon accumulation because it severs the mycorrhizal network that moves carbon underground.* Any soil programme aiming to build organic matter must treat fungal biology as the primary asset to protect.

---

## Which tool fits

| You need to... | Tool |
|---|---|
| Interpret a soil test report | test-interpretation |
| Decide what amendments to apply and how much | amendment-planning |
| Choose cover crops for your situation | cover-crop-selection |
| Diagnose and address compaction | compaction-diagnosis |
| Build a long-term fertility program | fertility-planning |

## Routing Decision

- **Have soil test numbers and don't know what they mean** → test-interpretation
- **Know what's low but unsure what to add or how much** → amendment-planning
- **Planning cover crops, unsure what to choose** → cover-crop-selection
- **Suspect compaction — poor drainage, shallow roots, hard pan** → compaction-diagnosis
- **Want a season-by-season fertility strategy** → fertility-planning
- **Unclear** → test-interpretation first; it reveals what else is needed

---

## Test Interpretation

*Makes sense of a soil test report.*

Ask the user to share their soil test numbers. A standard soil test tells you about mineral chemistry — it tells you almost nothing about the food web. Run both together for a complete picture: standard test for minerals, Ingham-method biological assessment (active bacteria, active fungi, protozoa, nematode counts) for biology. The mineral test shows what's there; the biological test shows whether the system can cycle it.

Work through mineral numbers in order:

**1. pH first — it controls everything else.**
- Below 6.0: nutrient lockout likely even if levels look adequate. Lime is usually the first move.
- 6.0–7.0: ideal for most crops. Work with what's here.
- Above 7.5: micronutrient availability drops. Sulphur applications may help.

**2. Organic matter (OM).**
- Below 2%: building OM is the priority — it governs biology, water retention, and nutrient cycling
- 2–5%: working range — maintain and build
- Above 5%: strong biological base, focus on balance not addition

**3. Major nutrients (NPK).**
- Nitrogen: don't read it from a test — too mobile. Use OM trend and crop response instead
- Phosphorus: below 20 ppm (Mehlich-3) warrants attention; above 80 ppm, adding more is wasted money
- Potassium: below 120 ppm is deficient; watch the K:Mg ratio (ideally 2:1 to 4:1)

**4. Secondary nutrients.**
- Calcium: should be 60–75% of cation exchange capacity (CEC)
- Magnesium: 10–15% of CEC; high Mg relative to Ca causes tight, compacted soil
- Sulphur: often overlooked; below 10 ppm warrants attention especially in sandy soils

**5. Micronutrients.**
- Flag any critically low (boron, zinc, manganese are common culprits)
- Fix pH and OM first — many micronutrient issues resolve without direct intervention

**Output format:**
```
SOIL TEST INTERPRETATION
pH: [value] — [status and implication]
Organic matter: [value]% — [status and priority]

MAJOR NUTRIENTS
P: [value ppm] — [status]
K: [value ppm] — [status]

SECONDARY NUTRIENTS
Ca: [% CEC] — [status]
Mg: [% CEC] — [status / ratio note]

MICRONUTRIENTS
[any flagged deficiencies]

PRIORITY ORDER
1. [first action — usually pH or OM]
2. [second action]
3. [third action]

WHAT TO IGNORE FOR NOW
[numbers that don't need action yet]
```

---

## Amendment Planning

*Decides what to add, in what form, and how much.*

Ask: what does the test show is low? What crops are being grown? What's the budget and what inputs are available?

**Decision sequence:**

1. **Fix pH before adding nutrients.** Lime raises pH; sulphur lowers it. Calculate based on buffer pH if available, not just soil pH.

2. **Choose amendment form based on speed and system:**
   - Fast-acting (soluble): results this season, suits cash-flow pressure, higher cost
   - Slow-release (rock minerals, composts): builds over 2–5 years, suits long-term approach, lower cost per unit
   - Biological (compost, inoculants): feeds the system, not just the crop

3. **Common amendments by deficiency:**

| Deficiency | Amendment options |
|---|---|
| Low pH | Ag lime, dolomite (if Mg also low), calcite |
| High pH | Elemental sulphur, acidifying fertilisers |
| Low P | Rock phosphate (slow), single superphosphate (fast), bone meal |
| Low K | Sulphate of potash, greensand, kelp meal, wood ash |
| Low Ca | Gypsum (doesn't raise pH), lime (raises pH), calcite |
| Low Mg | Dolomite, Epsom salt (fast, foliar), serpentine rock |
| Low S | Gypsum, sulphate of potash |
| Low B | Borax (use carefully — narrow margin) |

4. **Rate calculation:** Base on soil test recommendation where possible. If unavailable: conservative first application, retest in 12 months.

**Output:** Amendment list with rates per acre/hectare, application timing, and expected outcome timeline.

---

## Cover Crop Selection

*Chooses the right cover crop for the situation.*

Ask: what's the primary goal, what season is available, what equipment is available for termination?

**Match goal to species:**

| Goal | Species to consider |
|---|---|
| Fix nitrogen | Clover, vetch, field peas, fava beans |
| Break compaction | Daikon radish, tillage radish, chicory |
| Build organic matter fast | Rye, oats, sorghum-sudan, buckwheat |
| Suppress weeds | Dense canopy: rye, oats, buckwheat (allelopathic) |
| Feed soil biology | Diverse mixes — 5+ species outperforms monocultures |
| Winter soil cover | Winter rye, hairy vetch, crimson clover |
| Quick summer gap-fill | Buckwheat (6–8 weeks to flower), sorghum-sudan |
| Attract beneficials | Phacelia, buckwheat, crimson clover, mustard |

**Termination method matters:**
- Roller-crimper: only works at flowering/seed set, suits no-till
- Mowing: faster, may regrow; effective for annuals
- Incorporation: fastest breakdown, disrupts biology
- Winter-kill: easiest — choose frost-sensitive species if no equipment

**Output:** Recommended species or mix, seeding rate, timing window, termination method, and expected benefits.

---

## Compaction Diagnosis

*Identifies compaction, its cause, and how to address it.*

**Diagnosis steps:**

1. **Field observation:** Poor drainage after rain? Shallow root depth when pulling plants? Crops yellowing in wheel tracks? Standing water in low spots?

2. **Penetrometer test:** Insert to resistance — compaction layer is where it stops. Note depth.
   - Tillage pan: 15–25cm
   - Subsoil compaction: 25–45cm
   - Below 45cm: beyond mechanical remedy

3. **Spade test:** Dig 30cm, examine structure. Compacted: horizontal layers, few roots penetrating, grey mottling (anaerobic). Healthy: vertical channels, earthworms, roots following pores.

**Solutions by type:**

| Compaction type | Cause | Remedy |
|---|---|---|
| Surface (0–15cm) | Tillage, foot traffic, rain impact | Cover crops, mulch, reduce tillage, permanent beds |
| Tillage pan (15–25cm) | Repeated tillage at same depth | One-time subsoiling or deep-rooted covers (daikon) |
| Subsoil (25–45cm) | Heavy equipment on wet soil | Deep-rooted covers, biological — years not months |
| Structural (all depths) | Low OM, loss of biology | Long-term OM building, biology restoration |

**Rule:** Never subsoil wet soil — it smears rather than fractures. Only work when dry enough that fracturing occurs.

**Output:** Compaction type and depth, likely cause, recommended remedy, and timeline to expect improvement.

---

## Fertility Planning

*Builds a season-by-season fertility program.*

Ask: what crops are in rotation, what's the soil test baseline, what's the budget, organic or conventional?

**Framework:**

1. **Set the baseline:** Current test results → identify what's deficient, adequate, or excessive.

2. **Map crop nutrient demands:**
   - Heavy feeders (brassicas, corn, squash): high N, moderate P and K
   - Medium feeders (tomatoes, peppers, beans): moderate NPK
   - Light feeders (herbs, root veg): low N, balanced minerals
   - Nitrogen fixers (legumes): add N credit for following crop

3. **Plan inputs against crop sequence:**
   - Apply slow-release amendments (rock minerals, compost) in autumn — they need time
   - Apply fast-release inputs close to planting
   - Time compost to match crop demand, not calendar

4. **Build organic matter year-on-year:**
   - Every 1% OM increase releases ~20–30 lbs N/acre/year
   - Cover crops + compost is faster than either alone
   - Soil biology does the work — feed it, don't replace it

5. **Track and adjust:**
   - Retest every 2–3 years
   - Watch crop response as the leading indicator — plants show deficiency before tests do
   - Record what was applied, when, and what the crop looked like

**Output:** Season-by-season input schedule, estimated nutrient contribution of each input, and indicators to watch for during the season.
