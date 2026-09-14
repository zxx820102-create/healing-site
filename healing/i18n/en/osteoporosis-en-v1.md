---
title: "Osteoporosis Canon v1 (English v1) — settle the bone's account before the fracture"
created: 2026-09-13T02:57:03.777+08:00
updated: 2026-09-13T04:54:29.251+08:00
language: en
source_canon: docs/healing/osteoporosis-canon-v1-20260912.md
translation_version: 1
translated_date: 2026-09-13
epistemic_discipline: preserved
map: data/healing/osteo-map-20260912.json
source_canon_index: docs/theories/CANON-INDEX.md
status: canon-candidate
glossary: docs/healing/i18n/en/glossary-v1.md
translator_note: "Transcription, not authorship: every PMID, number, conclusion and falsification item is carried over verbatim from the source canon; source downgrades and the UNKNOWN/dropped-trial list preserved as-is; no medical content added. Epistemic labels preserved as-is (FACT / FACT·relayed / MODEL / INFERENCE / UNKNOWN — prefer an empty cell to an invented one; zero-unilateral-promotion). The source contains no in-body emergency hotline numbers; graph anchors (agc:, home:, joint:, fem:, men:, thy:, fa:, uro:) are kept in the source language of the neighboring graph nodes — including the Chinese-named anchors home:氡 and home:CO报警器, with this note serving as the translator gloss (radon; CO alarm). Drug content stays at positioning, two-sided risks and 'when to return to your doctor' exactly as in the source — no prescription doses. This volume is not medical advice — discuss with your doctor."
---

# Osteoporosis Canon v1

