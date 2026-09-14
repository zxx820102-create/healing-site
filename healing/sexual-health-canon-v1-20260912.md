---
title: 性健康正典 v1（2026-09-12·成人教育向·医学严肃口径）
created: 2026-09-12T22:14:34.461+08:00
updated: 2026-09-13T05:02:36.828+08:00
grounding:
  - docs/healing/human-needs-map-v1-20260912.md（罗盘第 1 条·空白×高频定级来源）
  - docs/healing/diet/food-drug-interaction-canon-20260912.md（药食交互正典·交互机制承接引用不复制）
  - docs/healing/deep-card-t2dm-20260912.md（慢病×性功能接口·T2DM 深）
  - PG screening_schedule（66 行·宫颈癌筛查已库·本篇只挂针不复制）
  - PG red_flags 表面（红旗模式沿用）
external_anchors:
  - WHO Sexual health 主题页「WHO working definition」https://www.who.int/health-topics/sexual-health（2026-09-12 核·定义句原样）
  - Laumann EO, Paik A, Rosen RC. JAMA 1999「Sexual dysfunction in the United States: prevalence and predictors」（被引 2861）
  - McCabe MP et al. J Sex Med 2016「Incidence and Prevalence of Sexual Dysfunction in Women and Men: Consensus Statement from the Fourth International Consultation on Sexual Medicine」（被引 313）
  - Serretti A, Chiesa A. J Clin Psychopharmacol 2009「Treatment-emergent sexual dysfunction related to antidepressants: a meta-analysis」（被引 357）
  - Basson R. J Sex Marital Ther 2000「The female sexual response: a different model」（被引 430）+ Basson 2002「A model of women's sexual arousal」+ Basson R. Endocrinol Metab Clin North Am 2021「Sexual Dysfunctions in Women: Are Androgens at Fault?」
  - Bancroft J, Graham CA, Janssen E et al. J Sex Res 2009「The dual control model: current status and future directions」（被引 217）+ Janssen E, Bancroft J. J Sex Res 2023 scoping review
  - Rider JR et al. Eur Urol 2016「Ejaculation Frequency and Risk of Prostate Cancer: Updated Results with an Additional Decade of Follow-up」（被引 57）× Leitzmann MF et al. JAMA 2004「Ejaculation frequency and subsequent risk of prostate cancer」（被引 59）——两立如实录
  - Trussell J. Contraception 2011「Contraceptive failure in the United States」（被引 889）+ Sundaram A et al. Perspect Sex Reprod Health 2017（NSFG 更新）
  - Henschke N et al. Cochrane Database Syst Rev 2025「Effects of human papillomavirus (HPV) vaccination programmes on community rates of HPV-related disease and harms」+ Bergman H et al. Cochrane 2025「HPV vaccination for the prevention of cervical cancer…network meta-analysis」
  - Brotto LA et al. J Consult Clin Psychol 2021「A randomized trial comparing group mindfulness-based cognitive therapy with group supportive sex education…female sexual interest/arousal disorder」（被引 44）+ Cochrane 2019「Bibliotherapy for sexual dysfunction」
  - Cheitlin MD（Prev Cardiol 2003）/Jackson G, Montorsi P, Cheitlin MD. Urology 2006「Cardiovascular safety of sildenafil citrate (Viagra): an updated perspective」
  - Hembree WC et al. J Clin Endocrinol Metab 2017「Endocrine Treatment of Gender-Dysphoric/Gender-Incongruent Persons: An Endocrine Society Clinical Practice Guideline」（被引 1485）
  - Bhasin S, Snyder PJ. N Engl J Med 2025「Testosterone Treatment in Middle-Aged and Older Men with Hypogonadism」+ Cochrane 2018「Testosterone supplementation in men with sexual dysfunction」
epistemic_discipline: 每条带认识态+来源+falsifier·宁空勿编；性反应周期框架一律 MODEL 不冒充生理事实；观察性方向未定谳如实两立；敏感面（未成年人/非自愿行为）一律导向专业求助线不处置
privacy_check: 九隐私词零出现（产出后 python3.11 扫描自证入收据）
---

