# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-17 06:22:02 |
| 运行耗时 | 347.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99657 |
| 去重后节点 | 27787 |
| TCP 可达 | 3000 |
| 真实可用 | 79 |
| Verified 输出 | 79 |
| Global 输出 | 86 |
| All 输出 | 27787 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.2 |
| geo | 1.5 |
| tcp | 84.4 |
| probe | 106.7 |
| real_test | 98.8 |
| china_check | 33.9 |
| write_verified | 0.2 |
| generate | 13.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58451 |
| vmess | 16611 |
| shadowsocks | 12068 |
| trojan | 10202 |
| hysteria2 | 1330 |
| http | 717 |
| shadowsocksr | 168 |
| socks | 61 |
| anytls | 26 |
| hysteria | 17 |
| tuic | 6 |

## 评分权重

| 因子 | 权重 |
| --- | --- |
| latency | 25.0 |
| jitter | 15.0 |
| tcp | 10.0 |
| speed | 10.0 |
| fingerprint_resistance | 5.0 |
| protocol_history | 15.0 |
| source_history | 20.0 |

## Top 节点评分

| 评分 | 协议 | 延迟(ms) | 抖动(ms) | 延迟分 | 抖动分 | TCP分 | 协议历史分 | 来源历史分 | 来源 | 服务器 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 80.99 | shadowsocks | 241.2 | 575.3 | 22.2 | 0.0 | 10.0 | 14.25 | 18.54 | Au1rxx-base64 | 149.22.95.183 |
| 80.77 | shadowsocks | 250.6 | 533.2 | 21.98 | 0.0 | 10.0 | 14.25 | 18.54 | Au1rxx-base64 | 173.244.56.9 |
| 80.71 | shadowsocks | 253.0 | 540.4 | 21.92 | 0.0 | 10.0 | 14.25 | 18.54 | Au1rxx-base64 | 173.244.56.6 |
| 80.3 | vless | 208.9 | 535.3 | 22.94 | 0.0 | 9.75 | 9.07 | 18.54 | Au1rxx-base64 | 154.29.159.211 |
| 79.67 | vless | 203.3 | 512.1 | 23.07 | 0.0 | 8.99 | 9.07 | 18.54 | Au1rxx-base64 | 23.95.222.127 |
| 79.32 | vless | 214.6 | 520.0 | 22.81 | 0.0 | 8.9 | 9.07 | 18.54 | Au1rxx-base64 | 154.9.241.170 |
| 78.33 | shadowsocks | 325.4 | 540.0 | 20.24 | 0.0 | 9.8 | 14.25 | 18.54 | Au1rxx-base64 | 103.11.76.248 |
| 76.14 | shadowsocks | 323.2 | 630.9 | 20.3 | 0.0 | 10.0 | 14.25 | 18.54 | Au1rxx-base64 | 156.146.38.167 |
| 76.05 | shadowsocks | 319.9 | 624.0 | 20.37 | 0.0 | 10.0 | 14.25 | 18.54 | Au1rxx-base64 | 156.146.38.169 |
| 75.6 | shadowsocks | 319.0 | 629.0 | 20.39 | 0.0 | 9.45 | 14.25 | 18.54 | Au1rxx-base64 | 156.146.38.168 |
| 75.06 | vless | 315.6 | 705.6 | 20.47 | 0.0 | 10.0 | 9.07 | 18.54 | Au1rxx-base64 | 147.45.60.160 |
| 74.98 | vless | 223.1 | 482.4 | 22.61 | 0.0 | 9.76 | 9.07 | 18.54 | Au1rxx-base64 | 45.63.53.81 |
| 74.77 | vless | 194.3 | 482.1 | 23.28 | 0.0 | 8.88 | 9.07 | 18.54 | Au1rxx-base64 | 176.122.183.26 |
| 74.48 | http | 201.7 | 518.7 | 23.11 | 0.0 | 0.0 | 14.53 | 19.84 | ermaozi | 138.199.35.198 |
| 74.43 | http | 203.9 | 515.8 | 23.06 | 0.0 | 0.0 | 14.53 | 19.84 | ermaozi | 138.199.35.214 |
| 74.42 | http | 204.4 | 515.2 | 23.05 | 0.0 | 0.0 | 14.53 | 19.84 | ermaozi | 138.199.35.216 |
| 74.35 | http | 207.3 | 519.9 | 22.98 | 0.0 | 0.0 | 14.53 | 19.84 | ermaozi | 138.199.35.195 |
| 74.26 | http | 211.3 | 512.6 | 22.89 | 0.0 | 0.0 | 14.53 | 19.84 | ermaozi | 38.95.111.226 |
| 73.5 | http | 200.9 | 507.9 | 23.13 | 0.0 | 0.0 | 14.53 | 19.84 | ermaozi | 138.199.35.197 |
| 73.5 | http | 200.9 | 514.1 | 23.13 | 0.0 | 0.0 | 14.53 | 19.84 | ermaozi | 138.199.35.205 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.999 | 0.98 | 100 | 702 | prefer |
| Au1rxx-base64 | 0.845 | 0.766 | 364 | 1993 | prefer |
| Surfboard-tg-mixed | 0.372 | 0.283 | 46 | 7109 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4986 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1993 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 4946 | observe |
| Epodonios-all | 0.255 | None | 0 | 7630 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10064 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5597 | observe |
| barry-far-vless | 0.255 | None | 0 | 5847 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 113 |
| geo | ClientOSError | - | 22 |
| speed | ClientOSError | - | 16 |
| 204 | ProxyError | - | 9 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 4 |
| 204 | TimeoutError | - | 3 |
| speed | ClientPayloadError | - | 2 |
| speed | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 86 | 79 | - |
| global | False | 93 | 86 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
