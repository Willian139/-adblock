# SportAdBlock

一款面向 Android 的运动世界校园 DNS 广告过滤工具。

## 功能

- 使用 Android VpnService 建立本地 VPN。
- 基于 DNS 域名规则过滤指定域名。
- 显示过滤运行状态、拦截次数和最近拦截记录。
- 支持手动开启和停止过滤。
- 不需要注册账号或连接项目自建服务器。

## 技术栈

- Java
- Android SDK
- Android VpnService
- Gradle

## 项目结构

```text
SportAdBlock/
├── app/
│   └── src/main/
│       ├── java/com/sportadblock/
│       │   ├── MainActivity.java
│       │   └── AdBlockVpnService.java
│       ├── assets/
│       │   └── rules.txt
│       └── AndroidManifest.xml
├── build.gradle
├── settings.gradle
└── README.md
cd ~/SportAdBlock

cat > README.md <<'EOF'
# SportAdBlock

一款面向 Android 的运动世界校园 DNS 广告过滤工具。

## 功能

- 使用 Android VpnService 建立本地 VPN。
- 基于 DNS 域名规则过滤指定域名。
- 显示过滤状态、拦截次数和最近拦截记录。
- 支持手动开启和停止过滤。

## 技术栈

- Java
- Android SDK
- Android VpnService
- Gradle

## 项目说明

本项目的 Android 应用代码由开发者在 AI 辅助下编写和修改。

广告域名规则参考了相关公开项目。规则清单不应被视为本项目原创成果。感谢相关原作者及开源社区贡献者。

原始规则的具体来源和适用许可证仍需核实。本项目暂不声明统一的开源许可证。

## 技术限制

- 主要处理 IPv4 UDP DNS 查询。
- 不解密 HTTPS 流量。
- 无法保证过滤所有广告。
- 过滤效果取决于域名规则及目标应用的网络行为。

## 免责声明

本项目仅供学习和研究。使用者应遵守适用法律及相关应用的服务条款。
