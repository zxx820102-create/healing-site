---
title: "COPD Canon v1 (English v1) — the third-leading cause of death that most people have never heard of, and the one intervention proven to change its course"
created: 2026-09-13T02:27:35.221+08:00
updated: 2026-09-13T04:53:26.107+08:00
language: en
source_canon: docs/healing/copd-canon-v1-20260912.md
translation_version: 1
translated_date: 2026-09-13
epistemic_discipline: preserved
source_canon_index: docs/theories/CANON-INDEX.md
glossary: docs/healing/i18n/en/glossary-v1.md
status: candidate_only
translator_note: "Transcription, not authorship: every PMID, number, conclusion and falsification item is carried over verbatim from the source canon; no medical content added. Epistemic labels preserved as-is (FACT / MODEL / INFERENCE / CONTRADICTED / UNKNOWN — left empty rather than invented). Drug content stays at direction-and-'discuss with your doctor' level exactly as in the source; this volume is not medical advice. Emergency care wording follows the source ('seek care immediately'); emergency numbers differ by region — call your local emergency number (e.g., 120 in mainland China, 911/999/112 elsewhere) (marked as translator calibration)."
---

# COPD Canon v1 (English)

> ## 🔴 Read before use (three safety rules)
> 1. This page is candidate health-education information (candidate_only) — it is not a diagnosis and not a prescription.
> 2. Any medication and treatment decision should be made together with a respiratory physician or general practitioner.
> 3. The red-flag lines for emergencies are in Face ⑥: sudden worsening of breathlessness, sputum turning purulent with high fever, drowsiness or altered consciousness, leg swelling — seek care immediately, do not wait.

---

## ⓪ What this volume is, and its evidence discipline

- **Division of labor with the respiratory canon**: `docs/healing/resp-canon-v1-20260912.md` covers the respiratory-disease family overview (where asthma/COPD/bronchiectasis/pulmonary fibrosis sit in the spectrum); this volume does the deep face of COPD alone.
- Epistemic states are labeled item by item (FACT/MODEL/INFERENCE/UNKNOWN); the evidence channel is TinyFish → Europe PMC REST bibliographic verification, with every PMID drawn from this lane's search results rather than memory; anything not verified is honestly downgraded (the downgrade list is in the receipt).

## ① Epidemiology face (①)

**Global (FACT · WHO fact sheet · verified via the channel 2026-09-13):**
- COPD is the world's **third leading cause of death**: **about 3.4 million deaths in 2023, roughly 6% of all global deaths** (GBD 2023 framing). The task brief had recorded "WHO ~3.5 million/year"; the current WHO page has been updated to 3.4 million — this volume follows the verified figure (the older 3.5 million is the pre-2019 framing).
- Nearly 90% of COPD deaths in people under 70 occur in low- and middle-income countries; measured in disability-adjusted life years it is the world's seventh-leading cause of poor health.
- Attribution: in high-income countries tobacco accounts for more than 70% of cases; in low- and middle-income countries tobacco accounts for 30–40%, and **household air pollution is a major risk factor**.

**China (FACT · Wang C et al., Lancet 2018, the China Pulmonary Health (CPH) study, PMID 29650248):**
- National cross-sectional survey (10 provinces · 50,991 participants · post-bronchodilator spirometry · GOLD 2017 criteria): **prevalence 8.6% (95%CI 7.5–9.9)**, projecting to **99.9 million (about 100 million) people** (95%CI 76.3–135.7 million).
- Men 11.9% vs women 5.4%; age 40 and above 13.7% vs ages 20–39 at 2.1%.

**Underdiagnosis = the silent disease (FACT+MODEL):**
- In the same study, **only 12.0% of people with COPD had ever had a spirometry test** (FACT · PMID 29650248, verified from the abstract).
- The claim "only about 3% had ever been told by a doctor they had COPD" comes from that study's full text — this lane could not verify the full text directly, so it is downgraded to MODEL (see the receipt's downgrade list). The conservative conclusion is unaffected: **the great majority of patients do not know they have the disease**.
- New evidence on pushing diagnostic tools into primary care (FACT · Yan 2026, Lancet Reg Health West Pac, PMID 42621354): pre-bronchodilator FEV1/FVC<0.56 has a positive predictive value of 0.953 for "confirmed post-bronchodilator <0.7," usable for immediate triage in primary care.

## ② Boundary-identification face (②)

