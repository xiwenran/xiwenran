<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:4A90E2,50:5E72E4,100:825EE4&height=200&section=header&text=xiwenran&fontSize=60&fontColor=fff&fontAlignY=38&desc=%E5%86%85%E5%AE%B9%E5%88%9B%E4%B8%9A%20%C2%B7%20AI%20%E5%B7%A5%E5%85%B7%E5%BC%80%E5%8F%91%20%C2%B7%20Claude%20Code%20%E9%87%8D%E5%BA%A6%E7%94%A8%E6%88%B7&descSize=16&descAlignY=60&descAlign=50)

[![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=5E72E4&center=true&vCenter=true&width=700&lines=%E5%86%85%E5%AE%B9%E5%9E%8B%E4%B8%9A%E5%8A%A1%E5%88%9B%E4%B8%9A%E8%80%85;%E6%95%99%E5%B8%88%E8%99%9A%E6%8B%9F%E8%B5%84%E6%96%99+%C2%B7+%E5%B0%8F%E7%BA%A2%E4%B9%A6%2B%E6%8A%96%E9%9F%B3%2B%E7%A7%81%E5%9F%9F;%E7%94%A8+Claude+Code+%E6%8A%8A%E5%85%A8%E9%93%BE%E8%B7%AF%E8%87%AA%E5%8A%A8%E5%8C%96;%E4%BB%8E%E5%8D%96%E8%B5%84%E6%96%99+%E2%86%92+%E5%8D%96%E6%95%88%E7%8E%87+%E2%86%92+%E5%8D%96%E6%96%B9%E6%B3%95+%E2%86%92+%E5%8D%96%E4%BF%A1%E4%BB%BB)](https://git.io/typing-svg)

![Views](https://komarev.com/ghpvc/?username=xiwenran&style=flat-square&color=5E72E4&label=Profile+Views)

</div>

---

## 👋 关于我

内容型业务创业者,主做**教师虚拟资料**,平台(小红书 + 抖音)+ 私域承接,已跑一年多,正从"验证可行"往"稳定放大"推进。同时在做 **AI 工具开发**,从纯人工转向工具辅助驱动。

**在想清楚的事**:

> 收入 4 层 — 卖资料(当前主力) → 卖效率(工具化降供给成本) → 卖方法(打法做成内容产品) → 卖信任(个人 IP)

每一层都在同时推进,只是权重不同。

---

## 🚀 内容生产线(10 个自用工具的真实编排)

### 链路一:课件 → 封面 → 发布

```
PPT_XL (AI 背景刷新) 
  → ppt-batch-tool (批量导出 PNG) 
  → 融景 / BJFM (合成实拍场景 / 大字报封面) 
  → 飞书多维表格 (排期) 
  → bjfb (自动发布) 
  → 小红书 / 抖音
```

### 链路二:内容 → 知识沉淀

```
外部素材 / xhsbj 产出 
  → lark-knowledge-intake (AI 结构化) 
  → 飞书多维表格 
  → lark-knowledge-upgrade (升级知识库页面) 
  → lark-knowledge-format (彩色排版) 
  → 飞书知识库
```

### 横切基础设施

- **teacher-script**: 课件 → 逐字稿 → 飞书归档,5 个并行子代理批量处理
- **Echo**: 多 Agent 协作框架(review / obsidian-capture / roundtable),横切所有项目

---

## 📦 活跃项目

| 项目 | 一句话 | Stack |
|---|---|---|
| [PPT_XL](https://github.com/xiwenran/PPT_XL) | PPTX AI 背景刷新 · Browser Workbench | Python + FastAPI + React |
| [ppt-batch-tool](https://github.com/xiwenran/ppt-batch-tool) | PPT 批量导出 PNG · Mac/Win 双端 | PyQt6 + COM 引擎 |
| [融景](https://github.com/xiwenran/rongjing) | 截图/视频透视嵌入实拍背景 · 批量合成 | Python · 双端打包 |
| [bjfb](https://github.com/xiwenran/bjfb) | 飞书多维表格驱动的内容自动发布 | Node · AI 写作 + 红线防护 |
| [lark-knowledge](https://github.com/xiwenran/lark-knowledge) | 飞书知识库生产线(5 个 skill) | Claude Code Skill |
| [teacher](https://github.com/xiwenran/teacher) | 教学课件 → 逐字稿 → 飞书 | Claude Code Skill |
| [xhsbj](https://github.com/xiwenran/xhsbj) | 个人内容生产工作台 | Electron · v1.0.0 |
| [Echo](https://github.com/xiwenran/Echo) | 多 Agent 协作框架 | Claude Code 全局配置 |
| [claude-code-guide](https://github.com/xiwenran/claude-code-guide) | Claude Code 完全学习指南 | Vite 静态站 |

---

## 🧠 我怎么工作

**三模型分工(Opus + Codex + Sonnet)**

| 角色 | 职责 |
|---|---|
| 👑 **Opus 4.7** 主会话 | 项目负责人 · 需求拆解 · 高风险决策 · 最终把关 |
| 👷 **Codex GPT-5.4** 子代理 | 代码工人 · 机械性实现 · 自主诊断修 bug |
| ✍️ **Sonnet 4.6** 子代理 | 文本工人 · 长文档 / SKILL.md / 方案 / 复盘 |

**组件化基础设施**:  
冷眼审查(高风险改动独立 Agent 看 diff) · 圆桌讨论(多 Agent 四省架构评审方向) · Obsidian 自动捕获(跨项目方法论沉淀) · 三档失败链(Codex 重试 → Sonnet 兜底 → Opus 亲自)

所有规则物理化落到 `CLAUDE.md`,不靠记忆。

---

## 📊 GitHub 一览

<div align="center">

![Stats](https://github-readme-stats.vercel.app/api?username=xiwenran&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=xiwenran&layout=compact&theme=tokyonight&hide_border=true&langs_count=8)

![Streak](https://streak-stats.demolab.com?user=xiwenran&theme=tokyonight&hide_border=true)

</div>

---

## 🌱 现在在想的方向

- **同行监测工具化**:小红书/抖音同行账号爆文 + 评论需求的半自动监测(方案已定,暂走手动摸盘阶段)
- **把打法做成内容产品**:AI 编程实践、Claude Code 工作流、内容生产自动化这些经验,从"自己用"到"写出来卖"的转换
- **基础设施稳定性**:Claude Code 插件生态、skill 的规则层/执行层分离、跨项目方法论沉淀

---

<div align="center">

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:4A90E2,50:5E72E4,100:825EE4&height=100&section=footer)

**卖资料 · 卖效率 · 卖方法 · 卖信任** — 一层一层来

</div>
