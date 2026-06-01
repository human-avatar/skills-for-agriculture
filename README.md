# skills-for-agriculture

Decision-making and guidance skills for farmers, growers, and land stewards. Built on expert practitioner knowledge — not generic advice.

Every skill operates from the premise that farm decisions are also ecosystem decisions. Recommendations prioritise long-term ecological health alongside farm viability — while always giving the conventional answer plainly when that's what the situation needs.

## Install

```
/plugin install skills-for-agriculture
```

## Start here

```
/s4ag
```

`/s4ag` is the router. Describe what you're working on and it points you to the right skill. Every other skill is namespaced `/s4ag-<domain>` and can also be invoked directly.

All skills share two conventions:
- **Checkpoints** — each tool pauses to confirm its assumptions (climate, system, urgency, budget) before producing a plan. A recommendation built on a wrong assumption wastes money in the field.
- **Next steps** — each tool ends by recommending the related skills worth running next.

## Packages

### Router
| Package | Command | Description |
|---|---|---|
| `s4ag` | `/s4ag` | Routes any farming need to the right starting skill |

### Philosophy & Systems
*Whole-farm thinking frameworks — the lens through which all other decisions are made.*

| Package | Command | Description |
|---|---|---|
| `s4ag-regenerative` | `/s4ag-regenerative` | Regenerative principles, assessment, ecosystem design, and transition from conventional — includes full transition pathway |
| `s4ag-permaculture` | `/s4ag-permaculture` | Zones, sectors, guilds, patterns, and ethics applied to farm planning |
| `s4ag-biodynamic` | `/s4ag-biodynamic` | Calendar, preparations, and Steiner principles in practice |
| `s4ag-syntropic` | `/s4ag-syntropic` | Ernst Götsch's succession-based agroforestry system |
| `s4ag-korean-natural-farming` | `/s4ag-korean-natural-farming` | Fermented inputs, IMO cultivation, low-cost indigenous fertility |
| `s4ag-indigenous` | `/s4ag-indigenous` | Traditional ecological knowledge, land relationships, and practice |
| `s4ag-transitioning` | `/s4ag-transitioning` | Routing entry for conventional→regenerative transition (into `/s4ag-regenerative`) |

### Land & Ecology
*The physical and ecological substrate of the farm — land, water, carbon, and climate.*

| Package | Command | Description |
|---|---|---|
| `s4ag-land-reading` | `/s4ag-land-reading` | Assessing a piece of land — patterns, history, potential |
| `s4ag-soil` | `/s4ag-soil` | Testing, amendments, soil food web, biology, and long-term fertility |
| `s4ag-water` | `/s4ag-water` | Irrigation, catchment, drainage, drought resilience |
| `s4ag-earthworks` | `/s4ag-earthworks` | Swales, berms, ponds, and contour design |
| `s4ag-carbon` | `/s4ag-carbon` | Sequestration, measurement, and carbon credits |
| `s4ag-climate-adaptation` | `/s4ag-climate-adaptation` | Managing for a changing climate, building resilience |
| `s4ag-biodiversity` | `/s4ag-biodiversity` | Habitat creation, wildlife corridors, hedgerows, and ecological integration |

### Living Systems
*The biological cycles that make fertility, pest control, and decomposition possible.*

| Package | Command | Description |
|---|---|---|
| `s4ag-composting` | `/s4ag-composting` | Hot composting, vermicomposting, bokashi, and compost tea |
| `s4ag-mycology` | `/s4ag-mycology` | Mushroom growing, inoculation, and fungal networks |
| `s4ag-pests` | `/s4ag-pests` | IPM ladder, biological controls, and companion planting |
| `s4ag-wildcrafting` | `/s4ag-wildcrafting` | Wild harvesting, edge management, and foraging integration |

### Plants
*Growing food and fibre — from annuals to perennials to trees.*

