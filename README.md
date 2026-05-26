# 五术资料收集工具

本仓库提供工具用于采集、转换五术相关资料，并同步到对应的子仓库中。

## 项目结构

```
wushu
├── shan/     # 山术 - 道教修行修炼
├── yi/       # 医 - 中医治病救人
├── ming/     # 命 - 命运推算预测
├── xiang/    # 相 - 相术风水面相
├── bu/       # 卜 - 占卜预测决策
└── tools/    # 采集和转换工具
```

## 子模块

本项目包含五个子模块仓库：

| 子模块 | 用途 | 仓库 |
|--------|------|------|
| shan | 山术 | git@github.com:wushuxue/shan.git |
| yi | 医 | git@github.com:wushuxue/yi.git |
| ming | 命 | git@github.com:wushuxue/ming.git |
| xiang | 相 | git@github.com:wushuxue/xiang.git |
| bu | 卜 | git@github.com:wushuxue/bu.git |

## 快速开始

### 克隆项目（含子模块）

```bash
git clone git@github.com:wushuxue/wushu.git
cd wushu
git submodule update --init --recursive
```

### 更新所有子模块

```bash
git submodule update --remote
```

## 中国五术简介

中国五术是古代中华文明的核心学术体系：

- **山**：道教修行、修炼成仙之道
- **医**：中医治病救人之术
- **命**：命运推算预测之学
- **相**：相术风水面相之辨
- **卜**：占卜预测决策之法

所有资料均以 Markdown 格式存储，便于阅读和维护。

## 贡献

欢迎提交 Pull Request 或 Issue 来完善五术资料库。