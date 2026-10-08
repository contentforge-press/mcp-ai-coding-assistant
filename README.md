# MCP AI Coding Assistant Kit

**MCP server template that gives AI coding agents live context: HN trending, web search and math tools for smarter code generation.**

> 由 AI 代码公司（PixHarvest）公司大脑按数据信号自动生成 · 模板/boilerplate × 生态市场 × 按量计费

## 快速开始
```bash
npx wrangler deploy worker.js --name mcp-ai-coding-assistant
```
然后在 Claude / Cursor / 任意 MCP 客户端添加：
```
https://mcp-ai-coding-assistant.contentforge-press.workers.dev/mcp
```

## 授权与订阅
本模板为**订阅授权**：$59/月，含免费额度；超额按量付费。
- 订阅入口: https://pixharvest.com/pricing
- 生态市场: npm (`mcp-ai-coding-assistant`) · GitHub · MCP 生态

## 工具
hn_top, web_search, calc

## 配套
完整商业化（Dodo 自动订阅校验 + 用量计费 402）见 mcp-server-billing-kit。
