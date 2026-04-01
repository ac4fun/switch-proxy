# switch-proxy


Quickly switch Chrome browser proxy settings with support for multiple proxy protocols and PAC auto-proxy, making proxy management simple and efficient.

✨ Key Features

🚀 Multiple Proxy Modes
• Direct Connection: Access the internet without any proxy
• Proxy Servers: Support for HTTP, HTTPS, SOCKS4, and SOCKS5 protocols
• PAC Auto-Proxy: Support for remote PAC scripts with intelligent proxy rules

⚙️ Powerful Configuration
• Add multiple proxy server configurations and switch between them instantly
• Proxy authentication support (username/password) with automatic credential filling
• Automatic PAC script refresh (hourly/daily) to keep rules up-to-date
• PAC script local caching mechanism for offline fallback

🎨 Elegant Interface
• Clean popup for quick proxy switching with just one click
• Comprehensive options page for managing all configurations
• Color-coded protocol badges (Blue HTTP, Green HTTPS, Orange SOCKS4, Pink SOCKS5, Green PAC)
• Real-time badge indicator showing current proxy status on toolbar icon

📱 Use Cases

✓ Developers debugging local proxy servers
✓ Corporate users switching between different proxies
✓ Research and education requiring specific proxy configurations
✓ Users frequently switching between different network environments
✓ Using PAC scripts for intelligent traffic routing

🎯 How to Use

Step 1: Add Proxy Configuration
• Click the extension icon and select "Open Options Page" at the bottom
• Add proxy servers in the "Proxy Server Management" tab
• Or add PAC configurations in the "PAC Auto-Proxy" tab

Step 2: Switch Proxy Mode
• Click the SwitchProxy icon on the browser toolbar
• Select the desired proxy mode from the popup list
• Active mode is highlighted with a green vertical line and light background

Step 3: Manage Configurations
• Edit or delete existing configurations in the options page
• Manual refresh button for PAC configurations
• View last refresh time for PAC scripts

🔐 Privacy & Security

• All configuration data is stored locally in your browser only
• No user data collection, analytics, or tracking services
• No advertisements, completely clean interface
• Transparent code logic, source available on GitHub
• Compliant with Chrome Extension Manifest V3 security standards

⚡ Technical Features

• Built on the latest Chrome Extension Manifest V3 specification
• Service Worker for automatic proxy state restoration on startup
• Automatic proxy authentication credential filling
• Intelligent PAC script caching for offline availability
• Responsive interface design for different screen sizes

📋 Permissions Explained

• proxy - Set browser proxy configuration
• storage - Store proxy configurations locally
• alarms - Scheduled PAC script refresh
• webRequest - Automatic proxy authentication
• host_permissions - Fetch remote PAC scripts (only when PAC is configured)

All permissions are used solely for core functionality.

🆘 Feedback & Support

For issues or feature requests:
📧 Email: ximuzmzj@gmail.com

🐛 Report Issues: https://github.com/ac4fun/switch-proxy/issues

📖 Documentation: https://github.com/ac4fun/switch-proxy


💡 FAQ

Q: Proxy not working after switching?
A: Ensure the proxy server is running and check if the address and port are correct. Open DevTools Console for error messages.

Q: PAC script refresh failed?
A: Ensure the PAC URL is accessible. If it fails, the extension will automatically use the cached script.

Q: Which browsers are supported?
A: Currently supports Chrome browser (version 88+). Chromium-based browsers (Edge, Brave) may also work.

Q: Will data sync to other devices?
A: If Chrome sync is enabled, configurations will automatically sync to your other devices.

---

🌟 If you find SwitchProxy helpful, please give us a 5-star rating and share with friends!

