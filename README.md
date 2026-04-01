## 基本信息

### 应用名称
```
SwitchProxy - 快速代理切换
```
或
```
SwitchProxy
```

### 简短描述（132 字符以内）
```
快速切换 Chrome 代理模式，支持 HTTP/HTTPS/SOCKS4/SOCKS5 代理和 PAC 自动代理，一键切换，简单高效。
```

英文版：
```
Quickly switch Chrome proxy modes. Supports HTTP/HTTPS/SOCKS4/SOCKS5 proxies and PAC scripts. Simple and efficient.
```

---

## 详细描述（中文版）

```markdown
快速切换 Chrome 浏览器的代理设置，支持多种代理协议和 PAC 自动代理，让代理管理变得简单高效。

✨ 主要功能

🚀 多种代理模式
• 直接连接：不使用任何代理，直接访问互联网
• 代理服务器：支持 HTTP、HTTPS、SOCKS4、SOCKS5 四种协议
• PAC 自动代理：支持远程 PAC 脚本，智能选择代理规则

⚙️ 强大配置
• 支持添加多个代理服务器配置，随时快速切换
• 支持代理认证（用户名/密码），自动填充无需手动输入
• PAC 脚本自动刷新（每小时/每天），始终保持最新规则
• PAC 脚本本地缓存机制，网络故障时自动回退使用缓存

🎨 优雅界面
• 简洁的 Popup 弹窗，点击图标即可快速切换代理
• 完整的选项页面，方便管理所有配置
• 彩色协议标识（蓝色 HTTP、绿色 HTTPS、橙色 SOCKS4、粉色 SOCKS5、绿色 PAC），一目了然
• 实时 Badge 状态指示，在工具栏图标上显示当前代理状态

📱 使用场景

✓ 开发者调试本地代理服务器
✓ 企业内网访问需要切换不同代理
✓ 科研教育需要使用特定代理配置
✓ 频繁切换不同网络环境的用户
✓ 使用 PAC 脚本进行智能分流

🎯 如何使用

第一步：添加代理配置
• 点击扩展图标，在弹窗底部点击「打开选项页」
• 在「代理服务器管理」标签添加代理服务器
• 或在「PAC 自动代理」标签添加 PAC 配置

第二步：切换代理模式
• 点击浏览器工具栏上的 SwitchProxy 图标
• 在弹出的列表中选择想要使用的代理模式
• 当前激活的模式会有绿色竖线和浅色背景高亮

第三步：管理配置
• 在选项页可以编辑或删除已有配置
• PAC 配置支持手动刷新按钮，立即更新脚本
• 查看 PAC 上次刷新时间，了解规则更新状态

🔐 隐私与安全

• 所有配置数据仅存储在本地浏览器中，不上传到任何服务器
• 不收集任何用户数据，不使用任何分析或跟踪服务
• 不显示任何广告，纯净无干扰
• 代码逻辑透明，可在 GitHub 上查看源代码
• 符合 Chrome Extension Manifest V3 安全标准

⚡ 技术特点

• 基于最新的 Chrome Extension Manifest V3 规范开发
• 使用 Service Worker 后台服务，启动时自动恢复代理状态
• 支持代理认证自动填充，无需每次手动输入密码
• PAC 脚本智能缓存机制，确保离线时仍可使用
• 响应式界面设计，适配不同屏幕尺寸

📋 权限说明

• proxy - 设置浏览器代理配置
• storage - 本地存储代理配置
• alarms - PAC 脚本定时刷新
• webRequest - 代理认证自动填充
• host_permissions - 拉取远程 PAC 脚本（仅在配置 PAC 时使用）

所有权限仅用于实现核心功能，不会用于其他任何目的。

🆘 反馈与支持

如遇到问题或有功能建议，欢迎联系：
📧 邮箱：ximuzmzj@gmail.com
🐛 问题反馈：https://github.com/ac4fun/switch-proxy/issues
📖 使用文档：https://github.com/ac4fun/switch-proxy

💡 常见问题

Q：切换代理后没有生效怎么办？
A：请确保代理服务器正常运行，并检查地址和端口是否正确。可以打开 DevTools 查看 Console 是否有错误信息。

Q：PAC 脚本刷新失败怎么办？
A：请确保 PAC URL 可以正常访问。如果 URL 正常但仍失败，扩展会自动使用本地缓存的脚本。

Q：支持哪些浏览器？
A：目前仅支持 Chrome 浏览器（需 88 及以上版本）。基于 Chromium 的浏览器（如 Edge、Brave）理论上也可以使用。

Q：数据会同步到其他设备吗？
A：如果您启用了 Chrome 同步功能，配置会自动同步到您的其他设备。

---

🌟 如果您觉得 SwitchProxy 好用，请给我们 5 星好评并分享给朋友，这是对我们最大的支持！
```


## 分类和标签

### 主要分类
- **开发者工具** (Developer Tools)
- 或 **生产工具** (Productivity)

### 标签建议
```
proxy, socks, http, https, pac, switch, network, developer, tool, productivity
```

---

## 支持的语言
- 中文（简体）
- English

---

## 截图标题建议

1. **Popup 界面**
   - 中文：「快速切换代理模式」
   - 英文：「Quick Proxy Switching」

2. **代理服务器管理**
   - 中文：「管理多个代理配置」
   - 英文：「Manage Multiple Proxy Configurations」

3. **PAC 配置管理**
   - 中文：「智能 PAC 自动代理」
   - 英文：「Smart PAC Auto-Proxy」

4. **彩色协议标识**
   - 中文：「一目了然的协议标识」
   - 英文：「Clear Protocol Indicators」

5. **实时状态指示**
   - 中文：「Badge 实时显示代理状态」
   - 英文：「Real-time Proxy Status Badge」
