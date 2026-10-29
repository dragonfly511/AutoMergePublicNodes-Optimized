# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-29 22:40:19 |
| 运行耗时 | 398.2s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 143773 |
| 去重后节点 | 59198 |
| TCP 可达 | 3000 |
| 真实可用 | 69 |
| Verified 输出 | 69 |
| Global 输出 | 70 |
| All 输出 | 59198 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.6 |
| tcp | 201.2 |
| probe | 98.3 |
| real_test | 39.9 |
| china_check | 27.5 |
| write_verified | 0.0 |
| generate | 23.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 89092 |
| vmess | 19485 |
| trojan | 17154 |
| shadowsocks | 14566 |
| hysteria2 | 2844 |
| shadowsocksr | 275 |
| http | 149 |
| socks | 90 |
| tuic | 50 |
| hysteria | 40 |
| anytls | 28 |

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
| 76.5 | shadowsocks | 240.7 | 673.4 | 22.2 | 0.0 | 8.25 | 12.29 | 17.76 | dragon | 37.19.198.243 |
| 76.45 | shadowsocks | 242.4 | 675.1 | 22.17 | 0.0 | 8.23 | 12.29 | 17.76 | dragon | 37.19.198.244 |
| 76.0 | shadowsocks | 237.9 | 661.6 | 22.27 | 0.0 | 8.18 | 12.29 | 17.76 | dragon | 185.230.230.18 |
| 75.57 | shadowsocks | 256.8 | 674.7 | 21.83 | 0.0 | 8.19 | 12.29 | 17.76 | dragon | 193.151.163.18 |
| 74.64 | shadowsocks | 296.4 | 669.3 | 20.92 | 0.0 | 8.17 | 12.29 | 17.76 | dragon | 15.204.233.41 |
| 74.56 | shadowsocks | 245.8 | 577.9 | 22.09 | 0.0 | 8.13 | 12.29 | 17.76 | dragon | 216.128.153.186 |
| 73.97 | shadowsocks | 332.5 | 688.2 | 20.08 | 0.0 | 8.34 | 12.29 | 17.76 | dragon | 193.151.160.18 |
| 73.89 | shadowsocks | 329.3 | 933.5 | 20.16 | 0.0 | 8.18 | 12.29 | 17.76 | dragon | 45.86.51.18 |
| 73.23 | trojan | 272.8 | 680.7 | 21.46 | 0.0 | 10.0 | 11.88 | 17.76 | dragon | 66.163.122.7 |
| 72.83 | shadowsocks | 286.5 | 680.1 | 21.15 | 0.0 | 8.19 | 12.29 | 17.76 | dragon | 185.215.132.9 |
| 72.42 | shadowsocks | 281.0 | 649.0 | 21.27 | 0.0 | 8.16 | 12.29 | 17.76 | dragon | 156.146.38.170 |
| 72.31 | shadowsocks | 297.5 | 729.9 | 20.89 | 0.0 | 8.21 | 12.29 | 17.76 | dragon | 193.151.160.9 |
| 71.85 | shadowsocks | 362.7 | 905.3 | 19.38 | 0.0 | 8.18 | 12.29 | 17.76 | dragon | 185.215.132.18 |
| 71.77 | shadowsocks | 245.5 | 684.7 | 22.09 | 0.0 | 3.63 | 12.29 | 17.76 | dragon | 37.19.198.236 |
| 71.44 | shadowsocks | 284.8 | 658.2 | 21.18 | 0.0 | 8.14 | 12.29 | 17.76 | dragon | 156.146.38.167 |
| 71.12 | trojan | 298.6 | 676.8 | 20.86 | 0.0 | 10.0 | 11.88 | 17.76 | dragon | 216.152.156.65 |
| 70.71 | hysteria2 | 230.0 | 645.2 | 22.45 | 0.0 | 0.0 | 12.0 | 17.76 | dragon | 129.213.91.185 |
| 69.65 | trojan | 352.3 | 680.8 | 19.62 | 0.0 | 9.81 | 11.88 | 17.76 | dragon | 216.106.186.32 |
| 69.65 | trojan | 486.1 | 1217.0 | 16.53 | 0.0 | 10.0 | 11.88 | 17.76 | dragon | 66.23.203.21 |
| 69.53 | shadowsocks | 315.5 | 612.8 | 20.47 | 0.0 | 8.27 | 12.29 | 17.76 | dragon | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.977 | 1.0 | 21 | 510 | prefer |
| dragon | 0.957 | 0.881 | 218 | 44588 | prefer |
| Au1rxx-base64 | 0.324 | 1.0 | 1 | 1725 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2709 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10379 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7758 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5789 | observe |
| barry-far-vless | 0.255 | None | 0 | 6033 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4444 | observe |
| mheidari-all | 0.255 | None | 0 | 33474 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1725 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 18 |
| 204 | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 37 | 69 | - |
| global | False | 40 | 70 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
