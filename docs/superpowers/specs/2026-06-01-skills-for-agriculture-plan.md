# Skills-for-Agriculture: Skill Writing Plan

**Date:** 2026-06-01  
**Purpose:** Define quality criteria and scope for all skills in the skills-for-agriculture package, grounded in Tavily research on leading frameworks and thinkers. This is a working plan for discussion and execution.

**Package count:** 47 packages on disk. 46 are substantive skills documented in this plan. 1 (`transitioning`) is a routing stub that redirects to `regenerative` and requires no independent content — it already correctly routes users to the transition sub-tools within `/regenerative`.

---

## Quality Criteria

Every skill in this library must meet all six criteria:

**1. Goal-oriented**
The skill exists to help the user achieve a specific agricultural goal — not to educate them about a topic. Every skill opens by identifying what the user is trying to do, then provides a structured way to do it. If a skill cannot be framed as "help the user achieve X", it needs to be redefined.

**2. Sustainability-biased, not exclusive**
Methodologies default to sustainable, regenerative, and ecologically sound practice. Conventional approaches are fully documented and not judged. Where a conventional path is the right answer for the user's situation, the skill gives it clearly. A more sustainable alternative is always noted — briefly, at the end — not as a lecture but as an available option.

**3. Nature-aligned reasoning**
The reasoning framework embedded in every skill is: natural systems are more capable than they appear, and working with them is almost always more effective long-term than working against them. This shapes the logic of recommendations without requiring the user to share the value.

**4. Soil health as foundation — Elaine Ingham's framework**
Ingham's soil food web is the biological lens underneath every skill, not just the soil skill. The fungi-to-bacteria ratio, the role of root exudates, the damage done by soluble synthetics and fungicides, and the principle that a healthy food web produces nutrients the crop needs — these ideas surface wherever they're relevant. Before recommending any input (fertiliser, pesticide, amendment), the skill asks whether it feeds or kills the biology.

**5. Transition-aware**
Every skill understands that users exist on a spectrum from fully conventional to fully regenerative. The skill meets them where they are. It does not assume the user is willing or able to change their whole system. It offers a transition pathway — a next step, not a destination — for those who want to move in a better direction without disrupting their current operation.

**6. Context-sensitive delivery**
The skill reads the user's urgency and intent first. A conventional farmer who needs a fast answer gets the answer first, then a brief note on alternatives. A farmer in crisis (crop failure, disease outbreak, animal emergency) gets immediate practical guidance — the ecological framing waits. Sustainability suggestions are offered, not imposed. The skill earns the right to advise on practice change by being genuinely useful on the immediate goal first.

---

## Skill Entry Format

Each skill in this plan is documented with:

- **User goal** — what the user is trying to achieve
- **Scope** — what this skill covers; what it explicitly excludes
- **Framework type** — methodology / decision tree / assessment / Q&A reasoning / process guide
- **Sub-tools** — the internal sections or tools the skill should contain
- **Key thinkers** — the authorities whose frameworks the skill draws on
- **Soil health angle** — how Ingham's soil food web connects to this domain
- **Transition pathway** — what conventional practice looks like here; the direction of travel toward better practice
- **Delivery note** — any specific guidance on how to handle the conventional/sustainable tension in this domain

---

## Cluster 1: Philosophy & Systems

*The thinking frameworks that sit underneath all farm decisions. These skills are invoked when the user wants to understand a whole-farm approach, not solve a specific problem. They provide the lens through which other skills should operate.*

---

### `regenerative`

**User goal:** Understand what regenerative agriculture means in practice and how to apply it to their farm.

**Scope:** Regenerative principles (the five — disturbance, living roots, soil cover, diversity, animal integration), farm assessment, entry points, transition planning, economics of transition, common traps. Excludes certification pathways (→ `certification`), specific enterprise decisions (→ domain skills).

**Framework type:** Assessment + decision methodology. The skill evaluates where the user is and routes to appropriate sub-tools.

**Sub-tools:**
- `principles` — what the five principles mean in practice with real farm examples
- `assessment` — score the current farm across each principle
- `entry-points` — where to start given their current system; highest-leverage first moves
- `ecosystem-design` — biodiversity, habitat, and function planning
- `decision-lens` — run a specific farm decision through a regenerative filter
- `readiness-check` — is the farmer ready to commit to transition
- `transition-sequencing` — order of changes to minimise financial and operational risk
- `transition-economics` — the financial journey; managing the dip in years 2–4
- `transition-traps` — the most common mistakes and how to avoid them

**Key thinkers:**
- **Gabe Brown** — five principles from practice (North Dakota cattle/grain operation). Specific insight: number of cover crop species matters more than species identity
- **Allan Savory / Holistic Management** — Holistic Planned Grazing as the primary land restoration tool in brittle grasslands; predator-prey dynamics as the model for grazing
- **David Montgomery** — archaeological and scientific case for rapid soil carbon rebuild; *Growing a Revolution* documents farms rebuilding OM in years not decades
- **Charles Massy** — five landscape functions framework (*Call of the Reed Warbler*); primary barrier to transition is farmer identity, not economics
- **Elaine Ingham** — soil food web as the biological underpinning of all regenerative practice
- **Christine Jones** — liquid carbon pathway; mycorrhizal networks as the carbon sequestration mechanism; fungicide use as the most destructive single input

**Soil health angle:** Ingham's framework is the biological engine of regenerative agriculture. The five principles are the management conditions under which the food web thrives. Every principle can be explained in food web terms: disturbance kills fungi; bare soil stops root exudates; monoculture impoverishes microbial diversity.

**Transition pathway:** Conventional → reduce disturbance first (least financially risky) → introduce cover crops → reduce synthetics progressively as biology recovers → integrate animals if system allows → build biodiversity infrastructure.

**Delivery note:** Users who ask "is this worth it financially" deserve a straight answer about the economics before the ecology. Transition economics are real — years 2–4 are hardest. Acknowledge this directly.

---

### `permaculture`

**User goal:** Apply permaculture design principles to a farm, garden, or land decision.

**Scope:** Zone and sector analysis, guild and companion planting design, ethics (earth care, people care, fair share), pattern language, design methodology. Excludes enterprise planning (→ `finance`), specific crop decisions (→ plant skills).

**Framework type:** Design methodology. Permaculture is fundamentally a design system — the skill structures a design process.

**Sub-tools:**
- `zone-design` — map zones 0–5 based on frequency of use and energy efficiency
- `sector-analysis` — sun, wind, water, fire, pest, and noise sectors mapped onto the site
- `guild-design` — design functional plant communities (nitrogen-fixers, accumulators, ground covers, climbers, canopy)
- `pattern-language` — applying natural patterns (edge, spiral, keyhole, mandala) to layout decisions
- `ethics-check` — applying the three permaculture ethics as a decision filter

**Key thinkers:**
- **Bill Mollison** — co-founder, *Permaculture: A Designers' Manual* — the canonical reference
- **David Holmgren** — co-founder, *Permaculture: Principles and Pathways Beyond Sustainability* — refined the principles into 12 design principles
- **Toby Hemenway** — *Gaia's Garden* — most accessible application to small-scale farms and homesteads
- **Masanobu Fukuoka** — *One-Straw Revolution* — do-nothing farming philosophy; natural farming as spiritual as well as practical

**Soil health angle:** Permaculture design maximises conditions for soil biology by prioritising permanent ground cover, perennial root systems, and stacked diversity — all of which feed Ingham's food web. Zone design reduces soil compaction by routing traffic away from productive areas.

**Transition pathway:** Conventional annual monoculture → begin with zone mapping and sector analysis (observation only, no cost) → introduce edges and polyculture into one zone → build guild plantings incrementally → develop permanent infrastructure (swales, food forest elements) as capital allows.

**Delivery note:** Permaculture can feel philosophical or even mystical to pragmatic farmers. Lead with the practical design tools (zones, sectors, guilds) — they're immediately useful regardless of whether the user buys into the broader worldview.

---

### `biodynamic`

**User goal:** Apply biodynamic principles and practices to their farm — preparations, calendar, and whole-farm organism thinking.

**Scope:** The nine preparations (500–508), the biodynamic calendar (root/flower/fruit/leaf days), farm organism concept, Demeter certification pathway overview. Excludes soil testing and amendment (→ `soil`), certification detail (→ `certification`).

**Framework type:** Practice methodology + calendar-based decision framework.

**Sub-tools:**
- `preparations` — what each preparation is, how to make it, when and how to apply it
- `calendar` — how to read and use the biodynamic calendar for sowing, planting, harvesting, processing
- `farm-organism` — designing the farm as a self-contained organism: integration of livestock, compost, crops, and habitat
- `transition` — moving from organic or conventional to biodynamic; sequencing preparations and practices

**Key thinkers:**
- **Rudolf Steiner** — *Agriculture Course* (1924), eight lectures at Koberwitz — the originating framework
- **Maria and Matthias Thun** — 40+ years of calendar research; annual *Biodynamic Sowing and Planting Calendar*
- **Ehrenfried Pfeiffer** — Steiner's student, brought biodynamics into practical farm application
- **Hugh Lovel** — *A Biodynamic Farm* — modern practical integration

**Soil health angle:** Preparations 500 (horn manure) and 501 (horn silica) work at the soil biology level — 500 stimulates microbial and fungal activity, and several preparations feed the soil food web in ways Ingham's framework can explain in biological terms. The farm-organism concept aligns with the closed-loop nutrient cycling Ingham advocates.

**Transition pathway:** Conventional → organic → introduce compost preparations → begin calendar observation and harvesting by calendar → introduce field sprays → build toward full preparations suite and farm organism design.

**Delivery note:** Some farmers will be skeptical of the cosmic/spiritual dimensions of biodynamics. The skill should acknowledge that the scientific evidence for some practices (lunar calendar effects on germination) is mixed while being clear that the soil biology practices are well-grounded. Let farmers find their own relationship with the more esoteric elements.

---

### `syntropic`

**User goal:** Design and manage a farm system using Ernst Götsch's syntropic agroforestry succession principles.

**Scope:** Succession-based design, stratification, placenta/secondary/climax species roles, pruning and chopping as disturbance tools, accelerating natural succession. Excludes broader agroforestry enterprise decisions (→ `agroforestry`), food forest design from a permaculture angle (→ `permaculture`).

**Framework type:** Design + management methodology — syntropic is an active management system, not a set-and-forget approach.

**Sub-tools:**
- `succession-design` — map the four succession stages and assign species to each
- `stratification` — design vertical layers by light requirement and temporal role
- `disturbance-management` — pruning, chopping, timing cuts to advance succession
- `placenta-species` — selecting and using pioneer species to build soil and open canopy
- `site-reading` — reading a degraded site and designing the succession timeline