# 性健康正典 v1（成人教育向·医学严肃口径）

**定位**：性健康是正规医学分支（WHO 纳入卫生主题），本篇把它从人类需求罗盘的「空白×高频」第一格升格为可行动正典。全篇**教育目的**：生理科普+求医路径+药物安全+预防行动卡+谣言证伪，零色情内容；不替代任何面诊与医嘱。结构化图（本篇全部节点·供织网道消费）在 `data/healing/sexual-health-map-20260912.json`，收据在 `system/control/receipts/2026-09-12-sexual-health/FINDINGS.md`。

**边界（先行声明）**：①本典为**成人**教育向——未成年人问题一律由监护人经学校教育/专业医疗渠道处理，本典不展开；②遭遇非自愿性行为/亲密关系暴力：第一优先是安全与医疗，走专业求助线（见第九节红旗卡），本典只转介不处置；③所有用药决定（含 PDE5 抑制剂、激素类）需处方医生面诊。

---

## 第一节 生理面：定义与反应周期

### 1.1 WHO 工作定义（FACT·已核原文）

WHO 正式工作定义：性健康是**与性相关的身体、情感、精神和社会适应的完好状态**——不仅是没有疾病、功能障碍或虚弱（"a state of physical, emotional, mental and social well-being in relation to sexuality…not merely the absence of disease, dysfunction or infirmity"，WHO 性健康主题页 2026-09-12 核）。含义：性健康的评价维度天然包含心理与关系面，「只查器官不问心理与关系」的口径不完整。

### 1.2 性反应周期模型（MODEL 框架·如实标注，不冒充生理事实）

| 模型 | 内容 | 认识态与用途 |
|---|---|---|
| Masters & Johnson 线性四期（1966《人类性反应》） | 兴奋→平台→高潮→消退 | MODEL：生理测量的经典框架；对人群拟合不完全，滞后于临床 |
| Kaplan 三相模型 | 欲望→兴奋→高潮 | MODEL：临床分型好用（对应三类困扰分层） |
| Basson 圆环/亲密驱动模型（2000·被引 430；2002） | 长期关系中欲望可为「反应性」——由亲密与刺激引发而非先自发产生；出发点多变 | MODEL：解释「先有亲密接触才 desire」的正常性，减少误诊「无欲望病」 |
| 双重控制模型（Bancroft & Janssen；2009 综述被引 217；2023 scoping review） | 性反应=「兴奋系统（油门）×抑制系统（刹车）」双闸门；焦虑/分心/压力是典型刹车 | MODEL：把「心理性困扰」机制化的主流研究框架 |

**诚实条款**：以上是**概念框架（MODEL）**，不是生理终稿；互相不排斥，临床上按问题选模型。

### 1.3 激素面：睾酮/雌激素×欲望——关系与限度

- **睾酮×男性欲望**：低睾酮与性欲下降、晨勃减少相关（FACT·关联级）；对确证性腺功能减退者，睾酮治疗对性功能改善为**小到中等**（Bhasin & Snyder NEJM 2025 综述；Cochrane 2018「Testosterone supplementation in men with sexual dysfunction」）。**限度（FACT·同等重要）**：并非所有低欲望者都低睾酮；睾酮不解决心理与关系因素；长期心血管安全性仍在追踪，须内分泌/男科评估后使用，非「补剂」。
- **雌激素×女性**：绝经后雌激素下降→阴道干涩/萎缩（现称 GSM，泌尿生殖综合征）→性交不适（FACT·指南级）；局部低剂量雌激素是妇科标准处理方向之一（遵妇科医嘱）。**欲望面**：Basson 2021 综述「Are Androgens at Fault?」指出女性性困扰中雄激素并非主因——女性低欲望≠缺激素（MODEL/综述级），先查心理与关系面。
- **高泌乳素/甲状腺/糖尿病**：均经内分泌通路影响欲望与功能（FACT·机制级）——这正是欲望骤降要查血而不是直接买补剂的原因（行动卡见第七节）。

