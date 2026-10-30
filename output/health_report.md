# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-30 05:00:27 |
| 运行耗时 | 380.6s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 144340 |
| 去重后节点 | 59354 |
| TCP 可达 | 3000 |
| 真实可用 | 70 |
| Verified 输出 | 70 |
| Global 输出 | 70 |
| All 输出 | 59354 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.5 |
| tcp | 204.6 |
| probe | 89.8 |
| real_test | 36.7 |
| china_check | 23.8 |
| write_verified | 0.0 |
| generate | 18.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 90028 |
| vmess | 18700 |
| trojan | 17507 |
| shadowsocks | 14631 |
| hysteria2 | 2851 |
| shadowsocksr | 269 |
| http | 143 |
| socks | 91 |
| tuic | 50 |
| hysteria | 40 |
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
| 79.59 | shadowsocks | 249.4 | 634.7 | 22.01 | 0.0 | 9.1 | 13.34 | 19.14 | dragon | 156.146.38.170 |
| 78.48 | shadowsocks | 253.8 | 632.4 | 21.9 | 0.0 | 9.1 | 13.34 | 19.14 | dragon | 156.146.38.167 |
| 78.09 | shadowsocks | 307.8 | 760.8 | 20.65 | 0.0 | 8.96 | 13.34 | 19.14 | dragon | 216.128.153.186 |
| 78.01 | shadowsocks | 289.6 | 698.9 | 21.07 | 0.0 | 8.89 | 13.34 | 19.14 | dragon | 37.19.198.160 |
| 77.06 | shadowsocks | 325.3 | 821.1 | 20.25 | 0.0 | 8.95 | 13.34 | 19.14 | dragon | 37.19.198.243 |
| 76.53 | shadowsocks | 333.8 | 838.0 | 20.05 | 0.0 | 8.93 | 13.34 | 19.14 | dragon | 37.19.198.244 |
| 76.38 | shadowsocks | 254.3 | 624.1 | 21.89 | 0.0 | 9.01 | 13.34 | 19.14 | dragon | 156.146.38.169 |
| 75.81 | trojan | 256.2 | 591.4 | 21.85 | 0.0 | 7.46 | 12.86 | 19.14 | dragon | 66.163.114.126 |
| 75.21 | trojan | 331.7 | 703.7 | 20.1 | 0.0 | 10.0 | 12.86 | 19.14 | dragon | 216.106.186.32 |
| 75.1 | shadowsocks | 345.6 | 866.1 | 19.78 | 0.0 | 8.84 | 13.34 | 19.14 | dragon | 185.215.132.18 |
| 74.71 | shadowsocks | 313.5 | 681.8 | 20.52 | 0.0 | 8.72 | 13.34 | 19.14 | dragon | 193.151.163.18 |
| 74.61 | shadowsocks | 249.6 | 624.2 | 22.0 | 0.0 | 9.13 | 13.34 | 19.14 | dragon | 156.146.38.168 |
| 74.55 | trojan | 299.4 | 697.9 | 20.85 | 0.0 | 9.81 | 12.86 | 19.14 | dragon | 216.152.156.65 |
| 74.35 | shadowsocks | 301.3 | 600.0 | 20.8 | 0.0 | 8.86 | 13.34 | 19.14 | dragon | 173.244.56.6 |
| 74.18 | shadowsocks | 367.4 | 888.4 | 19.27 | 0.0 | 8.97 | 13.34 | 19.14 | dragon | 185.230.230.18 |
| 72.6 | trojan | 339.1 | 708.9 | 19.93 | 0.0 | 8.56 | 12.86 | 19.14 | dragon | 216.106.186.33 |
| 72.52 | hysteria2 | 265.1 | 678.0 | 21.64 | 0.0 | 0.0 | 13.24 | 19.14 | dragon | 129.213.91.185 |
| 72.4 | shadowsocks | 402.8 | 974.4 | 18.45 | 0.0 | 8.87 | 13.34 | 19.14 | dragon | 193.151.160.9 |
| 72.24 | trojan | 258.7 | 601.2 | 21.79 | 0.0 | 8.28 | 12.86 | 19.14 | dragon | 66.163.114.45 |
| 72.21 | trojan | 356.0 | 719.0 | 19.54 | 0.0 | 10.0 | 12.86 | 19.14 | dragon | 216.238.80.100 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.99 | 0.914 | 210 | 44588 | prefer |
| ermaozi | 0.93 | 0.95 | 20 | 515 | prefer |
| Au1rxx-base64 | 0.324 | 1.0 | 1 | 1726 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2709 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10496 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7756 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5729 | observe |
| barry-far-vless | 0.255 | None | 0 | 5941 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4444 | observe |
| mheidari-all | 0.255 | None | 0 | 34034 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1726 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 13 |
| 204 | ClientOSError | - | 2 |
| 204 | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |
| geo | ClientOSError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 69 | 70 | - |
| global | False | 70 | 70 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