**Key thinkers:**
- **Ernst Götsch** — Swiss-Brazilian farmer and researcher; developed syntropic agroforestry at Fazenda Olhos D'Água in Bahia; compressed 120 years of natural succession into 20 years
- **The five core principles:** stratification, succession, density, diversity, disturbance
- **Seven operational principles:** maximise photosynthesis, natural succession and stratification, covered soil, selective weeding/pruning, concentrating energy, plant ecophysiology, synchronised plantings

**Soil health angle:** Syntropic systems build soil biology rapidly through the continuous root exudate flow from diverse, layered, perennial systems. The constant biomass return from pruning and chopping feeds the decomposer food web — Ingham's fungi in particular. Dense diverse systems are among the fastest ways to restore fungal-dominated soil biology.

**Transition pathway:** Degraded or bare land → pioneer placenta planting (fast-growing species, vegetables, nitrogen-fixers) → establish secondary species as pioneers mature → selective removal and pruning to advance succession → introduce climax species into developed understory. System improves annually rather than requiring inputs to maintain.

**Delivery note:** Syntropic requires commitment to active management and a multi-year horizon. Farmers looking for quick returns need to understand the timeline honestly. The productivity in early succession stages (vegetables, legumes) can deliver income while the longer-term system matures.

---

### `korean-natural-farming`

**User goal:** Make and apply Korean Natural Farming (KNF) inputs to reduce external input costs and build biological fertility.

**Scope:** The five core KNF preparations (IMO 1–4, FPJ, OHN, FFJ, WCA, LAB), when and how to apply each, sourcing local indigenous microorganisms. Excludes broader farm system design (→ `regenerative` or `permaculture`).

**Framework type:** Process methodology — KNF is a precise preparation and application protocol.

**Sub-tools:**
- `imo-cultivation` — collecting, cultivating, and applying Indigenous Microorganisms (IMO 1–4)
- `fermented-inputs` — Fermented Plant Juice (FPJ), Oriental Herbal Nutrients (OHN), Fish Fertiliser (FF), Water-Soluble Calcium (WCA)
- `lactic-acid-bacteria` — LAB serum: making and applying
- `application-timing` — matching inputs to crop growth stages (vegetative, reproductive, ripening)
- `cost-analysis` — calculating input cost savings vs. conventional approach

**Key thinkers:**
- **Cho Han-kyu** — founder of KNF; developed the system in 1960s South Korea as an alternative to chemical agriculture; trained over 18,000 practitioners globally through the Global Village Natural Farming Research Institute
- **Chris Trump** — primary Western practitioner and trainer; adapted KNF for temperate climates

**Soil health angle:** KNF is fundamentally a soil food web intervention — IMO cultivation is the direct application of Ingham's principle that the microbial community does the work. LAB serum and fermented inputs feed bacterial populations; the system builds toward a diverse, active food web without the biological collapse caused by soluble synthetics.

**Transition pathway:** High-input conventional → replace one input category at a time starting with LAB serum (lowest cost, easiest to make) → add FPJ production → build IMO cultivation capacity → progressively reduce purchased inputs as homemade biological fertility replaces them.

**Delivery note:** KNF's appeal to conventional farmers is the cost reduction argument. Lead with this — "make fertility for almost nothing using what's already on your land" — before the ecological framing. The preparations work whether or not the farmer is committed to the philosophy.

---

### `indigenous`

**User goal:** Draw on traditional ecological knowledge (TEK) and indigenous land relationships to inform farm and land management decisions.

**Scope:** Traditional ecological knowledge principles, reciprocity and honorable harvest ethics, polyculture and companion planting traditions (Three Sisters and beyond), fire and land management practices, relationship-based land stewardship. Excludes cultural appropriation of sacred practices — the skill advises on principles and frameworks, not on enacting specific ceremonial practices.

**Framework type:** Principles-based reasoning framework and Q&A.

**Sub-tools:**
- `tek-principles` — the foundational principles of traditional ecological knowledge as a decision framework
- `honorable-harvest` — applying reciprocity ethics to inputs, outputs, and land management
- `polyculture-traditions` — indigenous companion planting and polyculture systems (Three Sisters, forest gardens)
- `fire-and-land` — prescribed burning and land management traditions; cultural burning principles
- `relationship-approach` — shifting from extractive to relational land stewardship

**Key thinkers:**
- **Robin Wall Kimmerer** — Potawatomi botanist; *Braiding Sweetgrass* — the foundational text for integrating TEK with western science; reciprocity, animacy, the honorable harvest
- **M. Kat Anderson** — *Tending the Wild* — California Native American knowledge of land stewardship and management
- **Gary Paul Nabhan** — ethnoecologist; seed saving, traditional food systems, arid-land agriculture
- **Vandana Shiva** — seed sovereignty, traditional agricultural diversity as ecological resilience

**Soil health angle:** Indigenous agricultural systems — polycultures, no-till, organic matter return, no external synthetic inputs — map directly onto Ingham's ideal conditions for a healthy food web. The Honorable Harvest principle (take only what you need, give back what you can) is a cultural encoding of the soil food web logic: the system only sustains itself if the biology is continuously fed and never depleted.

**Transition pathway:** Extractive/conventional → begin observation and land reading (no cost, no change required) → introduce polyculture into one area → reduce bare soil → adopt an amendment practice that returns rather than extracts → build toward reciprocal land relationships over time.

**Delivery note:** This skill requires cultural sensitivity. The goal is to make TEK principles available as a reasoning framework without reducing them to technique. Acknowledge the source and context of these practices, and note where specific practices require guidance from knowledge-keepers of the relevant tradition.

---

## Cluster 2: Land & Ecology

*The physical and ecological substrate of the farm — the conditions within which everything else happens. These skills are invoked when the user needs to understand, assess, or improve the land itself.*

---

### `land-reading`

**User goal:** Assess an unfamiliar piece of land — or re-read land they already farm — to understand its potential, constraints, history, and ecological patterns.

**Scope:** Field observation methodology, reading landform and drainage patterns, soil profile assessment (without lab tests), vegetation as ecological indicator, historical land use assessment. Excludes soil lab testing and interpretation (→ `soil`), water system design (→ `water`), earthworks design (→ `earthworks`).

**Framework type:** Observation and assessment methodology — structured field reading.

**Sub-tools:**
- `landform-reading` — contour, slope, aspect, drainage patterns; what the shape of the land tells you
- `vegetation-indicators` — reading plant communities as indicators of soil type, drainage, compaction, and history
- `soil-profile` — spade test, penetrometer, earthworm count, slake test, smell and texture assessment
- `water-patterns` — reading where water flows, ponds, infiltrates, and drains; identifying problems and opportunities
- `history-reading` — land use history, aerial photography, local knowledge as inputs to assessment
- `potential-mapping` — translating observations into a map of enterprise potential and constraints

**Key thinkers:**
- **P.A. Yeomans** — *The Keyline Plan* — reading landscape for water patterns; keyline design as a systematic land-reading methodology
- **Masanobu Fukuoka** — observation as the primary tool; reading the land before acting on it
- **Jerome Osentowski** — *The Forest Garden Farm* — reading microclimate and site potential for food system design
- **Charles Massy** — landscape function framework as the analytical lens for land reading

**Soil health angle:** Vegetation indicators directly reveal food web health — certain weed species indicate bacteria-dominated, disturbed soils (annual weeds, dock, thistle); others indicate recovering or fungal-dominated soils (perennial forbs, clovers). Earthworm counts are a direct proxy for biological activity. A land reading always includes a food web status assessment.

**Transition pathway:** Visual walk-over observation (free, no tools needed) → basic soil assessment (spade, penetrometer, jar test) → vegetation mapping → water pattern mapping → historical research → integrate into potential map.

**Delivery note:** Farmers who have worked their land for years often resist being told to "read it differently." Frame this as validation and refinement of what they already know, not as replacing their expertise.

---

### `soil`

**User goal:** Understand what their soil needs and make good decisions about fertility, biology, structure, and amendments.

**Scope:** Soil test interpretation (mineral chemistry), soil biology assessment, amendment planning, cover crop selection, compaction diagnosis, long-term fertility planning. Excludes water management (→ `water`), earthworks (→ `earthworks`).

**Framework type:** Diagnostic + decision methodology — interprets data and routes to appropriate action.

**Sub-tools:**
- `test-interpretation` — reading soil test numbers through the Albrecht/Ingham lens: mineral ratios, OM, pH
- `amendment-planning` — what to apply, in what form, at what rate
- `cover-crop-selection` — matching cover crops to soil goals (N-fixation, compaction-busting, OM-building, weed suppression)
- `compaction-diagnosis` — identifying type, depth, cause, and remedy
- `fertility-planning` — season-by-season input schedule; building OM over time

**Key thinkers:**
- **Elaine Ingham** — soil food web; fungi-to-bacteria ratio; damage from soluble synthetics and fungicides; compost tea and biological inoculants
- **William Albrecht** — cation exchange capacity, mineral balance ratios (Ca 60–75% CEC, Mg 10–15%, K 2–5%); nutritional density vs yield
- **Neal Kinsey** — Albrecht method in practice; *Hands-On Agronomy*; mineral ratio relationships
- **Jeff Lowenfels & Wayne Lewis** — *Teaming with Microbes*; rhizosphere biology; plant diversity drives microbial diversity
- **Christine Jones** — liquid carbon pathway; mycorrhizal networks; OM building through living roots

**Soil health angle:** This is the Ingham skill par excellence. Every recommendation passes through the food web lens: does this input feed or kill biology? Before any amendment, ask what the food web status is. Mineral chemistry without biological context produces correct-looking numbers on a broken system.

**Transition pathway:** Conventional soluble inputs → test both chemistry and biology → address pH and OM first → introduce biological inoculants alongside (not replacing) existing inputs → progressively reduce soluble inputs as food web recovers → cover crops replace or reduce purchased fertility.

---

### `water`

**User goal:** Manage water on their farm — irrigation, drought resilience, drainage, catchment, and water quality.

**Scope:** Irrigation system selection and management, drought planning, drainage problems, water harvesting and storage, water quality. Excludes earthworks design (→ `earthworks`), catchment structures (→ `earthworks`).

**Framework type:** Decision methodology + Q&A for specific water problems.

