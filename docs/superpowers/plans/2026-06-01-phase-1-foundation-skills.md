# Phase 1: Foundation Skills Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Write the four Phase 1 foundation skills (`soil`, `regenerative`, `pests`, `seasons`) to the quality standard defined in the spec, establishing the SKILL.md template that all subsequent phases follow.

**Architecture:** Each skill is a single `SKILL.md` file inside `packages/<name>/`. Files follow a fixed structure: YAML frontmatter → opening philosophy → Expert Lineage → routing table → sub-tool sections. Quality is validated against the 6 criteria from the spec after each skill. Phases 2–5 follow the same pattern using this plan as a template.

**Tech Stack:** Markdown, YAML frontmatter, skills-for-agriculture package structure, git.

**Spec:** `docs/superpowers/specs/2026-06-01-skills-for-agriculture-plan.md`

---

## SKILL.md Template

Every skill follows this structure. Deviations require explicit justification.

```markdown
---
name: <skill-name>
description: "<Trigger description — when to invoke this skill. Include natural-language phrases a user might say. Keep under 200 chars.>"
allowed-tools: [Read]
---

# <Skill Title>

<Opening paragraph: 2–4 sentences. States the goal of the skill and the core principle it operates from. No bullet points. Written in second person ("your farm", "you"). Sets the tone — practical and direct.>

---

## Expert Lineage

*The thinkers whose frameworks underpin this skill — and what they specifically discovered that changes how you farm.*

**<Thinker Name> — <One-line identifier>**
<2–4 sentences. Specific contribution, not just biography. What did they discover, prove, or demonstrate that directly changes a recommendation in this skill? End with the practical implication for the farmer.>

[Repeat for each thinker — typically 3–6 thinkers per skill]

---

## Which tool fits

| You need to... | Tool |
|---|---|
| <user goal> | <sub-tool-name> |
[one row per sub-tool]

## Routing Decision

- **<User situation>** → <sub-tool-name>
- **<User situation>** → <sub-tool-name>
[one bullet per routing case — cover the common entry points]

---

## <Sub-tool Name>

*<One line: what this sub-tool does.>*

<Content: structured, actionable, direct. Use tables where they help. Use decision sequences where there is a clear order of operations. Always end with an Output section showing what a good response from this sub-tool looks like — either a template or an example.>

**Output:**
<Template or example of the skill's output — what the user receives at the end of this sub-tool.>

---

[Repeat sub-tool section for each tool in the routing table]
```

---

## Quality Checklist

Run this after writing each skill. Every box must be checked before committing.

- [ ] **Goal-oriented:** Can you complete the sentence "This skill helps the user ___"? Is that goal stated in the opening?
- [ ] **Sustainability-biased:** Does every sub-tool default to sustainable practice while documenting conventional clearly? Is the conventional path given without judgment?
- [ ] **Sustainable alternative always present:** Does every intervention recommendation include a note on a more ecologically sound alternative?
- [ ] **Nature-aligned reasoning:** Does the skill's logic favour working with natural systems? Is this implicit in recommendations, not preachy?
- [ ] **Soil health (Ingham):** Does the soil health angle appear where it's relevant? Is the food web lens applied before recommending inputs?
- [ ] **Transition-aware:** Does the skill include a clear pathway from current practice toward better practice?
- [ ] **Context-sensitive delivery:** Does the skill lead with the practical answer before the ecological framing? Would a conventional farmer in a hurry get what they need in the first 20% of the skill?
- [ ] **Expert Lineage present:** Are 3–6 thinkers documented with specific contributions, not just names?
- [ ] **Output templates present:** Does every sub-tool end with a concrete output template?
- [ ] **No TBDs or placeholders:** Every section has real content.

---

## Task 1: Write `soil` skill

**File:** `packages/soil/SKILL.md` (overwrite stub)

**Spec reference:** Cluster 2 — Land & Ecology — `soil` entry

Sub-tools to write: `test-interpretation`, `amendment-planning`, `cover-crop-selection`, `compaction-diagnosis`, `fertility-planning`

- [ ] **Step 1: Write the YAML frontmatter and opening**

Replace the entire contents of `packages/soil/SKILL.md` with:

