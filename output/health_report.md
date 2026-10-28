# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-28 12:28:32 |
| 运行耗时 | 420.5s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 143389 |
| 去重后节点 | 59264 |
| TCP 可达 | 3000 |
| 真实可用 | 72 |
| Verified 输出 | 72 |
| Global 输出 | 75 |
| All 输出 | 59264 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.6 |
| tcp | 206.8 |
| probe | 108.0 |
| real_test | 48.7 |
| china_check | 25.4 |
| write_verified | 0.1 |
| generate | 23.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 86468 |
| vmess | 21593 |
| shadowsocks | 16545 |
| trojan | 16174 |
| hysteria2 | 1995 |
| shadowsocksr | 271 |
| http | 117 |
| socks | 98 |
| hysteria | 46 |
| tuic | 43 |
| anytls | 39 |

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
| 77.95 | shadowsocks | 236.4 | 656.0 | 22.31 | 0.0 | 7.67 | 13.41 | 19.06 | dragon | 185.230.230.18 |
| 77.8 | shadowsocks | 251.7 | 689.4 | 21.95 | 0.0 | 7.38 | 13.41 | 19.06 | dragon | 216.9.225.189 |
| 73.47 | hysteria2 | 360.7 | 259.2 | 19.43 | 5.28 | 5.72 | 12.63 | 19.06 | dragon | 8.209.247.109 |
| 72.54 | shadowsocks | 461.4 | 864.0 | 17.1 | 0.0 | 7.79 | 13.41 | 19.06 | dragon | 15.204.246.132 |
| 71.96 | shadowsocks | 407.3 | 1040.1 | 18.35 | 0.0 | 7.28 | 13.41 | 19.06 | dragon | 185.215.132.18 |
| 70.55 | shadowsocks | 246.0 | 684.1 | 22.08 | 0.0 | 0.0 | 13.41 | 19.06 | dragon | 37.19.198.236 |
| 70.54 | shadowsocks | 246.4 | 681.3 | 22.07 | 0.0 | 0.0 | 13.41 | 19.06 | dragon | 37.19.198.244 |
| 70.53 | shadowsocks | 247.0 | 686.3 | 22.06 | 0.0 | 0.0 | 13.41 | 19.06 | dragon | 37.19.198.160 |
| 70.11 | hysteria2 | 392.6 | 788.2 | 18.69 | 0.0 | 6.36 | 12.63 | 19.06 | dragon | 62.210.124.146 |
| 69.9 | shadowsocks | 252.8 | 694.7 | 21.93 | 0.0 | 0.0 | 13.41 | 19.06 | dragon | 45.86.51.18 |
| 69.07 | shadowsocks | 403.6 | 1025.6 | 18.44 | 0.0 | 3.51 | 13.41 | 19.06 | dragon | 185.215.132.9 |
| 67.71 | shadowsocks | 347.2 | 989.1 | 19.74 | 0.0 | 0.0 | 13.41 | 19.06 | dragon | 193.151.163.18 |
| 67.69 | shadowsocks | 275.3 | 637.9 | 21.4 | 0.0 | 0.0 | 13.41 | 19.06 | dragon | 156.146.38.170 |
| 67.34 | shadowsocks | 278.2 | 642.1 | 21.34 | 0.0 | 0.0 | 13.41 | 19.06 | dragon | 156.146.38.168 |
| 66.79 | trojan | 275.3 | 753.1 | 21.41 | 0.0 | 2.15 | 11.67 | 19.06 | dragon | 66.163.122.81 |
| 66.47 | shadowsocks | 413.5 | 737.8 | 18.2 | 0.0 | 6.49 | 13.41 | 19.06 | dragon | 158.173.20.208 |
| 66.42 | trojan | 302.3 | 623.5 | 20.78 | 0.0 | 2.41 | 11.67 | 19.06 | dragon | 216.152.155.23 |
| 65.77 | shadowsocks | 431.1 | 1126.2 | 17.8 | 0.0 | 0.0 | 13.41 | 19.06 | dragon | 193.151.160.9 |
| 65.62 | trojan | 265.9 | 633.1 | 21.62 | 0.0 | 1.0 | 11.67 | 19.06 | dragon | 216.152.155.59 |
| 65.44 | shadowsocks | 411.9 | 1061.5 | 18.24 | 0.0 | 0.0 | 13.41 | 19.06 | dragon | 51.222.136.236 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.924 | 0.931 | 29 | 513 | prefer |
| dragon | 0.901 | 0.824 | 205 | 45232 | prefer |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 7544 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5004 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2801 | observe |
| Epodonios-all | 0.255 | None | 0 | 8035 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10603 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5575 | observe |
| barry-far-vless | 0.255 | None | 0 | 5789 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4500 | observe |
| mheidari-all | 0.255 | None | 0 | 24702 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.246 | None | 0 | 1778 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 20 |
| 204 | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 3 |
| 204 | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| cn-block | TimeoutError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 91 | 72 | - |
| global | False | 92 | 75 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
