# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-03 13:56:51 |
| 运行耗时 | 404.4s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 128487 |
| 去重后节点 | 58547 |
| TCP 可达 | 3000 |
| 真实可用 | 64 |
| Verified 输出 | 64 |
| Global 输出 | 65 |
| All 输出 | 58547 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.6 |
| tcp | 195.7 |
| probe | 106.5 |
| real_test | 46.6 |
| china_check | 23.9 |
| write_verified | 0.1 |
| generate | 23.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 78348 |
| vmess | 18159 |
| trojan | 16182 |
| shadowsocks | 12931 |
| hysteria2 | 2248 |
| shadowsocksr | 234 |
| socks | 133 |
| http | 91 |
| hysteria | 64 |
| tuic | 59 |
| anytls | 38 |

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
| 79.38 | shadowsocks | 237.2 | 657.5 | 22.29 | 0.0 | 8.83 | 13.7 | 19.06 | dragon | 45.86.51.18 |
| 77.35 | hysteria2 | 238.1 | 581.9 | 22.27 | 0.0 | 4.27 | 12.75 | 19.06 | dragon | 88.216.195.188 |
| 77.11 | trojan | 261.8 | 623.9 | 21.72 | 0.0 | 6.75 | 12.16 | 19.06 | dragon | 216.152.155.176 |
| 76.41 | trojan | 281.9 | 666.2 | 21.25 | 0.0 | 6.44 | 12.16 | 19.06 | dragon | 170.101.101.19 |
| 76.01 | trojan | 261.6 | 635.3 | 21.72 | 0.0 | 6.57 | 12.16 | 19.06 | dragon | 216.152.155.54 |
| 75.65 | trojan | 320.2 | 590.0 | 20.36 | 0.0 | 6.57 | 12.16 | 19.06 | dragon | 216.152.155.59 |
| 75.27 | shadowsocks | 271.3 | 759.1 | 21.5 | 0.0 | 8.01 | 13.7 | 19.06 | dragon | 37.19.198.244 |
| 75.18 | trojan | 301.0 | 683.3 | 20.81 | 0.0 | 8.46 | 12.16 | 19.06 | dragon | 216.152.156.81 |
| 75.01 | shadowsocks | 255.0 | 702.1 | 21.87 | 0.0 | 4.38 | 13.7 | 19.06 | dragon | 37.19.198.160 |
| 74.91 | trojan | 311.3 | 726.5 | 20.57 | 0.0 | 7.37 | 12.16 | 19.06 | dragon | 169.197.140.245 |
| 74.68 | shadowsocks | 247.8 | 636.9 | 22.04 | 0.0 | 4.38 | 13.7 | 19.06 | dragon | 193.151.163.18 |
| 74.37 | trojan | 303.8 | 713.9 | 20.74 | 0.0 | 6.2 | 12.16 | 19.06 | dragon | 169.197.140.169 |
| 73.78 | shadowsocks | 287.3 | 806.2 | 21.13 | 0.0 | 4.39 | 13.7 | 19.06 | dragon | 185.230.230.18 |
| 73.71 | trojan | 307.8 | 708.5 | 20.65 | 0.0 | 6.33 | 12.16 | 19.06 | dragon | 216.152.156.212 |
| 73.25 | shadowsocks | 302.1 | 736.4 | 20.78 | 0.0 | 4.21 | 13.7 | 19.06 | dragon | 193.151.160.9 |
| 73.21 | shadowsocks | 294.7 | 713.1 | 20.96 | 0.0 | 4.21 | 13.7 | 19.06 | dragon | 193.151.160.18 |
| 73.2 | trojan | 325.2 | 593.2 | 20.25 | 0.0 | 10.0 | 12.16 | 19.06 | dragon | 216.106.186.33 |
| 72.84 | trojan | 311.1 | 716.4 | 20.58 | 0.0 | 6.45 | 12.16 | 19.06 | dragon | 216.152.156.65 |
| 72.5 | shadowsocks | 346.7 | 941.4 | 19.75 | 0.0 | 4.49 | 13.7 | 19.06 | dragon | 15.204.233.41 |
| 72.47 | shadowsocks | 364.8 | 852.3 | 19.33 | 0.0 | 4.38 | 13.7 | 19.06 | dragon | 216.9.225.189 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.918 | 0.841 | 301 | 45127 | prefer |
| ermaozi | 0.912 | 1.0 | 18 | 592 | prefer |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8600 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 119 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5017 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2526 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10844 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6192 | observe |
| barry-far-vless | 0.255 | None | 0 | 6407 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4753 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 33 |
| 204 | ProxyError | - | 7 |
| 204 | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 1 |
| geo | TimeoutError | - | 1 |
| cn-block | ProxyError | - | 1 |
| speed | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 59 | 64 | - |
| global | False | 61 | 65 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
