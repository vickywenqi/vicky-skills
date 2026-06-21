# Vicky Skills 🎯

AI Skills I use every day, open sourced here.

All of them have been tested in my own projects for a while before being shared. Making, sharing, and iterating.

---

## 📋 Index

**📝 vicky-writer — WeChat Official Account Viral Article Writing**（Let Agent output articles following Vicky文奇's writing methodology）

---

## ✍️ vicky-writer（WeChat Official Account Viral Article Writing）

> _"A self-media creator with 150k followers, seriously sharing growth insights and money-making skills."_

My complete writing SOP skill for WeChat Official Account articles. Once installed, the Agent executes the full methodology—from topic selection, titles, frameworks, materials, openings, endings, golden quotes, drafting, to final polishing—outputting articles with my writing style, my rhythm, and my forbidden words all built in.

### Best for

You've read my articles on the WeChat Official Account「文奇不惑」and like the style, and want your AI to write in the same tone. For example, give it a topic, a video transcript, a case material, or a podcast interview, and let it write a long-form article with opinions, attitude, and logic.

### Not for

You want "general good writing." This skill has a stance—it will **reject**「不是…而是…」、**reject**「综上所述」、**reject**「在当今 AI 快速发展的时代」、**reject** parallelism and antithesis、**reject** first-second-third firstly-secondly-lastly、**reject** anything that sounds hollow, impersonal, or AI-generated. If your target audience prefers that style, this skill is not for you.

### What it does

- 8-step writing workflow（Analysis→Type judgment→Title→Framework→Body→Yizhuan detection→Zhuque detection→Self-check）
- 60+ forbidden rules（Avoid AI tone, formal language, preachy golden quotes）
- 8 viral title techniques + multiple title structure references
- 8 viral article framework types, trending-topic openings, event-chain-driven cases, golden-quote endings
- Yizhuan detection（Originality>75% + sensitive word avoidance）
- Zhuque AI detection avoidance rules（AIGC score<0.5）

→ [SKILL.md](./vicky-writer/SKILL.md)

---

## 📦 Installation

### Universal method（Works with any Agent that supports Skills）

In Claude Code, Codex, WorkBuddy, or OpenClaw, simply say:

```
Install this skill: https://github.com/vickyyanruoxi/vicky-skills/tree/main/vicky-writer
```

The Agent will clone it to the appropriate directory automatically.

### Platform-specific methods

| Platform | Command |
|----------|---------|
| **Claude Code** | `/plugin marketplace add vickyyanruoxi/vicky-skills` → `/plugin install vicky-writer` |
| **Codex** | `$skill-installer install https://github.com/vickyyanruoxi/vicky-skills/tree/main/vicky-writer` |
| **WorkBuddy** | Type in chat: `帮我安装 https://github.com/vickyyanruoxi/vicky-skills/tree/main/vicky-writer` |
| **OpenClaw** | `openclaw skill install vicky-writer` or give the Agent the GitHub link above |

### Manual installation

```bash
git clone https://github.com/vickyyanruoxi/vicky-skills.git
cp -r vicky-skills/vicky-writer ~/.claude/skills/vicky-writer      # Claude Code
cp -r vicky-skills/vicky-writer ~/.workbuddy/skills/vicky-writer    # WorkBuddy
```

---

## 👤 About the Author

Vicky文奇, a self-media creator with 150k followers, seriously sharing growth insights and money-making skills.
WeChat Official Account: 文奇不惑

---

## 📄 License

MIT License — Free to use, modify, and distribute. Just credit the original author.
