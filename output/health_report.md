# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-14 22:13:00 |
| 运行耗时 | 418.4s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 127380 |
| 去重后节点 | 58604 |
| TCP 可达 | 3000 |
| 真实可用 | 54 |
| Verified 输出 | 54 |
| Global 输出 | 55 |
| All 输出 | 58604 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.5 |
| geo | 1.7 |
| tcp | 187.3 |
| probe | 107.3 |
| real_test | 50.3 |
| china_check | 32.7 |
| write_verified | 0.0 |
| generate | 30.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77272 |
| vmess | 18812 |
| trojan | 14491 |
| shadowsocks | 13569 |
| hysteria2 | 2175 |
| shadowsocksr | 381 |
| tuic | 267 |
| http | 183 |
| socks | 124 |
| hysteria | 58 |
| anytls | 48 |

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
| 78.89 | trojan | 257.9 | 632.6 | 21.81 | 0.0 | 9.78 | 10.56 | 19.24 | dragon | 216.152.155.54 |
| 78.53 | trojan | 267.4 | 634.8 | 21.59 | 0.0 | 10.0 | 10.56 | 19.24 | dragon | 216.152.155.131 |
| 77.96 | trojan | 307.7 | 601.7 | 20.66 | 0.0 | 10.0 | 10.56 | 19.24 | dragon | 216.152.155.158 |
| 77.91 | trojan | 309.4 | 591.7 | 20.62 | 0.0 | 9.99 | 10.56 | 19.24 | dragon | 170.101.101.53 |
| 77.36 | trojan | 323.5 | 798.8 | 20.29 | 0.0 | 9.77 | 10.56 | 19.24 | dragon | 216.152.155.50 |
| 76.54 | trojan | 273.6 | 661.4 | 21.45 | 0.0 | 7.79 | 10.56 | 19.24 | dragon | 170.101.101.112 |
| 76.43 | trojan | 295.1 | 591.9 | 20.95 | 0.0 | 10.0 | 10.56 | 19.24 | dragon | 216.152.155.23 |
| 75.55 | trojan | 325.2 | 807.4 | 20.25 | 0.0 | 10.0 | 10.56 | 19.24 | dragon | 66.163.122.113 |
| 75.36 | trojan | 309.2 | 728.3 | 20.62 | 0.0 | 9.66 | 10.56 | 19.24 | dragon | 169.197.140.218 |
| 74.62 | shadowsocks | 312.4 | 849.9 | 20.55 | 0.0 | 8.84 | 13.81 | 19.24 | dragon | 15.204.246.132 |
| 74.37 | hysteria2 | 246.5 | 685.8 | 22.07 | 0.0 | 0.0 | 14.06 | 19.24 | dragon | 206.189.229.48 |
| 74.13 | trojan | 419.6 | 1054.9 | 18.07 | 0.0 | 10.0 | 10.56 | 19.24 | dragon | 169.197.140.245 |
| 73.6 | trojan | 310.8 | 734.0 | 20.58 | 0.0 | 7.77 | 10.56 | 19.24 | dragon | 169.197.140.208 |
| 73.52 | trojan | 337.6 | 610.7 | 19.96 | 0.0 | 9.67 | 10.56 | 19.24 | dragon | 66.163.114.114 |
| 73.32 | trojan | 320.8 | 691.0 | 20.35 | 0.0 | 9.69 | 10.56 | 19.24 | dragon | 216.152.156.49 |
| 73.31 | shadowsocks | 364.2 | 753.5 | 19.35 | 0.0 | 8.45 | 13.81 | 19.24 | dragon | 156.146.38.170 |
| 72.88 | trojan | 328.2 | 717.6 | 20.18 | 0.0 | 9.71 | 10.56 | 19.24 | dragon | 216.152.156.42 |
| 72.44 | trojan | 311.5 | 733.8 | 20.57 | 0.0 | 10.0 | 10.56 | 19.24 | dragon | 169.197.140.169 |
| 72.22 | trojan | 338.9 | 690.4 | 19.93 | 0.0 | 9.99 | 10.56 | 19.24 | dragon | 216.152.147.74 |
| 72.15 | trojan | 328.2 | 629.7 | 20.18 | 0.0 | 9.65 | 10.56 | 19.24 | dragon | 66.163.112.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.947 | 0.96 | 25 | 527 | prefer |
| dragon | 0.946 | 0.868 | 319 | 44363 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4966 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2652 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11797 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 9013 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6319 | observe |
| barry-far-vless | 0.255 | None | 0 | 6499 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4551 | observe |
| mheidari-all | 0.255 | None | 0 | 13757 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 23 |
| speed | TimeoutError | - | 7 |
| 204 | ProxyError | - | 5 |
| 204 | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | ClientOSError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 56 | 54 | - |
| global | False | 56 | 55 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
