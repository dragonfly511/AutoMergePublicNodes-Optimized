# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-13 05:46:29 |
| 运行耗时 | 361.1s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 126823 |
| 去重后节点 | 58440 |
| TCP 可达 | 3000 |
| 真实可用 | 60 |
| Verified 输出 | 60 |
| Global 输出 | 60 |
| All 输出 | 58440 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.6 |
| tcp | 202.2 |
| probe | 76.1 |
| real_test | 32.9 |
| china_check | 22.5 |
| write_verified | 0.0 |
| generate | 20.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77582 |
| vmess | 18854 |
| trojan | 14083 |
| shadowsocks | 13125 |
| hysteria2 | 2218 |
| tuic | 271 |
| http | 266 |
| shadowsocksr | 228 |
| socks | 90 |
| hysteria | 72 |
| anytls | 34 |

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
| 79.47 | trojan | 245.3 | 597.5 | 22.1 | 0.0 | 5.86 | 14.01 | 20.0 | dragon | 216.152.155.54 |
| 79.42 | trojan | 260.6 | 631.8 | 21.75 | 0.0 | 6.16 | 14.01 | 20.0 | dragon | 216.152.155.176 |
| 78.68 | trojan | 285.8 | 545.2 | 21.16 | 0.0 | 6.01 | 14.01 | 20.0 | dragon | 66.163.114.114 |
| 76.91 | hysteria2 | 304.6 | 708.1 | 20.73 | 0.0 | 4.42 | 14.0 | 20.0 | dragon | 34.24.25.1 |
| 76.52 | trojan | 282.6 | 636.1 | 21.24 | 0.0 | 5.89 | 14.01 | 20.0 | dragon | 170.101.101.53 |
| 76.26 | trojan | 283.0 | 692.2 | 21.23 | 0.0 | 5.91 | 14.01 | 20.0 | dragon | 170.101.101.211 |
| 75.86 | shadowsocks | 349.2 | 876.3 | 19.69 | 0.0 | 6.79 | 13.88 | 20.0 | dragon | 167.88.62.56 |
| 75.2 | trojan | 300.3 | 719.8 | 20.83 | 0.0 | 5.87 | 14.01 | 20.0 | dragon | 170.101.101.237 |
| 75.15 | trojan | 317.7 | 709.2 | 20.42 | 0.0 | 5.95 | 14.01 | 20.0 | dragon | 216.152.156.49 |
| 75.02 | shadowsocks | 327.6 | 822.5 | 20.2 | 0.0 | 6.33 | 13.88 | 20.0 | dragon | 38.64.138.135 |
| 75.0 | trojan | 303.6 | 671.7 | 20.75 | 0.0 | 5.88 | 14.01 | 20.0 | dragon | 216.152.156.42 |
| 74.5 | trojan | 313.6 | 664.3 | 20.52 | 0.0 | 5.78 | 14.01 | 20.0 | dragon | 216.152.156.65 |
| 74.24 | trojan | 305.7 | 617.7 | 20.7 | 0.0 | 5.76 | 14.01 | 20.0 | dragon | 66.163.112.147 |
| 74.2 | hysteria2 | 284.3 | 703.9 | 21.2 | 0.0 | 0.0 | 14.0 | 20.0 | dragon | 206.189.229.48 |
| 74.16 | trojan | 307.2 | 605.8 | 20.67 | 0.0 | 5.87 | 14.01 | 20.0 | dragon | 66.163.112.31 |
| 74.1 | trojan | 304.5 | 601.8 | 20.73 | 0.0 | 5.55 | 14.01 | 20.0 | dragon | 66.163.112.121 |
| 73.79 | trojan | 294.2 | 566.9 | 20.97 | 0.0 | 5.78 | 14.01 | 20.0 | dragon | 216.106.186.82 |
| 73.63 | trojan | 321.2 | 699.6 | 20.34 | 0.0 | 5.92 | 14.01 | 20.0 | dragon | 216.152.156.81 |
| 73.41 | trojan | 294.7 | 699.1 | 20.96 | 0.0 | 5.94 | 14.01 | 20.0 | dragon | 216.152.147.201 |
| 73.36 | trojan | 306.3 | 581.8 | 20.69 | 0.0 | 5.73 | 14.01 | 20.0 | dragon | 167.88.61.85 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.946 | 129 | 44243 | prefer |
| ermaozi | 0.957 | 0.964 | 28 | 594 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 13793 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4998 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2737 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11327 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8675 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6119 | observe |
| barry-far-vless | 0.255 | None | 0 | 6543 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4582 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |
| test_one_timeout | 15.0s | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 61 | 60 | - |
| global | False | 63 | 60 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
