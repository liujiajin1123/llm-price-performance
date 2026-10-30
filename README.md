# LLM Price × Performance

> 大模型 API **性能 × 价格**对比决策工具 — 选对档位比选对厂商更重要，别花冤枉钱。

## 在线预览

打开 [index.html](index.html) 即可使用，无需构建、无需依赖。

（后续开启 GitHub Pages 后可直接访问在线地址）

## 这是什么

一个单文件 HTML 交互式对比页面，覆盖 **22 款主流模型、10 家厂商**，帮你在选择 LLM API 时快速回答三个问题：

1. **我的预算能买到什么性能？** — 性价比散点图一眼定位
2. **这个价位哪个模型最值？** — 可排序表格按档位/厂商筛选
3. **我的场景该选哪个？** — 6 种开发场景直接给推荐

## 核心结论

| 发现 | 说明 |
|------|------|
| 选对 tier > 选对厂商 | 同厂旗舰与经济档差 1000 倍，同档跨厂价差通常 ≤20% |
| 性价比之王 | **GPT-6.1 Sol**（$2/$10，拿到 97% 旗舰性能） |
| 最大省钱杠杆 | Prompt Caching — Agent 场景能砍 60-80% 输入成本 |
| 国产首选 | **DeepSeek V4.1 Flash**（低谷半价 + 开源 MIT） |

## 收录模型

- **海外**：OpenAI (GPT-6 系列)、Anthropic (Claude Opus/Sonnet/Haiku 5.5)、Google (Gemini 3.1 Pro/3.8 Flash)、xAI (Grok 4.7)
- **国产**：DeepSeek V4 系列、阿里 Qwen3.8 系列、月之暗面 Kimi K3、智谱 GLM-5.3、字节豆包、MiniMax

价格统一折算为 **USD / 百万 tokens**，国产模型按 1 USD ≈ 7.2 CNY 换算。

## 数据来源

- 各厂商官方定价页（2026-10-08/13 核验）
- [BenchLM BenchAlign](https://benchlm.ai/)（2026-10-27）
- [LMArena](https://arena.ai/)（2026-10-22）
- [TrakToken 国内市场](https://www.traktoken.com/)（2026-10-29）

## 省钱贴士

- 离线批量任务走 Batch API，普遍 5 折
- DeepSeek 峰谷分时：低谷（非高峰时段）价格减半
- 推理模型别用 max effort，medium 对大多数任务够用
- 注意促销价到期时间（Gemini Flash 系列 12/31 后翻倍）

## 免责声明

价格变动频繁，本仓库为 2026 年 10 月快照。生产决策前请以各厂商官方定价页为准。性能综合分来自第三方评测，不同 benchmark 侧重点不同，建议结合自身场景测试。

## License

MIT
