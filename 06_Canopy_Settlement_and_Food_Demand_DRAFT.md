# Canopy Market-Town Population and Agricultural Demand — DRAFT

**Status:** Exploratory model. Neither the market town's population nor Leshy are author-approved canon. Main mechanical/lore authority remains [mystaria-codex](https://github.com/MyStalker/mystaria-codex).

## User-stated research order (2026-11-21)
Begin with **town population, urban footprint, and surrounding market population**, then extrapolate grocery demand before estimating output per farm and the number of farms required. This supersedes jumping immediately to isolated farm finances.

## Historical analogues, for scale only
Published historical research describes a substantial class of small medieval market towns around 2,000–6,000 residents (Jedwab et al., GWU working paper, https://www2.gwu.edu/~iiep/assets/docs/papers/2020WP/JedwabIIEP2020-9.pdf); estimated Pompeii near ~10,000 inhabitants within ~60 ha (https://pmc.ncbi.nlm.nih.gov/articles/PMC8773449/). Neither implies one mandatory Canopy town size, density, or institution.

## Proposed representative town (NOT CANON)
- Built-up town: **4,000 people**.
- Settled surrounding market catchment: **6,000 rural people**, total **10,000** residents.
- Indicative town footprint: **0.5–1.0 square km**, or 50–100 ha. Footprint includes roads, courtyards and some public gardens but **not full agricultural catchment**.
- This permits town guard, several clothiers, public baths, local noble house, crafts, markets and festivals without presuming large metropolis.
- Set explicit household/race/status demographics later; 10,000 human-like consumers is only an initial reference, not an actual count of food-demanding adults.
- The rural population produces some food it directly consumes. Do not count regional production sold in town and producer-consumed output as independent duplicate demands.

## Preliminary provisioning math (PROPOSED proxy)
- Human-analogue average: **2,000 kcal/person/day**, not approved racial or managmin physiology.
- 30% of purchased energy allowance unavailable to target dietary intake due to spoilage, scraps and consumption exceeding target; effective factor 0.70.
- Annual purchased-energy equivalent: `N * 2000 * 365 / 0.7`.
- Town alone N=4,000: **4.1714 billion kcal equivalents per year**.
- Region N=10,000: **10.4286 billion kcal equivalents per year**.
- Expressed as mass of hypothetical all-grain supply at 3,500 kcal/kg: approximately **1,192 tonnes town**, **2,980 tonnes region** annually. This is not actual crop mix or area requirement.
- Provisional household food-price contingency is 10% of baseline expenditure, **not** automatic increase in edible energy or crop harvest.
- Use calorie throughput only as temporary accounting until the five managmin dietary demands are defined.

## Hypothetical Leshen / Leshy (UNAPPROVED RACE)
Author is exploring a new smallest Mystaria race called **Leshen**, colloquially **Leshy**, about **2.5 feet** tall, plant people who do not eat conventional food because they subsist through photosynthesis. Their magic enables manipulation of plants and could improve Canopy agricultural productivity dramatically. Potential interaction with **clockwork harvesting machines** could narrow the gap between Canopy and Imperial (Worldspindle-enabled) food prices.

**Do not mark Leshy as canon or specify their mana/skill costs, racial stats, literal diet exceptions, magic magnitude, throughput or harvest yields until approved.** Photosynthesis still plausibly requires light, water, atmospheric carbon, mineral resources and growing space unless Mystaria magic explicitly waives these requirements.

### Leshy demand sensitivity
At 10,000 residents, using the same 2,000-kcal/person/day proxy for food-eating persons:
| Food-exempt population share | Food-consuming population | Annual purchased kcal equivalent |
|---:|---:|---:|
| 0% | 10,000 | 10.429 billion |
| 5% | 9,500 | 9.907 billion |
| 10% | 9,000 | 9.386 billion |
| 20% | 8,000 | 8.343 billion |

This changes demand only and does not include possible Leshy farm productivity. A 5% Leshy share is not a claim about demographics.

## Agricultural supply and price investigation backlog
1. Determine relative shares of free Thornguard, enslaved Bloomkin, Leshy if approved, and other races across town/countryside; household consumption differs by race and age.
2. Town housing density, landlords, civic spaces, homes and outlying villages; catchment travel times and delivery frequencies.
3. Crop calendar, land uses and proportional diet: field grain, vegetables, orchards, animal products, fishing, imports.
4. Realized yields and farm acreage before/after clockwork harvesters; distinguish labor savings from crop-yield increases.
5. Leshy plant magic: area affected, growth acceleration, regeneration, water/soil input, mana/energy costs, labor and equipment support.
6. Seed retention, animal feed, farm household consumption, spoilage, transport and merchant margins; compare gross harvest with market surplus.
7. Separate retail food price comparison against Imperium from agricultural cost comparison, accounting for wages and exchange rates.
8. Managmin food profiles and dietary ratios remain a later separate design study.

## Important scope control
Do not assign farm counts by dividing total dietary energy by an invented farm output. First choose crop/product mix, yields, farm size and actual commercial surplus. Separate a farm's capacity to feed people from its profitability and ownership regime.

## November 21 — Leshen foundation promoted to approved canon

**The foundational Leshen/Leshy race and economic role are NOW APPROVED and live in the primary codex**: [38 Leshen Foundations](https://github.com/MyStalker/mystaria-codex/blob/main/38_Leshen_Leshy_Foundations.md). The earlier "hypothetical Leshy (UNAPPROVED RACE)" section above is **superseded only for foundational identity, photosynthetic diet, Canopy homeland, plant-magic affinity, Haze sensitivity and broad Scarlands/Canopy economic role**. It remains explicitly a **proposal** regarding any percentages, productivity, crop yield, price, playable stat, or specific Magic Craft operation.

**Approved details:** ~2.5-foot Leshen/Leshy plant folk, photosynthetic/no ordinary meals; magic manipulates plants, specialization still to develop. Principal homeland Canopy; Leshy cultivation and clockwork potentially compete with Imperial Worldspindle agriculture. Scarlands horticultural and alchemical need, greenhouse confinement, hidden/subterranean cave gardens and persistent demand for rare ingredients. Leshy Haze sensitivity impairs their magic particularly strongly without rapid automatic death. Trade relationship and contested knightly protection/recovery orders are part of setting. The actual share of Leshy in our example settlement is still UNDECIDED.

## Agricultural throughput stress test (DRAFT, not endorsed yield mechanics)

If a *hypothetical* 10,000-person mixed market region without food-exempt residents requires the earlier 10.4286 billion gross-purchase-equivalent kcal per year, and **half** of purchased calories were supplied by edible grain, that grain portion is ~5.2143 billion kcal, or about **1,490 tonnes** of grain at 3,500 kcal/kg **at final consumer purchase**.

For an illustrative **80% net delivery from gross farm harvest after seed, storage, milling loss, and other upstream deductions**, gross grain harvest required is ~1,863 tonnes. Illustrative wheat yields (tonnes grain/ha cultivated/year):
| Hypothetical gross yield | Cultivated grain hectares | Typical 50-hectare *grain-area* units |
|---:|---:|---:|
| 2 t/ha | ~931 ha | ~19 |
| 3 t/ha | ~621 ha | ~13 |
| 4 t/ha | ~466 ha | ~10 |
| 6 t/ha | ~310 ha | ~7 |

The 50-ha figures represent **grain-cropped area**, NOT fully specified farm holdings. Additional vegetable, orchard, grazing, feed crop, hay, woodland, farm infrastructure and reserve lands are NOT included. A Leshy food-exempt share or different food diet modifies demand. The **80%** supply chain coefficient is entirely hypothetical and should not be confused with the consumer-side **30% food loss allowance** already included in gross-purchase demand: these are two sequential, conceptually different stages, and could overlap if the initial consumer food basket had already incorporated retailer losses. This hypothetical uses a purchased grain calorie share rather than treating grain as entire diet.

Real-world context for plausibility comparisons only: USDA 2024/25 global wheat yield around **3.57 metric tonnes per hectare** (USDA FAS July 2024), with historical medieval farm yields considerably lower and variable. Canopy magically enhanced gross yields require later author approval.

**Next investigation:** split local rural residents by occupation and food requirements; select fraction of edible energy from crops vs animal products; decide typical property sizes and farm density, share of agriculture done by free/enslaved/Leshy labor, and practical Leshy/clockwork yield enhancements. Avoid assuming an 80% food delivery rate or 50% grain calories as canon.

## November 21, 2026 — AUTHOR-SELECTED experimental town composition

**Explicitly an EXPERIMENTAL demographic model, not universal Canopy demographics or approved nutritional mechanics.** On the proposed **4,000-person reference town**:

| Population category | Share | Persons |
|---|---:|---:|
| Default enslaved population, principally Moontouched, Tidekin, Bloomkin and Duskpaws (roughly 4-ft stature overall) | **75%** | **3,000** |
| Centaurs, with horse-like food intake but **not** grass grazing | **10%** | **400** |
| Thornguard (also called Thornkin in this economic conversation) | **10%** | **400** |
| Leshen/Leshy, with no ordinary food consumption | **5%** | **200** |
| **TOTAL** | **100%** | **4,000** |

Caveat: 'default enslaved' is a social category whereas the other three are race categories. Do **not** conclude all 400 Centaurs, Thornguard, or Leshy are necessarily free; finer legal-class tables remain OPEN. This demographic mix is specified for the **town**, not yet for the 6,000-person rural catchment.

**Leshy physiology now canon:** Photosynthetic Leshy need actual **sun/light, water, and soil**. Scarlands alchemists can produce artificial sunlight in controlled environments, even subterranean gardens; this is helpful to sun-averse Vren but does not establish Vren immunity to direct artificial sunlight. Canon owner: [38 Leshen Foundations](https://github.com/MyStalker/mystaria-codex/blob/main/38_Leshen_Leshy_Foundations.md).

### Initial food-energy sensitivity (PURE MODEL ASSUMPTIONS)
For a first-pass comparison ONLY, use 1,600 kcal/day for each default smaller resident, 2,800 for Thornguard, **9,000 for Centaurs**, and 0 purchased ordinary-food kcal for Leshy. These are invented working proxies and neither biological canon nor medical nutrition guidance.

| Category | Count | Per-resident kcal/day proxy | Intended kcal/day |
|---|---:|---:|---:|
| Default small-bodied residents | 3,000 | 1,600 | 4,800,000 |
| Centaurs | 400 | 9,000 | 3,600,000 |
| Thornguard | 400 | 2,800 | 1,120,000 |
| Leshy | 200 | 0 | 0 |
| **Total** | **4,000** | — | **9,520,000** |

At 365 days and a 70% usable purchased-food factor:
- Intended consumed energy **3.4748 billion kcal/year**.
- Gross consumer purchase/household allowance **4.964 billion kcal/year**.
- Prior uniform 2,000-kcal for all 4,000 town residents yielded **4.1714 billion gross purchased kcal/year**; provisional racial composition result is **~19.0% higher**.
- Centaurs account for **37.8% of the intended dietary energy**, despite comprising 10% of population.
- This is not the **whole 10,000-person market-region** demand; rural demographics and agricultural producer consumption remain unspecified.
- Farm seed, processing losses, animal feed, transport and retailer waste must be handled separately without double-counting the existing 30% household purchase allowance.

### Centaur assumption stress test (all else unchanged)
| Centaur kcal/day | Total intended town kcal/day | Gross annual purchase-equivalent kcal |
|---:|---:|---:|
| 7,000 | 8,720,000 | 4.547 billion |
| 9,000 | 9,520,000 | 4.964 billion |
| 11,000 | 10,320,000 | 5.381 billion |

**Agricultural policy:** Because Centaurs do not graze grass as horses do, never equate their full energy intake with mere low-value pasture. Work out their actual crop/product diet and share of refined/processed food, along with costs of livestock feed separately. Leshy require water/light/soil infrastructure although they purchase no conventional meals.

**OPEN:** Percentages for rural 6,000, exact mix within the 3,000 enslaved residents, family size, physical farm yields, defined managmin diet, market demand by class, and real household wages. Original uniform-demand illustrations above are **superseded as the town's primary calculation** by this experimental demographic test, but remain useful as a comparison or for sensitivity analysis.
