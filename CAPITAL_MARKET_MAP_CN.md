# 中国资本市场地图：一级 / 二级市场 × AI

用于建立一套可持续扩展的资本市场知识地图。目标不是按金融教材章节背知识，而是理解：**钱从哪里来、由谁管理、投向什么、如何形成判断、如何退出，以及 AI 可以在哪些真实工作流中创造价值。**

> 方法：先有地图，再把真实项目、公司、政策、交易和工具挂到地图上。制度事实优先使用证监会、交易所、中基协、交易商协会等官方来源；知乎、X、Reddit 等社区内容只用于观察从业者工作流、观点和实践，不直接当作事实。

---

## 0. 总地图

```text
                         中国的“钱”
                           │
        ┌──────────────────┼──────────────────┐
        │                  │                  │
       政府               机构               居民/企业
 政府引导基金/国资     银行/保险/基金      高净值/家办/公司
        │                  │                  │
        └──────────────────┼──────────────────┘
                           ↓
                    【资本配置机构】
                           │
          ┌────────────────┴────────────────┐
          │                                 │
       一级市场                           二级市场
   Private Markets                    Public Markets
          │                                 │
 VC / PE / CVC /产业基金          公募/私募证券/自营等
          │                                 │
          ↓                                 ↓
  未上市股权 / 并购 / Pre-IPO      股票/债券/ETF/REITs/
                                  期货/期权/衍生品
          │                                 │
          └────────────┬────────────────────┘
                       │
                    企业资产
                       │
           ┌───────────┼───────────┐
           ↓           ↓           ↓
          IPO         并购        经营现金流
           │
     一级 → 二级
```

遇到任何金融机构，先回答四个问题：

1. 钱是谁的？
2. 钱投到哪？
3. 凭什么判断？
4. 最后怎么把钱拿回来？

---

## 1. 中国一级市场：先理解中国特色资金结构

不要简单照搬美国 VC 模型。中国一级市场里，政府投资基金、国资、产业资本、市场化 GP、社会资本、地方产业政策之间经常相互连接。

```text
政府 / 国资 / 市场化LP
        ↓
政府投资基金 / 母基金 / 机构LP
        ↓
      子基金 GP
        ↓
VC / PE / CVC / 产业基金
        ↓
AI / 机器人 / 半导体 / 新能源 / 生物医药 / 制造业 ...
```

分析一个中国一级市场项目时，除了公司本身，还要看：

- 资金属性
- GP 的投资策略
- 地方产业政策
- 产业链位置
- 后续融资能力
- 退出路径

---

## 2. 一级市场三个主体

### LP：出钱的人

常见来源：

- 政府投资基金 / 引导基金
- 国资
- 保险等机构资金
- 企业
- 家族办公室
- 高净值个人
- 母基金 FoF

### GP：管钱的人

GP 负责基金运营和投资决策，包括募资、找项目、研究、尽调、投决、投后和退出。

### Portfolio Company：被投企业

```text
LP
 ↓ 出资
基金
 ↓ GP管理
项目
 ↓ 投资
创业公司 / 成熟企业
 ↓ 成长
IPO / M&A / 股权转让 / 回购
 ↓
资金回流
 ↓
LP + GP
```

---

## 3. 一级市场核心框架：募、投、管、退

### 3.1 募 Fundraising

```text
GP定位
 ↓
基金策略
 ↓
过往业绩 / 团队能力
 ↓
寻找LP
 ↓
LP Due Diligence
 ↓
基金设立
 ↓
Capital Call / 出资
```

后续知识节点：

- Fund Size
- Vintage Year
- Management Fee
- Carry
- IRR
- MOIC
- TVPI
- DPI

这些属于**基金层 economics**，不要和单个公司的估值混在一起。

### 3.2 投 Investment

```text
Sourcing 找项目
   ↓
Screening 初筛
   ↓
Founder / Management Meeting
   ↓
行业研究 + 公司研究
   ↓
Pre-DD
   ↓
Term Sheet
   ↓
Due Diligence
 ├─ Commercial DD
 ├─ Financial DD
 ├─ Legal DD
 └─ Technical DD
   ↓
Valuation
   ↓
Investment Memo
   ↓
IC 投资委员会
   ↓
SPA / SHA 等交易文件
   ↓
Closing
```

