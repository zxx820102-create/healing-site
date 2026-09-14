---
title: "L2 EN i18n Glossary v1 — annotation standard, terminology, conventions"
created: 2026-09-13T02:37:16.565+08:00
updated: 2026-09-13T07:45:03.737+08:00
language: en (with zh source anchors)
scope: "all EN volumes under docs/healing/i18n/en/; baseline audited on the six volumes of 2026-09-13 (child-health, first-aid, mood, allergy, vertigo, vision)"
source_canons: "docs/healing/*-canon-v1-20260912.md (same name minus the -en suffix)"
status: canon-candidate
rule: "Later EN batches follow this glossary; deviations must be recorded as errata against it, not silently improvised."
---

# EN i18n Glossary v1 (2026-09-13)

Purpose: one glossary so every EN volume annotates, names, and calibrates the same way. Written from a line-by-line audit of the six EN volumes and their Chinese source canons. Three sections: §1 annotation standard, §2 terminology table, §3 convention policies.

---

## §1 Annotation standard (标注法规范)

### 1.1 State tokens

Eight tokens, uppercase, meanings inherited from each source canon's epistemic contract (认识态零擅升 — never promote a state unilaterally):

| Token | Source CN | Meaning (EN) |
|---|---|---|
| `FACT` | FACT | guideline / literature / authority text directly verified this round (原文级直核) |
| `FACT·relayed` | FACT·转述 | consistent multi-source relay of authoritative sources (incl. textbook-level consensus framing); not re-verified first-hand this round |
| `MODEL` | MODEL | directional framework consistent across sources; model/policy framing estimates |
| `INFERENCE` | INFERENCE | judgment derived transparently from verified numbers/evidence |
| `HYPOTHESIS` | HYPOTHESIS | mechanism hypothesis, not confirmed (used only where the source uses it, e.g., vision) |
| `CONTRADICTED` | CONTRADICTED | folk claim rejected by evidence; **counter-example history is never deleted** |
| `CONTESTED` | CONTESTED | claim actively disputed — affirmative evidence and counter-examples **stand side by side and are both presented honestly** (两案并列，不硬定); the question stays open, no verdict forced |
| `UNKNOWN` | UNKNOWN | could not be verified; **prefer an empty cell to an invented one** (宁空勿编) |