```markdown
---
name: soil
description: "Entry point for soil health decisions. Use when the user mentions soil tests, fertility, amendments, cover crops, compaction, soil biology, carbon, drainage, or says anything like 'my soil is', 'what should I add', 'soil test results', 'how do I improve my soil', or 'why are my crops struggling'."
allowed-tools: [Read]
---

# Soil

Soil decisions are biology decisions. The mineral chemistry on a soil test tells you what's there; the soil food web tells you whether the system can use it. Before adding any input, the right question is: does this feed or kill the biology? A healthy food web — bacteria, fungi, protozoa, nematodes, earthworms — produces every nutrient a crop needs. Your job is to feed the food web, not the crop.

---

## Expert Lineage

*The thinkers whose frameworks underpin this skill — and what they specifically discovered that changes how you farm.*

**Elaine Ingham — Soil Food Web**
Ingham mapped the complete trophic structure of living soil and established the fungi-to-bacteria ratio as the diagnostic lens: bacteria-dominated soils suit annuals; fungi-dominated soils suit perennials and trees. Her most actionable finding: most "nutrient deficiency" problems are food web problems — the biology to cycle available nutrients has been killed. Soluble synthetic fertilisers feed the crop while bypassing and slowly collapsing the food web. Before adding any input, ask whether it feeds or kills the biology.

**William Albrecht — Mineral Balance**
Albrecht at the University of Missouri spent forty years correlating soil mineral content with crop quality and animal health. He developed the cation saturation ratios that define balanced soil mineral chemistry: calcium at 60–75% of CEC, magnesium at 10–15%, potassium at 2–5%. His key insight: yield and nutritional density are separate variables. You can maximise yield on imbalanced soils — the food produced is nutritionally hollow. Read ratios, not just levels.

**Neal Kinsey — Albrecht in Practice**
Kinsey refined the Albrecht method through decades of farm-level consulting. His specific contribution: the relationship between minerals matters more than absolute levels. A soil with adequate calcium but excess magnesium behaves calcium-deficient because Mg displaces Ca on exchange sites and tightens soil structure. *Hands-On Agronomy* is the practitioner's manual for this.

**Jeff Lowenfels & Wayne Lewis — The Rhizosphere**
Their framework: 90% of soil biological activity happens in the few millimetres immediately surrounding plant roots. Each plant species has a unique microbial signature in its rhizosphere, selecting for specific bacteria and fungi through root exudate chemistry. This means plant diversity directly drives microbial diversity, and monocultures impoverish biology as surely as pesticides do.

**Christine Jones — Liquid Carbon Pathway**
Jones identified the fastest mechanism for moving photosynthetic carbon into deep soil: root exudates pumped directly into mycorrhizal fungal networks. Plants can allocate 30–40% of their photosynthetic output this way when the fungal network is intact. Her most counterintuitive finding: fungicide use damages soil carbon accumulation more than tillage — it severs the mycorrhizal pipeline that moves carbon underground.

---

## Which tool fits

| You need to... | Tool |
|---|---|
| Interpret a soil test report | test-interpretation |
| Decide what amendments to apply and how much | amendment-planning |
| Choose cover crops for your situation | cover-crop-selection |
| Diagnose and address compaction | compaction-diagnosis |
| Build a long-term fertility programme | fertility-planning |

## Routing Decision

- **Have soil test numbers and don't know what they mean** → test-interpretation
- **Know what's low, unsure what to add or how much** → amendment-planning
- **Planning cover crops, unsure what to choose** → cover-crop-selection
- **Suspect compaction — poor drainage, shallow roots, hard pan** → compaction-diagnosis
- **Want a season-by-season fertility strategy** → fertility-planning
- **Unclear** → test-interpretation first; it reveals what else is needed

---

## Test Interpretation

*Makes sense of a soil test report through the Albrecht/Ingham lens.*

Ask the user to share their soil test numbers. A standard soil test reports mineral chemistry only — it tells you almost nothing about the food web. For a complete picture: run a standard test for minerals, and an Ingham-method biological assessment (active bacteria, active fungi, protozoa, nematode counts) for biology. The mineral test shows what's there; the biological test shows whether the system can cycle it.

Work through numbers in this order:

**1. pH — it controls availability of everything else.**
- Below 6.0: nutrient lockout likely even if levels look adequate. Lime is usually the first move.
- 6.0–7.0: ideal for most crops. Work with what's here.
- Above 7.5: micronutrient availability drops. Sulphur applications may help.

**2. Organic matter (OM).**
- Below 2%: building OM is the priority — it governs biology, water retention, and nutrient cycling.
- 2–5%: working range — maintain and build.
- Above 5%: strong biological base; focus on mineral balance rather than OM addition.

**3. Major nutrients (NPK).**
- Nitrogen: don't read it from a test — too mobile. Use OM trend and crop response as proxies.
- Phosphorus: below 20 ppm (Mehlich-3) warrants attention; above 80 ppm, adding more is wasted money.
- Potassium: below 120 ppm is deficient; watch the K:Mg ratio (ideally 2:1 to 4:1).

**4. Secondary nutrients.**
- Calcium: should be 60–75% of CEC. Below this, soil structure and plant health suffer.
- Magnesium: 10–15% of CEC. High Mg relative to Ca tightens soil and competes with Ca uptake.
- Sulphur: often overlooked; below 10 ppm warrants attention, especially in sandy soils.

**5. Micronutrients.**
- Flag critically low values (boron, zinc, manganese are common culprits).
- Fix pH and OM first — many micronutrient issues resolve without direct application.

**Output:**
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
S: [value ppm] — [status]

MICRONUTRIENTS
[any flagged deficiencies]

PRIORITY ORDER
1. [first action — usually pH or OM]
2. [second action]
3. [third action]

WHAT TO IGNORE FOR NOW
[numbers that don't need action yet — why]
```

