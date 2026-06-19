# 可选工具

只在当前环境缺少网页/小红书读取能力，或用户明确询问如何安装时读取本文件。

## 推荐

- Agent-Reach：<https://github.com/Panniantong/Agent-Reach>
  - 用途：搜索和读取多个社交平台。
  - 注意：部分平台需要 Cookie 或登录状态。
- xiaohongshu-cli：<https://pypi.org/project/xiaohongshu-cli/>
  - 用途：小红书搜索、笔记读取等结构化操作。
  - 注意：可能需要登录 Cookie；平台接口和风控可能变化。
- Playwright：<https://playwright.dev/docs/intro>
  - 用途：当 Agent 环境允许时自建浏览器读取和 HTML 验证。

## 安装原则

- 优先使用宿主环境已有的浏览器/连接器，不重复安装。
- 先说明作用、需要的权限和风险，再征得用户同意。
- 不安装来源不明的插件，不索要用户密码，不输出 Cookie。
