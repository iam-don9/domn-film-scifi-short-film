# domn-film-scifi-short-film

![domn-film-scifi-short-film 封面](assets/readme/hero.webp)

> 科幻短片剧本写作执行流程。

## 是什么

科幻短片剧本写作执行流程。本仓库是一个 Agent 技能（SKILL.md 为唯一权威定义），把上面的方法论沉淀为可被对话触发的可执行流程。

## 怎么做（工作流）

<p align="center">
  <img src="./assets/readme/workflow.svg" width="100%" alt="domn-film-scifi-short-film 工作流：logline → 点子卡 → 拍子表 → 剧本 → 成片。点子双向测试，先立设定再写拍子">
</p>

1. **logline**
2. **点子卡**
3. **拍子表**
4. **剧本**
5. **成片**

## 怎么用

将本仓库放入支持 `SKILL.md` 的 Agent 技能目录：

- **WorkBuddy**：`~/.workbuddy/skills/domn-film-scifi-short-film/`
- **Codex / 其他**：对应 skills 目录

然后在对话中触发，例如：

```
用 domn-film-scifi-short-film 帮我处理一段需求。
```

## 依赖

纯提示词方法论 + references/ 弹药库；无代码依赖.

## 仓库结构

```
domn-film-scifi-short-film/
├── SKILL.md                 # 技能定义（唯一权威）
├── references/              # 方法论弹药库
├── assets/                  # 模板 / 占位素材
└── assets/readme/           # 本 README 的视觉资产（hero.webp / workflow.svg）
```

## 许可

本仓库内容以 `SKILL.md` 为唯一权威定义。如附带 `LICENSE` 文件，以其为准。

---

*README 由 `beautify-github-readme` 生成 · 封面图来自作者作品集，强调色由封面图采样派生。*
