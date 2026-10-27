# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-27 17:48:56 |
| 运行耗时 | 441.2s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 142021 |
| 去重后节点 | 59416 |
| TCP 可达 | 3000 |
| 真实可用 | 62 |
| Verified 输出 | 62 |
| Global 输出 | 63 |
| All 输出 | 59416 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| geo | 1.7 |
| tcp | 200.7 |
| probe | 126.7 |
| real_test | 52.5 |
| china_check | 21.0 |
| write_verified | 0.0 |
| generate | 29.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 85363 |
| vmess | 21582 |
| shadowsocks | 16637 |
| trojan | 15644 |
| hysteria2 | 2112 |
| shadowsocksr | 256 |
| http | 183 |
| socks | 141 |
| hysteria | 48 |
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
| 73.94 | trojan | 306.0 | 800.3 | 20.69 | 0.0 | 10.0 | 9.71 | 16.04 | dragon | 155.138.138.2 |
| 65.98 | shadowsocks | 274.0 | 765.3 | 21.44 | 0.0 | 0.0 | 12.5 | 16.04 | dragon | 37.19.198.160 |
| 65.94 | shadowsocks | 254.1 | 662.5 | 21.9 | 0.0 | 0.0 | 12.5 | 16.04 | dragon | 193.151.163.18 |
| 65.71 | trojan | 375.2 | 658.1 | 19.09 | 0.0 | 9.33 | 9.71 | 16.04 | dragon | 216.106.186.32 |
| 65.12 | hysteria2 | 234.7 | 659.9 | 22.34 | 0.0 | 0.0 | 13.24 | 16.04 | dragon | 129.213.91.185 |
| 64.97 | shadowsocks | 295.6 | 831.7 | 20.93 | 0.0 | 0.0 | 12.5 | 16.04 | dragon | 185.230.230.18 |
| 64.81 | shadowsocks | 324.3 | 885.1 | 20.27 | 0.0 | 0.0 | 12.5 | 16.04 | dragon | 216.9.225.189 |
| 64.73 | shadowsocks | 306.4 | 864.9 | 20.69 | 0.0 | 0.0 | 12.5 | 16.04 | dragon | 45.86.51.18 |
| 64.54 | trojan | 452.7 | 948.6 | 17.3 | 0.0 | 9.09 | 9.71 | 16.04 | dragon | 45.149.147.213 |
| 63.72 | trojan | 412.9 | 1016.6 | 18.22 | 0.0 | 6.24 | 9.71 | 16.04 | dragon | 66.23.203.21 |
| 63.56 | shadowsocks | 355.4 | 897.0 | 19.55 | 0.0 | 0.0 | 12.5 | 16.04 | dragon | 193.151.160.9 |
| 63.48 | http | 372.7 | 701.6 | 19.15 | 0.0 | 0.0 | 14.32 | 19.58 | ermaozi | 38.247.141.135 |
| 63.34 | shadowsocks | 466.7 | 915.0 | 16.98 | 0.0 | 9.34 | 12.5 | 16.04 | dragon | 82.38.31.62 |
| 63.27 | shadowsocks | 293.7 | 678.6 | 20.98 | 0.0 | 0.0 | 12.5 | 16.04 | dragon | 156.146.38.170 |
| 62.73 | http | 375.0 | 701.6 | 19.1 | 0.0 | 0.0 | 14.32 | 19.58 | ermaozi | 64.98.50.100 |
| 62.67 | hysteria2 | 328.8 | 305.8 | 20.17 | 3.53 | 0.0 | 13.24 | 16.04 | dragon | 8.209.247.109 |
| 62.5 | shadowsocks | 382.0 | 990.0 | 18.94 | 0.0 | 0.0 | 12.5 | 16.04 | dragon | 193.151.160.18 |
| 62.15 | http | 434.8 | 706.4 | 17.71 | 0.0 | 0.0 | 14.32 | 19.58 | ermaozi | 44.248.167.117 |
| 61.94 | shadowsocks | 382.5 | 565.2 | 18.92 | 0.0 | 9.83 | 12.5 | 16.04 | dragon | 107.172.219.230 |
| 61.48 | hysteria2 | 366.4 | 694.5 | 19.3 | 0.0 | 0.0 | 13.24 | 16.04 | dragon | 62.210.124.146 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.952 | 0.963 | 27 | 535 | prefer |
| dragon | 0.871 | 0.794 | 204 | 45531 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4988 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3052 | observe |
| Epodonios-all | 0.255 | None | 0 | 7531 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10393 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7059 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5319 | observe |
| barry-far-vless | 0.255 | None | 0 | 5532 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4573 | observe |
| mheidari-all | 0.255 | None | 0 | 24511 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1757 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 28 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| geo | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 99 | 62 | - |
| global | False | 99 | 63 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