### 1.4 年龄变化谱（FACT 级方向·个体差异大）

- 男性：勃起所需刺激增强/潜伏期延长、不应期随龄延长、ED 患病随年龄显著上升（Laumann 1999 与后续共识一致方向）。
- 女性：绝经前后润滑下降/组织变化（GSM）；围绝经期欲望波动常见。
- **正常谱≠疾病**：上述变化是老化谱的一部分；健康老年人维持性生活常见且与生活质量正相关（共识方向级）。变化的**速度与程度**异常（如数月内骤降、伴其他症状）才进入求医路径。

---

## 第二节 四类困扰分层：流行率区间与求医路径

### 2.1 分层与流行率（FACT·引用级·区间如实）

| 困扰类 | 内容 | 流行率面（区间） | 首选科室 |
|---|---|---|---|
| 欲望类（desire） | 性欲/性兴趣低下或缺失 | 女性最常见的一类；共识给区间不给单值（McCabe 2016 第四届国际性医学咨询共识·女性性欲类居首）；Laumann 1999：美 18-59 岁女性 43%/男性 31% 自报至少一类困扰 | 心理咨询/性治疗→内分泌排查 |
| 兴奋类（arousal） | 男性 ED；女性润滑/持续兴奋难 | 男性 ED 患病随龄陡升（共识一致方向）；ED 在中老年男性极常见 | 泌尿男科（男）/妇科+性医学科（女） |
| 高潮类（orgasm） | 高潮困难/早泄/延迟 | 早泄为男性最常见高潮类主诉（共识方向级）；率区间视定义宽 | 泌尿男科/性医学科 |
| 疼痛类（pain） | 性交痛/阴道痉挛 | 女性某时点自报性交痛相当常见（区间视定义宽） | 妇科（先排除器质）→盆底/性治疗 |

**关键区分（FACT·DSM-5 体系）**：「困扰」（自报问题）≠「障碍」（伴显著痛苦/功能损害+持续时长条件）。多数自报困扰不构成障碍；是否需要处理看痛苦度与功能影响，不是看「和不一致的标准比」。

### 2.2 求医路径行动卡（本典核心交付）

```text
第一步 分类：欲望低 / 兴起难（ED·润滑） / 高潮问题·早泄 / 疼痛 → 对应上表首选科室
第二步 查药：正在吃的药先过一遍（第二节 2.3 药物面）——药物性影响先排查，勿自行停药
第三步 查血：欲望/功能骤降 → 内分泌面筛查（睾酮/泌乳素/甲状腺/血糖）
        ED 且<40 岁或有心血管风险 → 同步做心血管代谢评估（见红旗卡）
第四步 心理与关系面：查因未见器质问题 / 伴焦虑-关系紧张 → 认证性治疗/伴侣咨询（有 RCT 级证据，见第五节）
第五步 复盘：任何「助性」处方药须处方医生评估；网购壮阳药=高风险来源（成分不明×硝酸酯污染风险）
```

### 2.3 药物性性功能影响（如实列·行动卡「先别停药」）

- **SSRI 类抗抑郁药**：治疗中出现性功能障碍为常见副作用——meta 分析（Serretti & Chiesa 2009·被引 357）显示总体常见且**不同药物间差异显著**（药物选择与调整属处方医生）；停药后持续综合征（PSSD）文献存在且机制未定谳（FACT：综述存在（2026 年新综述在刊）·机制 UNKNOWN）。**行动**：勿自行停药（抑郁复发风险）→ 与处方医生讨论换药/剂量/时窗方案。
- **降压药**：部分类别与性功能影响相关（老一代噻嗪类利尿剂/β 受体阻滞剂关联报告较多，ACEI/ARB 相对中性——MODEL 级，文献不一如实标）；换药决策归心内/处方医生。
- **抗精神病药**：高泌乳素机制相关（Serretti & Chiesa 2011 综述面）。
- **激素/化疗/阿片类长期使用**：均可经内分泌轴影响（机制级 MODEL）——用药清单是性困扰问诊的必查项。

