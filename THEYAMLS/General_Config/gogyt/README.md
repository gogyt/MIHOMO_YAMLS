# 📂 gogyt (通用进阶配置)

[🔙 返回上一级](../README.md)

> 🤖 自动技术分析 | 10 个配置文件

## ⚔️ 配置横向对比

| 特性 | `RulePro.yaml` | `RuleLite.yaml` | `Rule.yaml` | `RuleBeta.yaml` | `GeoPro.yaml` | `Geo.yaml` | `GeoLitePro.yaml` | `GeoLite.yaml` | `GeoBeta.yaml` | `RuleLitePro.yaml` |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **大小** | 61.4 KB | 38.5 KB | 48.2 KB | 67.0 KB | 53.9 KB | 42.1 KB | 39.4 KB | 34.9 KB | 45.8 KB | 43.0 KB |
| **混合端口** | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 |
| **面板地址** | 0.0.0.0:9090 | 0.0.0.0:9090 | 0.0.0.0:9090 | 0.0.0.0:9090 | 0.0.0.0:9090 | 0.0.0.0:9090 | 0.0.0.0:9090 | 0.0.0.0:9090 | 0.0.0.0:9090 | 0.0.0.0:9090 |
| **运行模式** | rule | rule | rule | rule | rule | rule | rule | rule | rule | rule |
| **TUN** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **策略组** | **128** | **48** | **68** | **169** | **128** | **68** | **64** | **48** | **90** | **64** |
| **规则数** | **62** | **31** | **51** | **64** | **61** | **50** | **30** | **30** | **61** | **31** |

## 📄 配置详情

