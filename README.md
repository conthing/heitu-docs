# heitu-docs

**数据采集**

数据采集功能由 Zigbee 驱动实现。(conthing/heitu-zigbee/driver)

**数据存储**

数据存储功能由 Redis 驱动和微服务实现。(conthing/heitu-zigbee/redis)

- [ ] 需要约定数据结构

**数据分析 SDK 和 例程**

SDK 为 Golang 版本，主要包含 (conthing/heitu-SDK)

- [ ] Redis 基本配置、CRUD 示例
- [ ] 简单的数据分析示例。

**数据上传**

数据上传由一个微服务实现，协议为 MQTT，基本功能有 (conthing/heitu-MQTT)

- [ ] 上报指定数据
- [ ] 接受云端指令

**Web 管理**

Web 管理系统主要功能有 (conthing/heitu-web)

- [ ] 用户登陆验证
- [ ] Zigbee 设备管理和入网管理
- [ ] 系统管理
