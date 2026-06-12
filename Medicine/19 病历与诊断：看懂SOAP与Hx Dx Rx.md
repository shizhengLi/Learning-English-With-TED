# 19 病历与诊断：看懂SOAP与Hx Dx Rx

## Opening Scene

> "58yo M c/o CP x 2d, SOB on exertion. Hx of HTN. BP 150/95, HR 102."

第一次翻开一份英文病历，你大概率会怀疑自己学的是假英语：满纸的 yo、c/o、Hx、x 2d，像是密码本被人撕掉了一半。但医生护士看一眼就懂——"58岁男性，主诉胸痛2天，活动后气促，有高血压病史，血压150/95，心率102。"

这不是医生在故弄玄虚。病历是写给同行看的工作文件，每天要写几十份，能省一个字母绝不多写一个。久而久之，这套缩写就成了全世界医院通用的"速记暗号"。

好消息是：这套暗号的规则极其简单，常用的就那么二三十个。这一篇我们把病历的骨架（SOAP 四段式）和最高频的缩写一次拆完。读完之后再回头看开头那行天书，你会发现它简直是大白话。

## 核心词汇 Core Vocabulary

先上术语表——这些是谈论病历和诊断时绕不开的"正经词"：

| #   | 英文                   | 音标                       | 中译     | 词根拆解                            | 一句话记忆               |
| --- | ---------------------- | -------------------------- | -------- | ----------------------------------- | ------------------------ |
| 1   | medical record         | /ˈmɛdɪkəl ˈrɛkərd/         | 病历     | record = re(再) + cord(心)→记在心上 | 病人的全部档案           |
| 2   | chart                  | /tʃɑːrt/                   | 病历表   | 源自希腊 chartes（纸张）            | 美剧里医生抱着的夹板     |
| 3   | diagnosis              | /ˌdaɪəɡˈnoʊsɪs/            | 诊断     | dia(穿过) + gnosis(知道)            | 看穿病情                 |
| 4   | differential diagnosis | /ˌdɪfəˈrɛnʃəl ˌdaɪəɡˈnoʊsɪs/ | 鉴别诊断 | differ(不同) + diagnosis            | 候选病因排除法           |
| 5   | prognosis              | /prɑːɡˈnoʊsɪs/             | 预后     | pro(预先) + gnosis(知道)            | 预知结局                 |
| 6   | assessment             | /əˈsɛsmənt/                | 评估     | assess = ad(去) + sess(坐)→坐下来判 | 医生的综合判断           |
| 7   | chief complaint        | /tʃiːf kəmˈpleɪnt/         | 主诉     | chief(首要的) + complaint(抱怨)     | 病人最想解决的那个问题   |
| 8   | admission              | /ədˈmɪʃən/                 | 入院     | ad(向) + mission(送)→送进来         | 办住院手续               |
| 9   | discharge              | /dɪsˈtʃɑːrdʒ/              | 出院     | dis(解除) + charge(负责)            | 医院"卸下"对你的责任     |
| 10  | discharge summary      | /dɪsˈtʃɑːrdʒ ˈsʌməri/      | 出院小结 | summary = sum(总和)                 | 这次住院的"结案报告"     |
| 11  | follow-up              | /ˈfɑːloʊ ʌp/               | 随访复诊 | follow(跟) + up(上)                 | 出院后回来"汇报近况"     |
| 12  | referral               | /rɪˈfɜːrəl/                | 转诊     | re(回) + fer(带)→把病人带给别人     | 介绍你去看专科           |

再上缩写表——病历上真正高频出现的就是它们：

| 缩写 | 全称                    | 中译       | 记忆点                         |
| ---- | ----------------------- | ---------- | ------------------------------ |
| Hx   | history                 | 病史       | H + x，x 代表后面省略的部分    |
| Dx   | diagnosis               | 诊断       | D + x，同上                    |
| Rx   | prescription / treatment | 处方/治疗  | 源自拉丁 recipe，药房标志 ℞    |
| Tx   | treatment               | 治疗       | T + x                          |
| Sx   | symptoms                | 症状       | S + x                          |
| Fx   | fracture                | 骨折       | F + x                          |
| c/o  | complains of            | 主诉       | 病人"抱怨"什么                 |
| yo   | years old               | 岁         | 58yo = 58岁                    |
| M/F  | male / female           | 男/女      | 性别一栏                       |
| BP   | blood pressure          | 血压       | B 血 + P 压                    |
| HR   | heart rate              | 心率       | H 心 + R 率                    |
| NPO  | nil per os（拉丁）      | 禁食       | "嘴巴里什么都不许进"           |
| stat | statim（拉丁）          | 立即       | 美剧名台词 "Get him to OR, stat!" |
| PRN  | pro re nata（拉丁）     | 必要时     | 疼了再吃，不疼不吃             |
| N/V  | nausea / vomiting       | 恶心呕吐   | 两个症状打包出现               |
| SOB  | shortness of breath     | 呼吸急促   | 喘不上气（不是骂人那个词！）   |
| WNL  | within normal limits    | 正常范围内 | 检查报告里最让人安心的三个字母 |