**The diagnostic line (FACT · Celli BR & MacNee W, ATS/ERS position paper, Eur Respir J 2004, PMID 15219010):**
- Post-bronchodilator **FEV1/FVC < 0.7** = presence of incompletely reversible airflow limitation — this is the objective threshold for diagnosis; symptoms cannot replace lung function testing.

**COPD vs asthma boundary (FACT/MODEL · textbook-level contrast):**

| Dimension | COPD | Asthma |
|---|---|---|
| Onset | Gradual after middle age (prevalence jumps to 13.7% after age 40, FACT) | Usually begins in childhood/adolescence |
| Course | Persistent · progressively worsening | Episodic · intervals can be normal |
| Airflow limitation | Incompletely reversible (FEV1/FVC<0.7 does not recover) | Reversible (substantial recovery spontaneously or with medication) |
| Background | Smoking / smoke-exposure history dominates | Allergy / family allergy history dominates |
| Day-night rhythm | Symptoms track daytime activity | Early-morning/nighttime cough and wheeze prominent |

- The two can coexist (asthma–COPD overlap); the boundary is drawn by reversibility testing on spirometry plus history, not by "wheezing or not" (MODEL).
- **The GOLD assessment framework**: 2011–2022 used the ABCD four groups (symptoms × exacerbation history, two axes setting treatment intensity); from 2023 simplified to **A/B/E three groups (E = the high exacerbation-risk group)**. This lane verified only that the 2025 report exists on goldcopd.org and could not read the body text directly — **the ABCD→ABE evolution is recorded as MODEL** (receipt downgrade list). The principle that assessment drives treatment intensity is itself FACT-level consensus.

## ③ Risk-factor face (③)

| Factor | Evidence and magnitude | Epistemic state |
|---|---|---|
| Smoking | ≥20 pack-years OR 1.95 (95%CI 1.53–2.47, Wang CPH); >70% of cases attributable to tobacco in high-income countries (WHO) | FACT |
| Secondhand smoke | WHO explicitly lists passive exposure among causes | FACT |
| **Biomass fuel / coal smoke (the local highlight)** | Meta-analysis of biomass smoke and COPD risk (Hu G et al., Chest 2010, PMID 20139228); WHO: household air pollution (wood/dung/crop-residue/coal for cooking and heating) is a major risk factor in low- and middle-income countries | FACT |
| COPD in never-smoking rural Chinese women | Women's prevalence 5.4% (Wang) + biomass-smoke meta-analysis + WHO naming household pollution a main driver — long-term cooking smoke from wood/coal is an important driver in this population | INFERENCE (multi-source synthesis; attribution strength below smoking, not the sole cause) |
| Ambient PM2.5 | Annual mean 50–74 μg/m³ OR 1.85; ≥75 μg/m³ OR 2.00 (Wang CPH) | FACT |
| Occupational dusts/fumes/chemicals | Explicitly listed by WHO; precise population-attributable fractions not verified | MODEL |
| Tuberculosis history | Two systematic review + meta-analysis papers on TB history and COPD (Front Med 2026, PMID 42638736; J Clin Med 2025, PMID 41227036 · bidirectional association) | FACT (the association exists) |
| Alpha-1 antitrypsin deficiency | Inborn condition · can cause emphysema at young ages and "remains persistently missed" (Stoller JK, Cleve Clin J Med 2026, PMID 41771676); **young (<45), never-smoker, lower-lobe-predominant emphysema → check serum AAT** | FACT (the disease exists + missing it is common); screening-indication framing MODEL |
| Early life | Frequent chronic cough in childhood OR 2.57 (Wang); preterm birth / severe childhood respiratory infections causing reduced lung growth (WHO) | FACT/MODEL |
| Low body weight | BMI<18.5 OR 1.43 (Wang CPH) | FACT |

## ④ The management honesty ledger (④)

**Smoking cessation = the only intervention proven to change the disease course (FACT):**
- The Lung Health Study RCT: cessation intervention significantly slowed FEV1 decline over 5 years (Anthonisen NR et al., JAMA 1994, PMID 7966841); the intervention effect was still measurable at 11 years (Murray RP et al., Prev Med 2002, PMID 12453707).
- The 14.5-year follow-up showed the cessation intervention reduced all-cause mortality (Ann Intern Med 2005) — the existence of that original article is corroborated by two companion commentary letters verified by this lane (PMID 16230731/16230735); **the original PMID was not captured → this item is recorded as MODEL**.
- WHO: even after many years of smoking, quitting still brings benefit — **it is never too late at any disease stage** (FACT).