| Package | Command | Description |
|---|---|---|
| `s4ag-vegetables` | `/s4ag-vegetables` | Intensive veg — variety, spacing, timing, succession |
| `s4ag-herbs` | `/s4ag-herbs` | Medicinal and culinary — growing, drying, value-add |
| `s4ag-grains` | `/s4ag-grains` | Small-scale grains — variety, harvest, storage |
| `s4ag-microgreens` | `/s4ag-microgreens` | Variety selection, systems, seeding density |
| `s4ag-seeds` | `/s4ag-seeds` | Saving, isolation, cleaning, storage |
| `s4ag-propagation` | `/s4ag-propagation` | Cuttings, grafting, division, layering |
| `s4ag-small-fruits` | `/s4ag-small-fruits` | Berries, brambles, currants, vines |
| `s4ag-orchards` | `/s4ag-orchards` | Fruit trees — establishment, pruning, rootstocks |
| `s4ag-agroforestry` | `/s4ag-agroforestry` | Silvopasture, food forests, and shelter belts |

### Animals
*Livestock and creatures managed for land health and farm output.*

| Package | Command | Description |
|---|---|---|
| `s4ag-livestock` | `/s4ag-livestock` | Rotational grazing, holistic planned grazing, animal health, land integration |
| `s4ag-poultry` | `/s4ag-poultry` | Layers, meat birds, ducks, mobile systems |
| `s4ag-bees` | `/s4ag-bees` | Hive management, natural beekeeping, pollination |
| `s4ag-pigs` | `/s4ag-pigs` | Pasture pigs, woodland systems, rotational management |
| `s4ag-goats` | `/s4ag-goats` | Dairy, meat, land clearing, grazing |
| `s4ag-aquaculture` | `/s4ag-aquaculture` | Fish, crayfish, and integrated water systems |

### Growing Environments
*Structures and systems that extend the season or intensify production.*

| Package | Command | Description |
|---|---|---|
| `s4ag-polytunnels` | `/s4ag-polytunnels` | Season extension, crop selection, environment management |
| `s4ag-controlled-environment` | `/s4ag-controlled-environment` | Hydroponics, aquaponics, vertical farming, and CEA |

### Farm Operations
*The practical rhythms and infrastructure of running a farm.*

| Package | Command | Description |
|---|---|---|
| `s4ag-seasons` | `/s4ag-seasons` | Rotation, succession planting, and year-round production |
| `s4ag-storage` | `/s4ag-storage` | Root cellars, grain storage, cold storage, post-harvest |
| `s4ag-fencing` | `/s4ag-fencing` | Rotational infrastructure, electric fencing, permanent fencing |

### Business & Market
*Making the farm financially viable.*

| Package | Command | Description |
|---|---|---|
| `s4ag-finance` | `/s4ag-finance` | Enterprise budgeting, cash flow, grants, loans |
| `s4ag-direct-marketing` | `/s4ag-direct-marketing` | Box schemes, farm shops, restaurants, online |
| `s4ag-market` | `/s4ag-market` | Farmers markets — planning, pricing, presentation |
| `s4ag-certification` | `/s4ag-certification` | Organic, biodynamic, regenerative — what's worth it |
| `s4ag-agritourism` | `/s4ag-agritourism` | Farm stays, events, education as income |
| `s4ag-succession` | `/s4ag-succession` | Succession planning, land access, tenure |

### People & Community
*The human systems that sustain a farming life.*

| Package | Command | Description |
|---|---|---|
| `s4ag-labour` | `/s4ag-labour` | Workers, wwoofers, apprentices, legal considerations |
| `s4ag-community` | `/s4ag-community` | CSAs, food hubs, cooperatives, shared land |
| `s4ag-education` | `/s4ag-education` | Farm visits, courses, workshops, learning farms |

## Structure

```
packages/
  s4ag/             ← the router, invoked as /s4ag
  s4ag-{domain}/
    SKILL.md        ← invoked as /s4ag-{domain}
```

## Status

Skills are being written progressively, grounded in expert practitioner knowledge. Fully written: `s4ag-regenerative` (includes transition pathway), `s4ag-soil`, `s4ag-pests`, `s4ag-seasons`, plus the `s4ag` router. Remaining packages are stubs being filled in by phase.
