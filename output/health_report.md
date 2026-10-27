# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-27 11:53:59 |
| 运行耗时 | 379.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 141936 |
| 去重后节点 | 59339 |
| TCP 可达 | 3000 |
| 真实可用 | 99 |
| Verified 输出 | 99 |
| Global 输出 | 99 |
| All 输出 | 59339 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.5 |
| tcp | 213.6 |
| probe | 70.5 |
| real_test | 45.6 |
| china_check | 24.9 |
| write_verified | 0.0 |
| generate | 18.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 84838 |
| vmess | 21861 |
| shadowsocks | 16637 |
| trojan | 15636 |
| hysteria2 | 2130 |
| http | 324 |
| shadowsocksr | 261 |
| socks | 145 |
| hysteria | 49 |
| anytls | 41 |
| tuic | 14 |

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
| 74.23 | hysteria2 | 221.1 | 601.0 | 22.66 | 0.0 | 0.0 | 13.33 | 19.24 | dragon | 66.94.121.46 |
| 73.82 | trojan | 334.1 | 347.6 | 20.04 | 1.97 | 9.54 | 13.47 | 19.24 | dragon | 45.32.52.173 |
| 73.66 | http | 243.2 | 579.9 | 22.15 | 0.0 | 0.0 | 14.41 | 19.7 | ermaozi | 44.248.167.117 |
| 71.47 | hysteria2 | 224.6 | 229.6 | 22.58 | 6.39 | 0.0 | 13.33 | 19.24 | dragon | 8.209.247.109 |
| 69.21 | trojan | 333.6 | 681.0 | 20.06 | 0.0 | 6.2 | 13.47 | 19.24 | dragon | 66.23.203.21 |
| 69.05 | http | 302.2 | 680.2 | 20.78 | 0.0 | 0.0 | 14.41 | 19.7 | ermaozi | 38.95.111.226 |
| 67.67 | http | 305.3 | 703.4 | 20.71 | 0.0 | 0.0 | 14.41 | 19.7 | ermaozi | 167.88.60.242 |
| 66.23 | trojan | 506.3 | 518.0 | 16.06 | 0.0 | 8.89 | 13.47 | 19.24 | dragon | 139.180.146.200 |
| 65.84 | trojan | 592.6 | 1103.1 | 14.06 | 0.0 | 8.29 | 13.47 | 19.24 | dragon | 45.149.147.213 |
| 65.64 | trojan | 646.1 | 1001.4 | 12.82 | 0.0 | 9.73 | 13.47 | 19.24 | dragon | 104.18.37.228 |
| 65.4 | trojan | 683.6 | 1069.0 | 11.95 | 0.0 | 10.0 | 13.47 | 19.24 | dragon | 45.130.125.75 |
| 65.09 | http | 379.9 | 784.6 | 18.98 | 0.0 | 0.0 | 14.41 | 19.7 | ermaozi | 38.247.141.135 |
| 64.8 | trojan | 666.8 | 988.1 | 12.34 | 0.0 | 10.0 | 13.47 | 19.24 | dragon | 104.16.72.50 |
| 64.7 | trojan | 668.4 | 1644.1 | 12.31 | 0.0 | 8.38 | 13.47 | 19.24 | dragon | 155.138.138.2 |
| 63.97 | http | 437.2 | 989.9 | 17.66 | 0.0 | 0.0 | 14.41 | 19.7 | ermaozi | 64.98.50.100 |
| 63.93 | trojan | 734.0 | 1192.3 | 10.79 | 0.0 | 9.94 | 13.47 | 19.24 | dragon | 172.66.40.99 |
| 63.76 | trojan | 565.4 | 1295.9 | 14.69 | 0.0 | 5.08 | 13.47 | 19.24 | dragon | 69.164.240.85 |
| 63.67 | trojan | 671.5 | 885.4 | 12.23 | 0.0 | 9.12 | 13.47 | 19.24 | dragon | 162.159.244.91 |
| 63.1 | trojan | 725.5 | 1015.8 | 10.98 | 0.0 | 9.11 | 13.47 | 19.24 | dragon | 89.150.34.41 |
| 62.75 | trojan | 738.5 | 1133.6 | 10.68 | 0.0 | 9.95 | 13.47 | 19.24 | dragon | 104.18.45.38 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.979 | 0.965 | 86 | 603 | prefer |
| dragon | 0.802 | 0.727 | 77 | 45531 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4988 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3052 | observe |
| Epodonios-all | 0.255 | None | 0 | 7509 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10244 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7059 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5319 | observe |
| barry-far-vless | 0.255 | None | 0 | 5497 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4573 | observe |
| mheidari-all | 0.255 | None | 0 | 24516 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.246 | None | 0 | 1774 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 15 |
| 204 | TimeoutError | - | 4 |
| cn-block | TimeoutError | - | 2 |
| 204 | ProxyError | - | 1 |
| speed | ClientOSError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 106 | 99 | - |
| global | False | 106 | 99 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