---

## Amendment Planning

*Decides what to add, in what form, and how much — without defaulting to the most expensive option.*

Ask: what does the test show is low? What crops are being grown? What's the budget? What's available locally?

**Decision sequence:**

**1. Fix pH before adding nutrients.** Lime raises pH; sulphur lowers it. Incorrectly-pH'd soil wastes every amendment you apply.

**2. Choose amendment form based on speed and system:**
- Fast-acting (soluble): results this season; higher cost; feeds crop, bypasses food web.
- Slow-release (rock minerals, composts): builds over 2–5 years; feeds the system.
- Biological (compost, inoculants): restores the food web; the highest-value investment if biology is degraded.

*Transition note: if the farm has used soluble synthetics for years, biological recovery takes 1–3 seasons. Continue conventional inputs alongside biological amendments during this period — don't remove the crutch before the system can walk without it.*

**3. Common amendments by deficiency:**

| Deficiency | Conventional option | Biological/slow option |
|---|---|---|
| Low pH | Ag lime, dolomite (if Mg also low) | Same — lime is lime |
| High pH | Elemental sulphur | Sulphur + acidifying organic matter |
| Low P | Single superphosphate (fast) | Rock phosphate, bone meal |
| Low K | Muriate of potash (fast) | Sulphate of potash, greensand, kelp |
| Low Ca | Gypsum (no pH change), lime (raises pH) | Gypsum, calcite |
| Low Mg | Epsom salt (fast, foliar) | Dolomite, serpentine rock |
| Low S | Ammonium sulphate | Gypsum |
| Low B | Borax (use carefully — narrow margin) | Borax — no slow alternative |

**4. Rate calculation:** Use soil test recommendation where provided. Without one: start conservatively, retest in 12 months. Overapplication of minerals is harder to fix than underapplication.

**Output:**
```
AMENDMENT PLAN
[Deficiency]: Apply [product] at [rate per acre/ha]
  Timing: [when to apply]
  Form: [granular/liquid/foliar]
  Expected timeline: [when to expect improvement]

TOTAL COST ESTIMATE: [£/$ per acre/ha]

RETEST DATE: [12 months from now]
```

---

## Cover Crop Selection

*Chooses the right cover crop for the situation.*

Ask: what is the primary goal? What season is available? What equipment is available for termination?

**Match goal to species:**

