# Frontend PPTX

一个面向 Claude Code 的演示文稿 skill，用来快速生成 HTML 幻灯片，或者把 `PPT / PPTX` 内容整理成网页演示稿。

## 适合做什么

- 从主题、提纲或现成文案生成演示稿
- 把 PowerPoint 内容提取后重组为 HTML 幻灯片
- 输出单文件、易分享、易修改的网页 slides

## 项目特点

- 零前端工程依赖，重点是直接产出可打开的 HTML
- 内置多套视觉风格、动画参考和版式约束
- 强调一屏一页，避免内容溢出和滚动
- 附带 PPT 提取、部署、导出 PDF 脚本

## 目录说明

- `SKILL.md`：核心工作流与生成规则
- `STYLE_PRESETS.md`：风格预设
- `viewport-base.css`：视口适配基础样式
- `html-template.md`：HTML 结构参考
- `animation-patterns.md`：动画参考
- `scripts/`：提取、部署、导出脚本

## 安装

### 方式一：插件市场

```bash
/plugin marketplace add LinYi-7/frontend-pptx
/plugin install frontend-pptx@frontend-pptx
```

### 方式二：手动安装

```bash
git clone https://github.com/LinYi-7/frontend-pptx.git ~/.claude/skills/frontend-pptx
```

安装后可在 Claude Code 中通过 `/frontend-pptx` 使用。

## 依赖说明

- Claude Code
- Python（用于 PPTX 提取，需安装 `python-pptx`）
- Node.js（用于部署和 PDF 导出）

## License

MIT
