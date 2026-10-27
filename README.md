# Hi, I'm jinlio 👋

**AI tooling & engineering** — 我做 AI 时代的「基础设施 + 应用」：给 agent 拍片的观测工具、给文本验伤的检测器、能跑完整调研的工作流，以及真实部署过的端侧模型。

🔗 博客：[blog.luckyguo.dpdns.org](https://blog.luckyguo.dpdns.org/)（记录每个项目的设计与踩坑）

## 精选项目

| 项目 | 一句话 | 亮点 |
|---|---|---|
| 🔬 [agent-xray](https://github.com/jinlio/agent-xray) | 零埋点、纯本地的 coding-agent 会话回放器：ZCode / Claude Code / Codex 日志 → 单文件交互式 HTML（时间轴、工具树、失败高亮、成本曲线） | 逆向三种日志格式并宽容降级；141 会话 / 9.8k 模型调用全量解析通过，9ms/会话；v0.4 已发布双语界面 |
| 🖋 [aigc-selfcheck（墨鉴）](https://github.com/jinlio/aigc-selfcheck-public) | 纯本地的中文论文 AIGC 痕迹自查：三路检测融合（微调分类器 + ONNX + 统计/PPL 特征）→ 逐句热力图、可解释证据、按单段敏感性排序的修改计划 | 全文不上传；三路分歧显式标记不硬判；改写建议带「不新增事实」防幻觉校验 |
| 🔍 [deep-research-skill](https://github.com/jinlio/deep-research-skill) | 可移植的多 agent 深度调研工作流：证据优先、多来源核验、冲突披露，交付可审计报告 | 纯工作流不绑定模型/搜索服务 |
| 🀄 [mjbrain](https://github.com/jinlio/mjbrain) | 基于 LAYA 微调的立直麻将实时决策推荐系统（recommend-only） | 真实强化学习数据管线 + 微调部署 |
| 🎋 [liuyao-skill](https://github.com/jinlio/liuyao-skill) | 六爻占卜与解卦 skill（铜钱法/蓍草法/手动起卦） | Agent 技能生态早期实践 |
| 🧰 [luckyguo-typecho-suite](https://github.com/jinlio/luckyguo-typecho-suite) | 可复用的 Typecho 主题 + 插件 + Meilisearch + SSRF 加固，双语部署指南 | 真实运行在生产博客上 |

## 技术栈

- **语言**：Python（主力）、SQL、PHP、JavaScript（无构建链的单文件前端）
- **AI/NLP**：transformers / ONNX Runtime / LoRA 微调（4060 8GB）／ Agent 工作流与 skill 设计
- **工程**：GitHub Actions CI（多版本矩阵 + golden 快照测试）、uv/pipx 分发、PyPI 发布、Hugo、SQLite（WAL 快照与能力探测）

## 我在意的工程观

零埋点优先于接入成本；本地优先于云端上传；诚实的不确定度优于伪精确的分数；单文件可分享优于注册账号才能看。

<!-- 联系方式：在此补一行 email 或微信/知乎链接 -->