| Goal | Species to consider |
|---|---|
| Fix nitrogen | Clover, vetch, field peas, fava beans, hairy vetch |
| Break compaction | Daikon radish, tillage radish, chicory, deep-rooted ryegrass |
| Build organic matter fast | Winter rye, oats, sorghum-sudan, buckwheat |
| Suppress weeds | Winter rye (allelopathic), buckwheat, dense oats |
| Feed soil biology | Diverse mixes — 5+ species outperforms monocultures |
| Winter soil cover | Winter rye, hairy vetch, crimson clover, field peas |
| Quick summer gap-fill | Buckwheat (6–8 weeks to flower), sorghum-sudan |
| Attract beneficials | Phacelia, buckwheat, crimson clover, mustard, coriander |

**Termination method matters:**
- Roller-crimper: effective only at flowering/seed set; suits no-till; kills without soil disturbance.
- Mowing: faster; may regrow; effective for annual species.
- Incorporation: fastest breakdown; disrupts biology; avoid if reducing tillage is a goal.
- Winter-kill: easiest option — choose frost-sensitive species (buckwheat, sorghum, phacelia) if no equipment.

**Food web note:** Diverse mixes feed diverse microbial communities. Single-species cover crops are better than bare soil; five-species mixes are better than single species. Each plant species feeds a different bacterial and fungal population in its rhizosphere.

**Output:**
```
COVER CROP RECOMMENDATION
Primary goal: [goal]
Season: [season available]

Recommended species: [species or mix]
Seeding rate: [kg/acre or lb/acre]
Sowing window: [dates]
Termination method: [method and timing]

Expected benefits:
- [benefit 1]
- [benefit 2]
```

---

## Compaction Diagnosis

*Identifies compaction, its cause, and how to fix it.*

**Step 1: Field observation.**
Poor drainage after rain? Shallow roots when pulling plants? Crops yellowing in wheel tracks? Puddles forming in low spots? Any of these warrants investigation.

**Step 2: Penetrometer test.**
Insert a penetrometer until it meets resistance — compaction layer is where it stops.
- 15–25cm: likely tillage pan.
- 25–45cm: subsoil compaction.
- Below 45cm: beyond mechanical remedy; biological-only.

**Step 3: Spade test.**
Dig 30cm, examine structure.
- Compacted: horizontal layers, few roots penetrating, grey or blue-grey mottling (anaerobic).
- Healthy: vertical pores and channels, earthworm tunnels, roots following pores freely.

**Solutions by compaction type:**

| Type | Depth | Cause | Remedy | Timeline |
|---|---|---|---|---|
| Surface | 0–15cm | Tillage, foot traffic, rain impact | Permanent beds, mulch, reduce tillage | 1–2 seasons |
| Tillage pan | 15–25cm | Repeated tillage at same depth | One-time subsoiling or deep-rooted covers (daikon) | 1 season mechanical; 2–3 biological |
| Subsoil | 25–45cm | Heavy equipment on wet soil | Deep-rooted cover crops; time — not machines | 3–5 years |
| Structural | All depths | Low OM, biology loss | OM building and biology restoration | 3–7 years |

**Critical rule:** Never subsoil wet soil — it smears rather than fractures. Only work when dry enough that soil fractures along natural planes.

**Output:**
```
COMPACTION DIAGNOSIS
Type: [surface / tillage pan / subsoil / structural]
Depth: [cm]
Likely cause: [cause]

Recommended remedy: [remedy]
Timeline to improvement: [timeline]
Do not: [what to avoid]
```

---

## Fertility Planning

*Builds a season-by-season fertility programme.*

Ask: what crops are in rotation? What does the soil test baseline show? What's the budget? Organic or conventional?

**Framework:**

**1. Set the baseline.** Current test → identify what's deficient, adequate, and excessive.

**2. Map crop nutrient demands:**
- Heavy feeders (brassicas, corn, alliums, squash): high N, moderate P and K.
- Medium feeders (tomatoes, peppers, root veg): moderate NPK.
- Light feeders (herbs, salad leaves, legumes): low N, balanced minerals.
- N-fixers (legumes): credit the following crop with 30–80 kg N/ha depending on stand.

