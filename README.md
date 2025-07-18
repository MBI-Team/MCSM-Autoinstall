# Minecraft 服务器配置索引

MCSManager是一个开源、分布式、开箱即用的控制面板，支持Minecraft和Steam game servers.
MCSManager提供Minecraft和其他游戏服务器支持。它帮助您管理多台物理机，在任何主机上配置游戏服务器，并提供一个安全可靠的多用户权限系统。MCSManager是大多数服务器托管服务提供商的一站式解决方案。

## 使用方法

使用MCSM管理员账户登录到面板，点击设置，在基本设置选项中，将实例模板配置设置为 
```URL

https://gh-proxy.com/github.com/MBI-Team/MCSM-Autoinstall/raw/refs/heads/main/index.json

```
然后就可以使用我们的重装模板啦。

## 功能特点

- 支持多种 Minecraft 版本（1.12.2 - 1.21.6）
- 提供多种服务器核心选择（Paper、Forge等）
- 包含预配置的整合包服务端
- 中文本地化支持
- 针对不同配置需求的优化选项

## 服务器类型

### Paper 服务端
- 支持最新版本（1.21.6）到经典版本（1.12.2）
- 优化的性能和稳定性
- 适合纯净生存服务器

### 预配置服务端
- 中文化服务端（含基础插件配置）
- 适合新手快速开服
- 低配置服务器优化版本

## 使用要求

- JDK 版本要求：
  - 1.21.x 版本：JDK 21+
  - 1.20.x 版本：JDK 17+
  - 1.16.x 及更早版本：JDK 8+
- 内存要求：最低 2GB RAM
- 建议使用 SSD 存储以获得更好性能

## 快速开始

1. 选择适合的服务器版本和类型
2. 下载对应的服务器文件
3. 确保已安装符合要求的 JDK 版本
4. 使用提供的启动命令运行服务器：
   ```bash
   # 示例启动命令
   java -Xms4096M -Xmx4096M -jar server.jar nogui
   ```

## 注意事项

- 首次启动服务器需要同意 EULA 协议
- 建议定期备份服务器数据
- 根据实际硬件配置调整内存分配
- 确保使用正确版本的 JDK

## 技术支持

如果遇到问题或需要帮助，可以：
- 查看对应版本的官方文档(https://docs.mcsmanager.com/)
- 参考社区讨论
- 提交 Issue 反馈问题
- 加入QQ交流群：[MCSM自动重装模板交流群](https://qm.qq.com/q/lse13asihU)

## 贡献

欢迎提交新的服务器配置或改进建议，让我们一起完善这个项目！

## 许可证

本项目遵循开源协议，详情请参见 LICENSE 文件。
