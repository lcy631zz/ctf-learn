# ctf-learn

一个陪**零基础**网安新生做 CTF 入门题的 skill。

> **这个仓库只放 skill 本体。** 个人笔记、题解、flag 一律存在私有仓库，不公开。

---

## 它做什么

解题之后**全自动**完成，不需要你说任何提示词：

1. **讲原理** —— 为什么这样能成，零基础视角，术语当场解释
2. **给最简操作流程** —— 能一步不差照抄，必带免命令备选
3. **记进知识库** —— 写题解、更新索引、生成小测题
4. **抽新知识点** —— 碰到没覆盖的概念，自动补进笔记

解题流程本身也写死了：**先侦察后动手** —— 任何题都先看 F12 / `curl -i` 的完整请求响应，禁止靠猜字段名撞大运。

---

## 安装

```bash
mkdir -p ~/.workbuddy/skills/ctf-learn
cp SKILL.md ~/.workbuddy/skills/ctf-learn/SKILL.md
```

或：

```bash
git clone git@github.com:lcy631zz/ctf-learn.git
cp ctf-learn/SKILL.md ~/.workbuddy/skills/ctf-learn/SKILL.md
```

装好后直接对 AI 说「帮我解这道题：\<贴地址或题面\>」，或「考考我」进复习模式。

---

## 配置

skill 默认把笔记写到 `~/ctf-learn-notes/`（**私有**）。想改路径，编辑 `SKILL.md` 的「知识库规则」一节。

> ⚠️ 如果你 fork 了这个仓库：默认笔记目录是私有的，别把 `knowledge/`、`writeups/` 这类目录提交到任何公开仓库。

---

## 适用对象

- 网安 / 计科专业低年级，刚接触 CTF
- 想边做题边补协议、编码、工具基础
- 讨厌"只给 flag 不给思路"的题解

---

## 许可

随意使用、修改、分发。
