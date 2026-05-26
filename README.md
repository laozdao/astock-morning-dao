# Astock Morning DAO

<p align="center">
  <img src="assets/logo.png" alt="Astock Morning DAO Logo" width="200">
</p>

<p align="center">
  <strong>A股全维度早盘综合分析报告技能</strong><br>
  基于宏观、政策、外围、资金、情绪、技术六维度的量化投资决策框架
</p>

<p align="center">
  <a href="https://github.com/laozdao/astock-morning-dao/releases/latest">
    <img src="https://img.shields.io/github/v/release/laozdao/astock-morning-dao?style=flat-square&color=blue" alt="Latest Release">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/github/license/laozdao/astock-morning-dao?style=flat-square&color=green" alt="License">
  </a>
  <a href="https://github.com/laozdao/astock-morning-dao/stargazers">
    <img src="https://img.shields.io/github/stars/laozdao/astock-morning-dao?style=flat-square&color=yellow" alt="Stars">
  </a>
</p>

---

## 📖 项目简介

**Astock Morning DAO** 是一个专为 A 股市场设计的早盘综合分析技能，基于顶尖投资机构的投研框架，构建了**"1+6"早报分析体系**：

- **1个总览技能**：汇总六大维度，交叉验证，输出当日操作指导
- **6个维度技能**：宏观、政策、外围市场、资金流向、市场情绪、技术面

### 核心特性

| 特性 | 说明 |
|------|------|
| 🎯 **六维度覆盖** | 宏观、政策、外围、资金、情绪、技术全方位分析 |
| ⚖️ **加权评分** | 基于维度重要性的综合评分体系（0-100分） |
| 🔍 **交叉验证** | 多维度信号共振与矛盾识别 |
| 📊 **量化输出** | 仓位建议、板块配置、操作计划、止损位 |
| 🎨 **精美报告** | 深色金融风格 HTML 报告模板 |
| 🔧 **易于扩展** | 模块化设计，支持自定义维度 |

---

## 🚀 快速开始

### 安装方法

#### 方法一：直接下载（推荐）

