# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-25 20:39:30 |
| 运行耗时 | 408.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 144306 |
| 去重后节点 | 59799 |
| TCP 可达 | 3000 |
| 真实可用 | 92 |
| Verified 输出 | 92 |
| Global 输出 | 92 |
| All 输出 | 59799 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.5 |
| tcp | 200.2 |
| probe | 107.4 |
| real_test | 45.6 |
| china_check | 31.9 |
| write_verified | 0.0 |
| generate | 17.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 87286 |
| vmess | 21477 |
| shadowsocks | 17477 |
| trojan | 15084 |
| hysteria2 | 2019 |
| shadowsocksr | 275 |
| http | 253 |
| tuic | 235 |
| socks | 116 |
| hysteria | 48 |
| anytls | 36 |

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
| 77.38 | shadowsocks | 240.0 | 624.3 | 22.22 | 0.0 | 9.94 | 13.37 | 18.82 | dragon | 156.146.38.168 |
| 74.97 | shadowsocks | 247.1 | 615.8 | 22.06 | 0.0 | 9.94 | 13.37 | 18.82 | dragon | 156.146.38.167 |
| 74.61 | shadowsocks | 315.2 | 769.6 | 20.48 | 0.0 | 7.07 | 13.37 | 18.82 | dragon | 216.9.225.189 |
| 70.56 | shadowsocks | 233.8 | 618.6 | 22.37 | 0.0 | 0.0 | 13.37 | 18.82 | dragon | 156.146.38.170 |
| 68.54 | shadowsocks | 291.0 | 694.0 | 21.04 | 0.0 | 0.0 | 13.37 | 18.82 | dragon | 37.19.198.243 |
| 68.22 | shadowsocks | 303.7 | 724.1 | 20.75 | 0.0 | 0.0 | 13.37 | 18.82 | dragon | 37.19.198.160 |
| 67.57 | shadowsocks | 306.9 | 760.9 | 20.67 | 0.0 | 0.0 | 13.37 | 18.82 | dragon | 37.19.198.236 |
| 66.74 | shadowsocks | 293.8 | 689.0 | 20.98 | 0.0 | 0.0 | 13.37 | 18.82 | dragon | 185.230.230.18 |
| 66.03 | shadowsocks | 291.1 | 701.0 | 21.04 | 0.0 | 0.0 | 13.37 | 18.82 | dragon | 37.19.198.244 |
| 65.06 | shadowsocks | 383.2 | 944.1 | 18.91 | 0.0 | 0.0 | 13.37 | 18.82 | dragon | 45.86.51.18 |
| 64.76 | shadowsocks | 307.6 | 618.8 | 20.66 | 0.0 | 0.0 | 13.37 | 18.82 | dragon | 173.244.56.9 |
| 63.01 | shadowsocks | 390.8 | 936.7 | 18.73 | 0.0 | 0.0 | 13.37 | 18.82 | dragon | 193.151.160.18 |
| 62.69 | trojan | 634.7 | 1126.8 | 13.09 | 0.0 | 10.0 | 10.0 | 18.82 | dragon | 172.64.150.28 |
| 61.88 | trojan | 659.1 | 1078.1 | 12.52 | 0.0 | 9.68 | 10.0 | 18.82 | dragon | 104.19.64.105 |
| 61.83 | hysteria2 | 426.1 | 871.7 | 17.91 | 0.0 | 5.88 | 12.0 | 18.82 | dragon | starlink-ft.251313.xyz |
| 61.4 | trojan | 644.8 | 1007.3 | 12.85 | 0.0 | 8.61 | 10.0 | 18.82 | dragon | 45.130.125.75 |
| 61.24 | trojan | 507.1 | 1228.6 | 16.04 | 0.0 | 7.96 | 10.0 | 18.82 | dragon | 69.164.240.85 |
| 60.75 | trojan | 638.9 | 1078.3 | 12.99 | 0.0 | 8.06 | 10.0 | 18.82 | dragon | 212.183.88.136 |
| 60.59 | shadowsocks | 672.6 | 1227.7 | 12.21 | 0.0 | 8.62 | 13.37 | 18.82 | dragon | 202.50.253.36 |
| 60.41 | hysteria2 | 448.9 | 709.3 | 17.39 | 0.0 | 0.0 | 12.0 | 18.82 | dragon | 62.210.124.146 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | 1.0 | 51 | 575 | prefer |
| dragon | 0.964 | 0.888 | 205 | 45637 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3849 | observe |
| Epodonios-all | 0.255 | None | 0 | 7913 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10415 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7442 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5721 | observe |
| barry-far-vless | 0.255 | None | 0 | 5934 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4177 | observe |
| mheidari-all | 0.255 | None | 0 | 24713 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.243 | None | 0 | 1702 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 19 |
| 204 | ClientOSError | - | 1 |
| geo | TimeoutError | - | 1 |
| speed | TimeoutError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 63 | 92 | - |
| global | False | 63 | 92 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
