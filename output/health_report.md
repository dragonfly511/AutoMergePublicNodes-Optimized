# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-16 12:25:09 |
| 运行耗时 | 322.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99281 |
| 去重后节点 | 27679 |
| TCP 可达 | 3000 |
| 真实可用 | 93 |
| Verified 输出 | 93 |
| Global 输出 | 99 |
| All 输出 | 27679 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.3 |
| geo | 1.4 |
| tcp | 87.5 |
| probe | 105.6 |
| real_test | 83.4 |
| china_check | 32.3 |
| write_verified | 0.0 |
| generate | 7.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58413 |
| vmess | 16416 |
| shadowsocks | 11909 |
| trojan | 10275 |
| hysteria2 | 1256 |
| http | 740 |
| shadowsocksr | 165 |
| socks | 59 |
| anytls | 25 |
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
| 78.61 | hysteria2 | 272.8 | 704.8 | 21.46 | 0.0 | 10.0 | 12.19 | 16.46 | Au1rxx-base64 | 129.213.91.185 |
| 78.17 | shadowsocks | 241.9 | 602.3 | 22.18 | 0.0 | 10.0 | 13.53 | 16.46 | Au1rxx-base64 | 156.146.38.170 |
| 77.99 | shadowsocks | 249.6 | 622.0 | 22.0 | 0.0 | 10.0 | 13.53 | 16.46 | Au1rxx-base64 | 156.146.38.167 |
| 77.94 | shadowsocks | 240.4 | 615.3 | 22.21 | 0.0 | 10.0 | 13.53 | 16.46 | Au1rxx-base64 | 156.146.38.169 |
| 77.36 | shadowsocks | 276.7 | 690.0 | 21.37 | 0.0 | 10.0 | 13.53 | 16.46 | Au1rxx-base64 | 156.146.38.168 |
| 76.59 | shadowsocks | 310.0 | 756.6 | 20.6 | 0.0 | 10.0 | 13.53 | 16.46 | Au1rxx-base64 | 37.19.198.236 |
| 75.52 | shadowsocks | 305.4 | 728.8 | 20.71 | 0.0 | 10.0 | 13.53 | 16.46 | Au1rxx-base64 | 37.19.198.243 |
| 72.79 | http | 309.1 | 728.2 | 20.62 | 0.0 | 0.0 | 14.67 | 20.0 | ermaozi | 172.64.68.89 |
| 72.6 | shadowsocks | 316.6 | 680.1 | 20.45 | 0.0 | 10.0 | 13.53 | 16.46 | Au1rxx-base64 | 149.22.95.183 |
| 71.86 | shadowsocks | 331.2 | 835.1 | 20.11 | 0.0 | 10.0 | 13.53 | 16.46 | Au1rxx-base64 | 37.19.198.244 |
| 71.42 | vless | 272.0 | 637.3 | 21.48 | 0.0 | 7.91 | 7.25 | 16.46 | Au1rxx-base64 | 195.211.98.43 |
| 69.93 | http | 314.2 | 704.4 | 20.5 | 0.0 | 0.0 | 14.67 | 20.0 | ermaozi | 64.98.50.100 |
| 69.56 | shadowsocks | 415.9 | 998.8 | 18.15 | 0.0 | 10.0 | 13.53 | 16.46 | Au1rxx-base64 | 51.222.136.236 |
| 69.08 | shadowsocks | 295.9 | 594.7 | 20.93 | 0.0 | 5.87 | 13.53 | 16.46 | Au1rxx-base64 | 173.244.56.9 |
| 69.02 | hysteria2 | 271.8 | 592.5 | 21.49 | 0.0 | 2.06 | 12.19 | 16.46 | Au1rxx-base64 | 66.94.121.46 |
| 68.35 | http | 295.4 | 595.7 | 20.94 | 0.0 | 0.0 | 14.67 | 20.0 | ermaozi | 138.199.35.210 |
| 68.29 | http | 295.7 | 606.4 | 20.93 | 0.0 | 0.0 | 14.67 | 20.0 | ermaozi | 138.199.35.206 |
| 68.28 | http | 296.6 | 601.8 | 20.91 | 0.0 | 0.0 | 14.67 | 20.0 | ermaozi | 138.199.35.202 |
| 68.27 | http | 368.6 | 897.1 | 19.25 | 0.0 | 0.0 | 14.67 | 20.0 | ermaozi | 38.247.141.135 |
| 68.1 | http | 301.8 | 623.1 | 20.79 | 0.0 | 0.0 | 14.67 | 20.0 | ermaozi | 138.199.35.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.995 | 0.978 | 90 | 693 | prefer |
| Au1rxx-base64 | 0.754 | 0.675 | 345 | 1990 | prefer |
| mheidari-all | 0.474 | 0.467 | 15 | 23871 | observe |
| Surfboard-tg-mixed | 0.455 | 0.367 | 30 | 7090 | observe |
| DeltaKronecker-all | 0.349 | 0.667 | 3 | 4946 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5024 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1990 | observe |
| Epodonios-all | 0.255 | None | 0 | 7568 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10091 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5572 | observe |
| barry-far-vless | 0.255 | None | 0 | 5827 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4265 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 85 |
| speed | ClientOSError | - | 15 |
| 204 | TimeoutError | - | 10 |
| geo | ClientOSError | - | 8 |
| cn-block | ClientOSError | - | 7 |
| cn-block | ProxyError | - | 6 |
| 204 | ProxyError | - | 5 |
| cn-block | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | TimeoutError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 104 | 93 | - |
| global | False | 112 | 99 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
