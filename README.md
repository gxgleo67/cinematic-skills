<div align="center">

# 🎬 像大师一样拍电影 · Cinematic Skills

**把电影大师的拍摄智慧，装进你的 AI 助手**

从 6 本经典电影技法书中提炼的 Agent Skills —— 镜头设计 × 场景转换

**中文** | [English](README_EN.md)

![Skills](https://img.shields.io/badge/skills-2-blue)
![Chapters](https://img.shields.io/badge/chapters-65-green)
![Techniques](https://img.shields.io/badge/techniques-400%2B-orange)
![Language](https://img.shields.io/badge/lang-%E4%B8%AD%E6%96%87-red)

<img src="assets/banner.webp" alt="像大师一样拍电影" width="100%">

</div>

---

## 📦 包含的技能

| Skill | 中文名 | 章节 | 适合场景 |
|---|---|---|---|
| **cinematic-shots** | 像大师一样运镜 | 55 | 设计镜头、拍对话戏/动作戏/悬疑戏、经典场景拉片解析 |
| **cinematic-transitions** | 像大师一样转场 | 10 | 场景衔接、转场设计、段落节奏、剪辑叙事 |

<p align="center">
  <img src="assets/orbit.webp" alt="像大师一样运镜" width="48%">
  &nbsp;
  <img src="assets/transitions.webp" alt="像大师一样转场" width="48%">
</p>
<p align="center">
  <sub>像大师一样运镜 —— 环绕调度</sub> &nbsp;&nbsp;&nbsp;&nbsp; <sub>像大师一样转场 —— 场景的溶解与衔接</sub>
</p>

## 🗂 目录结构

```
cinematic-skills/
├── cinematic-shots/              # 像大师一样运镜
│   ├── SKILL.md                  # 入口：核心框架 + 章节/主题索引
│   ├── chapters/                 # 55 个章节精华（按需加载）
│   ├── glossary.md               # 46 条术语表
│   ├── patterns.md               # 30 个技巧模式（何时用/怎么做/取舍）
│   ├── cheatsheet.md             # 决策速查（规则表 + 决策路径）
│   └── _index-*.md               # 各卷索引（章节地图）
│
└── cinematic-transitions/        # 像大师一样转场
    ├── SKILL.md                  # 入口：场景转换十大框架
    ├── chapters/                 # 10 个章节精华
    ├── glossary.md               # 53 条术语表
    ├── patterns.md               # 20 个转换手法模式
    └── cheatsheet.md             # 转场决策树 + 权衡矩阵
```

## 🚀 安装

**方式一：skills CLI（任何兼容 Agent Skills 的宿主）**

```bash
npx skills add https://github.com/gxgleo67/cinematic-skills --skill cinematic-shots
npx skills add https://github.com/gxgleo67/cinematic-skills --skill cinematic-transitions
```

**方式二：手动拷贝**

把 `cinematic-shots/` 和 `cinematic-transitions/` 拷到你的 skills 目录：

| 宿主 | 目录 |
|---|---|
| Kimi Code | `~/.kimi-code/skills/` |
| Claude Code | `~/.claude/skills/` |
| Copilot CLI / Codex | `~/.agents/skills/` |

拷完重开会话即可被发现。

## 💡 使用示例

```
用 cinematic-shots 讲讲追逐戏怎么拍才有紧张感
cinematic-shots 里多人对话怎么分配机位？
拍一段电话分手的戏，查 cinematic-shots 的远距离交谈
cinematic-transitions：两个情绪反差很大的场景怎么接？
cinematic-transitions 的 ch08 讲了什么？
```

不带参数提问时加载核心框架速查；带主题时自动定位并读取对应章节文件。

## 📖 完整案例

[案例：一场「坦白戏」的完整设计](examples/案例-坦白戏.md) —— 从转场进入到镜头执行，演示如何让 agent 用这两个技能设计一场戏：每一步决策都标注了出处章节。

## ✨ 内容特色

- **提炼结构，不是书摘** —— 每个章节文件都是「技巧名 + 何时用 + 怎么做 + 反模式 + 影片实例」的工具箱
- **忠实原始命名** —— 保留技巧的原称（如「延迟揭示」「借物摇镜」「六节点配额法」）
- **400+ 编号技巧全覆盖** —— 逐节比对，零缺失
- **冲突已调和** —— 不同来源的矛盾建议已标注主次与例外条件
- **实战决策导向** —— cheatsheet 是「当 X 做 Y 因为 Z」的判断逻辑，不是关键词列表

## 🎞 从分镜到成片

从分镜草图到成片画面，只差一套正确的方法：

<p align="center">
  <img src="assets/storyboard-split.webp" alt="从分镜到成片" width="88%">
</p>

---

<div align="center">
<sub>Made with Kimi Code</sub>
</div>