---

## 第三节 药食/物质交互面（接 food-drug 正典）

### 3.1 硝酸酯×PDE5 抑制剂=绝对禁忌（FACT·可致命·红旗卡单列）

**机制**：硝酸酯（硝酸甘油/单硝酸异山梨酯等，含舌下含服急救药）与 PDE5 抑制剂（西地那非/他达拉非等）同走 NO-cGMP 通路——叠加抑制→**血压骤降可致命**。心血管安全综述（Cheitlin 2003；Jackson, Montorsi & Cheitlin 2006）一致口径：用硝酸酯者禁用 PDE5 抑制剂。**吸食型亚硝酸酯（"poppers"）同属硝酸酯类禁忌**（共识级）。时间窗（停 PDE5 后多久可用硝酸酯）由急救医生掌握，非患者自行处理项。

### 3.2 酒精：剂量依赖的双面（FACT·方向级）

- 低剂量：主观去抑制（中枢皮层抑制解除·主观「放开了」）——这是「酒能助性」传言的生理根源。
- 高剂量：**抑制**性反应周期各期（勃起与高潮阈值均升）——实验室剂量-反应与人群研究一致方向；「A Meta-Analysis of Erectile Dysfunction and Alcohol Consumption」存在（Europe PMC 标题级核·2026-09-12）。
- 长期酗酒：ED 高发+性腺轴抑制；戒断后部分可逆（戒酒 prospective 随访研究存在·标题级核）。
- **一句话口径**：低剂量去抑制×高剂量抑制反应=**剂量依赖双面（FACT）**；「借酒助性」在高剂量方向因果相反。

### 3.3 西柚汁×PDE5（机制承接 food-drug 正典）

西地那非经 CYP3A4 代谢，西柚汁抑制肠道 CYP3A4→血药浓度升高（机制同 food-drug 正典 A2 西柚机制条·引用不复制）——服 PDE5 期间避大量西柚汁（MODEL 级定量未定谳·方向 FACT）。

### 3.4 性别 affirming 激素的监测面（一句带过·专业面遵医嘱）

性别 affirming 激素治疗是正规内分泌治疗：性激素水平+血常规/血脂/血栓风险等按指南定期监测（Endocrine Society 临床实践指南 Hembree 2017·被引 1485）——本典不展开剂量与方案，专业面一律遵专科医嘱。

---

## 第四节 关系与沟通面

### 4.1 沟通>技巧：干预证据面

- 性困扰多为「双人事件」：压力/关系紧张/性沟通缺失是心理性困扰的核心路径（双重控制模型的「刹车」项·MODEL）。
- **心理类干预有 RCT 级证据**：Brotto 等 2021（J Consult Clin Psychol·正念认知疗法 vs 支持性性教育·女性性兴趣/唤起障碍 RCT·被引 44）；Cochrane 2019「Bibliotherapy for sexual dysfunction」（自我帮助读物类干预证据有限但存在）。**对照**：纯「技巧型产品」宣称（课程/器具的疗效话术）证据弱（FACT：无合格对照证据面）。
- **行动卡**：把「谈」列为第一干预——与伴侣谈期望/不适/界限（FACT 级：沟通面干预有 RCT 锚），技巧在沟通之后；自助无效且痛苦显著→认证性治疗/伴侣咨询。

### 4.2 HPV 疫苗与筛查（癌症预防 FACT 级行动卡）

- **疫苗**：HPV 疫苗接种项目降低社区 HPV 相关疾病率（Cochrane 2025·Henschke 等人群程序综述）+ 网络meta（Cochrane 2025·Bergman 等：疫苗预防宫颈癌及 HPV 相关疾病）。**行动**：适龄者按当地免疫规划接种（价数/年龄扩延遵当地指南）；接种常见局部反应/晕厥报告存在，大规模证据面未见新增严重风险信号（Cochrane 2025 口径·如实）。
- **筛查不豁免**：疫苗不覆盖全部高危型——**接种疫苗者仍按指南做宫颈癌筛查**（FACT·指南一致；筛查间隔按 PG screening_schedule 已库面执行）。

