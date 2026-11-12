# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-12 14:55:47 |
| 运行耗时 | 376.3s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 127601 |
| 去重后节点 | 58781 |
| TCP 可达 | 3000 |
| 真实可用 | 98 |
| Verified 输出 | 98 |
| Global 输出 | 99 |
| All 输出 | 58781 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.6 |
| tcp | 195.3 |
| probe | 84.9 |
| real_test | 41.5 |
| china_check | 27.4 |
| write_verified | 0.0 |
| generate | 19.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 79223 |
| vmess | 18853 |
| trojan | 14069 |
| shadowsocks | 12628 |
| hysteria2 | 2096 |
| http | 252 |
| shadowsocksr | 222 |
| socks | 91 |
| hysteria | 68 |
| tuic | 62 |
| anytls | 37 |

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
| 78.34 | trojan | 372.9 | 976.5 | 19.15 | 0.0 | 8.9 | 13.07 | 19.72 | dragon | 216.152.155.23 |
| 78.16 | trojan | 280.9 | 619.8 | 21.28 | 0.0 | 8.87 | 13.07 | 19.72 | dragon | 170.101.101.67 |
| 77.74 | trojan | 269.6 | 623.1 | 21.54 | 0.0 | 8.88 | 13.07 | 19.72 | dragon | 216.152.155.176 |
| 77.57 | trojan | 258.9 | 597.5 | 21.79 | 0.0 | 5.49 | 13.07 | 19.72 | dragon | 216.152.155.131 |
| 77.48 | shadowsocks | 241.4 | 616.1 | 22.19 | 0.0 | 5.61 | 13.96 | 19.72 | dragon | 156.146.38.167 |
| 77.35 | shadowsocks | 245.7 | 525.8 | 22.09 | 0.0 | 8.3 | 13.96 | 19.72 | dragon | 38.145.220.193 |
| 77.2 | shadowsocks | 241.2 | 622.9 | 22.19 | 0.0 | 5.33 | 13.96 | 19.72 | dragon | 156.146.38.170 |
| 77.08 | shadowsocks | 252.3 | 653.9 | 21.94 | 0.0 | 5.46 | 13.96 | 19.72 | dragon | 156.146.38.169 |
| 76.98 | trojan | 357.0 | 888.0 | 19.51 | 0.0 | 7.87 | 13.07 | 19.72 | dragon | 216.152.155.59 |
| 75.92 | trojan | 309.8 | 599.4 | 20.61 | 0.0 | 8.6 | 13.07 | 19.72 | dragon | 66.163.112.142 |
| 75.72 | trojan | 302.7 | 721.2 | 20.77 | 0.0 | 4.66 | 13.07 | 19.72 | dragon | 170.101.101.112 |
| 75.46 | hysteria2 | 387.9 | 960.9 | 18.8 | 0.0 | 6.79 | 12.95 | 19.72 | dragon | 34.24.25.1 |
| 75.29 | trojan | 297.8 | 608.6 | 20.88 | 0.0 | 8.61 | 13.07 | 19.72 | dragon | 66.163.112.31 |
| 75.22 | trojan | 295.6 | 569.5 | 20.93 | 0.0 | 8.72 | 13.07 | 19.72 | dragon | 167.88.61.175 |
| 75.14 | trojan | 298.8 | 563.7 | 20.86 | 0.0 | 8.63 | 13.07 | 19.72 | dragon | 167.88.61.52 |
| 75.14 | trojan | 301.7 | 580.1 | 20.79 | 0.0 | 8.7 | 13.07 | 19.72 | dragon | 167.88.61.20 |
| 74.97 | trojan | 293.4 | 563.9 | 20.99 | 0.0 | 8.65 | 13.07 | 19.72 | dragon | 167.88.61.85 |
| 74.95 | trojan | 303.5 | 581.1 | 20.75 | 0.0 | 8.72 | 13.07 | 19.72 | dragon | 167.88.61.193 |
| 74.93 | trojan | 308.2 | 593.3 | 20.64 | 0.0 | 8.63 | 13.07 | 19.72 | dragon | 66.163.112.171 |
| 74.76 | trojan | 327.8 | 694.3 | 20.19 | 0.0 | 8.7 | 13.07 | 19.72 | dragon | 66.163.112.242 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.934 | 0.926 | 54 | 579 | prefer |
| dragon | 0.917 | 0.84 | 281 | 44265 | prefer |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4998 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2737 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11439 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8655 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6375 | observe |
| barry-far-vless | 0.255 | None | 0 | 6555 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4618 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 20 |
| test_one_timeout | 15.0s | - | 17 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 2 |
| 204 | TimeoutError | - | 1 |
| geo | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 78 | 98 | - |
| global | False | 80 | 99 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
