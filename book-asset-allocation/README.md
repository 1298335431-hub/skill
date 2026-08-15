# book-asset-allocation Skill

基于《睡后收入的真相：怎样让你躺着就能赚钱》的公开可核实方法论，做个人现金流、资产占比和新增资金再平衡分析。

## 文件结构

- `SKILL.md`：Skill 主指令
- `references/methodology.md`：书中方法论摘要与版本边界
- `scripts/rebalance.py`：确定性计算脚本
- `assets/monthly-input-template.json`：月度输入模板

## 安装到 Codex

把整个 `book-asset-allocation-skill` 文件夹放到你的技能目录中。Codex 当前支持全局 `~/.agents/skills/` 或项目内 `.agents/skills/`。

安装后可以尝试：

- `$book-asset-allocation 这个月我收入 5 万、支出 2.2 万，按书里的方法帮我配置。`
- `$book-asset-allocation 我把最新四类资产余额给你，做一次半年再平衡。`

## 版本说明

这是 v0.1：依据公开可访问的书籍目录、简介与公开读者笔记提炼。若之后提供完整书籍文件或微信读书划线，可升级为“逐条对照原书”的 v1.0。
