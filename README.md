# 临床R语言编程

> 🌐 **在线浏览**: [https://jingya221.github.io/MediSumGuide/](https://jingya221.github.io/MediSumGuide/)

临床研究中R语言编程的指南和最佳实践。

---

本指南为 **MediSum** 平台的使用说明，按平台支持的表格与输出类型组织。每类表格均有独立页面，说明界面选项、分组与筛选方式及结果展示。

完整目录见下方 **[指南目录](#指南目录)**，或使用左侧导航进入各章节。

---

## 指南目录

### 01-受试者基线信息

| 表格 | 说明 |
|------|------|
| [人口学和其他基本特征](docs/notes/01-受试者基线信息/02-人口学和其他基本特征.md) | 该表格主要呈现不同组别和呈现变量下的样本量。导入数据后，可以在左侧表格相关选项中选择使用的数据... |
| [受试者分布](docs/notes/01-受试者基线信息/01-受试者分布.md) | 受试者分布可以通过四种分类方式进行分析。 |
| [既往抗肿瘤治疗史](docs/notes/01-受试者基线信息/04-既往抗肿瘤治疗史.md) | 该表格主要呈现不同组别和呈现变量下的抗肿瘤治疗史及治疗分类的数据记录。导入数据后，可以在左侧表... |
| [肿瘤诊断](docs/notes/01-受试者基线信息/03-肿瘤诊断.md) | 该表格主要呈现不同组别和呈现变量下的描述性统计。导入数据后，可以在左侧表格相关选项中选择使用的... |


### 02-治疗后不良事件

| 表格 | 说明 |
|------|------|
| [MedDRA分类汇总](docs/notes/02-治疗后不良事件/02-04MedDRA分类汇总.md) | 该表将按照MedDRA系统器官类别(SOC)、首选术语(PT)分类汇总不同组别及合计组治疗后发... |
| [不良事件概况](docs/notes/02-治疗后不良事件/01-不良事件概况.md) | 该表格采用频数和百分比方式汇总不同组别及合计组治疗后发生的不良事件的概况。导入数据后，可以在左... |

---

## 使用说明

- 各页面介绍对应表格在 MediSum 中的配置方式（数据集、语言、分析集、分组变量、呈现变量等）。
- 界面支持中英文表格展示语言，分组支持计划组别、治疗组别及自定义分组等。
- 截图与选项名称以实际平台为准，便于按步骤操作。

---

*© 2026 Jingya Wang · [GitHub](https://github.com/jingya221/MediSumGuide)*


---

## 🚀 快速开始

### 在线浏览（推荐）
访问 [https://jingya221.github.io/MediSumGuide/](https://jingya221.github.io/MediSumGuide/)

### 本地运行
```bash
# 克隆仓库
git clone https://github.com/jingya221/MediSumGuide.git
cd MediSumGuide

# 安装依赖
pip install mkdocs mkdocs-material mkdocs-minify-plugin

# 本地预览
mkdocs serve
```

---

## 📁 项目结构

```
MediSumGuide/
├── docs/
│   ├── index.md
│   └── notes/
│       └── r-project-guide/
├── mkdocs.yml
├── update_readme.py
└── README.md
```

---

*📅 最后更新: 2026-03-06*

<p align="center">
  © 2026 Jingya Wang | <a href="https://github.com/jingya221/MediSumGuide">GitHub</a>
</p>
