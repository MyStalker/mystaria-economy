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