**Sub-tools:**
- `irrigation-selection` — choosing between drip, flood, overhead, subsurface; matching system to crop and soil
- `irrigation-scheduling` — when and how much to irrigate; soil moisture indicators
- `drought-planning` — building resilience before drought arrives; water-holding capacity through OM
- `drainage` — diagnosing drainage problems; tile drainage, surface drainage, biological drainage (deep roots)
- `water-harvesting` — simple collection and storage options; integrating with landscape
- `water-quality` — testing, common contaminants, treatment options

**Key thinkers:**
- **P.A. Yeomans** — *The Keyline Plan*; the most systematic framework for reading landscape water patterns and designing water-efficient farm systems
- **Brad Lancaster** — *Rainwater Harvesting for Drylands and Beyond* — water harvesting design for arid and semi-arid conditions
- **Gary Zimmer** — *The Biological Farmer* — soil OM as drought insurance; the relationship between biology and water retention
- **Judith Schwartz** — *Water in Plain Sight* — water cycle restoration through land management

**Soil health angle:** Healthy soil food webs dramatically improve water management: aggregate structure from fungal hyphae and bacterial biofilms increases infiltration rate; OM increases water-holding capacity by up to 20x its weight in water. Before adding irrigation infrastructure, ask whether the soil biology is working — in many cases, OM improvement solves irrigation problems more cheaply than hardware.

**Transition pathway:** Flood irrigation or overhead → improve soil OM to reduce irrigation demand → shift to drip where possible → integrate water harvesting → reduce input water cost year on year.

---

### `earthworks`

**User goal:** Design and build earthworks — swales, berms, ponds, and contour-based water management infrastructure.

**Scope:** Swale and berm design on contour, pond siting and sizing, keyline design, access tracks on contour. Excludes drainage tile and subsurface drainage (→ `water`), broader farm design (→ `permaculture`).

**Framework type:** Design + process methodology.

**Sub-tools:**
- `contour-reading` — finding the keyline and contours using an A-frame or laser level
- `swale-design` — sizing, spacing, and overflow design for on-contour swales
- `pond-siting` — selecting, sizing, and designing farm ponds for stock water, irrigation, or fire management
- `keyline-design` — Yeomans' keyline pattern for water distribution across a farm
- `access-design` — road and track placement that manages water rather than channelling it

**Key thinkers:**
- **P.A. Yeomans** — keyline design; the definitive methodology for earthworks-based water management on farms
- **Bill Mollison** — swale design within permaculture; landform reading and earthworks integration
- **Darren Doherty** — practical Yeomans keyline application; founder of Regrarians
- **Mark Shepard** — *Restoration Agriculture*; earthworks at farm scale integrated with enterprise

**Soil health angle:** Well-designed earthworks transform water from a runoff/erosion event into an infiltration event — the difference between water feeding soil biology and water stripping it. Swales and keyline ripping move water laterally through the soil, aerating and hydrating the microbial zone. Compaction from poorly sited tracks destroys the fungal networks Ingham documents.

**Transition pathway:** Identify erosion and runoff problems first (low-cost observation) → install on-contour earthworks to capture runoff → build soil OM alongside to improve infiltration → introduce ponds or storage as second phase.

---

### `carbon`

**User goal:** Understand and manage carbon sequestration on their farm — measuring it, building it, and potentially monetising it.

**Scope:** Soil carbon sequestration mechanisms, management practices that build carbon, carbon measurement approaches, voluntary carbon markets and credits. Excludes broader business planning (→ `finance`).

**Framework type:** Q&A reasoning + methodology for carbon-building decisions.

**Sub-tools:**
- `sequestration-mechanisms` — how carbon gets into soil and stays there; the liquid carbon pathway; organic matter composition
- `building-carbon` — management practices ranked by carbon impact: perennial cover, cover crops, reduced tillage, compost additions
- `measuring-carbon` — Brix testing, lab OM measurement, NIRS field measurement; what's practical at farm scale
- `carbon-markets` — voluntary carbon market overview; soil carbon credit schemes; eligibility, additionality, monitoring requirements

**Key thinkers:**
- **Christine Jones** — liquid carbon pathway; living roots as the primary mechanism; OM building in years not decades when management changes comprehensively
- **David Lal** — soil carbon sequestration science; the global potential of agricultural soils
- **David Montgomery** — *Growing a Revolution*; documented farm case studies of rapid OM recovery
- **Gabe Brown** — farm-level carbon building through regenerative practice

**Soil health angle:** Carbon and biology are inseparable — soil organic matter is largely microbial biomass and residues. Ingham's food web is the biological mechanism by which photosynthetic carbon is stabilised in soil. You cannot build carbon without building biology. Any carbon-building plan is a food web plan.

**Transition pathway:** Conventional tillage with bare soil → introduce cover crops (fast, low-cost first step) → reduce tillage → add compost → introduce perennials into rotation → begin carbon measurement.

---

### `climate-adaptation`

**User goal:** Understand how their farm is vulnerable to climate change and build resilience into their systems.

**Scope:** Climate risk assessment for the specific farm (flood, drought, heat, frost timing shifts, extreme weather), adaptation strategies, building biological resilience. Excludes carbon markets (→ `carbon`), water infrastructure (→ `water`, `earthworks`).

**Framework type:** Assessment + decision methodology.

**Sub-tools:**
- `risk-assessment` — mapping the farm's specific climate vulnerabilities by enterprise type
- `water-resilience` — drought-proofing and flood management strategies
- `diversity-as-resilience` — enterprise and species diversity as hedge against climate variability
- `infrastructure-adaptation` — polytunnels, windbreaks, shade structures for climate buffering
- `variety-selection` — climate-adapted varieties and species for changing conditions

**Key thinkers:**
- **Charles Massy** — five landscape functions as the framework for climate resilience; farms that function ecologically are more climate-resilient than farms that don't
- **Wes Jackson** — *Consulting the Genius of the Place*; place-adapted perennial polycultures as the most climate-resilient agricultural model
- **Gary Paul Nabhan** — arid-land adaptation; food sovereignty through locally adapted varieties
- **IPCC WGII** — agricultural adaptation chapter; documented climate impacts on agriculture by region

**Soil health angle:** Healthy biology dramatically improves climate resilience. High-OM soils hold more water and buffer temperature extremes. Fungal networks act as drought insurance — moving water between plants. Diverse food webs maintain function under stress when simplified systems crash. Before expensive infrastructure adaptation, ask whether the biological system is working.

**Transition pathway:** Identify the farm's most acute climate vulnerabilities → address the highest-risk enterprise first → build soil OM (cheapest climate adaptation available) → diversify enterprises → invest in infrastructure where biological approaches are insufficient.

---

### `biodiversity`

**User goal:** Increase functional biodiversity on their farm — for ecological resilience, pest control, pollination, and habitat.

**Scope:** Habitat creation and management (hedgerows, wildflower strips, woodland, ponds), wildlife corridors, integrating biodiversity into productive areas, monitoring. Excludes companion planting within crops (→ `pests` or crop skills), agroforestry enterprise (→ `agroforestry`).

**Framework type:** Design methodology + decision framework for biodiversity investment.

**Sub-tools:**
- `habitat-audit` — current biodiversity assessment; what's present, what's missing, what's at risk
- `hedgerow-design` — species selection, establishment, management
- `wildflower-strips` — design, seed mix selection, management
- `woodland-and-trees` — integrating trees into the farm for habitat, shelter, and ecosystem function
- `wildlife-corridors` — connecting habitat patches; landscape-scale thinking
- `monitoring` — simple monitoring protocols to track biodiversity change over time

**Key thinkers:**
- **E.O. Wilson** — *Half-Earth*; biodiversity science as the framework for understanding what's at stake
- **Dave Goulson** — *A Sting in the Tale*; bee biology and pollinator habitat requirements
- **Aldo Leopold** — *A Sand County Almanac*; land ethic as the moral framework for biodiversity conservation on working farms
- **George Monbiot** — *Feral*; rewilding principles applicable to farm-scale biodiversity

**Soil health angle:** Soil biodiversity is the invisible majority of farm biodiversity. Healthy food webs support surface and above-ground biodiversity: earthworms support bird populations; diverse bacteria and fungi support diverse soil invertebrates; healthy soils support healthy plants which support pollinators and insect communities. Biodiversity above ground and below ground are inseparable.

**Transition pathway:** Farm boundary hedgerow management (low cost, high impact) → introduce wildflower strips in margins → reduce pesticide use to allow insect recovery → establish ponds → create woodland elements as capital and time allow.

---

## Cluster 3: Living Systems

*The biological cycles that make fertility, pest management, and decomposition work. These are applied biology skills for active management of living systems.*

---

### `composting`

**User goal:** Make good compost and use it effectively to build soil biology and fertility.

**Scope:** Hot composting methodology, vermicomposting, Bokashi, compost tea, application timing and rates. Excludes broader fertility planning (→ `soil`), liquid KNF inputs (→ `korean-natural-farming`).

**Framework type:** Process methodology — step-by-step for each composting system.

**Sub-tools:**
- `hot-composting` — building, turning, monitoring, and finishing a hot compost pile; C:N ratio; thermophilic process
- `vermicomposting` — setting up a worm system, feeding, harvesting castings and leachate
- `bokashi` — fermentation-based kitchen and farm waste processing
- `compost-tea` — aerated compost tea (ACT) methodology; Ingham's protocol for biological inoculants
- `application` — when, where, and how much compost to apply; integrating with crop plans

**Key thinkers:**
- **Elaine Ingham** — compost tea methodology; using compost as a biological inoculant not just a fertility input; fungal vs. bacterial compost
- **William Brinton** — compost quality research; how to assess finished compost quality
- **Mary Appelhof** — *Worms Eat My Garbage* — the standard vermicomposting reference
- **Jeff Lowenfels** — compost as a means of reintroducing biology; composting as food web building

**Soil health angle:** Composting is the most direct way to build Ingham's soil food web. The type of compost made (high C:N = fungal; low C:N = bacterial) determines which organisms are introduced. Aerated compost tea can achieve bacterial populations of 10^9/ml and fungal hyphal lengths of 10–40m/g — transformative biological inoculation at low cost.

**Transition pathway:** No composting → start with on-farm waste composting (kitchen scraps, manure, crop residues) → develop hot composting system → introduce compost tea as a foliar/soil drench → progressively replace purchased fertilisers with homemade compost.

---

### `mycology`

**User goal:** Cultivate mushrooms for food, medicine, or farm integration, and understand how fungal networks function in the farm ecosystem.

**Scope:** Mushroom cultivation (log, straw, substrate-based), inoculation techniques, species selection, fungal networks and mycelium in the farm system. Excludes broader soil biology management (→ `soil`).