**The inhaler family map (FACT+MODEL):**

| Family | Role | Framing |
|---|---|---|
| SABA/SAMA (short-acting) | Onset within seconds · lasts 4–6h · for rescue | FACT (WHO) |
| LABA/LAMA (long-acting bronchodilators) | The **mainstay of once-daily maintenance treatment** — WHO: "bronchodilators are the most important medicines for treating COPD" | FACT (WHO) |
| ICS (inhaled corticosteroids) | **Not used alone**; combined with long-acting bronchodilators, targeted at the frequent-exacerbation / high-eosinophil phenotype | MODEL (positioning) + FACT (combination principle · WHO "can be combined with inhaled corticosteroids") |

- **Inhaler-technique error is a decades-spanning, universal problem** (Sanchis J et al., Chest 2016 systematic review, PMID 27060726) — "the medicine doesn't work" is very often "the technique wasn't done right." Practice point: at every follow-up visit demonstrate + re-teach with teach-back, and add a spacer when needed (WHO also states correct technique is the precondition, FACT).
- The ICS two-sided ledger: real risks (local effects — oropharyngeal candidiasis/hoarseness/skin bruising = FACT-level common knowledge; long-term high-dose association with pneumonia risk = MODEL, the JAMA 2008 meta was not verified by this lane → downgrade list) versus positioning value (fewer exacerbations). Withdrawal face: a systematic review on stopping ICS and its effect on exacerbation frequency and lung function exists (Int J Chron Obstruct Pulmon Dis 2024, PMID 38919905). **Those who need it should not refuse it because "steroids harm the body," and it should not be overused in people who don't need it.**
- **Pulmonary rehabilitation** (a multidimensional program of exercise + education): improves quality of life and exercise capacity (Cochrane review, McCarthy B et al. 2015, PMID 25705944) = FACT.
- **Long-term home oxygen therapy**: prolongs survival in severe resting hypoxemia — anchored by two RCTs: NOTT (Ann Intern Med 1980, PMID 6776858, continuous vs nighttime oxygen) and the MRC working party (Lancet 1981, PMID 6110912, long-term home oxygen in chronic hypoxic cor pulmonale). **Moderate hypoxemia does not benefit; oxygen without hypoxemia has no evidentiary basis** (MODEL · framing not directly verified). Starting criteria are set by a physician using blood gases/oxygen saturation.
- **Acute exacerbations**: the recognition triad = worsening breathlessness + more sputum + sputum turning purulent (Anthonisen NR et al., Ann Intern Med 1987, PMID 3492164; RCT: those with all three signs benefit most from antibiotics); antibiotics go only to those with the indication (stewardship).
- **Prevention**: annual influenza vaccine + pneumococcal vaccine (WHO FACT); a nationwide test-negative design study from Thailand: influenza vaccination in people with COPD reduced pneumonia and acute exacerbations (Vaccines 2026, PMID 42646728). Vaccine face interlinks → `docs/healing/vaccine-canon-v1-20260912.md`.

## ⑤ Nutrition and daily-living face (⑤)

- **Weight loss and muscle loss = negative prognostic signals** (MODEL-level consensus; low body weight is itself a COPD risk factor, OR 1.43 = Wang FACT) — this is the opposite face of "only being heavy is healthy": **deliberately keeping weight on is not health; preventing muscle loss is the key** (adequate protein + resistance activity).
- Eating practice (MODEL · daily-care experience layer): small frequent meals · avoid eating at the peak of breathlessness · ensure protein.
- **Pursed-lip breathing / diaphragmatic (abdominal) breathing**: evidence graded honestly — a Cochrane review on breathing exercises for COPD exists (Holland AE et al. 2012, PMID 23076942), **the benefit evidence is limited and uncertain = MODEL**; usable as a technique adjunct, **not a replacement** for exercise and pulmonary rehabilitation.
- Exercise: safe and the core of pulmonary rehabilitation (FACT · McCarthy); maintain daily physical activity (WHO FACT).
- Replacing indoor wood/coal cooking and heating with clean energy (WHO CHEST action direction · FACT-level policy face).

## ⑥ Red-flag face (⑥)

