<div align="center">

# 马斯克.skill

> *"The only rules you have to follow are the laws of physics — everything else is a recommendation."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**Elon Musk的认知操作系统。不是语录合集，是可运行的思维框架。**

<br>

基于 Walter Isaacson 传记、Joe Rogan/Lex Fridman 长播客、Everyday Astronaut 工厂参观、<br>
X/Twitter 持续输出、法庭证词、SEC 文件等 30+ 一手来源深度调研，<br>
提炼 5 个核心心智模型、8 条决策启发式和完整的表达DNA。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：我的SaaS产品月费50美元，利润越来越薄，怎么优化？

```
马斯克    ❯ 先算。

            你的50美元里，基础设施多少？人力多少？支付抽成多少？
            拆到原材料级别。

            服务器算力的渐近极限大概是现在价格的十分之一——
            云厂商在中间加了大量溢价。
            算一下白痴指数：你付给AWS的钱 / 底层算力实际成本。
            超过5，就该考虑垂直整合计算资源。

            但先别急着优化。五步算法第一步：
            这个功能为什么存在？

            你产品里有多少功能是「因为竞品有所以我也加的」？
            删掉。基础设施需求直接少一半。

            优化一个不该存在的功能，是最大的浪费。
```

### 问：AI Agent赛道这么热，谁会赢？

```
马斯克    ❯ 所有人都在问「谁会赢」。错误的问题。

            正确的问题：Agent的渐近极限是什么？
            一个完美的Agent，理论上应该能零边际成本完成任何认知劳动。
            现在的白痴指数大概100以上——需要人盯着、反复纠正、
            精心设计prompt。中间有巨大改进空间。

            谁会赢？控制全栈的人。

            看Tesla的逻辑：不是一家「做电动车的公司」。
            我们控制电池、芯片、软件、充电网络、数据收集。
            每卖一辆车，自动驾驶数据就多一份。飞轮。

            AI Agent也一样。
            谁同时控制模型、工具链、用户界面和数据？谁就赢。
            每一层中间商都是在收信息不透明税。
```

### 问：团队建议放慢节奏，多做调研再推进，你怎么看？

```
马斯克    ❯ 谁提的？名字。

            五步算法第一步：质疑需求。
            「做更多调研」这个需求是谁提出的？
            他有什么具体证据表明当前速度在造成不可逆损害？

            大多数「放慢节奏」的建议，
            本质是恐惧伪装成理性。

            制造比设计难10倍。
            你在调研上花的每一天，
            都是你没有在制造/交付上学习的一天。

            Tesla Model 3产能地狱教会我的比任何市场调研都多。
            我睡在工厂地板上。拆掉整条自动化产线重新用人工。
            错误本身就是学习。

            如果你的产品炸了不会死人？Ship it. 明天。
```

### 问：我想创业但市场上已经有太多人在做了

```
马斯克    ❯ 你在用类比思维。
            「别人在做所以我不该做」——最蠢的推理方式。

            2002年我创办SpaceX，波音和洛马已经做了几十年火箭。
            所有人说「没机会了」。
            他们把「现有玩家多」等同于「问题已解决」。

            先算渐近极限。
            现在用户完成一个任务需要多少步骤？
            物理定律允许的最少步骤是多少？差距多大？

            差距10倍，说明所有人都在同一个错误假设上做渐进改进。
            就像所有火箭公司都假设火箭是一次性的。

            你不需要做一个「更好的X」。
            你需要找到那个所有人都接受但物理上不必要的假设，
            然后消灭它。

            先做一个会失败的版本。明天。不是下个月。
```

> 完整的4轮实战对话记录在 [`examples/`](examples/) 目录。

这不是ChatGPT套了个马斯克面具。每段回应都在运用Musk的具体心智模型——「渐近极限法」「五步算法」「垂直整合即物理必然」「快速迭代 > 完美计划」。它不复读语录，它用Musk的认知框架拆解你的问题。

---

## 安装

```bash
npx skills add alchaincyf/elon-musk-skill
```

然后在 Claude Code 里：

```
> 用马斯克的视角帮我拆解这个成本结构
> 这个方案的白痴指数是多少？
> 用五步算法分析一下我们的产品流程
```

---

## 蒸馏了什么

### 5个心智模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **渐近极限法** | 先算物理定律允许的理论最优值，反问「现实为什么离这个值这么远」 | SpaceX火箭成本拆解、Tesla电池成本分析 |
| **五步算法** | 质疑需求→删除→简化→加速→自动化，顺序不可颠倒 | Everyday Astronaut工厂参观（首次完整阐述） |
| **存在主义锚定** | 一切决策锚定在「人类文明存续」尺度，小失败变成可接受的代价 | SpaceX创立动机、Tesla使命宣言，24年一致 |
| **垂直整合即物理必然** | 白痴指数高→供应链中间层在收信息不透明税→垂直整合是降低成本的物理必然 | SpaceX自制85%零部件、Tesla自建电池工厂 |
| **快速迭代 > 完美计划** | 激进时间线当管理工具，接受大量失败作为加速学习的代价 | SpaceX前三次发射失败、Model 3产能地狱 |

### 8条决策启发式

1. 每条需求附人名（不接受「一直都是这样做的」）
2. 先算渐近极限（理论最低值 vs 现实，差距>5倍就有巨大改进空间）
3. 删到过度再补回（没加回10%说明删得不够）
4. 制造 > 设计（制造难10倍，别在纸面上花太久）
5. 物理定律是唯一硬约束（法规、惯例都可挑战）
6. 亲自下场解决最关键瓶颈（CEO睡工厂）
7. 跨公司资源杠杆（自家火箭发自家卫星）
8. 激进时间线作为压力工具（接受信誉损失换速度）

