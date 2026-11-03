# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-03 00:50:11 |
| 运行耗时 | 401.5s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 126970 |
| 去重后节点 | 58398 |
| TCP 可达 | 3000 |
| 真实可用 | 59 |
| Verified 输出 | 59 |
| Global 输出 | 61 |
| All 输出 | 58398 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.6 |
| tcp | 193.4 |
| probe | 100.2 |
| real_test | 47.7 |
| china_check | 34.8 |
| write_verified | 0.0 |
| generate | 18.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77416 |
| vmess | 18091 |
| trojan | 15723 |
| shadowsocks | 12938 |
| hysteria2 | 2163 |
| shadowsocksr | 240 |
| socks | 126 |
| http | 99 |
| hysteria | 62 |
| tuic | 59 |
| anytls | 53 |

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
| 76.39 | hysteria2 | 272.8 | 704.3 | 21.46 | 0.0 | 5.18 | 13.33 | 17.42 | dragon | 88.216.195.188 |
| 75.96 | trojan | 300.4 | 692.8 | 20.82 | 0.0 | 8.9 | 12.46 | 17.42 | dragon | 216.152.156.81 |
| 75.9 | hysteria2 | 261.2 | 594.5 | 21.73 | 0.0 | 4.84 | 13.33 | 17.42 | dragon | 66.94.121.46 |
| 75.52 | hysteria2 | 283.8 | 723.1 | 21.21 | 0.0 | 5.06 | 13.33 | 17.42 | dragon | 129.213.91.185 |
| 75.04 | trojan | 251.1 | 641.6 | 21.96 | 0.0 | 5.7 | 12.46 | 17.42 | dragon | 216.152.155.59 |
| 74.88 | trojan | 258.7 | 625.6 | 21.79 | 0.0 | 5.71 | 12.46 | 17.42 | dragon | 216.152.155.131 |
| 74.85 | trojan | 257.8 | 602.0 | 21.81 | 0.0 | 5.81 | 12.46 | 17.42 | dragon | 66.163.114.126 |
| 74.7 | trojan | 274.6 | 643.8 | 21.42 | 0.0 | 5.9 | 12.46 | 17.42 | dragon | 216.152.155.176 |
| 74.44 | trojan | 259.8 | 607.1 | 21.76 | 0.0 | 5.73 | 12.46 | 17.42 | dragon | 66.163.114.166 |
| 73.9 | trojan | 305.8 | 695.8 | 20.7 | 0.0 | 5.82 | 12.46 | 17.42 | dragon | 170.101.101.67 |
| 73.6 | shadowsocks | 238.8 | 612.5 | 22.25 | 0.0 | 5.07 | 12.86 | 17.42 | dragon | 156.146.38.170 |
| 73.4 | shadowsocks | 331.4 | 703.8 | 20.11 | 0.0 | 8.96 | 12.86 | 17.42 | dragon | 45.86.51.18 |
| 73.04 | trojan | 257.5 | 611.7 | 21.82 | 0.0 | 5.84 | 12.46 | 17.42 | dragon | 216.152.155.54 |
| 72.92 | trojan | 256.2 | 574.3 | 21.85 | 0.0 | 5.69 | 12.46 | 17.42 | dragon | 66.163.114.245 |
| 72.51 | trojan | 256.3 | 586.0 | 21.84 | 0.0 | 5.65 | 12.46 | 17.42 | dragon | 66.163.114.132 |
| 72.33 | shadowsocks | 292.9 | 739.9 | 21.0 | 0.0 | 5.05 | 12.86 | 17.42 | dragon | 156.146.38.167 |
| 72.29 | trojan | 304.1 | 712.9 | 20.74 | 0.0 | 5.66 | 12.46 | 17.42 | dragon | 216.152.156.65 |
| 72.11 | shadowsocks | 259.3 | 645.5 | 21.78 | 0.0 | 5.05 | 12.86 | 17.42 | dragon | 156.146.38.168 |
| 71.56 | trojan | 325.7 | 729.9 | 20.24 | 0.0 | 9.03 | 12.46 | 17.42 | dragon | 66.163.122.81 |
| 71.12 | shadowsocks | 281.4 | 668.8 | 21.26 | 0.0 | 4.95 | 12.86 | 17.42 | dragon | 185.215.132.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.953 | 0.876 | 322 | 45127 | prefer |
| zhangkai | 0.809 | 0.941 | 17 | 43 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 14971 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 139 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4941 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2726 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10707 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8355 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5917 | observe |
| barry-far-vless | 0.255 | None | 0 | 6131 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4734 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 26 |
| 204 | ProxyError | - | 6 |
| 204 | ClientOSError | - | 4 |
| 204 | TimeoutError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| geo | ClientOSError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 30 | 59 | - |
| global | False | 30 | 61 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
