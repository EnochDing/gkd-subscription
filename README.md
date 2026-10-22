# GKD 个人规则整合 + 自建教程

把 GitHub 上 `topic:gkd-subscription` 下别人分享的规则**抓取 → 清洗 → 合并去重**，
生成一份本地可用的整合订阅；再附上手把手教程，教你写自己的规则。

## 目录结构

```
├── dist/
│   ├── gkd.json5        ← 最终整合订阅（1054 应用 / 8371 规则，3.4MB）
│   └── report.md        ← 统计报告（来源清单、去重率、许可提醒）
├── my-rules/
│   └── gkd.json5        ← 你自己的订阅模板（从这里开始写规则）
├── docs/
│   └── tutorial.md      ← 手把手教程：抓快照 → 写选择器 → 真机验证
├── scripts/
│   ├── fetch.py         ← 拉取 31 个源的最新规则
│   ├── tojson.js        ← JSON5→JSON 预处理（快）
│   ├── merge.py         ← 合并去重流水线
│   ├── report.py        ← 生成统计报告
│   ├── serve.py         ← 一键服务整合版，手机远程订阅
│   └── serve_myrules.py ← 一键服务你自己的规则
├── build/               ← 各源原始规则缓存（抓取产物）
├── build_json/          ← 预处理后的 JSON 缓存
└── sources.json         ← 源清单
```

## 快速开始

**用整合版**（手机上订阅）：

```bash
python scripts/serve.py        # 手机 GKD → 订阅 → ➕ → 输入打印的网址
```

**更新整合版**（源更新后重跑）：

```bash
python scripts/fetch.py
python scripts/merge.py
```

**开始写自己的规则**：读 `docs/tutorial.md`，从 `my-rules/gkd.json5` 动手。

## 依赖

- Python 3（fetch / merge / serve 用）
- Node.js 22（tojson.js 用，仅首次转换 JSON5 需要；依赖 `json5` 已装在工作区）

## 说明

- 整合订阅 id = `173001`，个人模板 id = `173002`，均不与任何源冲突
- 合并产物**仅供个人本地使用，请勿公开发布**（个别源作者声明了"请勿传播"，
  详见 `dist/report.md` 第六节）