对 AI / FDE 来说，这是最值得拆解的工作流。

每个节点都问：

- 输入是什么？
- 信息在哪？
- 谁负责判断？
- 哪一步重复劳动最多？
- 哪一步最容易丢上下文？
- 哪一步可以自动化？
- 哪一步必须保留人类最终权限？

### 3.3 管 Portfolio Management

```text
投资完成
 ↓
经营数据 / 财务数据
 ↓
产品 / 客户 / 招聘 / 现金流 / 融资计划
 ↓
风险与异常
 ↓
董事会 / 月报 / 季报 / LP汇报
 ↓
下一轮融资 / 战略协同 / 并购 / IPO
```

AI 可切入：

- Portfolio Brief
- 指标异常预警
- 自动整理周报 / 月报
- 行业与竞争对手跟踪
- 董事会材料辅助
- 投后事项追踪

### 3.4 退 Exit

典型路径：

- IPO
- M&A
- Secondary 股权转让
- Buyback 回购

判断一个投资不能只看“公司是不是好公司”，还必须看最终能否实现流动性和资本回报。

---

## 4. 分析一个公司：一级市场最小判断框架

收到一个 Pitch Deck 后，不先算估值，先回答：

1. 公司到底做什么？
2. 为什么是现在？
3. 市场是否足够大？
4. Founder / 团队为什么有资格赢？
5. 技术 / 产品是否真实有效？
6. 客户为什么愿意付钱？
7. 商业模式与单位经济是否成立？
8. 竞争壁垒是什么？
9. 增长能否持续？
10. 估值是否留下回报空间？
11. 最大反例是什么？
12. 什么事实出现会证明投资逻辑错了？
13. 最可能如何退出？

核心：**一级市场是在不完全信息下做企业判断，不是估值模型竞赛。**

---

## 5. 二级市场：先按 Sell Side / Buy Side 建图

```text
                       二级市场

          Sell Side                 Buy Side
          卖方                        买方

     券商研究所                    公募基金
     投资银行                      私募证券
     经纪 / Sales & Trading        保险资管
                                  券商自营等
         │                           │
         └──────── 信息 / 服务 ──────┘
                          ↓
                       投资决策
```

### Buy-side 研究链

```text
Macro
 ↓
Industry
 ↓
Company
 ↓
Financial Model
 ↓
Valuation
 ↓
Investment Thesis
 ↓
Catalyst
 ↓
Risk
 ↓
Position Sizing
 ↓
Execution
 ↓
Monitoring
 ↓
Attribution
```

研究一个二级公司时至少输出：

- Business
- Industry
- Financials
- Valuation
- Thesis
- Catalyst
- Risk
- Bear Case

---

## 6. 国内二级市场基础设施节点

### 股票

```text
上海证券交易所
├─ 主板
└─ 科创板

深圳证券交易所
├─ 主板
└─ 创业板

北京证券交易所
└─ 与新三板体系衔接
```

### 债券

不要只停留在 duration / convexity / yield 等金融理论，需要补市场结构：

```text
中国债券市场
     │
 ┌───┴────────┐
交易所市场   银行间市场
```

重点继续挂：

- 国债 / 地方债
- 金融债
- 公司债
- 企业债
- 非金融企业债务融资工具
- 信用风险
- 利率曲线
- 信用利差

### 期货 / 期权

已有定价、期权、期货基础后，重点转向真实用途：

- 产业套期保值
- 资产管理风险控制
- 系统化交易
- 跨资产策略
- 市场微观结构
- 程序化交易监管

---

## 7. 知识树：以后所有新知识都挂这里

