# ai-intro-for-friends — 项目笔记

## 线上地址
https://ai-intro-for-friends.onrender.com

## 这个网站是什么
写给营销圈朋友的 AI 入门长文。受众是对 AI 好奇但没系统了解的营销人。
不是 Chatbot 教程，是帮人建立"AI 世界地图"认知框架 + 上手 OpenClaw。
发布于 2026-04-10，由朋友圈分享触发。

## 内容结构
- Part 1：AI 世界地图（五层：LLM → Chatbot → Workflow → Agent → 垂直工具）
- Part 2：学 AI 的三个笨办法
- Part 3：上手 OpenClaw（A~F，含真实 Skill 案例）

## 文件关系
- **唯一源文件** = 这里的 `index.html`，直接改、直接 push
- 推到 GitHub → Render 自动上线
- 旧的 master 副本 `AI营销变局研究库/15-内容创作/培训分享/ai-intro-for-friends.html` 已废弃，不再维护

## 更新步骤
```bash
cd "/Users/wendy/Desktop/CCs Home/ai-intro-for-friends"
git add index.html
git commit -m "update: <改了什么>"
git push
```

## 设计规范
- 白底 + 紫色主色 `#6940a5`（Notion 风格）
- 字体：系统字体栈（PingFang SC 优先）
- 内容最大宽度 680px，左侧 260px 固定导航
- mobile：导航折叠为顶部按钮
- 交互：顶部进度条 + sticky 目录 + 回到顶部按钮

## GitHub Repo
https://github.com/wwwendy617/ai-intro-for-friends
