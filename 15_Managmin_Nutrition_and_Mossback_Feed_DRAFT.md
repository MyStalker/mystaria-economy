# Dietary Managmins — Affinity Nutrition and Mossback Feed Profiles (DRAFT)

**Date:** 2026-11-21. **Status:** AUTHOR'S NEW DESIGN DIRECTION with assistant proposals not yet ratified. Not a canonical numeric food/deficiency law. User asked to work out five-color diet, ingredient values useful for alchemy and later cooking, and reverse-engineer Mossback food.

## Existing canonical constraints
- Five colors Red, Blue, Green, White, Black; stomach makes dietary managmins bioavailable and Anima converts them to usable mana. Moontouched have special weak/modified Anima; ordinary Moontouched need dietary managmins to live, while Warlocks draw externally for spellcasting. Source [main World and Shimmer](https://github.com/MyStalker/mystaria-codex/blob/main/01_World_and_Shimmer.md) and [Warlock Soul Anatomy](https://github.com/MyStalker/mystaria-codex/blob/main/04_Warlock_Manacraft.md).
- Main racial file still flags **Kharak red mana affinity as unresolved**. User's example that Kharak could get half or 10% of recommended *Blue* does not approve Kharak blue affinity or settle their innate mana affinity.
- Approved Mossback is a Green-affinity Starspawn concept. Approved wild 25% and captive 75% survival to age 20; one month seed development. Mossback 10t working growth curve in study 13; Sunrush approved native bulk forage in main canon, while Sunlace Clover and Stonepod Reed still need independent approval as names/species.
- Food energy/protein/minerals/milk, managmins, alchemical ingredient extraction yield, and active mana are different accounting concepts. No calories-to-managmins conversion approved.

## User-proposed nutritional ideal (not yet final approved canon)
- Single-affinity organism's **ideal** dietary managmin allocation: **50% own affinity color**, and the other **50% divided equally**, i.e. **12.5% each remaining color**.
- Moontouched: **20% per color**, with **broader tolerance** to deviations.
- This describes **optimum**, not a severe requirement. A Kharak could be entirely healthy with **~50% of ideal Blue intake**, whereas ~10% may begin causing a deficiency if chronic. Numeric thresholds and penalties not approved.

## Recommended interpretation of tolerance (assistant proposal, not user approval)
Track actual daily *amount* of each color relative to the creature's recommended daily amount (RDA), not just the shares of a low-total diet. Example: for a 100-managmin/day Green-affinity creature, target Green50 and each other color12.5. 50% of Blue RDA is 6.25 Blue/day, not 6.25% of its total intake.
- >=100% of color RDA ideal; 50–99% often healthy; 25–49% marginal if sustained; 10–24% serious deficiency risk over time; <10% dangerous if sustained. No instant debuffs, damage or MP reduction authorized. Species-specific tolerances and time windows open.
- Nutrition needs an independent *total daily target* or an alternative mana-demand scaling rule and distinct bioavailability. Eating more total managmins can alter absolute intake despite profile imbalance. One color does not automatically replace another. Oversupply, storage, excretion/toxicity, age, pregnancy/Bloom, high spellcasting, dietary digestion, and Leshy photosynthetic acquisition remain open.

## Draft forage managmin shares (NOT total units per kg)
| Ingredient | Red % | Blue % | Green % | White % | Black % |
|---|---:|---:|---:|---:|---:|
| Sunrush Grass | 5 | 10 | 65 | 12 | 8 |
| Sunlace Clover (name still proposed) | 10 | 18 | 48 | 16 | 8 |
| Stonepod Reed (name still proposed) | 8 | 20 | 35 | 30 | 7 |
| Unspecified concentrated insect feed (just a modeling ingredient) | 45 | 5 | 10 | 5 | 35 |

At the earlier unapproved mix **70% Sunrush /25% Clover /5% Reed**, equal total managmins per dry-mass unit *for the comparison only*, aggregate shares are **Red 6.4%, Blue 12.5%, Green 59.25%, White 13.9%, Black 7.95%**. Relative to ideal Green affinity shares 12.5/12.5/50/12.5/12.5, Red is ~51.2% of proportional ideal and Black ~63.6%; both might be compatible with health if absolute intake is adequate and color tolerance is broad. This **cannot independently establish health** because total amount of each color/kg and daily RDA remain unapproved. Insect meal may be more concentrated in managmins and should not be modeled solely by equal-weight share without a potency scalar.

## Three-part item schema proposed for all future foods and alchemy
1. **Total managmin density per standard quantity** (e.g. managmin units per kg edible *dry material*), allowing plant-to-plant contrast.
2. **Five-color composition** (five absolute counts summing to total density, not just percentages), useful for potion ratio recipes; distinguish raw item content from extracted/usable portion.
3. **Physical food nutrition** (digestible energy, protein, minerals/water, spoiled/inedible fraction) separate from magical chemistry; also consider cooking changes, extraction losses, and preservation.

Example pure mathematical placeholder: if 1 kg of a fictional ingredient contains 40 total managmins and profile 5/10/65/12/8%, its counts are Red 2, Blue 4, Green 26, White 4.8, Black 3.2, fractional managmin representation only if fractional units allowed. Avoid selecting actual density or rounding conventions before approval.

## Research / next design choices
- Decide whether author's 50/12.5 ideal and 20% Moontouched ideal are **explicitly approved** as general nutrition canon.
- Choose *absolute daily targets* in units scaled to body size, growth, Anima needs and possibly spell usage, or a coarse low/medium/high diet tier; decide whether ingredient alchemy managmins use same units as diet and how cooking affects them.
- Define deficiency progression without penalizing ordinary mixed diets, and separate 50%-of-color-target from 50%-of-diet composition.
- Determine realistic absolute elemental supply of bulk grass and concentrated ingredients; carnivorous red-managmin plant direction cannot be inverted to claim noncarnivorous grasses are Red-rich without explanation.
- Special photosynthesis route for Leshy and any Mossback solar managmin acquisition is unresolved, even where solar *energy* is counted.
- Build nutrient balancing by optimization only after ingredient densities, safety limits and target RDAs are decided; keep all ratio and mass values explicit.


## 2026-11-21 — AUTHOR CORRECTION: MANAGMINS ARE ALL NUTRITION; KHARAK RED AFFINITY

Approved: Kharak have **Red mana affinity**, superseding older racial notes of unresolved color; there are **no independent in-world calories, protein, vitamins or nutritional minerals**, because dietary **managmins replace all those requirements**. These terms in older economic models are real-world modeling analogues only and cannot become a separate additional nutritional ledger. Approved energy unit: **1 managmin = 1 food Calorie (1 kcal)** as an external calibration. This is distinct from the physical science small calorie. No food-density value automatically follows without a reference energy per mass. 

Napier grass at published average 8.7 MJ metabolizable energy/kg dry matter gives a **PROPOSED** Sunrush density ~2,079 managmins/kg dry or ~940 per dry lb, and with hypothesized 20% dry fraction ~190 per fresh lb. The previously *unapproved* Sunrush composition 5% Red/10% Blue/65% Green/12% White/8% Black implies approximately 47/94/611/113/75 managmins per 940-managmin dry lb. Density, color profile and hydration are NOT approved just by approving the unit. Reference: https://pmc.ncbi.nlm.nih.gov/articles/PMC10682400/ . Published experimental adult 75kg daily dry-feed equivalent would imply ~156k consumed managmins/day for an all-Sunrush density-equivalent ration, before optional photosynthetic inputs, milk, mixed feed densities and growth modifiers. **No official total daily RDA is settled.** Review draft [15 Managmin Nutrition](15_Managmin_Nutrition_and_Mossback_Feed_DRAFT.md) for numerical choices awaiting approval.


## November 21, 2026 — MOSSBACK THREE-COLOR PHOTOSYNTHESIS AND REBALANCED FORAGE (NEW PROPOSAL)

**New author's ecological direction:** Mossback photosynthesis supplies **Green, Red and White managmins**. The precise fractional mix and absolute rate are NOT explicitly author approved. **Assistant proposed 70% Green, 15% Red, 15% White** of solar-generated managmins. Use the previously approved *working* assumption that solar output supplies 50% of total daily managmin-energy-equivalent need; this biological fraction remains revisable and is not permission for unlimited free intake. Photosynthetic output creates these nutritional managmins for the Mossback itself, rather than generating generic extra caloric energy in a separate nutritional system. Sunlight, time, water and environmental conditions still limit production; exact physical mechanism and alchemical harvesting of sunlight-derived managmins are OPEN.

Under the author's still-to-be-ratified nutritional ideal for Green-affinity organisms (**50% Green + 12.5% each other color**), each 100,000 total daily managmins would comprise 50,000 sunlight-derived (Green35,000/Red7,500/White7,500) plus 50,000 from food. Hence the **ideal food-only composition** must be **Red10%, Blue25%, Green30%, White10%, Black25%**. A 50,000-managmin daily ration then supplies R5,000/B12,500/G15,000/W5,000/K12,500. Verify total managmins, not just shares; do not invent ordinary protein/vitamin/mineral requirements alongside the managmins.

**Proposed revised source ingredient catalog (NOT approved as final plant values):** Counts below are total *bioavailable* managmins per one **dry pound of edible plant**, calibrated to real-world grass energy proxy using the approved **1 managmin per dietary food Calorie**. Other plant densities are speculative, not measured/approved botanical physiology.

| Plant | Total managmins per 1 dry lb | Red % | Blue % | Green % | White % | Black % | Color counts (R/B/G/W/K) per dry lb |
|---|---:|---:|---:|---:|---:|---:|---|
| Sunrush Grass | 940 | 5 | 24 | 33 | 9 | 29 | 47/225.6/310.2/84.6/272.6 |
| Sunlace Clover (species name still proposed) | 1200 | 20 | 29 | 22 | 11 | 18 | 240/348/264/132/216 |
| Stonepod Reed (species name still proposed) | 800 | 20 | 12 | 35 | 30 | 3 | 160/96/280/240/24 |

At the existing **70 lb Sunrush +25 lb Sunlace +5 lb Stonepod** proportions per 100 dry pounds, calories-equivalent total **99,800 managmins**, or **998 managmins per dry pound blended feed**. Calculated weighted blend percentages: **Red10.11%, Blue25.02%, Green29.77%, White10.44%, Black24.65%**. These are extremely close to the food-only ideal **10/25/30/10/25**, without adding an unapproved fourth food. Counts per 100 dry pounds: Red10,090 / Blue24,972 / Green29,714 / White10,422 / Black24,602, sum 99,800. Retain exact counts or decimal values before rounding; recipes may need integer rounding policy later. Higher Black in Sunrush than older speculative 8% is deliberate new proposal: rapid-cycle rhizomes/litter recycling may underpin a high Black managmin fraction without being carnivorous, consistent with nonmoral color meanings; no invented black magical power or fertilizer mechanics.

**Adult consumption illustration:** a hypothetical 10,000kg Mossback in the approved economic study consumes ~75 kg dry-feed equivalent/day when 50% solar credit is assumed. 75kg = ~165.35 dry lb/day. At 998 managmins/lb blended forage, this provides ~**165,016 food managmins/day**; under exactly 50% solar model, sunlight also supplies ~165,016/day, for total ~**330,032/day**. Food provides ~R16,683/B41,290/G49,132/W17,228/K40,670; solar provides ~R24,752/G115,511/W24,752; totals are approximately **R41,436/B41,290/G164,643/W41,980/K40,670**, within about 2% of theoretical ideal R41,254/B41,254/G165,016/W41,254/K41,254. No double-counted physical calories, protein, minerals or vitamins. Exact daily requirement is still a model, not established for all ages/physiological conditions; dry matter assumptions and Sunrush fresh moisture still OPEN.

**Status:** User has offered new RGB/Green-Red-White solar output concept; this document records assistant's unapproved fraction and revised color/density proposals. Do not promote detailed composition, precise solar rate or Mossback managmin RDA to canon absent explicit author approval. Earlier draft Sunrush 5/10/65/12/8 and Sunlace 10/18/48/16/8 and Stonepod 8/20/35/30/7 are SUPERSEDED AS WORKING PROPOSALS by these revised profiles, preserved only historically. Existing canonical 25% vs 75% survival and seed hatch timing unchanged.