### 4.3 避孕方法有效谱：完美使用 vs 典型使用（最重要的公开健康事实之一·FACT）

| 方法 | 完美使用（第一年失败率） | 典型使用 | 差距来源 |
|---|---|---|---|
| 口服复方避孕药 | ~0.3% | ~7-9%（NSFG 口径区间） | 需每天正确操作——漏服是典型结局 |
| 男用避孕套 | ~2% | ~13%（每 100 人·年） | 需每次全程正确使用 |
| LARC（宫内节育器/皮下植入） | <1% | <1% | **无需每次操作**——典型≈完美 |
| 体外排精/安全期 | （有条件给出） | 显著更高（波动大） | 依赖每次行为正确与周期预测 |

（Trussell 2011 Contraception·被引 889；Sundaram 2017 NSFG 更新；CDC/权威科普口径一致核验。）

- **读表法（本节真交付）**：方法有效性必须**双列读**——「说明书有效率」是完美使用，「人群实际有效率」是典型使用；**差距全部来自「每次都要做对」的操作负担**。选型时把操作负担当主要变量。
- **双重保护**：避孕套是唯一同时显著降低 STI 风险的避孕方法（FACT·共识级）——「避孕方案」与「STI 防护」是两个问题，前者答后者不一定答。

---

## 第五节 认证/证伪面：网络传言 5 条

| # | 传言 | 判定 | 证据与 falsifier |
|---|---|---|---|
| 1 | 「禁欲保精延寿（一滴精十滴血）」 | **无证据（传言 CONTRADICTED）** | 精液主要成分为水/蛋白/果糖，射精不损耗所谓「精气」（生理学常识级）；观察性研究方向相反或未定：Rider 2016（Eur Urol·被引 57）：射精频率 ≥21 次/月组前列腺癌风险**更低**（HR≈0.80·观察性）；Leitzmann 2004（JAMA·被引 59）：年轻组高频率组风险更高——**两研究如实两立=因果方向 UNKNOWN**；但无论方向，均不支持「保精获益」。falsifier：任何前瞻干预证明禁欲改善寿命/前列腺结局 |
| 2 | 「伟哥一吃伤心脏、会成瘾」与「伟哥保健壮阳人人可吃」（双向谣言） | **均 CONTRADICTED** | 真实红线唯一且明确：**硝酸酯合用=致命禁忌**（FACT）；无硝酸酯者经处方评估使用心血管安全性良好（Cheitlin 2003/Jackson 2006 综述面）；它不是增强剂——无适应证滥用+网购来源（成分不明）才是真实风险面。falsifier：无硝酸酯人群中按医嘱使用的 RCT 级心血管危害信号 |
| 3 | 「酒精助性/酒能壮阳」 | **剂量依赖双面·高剂量方向相反（CONTRADICTED）** | 低剂量去抑制（主观）×高剂量抑制反应（生理·实验室剂量-反应+人群一致）；长期酗酒 ED 高发且戒断后部分可逆（prospective 研究）。falsifier：高剂量组勃起/高潮指标优于对照的稳健证据 |
| 4 | 「HPV 疫苗导致不孕/严重后遗症」 | **CONTRADICTED（证据面）** | Cochrane 2025 人群程序综述+网络 meta：预防效力确立， harms 面未见新增严重风险信号（局部反应/晕厥报告存在·如实）；「卵巢早衰」个案报道未成因果证据面。falsifier：合格对照研究证实卵巢功能损害 |
| 5 | 「睾酮补剂=壮阳万能/抗衰神药」 | **CONTRADICTED（限度面）** | 性腺功能减退者性功能改善小-中等（NEJM 2025 综述/Cochrane 2018）；睾酮正常者补剂获益证据弱+长期心血管安全性仍在追踪；欲望低先查因（泌乳素/甲状腺/血糖/心理）而非直接补。falsifier：睾酮正常人群长期 RCT 显示抗衰/功能获益 |

