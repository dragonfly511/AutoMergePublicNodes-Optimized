# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-15 13:44:36 |
| 运行耗时 | 324.1s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 128342 |
| 去重后节点 | 59201 |
| TCP 可达 | 3000 |
| 真实可用 | 66 |
| Verified 输出 | 66 |
| Global 输出 | 67 |
| All 输出 | 59201 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.5 |
| tcp | 150.8 |
| probe | 76.3 |
| real_test | 44.8 |
| china_check | 25.9 |
| write_verified | 0.0 |
| generate | 19.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77717 |
| vmess | 18992 |
| trojan | 14662 |
| shadowsocks | 13770 |
| hysteria2 | 2196 |
| shadowsocksr | 381 |
| tuic | 266 |
| http | 140 |
| socks | 114 |
| hysteria | 74 |
| anytls | 30 |

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
| 81.77 | trojan | 260.8 | 658.3 | 21.74 | 0.0 | 10.0 | 12.71 | 19.82 | dragon | 66.163.122.113 |
| 80.12 | shadowsocks | 285.5 | 774.1 | 21.17 | 0.0 | 9.59 | 14.04 | 19.82 | dragon | 15.204.246.132 |
| 79.78 | trojan | 296.1 | 685.7 | 20.92 | 0.0 | 9.31 | 12.71 | 19.82 | dragon | 170.101.101.112 |
| 79.64 | shadowsocks | 271.6 | 637.3 | 21.49 | 0.0 | 9.31 | 14.04 | 19.82 | dragon | 156.146.38.170 |
| 77.31 | trojan | 294.3 | 673.5 | 20.97 | 0.0 | 9.03 | 12.71 | 19.82 | dragon | 216.152.156.42 |
| 76.3 | trojan | 321.3 | 693.4 | 20.34 | 0.0 | 10.0 | 12.71 | 19.82 | dragon | 216.152.156.81 |
| 76.29 | trojan | 310.6 | 693.6 | 20.59 | 0.0 | 10.0 | 12.71 | 19.82 | dragon | 216.152.156.49 |
| 75.83 | shadowsocks | 427.1 | 1030.3 | 17.89 | 0.0 | 8.58 | 14.04 | 19.82 | dragon | 15.204.246.107 |
| 75.24 | shadowsocks | 291.4 | 576.3 | 21.03 | 0.0 | 9.31 | 14.04 | 19.82 | dragon | 38.145.220.193 |
| 74.93 | shadowsocks | 299.1 | 595.2 | 20.85 | 0.0 | 9.33 | 14.04 | 19.82 | dragon | 23.150.152.38 |
| 74.88 | trojan | 309.1 | 734.3 | 20.62 | 0.0 | 9.35 | 12.71 | 19.82 | dragon | 169.197.140.214 |
| 74.8 | trojan | 327.9 | 661.3 | 20.19 | 0.0 | 8.96 | 12.71 | 19.82 | dragon | 66.163.114.114 |
| 74.8 | trojan | 328.2 | 655.5 | 20.18 | 0.0 | 9.05 | 12.71 | 19.82 | dragon | 66.163.114.45 |
| 74.34 | trojan | 281.8 | 665.4 | 21.25 | 0.0 | 10.0 | 12.71 | 19.82 | dragon | 170.101.101.53 |
| 74.23 | trojan | 327.2 | 630.5 | 20.2 | 0.0 | 8.95 | 12.71 | 19.82 | dragon | 66.163.112.13 |
| 74.18 | trojan | 334.6 | 634.9 | 20.03 | 0.0 | 9.22 | 12.71 | 19.82 | dragon | 216.106.186.155 |
| 73.41 | hysteria2 | 245.6 | 666.7 | 22.09 | 0.0 | 0.0 | 12.5 | 19.82 | dragon | 206.189.229.48 |
| 73.37 | trojan | 351.9 | 693.6 | 19.63 | 0.0 | 9.22 | 12.71 | 19.82 | dragon | 216.106.186.46 |
| 73.18 | trojan | 384.5 | 567.3 | 18.88 | 0.0 | 10.0 | 12.71 | 19.82 | dragon | 216.106.186.33 |
| 73.08 | trojan | 321.4 | 637.4 | 20.34 | 0.0 | 8.95 | 12.71 | 19.82 | dragon | 66.163.114.126 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.935 | 0.952 | 21 | 544 | prefer |
| dragon | 0.915 | 0.837 | 264 | 44363 | prefer |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4916 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3024 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11628 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8859 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6129 | observe |
| barry-far-vless | 0.255 | None | 0 | 6500 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4584 | observe |
| mheidari-all | 0.255 | None | 0 | 14652 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 20 |
| 204 | ProxyError | - | 16 |
| 204 | TimeoutError | - | 2 |
| speed | TimeoutError | - | 2 |
| cn-block | TimeoutError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 84 | 66 | - |
| global | False | 84 | 67 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
