# 外部 Skill 收藏

收藏的第三方/外部 Claude Code skill。与 [my-skills](https://github.com/circleone1980/my-skills)（自制 skill）对应——这里存放从外部安装或参考的 skill。

## 已收藏
- **design-md** — 创建和管理 `DESIGN.md` 文件（设计方向、tokens、视觉规则的单一真相源）。源自 Google Labs（Stitch）/ Open Design。
- **frontend-design** — 创建独特、生产级的前端界面，避免通用 AI 审美。Anthropic 官方出品。
- **awesome-design-md** — 70+ 知名品牌（Claude/Notion/Stripe/Linear…）的真实 `DESIGN.md` 风格库。取一份放进项目根，AI 照其生成视觉一致的 UI。VoltAgent 出品（94K⭐）。注：资源库，非 SKILL.md。

## 本地挂载（软链到 ~/.claude/skills/）

```bash
ln -s ~/projects/external-skills/<skill-name> ~/.claude/skills/<skill-name>
```

## 说明
- 外部 skill 遵循各自上游 LICENSE（见各 skill 目录内文件）
- 升级时从上游重新同步，再提交到此仓库