两点点评。第一，注意缩写表里混进了好几个拉丁词（NPO、stat、PRN）——医学英语的拉丁底色在病历上体现得淋漓尽致，这和第 01 篇讲的历史一脉相承。第二，"X 字母 + x"的家族（Hx/Dx/Rx/Tx/Sx/Fx）是病历缩写里最有规律的一支，下面 Deep Dive 专门讲它的来历。

## Deep Dive

### 1. SOAP：全世界病历的通用骨架

SOAP 不是肥皂，而是病程记录的四段式结构，全球医院通用：

- **S = Subjective（主观资料）**：病人自己说的。"我胸口疼了两天"——这是病人的叙述，医生没法直接验证，所以叫"主观"。主诉（chief complaint）就写在这一段。
- **O = Objective（客观资料）**：查出来的。血压、心率、化验单、心电图——仪器和体格检查给出的硬数据，不掺主观感受。
- **A = Assessment（评估）**：医生的判断。综合 S 和 O，医生给出诊断或者鉴别诊断清单。
- **P = Plan（计划）**：下一步怎么办。开什么药、做什么检查、要不要住院、何时复诊。

一个迷你示例，感受一下：

- **S**: Patient reports headache for 3 days.（病人说头痛三天）
- **O**: BP 130/85, temperature 37.2°C.（血压、体温数据）
- **A**: Tension headache, likely.（评估：可能是紧张性头痛）
- **P**: Ibuprofen PRN, follow-up in 1 week.（计划：布洛芬必要时服用，一周后复诊）

记住一个口诀：**病人说的归 S，查出来的归 O，医生想的归 A，接下来做的归 P。**练习题里我们会专门考这个归类。

### 2. "x 字尾家族"的来历：从药房标志 ℞ 说起

Hx、Dx、Rx、Tx、Sx、Fx——为什么都带个 x？

故事要从 **Rx** 讲起。它源自拉丁语 **recipe**，是动词"取用"的命令式——古代医生在处方开头写下这个词，意思是命令药剂师"取以下药材"。手写时 R 的尾巴上习惯划一道斜线，久而久之就成了药房门口那个标志 **℞**。今天英语里的 recipe（菜谱）和处方是同一个词的两个分身：一个让药剂师抓药，一个让厨师抓食材。

Rx 流行开之后，医生们发现"首字母 + x 表示省略"这个模式实在好用，于是依葫芦画瓢造出了一整个家族：history → **Hx**，diagnosis → **Dx**，treatment → **Tx**，symptoms → **Sx**，fracture → **Fx**。这里的 x 不读音，就是个"后面的字母我懒得写了"的占位符。一通百通，以后在病历上见到"大写字母 + x"，先往这个家族猜。

### 3. diagnosis 与 prognosis：看穿现在，预知未来

用第 02 篇的拆词公式拆一下这对兄弟：

- **diagnosis** = dia（穿过）+ gnosis（知道）→ 穿透表面症状、"看穿"病情本质 = 诊断
- **prognosis** = pro（预先）+ gnosis（知道）→ 提前知道病程走向 = 预后

gnosis 这个希腊词根就是"知道"，英语 know 和它是远房亲戚。一个 dia 一个 pro，前缀一换，"看穿现在"就变成了"预知未来"。

那 **differential diagnosis（鉴别诊断，缩写 DDx）**又是什么？它是医生的"排除法游戏"。胸痛可能是心梗、肺栓塞、胃食管反流，也可能只是肌肉拉伤——医生先列出所有候选答案，再用检查逐个排除，最后剩下的就是答案。《豪斯医生》整部剧演的就是这个游戏：白板上写满候选诊断，然后一个个划掉。

### 4. 出入院词族：从 admit 到 referral

围绕"住院"这件事有一组固定搭配，串成一条时间线记：

