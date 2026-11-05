# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-05 14:21:52 |
| 运行耗时 | 348.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 127670 |
| 去重后节点 | 58320 |
| TCP 可达 | 3000 |
| 真实可用 | 51 |
| Verified 输出 | 51 |
| Global 输出 | 51 |
| All 输出 | 58320 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.5 |
| tcp | 202.3 |
| probe | 71.5 |
| real_test | 25.0 |
| china_check | 23.7 |
| write_verified | 0.0 |
| generate | 19.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 78000 |
| vmess | 18401 |
| trojan | 14831 |
| shadowsocks | 13360 |
| hysteria2 | 2378 |
| shadowsocksr | 231 |
| http | 190 |
| socks | 120 |
| hysteria | 72 |
| tuic | 55 |
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
| 82.48 | trojan | 202.7 | 514.9 | 23.09 | 0.0 | 10.0 | 12.95 | 18.94 | dragon | 66.163.112.121 |
| 81.07 | trojan | 195.9 | 515.1 | 23.24 | 0.0 | 8.44 | 12.95 | 18.94 | dragon | 66.163.112.142 |
| 80.91 | trojan | 202.6 | 532.6 | 23.09 | 0.0 | 8.43 | 12.95 | 18.94 | dragon | 66.163.112.76 |
| 80.87 | trojan | 205.2 | 543.9 | 23.03 | 0.0 | 8.45 | 12.95 | 18.94 | dragon | 66.163.112.171 |
| 80.82 | trojan | 207.5 | 537.6 | 22.97 | 0.0 | 8.46 | 12.95 | 18.94 | dragon | 66.163.112.13 |
| 80.44 | shadowsocks | 180.4 | 480.8 | 23.6 | 0.0 | 10.0 | 12.0 | 18.94 | dragon | 38.145.220.193 |
| 79.56 | trojan | 199.1 | 528.5 | 23.17 | 0.0 | 7.0 | 12.95 | 18.94 | dragon | 66.163.112.242 |
| 78.39 | trojan | 197.3 | 515.3 | 23.21 | 0.0 | 7.79 | 12.95 | 18.94 | dragon | 66.163.112.147 |
| 78.08 | trojan | 226.9 | 596.7 | 22.53 | 0.0 | 6.16 | 12.95 | 18.94 | dragon | 66.163.112.31 |
| 77.38 | trojan | 280.9 | 634.3 | 21.28 | 0.0 | 8.25 | 12.95 | 18.94 | dragon | 66.163.114.114 |
| 77.37 | trojan | 281.8 | 636.7 | 21.25 | 0.0 | 8.2 | 12.95 | 18.94 | dragon | 66.163.114.245 |
| 76.84 | shadowsocks | 318.8 | 839.6 | 20.4 | 0.0 | 10.0 | 12.0 | 18.94 | dragon | 103.11.76.248 |
| 76.55 | trojan | 269.8 | 597.5 | 21.53 | 0.0 | 7.45 | 12.95 | 18.94 | dragon | 66.163.114.106 |
| 76.37 | trojan | 274.5 | 603.1 | 21.42 | 0.0 | 7.27 | 12.95 | 18.94 | dragon | 66.163.114.45 |
| 75.05 | trojan | 394.7 | 959.0 | 18.64 | 0.0 | 10.0 | 12.95 | 18.94 | dragon | 66.23.203.21 |
| 73.45 | trojan | 386.0 | 811.0 | 18.84 | 0.0 | 9.88 | 12.95 | 18.94 | dragon | 216.152.156.81 |
| 73.19 | trojan | 366.6 | 829.3 | 19.29 | 0.0 | 8.1 | 12.95 | 18.94 | dragon | 216.238.80.100 |
| 72.73 | trojan | 280.0 | 629.9 | 21.3 | 0.0 | 8.21 | 12.95 | 18.94 | dragon | 216.106.186.82 |
| 72.0 | trojan | 371.6 | 588.0 | 19.18 | 0.0 | 8.04 | 12.95 | 18.94 | dragon | 216.152.155.131 |
| 71.53 | trojan | 379.3 | 664.5 | 19.0 | 0.0 | 7.98 | 12.95 | 18.94 | dragon | 216.152.155.23 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.884 | 0.811 | 90 | 44959 | prefer |
| ermaozi | 0.864 | 0.87 | 23 | 593 | prefer |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 8706 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5039 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2653 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10862 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6147 | observe |
| barry-far-vless | 0.255 | None | 0 | 6241 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4612 | observe |
| mheidari-all | 0.255 | None | 0 | 14729 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 9 |
| test_one_timeout | 15.0s | - | 5 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 40 | 51 | - |
| global | False | 40 | 51 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