**3. Plan inputs against crop sequence:**
- Apply slow-release amendments (rock minerals, compost) in autumn — they need time to mineralise.
- Apply fast-release inputs close to planting for in-season responsiveness.
- Match compost timing to crop demand, not to calendar convenience.

**4. Build organic matter year on year:**
- Every 1% OM increase releases ~20–30 kg N/ha/year through mineralisation.
- Cover crops + compost builds faster than either alone.
- The food web does the nutrient cycling — feed it rather than replacing it with purchased fertility.

**5. Track and adjust:**
- Retest every 2–3 years.
- Watch crop response as the leading indicator — plants show deficiency before tests do.
- Record inputs applied, timing, and crop performance.

**Output:**
```
FERTILITY PLAN — [Year]

ROTATION: [crop sequence]

AUTUMN INPUTS
[input]: [rate] [timing] [purpose]

SPRING/PRE-PLANT INPUTS
[input]: [rate] [timing] [purpose]

IN-SEASON
[input]: [rate] [timing] [purpose]

COVER CROP WINDOWS
[period]: [species] [nitrogen credit to following crop]

ESTIMATED COST: [£/$ per acre/ha]

INDICATORS TO WATCH
- [crop response to watch for]
- [soil indicator to monitor]

RETEST DUE: [date]
```
```

- [ ] **Step 2: Verify file length and structure**

```bash
wc -l packages/soil/SKILL.md
```
Expected: 200+ lines. Check that all 5 sub-tools are present and all end with an Output section.

- [ ] **Step 3: Run quality checklist**

Open `docs/superpowers/specs/2026-06-01-skills-for-agriculture-plan.md` and run the 10-item quality checklist from this plan against `packages/soil/SKILL.md`. Every item must pass before committing.

- [ ] **Step 4: Commit**

```bash
cd /path/to/skills-for-agriculture
git add packages/soil/SKILL.md docs/superpowers/
git commit -m "feat: write soil skill — Ingham/Albrecht framework, 5 sub-tools"
```

---

## Task 2: Write `regenerative` skill

**File:** `packages/regenerative/SKILL.md` (overwrite existing)

**Spec reference:** Cluster 1 — Philosophy & Systems — `regenerative` entry

Sub-tools to write: `principles`, `assessment`, `entry-points`, `ecosystem-design`, `decision-lens`, `readiness-check`, `transition-sequencing`, `transition-economics`, `transition-traps`

- [ ] **Step 1: Write the YAML frontmatter and opening**

```markdown
---
name: regenerative
description: "Central skill for regenerative agriculture — philosophy, practice, and transition from conventional. Use when the user mentions regenerative ag, regen farming, soil health, carbon farming, biodiversity, holistic management, transitioning from conventional, stopping chemicals, going organic, or asks 'is my farm regenerative', 'how do I farm regeneratively', 'how do I start', or wants to understand the financial and practical journey of changing how they farm."
allowed-tools: [Read]
---

# Regenerative Agriculture

Regenerative farming doesn't just reduce harm — it rebuilds the ecological systems that make growing possible. Every farm decision is also an ecosystem decision: it either degrades or restores the soil biology, water cycles, biodiversity, and carbon flows that underlie long-term farm viability. The goal is not a steady state of "sustainable" — it is an actively improving trajectory. This skill covers the full arc: what regenerative means, the expert thinking it's grounded in, how to get there from where you are, and how to evaluate decisions along the way.

---

## Expert Lineage
```

Write the Expert Lineage section with this content:

```
## Expert Lineage

*The thinkers whose frameworks underpin this skill — and what they specifically discovered that changes how you farm.*

**Gabe Brown — Five Principles from Practice**
Running a cattle and grain operation in North Dakota, Brown was forced off conventional inputs after three consecutive catastrophic crop losses. His five principles aren't theory — they're the pattern he extracted from watching what worked across a decade of necessity-driven experimentation. His specific contribution beyond the principles: the number of cover crop species in a mix matters more than the individual species chosen. A twelve-species blend outperforms any two-species blend not because of the specific plants but because each species feeds a different microbial community.