#### 📝 RulePro.yaml
- **路径**: `RulePro.yaml` | **大小**: 61.4 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/RulePro.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (128个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 Github | `select` |
| 👆 油管视频 | `select` |
| 👆 谷歌FCM | `select` |
| 👆 谷歌服务 | `select` |
| 👆 Gemini | `select` |
| 👆 Claude | `select` |
| 👆 ChatGPT | `select` |
| 👆 Grok | `select` |
| 👆 AI服务 | `select` |
| 👆 维基百科 | `select` |
| 👆 即时通讯 | `select` |
| 👆 国外电商 | `select` |
| 👆 加密货币 | `select` |
| 👆 社交媒体 | `select` |
| 👆 TikTok | `select` |
| 👆 奈飞视频 | `select` |
| 👆 迪士尼+ | `select` |
| 👆 HBO | `select` |
| ... | 还有 108 个 |
</details>

#### 📝 RuleLite.yaml
- **路径**: `RuleLite.yaml` | **大小**: 38.5 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/RuleLite.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (48个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 漏网之鱼 | `select` |
| 👆 网络测试 | `select` |
| 👆 直接连接 | `select` |
| 👆 狮城策略 | `select` |
| 👆 香港策略 | `select` |
| 👆 日本策略 | `select` |
| 👆 美国策略 | `select` |
| 👆 台湾策略 | `select` |
| 👆 欧洲策略 | `select` |
| 👆 韩国策略 | `select` |
| 👆 其他策略 | `select` |
| ⚖️ 香港散列 | `load-balance` |
| ⚖️ 台湾散列 | `load-balance` |
| ⚖️ 狮城散列 | `load-balance` |
| ⚖️ 日本散列 | `load-balance` |
| ⚖️ 韩国散列 | `load-balance` |
| ⚖️ 美国散列 | `load-balance` |
| ⚖️ 欧洲散列 | `load-balance` |
| ... | 还有 28 个 |
</details>

#### 📝 Rule.yaml
- **路径**: `Rule.yaml` | **大小**: 48.2 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/Rule.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (68个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 Github | `select` |
| 👆 油管视频 | `select` |
| 👆 谷歌服务 | `select` |
| 👆 AI服务 | `select` |
| 👆 国外电商 | `select` |
| 👆 加密货币 | `select` |
| 👆 即时通讯 | `select` |
| 👆 社交媒体 | `select` |
| 👆 TikTok | `select` |
| 👆 奈飞视频 | `select` |
| 👆 迪士尼+ | `select` |
| 👆 HBO | `select` |
| 👆 Prime Video | `select` |
| 👆 Spotify | `select` |
| 👆 国外娱乐 | `select` |
| 👆 Bing(Copilot) | `select` |
| 👆 微软服务 | `select` |
| 👆 苹果服务 | `select` |
| ... | 还有 48 个 |
</details>

#### 📝 RuleBeta.yaml
- **路径**: `RuleBeta.yaml` | **大小**: 67.0 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/RuleBeta.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (169个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 Github | `select` |
| 👆 油管视频 | `select` |
| 👆 谷歌FCM | `select` |
| 👆 谷歌服务 | `select` |
| 👆 Gemini | `select` |
| 👆 Claude | `select` |
| 👆 ChatGPT | `select` |
| 👆 Grok | `select` |
| 👆 AI服务 | `select` |
| 👆 维基百科 | `select` |
| 👆 即时通讯 | `select` |
| 👆 国外电商 | `select` |
| 👆 加密货币 | `select` |
| 👆 社交媒体 | `select` |
| 👆 TikTok | `select` |
| 👆 奈飞视频 | `select` |
| 👆 迪士尼+ | `select` |
| 👆 HBO | `select` |
| ... | 还有 149 个 |
</details>

#### 📝 GeoPro.yaml
- **路径**: `GeoPro.yaml` | **大小**: 53.9 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/GeoPro.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (128个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 Github | `select` |
| 👆 油管视频 | `select` |
| 👆 谷歌FCM | `select` |
| 👆 谷歌服务 | `select` |
| 👆 Gemini | `select` |
| 👆 Claude | `select` |
| 👆 ChatGPT | `select` |
| 👆 Grok | `select` |
| 👆 AI服务 | `select` |
| 👆 维基百科 | `select` |
| 👆 即时通讯 | `select` |
| 👆 国外电商 | `select` |
| 👆 加密货币 | `select` |
| 👆 社交媒体 | `select` |
| 👆 TikTok | `select` |
| 👆 奈飞视频 | `select` |
| 👆 迪士尼+ | `select` |
| 👆 HBO | `select` |
| ... | 还有 108 个 |
</details>

#### 📝 Geo.yaml
- **路径**: `Geo.yaml` | **大小**: 42.1 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/Geo.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (68个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 Github | `select` |
| 👆 油管视频 | `select` |
| 👆 谷歌服务 | `select` |
| 👆 AI服务 | `select` |
| 👆 国外电商 | `select` |
| 👆 加密货币 | `select` |
| 👆 即时通讯 | `select` |
| 👆 社交媒体 | `select` |
| 👆 TikTok | `select` |
| 👆 奈飞视频 | `select` |
| 👆 迪士尼+ | `select` |
| 👆 HBO | `select` |
| 👆 Prime Video | `select` |
| 👆 Spotify | `select` |
| 👆 国外娱乐 | `select` |
| 👆 Bing(Copilot) | `select` |
| 👆 微软服务 | `select` |
| 👆 苹果服务 | `select` |
| ... | 还有 48 个 |
</details>

#### 📝 GeoLitePro.yaml
- **路径**: `GeoLitePro.yaml` | **大小**: 39.4 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/GeoLitePro.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (64个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 漏网之鱼 | `select` |
| 👆 网络测试 | `select` |
| 👆 直接连接 | `select` |
| 👆 狮城策略 | `select` |
| 👆 香港策略 | `select` |
| 👆 日本策略 | `select` |
| 👆 美国策略 | `select` |
| 👆 台湾策略 | `select` |
| 👆 欧洲策略 | `select` |
| 👆 韩国策略 | `select` |
| 👆 其他策略 | `select` |
| ⚖️ [主] 香港散列 | `load-balance` |
| ⚖️ [主] 台湾散列 | `load-balance` |
| ⚖️ [主] 狮城散列 | `load-balance` |
| ⚖️ [主] 日本散列 | `load-balance` |
| ⚖️ [主] 韩国散列 | `load-balance` |
| ⚖️ [主] 美国散列 | `load-balance` |
| ⚖️ [主] 欧洲散列 | `load-balance` |
| ... | 还有 44 个 |
</details>

#### 📝 GeoLite.yaml
- **路径**: `GeoLite.yaml` | **大小**: 34.9 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/GeoLite.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (48个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 漏网之鱼 | `select` |
| 👆 网络测试 | `select` |
| 👆 直接连接 | `select` |
| 👆 狮城策略 | `select` |
| 👆 香港策略 | `select` |
| 👆 日本策略 | `select` |
| 👆 美国策略 | `select` |
| 👆 台湾策略 | `select` |
| 👆 欧洲策略 | `select` |
| 👆 韩国策略 | `select` |
| 👆 其他策略 | `select` |
| ⚖️ 香港散列 | `load-balance` |
| ⚖️ 台湾散列 | `load-balance` |
| ⚖️ 狮城散列 | `load-balance` |
| ⚖️ 日本散列 | `load-balance` |
| ⚖️ 韩国散列 | `load-balance` |
| ⚖️ 美国散列 | `load-balance` |
| ⚖️ 欧洲散列 | `load-balance` |
| ... | 还有 28 个 |
</details>

#### 📝 GeoBeta.yaml
- **路径**: `GeoBeta.yaml` | **大小**: 45.8 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/GeoBeta.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (90个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 Github | `select` |
| 👆 油管视频 | `select` |
| 👆 谷歌FCM | `select` |
| 👆 谷歌服务 | `select` |
| 👆 Gemini | `select` |
| 👆 Claude | `select` |
| 👆 ChatGPT | `select` |
| 👆 Grok | `select` |
| 👆 AI服务 | `select` |
| 👆 维基百科 | `select` |
| 👆 即时通讯 | `select` |
| 👆 国外电商 | `select` |
| 👆 加密货币 | `select` |
| 👆 社交媒体 | `select` |
| 👆 TikTok | `select` |
| 👆 奈飞视频 | `select` |
| 👆 迪士尼+ | `select` |
| 👆 HBO | `select` |
| ... | 还有 70 个 |
</details>

#### 📝 RuleLitePro.yaml
- **路径**: `RuleLitePro.yaml` | **大小**: 43.0 KB | [查看源码](https://github.com/gogyt/MIHOMO_YAMLS/blob/main/THEYAMLS/General_Config/gogyt/RuleLitePro.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (64个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 👆 默认直连 | `select` |
| 👆 漏网之鱼 | `select` |
| 👆 网络测试 | `select` |
| 👆 直接连接 | `select` |
| 👆 狮城策略 | `select` |
| 👆 香港策略 | `select` |
| 👆 日本策略 | `select` |
| 👆 美国策略 | `select` |
| 👆 台湾策略 | `select` |
| 👆 欧洲策略 | `select` |
| 👆 韩国策略 | `select` |
| 👆 其他策略 | `select` |
| ⚖️ [主] 香港散列 | `load-balance` |
| ⚖️ [主] 台湾散列 | `load-balance` |
| ⚖️ [主] 狮城散列 | `load-balance` |
| ⚖️ [主] 日本散列 | `load-balance` |
| ⚖️ [主] 韩国散列 | `load-balance` |
| ⚖️ [主] 美国散列 | `load-balance` |
| ⚖️ [主] 欧洲散列 | `load-balance` |
| ... | 还有 44 个 |
</details>