> **In one sentence**: Osteoporosis is "silent skeletal bankruptcy" — the bone quietly pawns its calcium for decades and only speaks up at the first fragility fracture, while the bill for a hip fracture is priced at "15–30% mortality within one year." This canon's entire skeleton is one line: **settle the account before the fracture** — screening, nutrition, exercise, and fall prevention, four cheap things, come first; the honest drug account comes after.
>
> **How to read this volume**: ① epidemiology in real numbers → ② risk stratification and screening → ③ nutrition and exercise (fall prevention is the first lever) → ④ the honest drug account → ⑤ the men's dedicated face → ⑥ red flags → ⑦ the falsification face, seven items. Epistemic states labeled item by item; UNKNOWNs listed openly (Appendix A).
>
> **Interlink conventions**: aging-muscle and screening interlink `agc:` (aging-care volume) · home environment and the ~100-yuan life-saving cards interlink `home:` (dwelling volume) and the L5 whitepaper (`docs/healing/upstream-whitepaper-v1.md`) · the pain-immobility vicious cycle and supplement myths interlink `joint:` (bone-and-joint volume) · the whole menopause arc interlinks `fem:` (women's volume) · the men's face interlinks `men:` (men's volume) · thyroid function and bone interlink `thy:` (thyroid volume) · do-not-move-at-trauma-scene interlinks `fa:` (first-aid volume) · prostate ADT interlinks `uro:psa-dilemma` (urology volume · the PSA dilemma).

---

## ① Epidemiology-in-real-numbers face: the scale of the bankruptcy

**The global framing (FACT)**
- The International Osteoporosis Foundation (IOF) framing: **across the remaining lifetime, about 1 in 3 women and 1 in 5 men aged 50+ will experience an osteoporotic fracture**. Source: the IOF website's epidemiology page (osteoporosis.foundation, citing Kanis et al. long-term risk studies); Sözen et al. 2016 review relays the same framing. Note this is a **proportion of fractures occurring**, not a prevalence — far larger than the "diagnosis rate," because most osteoporosis is never diagnosed.

**The China framing (FACT·relayed · official survey)**
- The first national China osteoporosis epidemiological survey, released in 2018 by the National Health Commission: **prevalence 19.2% in people aged 50+ (women 32.1% · men 6.9%); 32.0% in people aged 65+, of whom women 51.6%**. The same survey: low bone mass in 57.4% of those 50+ (women 67.6%). That is: **about 1 in every 3 Chinese women over 50 has the disease; past 65, more than half of women**. The 65+ male breakdown was not fully relayed by an authoritative page this round (UNKNOWN, Appendix A).
- Interpretation (INFERENCE): the prevalence numbers sit far below the IOF fracture proportions — the gap between them is the scale of "silent fractures + undiagnosed disease," which is exactly why the screening chapter exists.

**Hip fracture: the endpoint priced in life and death (FACT · multi-source consistent)**
- **Mortality within 1 year after hip fracture is about 15–30%**: Panula et al. 2011 (Finnish population cohort) reported 27.3%; Downey et al. 2019's systematic review reported 22% (noting the classic 30% framing is outdated yet still startling); the 2025 review framing is 15–30%. **Interlink with the L5 whitepaper**: `docs/healing/upstream-whitepaper-v1.md`, "mortality within 1 year after hip fracture about 15–30% [FACT · multi-source consistent]" — the fall side writes fractures; the consequence side writes life and death.
- **Older men's 1-year mortality after hip fracture is higher than women's of the same age** (FACT · bibliographic direct verification): Olofsson et al. 2025 (Swedish 85+ population): women >20%, men >30%. The men's dedicated face (§⑤) is the other side of this coin: lower prevalence in men, but heavier consequences once fractured — "low prevalence" never means "low risk."
- A 2026 preprint meta pools 1-year mortality at 21.8% (preprint framing; side evidence only, not entering the main-text claim).

**Vertebral compression fracture: the silent majority (FACT phenomenon + MODEL framing)**
- The vertebrae are the most common site of osteoporotic fracture, and **a large share are silent fractures**: StatPearls and a 2025 study of older adults (previously unknown vertebral compression fractures found on health checkups, of which over 37% fully asymptomatic) both confirm "no symptoms ≠ no fracture" (FACT).
- "About 2/3 of vertebral compression fractures are never clinically diagnosed" is a widely relayed consensus framing (MODEL · this canon did not find a single original bibliographic record for direct verification; relayed status labeled honestly). Its two consequences: height loss/kyphosis gets written off as "normal aging," and the starting point of treatment gets postponed by an entire fracture cycle.

**The fracture chain (MODEL · aggregate framework)**
Fragility fracture → disability/bed rest → pneumonia, thrombosis, delirium → death or care dependence; meanwhile "pain → fear of moving → further bone and muscle loss → even easier refracture" forms a second vicious cycle (interlink with `joint:vicious_cycle`, the pain-immobility cycle, and `agc:fall_fracture_chain`, the fall-fracture chain). The entire meaning of osteoporosis treatment is to cut this chain at its most upstream point.

---

## ② Risk-stratification face: T-score, FRAX, who should be checked

**The three-band T-score ruler (FACT · WHO 1994)**
The WHO study group's 1994 definition (Kanis et al., Osteoporos Int, PMID 7696835; measured by DXA dual-energy X-ray at the lumbar spine/femoral neck, compared against peak bone mass of healthy young women):
- **T ≥ -1.0**: normal;
- **-2.5 < T < -1.0**: low bone mass (osteopenia);
- **T ≤ -2.5**: osteoporosis;
- When a **fragility fracture of the hip or vertebra has already occurred**, the case belongs to the severe/treatment threshold regardless of T-score (consensus framing, FACT·relayed).
Boundary honesty: T ≤ -2.5 is a **diagnostic cut-point**, not a **treatment cut-point** — treatment decisions combine fracture risk and FRAX, not the T-score alone (MODEL).

**FRAX: positioning and boundaries (FACT tool exists + MODEL boundaries)**
- Positioning: FRAX (Kanis et al. 2008, Osteoporos Int, PMID 18292978; tool review Schini et al. 2024, PMID 37874461) synthesizes age, sex, height and weight, prior fracture history, parental hip-fracture history, smoking, alcohol, glucocorticoids, rheumatoid arthritis, secondary osteoporosis, and femoral-neck T-score into the **10-year probability of a major osteoporotic fracture and of hip fracture** — its value is separating "T-score just past the line but risk very low" from "T-score not yet at -2.5 but risk already high"; the latter is precisely the majority who should be treated and are not.
- Boundaries (MODEL, stated honestly): ① it does not take fall risk and fall exposure into account — yet falls are the trigger of the fracture chain; ② country models (including the China model) carry population-calibration limitations; absolute values across populations need caution; ③ the output is a probability, not a verdict — the tool does not replace clinical judgment and individualized discretion.

**Who should be checked (FACT · guideline framing)**
- Women: **routine DXA screening from age 65** (USPSTF 2018, JAMA, PMID 29946735, Grade B; the 2025 update maintains the screening recommendation for women ≥65, PMID 39808425); **postmenopausal women under 65 with risk factors move earlier** (prior fragility fracture, parental hip-fracture history, smoking, low body weight, long-term glucocorticoids, etc.).
- Men: every USPSTF edition has judged routine screening in men "evidence insufficient"; clinical guideline consensus (Endocrine Society's male osteoporosis guideline et al., references in Appendix B) recommends **screening from ≥70, earlier at 50–69 with risk factors (including ADT exposure · see §⑤)**. Read this carefully: **it is not "men don't need screening" — it is "men get screened less."** The consequences of the two sentences are completely different.
- The test itself: DXA is non-invasive, with extremely small radiation, done in minutes (FACT·relayed); the real barrier was never the technology — it is "never thought to check."

---

## ③ Nutrition and exercise face: four cheap things

**Calcium: food first (FACT · official framing)**
- Per the Chinese Dietary Reference Intakes (2023 edition): adults' recommended calcium intake is **800 mg/day, 1000 mg/day for those 50+, tolerable upper limit 2000 mg/day** (official framing, relayed).
- The order must not be inverted: **dairy, soy products, leafy greens, nuts and other foods first; supplements only to fill the gap** — food brings calcium together with protein, vitamin K, magnesium and other synergistic nutrients; a supplement fills the mouth-gap, it does not replace the meal. Milk's calcium concentration is tens of times bone broth's (see ⑦ falsification item 1).

**Vitamin D: the honest grade (FACT and MODEL layered; this canon does not flatten them)**
- **Deficiency is genuinely widespread** (FACT): about 1 billion people worldwide are vitamin D insufficient/deficient (StatPearls framing); under the harmonized serum 25(OH)D<30 nmol/L standard, global prevalence is about 15.7% (2023 global pooled analysis).
- **But the benefit evidence for "universal supplementation" is negative** (FACT · bibliographic direct verification): the VITAL trial (LeBoff et al., NEJM 2022, PMID 35939577): in generally healthy mid-life and older adults, daily 2000 IU vitamin D3 **did not significantly reduce total or hip fractures**. A 2023 systematic review points the same way: vitamin D supplementation in older populations has no beneficial effect on falls or fracture incidence (Octary et al., retrieved record). The brief's named "ODYSSEY" trial could not be located as a vitamin D fracture RCT across two bibliographic searches — dropped per discipline, recorded honestly (Appendix A); this item's negative evidence is carried by VITAL + the systematic review, and the conclusion is unaffected.
- **The honest-grade conclusion (MODEL)**: ① the general population should not expect bone returns from indiscriminate high-dose supplementation; ② **for people already diagnosed with osteoporosis and started on drug treatment, vitamin D and calcium are part of the treatment plan** (ensuring safe use of antiresorptives, preventing hypocalcemia) — supplement as prescribed; ③ cutaneous synthesis is realistically constrained by latitude, season, sun-protection habits, and age (declining skin synthesis); testing (25(OH)D) should be used rationally — check when there is an indication, do not make it an indiscriminate routine checkup item (MODEL). Interlink with `agc:calcium_vitd_qty` (aging-care volume · the calcium-and-VD quantity card).

**Exercise: weight-bearing + resistance (FACT review on record + MODEL effect sizes)**
- Cochrane systematic review (Howe et al. 2011, PMID 21735380): exercise interventions in postmenopausal women have a **small but consistent positive effect** on bone mineral density, with combined programs (weight-bearing aerobic + resistance) carrying the most coherent evidence (effect-size framing MODEL).
- The mechanism framing (MODEL): bone is tissue rebuilt by load — longitudinal weight-bearing (walking, stair climbing, dancing) and progressive resistance (bands, machines, body weight) give bone the signal "it must get stronger"; swimming/cycling are good for the heart and lungs, but **do not count as weight-bearing** and cannot protect bone alone.
- Starting at any age still pays (see ⑦ item 4); interlink with the aging volume's muscle-strength-as-currency theory (`agc:resistance_training`, `agc:muscle_currency`): **muscle is bone's shadow** — one resistance-training purchase buys two assets.

**Fall prevention: the first lever (FACT + interlinks)**
- Fracture = bone strength × fall exposure. Improving bone strength is counted in years; **reducing falls is counted in weeks** — this is the whole system's most cost-effective lever (FACT: Cochrane review confirms exercise interventions reduce fall rates in older adults, Gillespie et al. 2012, PMID 22972103; multi-component home environmental assessment and modification is equally effective).
- On the home side, interlink the L5 whitepaper's **three ~100-yuan life-saving cards** (`docs/healing/upstream-whitepaper-v1.md`, "radon test kit, CO alarm, bathroom non-slip mat + load-bearing grab bar"): the bathroom non-slip mat and load-bearing grab bar are the direct solution to the fall-fracture chain; the dwelling volume's radon and CO cards are at `home:氡`, `home:CO报警器` (radon doubles as a lung-cancer face — one dwelling, two diseases prevented).
- The quick-wins checklist (MODEL · consensus framing): night lights and the three-step rise (sit 30 seconds after waking, then stand), non-slip slippers, clearing floor obstacles, regular vision checks, and reviewing fall risk when using sedatives/blood-pressure/glucose-lowering drugs (interlink with the aging volume's `agc:deprescribing` deprescribing card).

---

## ④ The honest drug account: every class written with both faces

> General rule: the choice, dose, and duration of osteoporosis drugs are the prescriber's domain; this face writes only **positioning, two-sidedness, and when one must return to the doctor**.

**Bisphosphonates: the first-line oral/intravenous choice (FACT · consensus)**
- Positioning: alendronate, risedronate (oral) and zoledronic acid (annual intravenous infusion) are most guidelines' first-line antiresorptives, significantly reducing vertebral and hip fracture risk (FACT·relayed).
- The oral two-face (FACT·relayed): esophageal irritation/reflux-like symptoms are real — taking on an empty stomach with plain water and staying upright 30+ minutes is the discipline; a history of esophageal stricture does not take the oral path. This face is usually managed by correct dosing technique, not by abandoning treatment.
- **Osteonecrosis of the jaw (ONJ): the real incidence is extremely low — written as it is** (FACT · bibliographic direct verification): the realistic estimate of ONJ in osteoporosis-dose oral bisphosphonate populations is about **0.001%–0.01% (one in a hundred thousand to one in ten thousand order)** (Lo et al. 2009, PMC record in Appendix B); the risk under high-dose intravenous regimens for cancer metastasis is far higher (re-stratified by model, MODEL). Companion discipline: tell the dentist the medication history before planned major oral surgery. **A below-one-in-a-thousand risk against a background of 15–30% one-year hip-fracture mortality — the scale's direction is clear** (INFERENCE; transparent arithmetic at ⑦ item 5).

**Denosumab: the discontinuation rebound is the key safety information (FACT · bibliographic direct verification)**
- Positioning: a RANKL inhibitor, one subcutaneous injection every six months, strong antiresorptive potency, one of the pathways usable in renal impairment (FACT·relayed).
- **The face that must enter the canon**: after denosumab **discontinuation, bone-turnover rebound and rapid bone loss occur, with multifocal vertebral-fracture rebound cases on direct bibliographic record** (Tsourdi/Anastasilakis et al. case series, JCEM 2017 et al., PMID 28240371; review in Appendix B PMC). Meaning: **denosumab has no free state of "stopped is stopped" — stopping or switching must be arranged by a doctor as a sequential antiresorptive bridge** (bridge strategy details MODEL); using the full cycle and transitioning as prescribed is this drug's lifeline.

**The anabolic agents: teriparatide and romosozumab (FACT · bibliographic direct verification)**
- Positioning: people at **very high fracture risk** (multiple fragility fractures, extremely low T-score, still fracturing on antiresorptive therapy) take the "anabolic first, antiresorptive after" sequential strategy (MODEL · consensus direction).
- Teriparatide (a parathyroid hormone fragment; Neer et al. 2001 NEJM, PMID 11346808: significantly reduces new vertebral fractures); romosozumab (a sclerostin antibody; the FRAME trial, Saag et al. 2016 NEJM, PMID 27641143: reduces fracture risk in postmenopausal women). The two faces: romosozumab showed a cardiovascular event imbalance in the ARCH controlled trial (MODEL · label-warning framing: not used after recent myocardial infarction/stroke); teriparatide carries a label warning from a rat osteosarcoma signal (MODEL · label framing, relayed with limited human evidence). Duration is limited and doctor-managed — these are the "heavy artillery," not routine starting drugs.

**Glucocorticoid-induced osteoporosis: intervene at ≥3 months (FACT · guideline direct verification)**
- Long-term glucocorticoids are the leading cause of iatrogenic osteoporosis. The American College of Rheumatology guideline (2017 edition PMID 28585373; 2022 update PMID 37845798) framing: **anyone expected to take prednisone ≥2.5 mg/day for ≥3 months should have fracture risk assessed and prevention/treatment started** (the intervene-at-3-months guideline framing is FACT).
- The common error is treating steroid-related osteoporosis as "incidental and unavoidable" — it is **the removable share of the risk** (INFERENCE): people on steroids should complete Chapter ②'s screening process all the earlier.

---

## ⑤ The men's dedicated face: low prevalence is not low risk

- **Prostate cancer ADT treatment = high osteoporosis risk** (FACT · bibliographic direct verification): Shahinian et al. (NEJM 2005, PMID 15647578): fracture risk rises with treatment duration in prostate cancer populations on androgen deprivation therapy (ADT). Once the drug removes androgen's protective effect on bone, loss accelerates — **ADT exposure by itself is an indication for earlier screening and intervention** (MODEL · guideline-consensus direction). The PSA dilemma itself interlinks at `uro:psa-dilemma` (urology volume · PSA chapter) and `men:redflags` (men's volume red flags).
- **Men's screening deficit, stated honestly** (MODEL · multi-source consistent): screening evidence insufficient for men (USPSTF framing) + symptoms ignored + low care-seeking — the triple overlay lands as: men's diagnosis and treatment rates significantly below women's, while **1-year mortality after hip fracture is actually higher than women's** (§①, Olofsson 2025: 85+ men >30% vs women >20%). The men's face's full expansion interlinks the men's volume (`men:`).
- The fracture red flags (sudden mid-back pain, height loss) apply equally to men and are more easily missed — "men don't get osteoporosis" is the most expensive misbelief in the book (joined at ⑦ item 3).

---

## ⑥ Red-flag face: when these four appear, don't wait for the next checkup

1. **Sudden mid-back pain** (thoracolumbar), worse on turning over, rising, or coughing — especially with only trivial injury or none at all: beware an acute vertebral compression fracture (FACT·relayed; the IOF explicitly names back pain and height loss as possible first symptoms of vertebral fracture).
2. **Height loss >4 cm** (or >6 cm against one's tallest young-adult height, the extended framing): the screening trigger line for vertebral fracture (the UK framing triggers vertebral morphology assessment at 4 cm, MODEL · relayed; the height-loss–vertebral-fracture association has direct bibliographic verification: Xu et al. 2010/2011, PMC records in Appendix B).
3. **Worsening kyphosis / progressive spinal curvature**: the accumulated shape of multiple vertebral compressions — equally triggers VFA (vertebral fracture assessment) (MODEL).
4. **Unable to stand and bear weight after hip/groin trauma**: seek care immediately; the classic signal of hip fracture, with no delay allowed (FACT · first-aid common-sense framing; trauma-scene handling interlinks `fa:do_not_move` — immobilize first, move minimally, call professional transport).
- Addendum: a prior fragility fracture in adulthood (a low-trauma wrist/spine/hip fracture) is itself a red flag — not "already finished healing," but "risk already proven."

---

## ⑦ The falsification face, seven items: each with its falsifier (what evidence would overturn it)

> Format: claim → verdict (this canon's position) → falsifier (if the following evidence appears, the position must be corrected and written back). Counter-example history is never deleted.

1. **"Bone broth builds calcium" — refuted (MODEL)**. Bone broth's calcium content is far below dairy's (the leached calcium is minimal — the fat and purines, though, are quite real); the milky white comes from emulsified fat, not calcium; the true calcium path = dairy/soy products/leafy greens. Structurally interlinked with the bone-and-joint volume's "supplement myths" (`joint:supplements`; the joint volume's numbering referenced by the canon index; the men's-health volume's cross-reference table lists the bone-and-joint volume as an independent volume). **Falsifier**: if authoritative measured data showed calcium per 100 ml of bone broth reaching half or more of milk's, this item must be rewritten.
2. **"Calcium supplements cause kidney stones, so don't supplement" — refuted · both faces stated (FACT+MODEL)**: dietary calcium intake is **negatively** correlated with stone risk (Curhan et al. 1993 NEJM, bibliographic direct verification — high dietary calcium actually lowers stone risk); the supplement side is inconsistent — a systematic review of supplements and stone risk in osteoporosis populations suggests a small and uncertain risk (Candelas et al. 2012, PMID 23137489; MODEL). The correct posture: **food first, dose per recommendation (1000 mg/day total dietary intake for 50+), total below the 2000 mg upper limit**, and those with a stone history tell their doctor before deciding on supplements. **Falsifier**: if routine-dose supplements in RCTs caused a significant, multiplied rise in stone incidence, this item's position must tighten to "supplements with caution in stone formers."
3. **"Osteoporosis is an inevitability of aging — no need to treat" — refuted (FACT)**. The inevitability thesis collides with three fact sets: ① drug therapy has mature bibliography with fracture-endpoint benefit (Chapter ④'s lines); ② fall prevention and nutrition/exercise are operable variables (Chapter ③); ③ the decisive difference of "treat or not" lands on hip fracture's 15–30% one-year mortality (§①). What ages is age; what is preventable is fracture. **Falsifier**: if high-quality RCT evidence appeared showing current first-line drugs do not reduce any clinical fracture endpoint, this item would be rewritten — all evidence to date points the opposite way.
4. **"Starting exercise too late is useless" — refuted (FACT)**. The Cochrane review enrolled postmenopausal women of all ages: exercise has a small but consistent positive effect on bone mineral density (PMID 21735380); exercise interventions in older adults reduce fall rates (PMID 22972103) — the fall-rate reduction holds in the oldest bands too. Starting at any age still buys the twin returns of "bone loading signal + lower fall risk"; only from the oldest start does the return cash in faster (INFERENCE). **Falsifier**: if RCTs showed exercise ineffective on both bone density and fall endpoints in the oldest age group, this item would be rewritten by age band.
5. **"Bisphosphonates damage bone — don't take them" — refuted · both faces written together (FACT)**. One face is the real-world ONJ rate of about 0.001%–0.01% at osteoporosis doses (below the one-in-a-thousand scale) and the extremely low rate of atypical femoral fracture (the latter not separately bibliographically verified this round; framing MODEL · Appendix A); the other is the significant reduction in vertebral/hip fracture risk against hip fracture's 15–30% one-year mortality background (§①④). Transparent arithmetic (INFERENCE): a one-in-ten-thousand-order serious-adverse-event rate set against a background mortality risk counted in tens of percentage points — the direction is not ambiguous. The main-course discipline: dental check before starting, take on schedule, reassess per course (long-term drug-holiday strategy is the doctor's call). **Falsifier**: if long-course osteoporosis-dose cohorts showed the combined serious-adverse-event rate approaching or exceeding the mortality reduction corresponding to the fracture benefit, this position must be re-estimated.
6. **"Some sun is all you need — ignore the rest" — refuted (MODEL+FACT)**. The reality constraints, three in a row: latitude and season (high-latitude winter synthesis near zero), sun-protection habits (sunscreen itself blocks synthesis), declining skin synthesis efficiency in older adults (MODEL · relayed); and "universal supplementation has bone benefits" is equally pinned down by VITAL's negative result (§③) — so the right answer is neither "enough sun suffices" nor "everyone takes large doses," but **food first + those at risk supplement as prescribed + testing used rationally** (check 25(OH)D when there is an indication or clinical suspicion; no indiscriminate blanket screening). **Falsifier**: if cohorts showed >90% of regular sun-exposed people reaching winter 25(OH)D adequacy, correlated with fracture endpoints, this item would raise sun exposure's weight.
7. **"Massage and bone-setting can knead a compression fracture back" — refuted · red-line grade (FACT · common sense + interlinks)**. An acute vertebral compression fracture is a fracture; violent massage/tuina or bone-setting may worsen vertebral collapse and neurological injury — after trauma-related back pain, immobilize first and confirm on imaging first, and only then discuss treatment; the trauma-scene iron rules interlink `fa:do_not_move` (first-aid volume · do-not-move principle) and `fa:call_120_only`. Vertebral augmentation (bone cement) applies to those with persistent pain, assessed by a doctor against indications (MODEL). **Falsifier**: if high-quality RCTs proved massage safe and endpoint-improving in acute VCF, this item must be rewritten — existing common sense and pathology all point the opposite way.

---

## Appendix A: the UNKNOWN and downgrade list (prefer an empty cell to an invented one)

1. **The "ODYSSEY" trial could not be located**: two rounds of bibliographic searching hit no vitamin D fracture RCT named ODYSSEY (returns were all vitamin D meta-analyses on depression faces, etc.) → dropped per discipline; vitamin D's general-population negative evidence is carried by VITAL (PMID 35939577) + the 2023 systematic review. If the owner or a later lane supplies the name's true identity, backfill this canon and upgrade this item.
2. The China 2018 survey's **65+ male prevalence breakdown** was not fully relayed by an authoritative page (only the 50+ male 6.9% and 65+ female 51.6% figures obtained) → left empty.
3. **Atypical femoral fracture (AFF) incidence** was not separately bibliographically verified this round → mentioned at ⑦5 only in a MODEL framing, no number given.
4. "About 2/3 of vertebral compression fractures are never clinically diagnosed" is a consensus relayed framing (MODEL); no single original record was locked.
5. The Cochrane exercise review's **effect-size numbers** and the falls review's **specific reduction percentages** were not extracted item by item → qualitative statements only.
6. Prostate ADT's **specific risk-ratio numbers** for fracture risk were not extracted from abstracts → direction only (rises with treatment duration, FACT).
7. The 4 cm height-loss trigger line: UK guideline framing relayed via second-hand sites (MODEL); original page not directly verified.

## Appendix B: source index (bibliographic grade · all verified via TinyFish bibliographic search)

| # | Topic | Position | Epistemic state |
|---|------|------|--------|
| 1 | IOF 1-in-3 · 1-in-5 framing | osteoporosis.foundation epidemiology page; Sözen 2016 review (PMC5335887) | FACT |
| 2 | China 2018 epidemiological survey | NHC release · People's Daily Health 2018-10-19 and official-media relay pages | FACT·relayed |
| 3 | Hip-fracture 1-year mortality 27.3% | Panula 2011 (PMC3118151) | FACT |
| 4 | Hip-fracture 1-year mortality 22% (30% framing outdated) | Downey 2019 systematic review (PMC6428998) | FACT |
| 5 | Hip fracture 15–30% and higher in men | Andaloro 2025 review (PMC12285999); Olofsson 2025 (PMC12946382: 85+ women >20%, men >30%) | FACT |
| 6 | L5 whitepaper interlink | docs/healing/upstream-whitepaper-v1.md (1-year mortality 15–30% · three ~100-yuan life-saving cards) | FACT · multi-source consistent |
| 7 | WHO 1994 T-score definition | Kanis 1994, Osteoporos Int, PMID 7696835 | FACT |
| 8 | FRAX tool | Kanis 2008, Osteoporos Int, PMID 18292978; Schini 2024 review, PMID 37874461 | FACT |
| 9 | USPSTF screening 2018/2025 | Curry 2018, JAMA, PMID 29946735; Nicholson 2025, PMID 39808425 | FACT |
| 10 | Men's screening guideline | Endocrine Society clinical guideline for men (bibliographic-search hit) | FACT·relayed |
| 11 | China calcium intake recommendation | Chinese Dietary Reference Intakes (2023 edition) · official-media relay | FACT·relayed |
| 12 | VD deficiency prevalence | StatPearls (about 1 billion people); Cui 2023 global pooling (<30 nmol/L 15.7%) | FACT |
| 13 | VITAL negative result | LeBoff 2022, NEJM, PMID 35939577 (2000 IU/d did not reduce total/hip fractures) | FACT |
| 14 | VD supplementation has no fall/fracture effect | Octary 2023 systematic review (retrieved record) | FACT·relayed |
| 15 | Exercise and bone density | Howe 2011 Cochrane, PMID 21735380 | FACT |
| 16 | Exercise reduces fall rates | Gillespie 2012 Cochrane, PMID 22972103 | FACT |
| 17 | ONJ 0.001%–0.01% | Lo 2009 (PMC10159647); cancer-dose contrast (MedSafe/ADA relay) | FACT |
| 18 | Denosumab discontinuation rebound | JCEM 2017 series, PMID 28240371; prevention review (PMC8419613) | FACT |
| 19 | Teriparatide | Neer 2001, NEJM, PMID 11346808 | FACT |
| 20 | Romosozumab FRAME | Saag 2016, NEJM, PMID 27641143 (ARCH cardiovascular face · label framing MODEL) | FACT |
| 21 | Glucocorticoid guideline | ACR 2017, PMID 28585373; ACR 2022 update, PMID 37845798 | FACT |
| 22 | ADT fracture risk | Shahinian 2005, NEJM, PMID 15647578 | FACT |
| 23 | Dietary calcium negatively associated with stones | Curhan 1993, NEJM (bibliographic direct verification) | FACT |
| 24 | Supplements and stone risk | Candelas 2012, PMID 23137489 | FACT/MODEL |
| 25 | Height loss and vertebral fracture | Xu 2010/2011 (PMC records); UK 4 cm trigger line (second-hand relay, MODEL) | FACT/MODEL |
| 26 | Vertebral fracture silence | StatPearls NBK448171; 2025 older-adult silent-fracture study (PMC11943146) | FACT |

*Channel discipline: all PMIDs come from TinyFish bibliographic-search result pages — none written from memory; PubMed result pages are JS-rendered and could not be fetched directly, so the bibliographic-search recipe was used; the three hip-fracture mortality papers and Lo 2009 are located by PMC number (PMIDs not shown on the search pages — downgraded honestly, see receipt).*


---

*This volume translated 2026-09-13 by the night-window i18n lanes from `docs/healing/osteoporosis-canon-v1-20260912.md`. Epistemic labels throughout; counter-example history never deleted; prefer an empty cell to an invented one. Transcription, not authorship — this volume is not medical advice; discuss with your doctor.*