**Framework type:** Process methodology for cultivation; Q&A for understanding fungal ecology.

**Sub-tools:**
- `species-selection` — which species to grow based on substrate, climate, market, and experience level
- `log-inoculation` — plug spawn method for shiitake, oyster, and others on hardwood logs
- `substrate-cultivation` — straw, sawdust, and cardboard-based growing for oyster and other species
- `fungal-networks` — understanding mycorrhizal and saprotrophic fungi in the farm ecosystem; protecting and encouraging fungal networks
- `farm-integration` — using spent substrate as soil amendment; integrating mushroom production with waste streams

**Key thinkers:**
- **Paul Stamets** — *Mycelium Running*; the most comprehensive practical guide to fungi cultivation and fungal ecology; wood-chip inoculation for farm integration
- **Tradd Cotter** — *Organic Mushroom Farming and Mycoremediation*; farm-scale production and ecological integration
- **Elaine Ingham** — mycorrhizal fungi as the primary soil carbon sequestration mechanism; the damage done by tillage and fungicides to fungal networks

**Soil health angle:** Mycorrhizal fungi are the most important organisms in Ingham's soil food web for perennial and tree systems. Understanding fungal networks makes every management decision clearer: tillage destroys them; perennial roots sustain them; diverse plant communities develop diverse fungal communities. Mushroom cultivation skills directly transfer to on-farm fungal management.

**Transition pathway:** Purchase mushrooms → grow in containers from kit → outdoor log inoculation → wood-chip bed systems integrated into farm pathways and compost → actively protect and encourage mycorrhizal networks across the farm.

---

### `pests`

**User goal:** Identify a pest problem and decide how to manage it — from immediate intervention to long-term prevention.

**Scope:** IPM framework, pest identification, biological control options, cultural controls, companion planting for pest management, chemical control as last resort with safer alternatives noted. Handles insects, fungi, bacteria, and nematode pests. Does not cover vertebrate pests (dealt with in livestock/general context) or weeds (→ crop skills).

**Framework type:** Decision methodology — the IPM ladder from least to most intervention.

**Sub-tools:**
- `identification` — diagnosing what the pest or disease is before acting
- `threshold-assessment` — is the level of damage actually worth intervening on
- `cultural-controls` — rotation, variety selection, timing, companion planting, physical barriers
- `biological-controls` — beneficial insects, predatory mites, nematodes, Bt, Trichoderma; when and how to use
- `organic-interventions` — copper, sulphur, neem, pyrethrin — when these are appropriate and their limitations
- `conventional-options` — chemical control: what's effective, with integrated notes on biology impact and alternatives

**Key thinkers:**
- **Mary Louise Flint & Steve Dreistadt** — *Natural Enemies Handbook* — the primary reference for beneficial insect identification and deployment
- **Eliot Coleman** — *The New Organic Grower*; pest prevention through cultural practices and crop health
- **Jeff Gillman** — *The Truth About Organic Gardening* — balanced evidence-based assessment of organic vs conventional interventions
- **Ingham** — soil biology as the primary pest prevention mechanism; healthy food webs produce plant health that resists pest pressure

**Soil health angle:** Most pest and disease pressure is a symptom of plant stress, which is often a symptom of food web dysfunction. Ingham's framework predicts that plants grown on a functioning soil food web have better nutrient availability, better cell wall integrity, and better systemic resistance than plants on degraded biology. Address the food web before reaching for any spray — biological or chemical.

**Transition pathway:** Chemical-first → use chemical selectively (apply threshold assessment before spraying) → substitute biological controls for softer chemicals → build cultural prevention into crop plans → invest in beneficial habitat to establish permanent biological control infrastructure.

**Delivery note:** Conventional farmers need a fast, clear answer on what will control their pest. Lead with identification and the most effective control (even if chemical), then note what monitoring and cultural practices would prevent the problem next season.

---

### `wildcrafting`

**User goal:** Harvest wild plants from their land sustainably and integrate foraging into the farm system.

**Scope:** Wild plant identification for harvest, sustainable harvest protocols, the Honorable Harvest principle applied to wild gathering, integrating hedgerow and edge management for wildcrafting, value-adding wild harvests. Excludes medicinal herb cultivation (→ `herbs`), formal biodiversity management (→ `biodiversity`).

**Framework type:** Q&A and decision methodology — identification + sustainable harvest judgement.

**Sub-tools:**
- `identification` — identifying common wild edibles and medicinals with confidence; the ID protocol before harvest
- `harvest-protocols` — sustainable harvest rates by species; seasonal timing; leaving enough for ecological function
- `edge-management` — managing farm edges to increase wildcrafting yield without compromising ecological function
- `value-adding` — drying, tincturing, preserving wild harvests; market potential
- `foraging-integration` — integrating wild harvest into farm income and diet without turning it into extraction

**Key thinkers:**
- **Robin Wall Kimmerer** — Honorable Harvest principles as the ethical framework for wildcrafting
- **Samuel Thayer** — *The Forager's Harvest* — the most rigorous and careful wild plant identification reference for North America
- **Roger Phillips** — *Wild Food* — comprehensive European reference
- **Kat Anderson** — *Tending the Wild* — indigenous management of wild harvests as a production system

**Soil health angle:** Wild plants on a healthy farm are indicators of biological function. Dock indicates compaction and poor biology; clover indicates nitrogen-fixing bacterial communities; nettles indicate phosphorus-rich biology. Reading the wild plant community through Ingham's lens tells you about the food web status of every field edge.

**Transition pathway:** No wildcrafting → learn 5–10 confident ID species → develop a harvest protocol → begin managing edges for wildcrafting yield → build into farm income as a low-input value stream.

---

## Cluster 4: Plants

*Growing food and fibre — from annuals to perennials to trees. These skills handle the practical decisions of cultivation.*

---

### `vegetables`

**User goal:** Make good decisions about growing vegetables — variety selection, spacing, timing, succession, and problem-solving.

**Scope:** Annual and biennial vegetable production for market, household, or diversification. Covers intensive production systems. Excludes storage (→ `storage`), selling at market (→ `market`, `direct-marketing`).

**Framework type:** Decision methodology + Q&A for specific growing problems.

**Sub-tools:**
- `variety-selection` — choosing varieties for productivity, flavour, disease resistance, and market
- `spacing-and-density` — intensive bed spacing; balancing yield per area vs. plant health
- `succession-planning` — scheduling plantings for continuous harvest
- `growing-calendar` — what to sow, plant, and harvest by month for temperate climates
- `problem-diagnosis` — identifying and responding to common crop failures
- `intensive-systems` — permanent beds, no-dig, broadfork; the market garden approach

**Key thinkers:**
- **Eliot Coleman** — *The New Organic Grower*, *Four-Season Harvest* — the foundational texts for intensive organic vegetable production; four-season production in cold climates
- **Jean-Martin Fortier** — *The Market Gardener* — high-income small-scale production system; intensive bed-based approach with detailed rotation and succession
- **Charles Dowding** — no-dig methodology; minimal disturbance for vegetable production; documented trial results

**Soil health angle:** Vegetable production has the most intensive soil management demands of any farm enterprise. No-dig and permanent bed systems maintain fungal networks that tillage-based systems destroy. Coleman's and Dowding's work demonstrates that minimal disturbance with compost additions outperforms conventional cultivated beds for yield and soil health simultaneously.

**Transition pathway:** Conventional tilled vegetable beds → introduce permanent bed system → shift to no-dig with compost mulch → reduce or eliminate synthetic fertility as food web builds → introduce succession cover crops between plantings.

---

### `herbs`

**User goal:** Grow medicinal and culinary herbs successfully — from cultivation decisions to drying and value-adding.

**Scope:** Annual and perennial herb cultivation, medicinal and culinary varieties, drying and processing, simple value-adding. Excludes wildcrafting (→ `wildcrafting`), market selling (→ `direct-marketing`).

**Framework type:** Q&A + process methodology.

**Sub-tools:**
- `species-by-species` — cultivation guide for the most common culinary and medicinal herbs
- `drying-and-processing` — methods for preserving medicinal quality through correct drying
- `perennial-design` — integrating perennial herbs into the farm system as part of food web support
- `medicinal-growing` — specific requirements for herbs grown for medicinal quality vs culinary

**Key thinkers:**
- **Rosemary Gladstar** — *Medicinal Herbs: A Beginner's Guide* — most accessible introduction to growing for medicine
- **Jekka McVicar** — *The Complete Herb Book* — comprehensive cultivation reference
- **Richo Cech** — *Making Plant Medicine* — growing for medicine with quality and potency focus

**Soil health angle:** Herb quality — essential oil content, medicinal potency — is heavily influenced by soil biology. Stressed plants grown on low-biology soils produce different (often inferior) chemistry than plants on thriving food webs. Ingham's framework explains why herbs grown with minimal inputs in biologically active soils are often superior to heavily fertilised crops.

**Transition pathway:** Purchase herbs → grow from seed/cutting in pots → establish in-ground perennial herb bed → integrate into farm system as companion plants and habitat for beneficials.

---

### `grains`

**User goal:** Grow grains at small scale — for food self-sufficiency, stock feed, or niche market.

**Scope:** Small-scale grain production (wheat, oats, rye, barley, spelt, buckwheat, corn), variety selection, harvest, basic storage. Excludes large-scale conventional grain farming, specialist milling.

**Framework type:** Process methodology + Q&A.

**Sub-tools:**
- `variety-selection` — heritage vs modern varieties; landrace grains; matching variety to climate and use
- `establishment` — seedbed preparation, seeding rates, timing
- `harvest-management` — small-scale harvest options; moisture content for storage
- `rotation-planning` — grains within a diverse rotation; break crops; soil health integration

**Key thinkers:**
- **Wes Jackson** — Land Institute; perennial grain crops as the ecological future of grain farming; *Consulting the Genius of the Place*
- **Gary Paul Nabhan** — heritage grain revival; landrace varieties adapted to place
- **Phil Shepard** — *Restoration Agriculture* — perennial grain crops integrated with livestock and tree systems
- **Masanobu Fukuoka** — *One-Straw Revolution* — do-nothing grain farming as a proof of concept for minimal intervention

**Soil health angle:** Grain monocultures are among the most biologically damaging agricultural systems — annual tillage, monoculture, and nitrogen-heavy fertility destroys fungal communities and builds bacterial-dominant soils. Even small-scale grain growers can mitigate this through cover cropping, reduced tillage, and diverse rotations. Fukuoka's grain-growing without tillage demonstrates that the food web can maintain grain fertility without external inputs.