**CONTESTED vs CONTRADICTED — keep the two cases side by side, never merge (2026-09-13 addition, per the batch4 FINDINGS flag (`2026-09-13-i18n-en-batch4/FINDINGS.md` 瑕疵#3))**: `CONTRADICTED` closes a folk claim — evidence has rejected it and the counter-example history stays on file. `CONTESTED` keeps both cases open at once — affirmative evidence and counter-examples coexist (e.g., the home-health volume's "CO2 causes cognitive impairment as independent causation" item: positive studies on one side, a null counter-study on the other). Several source canons use `CONTESTED` in their own token sets (headache / lbp / insomnia frontmatter; home-health body); per 认识态零擅升 a volume's token set is carried over verbatim, and converting `CONTESTED` into `CONTRADICTED` (or back) in either direction is a state change and is banned.

**The only conforming EN form of the relay tag is `FACT·relayed`.** Banned shorthands: `FACT·trans`, `FACT-trans`, `FACT · relayed`, `FACT·r`. Reason: `trans` reads as "translated/transition" and hides the source concept 转述 ("relayed from authoritative sources").

### 1.2 Attachment grammar

- Lexicalized relay tag: compact, single token — `FACT·relayed` (no spaces; it is one word with a dot in it).
- Source/qualifier attribution: **spaced** middle dot — `FACT · NICE NG143 + AAP`, `FACT · WAO 2020`, `MODEL · epidemiological evidence supports the direction`. Long qualifiers need the air; this is the majority EN form and is conforming.
- Compound judgments carry over verbatim from the source: `FACT + MODEL`, `CONTRADICTED → rebuilt as MODEL`, `CONTRADICTED (premise) + unsupported (practice)`, `FACT·relayed + UNKNOWN`.
- Definitional legend lines inside a volume ("Epistemic labels: FACT = …, MODEL = …") are prose definitions, exempt from the attachment grammar.
- The CN colon form (`FACT：…`, used by the vision source canon) maps to EN `STATE · qualifier`, **not** `STATE:`.

### 1.3 Brackets

ASCII square brackets only in EN volumes: `[TCM·Traditional]`, `[MODEL]`, `[MODEL+FACT]`, `[FACT: NHC document 2024-12-25, …]`. The CJK full-width bracket 【】 belongs to the CN source typography — translate the brackets, keep the content: `【中医·传统】` → `[TCM·Traditional]`, `【MODEL】` → `[MODEL]`.

### 1.4 Structure words (fixed renderings)

| CN | EN (fixed) |
|---|---|
| 就医红旗 / 红旗章 | red flag / red-flag chapter |
| 证伪面 / 证伪条目 / 证伪器 | falsification face / falsification item / falsifier |
| 反例历史不删 | counter-example history is never deleted |
| 行动卡 | action card |
| 互指 | interlink (not "cross-reference") |
| 面 / 卷 / 正典 | face / volume / canon |
| 一句话 / 本册读法 / 一句话收拢 | In one sentence / How to read this volume / one-line collapse |
| 诚实边界 / 宁空勿编 | honest boundaries / prefer an empty cell to an invented one |
| 就医红线 / 红线总表 | red line (must-go-to-hospital) / red-line master table |
| 译者校准 | translator calibration — marked inline as *(translator calibration)* |
| 零冻结 | stays unfrozen (screening/policy content: "latest local policy and your clinician prevail") |
| 直核 / 转述 | directly verified (this round) / relayed |
| 口径 | framing (e.g., "guideline framing", "verified numbers") |

---

## §2 Terminology table (CN → EN)

First occurrence carries the EN term; optional CN gloss per §3.3. Drug names use INN (paracetamol, with "(acetaminophen)" US alias allowed at first occurrence). Eponyms keep source form (Ménière disease, Epley maneuver, Dix-Hallpike, Brandt-Daroff, Kawasaki disease, Reye syndrome, Barany 2015).

### 2.1 Allergy & immune (allergy)

过敏 allergy · 致敏 sensitization · 过敏性鼻炎 allergic rhinitis · 严重过敏反应 anaphylaxis · 过敏性休克 anaphylactic shock · 肾上腺素 epinephrine (adrenaline) · 肾上腺素自动注射笔 epinephrine auto-injector · 荨麻疹 urticaria (hives) · 风团 wheals · 血管性水肿 angioedema · 特应性皮炎 atopic dermatitis (eczema) · 特应性体质 atopy · 接触性皮炎 contact dermatitis · 斑贴试验 patch test · 皮肤点刺试验 skin prick test (SPT) · 特异性 IgE specific IgE (sIgE) · 口服食物激发试验 oral food challenge (OFC) · 脱敏治疗/过敏原免疫治疗 allergen immunotherapy (AIT) · 白三烯受体拮抗剂 leukotriene receptor antagonist · 鼻用糖皮质激素 intranasal corticosteroid · 乳糖不耐受 lactose intolerance · 双相反应 biphasic reaction · 食物依赖性运动诱发严重过敏反应 food-dependent, exercise-induced anaphylaxis · 卫生假说 hygiene hypothesis · 变态反应科 allergy (immunology) clinic

### 2.2 Vertigo & dizziness (vertigo)

眩晕 vertigo · 头晕 dizziness · 晕厥前 presyncope · 失衡 disequilibrium · 头昏沉 lightheadedness · 耳石症 BPPV (benign paroxysmal positional vertigo) · 耳石 otoconia ("ear crystals") · （耳石）复位 repositioning (maneuver) · 前庭神经炎 vestibular neuritis · 迷路炎 labyrinthitis · 梅尼埃病 Ménière disease · 前庭性偏头痛 vestibular migraine · 持续性姿势-知觉性头晕 persistent postural-perceptual dizziness (PPPD) · 体位性低血压 orthostatic hypotension · 前庭康复 vestibular rehabilitation · 位置试验 Dix-Hallpike positional test · 眼震 nystagmus · HINTS 床旁三步 HINTS bedside three-step exam · 急性前庭综合征 acute vestibular syndrome (AVS) · 后循环缺血 posterior-circulation ischemia · 椎基底动脉供血不足 vertebrobasilar insufficiency (VBI, retired term) · 突聋 sudden sensorineural hearing loss · 内淋巴积水 endolymphatic hydrops · 半规管 semicircular canal · 椭圆囊 utricle

### 2.3 Eye & vision (vision)

近视 myopia · 高度近视 high myopia · 假性近视 pseudomyopia · 远视 hyperopia · 散光 astigmatism · 老视 presbyopia · 眼轴 axial length · 睫状肌麻痹（散瞳）验光 cycloplegic (dilated) refraction · 调节痉挛 accommodation spasm · 弱视 amblyopia · 斜视 strabismus (eye turn) · 白瞳症 leukocoria · 红光反射 red reflex · 青光眼 glaucoma · 闭角型 angle-closure · 白内障 cataract · 超声乳化 phacoemulsification · 糖尿病视网膜病变 diabetic retinopathy (DR) · 年龄相关黄斑变性 age-related macular degeneration (AMD) · 干眼 dry eye disease · 睑板腺功能障碍 meibomian gland dysfunction (MGD) · 人工泪液 artificial tears · 视野缺损 visual-field defect · 飞蚊 floaters · 闪光感 flashes · 视网膜脱离 retinal detachment · 角膜塑形镜 orthokeratology (ortho-K) · 离焦框架镜 defocus spectacle lenses · 低浓度阿托品 low-concentration atropine · 重复低强度红光 repeated low-level red light (RLRL) · 视疲劳 (digital) eye strain

### 2.4 Child health (child-health)

发热 fever · 退热药 antipyretic · 对乙酰氨基酚 paracetamol (acetaminophen) · 布洛芬 ibuprofen · 热性惊厥 febrile seizure · 三凹征 chest indrawing · 吸气呻吟 grunting · 鼻翼扇动 nasal flaring · 紫绀 cyanosis · 脱水 dehydration · 口服补液盐 oral rehydration salts (ORS) · 囟门 fontanelle · 皮褶回缩 skin pinch · 幼儿急疹 roseola (exanthem subitum) · 手足口病 hand-foot-mouth disease · 猩红热 scarlet fever · 川崎病 Kawasaki disease · 瑞氏综合征 Reye syndrome · 婴儿肉毒中毒 infant botulism · 捂汗 bundling up / over-wrapping (folk) · 温水擦浴 tepid sponging · 非褪色疹 non-blanching rash · 玻璃杯试验 glass-tumbler test · 脑膜炎球菌病 meningococcal disease

### 2.5 First aid (first-aid)

心肺复苏 CPR · 单纯按压式 Hands-Only CPR · 胸骨 sternum · 自动体外除颤器 AED (automated external defibrillator) · 海姆立克法 abdominal thrusts · 背部拍击 back blows · 止血带 tourniquet · 恢复体位（侧卧位） recovery position · 高压氧舱 hyperbaric oxygen (chamber) · 脑脊液漏 CSF leak · 催吐 induced vomiting · 腐蚀性物质 corrosives · 烃类 hydrocarbons · 一氧化碳 carbon monoxide (CO) · 生石灰 quicklime · 好人条款 Good Samaritan clause · 掐人中 philtrum pressure · 濒死叹息样呼吸 agonal (gasping) respiration · 缺血/坏死/再灌注损伤 ischemia / necrosis / reperfusion injury

### 2.6 Mood (mood)

抑郁症 major depressive disorder · 躯体化 somatization · 认知行为治疗 cognitive behavioral therapy (CBT) · 广泛性焦虑 generalized anxiety disorder (GAD) · 社交焦虑 social anxiety · 惊恐发作 panic attack · 停药综合征 discontinuation syndrome · 渐进暴露 graded exposure · 行为激活 behavioral activation · 病耻感 stigma · 心理援助热线 psychological assistance hotline · 光照疗法 light therapy · 睡眠剥夺 sleep deprivation

### 2.7 Folk practices (keep the [TCM·Traditional] label; describe, never mock)

捂汗 bundling up to sweat it out (folk) · 掐人中 philtrum pressure · 小儿推拿 pediatric tuina massage · 眼保健操 eye-protection exercises (school eye exercises) · 活血化瘀 "promoting blood circulation and resolving stasis" (quote as folk framing) · 凉开三宝 the "three treasures" of cooling-opening (releasing) formulas — 安宫牛黄丸 Angong Niuhuang Wan · 紫雪 Zixue · 至宝丹 Zhibao Dan (pinyin names primary, functional description in parentheses; unified rendering fixed 2026-09-13 per a verification flag — supersedes "Angong Niuhuang pills" / "three cool-opening treasures"; `FACT·relayed` [TCM·Traditional]; describe, never mock)

### 2.8 Thyroid (thyroid)

Added 2026-09-13, terms taken from the volume's actual usage per the batch7 FINDINGS flag (瑕疵#3); CN anchors verified against `docs/healing/thyroid-canon-v1-20260912.md`.

甲状腺 thyroid · 甲状腺结节 thyroid nodule · 甲状腺功能亢进（甲亢）hyperthyroidism · 甲状腺功能减退（甲减）hypothyroidism · 亚临床甲状腺功能减退 subclinical hypothyroidism · 亚临床甲状腺功能亢进 subclinical hyperthyroidism · 促甲状腺激素 thyroid-stimulating hormone (TSH) · 桥本甲状腺炎 Hashimoto thyroiditis · 格雷夫斯病 Graves disease · 甲状腺风暴 thyroid storm · 产后甲状腺炎 postpartum thyroiditis · 黏液性水肿 myxedema · TI-RADS 分层（TR1-TR5）TI-RADS tiering (TR1-TR5) · 细针穿刺 fine-needle aspiration (FNA) · 左甲状腺素 levothyroxine · 乳头状癌 papillary (thyroid) carcinoma · 过度诊断 overdiagnosis · 尿碘 urinary iodine (UIC)

### 2.9 Epilepsy (epilepsy)

Added 2026-09-13, same provenance as §2.8; CN anchors verified against `docs/healing/epilepsy-canon-v1-20260912.md`. (热性惊厥 febrile seizure already lives in §2.4; 病耻感 stigma in §2.6 — not duplicated here.)

癫痫 epilepsy · 痫性发作 seizure · 急性症状性发作 acute symptomatic seizure · 癫痫持续状态 status epilepticus · 癫痫猝死 sudden unexpected death in epilepsy (SUDEP) · 抗癫痫发作药物 anti-seizure medications (ASMs) · 全面强直-阵挛发作 generalized tonic-clonic seizure · 失神发作 absence seizure · 局灶性发作 focal seizure · 发作间期 interictal · 脑电图 electroencephalogram (EEG) · 生酮饮食 ketogenic diet · 光敏性 photosensitivity · 癫痫灶（致痫区）切除 epileptogenic-zone resection · 迷走神经刺激 vagus nerve stimulation (VNS) · 脑深部电刺激 deep brain stimulation (DBS) · 痫证 the xian syndrome [TCM·Traditional]

### 2.10 Men's health (men-health)

Added 2026-09-13, same provenance as §2.8; CN anchors verified against `docs/healing/men-health-canon-v1-20260912.md`.

迟发性性腺功能减退 late-onset hypogonadism (LOH) · 男性更年期 "male menopause" (the volume flags the term as misleading — keep quoted as framing) · 睾酮 testosterone · 晨间睾酮 morning testosterone · 睾酮替代治疗 testosterone replacement (TRT) · 红细胞压积 hematocrit · 腹主动脉瘤 abdominal aortic aneurysm (AAA) · 精索静脉曲张 varicocele · 精液分析 semen analysis · 包年 pack-year · 前列腺特异抗原 prostate-specific antigen (PSA) · 低剂量CT low-dose computed tomography (LDCT) · 睡眠呼吸暂停（阻塞性）obstructive sleep apnea (OSA) · 雄激素性脱发 androgenetic alopecia

### 2.11 Diabetes & blood sugar (diab)

Added 2026-09-13, same provenance as §2.8; CN anchors verified against `docs/healing/diab-canon-v1-20260912.md`.

糖尿病 diabetes · 糖尿病前期 prediabetes · 空腹血糖受损 impaired fasting glucose (IFG) · 糖耐量受损 impaired glucose tolerance (IGT) · 空腹血糖（空腹血浆血糖）fasting plasma glucose (FPG) · 糖化血红蛋白 hemoglobin A1c (HbA1c) · 口服葡萄糖耐量试验 oral glucose tolerance test (OGTT) · 酮症酸中毒（DKA）diabetic ketoacidosis (DKA) · 尿白蛋白（UACR）urine albumin (UACR) · 15-15 法则 the 15-15 rule · 缓解 remission · 二甲双胍 metformin · 苏木杰效应 Somogyi effect · 双循环假说 the twin-cycle hypothesis · 大庆研究 the Da Qing study · 糖尿病足 diabetic foot · 无症状低血糖 hypoglycemia unawareness · 升糖指数 glycemic index (GI)

### 2.12 Cardiovascular (cardio)

Added 2026-09-13, terms folded from the batch8 proposal (`2026-09-13-i18n-en-batch8/FINDINGS.md` flaw-4); every EN form verified against `docs/healing/i18n/en/cardio-en-v1.md` actual usage. Seed note: the batch8 seed listed 心梗 as "myocardial infarction", but the volume never uses that form — it uses **heart attack** in prose and bare **infarction** in compact chains (e.g., "heart (infarction / heart failure)"); the volume's actual usage is authoritative per §3.8-2.

心梗 heart attack (compact chains: infarction) · 卒中 stroke · 心衰 heart failure · 靶器官 target organ(s) (the four: brain / heart / kidneys / eyes)

### 2.13 Stomach & gut (gi-health)

Added 2026-09-13, same provenance as §2.12; EN forms verified against `docs/healing/i18n/en/gi-health-en-v1.md`.

四联疗法 bismuth quadruple therapy · 尿素呼气试验 urea breath test · 宿便 "retained stool" (folk; not a medical concept — carried CONTRADICTED in the volume, counter-example history kept)

### 2.14 Respiratory (resp)

Added 2026-09-13, same provenance as §2.12; EN forms verified against `docs/healing/i18n/en/resp-en-v1.md`. Seed note: the seed's 咯血 = "hemoptysis" is not the volume's usage — the volume says **coughing up blood (blood-streaked sputum)**; entered from the volume. 包年 pack-year already lives in §2.10 (men-health) — same pair, not duplicated here.

老慢支 chronic bronchitis (old name, carried under the COPD umbrella) · 咯血 coughing up blood (blood-streaked sputum) · 喘鸣 stridor

### 2.15 Infection & antimicrobials (infection)

Added 2026-09-13, same provenance as §2.12; EN forms verified against `docs/healing/i18n/en/infection-en-v1.md`. The batch8 seed list did not assign these to volumes; grep located 消炎药 / 检疫期 / 无菌性炎症 in this volume, so they enter here rather than in §2.13/§2.14.

检疫期 quarantine · 无菌性炎症 sterile inflammation · 消炎药 "anti-inflammation medicine" (colloquial misnomer — often mis-meaning antibiotics; the volume's renaming table keeps the two drug classes apart) · AWaRe 分类 the WHO AWaRe classification (Access / Watch / Reserve) · 直接抗病毒药 DAA (direct-acting antivirals)

### 2.16 Joints & bone (joint)

Added 2026-09-13, terms folded from the batch9 proposal (`2026-09-13-i18n-en-batch9/FINDINGS.md` 瑕疵#4); EN forms verified against `docs/healing/i18n/en/joint-en-v1.md`.

骨关节炎 osteoarthritis (OA) · 类风湿关节炎 rheumatoid arthritis (RA) · 痛风 gout · 高尿酸血症 hyperuricemia · 痛风石 tophi · 氨糖 glucosamine · 硫酸软骨素 chondroitin sulfate · 玻璃酸钠 hyaluronic acid (viscosupplementation) · 打封闭 "block injection" (intra-articular glucocorticoid injection) · 生长痛 growing pains · 老寒腿 the folk "old cold legs" (laohan tui) label (folk framing; describe, never mock)

### 2.17 Kidney & urinary (uro)

Added 2026-09-13, same provenance as §2.16; EN forms verified against `docs/healing/i18n/en/uro-en-v1.md`. 肾虚 follows the [TCM·Traditional] + transliteration convention (§2.7 凉开三宝 style): pinyin carried at first occurrence, TCM pattern kept on its own layer, never a kidney-disease claim — matching the volume's own translator_note.

肾虚 kidney deficiency (shenxu) [TCM·Traditional] · 夜间多尿 nocturnal polyuria · 无症状菌尿 asymptomatic bacteriuria · 马兜铃酸肾病 aristolochic acid nephropathy (AAN) · 西布曲明 sibutramine · 布美他尼 bumetanide · 肾绞痛 renal colic

### 2.18 Skin & hair (skin-health)

Added 2026-09-13, same provenance as §2.16; EN forms verified against `docs/healing/i18n/en/skin-health-en-v1.md`. 雄激素性脱发 androgenetic alopecia already lives in §2.10 (men-health) — same pair, not duplicated here.

经皮失水率 transepidermal water loss (TEWL) · 过氧化苯甲酰 benzoyl peroxide (BPO) · 阿达帕林 adapalene · 休止期脱发 telogen effluvium · 斑秃 alopecia areata · 红皮病 erythroderma · 一元硬币 one-coin-sized blob (source anchor kept; the general 2 mg/cm² measure is carried alongside in the volume)

### 2.19 Blood — folk layer (blood)

Added 2026-09-13, terms folded from the batch10 proposal (`2026-09-13-i18n-en-batch10/FINDINGS.md` §2; the batch had suggested §2.7 — entered in this domain section instead per the domain-section rule, keeping §2.7's folk styling: quoted framing, describe never mock). EN forms verified against `docs/healing/i18n/en/blood-en-v1.md`. Convention note: these are folk practice *concepts*, so they follow the §2.7 活血化瘀 precedent (descriptive quoted folk framing) rather than pinyin-primary; pinyin-primary stays reserved for named entities (formulas, herbs) per §2.7 凉开三宝.

补血 "blood-nourishing" (folk framing; describe, never mock) · 排瘀 "expelling stasis" (folk; kin to §2.7 活血化瘀) · 以形补形 "like nourishes like" (folk analogy frame; the literal image given once as a gloss in the volume) · 元气 "vital essence" (folk; the volume keeps the no-physiological-entity boundary explicit)

### 2.20 Cancer (cancer)

Added 2026-09-13, same provenance as §2.19; EN form verified against `docs/healing/i18n/en/cancer-en-v1.md`.

带瘤生存 "living with the tumor" (the cancer-as-chronic-disease framing the source itself supplies)

### 2.21 Women's health (women-health)

Added 2026-09-13, same provenance as §2.19; EN form verified against `docs/healing/i18n/en/women-health-en-v1.md`.

老朋友回来了 "my old friend came back" (folk euphemism for menstruation returning; image + parenthetical explanation per the volume)

### 2.22 Senses (senses)

Added 2026-09-13, same provenance as §2.19; EN form verified against `docs/healing/i18n/en/senses-en-v1.md`.

查得出、压得住、救不回 "detectable, pressable-down, not winnable-back" (glaucoma three-beat; effect-equivalence rendering with literal gloss, per §3.7 style, kept inline in its domain section)

### 2.23 Mood — batch-11 additions (mood)

Added 2026-09-13, terms folded from the batch11 proposal (`2026-09-13-i18n-en-batch11/FINDINGS.md`, mood list); every EN form verified against `docs/healing/i18n/en/mood-en-v1.md`. §2.6 (mood core) untouched — new section, no renumbering. FIX notes: SSRI 类 entered as the volume writes it (**SSRI medication / SSRIs**; neither the spelled-out form nor "SSRI antidepressants" is used in the volume); 矫情话语's seed "you're being dramatic / you overthink" is not the volume's wording — the volume's loop-breaker line is **"you're just being dramatic"**; entered from the volume.

电击感 electric-shock sensations · 情绪迟钝 emotional blunting · 认知疤痕 cognitive scarring · 内感暴露 interoceptive exposure · 正念 mindfulness · 正念减压/正念认知治疗 MBSR/MBCT (mindfulness-based interventions; relapse-prevention evidence face) · 季节性情感障碍 seasonal affective disorder (SAD) · 单胺假说 monoamine hypothesis · 命令性幻听 command hallucinations · 自杀意念 suicidal ideation · 网络meta分析 network meta-analysis (NMA) · 伞状综述 umbrella review · SSRI 类 SSRI medication (SSRIs) · 绿线/黄线 green line / yellow line (the volume's care-timing tiers: green = can be arranged calmly, yellow = counted in weeks) · 矫情话语 "you're just being dramatic" (folk dismissive stigma discourse; the volume's move is translating it back into symptoms)

### 2.24 Burnout (burnout)

Added 2026-09-13, same provenance as §2.23 (batch11 burnout list); EN forms verified against `docs/healing/i18n/en/burnout-en-v1.md`. FIX note: 裸辞's seed "quit cold turkey" is not the volume's form — the volume carries the quoted hyphenate **"quit-cold-turkey solutions"** (rumor face); entered from the volume. job strain: the source canon keeps the EN term inside its CN prose ("高 strain"), so the CN anchor stays the EN word. Cross-refs: 群体归因分数 (§2.28, aging volume) shares this EN term and 掌握经验 (§2.32) shares "mastery experiences" — both CN anchors kept, one EN term each.

职业现象 occupational phenomenon (ICD-11 QD85; not classified as a medical condition) · 情绪耗竭 emotional exhaustion · 去人格化 depersonalization · 犬儒 cynicism · 职业效能感 professional efficacy · 工作要求-控制模型 the job demand-control model (JDC) · job strain（源卷 CN 行文即保留英文）job strain · 心理分离 psychological detachment · 恢复体验 recovery experiences (volume plural) · 掌握体验 mastery experiences · 人群归因分值 population attributable fraction (PAF) · 适应原 adaptogen · 裸辞 "quit-cold-turkey" (volume form: the quoted hyphenate, rumor face) · 带娃倦怠 childcare burnout · 家务倦怠 household burnout · 学业倦怠 academic burnout · 职业倦怠量表 MBI (Maslach Burnout Inventory) / CBI (Copenhagen Burnout Inventory) / UWES (engagement scale) · 失眠认知行为治疗 CBT-I

### 2.25 Pain (pain)

Added 2026-09-13, same provenance as §2.23 (batch11 pain list); EN forms verified against `docs/healing/i18n/en/pain-en-v1.md`. The TCM layer follows the volume's own §⑤ discipline (traditional-theory content labeled [TCM·Traditional]; "meridians" as anatomical-physiological entities stay UNKNOWN in the volume). FIX notes: 烟雾报警器's seed hyphenate "smoke-alarm" is not the volume's spacing — the volume writes **smoke alarm** (metaphor kept per §3.7, image travels); 束带痛's seed "band-like thoracic pain" is not the volume's wording — the red-flag table says **band-like thoracic-level pain**.

慢性原发性疼痛 chronic primary pain · 中枢敏化 central sensitization · 生物心理社会 biopsychosocial · 恐惧回避模型 fear-avoidance model · 烟雾报警器 smoke alarm (metaphor kept; §3.7 image-travels) · 个体病人数据meta分析 individual-patient-data meta-analysis (IPDMA) · 假针灸 sham acupuncture · 雷击样头痛 thunderclap headache · 蛛网膜下腔出血 subarachnoid hemorrhage · 可逆性脑血管收缩综合征 reversible cerebral vasoconstriction syndrome · 马尾综合征 cauda equina syndrome · 鞍区麻木 saddle numbness (the cauda-equina five's first item; "saddle anesthesia" is not the volume's wording) · 束带痛 band-like thoracic-level pain · 椎间盘炎 spondylodiscitis · 压缩性骨折 compression fracture · 疼痛神经科学教育 pain neuroscience education (PNE) · MME（吗啡毫克当量）MME (abbreviation kept as-is in the volume) · SMD/WMD/NNT（统计缩写）SMD / WMD / NNT (statistical abbreviations kept as-is) · 经络 meridians · 腧穴 acupoints · 行气活血 "promoting qi flow and blood circulation" [TCM·Traditional] · 穴位特异性 point specificity · 干针 dry needling

### 2.26 Oral health (oral-health)

Added 2026-09-13, same provenance as §2.23 (batch11 oral-health list); EN forms verified against `docs/healing/i18n/en/oral-health-en-v1.md`. FIX notes — seed forms not the volume's usage, entered from the volume: 楔状缺损 = **wedge-shaped cervical defects** (no "non-carious"); 白斑/红斑 = **oral white patches / red patches** (leukoplakia/erythroplakia never used in the volume); 张口受限 = **limited mouth opening** (no "trismus"); 六龄齿 = **the first permanent molars** (eruption "around age 6" carried in the volume); 智齿 = **wisdom teeth** ("third molars" not used); 龋齿 = **dental caries** ("tooth decay" alias not used); 洗牙/常规洁治 = **(routine) scale and polish** (anchored to the volume's Cochrane "Routine scale and polish" review).

龋齿 dental caries · 牙龈炎 gingivitis · 牙周炎 periodontitis · 附着丧失 attachment loss · 牙槽骨吸收 alveolar bone resorption · 菌斑生物膜 plaque biofilm · 变形链球菌群 mutans streptococci · 再矿化 remineralization · 生态失调 dysbiosis · 窝沟封闭 pit-and-fissure sealants · 涂氟 fluoride varnish · 洗牙/常规洁治 (routine) scale and polish · 龈下刮治 subgingival scaling · 邻面清洁 interdental cleaning · 齿间刷 interdental brush · 冲牙器 water flosser (oral irrigator) · 龈沟 gum line · 楔状缺损 wedge-shaped cervical defects · 龈退缩 gum recession · 酸蚀性牙磨损 erosive tooth wear · 脱矿白斑 demineralized white-spot lesions · dmft（龋失补指数）dmft (index abbreviation kept as-is) · 氟斑牙 dental fluorosis · 种植体周围炎 peri-implantitis · 根管再治疗 root canal retreatment · 桩冠 post-and-core crown · 半切 hemisection · 智齿 wisdom teeth · 阻生 impacted · 冠周炎 pericoronitis · 含牙囊肿 dentigerous cyst · 干槽症 dry socket · 牙脱位 tooth avulsion · 30分钟再植窗 the 30-minute reimplantation window · 白斑/红斑 oral white patches / red patches (the volume's red-flag wording) · 口底 floor of mouth · 槟榔 areca nut · 张口受限 limited mouth opening · 六龄齿 the first permanent molars (around age 6) · 乳牙 primary teeth

### 2.27 Sexual health (sexual-health)

Added 2026-09-13, terms folded from the batch12 proposal (`2026-09-13-i18n-en-batch12/FINDINGS.md` §4, sexual-health list); every EN form verified against `docs/healing/i18n/en/sexual-health-en-v1.md`. FIX notes: 性欲低下 = **low or absent sexual desire / interest** (the volume's table wording); 睾丸扭转 carried in the volume's red-flag chain ("Acute severe testicular/scrotal pain", torsion time window hours-scale) — standard EN kept, volume compact form noted; 长效可逆避孕 = **LARC (IUD / subdermal implant)** (spelled-out form not used in the volume); 勃起功能障碍 = **erectile dysfunction** ("(ED)" alias not used in the volume); 困扰/障碍 from the volume's DSM-5 key-distinction wording. 性腺功能减退 is kin to §2.10's 迟发性性腺功能减退 late-onset hypogonadism (LOH) — different anchor, not duplicated.

性健康 sexual health · 性反应周期 sexual response cycle · 性欲低下 low or absent sexual desire / interest · 勃起功能障碍 erectile dysfunction · 早泄 premature ejaculation · 阴茎异常勃起 priapism · 睾丸扭转 testicular torsion (volume form: "torsion" in the red-flag chain) · 阴道痉挛 vaginismus · 绝经泌尿生殖综合征 genitourinary syndrome of menopause (GSM) · 性腺功能减退 hypogonadism (kin to §2.10 LOH) · 高泌乳素血症 hyperprolactinemia · 双重控制模型 the dual control model (Bancroft & Janssen) · 亲密驱动模型（Basson）the intimacy-based model (Basson) · 完美使用/典型使用 perfect use / typical use · 长效可逆避孕 LARC (IUD / subdermal implant) · 双重保护 dual protection · PDE5 抑制剂 PDE5 inhibitor · 硝酸酯 nitrate · 停药后持续综合征 post-SSRI sexual dysfunction (PSSD) · 性别肯定激素治疗 gender-affirming hormone therapy · 性治疗 sex therapy · 困扰/障碍（DSM-5 区分）a "trouble" ≠ a "disorder" (the DSM-5 key distinction)

### 2.28 Aging care (aging-care)

Added 2026-09-13, same provenance as §2.27 (batch12 aging-care list); EN forms verified against `docs/healing/i18n/en/aging-care-en-v1.md`. FIX notes: 衰弱前期 = **pre-frail** (the volume's form: "1–2 = pre-frail", "the pre-frail window is reversible"); 质子泵抑制剂 = **PPI** (the volume keeps the abbreviation, "the '-prazole' stomach drugs"; spelled-out form not used); 预立医疗决定 = **advance care decisions / advance directives** (the volume's heading form). Cross-ref: 群体归因分数 shares its EN with §2.24's 人群归因分值 — both CN anchors kept. Conflict note: 异地就医备案 is rendered here as **cross-region medical-insurance filing**; the care-access volume renders the same CN as "cross-region care registration" (§2.35) — two renderings stand side by side, left to the glossary owner (捂汗 §2.4/§2.7 precedent, no unilateral merge).

肌少症 sarcopenia · 可能肌少症 possible sarcopenia · 握力 grip strength · 步速 gait speed · 骨量减少 osteopenia (low bone mass) · 骨密度 T 值 T-score · 抗骨吸收药 antiresorptive · 双膦酸盐 bisphosphonate · 脆性骨折 fragility fracture · 髋部骨折 hip fracture · 群体归因分数 population attributable fraction (PAF) (same EN as §2.24 人群归因分值) · 主观认知下降 subjective cognitive decline (SCD) · 衰弱 frailty · 衰弱前期 pre-frail · 多重用药 polypharmacy · 处方精简 deprescribing · 质子泵抑制剂 PPI (the "-prazole" stomach drugs) · 喘息服务 respite care · 预立医疗决定 advance care decisions / advance directives · 缓和医疗 palliative care · 记忆门诊 memory clinic · 日落综合征 sundowning (volume red-flag form: "sundowning-like behavior") · 异地就医备案 cross-region medical-insurance filing (§2.35 carries the care-access volume's "cross-region care registration" — parallel, owner to adjudicate)

### 2.29 Intimate violence (intimate-violence)

Added 2026-09-13, terms folded from the batch13 proposal (`2026-09-13-i18n-en-batch13/FINDINGS.md`, 关系暴力域 list); every EN form verified against `docs/healing/i18n/en/intimate-violence-en-v1.md` and taken directly from the volume's own renderings — protective content, zero free rendering, red flags and referral framing untouched. 冷暴力 follows the volume's translator_note framing exactly.

亲密伴侣暴力 intimate partner violence (IPV) · 强制控制 coercive control · 自由罪 liberty crime · 精神/情感虐待 psychological / emotional abuse · 冷暴力 "cold violence" (leng baoli, CN everyday term mapped to psychological / emotional abuse) · 告诫书 written warning (gaojieshu) · 人身安全保护令 personal safety protection order · 妇联妇女维权热线 Women's Federation rights-protection hotline · 窒息史 strangulation history · 创伤联结 traumatic bonding · 代际传递 intergenerational transmission · 替代性压力 vicarious (secondary) stress · 临时庇护场所 temporary shelter site

### 2.30 Pairbond — relationship science (pairbond)

Added 2026-09-13, same provenance as §2.29 (batch13 关系科学域 list); EN forms verified against `docs/healing/i18n/en/pairbond-en-v1.md`. FIX note: 情绪账户's seed "emotional bank account" is not the volume's form — the volume writes **the relationship's emotional account (the savings of everyday kind interactions)**; entered from the volume.

催逼-退避 demand-withdraw · 软启动 soft startup · 修复尝试 repair attempts · 筑墙 stonewalling · 感知伴侣回应性 perceived partner responsiveness · 永久性问题 perpetual problems · 情绪账户 the relationship's emotional account (the savings of everyday kind interactions) · 相遇池 meeting pool · 焦虑-矛盾 anxious-ambivalent · 紊乱型 disorganized

### 2.31 Identity (identity)

Added 2026-09-13, same provenance as §2.29 (batch13 身份域 list); EN forms verified against `docs/healing/i18n/en/identity-en-v1.md`. Cross-ref note: 人格解体/现实解体障碍 shares the "depersonalization" root with §2.24's burnout dimension (去人格化) — different concepts, both stand.

叙事身份 narrative identity · 自我连续性 self-continuity · 救赎序列 redemption sequence · 繁衍感 generativity · 人格解体/现实解体障碍 depersonalization/derealization disorder (DPDR) (depersonalization root shared with §2.24's burnout dimension — different concepts) · 身份饼图 identity pie chart · 桥段练习 bridge-segment exercise · 交错性 intersectionality

### 2.32 Self-worth (self-worth)

Added 2026-09-13, same provenance as §2.29 (batch13 自尊域 list); EN forms verified against `docs/healing/i18n/en/self-worth-en-v1.md`. Cross-ref note: 掌握经验 shares its EN ("mastery experiences") with §2.24's 掌握体验 — both CN anchors kept.

条件性自我价值 contingencies of self-worth · 脆弱自尊 fragile self-esteem · 身体自尊 body-esteem / physical self-worth · 自我同情 self-compassion · 共同人性 common humanity · 掌握经验 mastery experiences (same EN as §2.24 掌握体验) · 替代经验 vicarious experiences · 心理对照 mental contrasting · 过程赞美/特质赞美 process praise / trait praise

### 2.33 Flow & creation (flow-creation)

Added 2026-09-13, terms folded from the batch14 proposal (`2026-09-13-i18n-en-batch14/FINDINGS.md` §2, flow list); every EN form verified against `docs/healing/i18n/en/flow-creation-en-v1.md`. 微创造 is the source lane's own design vocabulary (MC1–MC7 cards carried as-is); transient hypofrontality stays HYPOTHESIS in the volume.

微创造 micro-creation · 挑战×技能八分区 the challenge×skill eight-zone map · 瞬时前额叶低活动 transient hypofrontality (HYPOTHESIS kept in the volume)

### 2.34 Financial health (financial-health)

Added 2026-09-13, same provenance as §2.33 (batch14 financial list); EN forms verified against `docs/healing/i18n/en/financial-health-en-v1.md`. 带宽税/tunneling are established Mullainathan & Shafir terms the source already uses in English.

带宽税 bandwidth tax (companion term: tunneling) · 雪崩法 the avalanche method · 雪球法 the snowball method · 金钱例会 money meeting · 八钩清单 the eight-hook list

### 2.35 Care access (care-access)

Added 2026-09-13, same provenance as §2.33 (batch14 care-access list); EN forms verified against `docs/healing/i18n/en/care-access-en-v1.md`. FIX notes: 封顶线's seed "annual benefit cap" is not the volume's wording — the volume pairs **the deductible threshold / the annual cap**; 惠民保's gloss from the volume = **city-customized inclusive supplementary insurance** (volume styles the name Huiminbao). Conflict note: 异地就医备案 here = **cross-region care registration** (this volume's §4.2 heading); the aging-care volume renders the same CN as "cross-region medical-insurance filing" (§2.28) — parallel, owner to adjudicate.

分级诊疗 tiered healthcare delivery (compact use: "tiered delivery") · 三甲 Class-3A (top-tier) hospital · 互联网医院 internet hospital · 夜间门诊 evening clinic · 延时门诊 extended-hours clinic · 异地就医备案 cross-region care registration (§2.28 carries the aging volume's "cross-region medical-insurance filing" — parallel, owner to adjudicate) · 起付线 the deductible threshold · 封顶线 the annual cap · 甲类/乙类 Class A / Class B (the drug-catalog split; "inside the catalog" ≠ "all reimbursed" per the volume) · 一致性评价 consistency evaluation · 惠民保 huiminbao (volume styles it Huiminbao; city-customized inclusive supplementary insurance) · 百万医疗险 million-yuan medical insurance · 偶发瘤级联 incidentaloma cascade

### 2.36 Status gradient (status-gradient)

Added 2026-09-13, same provenance as §2.33 (batch14 status list); EN forms verified against `docs/healing/i18n/en/status-gradient-en-v1.md`. 微营养 is the volume's own metaphor for weak-tie interactions, kept with the metaphor transparent.

梯子题 the ladder question (MacArthur ladder) · 非稳态负荷 allostatic load · 弱连接 weak ties · 相对剥夺 relative deprivation · 微营养 "micro-nutrients" (the volume's own metaphor for weak-tie interactions)

### 2.37 Sleep — textbook additions (sleep-textbook)

Added 2026-09-13, terms folded from the textbook EN pilot's proposal (`system/control/receipts/2026-09-13-tb-en-1/FINDINGS.md` §3); every EN form is the sleep textbook's actual usage. Already living in the glossary, not re-entered: CBT-I (§2.24), light therapy (§2.6), sleep deprivation (§2.6) — the pilot's own pre-screen, re-verified here.

睡眠压力 sleep pressure · 腺苷 adenosine · 昼夜节律 circadian rhythm · 视交叉上核 suprachiasmatic nucleus · 双过程模型 two-process model · 睡眠潜伏期 sleep-onset latency (SOL) · 睡眠效率 sleep efficiency (SE) · 醒后清醒时间 wake after sleep onset (WASO) · 慢波睡眠 slow-wave sleep (SWS / deep sleep) · 睡眠片段化 sleep fragmentation · 刺激控制 stimulus control · 睡眠限制 sleep restriction · 时型 chronotype (early bird / night owl) · 社交时差 social jet lag · 褪黑素 melatonin · 延迟睡眠时相障碍 delayed sleep-wake phase disorder (DSWPD) · IARC 2A类 IARC Group 2A ("probably carcinogenic to humans") · 数字疗法 digital therapeutics · 决策树 decision tree · 误区速查 myth quick-check · 学习目标 learning objectives · 四档人话 the four plain-language confidence tiers

### 2.38 Eat — textbook additions (eat-textbook)

Added 2026-09-13, terms folded from the eat textbook lane's proposal (findings note §3); every EN form is the eat textbook's actual usage. Already living in the glossary, not re-entered: glycemic index (§2.11), sarcopenia (§2.28), diabetic ketoacidosis (§2.11), heart attack / stroke / heart failure (§2.12), action card / falsifier (§1.4) — the lane's own pre-screen, re-verified here. The lane deferred 决策树 / 误区速查 / 学习目标 to §2.37 (the sleep pilot proposed them first) rather than re-proposing. Anchor merge 2026-09-13: the 进食窗口 and 一日一餐 CN anchors merged into the TRE / OMAD entries below from the aging volume's usage — §2.40 dual-anchor precedent (judgment-card review, findings note §4).

超加工食品 ultra-processed food (UPF) · 完整食物 whole foods · 热量缺口 calorie deficit · 宏量营养素 macronutrients · 血糖反应 glycemic response · 胰岛素敏感性 insulin sensitivity · 膳食纤维 dietary fiber · 发酵食品 fermented foods · 瘦体重 lean body mass · 进食窗口 / 进食窗 time-restricted eating (TRE) · 隔日禁食 alternate-day fasting (ADF) / 5:2 · 一日一餐 / OMAD one meal a day (OMAD) · 依从性 adherence · 替代指标 surrogate marker · 硬结局 hard outcome · 糖化终产物 advanced glycation end-products (AGEs) · 连续血糖监测 continuous glucose monitoring (CGM) · 时间营养 chrononutrition · 质量轴 the quality axis · 热量前置 front-load calories · 早多晚少 more earlier, less later · 过午不食 noon-cutoff eating · 轻断食 intermittent fasting · 少食多餐 many small meals · 促泌剂 secretagogue · 磺脲类 sulfonylureas · 抗阻训练 resistance training · 进食障碍史 eating-disorder history · 指南级 guideline-level

### 2.39 Constitution — textbook additions (constitution-textbook)

Added 2026-09-13, terms folded from the constitution textbook lane's proposal (`system/control/receipts/2026-09-13-tb-en-2/FINDINGS.md` §3); the nine-type EN names are the constitution canon's own English grid renderings (C1–C9), carried verbatim by the lane — zero coining. 【中医·传统】[TCM·Traditional] was listed only as an already-existing convention (§1.3/§2.7) and is not re-entered. Folk/marketing items keep the quoted framing: describe, never mock (§2.7 style).

平和质 balanced constitution (平和质) · 气虚质 qi-deficiency constitution (气虚质) · 阳虚质 yang-deficiency constitution (阳虚质) · 阴虚质 yin-deficiency constitution (阴虚质) · 痰湿质 phlegm-dampness constitution (痰湿质) · 湿热质 damp-heat constitution (湿热质) · 血瘀质 blood-stasis constitution (血瘀质) · 气郁质 qi-stagnation constitution (气郁质) · 特禀质 special/allergic constitution (特禀质) · 九分法 the nine-type classification · 兼夹体质 composite (mixed) constitution · 治未病 zhi wei bing (treating illness before it arises) · 食养 dietary nourishment · 宜忌 suited-avoid lists · 发物 fawu ("trigger foods") · 横断面研究 cross-sectional study · 系统综述与 META 分析 systematic review and meta-analysis · 效应量 effect size · 关联聚合 association aggregation · 网络药理学 network pharmacology · 五分模型 five-type model · 人群相对性 population relativity · 假设生成器 hypothesis generator · 台湾生物银行 Taiwan Biobank · 中医体质量表 Constitution in Chinese Medicine Questionnaire (CCMQ; the abbreviation is the source volume's own) · 壮阳药 "yang-tonifying drugs" (descriptive quoted framing; describe, never mock, §2.7 style) · 导引 daoyin (traditional guided exercises) · 津液 jinye (body fluids) · 官方口径 official accounting · 发布会 launch briefing · 自媒体 self-media · 检索面 search face · 体质辨识门诊 constitution-identification clinic · 排毒 detox (marketing-claim quoted framing)

### 2.40 Epistemic talk — textbook confidence tiers (epistemic-talk)

Added 2026-09-13, convention-layer mapping pairs folded from the three textbook lanes' proposals (sleep-pilot FINDINGS §2/§3; eat-volume FINDINGS §3; third-textbook-lane FINDINGS §3): the textbook layer speaks plain-language confidence tiers instead of the §1.1 tokens (four tiers in the sleep pilot, five in the eat volume — a CONTESTED tier included), and these are the fixed EN renderings, zero promotion in either direction (认识态零擅升). Consensus note: 不知道 / 没人知道 → not known is a three-lane consensus form — the sleep-pilot lane extracted 不知道→not known, and the eat-volume and third-textbook lanes independently extracted the same EN form under 没人知道; merged here into one entry with both CN anchors (one EN term, per the §2.24 cross-ref precedent), not a conflict. Layer note: the constitution volume's table 5-1 additionally carries three source-level tokens verbatim (`Hypothesis` / `Analogy (not to be used as fact)` / `Preliminary signal`) — a verbatim source-token carry inside one table, distinct from the general talk-layer mappings below; not a competing form. Extended 2026-09-13: +11 mapping pairs folded from the batch-3 textbook lanes' proposals (aging / supplement / drug-food / mind-body), including the two zero-promotion key forms ·animal and traditional practice, not modern evidence; 三多 the "three manys" enters marked *(translator calibration; left to the glossary owner)*.

确定 confirmed · 研究已确认 confirmed by research · 比较确定 fairly well established · 还在研究 still being studied · 指南推荐 guideline-recommended · 类比 analogy, not evidence · 学界还在争论 still contested in the field · 假说 hypothesis · 初步信号 preliminary signal · 不知道 / 没人知道 not known · 指南共识 guideline consensus · 档位后缀动物 ·animal (tier suffix; zero-promotion key form) · 强制 mandatory · 强制级 mandatory tier · 强烈建议 strongly recommended · 遵医嘱 as the doctor directs · 惯例 convention · 一致 Consistent · 三多 the "three manys" *(translator calibration; left to the glossary owner)* · 传统 traditional practice, not modern evidence (zero-promotion key form) · 争论 (the table's short form) contested

### 2.41 Aging — textbook additions (aging-textbook)

Added 2026-09-13, terms folded from the aging textbook lane's proposal (`system/control/receipts/2026-09-13-tb-en-3/FINDINGS.md` §3); every EN form is the aging textbook's actual usage. Conflict note: the batch-internal 汇总分析 (this lane's **pooled analysis** vs the gut volume's **meta-analysis**, §2.42) now stands as parallel entries below (folded 2026-09-13) — owner adjudication still open. Raw tokens DunedinPACE, mTOR, NAD+/NR/NMN, senolytics, VO2max stay as-is per the §2.24 abbreviation precedent (not counted as pairs).

终点 endpoint · 替身 stand-in · 随机对照试验 randomized controlled trial (RCT) · 热量限制 caloric restriction (CR) · 健康跨度 healthspan (years without disability) · 全因死亡 all-cause mortality · 观察性证据 observational evidence · 替代指标陷阱 surrogate-marker trap (the critique phrase; §2.38's 替代指标 surrogate marker is the neutral term) · 泡沫流水线 bubble pipeline (surrogate marker proven → clinical benefit unproven → sold to healthy people) · 衰竭标志 hallmarks of aging · 表观遗传时钟 epigenetic clock · 衰老速度 pace of aging · 自噬 autophagy · 端粒 telomere · 僵尸细胞 "zombie cells" · 慢性低度炎症 chronic low-grade inflammation · 氧化应激面板 oxidative-stress panel · 年轻血回输 young-blood transfusion · 亚精胺 spermidine · 表观重编程 epigenetic reprogramming · 合成代谢抵抗 anabolic resistance · 合成阈值 anabolic threshold · 体成分评估 body-composition assessment · 骨密度 bone density (near-family: §2.28's 骨密度 T 值 T-score — different pair) · 心肺适能 cardiorespiratory fitness · 衰老套餐 "aging panels" · 时钟单次解读 one-shot clock readings · 长寿诊所 longevity clinic · 处方药代购 reseller-purchased prescription drugs · 家用桑拿房 home sauna (room) · 血数字 a blood number (consumer-critique phrase, carried from the source) · 轻断食 light fasting (§2.38 carries the eat volume's 轻断食 intermittent fasting — parallel, owner to adjudicate) · 汇总分析 pooled analysis (the gut volume renders the same CN as meta-analysis, §2.42 — parallel, owner to adjudicate; the aging CN source uses 汇总 verbally — this pair's CN anchor is the lane's normalization)

### 2.42 Gut — textbook additions (gut-textbook)

Added 2026-09-13, terms folded from the gut textbook lane's proposal (`system/control/receipts/2026-09-13-tb-en-4-gut/FINDINGS.md` §3); every EN form is the gut textbook's actual usage. Conflict note: the batch-internal 汇总分析 (the aging volume's **pooled analysis**, §2.41, vs this lane's **meta-analysis**) now stands as parallel entries, §2.41 and below (folded 2026-09-13) — owner adjudication still open.

肠道菌群 gut microbiome · α 多样性 alpha diversity · 短链脂肪酸 short-chain fatty acids (SCFA) · 丁酸 butyrate · 乙酸 acetate · 丙酸 propionate · 益生菌 probiotics · 益生元 prebiotics · 后生元 postbiotics · 抗性淀粉 resistant starch · 多酚 polyphenols · 肠脑轴 gut-brain axis · 血清素 serotonin · 粪菌移植 fecal microbiota transplantation (FMT) · 艰难梭菌 C. difficile (C. diff) · 抗生素相关性腹泻 antibiotic-associated diarrhea (AAD) · CFU colony-forming units (CFU) · 菌株级 strain-level · 适应证 indication · 定植 colonization · 定植窗 colonization window · 定植抗性 colonization resistance · 厚壁菌门 Firmicutes · 拟杆菌门 Bacteroidetes · 古菌 archaea · 噬菌体 bacteriophages · 柔嫩梭菌 Faecalibacterium prausnitzii · 罗斯氏菌 Roseburia · 阿克曼氏菌 Akkermansia · 双歧杆菌 Bifidobacterium · 乳酸杆菌 Lactobacillus · 布拉氏酵母菌 Saccharomyces boulardii · 鼠李糖乳杆菌 GG Lactobacillus rhamnosus GG (LGG) · 母乳低聚糖 human milk oligosaccharides · 血脑屏障 blood-brain barrier · 迷走神经 vagus nerve (cross-ref §2.9's vagus nerve stimulation (VNS) — different pair) · 无菌小鼠 germ-free mice · 乳化剂 emulsifier · 羧甲基纤维素 carboxymethylcellulose · 聚山梨酯-80 polysorbate 80 · 黏液层 mucus layer · 短肠综合征 short bowel syndrome · D-乳酸酸中毒 D-lactic acidosis · 脑雾 brain fog · 肠易激综合征 irritable bowel syndrome (IBS) · 炎症性肠病 inflammatory bowel disease (IBD) · 代谢综合征 metabolic syndrome · 肠龄 gut age · 肠漏 leaky gut · 排毒套餐 detox packages (marketing term, quoted use; §2.39's 排毒 detox word family) · 就医线 the care-seeking line (structure word; distinct from §1.4's 就医红旗 red flag) · 人群速查 population quick-check · 菌相 microbiome profile · 汇总分析 meta-analysis (the aging volume renders the same CN as pooled analysis, §2.41 — parallel, owner to adjudicate)

### 2.43 Drink — textbook additions (drink-textbook)

Added 2026-09-13, terms folded from the drink textbook lane's proposal (`system/control/receipts/2026-09-13-tb-en-5-drink/FINDINGS.md` §3); every EN form is the drink textbook's actual usage. Missing-candidate note: the volume's standalone 氟中毒 fluorosis and 菌膜 biofilm matched only word families in the glossary (§2.26's dental fluorosis / plaque biofilm) — resolved 2026-09-13: both generic pairs added below with word-family cross-refs (per judgment-card review).

总水摄入 total water intake · 水中毒 water intoxication · 低钠血症 hyponatremia · 稀释性低钠血症 dilutional hyponatremia · 运动性低钠血症 exercise-associated hyponatremia (EAH) · 渗透压 osmolality · 下丘脑 hypothalamus · 渗透压感受器/容量感受器 osmoreceptors / volume receptors (composite entry) · 抗利尿激素 antidiuretic hormone (AVP) · 半衰期 half-life · 快/慢代谢者 fast-/slow-metabolizer · IARC 分组 IARC groups · ADI acceptable daily intake · 双萜 diterpenes · 咖啡醇 cafestol · 低密度脂蛋白胆固醇 low-density lipoprotein cholesterol (LDL, "bad cholesterol") · 乙醛 acetaldehyde · 喝酒脸红 alcohol flushing (the flush) · 含糖饮料 sugar-sweetened beverages (SSB) · 非糖甜味剂 non-sugar sweeteners (NSS) · 代糖 sugar substitutes · 糖醇 sugar alcohols · 高倍甜味剂 high-intensity sweeteners · 反向因果 reverse causation · 戒断者混杂 sick-quitter confounding · 孟德尔随机化 Mendelian randomization · J 曲线 the J curve · 最安全饮酒量=零 the safest level of drinking = zero · 砖茶型氟中毒 brick-tea fluorosis (kin to §2.26's 氟斑牙 dental fluorosis — different pair) · 茶多酚 tea polyphenols · 儿茶素 catechins · 纸滤滴滤 paper-filtered drip · 手冲 pour-over · 法压 French press · 土耳其式 Turkish · 斯堪的纳维亚煮沸式 Scandinavian boiled coffee · 意式浓缩 espresso · 滤芯 filter cartridge · 活性炭 activated carbon · 余氯 residual chlorine · 微塑料 microplastics · 咖啡因戒断性头痛 caffeine-withdrawal headache · 国际头痛疾病分类第 3 版 International Classification of Headache Disorders, third edition (ICHD-3) · 阶梯减量 taper down stepwise · 剂量依赖 dose-dependent · 无阈值线性假定 linear no-threshold assumption · 定谳 the verdict · 纯赔 pure loss (source-volume framing phrase) · 医疗边界 medical boundary · 氟中毒 fluorosis (generic pair; the qualified forms live as §2.26's 氟斑牙 dental fluorosis and §2.43's 砖茶型氟中毒 brick-tea fluorosis) · 菌膜 biofilm (generic pair; kin to §2.26's 菌斑生物膜 plaque biofilm — different anchor)

### 2.44 Supplement — textbook additions (supplement-textbook)

Added 2026-09-13, terms folded from the supplement textbook lane's proposal (`system/control/receipts/2026-09-13-tb-en-7-supp/FINDINGS.md` §3); every EN form is the supplement textbook's actual usage. Raw tokens Wernicke, 25(OH)D, EGRAC/PLP/MMA/holoTC, P-5-P stay as-is per the §2.24 abbreviation precedent (full names: EGRAC = erythrocyte glutathione reductase activation coefficient; PLP = pyridoxal phosphate; MMA = methylmalonic acid; holoTC = holotranscobalamin). Mutual confirmation (互证): 生物素 biotin and 血色病/血色沉着病 hemochromatosis appear independently in both this lane's and the drug-food lane's proposals — folded once here, annotated in §2.45.

时钟律 the clock law · 双向律 the bidirectional law · 恒稳带 the steady-state plateau · 功能学指标 functional markers · 补剂史混杂 supplement-history confounding · 负结果 negative results · 分级表 the grading master table · 证伪表 the falsifier registry (names the §1.4 falsifier canon section; declared in the volume) · 检测导向 testing-directed · 脚气病 beriberi · 糙皮病 pellagra · 佝偻 rickets · 骨软化 osteomalacia · 口角炎 angular cheilitis · 舌炎 glossitis · 畏光 photophobia · 巨幼红细胞性贫血 megaloblastic anemia · 铁粒幼贫血 sideroblastic anemia · 周围神经病变 peripheral neuropathy · 亚急性联合变性 subacute combined degeneration · 神经管缺陷 neural tube defects (NTD) · 高钙血症 hypercalcemia · 肾钙质沉着 nephrocalcinosis · 血色病 / 血色沉着病 hemochromatosis (dual CN anchors, one EN — §2.24 precedent; 互证: the drug-food volume's 血色沉着病 anchor, §2.45) · 萎缩性胃炎 atrophic gastritis · 妊娠剧吐 hyperemesis gravidarum · 视黄醇 retinol · 视黄醇当量 retinol activity equivalents (RAE) · 膳食叶酸当量 dietary folate equivalents (DFE) · 国际单位 international units (IU) · β-胡萝卜素 beta-carotene · 烟酸 niacin · 泛酸 pantothenic acid · 生物素 biotin (互证: the drug-food volume's identical CN/EN form, §2.45) · 叶酸（合成）folic acid vs food folate (composite entry; the source splits the two forms) · 肌钙蛋白 troponin · 红细胞转酮醇酶活性系数 erythrocyte transketolase activity coefficient (ETK-AC) · 结晶形式（B12）crystalline form (B12) · 甲钴胺 methylcobalamin · 强化食品 fortified foods · 复合维生素 multivitamin · 泡腾片 effervescent tablets · 孕妇奶粉 prenatal milk powder · 带货话术 sales patter · 恒定摄入 constant intake (warfarin context)

### 2.45 Drug–food — textbook additions (drug-food-textbook)

Added 2026-09-13, terms folded from the drug-food textbook lane's proposal (`system/control/receipts/2026-09-13-tb-en-8-foodrug/FINDINGS.md` §3); every EN form is the drug-food textbook's actual usage. Mutual confirmation (互证): 生物素 biotin and 血色沉着病 hemochromatosis (this volume's CN anchor variant of §2.44's 血色病 — dual CN anchors, one EN) are folded once in §2.44 — same pairs, not duplicated here. Conflict note: 壮阳药 (this volume's **ED drugs** vs §2.39's "yang-tonifying drugs") is two senses, not a mistranslation — folded 2026-09-13 as the **ED drugs** entry below, pure translation mapping (zero dosage, zero advice); §2.39's quoted form stands unchanged (捂汗 §2.4/§2.7 precedent, owner adjudication open).

药物相互作用 drug-food interaction · CYP 酶（肝药酶）CYP enzymes (the liver's drug-processing enzymes) · 酶抑制 enzyme inhibition · 酶诱导 enzyme induction · 转运蛋白（P-糖蛋白）transporter (P-glycoprotein) · 螯合 chelation · 治疗窗 therapeutic window · 窄治疗窗 narrow therapeutic window · 底物药 substrate medicine · 消化流水线 the digestion assembly line · 门口搬运工 the porters at the door · 胶水 the glue · 油门与刹车 the accelerator and the brake · 机制三件套 the mechanism trio · 三件套清单 the three-part medication list (same words, different referent than the mechanism trio; carried from the source) · 推演规则 inference rule · 举一反三 extrapolate from one case to the rest · 药变强 the drug gets stronger · 药变弱 the drug gets weaker · 化验单变假 the lab report turns fake · 双硫仑样反应 disulfiram-like reaction · 双向陷阱 the two-way trap · 骤变 sudden swing · 叠加 stack-on · 对冲 offset · DOAC (the newer oral anticoagulants) · 抗凝门诊 anticoagulation clinic · 就医信号 care-seeking signals · 说明书 package insert · 隐形硝酸酯 hidden nitrates (kin to §2.27's 硝酸酯 nitrate — different anchor) · 大型中性氨基酸转运体 large neutral amino acid transporter · 蛋白再分配 protein redistribution · 高金丝桃素 hyperforin · 香豆素类成分 coumarin-type constituents · MTT 侧链 MTT side chain · 中枢镇咳药 centrally acting cough medicines · 隐性钾补剂 hidden potassium supplement · 低钠盐 low-sodium salt · 白水 plain water · 含矿复合维生 mineral-containing multivitamins · 脂溶维 fat-soluble vitamins · 铜缺乏神经病 copper-deficiency neuropathy · UL (tolerable upper intake level) · 甲状腺/心梗/激素免疫分析 thyroid/heart-attack/hormone immunoassays · 十八反 the Eighteen Antagonisms (shi ba fan) · 十九畏 the Nineteen Fears (shi jiu wei) · 七情配伍 the seven classical compatibility relations · 歌诀 mnemonic verses · 概念层历史混叠 historical superimposition at the concept level · 标注纪律 labeling discipline · 一致（双框架）Consistent (dual framework) · 传统相克 traditional incompatibility (xiangke) · 破气 breaks qi · 补气 qi tonic · 壮阳药 ED drugs (this volume's sense — the nitrate-interaction red-flag context, kin to §2.27's PDE5 inhibitor; §2.39 carries the constitution volume's "yang-tonifying drugs" — two senses of one CN word, not a mistranslation)

### 2.46 Mind–body — textbook additions (mindbody-textbook)

Added 2026-09-13, terms folded from the mind-body textbook lane's annex proposal (`system/control/receipts/2026-09-13-tb-en-6-mindbody/FINDINGS.md` §3; annex-supplement volume, admitted per the fold-4 materials' §7 disclosure); every EN form is the mind-body textbook's actual usage. Five first-rendering wu-line/sound-healing forms are the lane's own first proposals, carried as declared.

身心灵 mind-body-spirit · 身层/心层/灵层 the body layer / the mind layer / the spirit layer · 十八因素 the eighteen factors · 副作用格 side-effect cell · 三条医疗边界 the three medical boundaries · 自主神经 the autonomic nerves · 交感/副交感 accelerator (sympathetic) / brake (parasympathetic) (imagery kin to §2.45's 油门与刹车 the accelerator and the brake) · 心率变异性 heart rate variability (HRV) · 过度换气 hyperventilation · 冷休克反应 cold shock response · 心源性猝死 sudden cardiac death · 类运动应激 exercise-like stressor · 过训综合征 overtraining syndrome · 横纹肌溶解 rhabdomyolysis · 应激轴 stress axis · 菌-肠-脑轴 microbiome-gut-brain axis (superset of §2.42's 肠脑轴 gut-brain axis) · 产丁酸菌 butyrate-producing bacteria (kin to §2.42's 丁酸 butyrate) · 睡着的耳朵也在计账 the sleeping ear keeps the ledger too (rhetoric carried from the source) · 压力三分法 the three-way stress sort · 认知重评 cognitive reappraisal · 表达抑制 expressive suppression · 情绪命名 affect labeling · 反刍 rumination · 强制积极 forced positivity · 回避式减压 avoidant stress relief · 决策疲劳 decision fatigue · 执行功能 executive function · 信息节食 information dieting · 二次压抑/二次伤害 secondary suppression / secondary harm · 呼吸锚定 breath anchoring · 身体扫描 body scan · 静修 retreat · 禅修病 "meditation sickness" · 创伤重现 re-experiencing · 过度觉醒 hyperarousal · 解离 dissociation · 「隔玻璃」看世界 watching the world through glass (metaphor carried from the source) · 负效价体验 negative-valence experiences · 整合式哀伤 integrated grief · 波浪节律 wave rhythm · 延长哀伤障碍 prolonged grief disorder (PGD) · 对话式书写 dialogic writing · 延迟性哀伤 delayed grief · 意义句 meaning sentence · 价值观澄清写作 values-clarification writing · 敬畏 awe · 自我消解 self-dissolution (the small self) · 历史级教训 a history-grade lesson · 道德许可 moral licensing · 同情疲劳 compassion fatigue · 照护者耗竭 caregiver burnout (§2.24's burnout word family) · 共同调节 co-regulation · 技能型志愿 skills-based volunteering · 被迫摊派 compelled, assigned volunteering · 强连接圈 strong-tie circle (antonym of §2.36's 弱连接 weak ties) · 施压型劝交 pressure-to-socialize · 巫线 the wu-line · 入静 stillness practice · 音声疗愈 sound healing · 五音应五脏 the five tones matching the five organs · 边界句 boundary sentence

---

## §3 Convention policies (惯例政策)

### 3.1 Emergency and hotline numbers — 「按读者地区取号 + 卷内译者注」

Policy: the EN volume keeps the source canon's own anchored number, tells the reader to use their local number by region, and marks the substitution explicitly. Never invent numbers for other regions; what the source marks UNKNOWN stays UNKNOWN.

- Frontmatter: each volume's `translator_note` states the anchor and the local-number rule once, marked as translator calibration.
- First in-body occurrence template (medical emergency):

  `call 120 (mainland China's medical emergency line; readers elsewhere: use your local emergency number — *(translator calibration)*)`

- Volume-banner template (used at the top of L1 volumes that reference numbers throughout):

  `> **Emergency number in this volume = 120 (mainland China's medical emergency line)** — readers elsewhere: use your local emergency number (112 / 911 / 999). Source's international coverage: UNKNOWN. *(translator calibration)*`

- Subsequent mentions: bare source number or "your local emergency number", no repeated gloss needed.
- Hotline analog (mood): CN 12356 stays as source anchor; international pointer (findahelpline.com; US 988; UK/Ireland Samaritans 116 123) added once, marked *(translator calibration; source anchor = 12356)*.

### 3.2 Numbers, units, citations

Every PMID, dose-logic range, percentage, and conclusion is carried verbatim from the source canon — transcription, not authorship. No re-computation, no new literature. Full DOI/PMID verification ledgers stay in the source canon's receipt, not duplicated into EN volumes.

### 3.3 Chinese glosses in EN text

EN-first always. An optional CN gloss in parentheses is allowed at first occurrence only, and only where it names a folk practice (掐人中), disambiguates a graph anchor, or aids bilingual audit. Interlink anchors that must match graph nodes stay in the source language with a translator note (e.g., `home:运动防跌` — "anchor names kept in the source language of the neighboring graph nodes").

### 3.4 Safe messaging (mood-family volumes)

Person-first phrasing; no method detail; means-restriction appears only as prevention guidance; crisis-line block sits at the top of the suicide-intervention face. Wording calibrated to English public-health safe-messaging conventions and marked in translator_note.

### 3.5 Volume tiers

- `L1` (lay-level condensed rendering): red-flag chapter preserved item-by-item; dosage iron law ("every actual dose defers to the drug label and your doctor/pharmacist") preserved verbatim; sections may compress but never invent.
- `v1` (fuller transcription): face-by-face transcription with interlink table and honest-boundaries section.
- Both tiers are "transcription, not authorship — discuss with your doctor; this volume is not medical advice."

### 3.6 Falsifier inheritance and UNKNOWN discipline

Each volume inherits the source canon's falsifier clause (guideline revision or title-level retraction → corresponding section downgraded with an erratum). UNKNOWN is never hidden; a blank beats an invented value.

### 3.7 Idiom transfer — effect equivalence (习语=效果等值)

Render the *effect* of a Chinese idiom, not its literal image, unless the image itself travels. Verified pairs from this audit:

| CN idiom | conforming EN | note |
|---|---|---|
| 让病程裸奔 | let the disease run unchecked | "running naked" is a false friend image |
| 万金油 | cure-all | "all-purpose oil" is literal |
| 充值 | tops up | works ("every avoidance tops up the next attack") |
| 用湿毛巾对付房子着火 | fighting a house fire with a wet towel | image travels; keep |
| 照妖镜 | demon-revealing mirror | image travels with the metaphor flagged as such; keep |
| 见过世面的痕迹 | the footprint of "having seen the world" | keep, mild domestication fine |
| 对方先挂 | they hang up first | keep |
| 成本函数 | cost function | source itself is mathematical; keep |

### 3.8 New-volume checklist (for future batches)

1. Five-minute pass with §1: relay tag, bracket form, colon-form migration.
2. Terminology via §2; add new pairs here rather than coining privately.
3. Emergency/hotline numbers via §3.1 templates.
4. Idioms via §3.7; when unsure, mark the sentence for bilingual review instead of guessing.
5. Run the lane verify suite with the volume list before closing.

---

*Glossary v1 by the night-window lanes, 2026-09-13. Baseline: six EN volumes × their CN source canons, line-level audit. This file standardizes annotation and terminology only — it adds no medical content to any volume.*
