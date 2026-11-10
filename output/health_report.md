# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-10 14:39:14 |
| 运行耗时 | 430.6s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 127000 |
| 去重后节点 | 59063 |
| TCP 可达 | 3000 |
| 真实可用 | 77 |
| Verified 输出 | 77 |
| Global 输出 | 78 |
| All 输出 | 59063 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.6 |
| geo | 1.7 |
| tcp | 204.7 |
| probe | 107.1 |
| real_test | 45.7 |
| china_check | 32.1 |
| write_verified | 0.0 |
| generate | 30.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 78340 |
| vmess | 18232 |
| trojan | 14584 |
| shadowsocks | 12701 |
| hysteria2 | 2261 |
| shadowsocksr | 383 |
| http | 279 |
| socks | 76 |
| hysteria | 65 |
| tuic | 47 |
| anytls | 32 |

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
| 84.62 | trojan | 178.5 | 477.2 | 23.65 | 0.0 | 10.0 | 13.53 | 19.94 | dragon | 167.88.61.20 |
| 83.89 | trojan | 180.9 | 492.6 | 23.59 | 0.0 | 10.0 | 13.53 | 19.94 | dragon | 167.88.61.193 |
| 83.5 | trojan | 183.4 | 480.1 | 23.53 | 0.0 | 10.0 | 13.53 | 19.94 | dragon | 167.88.61.85 |
| 81.32 | trojan | 175.5 | 460.3 | 23.71 | 0.0 | 6.64 | 13.53 | 19.94 | dragon | 167.88.61.52 |
| 80.85 | trojan | 254.7 | 691.1 | 21.88 | 0.0 | 10.0 | 13.53 | 19.94 | dragon | 167.88.61.198 |
| 79.83 | trojan | 240.2 | 559.8 | 22.22 | 0.0 | 6.64 | 13.53 | 19.94 | dragon | 66.163.112.147 |
| 78.76 | shadowsocks | 226.7 | 539.3 | 22.53 | 0.0 | 10.0 | 13.89 | 19.94 | dragon | 95.215.201.18 |
| 78.69 | trojan | 239.8 | 550.5 | 22.23 | 0.0 | 6.72 | 13.53 | 19.94 | dragon | 66.163.112.31 |
| 78.2 | trojan | 242.8 | 575.0 | 22.16 | 0.0 | 6.72 | 13.53 | 19.94 | dragon | 66.163.112.13 |
| 77.36 | trojan | 298.5 | 466.8 | 20.87 | 0.0 | 10.0 | 13.53 | 19.94 | dragon | 216.106.186.33 |
| 76.44 | trojan | 334.5 | 691.9 | 20.04 | 0.0 | 10.0 | 13.53 | 19.94 | dragon | 216.152.155.59 |
| 75.91 | trojan | 349.4 | 709.6 | 19.69 | 0.0 | 9.88 | 13.53 | 19.94 | dragon | 216.152.155.158 |
| 75.64 | trojan | 366.9 | 752.4 | 19.28 | 0.0 | 9.81 | 13.53 | 19.94 | dragon | 216.152.155.23 |
| 75.29 | http | 184.7 | 484.5 | 23.5 | 0.0 | 0.0 | 14.49 | 19.8 | ermaozi | 167.88.60.242 |
| 75.02 | http | 196.5 | 507.1 | 23.23 | 0.0 | 0.0 | 14.49 | 19.8 | ermaozi | 172.64.68.89 |
| 74.71 | trojan | 368.6 | 718.2 | 19.25 | 0.0 | 10.0 | 13.53 | 19.94 | dragon | 170.101.101.112 |
| 74.68 | trojan | 344.2 | 777.5 | 19.81 | 0.0 | 10.0 | 13.53 | 19.94 | dragon | 66.23.203.21 |
| 74.68 | trojan | 375.0 | 746.0 | 19.1 | 0.0 | 9.77 | 13.53 | 19.94 | dragon | 170.101.101.131 |
| 74.6 | trojan | 238.7 | 555.0 | 22.25 | 0.0 | 6.72 | 13.53 | 19.94 | dragon | 66.163.112.121 |
| 74.54 | trojan | 239.1 | 556.1 | 22.24 | 0.0 | 6.64 | 13.53 | 19.94 | dragon | 66.163.112.76 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.968 | 0.891 | 276 | 44733 | prefer |
| ermaozi | 0.94 | 0.928 | 69 | 619 | prefer |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| mheidari-all | 0.259 | 0.333 | 3 | 14274 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4955 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2620 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11070 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8433 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6281 | observe |
| barry-far-vless | 0.255 | None | 0 | 6343 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4667 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 15 |
| 204 | ProxyError | - | 6 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 3 |
| geo | ProxyError | - | 3 |
| 204 | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 57 | 77 | - |
| global | False | 58 | 78 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