**Transition pathway:** Conventional tilled grain → introduce cover crop in rotation → reduce tillage → incorporate legume break crop → move toward a mixed system where grain is one component of diversity.

---

### `microgreens`

**User goal:** Set up and run a microgreens system — for household use or small-scale market production.

**Scope:** Variety selection, system design (trays, media, lighting), seeding density, harvest timing, common problems. Excludes sprouting (different system), broader market selling (→ `market`).

**Framework type:** Process methodology.

**Sub-tools:**
- `variety-selection` — which species suit microgreens production; flavour, speed, difficulty, market demand
- `system-design` — tray size, growing media (soil vs. soilless), light requirements, seeding density
- `seeding-and-growing` — step-by-step from seeding to harvest
- `troubleshooting` — mould, uneven germination, poor growth, pest issues

**Key thinkers:**
- **Mark Mathew Braunstein** — *Microgreen Garden* — early text on microgreens cultivation
- **Johnny's Selected Seeds** — agronomic research on microgreen seeding rates and yields
- **Cornell CEA group** — research on optimising microgreen production systems

**Soil health angle:** Microgreens are typically grown in soilless media — the food web lens is less central here. However, soil-grown microgreens have documented superior nutritional density. The skill should note that for nutritional quality, a biologically active growing medium outperforms sterile media, and that spent microgreen trays are a valuable compost input.

**Transition pathway:** Soilless commercial media → introduce a small percentage of compost → trial soil-based growing → use spent media as compost input.

---

### `seeds`

**User goal:** Save seed from their crops successfully — for self-sufficiency, variety preservation, or local adaptation.

**Scope:** Seed saving methodology for common vegetables and herbs — isolation distances, selection criteria, cleaning, drying, storage. Excludes plant breeding (→ separate skill if added), commercial seed production.

**Framework type:** Process methodology + species-specific guidance.

**Sub-tools:**
- `isolation` — crossing risk by species; isolation distances and barriers; time isolation
- `selection` — roguing for type, health, and performance; what to select for
- `cleaning-and-drying` — wet and dry processing methods; moisture content targets
- `storage` — container selection, temperature, humidity; viability by species
- `species-guides` — quick reference for the most commonly saved crops

**Key thinkers:**
- **William Woys Weaver** — *Heirloom Vegetable Gardening* — the definitive historical and practical reference for heirloom variety preservation
- **Carol Deppe** — *Breed Your Own Vegetable Varieties* — seed saving through to active breeding; the most rigorous practitioner guide
- **Suzanne Ashworth** — *Seed to Seed* — the standard practical reference for seed savers
- **Vandana Shiva** — seed sovereignty framing; why saving seed is a political and ecological act

**Soil health angle:** Locally adapted seeds developed through on-farm selection are more biologically resilient than commercial varieties bred for industrial systems. Seeds saved from plants grown in healthy food web soils carry epigenetic advantages. The act of saving seed is also an act of maintaining the on-farm biological system — seeds adapted to local soil biology are more likely to establish successfully in that soil.

**Transition pathway:** Buy commercial seed every year → save seed from one or two reliable crops → expand to the full vegetable garden → develop locally adapted varieties through selection over years.

---

### `propagation`

**User goal:** Propagate plants vegetatively — cuttings, division, grafting, layering — for farm use or sale.

**Scope:** Practical propagation techniques for farm and garden plants. Covers softwood and hardwood cuttings, division, layering, simple grafting. Excludes seed propagation (→ `seeds`).

**Framework type:** Process methodology — technique-specific guides.

**Sub-tools:**
- `cuttings` — softwood, semi-ripe, hardwood; timing, media, hormone use
- `division` — perennial division; timing, replanting
- `layering` — air layering, simple layering, tip layering for fruits and shrubs
- `grafting` — whip-and-tongue, chip budding for fruit trees; rootstock matching
- `mist-propagation` — setting up a simple mist unit for high-volume propagation

**Key thinkers:**
- **Ken Muir** — soft fruit propagation
- **Stefan Buczacki** — *Propagating Plants* — comprehensive reference
- **R.J. Garner** — *The Grafter's Handbook* — the definitive grafting reference

**Soil health angle:** Rooting media biology matters significantly for propagation success. Sterile media gives control but misses the benefit of mycorrhizal inoculation — plants inoculated with mycorrhizal fungi at propagation stage establish dramatically better in field soils. The skill should recommend mycorrhizal inoculation at the propagation stage for perennial plants.

**Transition pathway:** Rooting in sterile perlite/vermiculite → add mycorrhizal inoculant at rooting stage → trial compost-based media → develop on-farm propagation system that reduces purchased plant costs.

---

### `small-fruits`

**User goal:** Establish and manage small fruit production — berries, brambles, currants, vines — successfully.

**Scope:** Variety selection, establishment, training systems, pruning, pest and disease management for small fruits. Excludes orchards (→ `orchards`), market selling (→ `market`).

**Framework type:** Q&A + decision methodology per enterprise type.

**Sub-tools:**
- `variety-selection` — variety choice by climate, market, disease resistance, season
- `establishment` — site preparation, planting, establishment year management
- `training-and-pruning` — system selection and annual pruning methodology by species
- `nutrition-and-soil` — small fruit specific fertility needs; mycorrhizal dependency of blueberries and others
- `pest-and-disease` — common problems by species; IPM approach

**Key thinkers:**
- **Lewis Hill** — *Fruits and Berries for the Home Garden* — accessible practical reference
- **Lee Reich** — *Uncommon Fruits for Every Garden* — expanding small fruit diversity beyond the mainstream
- **Michael Phillips** — *The Holistic Orchard* — covers small fruits within an ecological approach; mycelial connections; avoiding chemistry

**Soil health angle:** Blueberries, strawberries, and raspberries are heavily mycorrhizal-dependent — their establishment and productivity is directly linked to fungal networks. Conventional strawberry production (methyl bromide fumigation, black plastic) is among the most biologically destructive agricultural practices. Small fruit systems designed around fungal health outperform chemically dependent systems long-term.

**Transition pathway:** Chemical-dependent conventional system → reduce fungicide use (most damaging to mycorrhizae) → introduce compost mulch → transition strawberries to raised beds or table-top without fumigation → establish mycorrhizal diversity in permanent plantings.

---

### `orchards`

**User goal:** Establish and manage a fruit tree orchard successfully.

**Scope:** Species and variety selection, rootstock choice, site selection, planting, pruning systems, nutrition, pest and disease management. Excludes agroforestry enterprise design (→ `agroforestry`), market selling (→ `direct-marketing`).

**Framework type:** Decision methodology + Q&A per management phase.

**Sub-tools:**
- `species-variety-rootstock` — matching species, variety, and rootstock to site, market, and management system
- `establishment` — site preparation, planting, staking, first-year management
- `pruning-systems` — open centre, central leader, espalier; annual pruning methodology
- `nutrition` — orchard fertility; compost, mulch, green manure; avoiding excess nitrogen
- `pest-disease-management` — IPM for orchards; the holistic orchard approach; conventional spray programmes

**Key thinkers:**
- **Michael Phillips** — *The Holistic Orchard*; the definitive ecological orchard management reference; mycelial networks; biological fungal management; neem and clay kaolin alternatives
- **Harold McGee** — fruit science; understanding flavour development and the factors that influence it
- **Tom Burford** — *Apples of North America* — heirloom apple reference; variety knowledge and heritage preservation
- **Ann Fowler Rhoads & Timothy Block** — European orchard management traditions

**Soil health angle:** Orchard trees are among the most fungal-dependent plants in agricultural systems. Ingham's fungi-to-bacteria ratio is critical: young orchards need fungal inoculation; conventional spray programmes destroy the mycorrhizal network that makes trees productive and resilient. The holistic orchard approach (Phillips) is essentially Ingham's food web management applied to tree fruit.

**Transition pathway:** Conventional spray programme → introduce kaolin clay and neem before reaching for fungicides → reduce fungicide to minimum necessary → mulch with wood chips to restore fungal networks → introduce biological fungicides (Bacillus, Trichoderma) → build toward holistic system.

---

### `agroforestry`

**User goal:** Design and manage an agroforestry system — silvopasture, food forest, windbreaks, riparian buffers.

**Scope:** The main agroforestry systems (silvopasture, alley cropping, food forests, windbreaks, riparian buffers), design methodology, species selection, integration with other enterprises. Excludes syntropic farming (→ `syntropic`), orchard management (→ `orchards`).

**Framework type:** Design methodology.

**Sub-tools:**
- `system-selection` — choosing the right agroforestry system for the farm context
- `silvopasture` — integrating trees into grazing systems; species, spacing, livestock management
- `alley-cropping` — annual crops between tree rows; design, management, harvest
- `food-forest` — seven-layer food forest design; species selection for each layer
- `windbreaks` — species selection, design, establishment for wind and erosion protection
- `riparian-buffers` — stream bank planting; species selection, management, compliance

**Key thinkers:**
- **Martin Crawford** — *Creating a Forest Garden* — the most comprehensive practical food forest guide
- **Mark Shepard** — *Restoration Agriculture* — large-scale agroforestry integrated with livestock and annuals; the STUN (Sheer Total Utter Neglect) philosophy
- **Ernst Götsch** — syntropic agroforestry methodology (→ `syntropic` for full treatment)
- **USDA NRCS** — agroforestry practice standards and technical guidance

**Soil health angle:** Agroforestry systems, particularly food forests and silvopasture, create the fungal-dominated soil biology that Ingham describes as ideal for perennial production. Tree roots and mycorrhizal networks reach depths annual systems never access, cycling nutrients from subsoil to surface. Agroforestry systems sequester more carbon and build more OM faster than any purely annual system.

**Transition pathway:** Annual monoculture → introduce windbreaks (first trees, cheapest to establish, clear function) → add silvopasture elements if livestock present → develop agroforestry alleys → build toward food forest or full integration over 10–20 years.

---

## Cluster 5: Animals

*Livestock and creatures managed for land health and farm output.*

---

### `livestock`

**User goal:** Manage grazing animals well — for land health, animal performance, and farm profitability.

**Scope:** Rotational and holistic planned grazing methodology, stocking rate, grazing planning, land recovery, integrating livestock with crop enterprises. Excludes species-specific health and husbandry (→ `poultry`, `pigs`, `goats`).

**Framework type:** Decision methodology — the holistic planned grazing framework.

**Sub-tools:**
- `grazing-planning` — the holistic planned grazing planning process; recovery periods, stock density, paddock design
- `stocking-rate` — calculating and adjusting stocking rate to land capacity
- `recovery-monitoring` — reading grass recovery and adjusting the plan in real time
- `integration` — combining livestock with cropping, orchards, and agroforestry
- `fencing-for-rotation` — minimal fencing systems for rotational grazing (cross-reference → `fencing`)

