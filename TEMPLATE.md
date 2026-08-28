# 贡献模板（Contribution Template）

> 用这个模板提交你的收录建议：复制对应场景的代码块，把 `<>` 占位符换成真实内容，
> 既可放在 Pull Request 描述里，也可作为 Issue 提交。提交前过一遍末尾的「自检清单」。

---

## 场景 A：给「已收录」的来源仓库追加一个技能

> 当目标来源仓库**已经在 README 里**时，只需在对应簇下追加一行。不新建簇、不动其他簇。

```markdown
- **<技能英文原名>** — <一句中文用途说明>
```

**示例（在 Anthropic 官方技能簇下加一行）：**

```markdown
- **pdf-query** — 对 PDF 做语义问答与关键段提取，输出可溯源引用。
```

---

## 场景 B：新增一个「来源仓库簇」（仓库已在某大分类下归位）

> 用于把**一个新仓库**收录进**已经存在的 9 大分类之一**（如科研学术 / 公众号创作 / 前端设计…）。
> 把它追加到对应大分类的末尾，保持分类内标题层级一致。

```markdown
### <仓库名> ★<stars 数值>

**来源仓库**：[<owner>/<repo>](<仓库完整 URL>)

<一句话介绍：这个仓库解决什么问题，为什么值得收录（高级别 / 文档清晰 / 实测可用）>

- **<skill-a>** — <中文用途说明>
- **<skill-b>** — <中文用途说明>
```

**示例：**

```markdown
### acme-note-skills ★1.2k

**来源仓库**：[acme/acme-note-skills](https://github.com/acme/acme-note-skills)

面向知识工作者的笔记自动化套件：语音转 Markdown、双链接整理与定期复盘，文档完整、可持续维护。

- **note-transcribe** — 把语音 / 会议录音转成带时间戳的 Markdown 笔记。
- **note-linker** — 扫描笔记库补全双链（wikilinks）并维护目录索引。
- **note-review** — 按周 / 月为笔记做间隔复盘，产出摘要与待办。
```

---

## 场景 C：新增一个「大分类」

> 用于收录**9 大分类之外的新赛道**（如金融 / 医疗 / 游戏 / 法律…）。需要同时做 3 件事：
> ① 新建 `##` 大分类块；② 在「目录」里加一行可跳转条目；③ 更新顶部徽章统计。

**C-1. 在正文新增分类（追加到 9 大分类之后、`相关说明` 之前）：**

```markdown
<在当前大分类结尾已有一行 `[⬆ 返回目录](#toc)`，在其上方插入：>

## <分类名> · <Category English>

> <一句话说明该分类覆盖的能力范围>

### <仓库名> ★<stars>

**来源仓库**：[<owner>/<repo>](<仓库完整 URL>)

<一句话介绍>

- **<skill-a>** — <中文用途说明>
- **<skill-b>** — <中文用途说明>

[⬆ 返回目录](#toc)
```

**C-2. 在「目录」追加（接在最后编号之后）：**

```markdown
<递增编号，如当前目录到 11 就写 12> **[<分类名>](#<英文锚点 id>)**：[<一句话关键词>]
```

> 锚点规则：每类 `##` 标题上方放一行 `<a id="<英文 id>"></a>`（如 `<a id="finance"></a>`），
> 目录里的 `#<英文 id>` 与之对应时可跳转。

**C-3. 更新顶部徽章（`README.md` 第 2 行附近）：**

```markdown
![skills](https://img.shields.io/badge/skills-<新总数>-blue) ![repos](https://img.shields.io/badge/repos-<新仓库数>-green) ![stars](https://img.shields.io/badge/stars-<新合计 f>-brightgreen)
```

---

## 自检清单（提交前逐项勾选）

- [ ] 有可用的 `SKILL.md`，能被 Claude Code / Codex / pi 等 Agent 环境加载
- [ ] 有清晰的中文（或可理解英文）文档与触发说明
- [ ] 有维护迹象：近期提交 / issue 有回应 / stars 较高 / 实测可用
- [ ] 中文描述 ≤ 60 字，动词开头（生成 / 审查 / 构建 / 检索…），保留英文术语
- [ ] 未与已有条目重复（重复则合并，不重复列条）
- [ ] 只写「它能做什么」，不写「它很强大」等营销话术
- [ ] 若新增仓库：补充了 `**来源仓库**` 链接 + 一句话介绍
- [ ] 若新增分类：已同步更新「目录」与顶部徽章统计
- [ ] 已在所属大分类结尾保留 `[⬆ 返回目录](#toc)`

---

## 已收录分类速查（避免放错分类）

| 编号 | 分类 | 典型内容 |
|---|---|---|
| 01 | 官方出品 · Official | Anthropic / Codex 官方技能 |
| 02 | 科研学术 · Research | Nature 系列 / academic / scientific |
| 03 | 公众号 · 中文内容创作 | wechat / wewrite / Humanizer-zh |
| 04 | 知识管理与检索 | Obsidian / claude-obsidian / anysearch / Agent-Reach |
| 05 | 前端 · 设计与视觉 | garden-skills / huashu / taste / slides |
| 06 | 安全逆向 · Security | reverse-skill |
| 07 | SEO 优化 | claude-seo |
| 08 | 个人 IP 打造 | ip-strategist |
| 09 | 工程流程与元技能 | Matt Pocock / qiushi |