Any one of the following = **seek care immediately** (FACT/MODEL mixed · clinical consensus):
1. Sudden increase in shortness of breath, not easing at rest (exacerbation, or pneumothorax and similar);
2. Sputum turning purulent-green + increased sputum volume (infective exacerbation — the indication face of the Anthonisen triad);
3. Fever (possible infection → interlink with the first-aid canon's fever face fa:fever-firstaid);
4. **Drowsiness / altered consciousness / cannot be woken** — a signal of CO2 retention (type II respiratory failure), the emergency within emergencies (MODEL · consensus);
5. **Leg (lower-limb) swelling** — a signal of right-heart overload / cor pulmonale (the MRC trial population was precisely "chronic hypoxic cor pulmonale," PMID 6110912 corroborating the entity); cardio canon interlink card:end-stage-heart-failure;
6. Bluish lips, difficulty speaking in full sentences, chest pain.

## ⑦ Falsification face (⑦ · each item with its falsifier)

| # | Popular claim | Verdict | falsifier (what finding would overturn this verdict) |
|---|---|---|---|
| 1 | "Wheezing = just getting old, it's normal" | CONTRADICTED (as a reason not to get checked) | New persistent breathlessness + sputum after 40 = check lung function (prevalence 8.6% vs only 12% ever spirometry-tested = the scale of silence, Wang FACT). If population screening showed the lung-function abnormality rate in older breathless people did not differ from asymptomatic peers, this verdict would be withdrawn |
| 2 | "Quitting smoking or not makes no difference" | CONTRADICTED | LHS RCT: the cessation arm's FEV1 decline significantly slowed (PMID 7966841); benefit at every stage of quitting (WHO FACT). If a new RCT showed the cessation arm's lung-function trajectory did not differ from continued smokers', rewrite |
| 3 | "Inhaled steroids harm the body; dare not use them" | CONTRADICTED (as blanket refusal) | ICS has a real risk face (local effects + pneumonia association MODEL) and a positioning value (combination for frequent exacerbators). If a large RCT showed ICS-containing regimens did not reduce moderate-severe exacerbations, its positioning would be rewritten |
| 4 | "Take antibiotics at the first sign of a cold" | CONTRADICTED (as unconditional use) | Anthonisen 1987 RCT: benefit stratified by the triad (PMID 3492164); self-medicating without indication = resistance + futility risk. If the stratified-benefit difference disappeared, rewrite |
| 5 | "If you don't smoke you won't get it" | CONTRADICTED | Chinese women's prevalence 5.4% (Wang FACT) + biomass-smoke meta-analysis (PMID 20139228) + WHO: household air pollution a main driver in LMICs + TB-history association (PMID 42638736) |
| 6 | "Exercise harms the lungs" | CONTRADICTED | Cochrane pulmonary rehabilitation improves quality of life and exercise capacity (PMID 25705944). If RCTs showed training arms had worse outcomes, rewrite |
| 7 | "Supplements cleanse the lungs" | UNKNOWN (prefer an empty cell to an invented one) | No known supplement has been shown to reverse structural lung damage. Falsifier: any product showing improved FEV1 or exacerbation frequency in a pre-registered RCT with independent replication |
| 8 | "Symptoms are mild = no need to test lung function" | CONTRADICTED | Same as #1: the mass underdiagnosis of the silent disease is itself the evidence (Wang FACT) |

## Endnotes

- **Known unknowns (UNKNOWN as a first-class citizen)**: the body-text details of GOLD ABE · the original PMID of Anthonisen 2005 · the PMID of the JAMA 2008 ICS–pneumonia meta · the full-text figure "about 3% told of diagnosis" · the exact wording of long-term oxygen therapy initiation criteria — all are in the receipt's downgrade list; memory does not fill gaps.
- **Channel and verifiability**: TinyFish → Europe PMC REST, all PMIDs from this lane's search results; the per-anchor verification table is in `system/control/receipts/2026-09-12-copd/FINDINGS.md`.
- **Interlinks**: respiratory canon (family overview) · vaccine canon (vaccine face) · first-aid canon (fever/critical illness) · cardio canon (cor pulmonale) · aging canon (geriatric comorbidity).
- This volume shares source and batch with the weave map `data/healing/copd-map-20260912.json`; all 4 cross-graph anchors are existing node ids in neighboring maps (vax:flu-vaccine / fa:fever-firstaid / card:end-stage-heart-failure / agc:aging).

**stage:done**


---

*This volume translated 2026-09-13 by the night-window i18n lanes from `docs/healing/copd-canon-v1-20260912.md`. Epistemic labels throughout; counter-example history never deleted; prefer an empty cell to an invented one. Transcription, not authorship — this volume is not medical advice; discuss with your doctor.*