**Allan Savory — Holistic Planned Grazing**
Savory's core discovery was counterintuitive: brittle grasslands were desertifying because of the *absence* of grazing pressure, not its presence. Grasslands co-evolved with large herds moving under predator pressure — intense impact concentrated in time, followed by long recovery. His Holistic Planned Grazing framework — high density, short duration, full recovery — is the tool. The implication: correctly timed, high-density grazing with full recovery is restorative, and is likely the largest available lever for atmospheric carbon drawdown in agricultural landscapes.

**David Montgomery — The Speed of Recovery**
A geologist at the University of Washington, Montgomery traced the history of agriculture through the archaeology of soil loss. His field research into working regenerative farms produced this finding: soil organic matter can be rebuilt in years rather than decades when management changes are made simultaneously and comprehensively. The conventional assumption that soil regeneration takes generations is wrong. Farms that make incremental changes see slow improvement; farms that shift all inputs at once see rapid biological response.

**Charles Massy — Five Landscape Functions**
Massy's *Call of the Reed Warbler* synthesises decades of Australian regenerative farm case studies into five landscape functions: solar energy conversion, water cycle, mineral/nutrient cycle, biodiversity, and the human/social layer. His most important finding is not ecological but psychological: the primary barrier to farm transition is farmer identity and values, not economics, knowledge, or equipment. Farms driven by genuine values complete the transition; farms driven primarily by economic pressure usually falter in years 2–4.

**Elaine Ingham — Soil Food Web**
Ingham mapped the complete trophic structure of living soil and established the fungi-to-bacteria ratio as the diagnostic lens that explains why regenerative practices work. Annual crops thrive in bacteria-dominated soils; perennials and trees require fungi-dominated soils. Most conventional fertility management actively suppresses fungi while feeding bacteria. Her practical implication: before adding any input, ask whether it feeds or kills the biology.

**Christine Jones — Liquid Carbon Pathway**
Jones' research established the primary mechanism by which regenerative management sequesters carbon: root exudates pumped directly into mycorrhizal fungal networks. Plants can allocate 30–40% of their photosynthetic output this way when the fungal network is intact. Her most counterintuitive finding: fungicide use is more damaging to soil carbon accumulation than tillage — it severs the mycorrhizal pipeline that moves carbon underground.
```

Then write the routing table and all nine sub-tools following the SKILL.md template. Sub-tool content should be drawn directly from the spec entry plus the quality criteria:

- `principles` — the five principles (minimise disturbance, living roots, soil cover, diversity, animal integration), each explained with the food web mechanism behind it
- `assessment` — 1–5 score across each principle; what each score looks like in practice; output is a total score and priority gaps
- `entry-points` — decision tree: what's the user's biggest leverage point given their current system (crops-only, livestock, mixed, degraded land, new to farming)
- `ecosystem-design` — biodiversity zones, wildlife corridors, hedgerows, habitat strips; function-first design
- `decision-lens` — a filter for any farm decision: does this move me toward or away from each of the five principles
- `readiness-check` — honest assessment of whether the farmer is ready: financial cushion, knowledge base, mindset, support network
- `transition-sequencing` — order of changes to minimise disruption: reduce disturbance first, then introduce cover crops, then reduce synthetics, then integrate animals, then build biodiversity
- `transition-economics` — the financial profile of transition; years 1–2 (neutral/slight improvement), years 2–4 (hardest), years 4+ (improving); strategies for bridging
- `transition-traps` — the five most common failure modes: changing too much too fast, removing synthetics before biology recovers, no financial buffer for year 2–4, farming to certify not to regenerate, doing it alone

Every sub-tool must end with an **Output** block.

- [ ] **Step 2: Verify structure**

```bash
wc -l packages/regenerative/SKILL.md
grep "## " packages/regenerative/SKILL.md
```
Expected: 300+ lines. Nine sub-tool headings present.

- [ ] **Step 3: Run quality checklist**

Pay particular attention to the context-sensitive delivery criterion for this skill — a conventional farmer asking "should I go regenerative" should get a financially honest answer, not an ecological lecture.

- [ ] **Step 4: Commit**

```bash
git add packages/regenerative/SKILL.md
git commit -m "feat: write regenerative skill — 9 sub-tools, full transition pathway"
```

---

## Task 3: Write `pests` skill

**File:** `packages/pests/SKILL.md` (overwrite stub)

**Spec reference:** Cluster 3 — Living Systems — `pests` entry

Sub-tools to write: `identification`, `threshold-assessment`, `cultural-controls`, `biological-controls`, `organic-interventions`, `conventional-options`

- [ ] **Step 1: Write the YAML frontmatter and opening**

```markdown
---
name: pests
description: "Pest and disease management. Use when the user describes a pest, disease, or crop damage problem, or asks how to control something eating or damaging their crops. Also use for: 'what's wrong with my plants', 'holes in leaves', 'wilting', 'yellow leaves', 'white powder', 'black spots', 'insects on my crops', or any request to identify or control a farm pest or disease."
allowed-tools: [Read]
---

