# zcode-skills

我的 ZCode Agent 自用 Skills 合集，安装于用户级技能目录 `~/.zcode/skills/`，对所有项目生效。

## 包含的 Skills

| Skill | 说明 |
| --- | --- |
| **impeccable** (v4.3.1, Apache 2.0) | 前端界面设计与打磨全能技能：设计/重构/审计/优化网页、落地页、仪表盘、产品 UI；覆盖视觉层级、排版、配色、动效、可访问性、响应式、设计系统等。自带 `impeccable.exe` 可视化工具。 |
| **ui-styling** (v1.0.0, MIT) | 基于 shadcn/ui（Radix UI + Tailwind）与 Tailwind CSS 的界面样式技能：构建可访问组件（对话框、下拉、表单、表格）、主题定制、暗色模式、海报与视觉设计。 |
| **ui-ux-pro-max** | 本地可检索的 UI/UX 设计知识库：79 种风格（50 个可用）、192 套配色方案、74 组字体搭配、119 条 UX 准则、105 个图标、17 个 GSAP 动效预设、25 种图表类型、22 个技术栈指南。 |

## 如何使用

把对应目录复制到 ZCode 的用户级技能目录即可：

```
# Windows
xcopy /E /I impeccable "%USERPROFILE%\.zcode\skills\impeccable"

# macOS / Linux
cp -r impeccable ~/.zcode/skills/
```

安装后重启 ZCode 会话，技能会自动按需触发，也可以用 `/impeccable`、`/ui-styling` 等方式手动调用。
