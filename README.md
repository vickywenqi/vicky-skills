# Vicky Skills 🎯

我自己每天都用的 AI Skill，都开源在这里。

都是在自己项目里跑通了一段时间，确实好用，才搬出来开源的。边做，边分享，边迭代。

---

## 📋 目录索引

**📝 vicky-writer — 公众号爆文写作**（让 Agent 按 Vicky文奇的写作方法论输出公众号文章）

---

## ✍️ vicky-writer（公众号爆文写作）

> _"有15w粉丝的自媒体人，在认真分享成长认知和搞钱技能。"_

我自己写公众号的完整写作 SOP skill。装上之后，Agent 执行从选题、标题、框架、素材、开头、结尾、金句、成文、精修的全流程方法论，输出文章，我的文风、我的节奏、我的禁忌词全在里面。

### 适合

你看过我公众号「文奇不惑」的文章，觉得风格还行，想让你的 AI 也照着这个调子写公众号文章。比如给一个主题、一段视频文案、一个案例素材、一段播客采访，让它写成有观点、有态度、有逻辑的长文。

### 不适合

你想要的是"通用好文笔"。这个 skill 是有立场的——它会**拒绝**「不是…而是…」、**拒绝**「综上所述」、**拒绝**「在当今 AI 快速发展的时代」、**拒绝**排比句和对仗句、**拒绝**第一第二第三首先其次最后、**拒绝**一切假大空不说人话看起来像AI写的东西。如果你的目标读者就好这一口，那这个 skill 不适合你。

### 它会做什么

- 8步写作流程（拆解→判断类型→标题→框架→正文→易撰检测→朱雀检测→自检）
- 60+条禁止规则清单（避免AI味、书面语、说教式金句）
- 爆款标题8大技巧 + 多种标题结构参考
- 爆文框架8大类型，热点切入开头、事件链驱动案例、金句收束结尾等写法
- 易撰原创检测（原创度>75% + 敏感词规避）+ 朱雀AI检测规避规则（AIGC值<0.5）

→ [SKILL.md](./vicky-writer/SKILL.md)

---

## 📦 安装

### 一句话安装（推荐）

打开你的 AI Agent（WorkBuddy / Codex / Claude Code / OpenClaw），直接把这句话发给它：

```
帮我安装这个 skill：https://github.com/vickywenqi/vicky-skills/tree/main/vicky-writer
```

Agent 会自动下载安装，你不用做任何操作。

> 🇨🇳 **国内用户**：把上面链接里的 `github.com` 换成 `gitee.com` 即可加速：
> `https://gitee.com/vickywenqi/vicky-skills/tree/main/vicky-writer`

### 手动安装

如果一键安装不成功，也可以手动：

1. 下载 zip 包（GitHub 页面点 Code → Download ZIP，或找作者要）
2. 解压后把 `vicky-writer` 文件夹放到你 AI Agent 的 skills 目录：
   - **WorkBuddy**：`~/.workbuddy/skills/vicky-writer/`
   - **Codex**：`~/.codex/skills/vicky-writer/`
   - **Claude Code**：`~/.claude/skills/vicky-writer/`
   - **OpenClaw**：工作区 `skills/vicky-writer/`
3. 重启 Agent，输入 `/skills` 查看是否安装成功

---

## 👤 关于作者

Vicky文奇，15w粉丝自媒体人，在认真分享成长认知和搞钱技能。
公众号：文奇不惑

---

## 📄 开源协议

MIT License — 自由使用、修改、分发，注明原作者即可。
