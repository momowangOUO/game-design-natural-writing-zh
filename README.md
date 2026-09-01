# game-design-natural-writing-zh

一个用于中文游戏策划、关卡提案、规则页、方法论和评审稿的 Codex Skill。它不靠替换“AI 高频词”来伪装人类文风，而是优先修复三类更根本的问题：

- 让玩家、队伍、怪物和设施承担真实动作；
- 把设计结论放回可以追溯的因果过程；
- 在自然化改写时完整保留数字、规则、归属和例外。

## 安装

把仓库复制到 Codex 的 Skills 目录：

```text
~/.codex/skills/game-design-natural-writing-zh/
```

重新启动 Codex 后，可以直接要求：

```text
请用 game-design-natural-writing-zh 重写这份关卡策划，保留规则和数字，去掉 AI 味。
```

Skill 允许隐式调用。当用户提出“像人话一些”“不要有 AI 味”“主语不清楚”“写得太刻意”等要求时，也适合自动启用。

## 文件

- `SKILL.md`：执行规则；
- `references/examples.md`：正反例与常见误区；
- `tests/pressure-scenarios.md`：压力测试；
- `tests/baseline-observations.md`：实际失败基线；
- `tests/green-results.md`：按新版规则重新作答的结果。

## 适用边界

这个 Skill 处理中文游戏设计文案，不负责替用户补齐未经确认的规则，也不应为了“自然”改动概率、时间、资源来源或奖励归属。

## License

MIT
