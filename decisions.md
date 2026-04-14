# Decisions

## Confirmed Defaults
- Canonical memory store is `D:\AI\agent-memory`.
- Nightly merge runs at 22:00 Europe/Warsaw.
- OpenClaw handles background consolidation while Codex consumes local mirrors.
- Weekly reports prepare on Friday 18:30 Europe/Warsaw and dispatch to Gmail plus Weixin at 18:40.
- Monthly reports prepare on day 1 at 09:30 Europe/Warsaw and dispatch to Gmail plus Weixin at 09:40, with daily 10:00 recovery.
- 我看到他们都是在一个sync的分支上，而默认的main都是只有一个readme，这样是好的吗？
- 检查一下openclaw的模型设置，默认要求gpt5.4 high模式，可以的话用最牛逼的
- Third-party skills intended for both Codex and OpenClaw must be installed or mirrored into both local skill directories.
- Obsidian 主库：`D:\Documents\笔记`
- 双主库：两个系统同时沉淀长期记忆、决策、经验，最后不知道谁是真的。
- 定时合并：light sync、nightly merge、skills synthesis
- 外部知识库默认只读，不得直接成为第二记忆源。