```text
CAPITAL MAP
│
├── 01 Money 钱从哪里来
│   ├─ 政府 / 国资
│   ├─ LP
│   ├─ 银行
│   ├─ 保险
│   ├─ 企业
│   └─ 个人 / 家办
│
├── 02 Institutions 谁在管钱
│   ├─ VC
│   ├─ PE
│   ├─ CVC
│   ├─ 产业基金
│   ├─ 公募
│   ├─ 私募证券
│   ├─ 券商
│   └─ 银行 / 保险资管
│
├── 03 Assets 钱买什么
│   ├─ Equity
│   ├─ Debt
│   ├─ Fund
│   ├─ Futures
│   ├─ Options
│   └─ REITs
│
├── 04 Private Market
│   ├─ 募
│   ├─ 投
│   ├─ 管
│   └─ 退
│
├── 05 Public Market
│   ├─ Research
│   ├─ Valuation
│   ├─ Portfolio
│   ├─ Trading
│   └─ Risk
│
├── 06 Company
│   ├─ Business Model
│   ├─ Accounting
│   ├─ Corporate Finance
│   ├─ Strategy
│   └─ Governance
│
├── 07 Industry
│   ├─ AI
│   ├─ Robotics
│   ├─ Semiconductor
│   ├─ Manufacturing
│   └─ 其他持续扩展
│
└── 08 AI × Capital
    ├─ Sourcing Agent
    ├─ Screening Agent
    ├─ Research Agent
    ├─ DD Agent
    ├─ IC / Memo Copilot
    ├─ Portfolio Agent
    ├─ LP Reporting Agent
    └─ Knowledge / CRM Agent
```

---

## 8. 当前学习优先级

### S：会计 + 公司分析

不是为了考试，而是能回答：

- 公司怎么赚钱？
- 收入怎么确认？
- 成本和现金流在哪里？
- 三张表如何联动？
- 增长来自哪里？
- 资产负债表有什么风险？

### S：一级项目 Workflow

真正理解：

`Sourcing → Screening → DD → Memo → IC → Closing → Portfolio → Exit`

### A：公司估值

优先：

- Comparable Companies
- Precedent Transactions
- DCF
- VC Method
- Cap Table / Dilution

LBO 暂后。

### A：行业研究

优先用熟悉的技术行业打灰：

- AI
- 机器人
- 半导体
- 企业软件
- 智能制造

### B：二级股票研究

不系统背书，直接选真实公司做：

`Business → Industry → Financials → Valuation → Thesis → Bear Case`

---

## 9. AI × Capital：Agent 机会地图

```text
Deal Sourcing
    ↓
Screening
    ↓
Research
    ↓
Due Diligence
    ↓
Investment Memo
    ↓
IC
    ↓
Portfolio Monitoring
    ↓
LP Reporting / Exit
```

可能的 Agent：

### Sourcing / Screening Agent

输入：BP、官网、新闻、数据库、历史项目。

输出：结构化公司卡片、赛道归类、初筛理由、缺失信息。

### Research Agent

输入：公司、行业、政策、竞争对手、论文、专利等。

输出：事实库、证据链、竞争格局、待验证假设。

### DD Agent

辅助整理材料、检查缺口、维护问题清单，但**不能把模型输出直接当 ground truth**。

### IC / Memo Copilot

把研究材料组织成 investment memo；事实、假设、推断、反例分栏；最终投资判断仍由人负责。

### Portfolio Agent

连接投后公司的经营数据、会议纪要、新闻和待办，生成 brief、风险提示和 follow-up。

### Knowledge / CRM Agent

把微信、邮件、会议纪要、BP、Excel、CRM、飞书等碎片信息连接起来，解决机构记忆丢失问题。

重要约束：

- 权限与保密
- 来源可追溯
- 人工最终决策权
- 冲突证据暴露
- 数据版本管理
- 敏感客户信息隔离

---

## 10. 面试 / 入职时的业务侦察问题

如果进入一家投资机构，不急着展示“会做 Agent”，先把业务图画出来。

优先问：

