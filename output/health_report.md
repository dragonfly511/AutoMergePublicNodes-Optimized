# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-12 00:21:08 |
| 运行耗时 | 430.2s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 127283 |
| 去重后节点 | 58593 |
| TCP 可达 | 3000 |
| 真实可用 | 78 |
| Verified 输出 | 78 |
| Global 输出 | 80 |
| All 输出 | 58593 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.8 |
| geo | 1.7 |
| tcp | 196.4 |
| probe | 104.6 |
| real_test | 55.3 |
| china_check | 32.1 |
| write_verified | 0.0 |
| generate | 31.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 79008 |
| vmess | 18734 |
| trojan | 13906 |
| shadowsocks | 12721 |
| hysteria2 | 2135 |
| http | 295 |
| shadowsocksr | 229 |
| socks | 87 |
| hysteria | 68 |
| tuic | 64 |
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
| 78.76 | trojan | 175.0 | 476.8 | 23.73 | 0.0 | 9.14 | 10.25 | 18.14 | dragon | 216.106.186.46 |
| 78.74 | trojan | 176.4 | 479.6 | 23.69 | 0.0 | 9.16 | 10.25 | 18.14 | dragon | 216.106.186.82 |
| 78.66 | trojan | 179.9 | 489.8 | 23.61 | 0.0 | 9.16 | 10.25 | 18.14 | dragon | 216.106.186.66 |
| 76.79 | hysteria2 | 225.9 | 511.0 | 22.55 | 0.0 | 6.1 | 11.0 | 18.14 | dragon | 67.216.207.144 |
| 76.01 | trojan | 247.0 | 492.6 | 22.06 | 0.0 | 8.98 | 10.25 | 18.14 | dragon | 167.88.61.175 |
| 75.63 | trojan | 273.6 | 601.9 | 21.45 | 0.0 | 9.07 | 10.25 | 18.14 | dragon | 167.88.61.52 |
| 75.54 | trojan | 259.0 | 515.7 | 21.78 | 0.0 | 9.05 | 10.25 | 18.14 | dragon | 167.88.61.20 |
| 74.69 | trojan | 258.7 | 573.5 | 21.79 | 0.0 | 9.01 | 10.25 | 18.14 | dragon | 167.88.61.193 |
| 74.63 | trojan | 198.6 | 544.1 | 23.18 | 0.0 | 5.56 | 10.25 | 18.14 | dragon | 216.106.186.155 |
| 74.36 | shadowsocks | 240.4 | 553.7 | 22.21 | 0.0 | 7.31 | 13.2 | 18.14 | dragon | 38.145.220.193 |
| 74.32 | shadowsocks | 216.8 | 502.4 | 22.76 | 0.0 | 4.72 | 13.2 | 18.14 | dragon | 137.184.89.151 |
| 73.5 | trojan | 262.0 | 572.9 | 21.71 | 0.0 | 9.09 | 10.25 | 18.14 | dragon | 167.88.61.198 |
| 72.9 | http | 221.4 | 555.2 | 22.65 | 0.0 | 0.0 | 13.73 | 19.02 | ermaozi | 172.64.69.89 |
| 72.82 | http | 225.1 | 553.7 | 22.57 | 0.0 | 0.0 | 13.73 | 19.02 | ermaozi | 172.64.68.89 |
| 72.58 | trojan | 291.6 | 607.8 | 21.03 | 0.0 | 8.83 | 10.25 | 18.14 | dragon | 66.163.112.121 |
| 72.5 | trojan | 305.2 | 631.6 | 20.71 | 0.0 | 9.09 | 10.25 | 18.14 | dragon | 66.163.112.31 |
| 72.48 | trojan | 266.8 | 489.2 | 21.6 | 0.0 | 9.17 | 10.25 | 18.14 | dragon | 167.88.61.85 |
| 72.24 | shadowsocks | 275.0 | 633.4 | 21.41 | 0.0 | 4.92 | 13.2 | 18.14 | dragon | 169.197.142.68 |
| 72.2 | trojan | 315.4 | 754.7 | 20.48 | 0.0 | 10.0 | 10.25 | 18.14 | dragon | 66.163.114.132 |
| 72.05 | shadowsocks | 341.2 | 621.0 | 19.88 | 0.0 | 6.87 | 13.2 | 18.14 | dragon | 23.150.152.38 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.986 | 0.908 | 348 | 44265 | prefer |
| ermaozi | 0.974 | 0.961 | 77 | 608 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 14184 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4981 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2629 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11251 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8641 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6380 | observe |
| barry-far-vless | 0.255 | None | 0 | 6559 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4595 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 17 |
| speed | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| geo | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| speed | ClientOSError | - | 2 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 121 | 78 | - |
| global | False | 123 | 80 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