**Key thinkers:**
- **Allan Savory** — *Holistic Management*; the definitive framework for planned grazing; brittle vs non-brittle environments; recovery periods as the key variable
- **Joel Salatin** — *You Can Farm*, *Salad Bar Beef* — practical polyface system; mob grazing and multi-species stacking
- **Jim Gerrish** — *Management-Intensive Grazing* — detailed practical grazing planning from a Missouri pasture context
- **Andre Voisin** — *Grass Productivity* — the foundational pasture science; rest periods and grass recovery

**Soil health angle:** Well-managed rotational grazing builds soil biology faster than any other management practice on grassland. Dung beetles, hoof action, and root exudate stimulation from grazing plants all feed the food web. Savory's recovery periods allow mycorrhizal networks to rebuild between grazing events. Continuous low-density grazing does the opposite — it is one of the most biologically degrading agricultural practices.

**Transition pathway:** Set stocking or continuous grazing → divide into minimum 4–6 paddocks → implement basic rotation → extend rest periods → develop holistic grazing plan → move toward high-density short-duration mob grazing with full recovery.

---

### `poultry`

**User goal:** Manage a poultry enterprise well — layers, meat birds, or ducks in a system that works for the land and the farmer.

**Scope:** Layer and meat bird management, mobile systems, housing, health, integration with other farm enterprises. Excludes processing (requires compliance context), large-scale commercial systems.

**Framework type:** Q&A + decision methodology.

**Sub-tools:**
- `system-selection` — fixed housing vs. mobile; layers vs. meat birds vs. dual purpose
- `mobile-systems` — egg mobile and pastured meat bird systems; pasture management
- `housing` — housing requirements, predator protection, ventilation
- `health-management` — common poultry health issues; prevention-first approach; when to call a vet
- `feed-and-nutrition` — feed formulation vs. commercial feed; integration with farm forages
- `integration` — chicken tractors in market gardens; ducks in orchards and rice systems

**Key thinkers:**
- **Joel Salatin** — *Pastured Poultry Profits* — the egg mobile and broiler tractor systems; land healing with poultry
- **Harvey Ussery** — *The Small-Scale Poultry Flock* — the most comprehensive reference for small-scale integrated poultry
- **Andy Lee & Pat Foreman** — *Day Range Poultry* — practical day-ranging systems

**Soil health angle:** Pastured poultry is a powerful tool for soil biology if managed correctly — the scratching, manure deposition, and pest consumption all benefit the food web. But over-concentrated poultry destroy biology through nitrogen burn and compaction. Rotation is critical: the skill should frame poultry integration through Ingham's lens — manure concentration beyond the food web's capacity to process it becomes toxic.

**Transition pathway:** Battery cage or intensive shed → introduce outdoor access → develop rotation system → move to fully pastured mobile system if enterprise supports it.

---

### `bees`

**User goal:** Manage a beehive or beehives well — for pollination, honey, or both.

**Scope:** Colony management through the season, inspection methodology, swarm management, common disease and pest diagnosis (Varroa, AFB, EFB, Nosema), natural beekeeping approaches alongside conventional. Excludes large commercial operations.

**Framework type:** Process methodology + seasonal calendar.

**Sub-tools:**
- `seasonal-management` — what to do in each season; the apiary calendar
- `inspection` — how to inspect a hive; what to look for; records
- `swarm-management` — reading swarm signs; catching and managing swarms; prevention
- `varroa-management` — integrated Varroa management; treatment options from natural to synthetic
- `disease-diagnosis` — identifying and responding to common hive diseases
- `natural-beekeeping` — low-intervention approaches; top bar hives; treatment-free beekeeping

**Key thinkers:**
- **David Heaf** — *The Bee-Friendly Beekeeper* — natural beekeeping principles; bee-centric management
- **Seeley Thomas** — *Honeybee Democracy* — biology of swarm decision-making; implications for hive management
- **Johann Thür** — *Beekeeping Naturally* — warré hive system; minimal intervention
- **Phil Chandler** — *The Barefoot Beekeeper* — accessible guide to natural beekeeping

**Soil health angle:** Bees are the primary pollination service in most farm systems. Pollinator health is directly connected to pesticide use — the same insecticides and fungicides that damage the soil food web damage bee health. A farm commitment to reducing chemistry for soil biology reasons simultaneously supports pollinator health. The skill should make this connection explicit.

**Transition pathway:** Conventional Langstroth with synthetic Varroa treatments → trial oxalic acid and other approved organic Varroa treatments → reduce treatment frequency through improved colony genetics → develop locally adapted treatment-resistant stock where possible.

---

### `pigs`

**User goal:** Manage pigs in a system that works for the land, the animals, and the farm income.

**Scope:** Pasture pig systems, woodland systems, rotational management, housing, breed selection, nutrition, basic health. Excludes intensive indoor systems, processing.

**Framework type:** Decision methodology + Q&A.

**Sub-tools:**
- `system-selection` — woodland vs. pasture vs. orchard integration; breed matching to system
- `rotational-management` — how long pigs can be in each area before land is compromised; recovery periods
- `nutrition` — pasture and woodland contribution to diet; supplement requirements; managing without purchased feed where possible
- `housing` — ark and shelter requirements; predator protection
- `health-basics` — worms, mange, foot problems; prevention and treatment

**Key thinkers:**
- **Joel Salatin** — pig integration in a multi-species system; *Everything I Want to Do Is Illegal*
- **Noel Coward** — pasture pig production systems
- **Forrest Prichard** — *Gaining Ground* — integrating pigs into a diversified farm system

**Soil health angle:** Pigs are the most destructive grazing animal to soil biology if not rotationally managed — their rooting behaviour destroys fungal networks and compacts soil. But this destructive capacity is also their most valuable tool: pigs can be used to clear scrub, work compacted ground, and prepare areas for replanting. The skill frames this as "destructive power as a tool" — used intentionally in rotation and then allowed to recover.

**Transition pathway:** Static paddock → basic rotation (2–3 areas) → extend rotation to allow full vegetation recovery → integrate with orchard or woodland where possible → manage rooting as a land preparation tool.

---

### `goats`

**User goal:** Manage goats effectively for dairy, meat, fibre, or land clearing.

**Scope:** Dairy and meat goat management, land clearing applications, housing, nutrition, health, fencing requirements. Excludes large commercial dairy operations.

**Framework type:** Q&A + decision methodology.

**Sub-tools:**
- `system-selection` — dairy vs. meat vs. fibre vs. land management; breed matching
- `dairy-management` — milking, breeding, kid management, mastitis prevention
- `land-clearing` — using goats as a land management tool; targeted grazing; controlling scrub and invasives
- `nutrition` — browse and pasture contribution; mineral requirements; avoiding toxic plants
- `health-basics` — worms (FAMACHA), foot problems, CAE; prevention-first approach

**Key thinkers:**
- **Cheryl K. Smith** — *Goat Health Care* — the most comprehensive health reference
- **Gail Damerow** — *Storey's Guide to Raising Dairy Goats* — practical management reference
- **Aldo Leopold** — browsing impact on vegetation structure; the ecological case for managing goat impact

**Soil health angle:** Goats as browsers rather than grazers interact with soil biology differently from cattle or sheep. Heavy browsing on shrubs and trees can remove the woody perennial root systems that sustain fungal networks. The skill should frame goat land management through the lens of succession and recovery — used in rotation to manage scrub without eliminating the plants that build fungal soil biology.

**Transition pathway:** Static or minimally rotated → basic rotation with recovery periods → integrate browsing with grazing management plan → develop targeted grazing programme for land management objectives.

---

### `aquaculture`

**User goal:** Set up and manage a small-scale aquaculture system for food production or farm integration.

**Scope:** Small-scale fish (trout, perch, carp), crayfish, and integrated aquaponics systems. Excludes large commercial aquaculture operations, offshore systems.

**Framework type:** Decision methodology + process guide.

**Sub-tools:**
- `system-selection` — pond vs. tank vs. aquaponics; species matching to system and market
- `water-quality` — the key parameters; measuring, maintaining, problems
- `feeding-and-nutrition` — commercial feed vs. on-farm feed production (duckweed, insects, algae)
- `aquaponics` — integrating fish production with plant production; system design; balancing fish load and plant beds
- `integrated-systems` — using aquaculture effluent for irrigation and fertility; connecting to other farm water systems

**Key thinkers:**
- **Murray Hallam** — *Aquaponics Made Easy* — accessible introduction to aquaponics systems
- **Nick Savidov** — Alberta Agriculture aquaponics research; plant production in aquaponic systems
- **Will Allen** — Growing Power's aquaponics integration within urban farming systems

**Soil health angle:** Aquaponic effluent is a high-quality biological inoculant for soil and growing media — rich in bacteria, beneficial microorganisms, and bioavailable nutrients. Integrating aquaculture with soil-based growing creates a nutrient cycle that mirrors natural wetland systems. The skill should frame aquaculture not as isolated fish production but as a biological fertility engine for the rest of the farm.

**Transition pathway:** Isolated pond or tank → begin using effluent for irrigation → develop basic aquaponics integration → connect to broader farm fertility cycle.

---

## Cluster 6: Growing Environments

*Structures and systems that extend the season or intensify production.*

---

### `polytunnels`

**User goal:** Get the most out of a polytunnel — planning crops, managing environment, extending season.

**Scope:** Polytunnel crop planning and rotation, environmental management (ventilation, humidity, temperature), soil management under cover, pest and disease in enclosed spaces. Excludes CEA/hydroponics (→ `controlled-environment`).

**Framework type:** Decision methodology + seasonal calendar.

**Sub-tools:**
- `crop-planning` — what to grow, rotation, succession in a polytunnel
- `environmental-management` — ventilation, humidity, temperature management without expensive equipment
- `soil-management` — the challenge of continuous covered growing; maintaining biology under cover
- `pest-disease` — enclosed environment pest and disease pressure; biological controls in polytunnels
- `season-extension` — maximising the season extension benefit; spring and autumn cropping

**Key thinkers:**
- **Eliot Coleman** — *The Winter Harvest Handbook* — cold-climate polytunnel and low tunnel production; season extension methodology
- **Charles Dowding** — polytunnel management in UK climate; soil management under cover
- **Joy Larkcom** — *Grow Your Own Vegetables* — polytunnel crop planning reference

