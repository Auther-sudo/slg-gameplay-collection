# SLG 玩法搜集与转换工具集

> 面向 SLG（CoK-like / 4X）策划的**玩法资产管理与移植辅助工具集** —— 把零散的玩法灵感，结构化沉淀为可复用的「用研验证」素材。

![Type](https://img.shields.io/badge/Type-Interview%20Portfolio-9cf)
![Frontend](https://img.shields.io/badge/Frontend-HTML5%2FJS-orange?logo=html5)
![Data](https://img.shields.io/badge/Data-xlsx%20%E7%9F%A5%E8%AF%86%E5%BA%93-blue)
![Privacy](https://img.shields.io/badge/Privacy-Key%E4%BB%85%E5%AD%98%E6%9C%AC%E5%9C%B0-success)

---

## 📌 项目简介

做 SLG 策划时，玩法灵感往往散落在表格、文档、截图里，难以复用，也更难向用研 / 运营讲清楚「这个玩法值不值得做」。

本仓库把这一过程工具化：一方面用 **xlsx 知识库**把玩法按系统维度拆解、归类；另一方面提供**标准化的用研填表模板**，把「玩法 idea → 验证结论」的链路打通；再配合一个**纯浏览器端的玩法移植 Agent**，零部署即可完成「理解 → 移植方案 → 运营评估 → 文档生成」。

---

## ✨ 核心亮点

- **玩法拆解知识库**：按「社交 / 非社交（副玩法、模拟经营养成线）」系统分类的玩法拆解表，沉淀可复用素材。
- **用研格式标准化**：内置「玩法验证」「吸量点验证」两套填表模板，让策划输出的内容直接对齐用研口径。
- **浏览器端移植 Agent（零部署）**：单个 HTML 文件，打开即用；API Key 仅保存在你本地浏览器 `localStorage`，**不上传任何服务器**，隐私可控。

---

## 🧰 工具一览

| 模块 | 说明 |
| --- | --- |
| `slg玩法汇总/` | 按社交 / 非社交分类的玩法拆解表（xlsx），系统梳理主流 SLG 的玩法构成 |
| `用研格式示例/` | 玩法验证、吸量点验证的用研填表格式（xlsx），打通「想法 → 验证」 |
| `slg-gameplay-porting-agent.html` | 纯前端玩法移植 Agent，引导完成理解 / 移植 / 评估 / 文档全流程 |

---

## 🚀 快速开始

**玩法移植 Agent（无需安装）：**

直接用浏览器打开 `slg-gameplay-porting-agent.html`，填入你的 LLM / 搜索 API Key，按引导完成：

```
玩法理解 → 移植方案 → 运营评估 → 文档生成
```

**玩法知识库 / 用研模板：**

用 Excel / WPS / Numbers 打开对应 xlsx 即可查看与二次编辑。

---

## 📂 目录结构

```
slg-gameplay-collection/
├── README.md                         # 本文件
├── slg-gameplay-porting-agent.html   # 纯浏览器端玩法移植 Agent（零部署）
├── slg玩法汇总/                      # 玩法拆解知识库（xlsx）
│   ├── 社交类玩法拆解.xlsx
│   └── 非社交类（副玩法·模拟经营养成线）.xlsx
└── 用研格式示例/                     # 用研填表模板（xlsx）
    ├── 玩法验证用研表.xlsx
    └── 吸量点验证用研表.xlsx
```

---

## 🔒 隐私与安全

- 移植 Agent 的所有 API Key 仅存储于**你本地浏览器**，不会经过任何第三方服务器。
- 本仓库只保留**通用方法论与公开游戏的玩法分析**，不含任何在研项目的世界观记忆或设计稿。

---

## 👤 关于本仓库

本仓库是 **Auther-sudo** 的面试作品集之一，展示游戏策划工作中的「玩法资产管理 + AI 辅助移植」实践。

> 欢迎在 GitHub 主页查看更多作品：[@Auther-sudo](https://github.com/Auther-sudo)