1. **admit / admission（入院）**：病情需要住院观察，"He was admitted to the cardiology ward."（他被收进了心内科病房。）
2. **discharge（出院）**：dis（解除）+ charge（责任）——医院解除对你的照护责任，放你回家。
3. **discharge summary（出院小结）**：出院时的"结案报告"，写明这次住院的诊断、治疗经过和出院医嘱，下一位接手的医生全靠它了解你的情况。
4. **follow-up appointment（随访复诊）**：出院不等于结束，"Follow-up in 2 weeks" 意思是两周后回门诊复查。
5. **referral（转诊）**：全科医生搞不定的问题，写一封 referral 把你介绍给专科医生——"I'll give you a referral to a cardiologist."（我给你转诊到心内科专家那里。）

## Read & Practice 实战

来一份完整的迷你 SOAP note，正是急诊科医生每天写的那种。先整体看一遍：

> **S:** 58yo M c/o chest pain x 2 days, worse on exertion. Reports SOB and N/V this morning. Hx of HTN.
> **O:** BP 150/95, HR 102. Lungs clear. ECG shows ST changes.
> **A:** Chest pain, rule out acute MI. DDx: angina, GERD.
> **P:** Admit. NPO. Aspirin stat. Morphine PRN for pain. Cardiology referral.

逐行破译：

- **58yo M c/o chest pain x 2 days** —— 58岁男性，主诉胸痛2天。注意这个 **x** 不是字母，是乘号"×"，表示"持续了……"，x 2 days = 持续两天。
- **worse on exertion** —— 活动后加重。exertion（用力、体力活动）是描述症状加重诱因的高频词，更多症状描述的套路见第 16 篇。
- **Reports SOB and N/V this morning** —— 自述今晨出现呼吸急促和恶心呕吐。reports 和 c/o 一样，都是"病人说"的标记词，所以这些都归在 S 段。
- **Hx of HTN** —— 高血压（hypertension）病史。Hx of... 是交代既往史的固定句式。
- **BP 150/95, HR 102. ECG shows ST changes** —— 血压、心率、心电图，全是仪器给的硬数据，标准的 O 段内容。
- **rule out acute MI** —— "需排除急性心肌梗死"。rule out（排除）是 A 段的灵魂动词，意思是"高度怀疑，待检查证实或排除"。
- **DDx: angina, GERD** —— 鉴别诊断：心绞痛、胃食管反流。排除法游戏的候选名单。
- **Admit. NPO. Aspirin stat. Morphine PRN.** —— 收入院；禁食（可能要做检查或手术）；阿司匹林立即给；吗啡必要时给（疼了才用）。四个词组、四条医嘱，P 段的简洁风格一览无余。

## Practice 练习

**Ⅰ. 缩写破译：把下面的病历短句翻译成"人话"（中文）**

1. 45yo F c/o headache x 3d.
2. Hx of DM, no Sx today.（DM = diabetes mellitus 糖尿病）
3. Pt NPO after midnight, surgery at 8 am.（Pt = patient）
4. Tylenol PRN for fever, recheck BP stat.
5. Fx of left wrist, Tx: cast x 6 weeks.

**Ⅱ. SOAP 归类：下面各句属于 S / O / A / P 哪一段？**

1. Patient states the pain started after dinner.
2. Temperature 38.5°C, HR 96.
3. Order chest X-ray and start antibiotics.
4. Likely pneumonia, rule out bronchitis.

**Ⅲ. 中译英**

1. 主诉：胸痛2天。（用缩写写成病历体）
2. 他昨天出院了，两周后复诊。
3. 医生给了我一封转诊信去看神经科医生（neurologist）。

---

**参考答案**

- Ⅰ.
  1. 45岁女性，主诉头痛3天。
  2. 有糖尿病病史，今日无症状。
  3. 病人午夜后禁食，早上8点手术。
  4. 发热时必要时服泰诺，立即复测血压。
  5. 左腕骨折，治疗：石膏固定6周。

- Ⅱ.
  1. S（病人自己说的）
  2. O（仪器测出来的）
  3. P（下一步的检查和用药计划）
  4. A（医生的判断与鉴别诊断）

- Ⅲ.
  1. c/o chest pain x 2 days.
  2. He was discharged yesterday, with a follow-up in 2 weeks.
  3. The doctor gave me a referral to a neurologist.

---

📌 **下一篇预告**：**20 药物与处方：从剂型到bid tid**——处方上的拉丁暗号一次说清：bid、tid、qd 到底一天吃几次？tablet、capsule、ointment 都是什么剂型？看完这篇，药盒说明书不再靠猜。