**Soil health angle:** Polytunnel soils are among the most biologically stressed in any farming system — covered from rainfall (limits microbial diversity), heated (reduces fungal populations), and continuously cropped (limited rotation). Maintaining soil biology under cover requires active management: frequent compost additions, biological inoculants, and deliberate rotation. Ingham's food web framework is especially important here because the usual biological recovery mechanisms (rain, diversity, rest) are constrained.

**Transition pathway:** Annual bed preparation with synthetic fertilisers → switch to compost-only fertility → introduce biological inoculants → develop proper rotation → no-dig under cover.

---

### `controlled-environment`

**User goal:** Design, set up, or optimise a controlled environment agriculture (CEA) system — hydroponics, aquaponics, or vertical farming.

**Scope:** CEA system types and selection (DWC, NFT, ebb-and-flow, aquaponics), crop selection, nutrient management, light management, economic analysis. Excludes standard polytunnel growing (→ `polytunnels`).

**Framework type:** Decision methodology + Q&A.

**Sub-tools:**
- `system-selection` — matching CEA system type to crop, scale, and budget
- `nutrient-management` — hydroponic nutrient solutions; organic vs synthetic options; monitoring
- `lighting` — natural light supplementation; LED spectrum; DLI targets by crop
- `crop-selection` — which crops make economic sense in CEA vs. soil growing
- `economics` — capital and operating costs; when CEA pencils out

**Key thinkers:**
- **Cornell CEA programme** — the primary research institution for CEA in North America; extensive published guidance
- **Merle Jensen** — controlled environment horticulture; the foundational academic framework
- **Will Allen** — Growing Power; demonstrating CEA integrated with community food systems

**Soil health angle:** CEA systems are explicitly soil-free — the Ingham framework doesn't apply directly. However, the skill should note: biological hydroponic systems (adding beneficial microorganisms to nutrient solutions) consistently outperform sterile chemical systems in plant health and productivity. The food web exists in water too — a biologically managed hydroponic system draws on the same principles.

**Transition pathway:** Sterile chemical nutrient solution → trial beneficial microbial additions → develop a fully biological hydroponic programme → where possible, integrate with aquaponics for a more complete biological cycle.

---

## Cluster 7: Farm Operations

*The practical rhythms and infrastructure of running a farm.*

---

### `seasons`

**User goal:** Plan and execute a year-round production calendar — crops, livestock tasks, and farm operations timed correctly.

**Scope:** Seasonal planning for crop rotation, livestock management, and farm tasks. Includes succession planting schedules, grazing planning calendars, and key seasonal decision points. Excludes individual crop advice (→ crop skills).

**Framework type:** Planning methodology + calendar framework.

**Sub-tools:**
- `crop-calendar` — monthly crop planning template; what to sow, plant, harvest, and prepare
- `rotation-planning` — designing a crop rotation that serves soil health and breaks pest cycles
- `livestock-calendar` — seasonal livestock management tasks calendar
- `succession-planning` — continuous harvest scheduling through succession planting
- `annual-review` — end-of-season review methodology; what to record and what to change

**Key thinkers:**
- **Jean-Martin Fortier** — succession planting scheduling; the market garden production calendar
- **Eliot Coleman** — four-season production; extending the growing calendar in cold climates
- **Joel Salatin** — seasonal farm operations calendar within a diversified system

**Soil health angle:** The seasonal calendar is the primary tool for ensuring Ingham's principle of living roots year-round. Gaps in the calendar where soil is bare are gaps in the food web's energy supply. The skill should systematically identify bare soil periods and prompt cover crop or overwintering crop solutions.

**Transition pathway:** Ad-hoc reactive scheduling → develop a basic crop calendar → introduce succession planting → integrate livestock calendar → build in annual soil rest periods with cover crops → move toward a fully planned, year-round living root system.

---

### `storage`

**User goal:** Store farm produce well — reducing losses, maintaining quality, and extending the marketing window.

**Scope:** Root cellars, grain storage, cold storage, post-harvest handling. Covers both traditional/low-energy and modern refrigeration approaches. Excludes processing and value-adding.

**Framework type:** Decision methodology + Q&A per produce type.

**Sub-tools:**
- `root-cellar` — design, siting, humidity and temperature management; crops suited to root cellar storage
- `grain-storage` — moisture content targets; insect and rodent control; traditional vs modern storage
- `cold-storage` — refrigeration options; produce-specific temperature requirements
- `post-harvest-handling` — cooling, curing, packing; reducing storage losses from handling damage

**Key thinkers:**
- **Mike and Nancy Bubel** — *Root Cellaring* — the standard reference for traditional cold storage
- **Eliot Coleman** — post-harvest handling in a market garden context
- **USDA AMS** — produce storage guidelines; temperature and humidity requirements by commodity

**Soil health angle:** Post-harvest quality is a proxy for soil health — nutritional density, shelf life, and disease resistance in storage are all influenced by the biological status of the soil the crop was grown in. Produce from high-OM, biologically active soils stores better than produce from low-biology, heavily fertilised systems. The skill should note this connection as motivation for soil biology investment.

**Transition pathway:** Selling or consuming immediately after harvest → introduce basic root cellar capability → develop cold storage → reduce losses through systematic post-harvest handling improvement.

---

### `fencing`

**User goal:** Plan and build fencing that serves rotational management, protects crops, and minimises long-term cost.

**Scope:** Permanent and temporary fencing systems, electric fencing methodology, rotational infrastructure design, predator exclusion. Excludes aquaculture fencing.

**Framework type:** Decision methodology + process guide.

**Sub-tools:**
- `system-selection` — permanent vs. temporary; single-wire vs. multi-wire; stock species requirements
- `electric-fencing` — energiser selection and sizing; earthing; troubleshooting
- `rotational-infrastructure` — laying out a paddock system for rotational grazing; lane systems
- `predator-exclusion` — poultry and small stock protection; electric netting; permanent exclusion
- `maintenance` — regular inspection; fault-finding; vegetation management

**Key thinkers:**
- **Jim Gerrish** — *Management-Intensive Grazing* — the fencing chapter as a practical guide to rotational infrastructure
- **Joel Salatin** — step-in post and polywire temporary systems; low-cost rotational infrastructure
- **Premier 1 Supplies** — the primary practical reference for electric fencing methodology

**Soil health angle:** Fencing is the infrastructure that makes rotational grazing possible, and rotational grazing is the management practice most directly connected to soil biology recovery in grassland systems. The skill should frame fencing investment as a biological investment — the paddock system is the delivery mechanism for the biology-building management that follows.

**Transition pathway:** Single perimeter fence → divide into 2–3 paddocks → temporary electric netting for rapid rotation → permanent subdivision → lane system for mob grazing.

---

## Cluster 8: Business & Market

*Making the farm financially viable.*

---

### `finance`

**User goal:** Understand and manage their farm's finances — budgets, cash flow, profitability, and investment decisions.

**Scope:** Enterprise gross margins, whole-farm cash flow, investment appraisal, grants and loans, break-even analysis. Excludes tax advice (professional domain), succession and ownership structure (→ `succession`).

**Framework type:** Decision methodology + structured financial analysis tools.

**Sub-tools:**
- `gross-margins` — enterprise gross margin calculation; comparing enterprises
- `cash-flow` — building and reading a cash flow forecast; managing seasonal cash crunches
- `break-even` — break-even analysis for a new enterprise or investment
- `grants-and-loans` — navigating agricultural finance; what's available and when to use it
- `transition-economics` — the financial profile of transitioning to regenerative; managing the income dip

**Key thinkers:**
- **SARE (Sustainable Agriculture Research & Education)** — enterprise budgeting templates for small and direct-market farms
- **Severine von Tscharner Fleming** — *The Greenhorns* — new-farmer finance and viability framing
- **Gary Zimmer** — *The Biological Farmer* — connecting biological investment to financial returns

**Soil health angle:** Soil health is a financial asset. Increasing OM by 1% on a farm can reduce irrigation costs, reduce purchased fertility costs, increase yield stability, and command premium prices through certification. The skill should frame soil biology investment in financial terms — it is capital accumulation, not just ecological stewardship.

**Transition pathway:** No structured financial management → develop basic enterprise gross margins → build a whole-farm cash flow → integrate transition costs into financial planning → track soil health improvements as a capital asset.

---

### `direct-marketing`

**User goal:** Sell farm produce directly to customers — box schemes, farm shops, online, restaurant and wholesale accounts.

**Scope:** Setting up and running direct-to-consumer and direct-to-business sales channels. Includes CSA/box scheme design, farm shop, online platforms, restaurant relationships. Excludes farmers markets (→ `market`).

**Framework type:** Decision methodology + channel-specific guidance.

**Sub-tools:**
- `csa-design` — box scheme design; share pricing, delivery logistics, member management
- `farm-shop` — setting up a farm shop; range selection, pricing, margins, customer experience
- `online-sales` — platforms and fulfilment for online farm shop
- `restaurant-relationships` — building and maintaining chef relationships; pricing for wholesale

**Key thinkers:**
- **Jean-Martin Fortier** — direct marketing as the primary revenue strategy for small-scale producers
- **Elizabeth Henderson** — *Sharing the Harvest* — the definitive CSA guide
- **Severine von Tscharner Fleming** — new farmer direct marketing

**Soil health angle:** Direct marketing enables premium pricing for provenance and quality — and biological soil management is the most defensible route to genuine quality. The skill should frame soil biology investment as a marketing asset: customers who understand the connection between soil health and food quality will pay a premium, and that premium is the financial return on the soil investment.

**Transition pathway:** Selling to wholesale or auction → establish one direct channel (farm shop or box scheme) → expand to additional channels → develop customer relationships that build premium pricing.

---

### `market`

**User goal:** Plan, prepare for, and sell successfully at a farmers market — from first market to optimising a regular pitch.

**Scope:** Market selection and application, stall display and presentation, pricing and product mix decisions, customer conversation, weather and seasonal preparation, financial record-keeping and performance tracking. Excludes box schemes and online selling (→ `direct-marketing`), broader business finance (→ `finance`).

**Framework type:** Decision methodology + operational checklist.

**Sub-tools:**
- `market-selection` — evaluating and choosing the right market; footfall, customer demographic, competition, access and logistics
- `display-and-presentation` — stall layout; height, signage, product grouping; what drives purchase decisions at a market stall
- `pricing` — pricing for market context; reading competitors; adjusting in real time; margin vs. volume decisions
- `product-mix` — what to take and in what quantities; lead products and supporting range; seasonal adjustments; reducing surplus and shortfall
- `customer-conversation` — talking about how you farm; building return customers; the story as a sales tool
- `market-day-operations` — packing list, setup, breakdown, cash handling, weather prep
- `performance-tracking` — what to record at each market; using data to improve selection, quantity, and timing