---

## 第六节 一页行动卡汇总（打印向）

**求医选择**：欲望低→性治疗/心理咨询+内分泌查血；ED→泌尿男科（<40 岁或有心血风险同步心内评估）；早泄/延迟→泌尿男科；性交痛/出血→妇科；查因不明→性医学门诊。
**用药三查**：①新药后出现性功能变化→查说明书性功能副作用条目并与处方医生谈；②抗抑郁药性副作用常见且可调（勿自行停）；③服 PDE5 前自问「我在用任何硝酸酯吗」——在用=禁忌。
**预防三件**：适龄 HPV 疫苗（接种≠免筛查）；宫颈癌筛查按表；避孕选型双列读表（完美 vs 典型）+避孕套双层防护 STI。
**沟通第一**：与伴侣的性沟通=有 RCT 锚的第一干预；痛苦显著或自助无效→认证性治疗。
**生活方式**（方向级 MODEL·非性功能特效药）：规律运动/控糖/戒烟/限酒——血管健康与勃起功能同路（T2DM×ED 见 docs/healing/deep-card-t2dm-20260912.md）。

## 第七节 就医红线（红旗卡·单列）

| 红旗 | 动作 |
|---|---|
| 正在用硝酸酯（含急救舌下含服）+ 想用/在用 PDE5 抑制剂 | **禁忌**——先心内科重新评估用药方案 |
| 阴茎异常勃起 >4 小时（痛或不痛） | **立即急诊**（缺血损伤风险·时间敏感） |
| 睾丸/阴囊急性剧痛 | **立即急诊**（扭转时间窗·小时级） |
| 性交后出血 / 绝经后出血 | 尽快妇科（宫颈筛查红线） |
| 欲望骤降 + 溢乳/头痛/视野缺损 | 尽快内分泌（高泌乳素/垂体评估） |
| 新发 ED + 胸痛/气短/运动耐量下降 | 先心内科（ED 可为血管病哨点·MODEL 级提示） |
| 性活跃 + 尿痛/异常分泌物/生殖器溃疡 | STI 检测（拖延=并发症+传播） |
| 遭遇非自愿性行为/亲密关系暴力 | **安全第一**：警方/妇联/心理危机热线/医疗机构——本典只转介不处置 |
| 未成年人性问题 | 监护人+学校教育/专业医疗渠道（本典成人向·不展开） |

## 第八节 falsifier 表（本典整体可证伪面）

1. 流行率数字随定义/年代/文化漂移——引用必须带来源与年份；新一版国际咨询共识发布即重算区间。
2. Basson/双重控制模型若被更强机制框架替代（如新预测加工框架获得 RCT 级区分效度）→ 模型节重写。
3. 睾酮长期心血管安全性以进行中的大型 RCT 追踪为准——TRAVERSE 类新结果落地即更新限度表述。
4. 避孕典型使用失败率每轮国家调查（NSFG 类）更新即刷新。
5. PSSD 机制从 UNKNOWN 升格（定谳机制+可重复生物标志）→ 2.3 节改写。
6. 传言证伪表是活的：任一传言出现合格反证研究即翻案并记录（不删历史判定）。

## 第九节 源头指针与更新路径

- 图数据：`data/healing/sexual-health-map-20260912.json`（≥25 节点 ≥35 边·接 drug:/food:/need: 命名空间）
- 收据：`system/control/receipts/2026-09-12-sexual-health/FINDINGS.md`（检索通道/锚点核验/隐私扫描）
- 接口：food-drug 正典（西柚/硝酸酯机制承接）·T2DM 深卡（慢病×ED）·red_flags 表（红旗模式）·screening_schedule（筛查间隔）
- v2 候选：孕产期/围绝经期性健康专面·疼痛性交专卡·盆底康复×性功能·LGBTQ+ 专面·中华文化语境伴侣沟通行动卡（引关系修复正典接口）

- English edition: [i18n/en/sexual-health-en-v1.md](i18n/en/sexual-health-en-v1.md)