# Pests & Disease

Most pest and disease problems are symptoms of plant stress, and most plant stress is a symptom of food web dysfunction. Before reaching for any spray — biological or chemical — the most useful question is: why is this plant stressed enough to attract this pest? That said, when a crop is under immediate attack, the immediate answer comes first.

---

## Expert Lineage
```

Expert Lineage thinkers: Mary Louise Flint & Steve Dreistadt (IPM/natural enemies), Eliot Coleman (prevention through plant health), Jeff Gillman (evidence-based assessment of organic vs conventional), Elaine Ingham (biology as primary pest prevention).

Write the IPM ladder framework as the core structure of this skill. The ladder runs from least to most intervention:

```
Level 1: Do nothing (is it actually a problem?)
Level 2: Cultural controls (rotation, timing, variety, physical barriers)
Level 3: Biological controls (beneficials, predatory insects, Bt, Trichoderma)
Level 4: Approved organic interventions (neem, copper, sulphur, pyrethrin)
Level 5: Conventional chemistry (targeted, with damage acknowledged)
```

**Critical for context-sensitive delivery:** A farmer saying "there are aphids all over my brassicas and I'm harvesting tomorrow" gets Level 4/5 immediately, with a one-line note on prevention for next season. The IPM ladder is a planning tool, not a gate. The skill delivers the answer at the right level for the urgency.

Sub-tools:
- `identification` — structured identification protocol: what does the damage look like, where is it, what else is in the field; key symptom tables by crop type
- `threshold-assessment` — is the level of damage actually worth treating; economic threshold concept; the "do nothing" default
- `cultural-controls` — rotation, variety resistance, timing, companion planting, physical barriers, sanitation; concrete options by pest category
- `biological-controls` — beneficial insect habitat, predatory mite releases, nematode applications, Bt for caterpillars, Trichoderma for soil pathogens; what to buy, when to apply, what to expect
- `organic-interventions` — neem oil, copper, sulphur, pyrethrin, spinosad; when each is appropriate, limitations, and biology impact
- `conventional-options` — active ingredients, application windows, PHIs, RE-entry; note on biology impact; alternative at same intervention level

Every sub-tool ends with Output block. The `conventional-options` sub-tool must include: "Sustainable alternative at this level: [specific alternative]" as a standard output field — brief, not preachy.

- [ ] **Step 2: Verify structure**

```bash
wc -l packages/pests/SKILL.md
grep "^## " packages/pests/SKILL.md
```
Expected: 250+ lines. Six sub-tool headings plus Expert Lineage and routing table.

- [ ] **Step 3: Run quality checklist**

This skill has the sharpest conventional/sustainable tension. Check specifically: does a farmer who just wants to know what spray to use get a clear answer without being lectured? Does the sustainable alternative appear as a note, not a condition?

- [ ] **Step 4: Commit**

```bash
git add packages/pests/SKILL.md
git commit -m "feat: write pests skill — IPM ladder framework, 6 sub-tools"
```

---

## Task 4: Write `seasons` skill

**File:** `packages/seasons/SKILL.md` (overwrite stub)

**Spec reference:** Cluster 7 — Farm Operations — `seasons` entry

Sub-tools to write: `crop-calendar`, `rotation-planning`, `livestock-calendar`, `succession-planning`, `annual-review`

- [ ] **Step 1: Write the YAML frontmatter and opening**

```markdown
---
name: seasons
description: "Seasonal and annual farm planning. Use when the user asks about crop rotation, succession planting, what to do next, planning the year, when to sow or plant, planning a market garden calendar, livestock seasonal tasks, or says 'what should I be doing now', 'how do I plan my year', or 'I need a growing calendar'."
allowed-tools: [Read]
---