1. 访问 [Releases 页面](https://github.com/laozdao/astock-morning-dao/releases/latest)
2. 下载 `astock-morning-dao.skill` 文件
3. 将技能文件导入到你的 AI 助手系统中

#### 方法二：源码安装

```bash
# 克隆仓库
git clone https://github.com/laozdao/astock-morning-dao.git

# 进入目录
cd astock-morning-dao

# 打包技能（如需修改）
python scripts/package_skill.py .
```

### 使用方法

安装技能后，可以通过以下方式调用：

```
生成今天的全维度早盘报告
制作 2025-05-26 的综合分析报告
查看今日 A 股操作指导
```

---

## 📊 六维度分析框架

### 维度权重设计

| 维度 | 权重 | 优先级 | 核心功能 |
|------|:----:|:------:|----------|
| 宏观 | 25% | ⭐⭐⭐⭐⭐ | 周期定位、大方向判断 |
| 政策 | 25% | ⭐⭐⭐⭐⭐ | 板块映射、受益/受损识别 |
| 资金 | 20% | ⭐⭐⭐⭐⭐ | 热点确认、趋势验证 |
| 情绪 | 12% | ⭐⭐⭐⭐ | 极端值预警、逆向信号 |
| 外围 | 10% | ⭐⭐⭐ | 开盘指引、情绪传导 |
| 技术 | 8% | ⭐⭐⭐ | 入场时机、关键点位 |

### 综合评分体系

| 综合评分 | 市场判断 | 仓位建议 | 风险偏好 |
|----------|----------|:--------:|----------|
| 80-100 | 强烈看多 | 80-100% | 积极进攻 |
| 60-79 | 偏多 | 60-80% | 稳健偏多 |
| 40-59 | 中性 | 40-60% | 均衡配置 |
| 20-39 | 偏空 | 20-40% | 防御为主 |
| 0-19 | 强烈看空 | 0-20% | 空仓避险 |

---

## 📚 研究文档

本项目基于以下研究文档构建，详细阐述了六维度分析框架的理论基础和实践方法：

### 模型理论系列 (M Series)

| 文档 | 主题 | 说明 |
|------|------|------|
| [M01-03: 早盘分析框架](docs/M01-03-morning-analysis-framework.md) | 六维度融合决策模型 | 完整的框架设计和回测验证 |

### 方法论系列 (R Series)

| 文档 | 主题 | 说明 |
|------|------|------|
| [R04-01: 六维度研究方法论](docs/R04-01-six-dimension-methodology.md) | 从信息收集到投资决策 | 系统化的研究流程 |
| [R04-02: 资金流向量化](docs/R04-02-capital-flow-quantification.md) | 北向资金到主力动向 | 多维度资金监测体系 |
| [R04-03: 情绪指标构建](docs/R04-03-sentiment-indicator-construction.md) | 行为金融到量化交易 | 综合情绪指数 DEI |
| [R04-04: 技术面量化](docs/R04-04-technical-quantification.md) | 经典理论到现代量化 | 趋势、动量、形态识别 |

### 行业研究系列 (I Series)

| 文档 | 主题 | 说明 |
|------|------|------|
| [I09-01: 政策驱动分析](docs/I09-01-policy-driven-analysis.md) | TMT行业政策量化框架 | 以 AI 产业为例 |

> 📖 **完整研究文档库**：[Dao Quant Research](https://github.com/laozdao/dao-quant-research)

---

## 🏗️ 项目结构

```
astock-morning-dao/
├── SKILL.md                      # 技能定义文件
├── assets/
│   └── report-template.html      # HTML报告模板
├── docs/                         # 研究文档
│   ├── M01-03-morning-analysis-framework.md
│   ├── R04-01-six-dimension-methodology.md
│   ├── R04-02-capital-flow-quantification.md
│   ├── R04-03-sentiment-indicator-construction.md
│   ├── R04-04-technical-quantification.md
│   └── I09-01-policy-driven-analysis.md
├── .github/
│   └── workflows/
│       └── release.yml           # 自动发布工作流
├── LICENSE                       # 开源协议
├── CONTRIBUTING.md               # 贡献指南
└── README.md                     # 本文件
```

---

## 🎯 使用示例

### 示例 1：生成完整早盘报告

```
用户：生成今天的全维度早盘报告

系统：
┌─────────────────────────────────────────┐
│  A股全维度早盘综合报告 - 2025年5月26日   │
├─────────────────────────────────────────┤
│  综合评分: 78分（偏多）                  │
│  仓位建议: 60-80%                       │
│  风险等级: 中等                         │
├─────────────────────────────────────────┤
│  六维度信号:                            │
│  • 宏观: ↑多头 ⭐⭐⭐⭐ 复苏拐点确立      │
│  • 政策: ↑利好 ⭐⭐⭐⭐⭐ AI政策发布       │
│  • 外围: ↑利好 ⭐⭐⭐ 美股小幅上涨        │
│  • 资金: ↑流入 ⭐⭐⭐⭐ 北向+80亿         │
│  • 情绪: →乐观 ⭐⭐⭐ 赚钱效应良好        │
│  • 技术: ↑多头 ⭐⭐⭐⭐ 多头排列          │
├─────────────────────────────────────────┤
│  板块配置:                              │
│  • 重点配置: AI算力 40%                 │
│  • 积极配置: 医药 25%                   │
│  • 观察配置: 新能源 15%                 │
└─────────────────────────────────────────┘
```

### 示例 2：操作指导输出

```
当日操作指导:
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
📈 市场方向: 偏多，震荡上行
📊 综合评分: 78/100
💰 仓位建议: 60-80%（偏多配置）
⚠️  风险等级: 中等

板块配置策略:
┌──────────┬──────────┬────────────────┬────────┐
│ 配置方向  │ 板块      │ 逻辑            │ 仓位   │
├──────────┼──────────┼────────────────┼────────┤
│ 重点配置  │ AI算力    │ 政策+资金+技术共振 │ 40%   │
│ 积极配置  │ 医药      │ 北向加仓+超跌   │ 25%   │
│ 观察配置  │ 新能源    │ 超跌反弹        │ 15%   │
│ 规避板块  │ 银行地产  │ 资金流出        │ 0%    │
└──────────┴──────────┴────────────────┴────────┘

关键点位:
• 压力位: 3180
• 支撑位: 3120
• 止损位: 跌破3100减仓50%
```

---

## 🔬 理论基础

本项目基于以下核心理论构建：

### 1. 多因子模型理论

参考 Fama-French 多因子模型，将市场收益分解为多个维度：

$$R_i = \alpha + \sum_{j=1}^{6} \beta_j F_j + \epsilon$$

其中 $F_j$ 代表六个维度的因子暴露。

### 2. 行为金融学

基于 Kahneman 和 Tversky 的前景理论，识别投资者情绪偏差：
- 过度自信导致的过度交易
- 损失厌恶导致的止损犹豫
- 羊群效应导致的趋势强化

### 3. 市场微观结构

分析订单流、资金流向对价格形成的影响：
- 北向资金的"聪明钱"效应
- 主力资金的板块轮动引导
- 散户情绪的逆向指标价值

---

## 🤝 贡献指南

我们欢迎社区贡献！请参考 [CONTRIBUTING.md](CONTRIBUTING.md) 了解如何：

- 提交 Bug 报告
- 提出新功能建议
- 提交代码改进
- 完善文档

### 贡献者

<a href="https://github.com/laozdao/astock-morning-dao/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=laozdao/astock-morning-dao" alt="Contributors" />
</a>

---

## 📄 开源协议

本项目采用 [MIT License](LICENSE) 开源协议，允许：

- ✅ 商业使用
- ✅ 修改
- ✅ 分发
- ✅ 私人使用

唯一要求：保留版权声明。

---

## 🙏 致谢

- [Dao Quant Research](https://github.com/laozdao/dao-quant-research) - 研究文档支持
- [Trae Solo](https://www.trae.ai/) - AI 开发平台支持

---

## 📞 联系我们

- **GitHub Issues**: [提交问题](https://github.com/laozdao/astock-morning-dao/issues)
- **Email**: laozdao@126.com
- **微信公众号**: [老子道量化研究](https://laozdao.github.io/)

---

<p align="center">
  <strong>⚠️ 免责声明</strong><br>
  本项目仅供学习研究交流，不构成任何投资建议。股市有风险，投资需谨慎。
</p>

<p align="center">
  <sub>© 2026 [laozdao (老子道)](https://laozdao.github.io/) · Dao Quant Research</sub>
</p>
