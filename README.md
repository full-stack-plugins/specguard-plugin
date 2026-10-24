# SpecGuard（需求规格防护）

> 校验规格基线、追踪关系与覆盖缺口；语义歧义交人工复核。

版本：0.1.0 · 许可证：Apache-2.0

## 定位

让需求、验收、设计、任务与测试义务保持可追踪。

当前为插件脚手架：有真实 CLI 时执行并保留证据；无 CLI 时明确输出 DESIGN_ONLY，不冒充通过。

## 安装

codex plugin marketplace add partme-ai/full-stack-plugins
codex plugin add specguard@full-stack-plugins

## 边界

- 不替代其他专业 Guard。
- 不绕过受保护分支、必需检查或人工审批。
