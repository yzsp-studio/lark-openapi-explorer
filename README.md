<div align="center">

# 🎬 lark-openapi-explorer

## 现有命令覆盖不到？去官方文档底层把原生接口挖出来直接用
## When no command fits, dig the raw API straight out of the official docs

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

这是一个原生 OpenAPI 探索技能：当需求无法被现有技能或已注册命令满足时，从官方文档库里挖掘未经封装的原生接口，并把它调用起来。技能先明确文档库结构与挖掘流程，再按「确认现有能力不足 → 从顶层索引定位模块 → 从模块文档定位具体 API → 获取 API 完整规范」四步走，避免一上来就盲搜。产出是可实际调用的原生接口与完整调用规范。

### ✨ 能做什么

- 在现有技能与已注册命令覆盖不到时启用
- 先确认能力不足，再从顶层索引进模块
- 从模块文档定位具体 API，再获取完整规范
- 梳理文档库结构，明确挖掘流程
- 产出可直接调用的原生接口与完整参数规范
- 按步骤推进，避免无依据的盲搜与试错

### 📦 包含的技能

- `lark-openapi-explorer` —— 见 [`lark-openapi-explorer/SKILL.md`](lark-openapi-explorer/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/lark-openapi-explorer.git
cp -r lark-openapi-explorer/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

An explorer skill for native OpenAPI: when no existing skill or registered command can satisfy a request, it mines un-wrapped native endpoints out of the official documentation library and gets them called. It documents the library structure and a staged digging flow—confirm existing coverage is insufficient, locate the module from the top-level index, find the specific API in the module doc, then pull the full API spec—so nothing starts with blind searching. The output is a callable native endpoint plus its complete request/response contract.

### ✨ What it does

- Kicks in only when existing skills and registered commands fall short
- Confirms the coverage gap, then walks the top-level index into a module
- Locates the exact API in module docs, then pulls its full spec
- Maps the documentation-library structure behind the flow
- Yields a callable native endpoint with a complete parameter contract
- Staged four-step dig instead of unfounded blind searching

### 📦 Skills included

- `lark-openapi-explorer` — [`lark-openapi-explorer/SKILL.md`](lark-openapi-explorer/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/lark-openapi-explorer.git
cp -r lark-openapi-explorer/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
