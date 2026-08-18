# MAIT 选课冲突、课程关联与职业方向建议

> [!info] 分析范围
> - 时间冲突以 [[Subject Description/Sem 1|Semester 1 Class Timetable]] 为准，课表更新时间为 **2026-08-14 11:15:40 HKT**。
> - 课程关联与职业建议基于工作区内 Compulsory subjects 和 Elective Subjects 的全部 27 份课程说明。
> - 就业趋势资料检索日期为 **2026-08-17**。
> - 教室、教师及开课安排仍可能调整，最终以 eStudent 选课系统为准。

## 核心结论

如果暂时没有明确职业方向，三门选修优先考虑：

> **COMP5423 Natural Language Processing + DSAI5204 Efficient Data Processing + COMP5355 Cyber and Internet Security**

这三门分别补足 AI 应用、数据系统和安全能力，彼此内容重复较少。在合理选择必修课班次后，Sem 1 可以做到完全不撞课。

校方当前课程结构是 7 门必修、3 门选修，共 30 学分，另有 1 学分的学术诚信课。因此，每个选修名额都很宝贵。

- [PolyU MAIT 官方课程结构](https://www.polyu.edu.hk/ama/study/pg/master-mathematics-for-artificial-intelligence-technology/curriculum/)

## 一、Sem 1 所有时间冲突

### 完全冲突

| 时间 | 冲突课程 | 说明 |
|---|---|---|
| 周一 18:30–21:20 | AMA571 周一班 ↔ COMP5355 | 全学期完全重合 |
| 周三 18:30–21:20 | AMA567 ↔ COMP5523 ↔ DSAI5204 | 三门课只能选一门 |
| 周四 18:30–21:20 | AMA524 ↔ AMA528 周四班 ↔ COMP5423 | 三门课只能选一门 |
| 周五 18:30–21:20 | COMP5112 ↔ COMP5434 | 全学期完全重合 |

### 部分学期冲突

| 冲突课程 | 冲突周次 | 说明 |
|---|---:|---|
| AMA571 周二班 ↔ DSAI5104 | 第 1–7、10–13 周 | 几乎整个学期冲突，不可视为可兼容 |
| COMP5112 ↔ DSAI5104 | 第 8–9 周 | 两周完全重合 |
| COMP5434 ↔ DSAI5104 | 第 8–9 周 | 两周完全重合 |
| AMA528 周一班 ↔ DSAI5T09 周一班 | 第 1–13 周，10:30–11:20 | 每周重叠最后 50 分钟 |

### 可用于避让的班次

- AMA528：周一上午或周四晚上。
- AMA571：周一晚上或周二晚上。
- DSAI5T09：课表看起来有周一和周六两个在线班次。
- DSAI5104：第 8–9 周自动改为周五，没有其他班次。

> [!warning] 班次权限待确认
> 课表中的不同 Subject Group 不一定全部对 MAIT 学生开放。尤其 DSAI5T09 的两条记录看起来像平行班，但仍应在 eStudent 中确认是否可以只选周六班。

### 推荐的无冲突必修排法

| 课程 | 推荐时段 |
|---|---|
| AMA528 | 周一 08:30–11:20 |
| AMA564 | 周一 12:30–15:20 |
| DSAI5104 | 周二；第 8–9 周改周五 |
| DSAI5T09 | 周六在线班 |

在此基础上，可以无冲突地从以下三组各选一门：

- 周一晚上：AMA571 或 COMP5355。
- 周三晚上：AMA567、COMP5523 或 DSAI5204。
- 周四晚上：AMA524 或 COMP5423。

因此，`COMP5355 + DSAI5204 + COMP5423` 是当前最整齐的三门组合。

如果 AMA528 被迫安排在周四，则本学期无法再上 AMA524 或 COMP5423。此时可以考虑把 COMP5423 延后到 Sem 2，但需要等 Sem 2 正式课表确认。

## 二、课程重合度与知识联系

以下“高、较高、中”是根据课程大纲逐项比较得出的课程规划判断，不是校方公布的数据。

### 整体知识网络

| 能力群 | 课程 | 关系 |
|---|---|---|
| 数学与学习理论 | AMA528、DSAI5104、AMA524、DSAI5103、AMA579 | 概率 → 优化/数值计算 → 高维统计与学习理论 |
| AI 模型主干 | AMA564、AMA574、AMA577、COMP5554、DSAI5105 | 深度学习 → 生成式 AI/RL → 综合应用 |
| NLP/LLM | COMP5423 | 承接 AMA564、AMA574，补充语言学、检索、问答和系统项目 |
| 视觉与多媒体 | COMP5523、DSAI5206、DSAI5209 | 视觉算法、现代视觉模型、图像视频表示与压缩 |
| 数据与系统 | COMP5112、DSAI5204、COMP5434 | 数据结构/数据库 → 分布式数据库 → 大数据平台 |
| 安全可信 | DSAI5T09、COMP5355、DSAI5208 | 通用伦理 → 网络安全 → AI 攻击、隐私和可信 AI |
| 金融科技 | AMA571、AMA569、AMA576 | 区块链金融、碳金融、算法交易 |
| 领域及前沿 | AMA578、BME5150、DSAI5203、AMA567 | 通用前沿综述、医疗 AI、类脑计算、量子计算 |

### 最需要避免重复选择的组合

| 课程组合 | 重合度 | 结论 |
|---|---|---|
| COMP5112 ↔ DSAI5204 | 高 | 都讲数据结构、排序搜索、关系数据库、SQL、索引和查询；后者多了事务和分布式数据库 |
| COMP5523 ↔ DSAI5206 | 高 | 都覆盖图像处理、CNN、特征、检测、分割、跟踪和 3D 视觉；一般不要两门都选 |
| AMA564 ↔ COMP5554 | 高 | 神经网络、CNN、RNN、Transformer、梯度训练重复明显；后者胜在广度而非深度 |
| DSAI5206 ↔ DSAI5209 | 较高 | 检测、分割和视觉数据处理重合；5209 更偏压缩、视频编码和水印 |
| AMA574 ↔ COMP5423 | 中 | 都涉及 LLM；但 NLP 还有句法、语义、序列标注、检索、问答与 RAG，因此不算重复选课 |
| DSAI5104 ↔ DSAI5103 | 中 | PCA、回归、聚类、正则化有交集；前者偏优化，后者偏高维统计 |
| DSAI5104 ↔ AMA524 | 中 | 牛顿法、拟牛顿法、线性代数和迭代方法重合；AMA524 另有 ODE/PDE 与数值积分 |
| AMA564 ↔ AMA579 | 中 | 偏差—方差、VC 维重合；AMA579 进一步进入 PAC、泛化界和算法稳定性 |
| AMA528 ↔ AMA569 | 中 | 概率、统计、Markov 过程是共同基础；AMA569 进一步进入时间序列和碳资产定价 |
| AMA577 ↔ AMA571/AMA576 | 中 | 都会使用强化学习；后两门强调金融应用 |
| DSAI5204 ↔ COMP5434 | 中 | 都涉及分布式数据处理；前者偏数据库原理，后者偏 Hadoop、Spark、NoSQL 和云平台 |
| COMP5355 ↔ DSAI5208 | 中 | 都涉及攻击、安全和隐私；前者是网络/Web 安全，后者是 AI 安全、深伪和隐私计算 |
| BME5150 ↔ AMA578/DSAI5105 | 中 | 医疗 AI 概论和通用 AI 应用会重复；BME5150 的价值主要是临床问题定义和医疗领域语境 |

### 相对独立、难以被其他课程替代的内容

- AMA567：量子信息与量子算法。
- DSAI5203：脉冲神经网络、脑信号和神经形态硬件。
- AMA576：市场微观结构、订单簿和交易执行。
- DSAI5208：深伪检测、差分隐私、同态加密、联邦学习和生物识别安全。

## 三、按就业方向推荐三门选修

全球就业趋势中，AI 与大数据、网络与网络安全是增长最快的技能方向；大数据专家、金融科技工程师、AI/ML 专家和软件开发人员也属于增长较快的岗位。香港政府的人力预测同样指出，AI 专家、数据分析师和 IT 专家的需求正在上升。

- [World Economic Forum: Future of Jobs Report 2025](https://www.weforum.org/publications/the-future-of-jobs-report-2025/digest/)
- [香港政府：最新人力推算报告](https://www.info.gov.hk/gia/general/202411/14/P2024111400292.htm)
- [香港人才清单：Innovation and Technology Experts](https://www.hkengage.gov.hk/en/talent-list/talent-details/innovation-and-technology-experts)

| 未来方向 | 推荐三门 | 说明 |
|---|---|---|
| 通用就业/尚未确定方向 | COMP5423 + DSAI5204 + COMP5355 | AI 应用、数据底座、安全，重复少且当前可排成无冲突组合 |
| LLM/NLP 应用工程师 | COMP5423 + DSAI5204 + COMP5434 | NLP/RAG + 数据库/分布式处理 + 大数据平台；COMP5434 最好放 Sem 2/3 |
| 计算机视觉/机器人 | DSAI5206 + DSAI5204 + DSAI5208 | 现代视觉 + 数据系统 + 可信视觉/深伪/隐私；若 5206 不开则换 COMP5523 |
| 数据工程/ML 平台 | DSAI5204 + COMP5434 + COMP5355 | 数据库、Spark/NoSQL/云、安全；不要再选 COMP5112 |
| 网络安全/AI 安全 | COMP5355 + DSAI5208 + DSAI5204 | 网络层安全、AI 攻防与隐私、数据系统 |
| 量化研究/算法交易 | AMA576 + DSAI5103 + AMA579 | 市场微观结构、高维统计、学习理论；偏理论和研究 |
| 金融科技/Web3 | AMA571 + COMP5355 + DSAI5204 | Solidity/DeFi、系统安全、数据后端；COMP5355 可放 Sem 3 避开 AMA571 |
| 医疗 AI | BME5150 + DSAI5206 或 COMP5523 + DSAI5208 | 临床问题、医学视觉、隐私和可信 AI |
| AI 科研/申博 | AMA579 + DSAI5103 + AMA524 | 学习理论、高维统计、数值方法；比再选一门综合 AI 概论更有价值 |
| 量子计算研究 | AMA567 + AMA524 + AMA579 | 数值线性代数、量子算法和理论基础；职业面很窄，主要面向研究 |

### 选课资格风险

- DSAI5103 标有前置课 AMA563/DSAI5102。
- DSAI5208 标有前置课 DSAI5205/DSAI5207。

这些前置课不属于当前 MAIT 必修组合，选课前必须确认能否以 AMA528、AMA564、DSAI5104 等课程申请豁免。

此外，BME5150 和 DSAI5206 虽然课程说明写着 Sem 1，但没有出现在当前 Sem 1 课表中，不能视为本学期已经确认开课。

## 四、更适合自学、不建议轻易占名额的课程

### COMP5112 Data Structures and Database Systems

数据结构、排序、SQL、ER 模型和数据库规范化都有大量成熟公开资源。如果已有计算机基础，直接选内容更完整的 DSAI5204。

### COMP5554 Advanced Artificial Intelligence

与必修的深度学习、生成式 AI、强化学习重合过多。GNN、元学习、联邦学习等缺口可按需自学。

### COMP5523 与 DSAI5206

只选一门。就业导向优先内容更现代的 DSAI5206；若本学期不开，再选 COMP5523。

### DSAI5209 Visual Data Representation and Processing

除非目标是视频编解码、多媒体、流媒体或数字水印，否则不如选现代视觉或数据系统课程。

### BME5150 Medical Artificial Intelligence and Data Analytics

如果不准备进入医疗行业，其通用 AI 部分会被 AMA578 和 DSAI5105 覆盖。

### AMA567 Quantum Computing for Data Science

量子计算很独特，但对普通 AI 岗位的转化率低。没有明确科研计划时，不值得占三分之一选修额度。

### AMA571 Financial Technology

如果只想学习 Solidity、钱包和 DeFi，可以通过自建项目学习；只有明确走金融科技或 Web3 时才值得选。

### AMA524 Scientific Computing

一般 AI 工程岗位可以自学 NumPy、SciPy 和数值方法；科学计算、仿真、量化或申博方向则值得正式修读。

### COMP5434 Big Data Computing

这门课处于临界位置。数据工程方向值得选；普通 AI 方向可以自学 Spark、云平台和数据管道，而且已有课程经验反映其内容偏广、偏理论。

## 最终决策原则

选修名额应优先用于获得以下资源：

1. 难以独立掌握的系统理论；
2. 有教师反馈的实战项目；
3. 特定行业的领域知识和人脉；
4. 与必修课互补、而不是再次复习同一套 AI 概论。

标准算法、通用工具和大范围综述课程应尽量通过自学完成，把三个选修名额留给真正能够形成职业差异化的能力。
