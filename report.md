# GKD 个人整合订阅 · 统计报告

> 生成时间：2026-10-22  
> 订阅 id：173001（已核对不与任何源冲突）

## 一、总览

| 指标 | 合并前 | 合并后 | 收敛 |
|---|---|---|---|
| 应用条目 | 5099 | 1054 | 保留 20.7% |
| 规则组 | 12153 | 3493 | 保留 28.7% |
| 应用规则 | 17724 | 8371 | 去重 9353 条（52.8%） |
| 全局规则 | 83 | 77 | 去重 6 条 |
| 规则类别 | - | 23 | 归一化命名 |

## 二、收录的源

| 源 | star | 应用数 | 规则数 | 原始订阅 |
|---|---|---|---|---|
| [Lin-arm/GKD_subscription](https://github.com/Lin-arm/GKD_subscription) | 6176 | 985 | 3852 | [dist 原文件](https://raw.githubusercontent.com/Lin-arm/GKD_subscription/main/dist/gkd.json5) |
| [AIsouler/GKD_subscription](https://github.com/AIsouler/GKD_subscription) | 12041 | 886 | 3186 | [dist 原文件](https://raw.githubusercontent.com/AIsouler/GKD_subscription/main/dist/AIsouler_gkd.json5) |
| [mrlctate/gkd-mrlc](https://github.com/mrlctate/gkd-mrlc) | 146 | 690 | 2395 | [dist 原文件](https://raw.githubusercontent.com/mrlctate/gkd-mrlc/main/dist/beta-gkd.json5) |
| [mrlctate/gkd-mrlc](https://github.com/mrlctate/gkd-mrlc) | 146 | 693 | 2413 | [dist 原文件](https://raw.githubusercontent.com/mrlctate/gkd-mrlc/main/dist/gkd.json5) |
| [ganlinte/GKD-subscription](https://github.com/ganlinte/GKD-subscription) | 898 | 610 | 1381 | [dist 原文件](https://raw.githubusercontent.com/ganlinte/GKD-subscription/main/dist/ganlin_gkd.json5) |
| [MengNianxiaoyao/gkd-subscription](https://github.com/MengNianxiaoyao/gkd-subscription) | 476 | 285 | 1431 | [dist 原文件](https://raw.githubusercontent.com/MengNianxiaoyao/gkd-subscription/main/dist/gkd.json5) |
| [Lin-arm/gkd-Rules](https://github.com/Lin-arm/gkd-Rules) | 85 | 31 | 450 | [dist 原文件](https://raw.githubusercontent.com/Lin-arm/gkd-Rules/main/dist/gkd.json5) |
| [VolcanoSAhrimp/gkd-rule](https://github.com/VolcanoSAhrimp/gkd-rule) | 19 | 793 | 2298 | [dist 原文件](https://raw.githubusercontent.com/VolcanoSAhrimp/gkd-rule/main/dist/gkd.json5) |
| [yanmuq/muqi_gkd](https://github.com/yanmuq/muqi_gkd) | 19 | 33 | 160 | [dist 原文件](https://raw.githubusercontent.com/yanmuq/muqi_gkd/main/dist/gkd.json5) |
| [lisrain/GKD_subscription](https://github.com/lisrain/GKD_subscription) | 14 | 33 | 90 | [dist 原文件](https://raw.githubusercontent.com/lisrain/GKD_subscription/main/dist/gkd.json5) |
| [cjy0812/Ling033_GKD_Rules](https://github.com/cjy0812/Ling033_GKD_Rules) | 7 | 10 | 64 | [dist 原文件](https://raw.githubusercontent.com/cjy0812/Ling033_GKD_Rules/main/dist/gkd.json5) |
| [MINIPuffer/GKD_subscription](https://github.com/MINIPuffer/GKD_subscription) | 14 | 3 | 4 | [dist 原文件](https://raw.githubusercontent.com/MINIPuffer/GKD_subscription/main/dist/gkd.json5) |
| [37-7/GKD-FuckSearchHistory](https://github.com/37-7/GKD-FuckSearchHistory) | 0 | 28 | 52 | [dist 原文件](https://raw.githubusercontent.com/37-7/GKD-FuckSearchHistory/main/gkd.json5) |
| [kkyoung2025/kkyoung](https://github.com/kkyoung2025/kkyoung) | 0 | 6 | 5 | [dist 原文件](https://raw.githubusercontent.com/kkyoung2025/kkyoung/main/dist/gkd.json5) |
| [MarsGao/GkAndroidLabGKDCoupon](https://github.com/MarsGao/GkAndroidLabGKDCoupon) | 3 | 1 | 11 | [dist 原文件](https://raw.githubusercontent.com/MarsGao/GkAndroidLabGKDCoupon/main/dist/gkd.json5) |
| [LenorEric/GK-Lemon-D](https://github.com/LenorEric/GK-Lemon-D) | 16 | 12 | 24 | [dist 原文件](https://raw.githubusercontent.com/LenorEric/GK-Lemon-D/main/dist/GK-LEMON-D.json5) |

## 三、剔除项及原因

- **冗余副本**（规则指纹与更高 star 源重叠 ≥90%）：
  - `Breathe0503/GKD_subscription:dist/gkd.json5`
  - `Breathe0503/GKD_subscription:dist/AIsouler_gkd.json5`
- **空模板**（version=0 且无任何规则）：
  - `fifizy/gkd:dist/gkd.json5`
  - `0123z/gkd-subscription:dist/gkd.json5`
  - `xedmondy/gkd:dist/gkd.json5`
  - `sinchan3001/gkd:dist/gkd.json5`
  - `QING-XIAO/subscription-template:dist/gkd.json5`
  - `panglw/gkd:dist/gkd.json5`
  - `shixv/subscription-template:dist/gkd.json5`
  - `Linjoeel/8417:dist/gkd.json5`
  - `DevlMeIKraI/gkd-subscription:dist/gkd.json5`
  - `ACGZOOM/subscription-template:dist/gkd.json5`
  - `wongchao-IG/subscription:dist/gkd.json5`
  - `Liangism/gkd:dist/gkd.json5`
  - `kira-kasum/AAA:dist/gkd.json5`

## 四、去重规则

一条规则的指纹 = `sha1(生效 activityIds + matches + excludeMatches + excludeActivityIds + action + matchRoot)`。
同一包名下指纹相同即视为重复，只保留**高 star 源**（视为质量代理）首次出现的那条。

合并时同步做了这些保正确性处理：

- `group.key` / `rule.key` 全部重排（多源合并必然撞 key）
- `preKeys` / `scopeKeys` 引用重映射到新 key（已校验零断链）
- 组级 `activityIds` 与规则级等价归一：组内一致上提、不一致逐条下推，避免语义错位
- 类别只是 UI 开关、不约束规则（已实测全部源的字段确认）

## 五、使用方法

1. **手机与电脑同一 Wi-Fi**
2. 电脑上运行 `python scripts/serve.py`，会打印一个 `http://<电脑IP>:8666/gkd.json5` 地址
3. GKD App → 首页 → 订阅 → 右上角 ➕ → 粘贴该网址添加远程订阅
4. 或者：电脑浏览器打开上述地址全选复制，GKD → 本地订阅 → 粘贴导入（文件 3.4MB，粘贴可能卡顿，推荐远程方式）

想更新规则时，回到电脑运行：

```bash
python scripts/fetch.py   # 拉取各源最新版本
python scripts/merge.py   # 重新合并去重
```

GKD 端下拉刷新即可拿到最新版（version 会自增）。

## 六、传播边界（重要）

部分源作者声明了传播意愿：

- **lisrain/GKD_subscription**：订阅名明确标注「请勿传播」

因此**本合并产物仅供个人本地使用，请勿公开发布或二次分发**。
上游各源大多为 GPL-3.0 或作者自定义条款，公开分发前需逐源核对授权。

