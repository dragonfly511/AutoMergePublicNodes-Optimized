# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-10 23:04:18 |
| 运行耗时 | 403.5s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 127671 |
| 去重后节点 | 59499 |
| TCP 可达 | 3000 |
| 真实可用 | 64 |
| Verified 输出 | 64 |
| Global 输出 | 66 |
| All 输出 | 59499 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.6 |
| tcp | 204.9 |
| probe | 81.5 |
| real_test | 58.7 |
| china_check | 32.4 |
| write_verified | 0.0 |
| generate | 19.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 79023 |
| vmess | 18039 |
| trojan | 14854 |
| shadowsocks | 12859 |
| hysteria2 | 2169 |
| shadowsocksr | 267 |
| http | 262 |
| socks | 94 |
| anytls | 39 |
| hysteria | 38 |
| tuic | 27 |

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
| 81.12 | shadowsocks | 232.4 | 546.7 | 22.4 | 0.0 | 9.93 | 13.74 | 19.36 | dragon | 38.145.220.193 |
| 79.27 | trojan | 261.8 | 580.5 | 21.72 | 0.0 | 10.0 | 12.05 | 19.36 | dragon | 66.163.112.147 |
| 79.11 | trojan | 262.3 | 605.0 | 21.71 | 0.0 | 9.35 | 12.05 | 19.36 | dragon | 66.163.114.106 |
| 78.73 | trojan | 257.3 | 587.3 | 21.82 | 0.0 | 10.0 | 12.05 | 19.36 | dragon | 66.163.114.45 |
| 78.39 | hysteria2 | 269.5 | 577.8 | 21.54 | 0.0 | 9.05 | 11.47 | 19.36 | dragon | 66.94.121.46 |
| 77.83 | shadowsocks | 287.7 | 667.1 | 21.12 | 0.0 | 9.91 | 13.74 | 19.36 | dragon | 185.215.132.18 |
| 77.71 | trojan | 296.4 | 659.4 | 20.92 | 0.0 | 9.95 | 12.05 | 19.36 | dragon | 216.152.155.158 |
| 77.66 | shadowsocks | 296.1 | 802.9 | 20.92 | 0.0 | 8.14 | 13.74 | 19.36 | dragon | 167.88.62.203 |
| 77.43 | trojan | 261.8 | 570.4 | 21.72 | 0.0 | 8.09 | 12.05 | 19.36 | dragon | 66.163.112.142 |
| 77.42 | shadowsocks | 307.0 | 806.2 | 20.67 | 0.0 | 8.15 | 13.74 | 19.36 | dragon | 167.88.62.56 |
| 77.34 | trojan | 262.5 | 602.3 | 21.7 | 0.0 | 8.16 | 12.05 | 19.36 | dragon | 66.163.114.166 |
| 77.25 | trojan | 266.1 | 586.4 | 21.62 | 0.0 | 8.09 | 12.05 | 19.36 | dragon | 66.163.112.171 |
| 77.11 | shadowsocks | 289.4 | 666.5 | 21.08 | 0.0 | 9.91 | 13.74 | 19.36 | dragon | 185.215.132.9 |
| 77.03 | trojan | 266.2 | 580.3 | 21.62 | 0.0 | 7.94 | 12.05 | 19.36 | dragon | 66.163.112.31 |
| 76.74 | trojan | 294.0 | 648.7 | 20.97 | 0.0 | 9.95 | 12.05 | 19.36 | dragon | 216.152.155.59 |
| 76.72 | trojan | 276.1 | 611.9 | 21.39 | 0.0 | 8.1 | 12.05 | 19.36 | dragon | 66.163.112.242 |
| 76.6 | shadowsocks | 233.7 | 512.4 | 22.37 | 0.0 | 7.96 | 13.74 | 19.36 | dragon | 137.184.89.151 |
| 76.4 | shadowsocks | 313.7 | 728.7 | 20.52 | 0.0 | 9.27 | 13.74 | 19.36 | dragon | 38.91.107.57 |
| 76.19 | shadowsocks | 356.7 | 931.8 | 19.52 | 0.0 | 8.07 | 13.74 | 19.36 | dragon | 149.40.57.133 |
| 75.83 | trojan | 263.4 | 568.9 | 21.68 | 0.0 | 8.16 | 12.05 | 19.36 | dragon | 66.163.112.121 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | 1.0 | 70 | 619 | prefer |
| dragon | 0.976 | 0.899 | 345 | 45201 | prefer |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8562 | observe |
| mheidari-all | 0.335 | 1.0 | 1 | 13868 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4955 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2620 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11122 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6459 | observe |
| barry-far-vless | 0.255 | None | 0 | 6669 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4595 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 14 |
| 204 | ProxyError | - | 5 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| cn-block | TimeoutError | - | 3 |
| speed | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |
| speed | TimeoutError | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 77 | 64 | - |
| global | False | 78 | 66 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