# Seasons & Planning

A farm runs on rhythm. The planning tool that removes the most stress and prevents the most mistakes is a calendar — not a sophisticated one, but one that actually covers the whole year and gets used. This skill builds that calendar and keeps it honest: living roots in the ground as much of the year as possible, gaps covered, and the soil never left bare.

---

## Expert Lineage
```

Expert Lineage thinkers: Jean-Martin Fortier (succession planting scheduling, market garden calendar), Eliot Coleman (four-season production, cold-climate calendar), Joel Salatin (diversified farm operations calendar).

Sub-tools:
- `crop-calendar` — monthly template (Northern Hemisphere temperate climate as default, with prompt to adjust for user's zone): what to sow, plant, harvest, and prepare each month; output is a filled 12-month table
- `rotation-planning` — the principles of rotation (break pest cycles, balance fertility, manage soil biology); a worked example for a 4-bed rotation; output is a rotation map
- `livestock-calendar` — key seasonal livestock tasks by species (cattle, sheep, pigs, poultry); breeding, vaccination, parasite management, grazing calendar; output is a 12-month tasks list
- `succession-planning` — calculating how many plantings at what intervals to hit a continuous harvest target; worked example for lettuce and salad; output is a succession table
- `annual-review` — what to record at end of season; yield per bed, sellout rates at market, soil test dates, what to change; output is a review template

Soil health integration for `crop-calendar` and `rotation-planning`: every gap in the calendar where soil would be bare should be flagged and a cover crop suggested. Living roots year-round is the default target; deviations are acknowledged but explained.

Every sub-tool ends with Output block — the `crop-calendar` output should be an actual filled table with example crops.

- [ ] **Step 2: Verify structure**

```bash
wc -l packages/seasons/SKILL.md
grep "^## " packages/seasons/SKILL.md
```
Expected: 200+ lines. Five sub-tool headings present.

- [ ] **Step 3: Run quality checklist**

Check specifically: does `crop-calendar` highlight bare soil periods and prompt cover crop solutions? Is the conventional farmer who just wants to know what to do in May served immediately?

- [ ] **Step 4: Commit**

```bash
git add packages/seasons/SKILL.md
git commit -m "feat: write seasons skill — crop calendar, rotation, succession planning"
```

---

## Task 5: Commit spec and plan

- [ ] **Step 1: Commit documentation**

```bash
git add docs/
git commit -m "docs: add skill writing spec and Phase 1 implementation plan"
```

---

## Phases 2–5: Plan Files

Each remaining cluster gets its own plan file using the same structure as this one. The template, quality checklist, and SKILL.md structure defined above apply to all of them. Create the following plan files as each phase begins:

| Plan file | Skills covered |
|---|---|
| `2026-06-01-phase-2-high-traffic-skills.md` | `vegetables`, `livestock`, `water`, `composting`, `finance` |
| `2026-06-01-phase-3-philosophy-skills.md` | `permaculture`, `syntropic`, `korean-natural-farming`, `biodynamic`, `indigenous` |
| `2026-06-01-phase-4-remaining-practical.md` | All Cluster 4–7 skills not in Phase 1 or 2 |
| `2026-06-01-phase-5-business-community.md` | All Cluster 8–9 skills |

Each plan is self-contained. Write Phase N plan before beginning Phase N execution. Spec content for each skill is in `docs/superpowers/specs/2026-06-01-skills-for-agriculture-plan.md`.

---

## Self-Review Notes

- All 4 Phase 1 tasks include complete file content or complete structural guidance (no TBDs)
- Quality checklist is explicit and runnable after each task
- Commit message pattern is consistent
- Phase 2–5 plan files are templated but not written — this is intentional; they should be written just before execution of each phase so they can incorporate lessons from earlier phases
- The `transitioning` stub package requires no changes — it already correctly routes to `/regenerative`