**Key thinkers:**
- **Jean-Martin Fortier** — *The Market Gardener*; market selling as the primary revenue strategy; detailed tracking and optimisation methodology
- **Eliot Coleman** — quality and variety as the market farmer's competitive advantage
- **WSDA Direct Marketing Handbook** — the most comprehensive free reference for farmers market operations

**Soil health angle:** At a farmers market, story is the competitive advantage over supermarkets. A farmer who can explain what soil biology is, why their food is grown differently, and what that means for flavour and nutrition has a differentiated product. Soil health investment shows up on the stall — in flavour, shelf life, and the farmer's ability to describe genuinely different practice.

**Transition pathway:** First market with no tracking → begin tracking per-product revenue and sellout rates → use data to refine product mix → develop customer conversation and story → build a regular customer base that generates predictable revenue.

---

### `certification`

**User goal:** Understand and navigate organic, biodynamic, or regenerative certification — whether to pursue it, and how.

**Scope:** Organic certification (main schemes by region), biodynamic (Demeter), regenerative (Regenerative Organic Certified, Soil Association Organic), certification costs and benefits analysis. Excludes carbon credits (→ `carbon`).

**Framework type:** Decision methodology + process guide per certification type.

**Sub-tools:**
- `is-it-worth-it` — costs vs. benefits analysis for certification; premium pricing vs. compliance cost
- `organic-process` — the organic certification process; what's required; transition period
- `biodynamic-process` — Demeter certification requirements; the additional requirements beyond organic
- `regenerative-certification` — Regenerative Organic Certified and equivalent schemes; what they require
- `participatory-guarantee` — PGS schemes as a lower-cost certification alternative

**Key thinkers:**
- **Demeter International** — biodynamic certification standards
- **Rodale Institute** — Regenerative Organic Certified standard
- **Soil Association (UK)** — the most established organic certification body in the UK

**Soil health angle:** Most meaningful certification schemes now include soil health metrics. The Regenerative Organic Certified standard explicitly requires soil health improvement over time. Framing certification as documentation of soil biology investment — rather than just a marketing label — connects the commercial and ecological dimensions.

**Transition pathway:** Uncertified → practice organic methods without certification (first) → assess whether certification premium justifies cost → pursue certification if it pencils out or if market access requires it.

---

### `agritourism`

**User goal:** Develop agritourism as a farm income stream — farm stays, events, education, experiences.

**Scope:** Agritourism enterprise design, planning permission and compliance considerations, pricing, marketing, operational management. Excludes formal farm education programmes (→ `education`).

**Framework type:** Decision methodology + enterprise design guide.

**Sub-tools:**
- `enterprise-design` — defining the agritourism offer; what's right for the farm and the farmer
- `compliance` — planning permission, food safety, public liability; what's needed
- `pricing` — pricing agritourism experiences; what the market will bear
- `marketing` — reaching the agritourism customer; online presence, partnerships
- `operations` — managing guests on a working farm; the practical realities

**Key thinkers:**
- **Pennsylvania State Extension** — agribusiness and agritourism guidance
- **Oregon State University Extension** — small farm business diversification
- **Farm Stay UK** — the primary network for farm accommodation in the UK

**Soil health angle:** Agritourism visitors are increasingly motivated by interest in food provenance and sustainable farming. A farm committed to soil health and regenerative practice has a genuine story to tell — and that story is agritourism content. The skill should connect ecological practice to the visitor experience.

**Transition pathway:** Single farm income stream → identify agritourism opportunities that fit the current operation without major capital → trial a small-scale offer → develop and scale.

---

### `succession`

**User goal:** Plan for farm succession — either passing the farm on or accessing land as a new entrant.

**Scope:** Succession planning for retiring farmers, land access options for new entrants, tenure models (ownership, lease, share farming, community land trust), legal structure options. Excludes tax advice (professional domain).

**Framework type:** Decision methodology + Q&A.

**Sub-tools:**
- `succession-planning` — the succession planning process for existing farm owners; timeline, options, key decisions
- `land-access` — pathways to accessing land for new entrant farmers; lease, purchase, equity share, community models
- `tenure-models` — options beyond ownership and commercial tenancy; community land trusts, share farming, farm business tenancy
- `next-generation` — family succession; managing the transition between generations
- `new-entrant-support` — resources, networks, and programmes for beginning farmers

**Key thinkers:**
- **Land For Good** — the primary US resource for farm succession and access
- **New Entry Sustainable Farming Project** — new farmer support; land access methodology
- **Soil Association** — farm succession guidance in the UK context
- **Farms of the Future / Sustainable Food Trust** — alternative land tenure models

**Soil health angle:** Long-term land tenure is the primary enabler of long-term soil investment. Short-term tenants rarely invest in biology because the benefits accrue beyond the tenancy period. The skill should make this connection explicit: secure long-term tenure is a prerequisite for serious soil health improvement, and tenure models that share the benefits of soil improvement between tenant and landlord are more ecologically sound.

**Transition pathway:** No succession plan → begin the conversation early (5–10 years before planned transition) → document the farm's assets including soil health and biological infrastructure → develop a legally structured plan with professional help.

---

## Cluster 9: People & Community

*The human systems that sustain a farming life.*

---

### `labour`

**User goal:** Find, manage, and develop farm workers, wwoofers, apprentices, or volunteers effectively.

**Scope:** Hiring and HR basics, wwoofer/volunteer management, apprenticeship design, legal compliance (employment law basics). Excludes succession and ownership transfer (→ `succession`).

**Framework type:** Decision methodology + Q&A.

**Sub-tools:**
- `hiring` — job description, interview, selection; matching the person to the role and the farm
- `wwoofers-and-volunteers` — getting the best from non-paid labour; what works and what doesn't
- `apprenticeships` — designing a genuine learning experience alongside useful work
- `legal-basics` — employment status, minimum wage, accommodation deductions; staying on the right side of the law
- `farm-culture` — creating a working environment people want to be part of; retention

**Key thinkers:**
- **Growing Home** — workforce development in urban agriculture; structured training programmes
- **WWOOF networks** — standards and guidance for hosting wwoofers
- **ATTRA (National Sustainable Agriculture Information Service)** — labour management in sustainable agriculture

**Soil health angle:** Farm workers who understand soil biology work differently — they treat soil as a living system rather than a substrate. A farm that educates its labour force in soil food web principles benefits from every worker's choices and habits (no compaction on wet soil, careful compost handling, awareness of spray impacts). The skill should frame soil education as part of any apprenticeship or training programme.

**Transition pathway:** No formal labour management → establish basic employment compliance → develop induction and training process → create apprenticeship framework → build a farm culture where soil health is a shared value.

---

### `community`

**User goal:** Build community connections through the farm — CSAs, food hubs, cooperatives, shared land.

**Scope:** Community-supported agriculture design, food hub participation, cooperative models, shared land initiatives. Excludes formal farm education (→ `education`).

**Framework type:** Decision methodology + Q&A.

**Sub-tools:**
- `csa-community` — building a genuine CSA community, not just a box scheme customer base; member engagement
- `food-hub-participation` — joining or establishing a food hub; aggregation and shared marketing
- `cooperative-models` — farmer cooperative structures; shared input buying, shared marketing
- `shared-land` — community land ownership models; co-operative land management

**Key thinkers:**
- **Elizabeth Henderson** — *Sharing the Harvest*; the CSA as community not commerce
- **SARE** — community food system building
- **La Via Campesina** — food sovereignty movement; the political framing of community food systems

**Soil health angle:** Community food systems create accountability for how food is grown. CSA members who visit the farm develop understanding of soil health; that understanding creates market demand for biological practice and social pressure against degradation. Community engagement is a mechanism for translating soil health investment into market value and social capital.

**Transition pathway:** Isolated farm selling through intermediaries → establish direct customer relationships → develop CSA or farm community → participate in food hub or cooperative → build toward food sovereignty at community scale.

---

### `education`

**User goal:** Design and run farm-based education — visits, courses, workshops, apprenticeships.

**Scope:** Farm visit design for schools and public, course and workshop design, running a learning farm programme, farm-based apprenticeship as education. Excludes general labour management (→ `labour`), agritourism income (→ `agritourism`).

**Framework type:** Design methodology + Q&A.

**Sub-tools:**
- `school-visits` — designing a school farm visit; age-appropriate activities; curriculum connections
- `workshops` — designing and running a farm workshop; from one-day courses to week-long intensives
- `learning-farm` — establishing the farm as a permanent learning institution; programmes and partnerships
- `online-education` — translating farm knowledge to online content; courses, video, membership

**Key thinkers:**
- **Growing Home (Chicago)** — workforce development and farm education as community service
- **Groundswell (UK)** — farmer-to-farmer education through the no-till and regenerative conference
- **Weston A. Price Foundation** — nutrition and food education rooted in agricultural practice

**Soil health angle:** Farm education that includes soil biology — even a basic worm count and jar test — produces visitors who understand the living nature of soil. This understanding has ripple effects: children who know soil is alive become adults who care about how food is grown. The skill should make soil biology education a standard component of any farm education programme.

**Transition pathway:** No education programme → begin with occasional farm visits → develop a structured visit programme → design workshops around areas of farm strength → consider building toward a formal education income stream.

---

## Summary: Skill Writing Priorities

Based on the scope mapping above, the following sequence is recommended for writing:

**Phase 1 — Foundation skills (write first, these underpin all others)**
1. `soil` — Ingham's framework; the biological foundation
2. `regenerative` — the whole-farm philosophy
3. `pests` — IPM ladder; most frequently needed
4. `seasons` — the planning framework everything else slots into

**Phase 2 — High-traffic practical skills**
5. `vegetables` — the most queried crop domain
6. `livestock` — Savory's holistic grazing framework
7. `water` — critical for most farm operations
8. `composting` — DIY biology building
9. `finance` — financial viability underpins everything

**Phase 3 — Philosophy and systems (complete the thinking frameworks)**
10. `permaculture`
11. `syntropic`
12. `korean-natural-farming`
13. `biodynamic`
14. `indigenous`

**Phase 4 — Remaining plant, animal, and operations skills**
All remaining skills in Clusters 4–7

**Phase 5 — Business and community skills**
All Cluster 8–9 skills

---

*Research sources: Tavily web research conducted 2026-06-01. Key sources include Soil Foodweb School, Holistic Management International, Agenda Götsch, Demeter International, SARE, Cornell CEA, ATTRA, Land For Good, and published works of the thinkers cited throughout.*
