# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-28 22:26:54 |
| 运行耗时 | 386.6s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 144053 |
| 去重后节点 | 59128 |
| TCP 可达 | 3000 |
| 真实可用 | 68 |
| Verified 输出 | 68 |
| Global 输出 | 69 |
| All 输出 | 59128 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.6 |
| tcp | 204.2 |
| probe | 90.5 |
| real_test | 35.3 |
| china_check | 30.3 |
| write_verified | 0.0 |
| generate | 19.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 90955 |
| vmess | 18904 |
| trojan | 16483 |
| shadowsocks | 14202 |
| hysteria2 | 2955 |
| shadowsocksr | 237 |
| http | 116 |
| socks | 91 |
| tuic | 45 |
| hysteria | 35 |
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
| 74.07 | trojan | 309.2 | 823.4 | 20.62 | 0.0 | 7.78 | 10.65 | 18.02 | dragon | 66.23.203.21 |
| 73.43 | shadowsocks | 225.2 | 604.5 | 22.56 | 0.0 | 3.62 | 13.23 | 18.02 | dragon | 156.146.38.170 |
| 73.18 | shadowsocks | 228.4 | 610.9 | 22.49 | 0.0 | 3.44 | 13.23 | 18.02 | dragon | 156.146.38.168 |
| 72.56 | shadowsocks | 273.6 | 517.1 | 21.44 | 0.0 | 7.36 | 13.23 | 18.02 | dragon | 216.105.168.18 |
| 70.36 | shadowsocks | 260.8 | 577.8 | 21.74 | 0.0 | 3.86 | 13.23 | 18.02 | dragon | 173.244.56.9 |
| 69.75 | hysteria2 | 263.3 | 259.5 | 21.68 | 5.27 | 0.0 | 12.19 | 18.02 | dragon | 8.209.247.109 |
| 69.54 | trojan | 325.3 | 656.5 | 20.25 | 0.0 | 7.68 | 10.65 | 18.02 | dragon | 216.106.186.32 |
| 68.42 | shadowsocks | 222.9 | 593.3 | 22.62 | 0.0 | 3.55 | 13.23 | 18.02 | dragon | 156.146.38.169 |
| 68.39 | shadowsocks | 224.0 | 597.3 | 22.59 | 0.0 | 3.55 | 13.23 | 18.02 | dragon | 156.146.38.167 |
| 68.34 | shadowsocks | 367.5 | 858.3 | 19.27 | 0.0 | 4.21 | 13.23 | 18.02 | dragon | 95.215.201.18 |
| 68.16 | shadowsocks | 257.7 | 578.2 | 21.81 | 0.0 | 4.05 | 13.23 | 18.02 | dragon | 173.244.56.6 |
| 68.13 | shadowsocks | 321.3 | 737.1 | 20.34 | 0.0 | 3.38 | 13.23 | 18.02 | dragon | 37.19.198.244 |
| 68.11 | shadowsocks | 319.5 | 735.0 | 20.38 | 0.0 | 3.4 | 13.23 | 18.02 | dragon | 37.19.198.236 |
| 68.01 | hysteria2 | 413.6 | 1074.3 | 18.2 | 0.0 | 3.1 | 12.19 | 18.02 | dragon | 129.213.91.185 |
| 67.75 | shadowsocks | 323.0 | 753.0 | 20.3 | 0.0 | 3.39 | 13.23 | 18.02 | dragon | 37.19.198.243 |
| 67.53 | hysteria2 | 361.8 | 628.0 | 19.4 | 0.0 | 3.12 | 12.19 | 18.02 | dragon | 66.94.121.46 |
| 66.95 | shadowsocks | 321.3 | 726.9 | 20.34 | 0.0 | 3.33 | 13.23 | 18.02 | dragon | 193.151.163.18 |
| 66.57 | shadowsocks | 393.3 | 944.3 | 18.67 | 0.0 | 3.02 | 13.23 | 18.02 | dragon | 193.151.160.18 |
| 66.55 | shadowsocks | 389.4 | 644.9 | 18.76 | 0.0 | 3.08 | 13.23 | 18.02 | dragon | 193.151.160.9 |
| 66.43 | shadowsocks | 318.5 | 713.1 | 20.4 | 0.0 | 3.41 | 13.23 | 18.02 | dragon | 185.230.230.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.994 | 0.918 | 196 | 44753 | prefer |
| ermaozi | 0.924 | 0.931 | 29 | 513 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 33849 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5004 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2801 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10359 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7686 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5749 | observe |
| barry-far-vless | 0.255 | None | 0 | 5963 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4323 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1755 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1755 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 7 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | ClientOSError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| speed | TimeoutError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: o|y | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 72 | 68 | - |
| global | False | 75 | 69 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