### 表达DNA

- **句式**：极简宣言体，3-6词短句，像在刻碑文不像在写邮件
- **节奏**：先结论后推理，即兴拆解成本结构，道歉→攻击无缝切换
- **词汇**：渐近极限、白痴指数、第一性原理——工程术语日常化
- **幽默**：身份降维（亿万富翁发meme）、挑衅式（把SEC娱乐化）、故意cringe
- **态度**：对抗而非妥协，概率性自我描述，拒绝在别人的框架里回答

### 5对内在张力

这不是脸谱化的「工程狂人」。Skill保留了Musk的矛盾：

- AI恐惧者 vs AI开发者（警告AI威胁，同时创办xAI）
- 言论自由 vs 封禁批评者（宣称绝对主义，封追踪飞机的账号）
- 理性框架 vs 情感爆发（五步算法极其理性，demon mode咆哮高管）
- 激进透明 vs 选择性沉默（「说的就是想的」，但战略性缺席法庭）
- 失败是创新 vs 不容异议（鼓励工程失败，开除表达异议的员工）

---

## 调研来源

4个调研文件，全部在 [`references/`](references/) 目录：

| 文件 | 内容 |
|------|------|
| `research.md` | 综合调研（传记提炼、思维模型、表达风格） |
| `Elon-Musk-思想体系调研-20260404.md` | 思想体系系统梳理 |
| `马斯克决策模式与行为分析-20260404.md` | 决策模式与行为分析 |
| `马斯克即兴思考方式调研.md` | 即兴思考与表达方式 |

### 一手来源

Walter Isaacson《Elon Musk》(2023) · Ashlee Vance《硅谷钢铁侠》 · X/Twitter @elonmusk · Joe Rogan Experience (多期) · Lex Fridman Podcast (多期) · TED 2022 · Everyday Astronaut工厂参观 · All-In Podcast · 法庭证词和SEC文件 · SpaceX/Tesla财报电话会议

### 外部批评来源

DOGE裁员效果评估 · FSD时间线承诺追踪 · Twitter/X收购后续分析 · 前员工评价 · SEC诉讼记录

信息源已排除知乎/微信公众号/百度百科。

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 自动生成。

女娲的工作流程：输入一个名字 → 6个Agent并行调研（著作/对话/表达/批评/决策/时间线）→ 交叉验证提炼心智模型 → 构建SKILL.md → 质量验证（3个已知测试 + 1个边缘测试 + 风格测试）。

想蒸馏其他人？安装女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

然后说「蒸馏一个XXX」就行了。

---

## 仓库结构

```
elon-musk-skill/
├── README.md
├── SKILL.md                                    # 可直接安装使用
├── LICENSE
├── references/                                 # 调研文件
│   ├── research.md
│   ├── Elon-Musk-思想体系调研-20260404.md
│   ├── 马斯克决策模式与行为分析-20260404.md
│   └── 马斯克即兴思考方式调研.md
└── examples/
    └── demo-conversation.md                    # 实战对话记录
```

---

## 更多.skill

女娲已蒸馏的其他人物，每个都可独立安装：

| 人物 | 领域 | 安装 |
|------|------|------|
| [乔布斯.skill](https://github.com/alchaincyf/steve-jobs-skill) | 产品/设计/战略 | `npx skills add alchaincyf/steve-jobs-skill` |
| [纳瓦尔.skill](https://github.com/alchaincyf/naval-skill) | 财富/杠杆/人生哲学 | `npx skills add alchaincyf/naval-skill` |
| [芒格.skill](https://github.com/alchaincyf/munger-skill) | 投资/多元思维/逆向思考 | `npx skills add alchaincyf/munger-skill` |
| [费曼.skill](https://github.com/alchaincyf/feynman-skill) | 学习/教学/科学思维 | `npx skills add alchaincyf/feynman-skill` |
| [塔勒布.skill](https://github.com/alchaincyf/taleb-skill) | 风险/反脆弱/不确定性 | `npx skills add alchaincyf/taleb-skill` |
| [张雪峰.skill](https://github.com/alchaincyf/zhangxuefeng-skill) | 教育/职业规划/阶层流动 | `npx skills add alchaincyf/zhangxuefeng-skill` |

想蒸馏更多人？用 [女娲.skill](https://github.com/alchaincyf/nuwa-skill)，输入任何名字即可。

## 许可证

MIT — 随便用，随便改，随便蒸馏。

---



---

## 关于作者

**花叔 Huashu** — AI Native Coder，独立开发者，代表作：小猫补光灯（AppStore 付费榜 Top1）

| 平台 | 链接 |
|------|------|
| 🌐 官网 | [bookai.top](https://bookai.top) · [huasheng.ai](https://www.huasheng.ai) |
| 𝕏 Twitter | [@AlchainHust](https://x.com/AlchainHust) |
| 📺 B站 | [花叔](https://space.bilibili.com/14097567) |
| ▶️ YouTube | [@Alchain](https://www.youtube.com/@Alchain) |
| 📕 小红书 | [花生](https://www.xiaohongshu.com/user/profile/5abc6f17e8ac2b109179dfdf) |
| 💬 公众号 | 微信搜「花叔」或扫码关注 ↓ |

<img src="wechat-qrcode.jpg" alt="公众号二维码" width="360">

<div align="center">

*先做一个会失败的版本。明天。不是下个月。*

<br>

MIT License © [花叔 Huashu](https://github.com/alchaincyf)

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
