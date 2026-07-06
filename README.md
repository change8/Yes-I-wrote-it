# Yes, I Wrote It

AI 写的文字太完美了——句式工整、逻辑严密、没有瑕疵。但真人写东西不是这样的。

这个 Skill 帮你消除中文写作中的「AI 味」，让输出读起来像你自己写的。

## 功能

- **12 类 AI 句式精准清理**：二元对比壳、伪洞察标记、冒号讲义腔、命令式开场、空泛总结、时态错位、空泛比较、抽象施压、比喻口号式结尾、万能框架等
- **诊断模式**：逐句分析"这句为什么像 AI 写的"，指出触发规则和修改建议
- **双模式**：完整去 AI 味 + 自然化输出 / 仅去 AI 味（不改原意）

## 快速开始

### 安装到项目

克隆到你的 Agent Skill 目录：

```bash
# Codex
cp -R yes-i-wrote-it /your-project/.agents/skills/yes-i-wrote-it

# Claude Code
cp -R yes-i-wrote-it /your-project/.claude/skills/yes-i-wrote-it

# Hermes Agent
cp -R yes-i-wrote-it ~/.hermes/skills/yes-i-wrote-it
```

### 用法

在 Agent 对话中直接使用：

```
去 AI 味：帮我改一下这段文字，去掉 AI 痕迹。

诊断模式：分析一下这段话为什么像 AI 写的。

仅去 AI 味：只去掉 AI 句式，不改原意的表达方式。
```

## 核心特色

- **保留事实不动**：数据、产品名、模型名、日期、术语一律不动
- **保留个人判断**：不为了让文本"顺滑"而抹掉作者的观点立场
- **四桶法工作流**：事实/判断/经验/行动分类提取，精准改写
- **完整终检清单**：20+ 条 regex 级别查杀规则，避免遗漏
- **诊断模式**：逐句分析"这句哪里像 AI"，给出精准修改建议

## 致谢

本 skill 基于 [rnskill](https://github.com/Pluviobyte/rnskill) 的人话体系增强。

## License

Apache 2.0