1. 你们主要做 VC、PE、FA、产业投资还是其他业务？
2. 一个项目从首次接触到最终投资，大致经过哪些环节？
3. 项目 / 客户信息主要存在微信、Excel、飞书、CRM 还是各种文档？
4. 现在最耗时间、最重复的信息工作是什么？
5. 哪些判断必须由投资人 / 创始人亲自做？
6. 最希望 Agent 先解决哪一个真实 workflow？
7. 什么输出才算“可用”，如何验收？

拿到答案后画：

```text
Input
 ↓
Data / Source
 ↓
Process
 ↓
Human Judgment
 ↓
Output
 ↓
Feedback
```

第一天优先画现状流程；第二步找重复劳动；第三步找信息断点；第四步找必须保留的人类判断；第五步才决定是否使用 Agent。

---

## 11. 建筑师学习法：地图 → 建筑 → 打灰

### 地图

先知道一个知识点属于哪里，不追求一次学透。

### 建筑

每遇到真实问题，都挂回地图。例如：

- LP 季报 → 一级 / 募 / LP Relations
- 看 BP → 一级 / 投 / Screening
- 调研机器人 → 一级 / 投 / Sector Research
- 财务整理 → 一级 / DD / Financial DD

### 打灰

用真实公司反复做 Mini Investment Memo：

1. 公司做什么？
2. 为什么现在？
3. 市场多大？
4. 商业模式？
5. 核心竞争优势？
6. 竞争者？
7. 关键数据？
8. 为什么值得投？
9. 最大风险？
10. 什么事实会证明我错了？
11. 如何退出？

目标不是“学完金融”，而是持续增加真实案例节点，让知识图越来越密。

---

## 12. 与 Ark Claw 的协作规则

Ark Claw 的角色不是替代判断，而是**研究员 + 信息管理员 + 地图维护员**。

每次研究任务尽量使用以下输出结构：

```markdown
## Research Node

### 1. Map Location
- CAPITAL MAP > ... > ...

### 2. Question
- 本次要回答的问题

### 3. Facts
- 可验证事实
- 每条附来源、日期、原始链接

### 4. Inferences
- 基于事实的推断
- 明确说明推断链

### 5. Counter-Evidence
- 相反证据 / 反例

### 6. Unknowns
- 当前无法确认的内容

### 7. Decision Relevance
- 这些信息会改变什么判断？

### 8. Next Actions
- 下一步最值得验证的 1~3 件事
```

证据等级：

- **A：官方 / 监管 / 公司原始披露 / 法定文件**
- **B：高质量数据库 / 主流机构研究 / 权威媒体**
- **C：从业者访谈 / X / Reddit / 知乎 / 社区经验**
- **D：未经验证的二手转载 / 营销话术**

规则：

1. A/B 可作为事实依据；C 主要生成假设；D 默认不进入结论。
2. 不要只给链接，必须先过滤、归类、去重。
3. 不隐藏可能改变结论的反证。
4. 不把“行业普遍如此”建立在单个案例上。
5. 信息必须标注日期，防止旧数据污染当前判断。
6. 最终把新知识挂回本文件对应节点，而不是不断生成孤立报告。

---

## 13. 下一批待建节点

- [ ] 中国 VC / PE / CVC / 产业基金 / FA 的边界与典型商业模式
- [ ] 中国 LP 结构与政府投资基金体系
- [ ] 一级项目真实 DD checklist
- [ ] Investment Memo 模板
- [ ] IC 决策流程与权限边界
- [ ] Cap Table / Dilution 实战
- [ ] VC / PE 常见估值方法
- [ ] 投后管理指标体系
- [ ] 中国一级市场退出机制
- [ ] Buy-side / Sell-side 岗位地图
- [ ] A股 / 港股 / 美股市场结构差异
- [ ] AI Agent 在投资机构的真实落地案例
- [ ] 投资机构信息安全、客户保密、权限与审计

---

## 14. 核心原则

> **不要为了“懂金融”而堆知识。要理解资本如何运转，再把真实项目不断挂到地图上。**

> **不要先找 Agent 能做什么。先画业务流程，再找高摩擦、高频、可验证的节点。**

> **事实、推断、建议、未知必须分开。**
