# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-27 07:29:18 |
| 运行耗时 | 463.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 123429 |
| 去重后节点 | 58453 |
| TCP 可达 | 3000 |
| 真实可用 | 80 |
| Verified 输出 | 80 |
| Global 输出 | 83 |
| All 输出 | 58453 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.5 |
| geo | 1.4 |
| tcp | 210.5 |
| probe | 110.6 |
| real_test | 68.1 |
| china_check | 34.9 |
| write_verified | 0.0 |
| generate | 29.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 73551 |
| vmess | 19526 |
| shadowsocks | 13917 |
| trojan | 13227 |
| hysteria2 | 2206 |
| shadowsocksr | 285 |
| tuic | 271 |
| socks | 195 |
| http | 154 |
| anytls | 59 |
| hysteria | 38 |

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
| 80.1 | shadowsocks | 205.6 | 543.8 | 23.02 | 0.0 | 10.0 | 12.84 | 18.24 | dragon | 149.22.95.183 |
| 78.75 | trojan | 229.9 | 510.3 | 22.46 | 0.0 | 10.0 | 11.25 | 18.24 | dragon | 167.88.61.20 |
| 78.71 | trojan | 243.0 | 494.6 | 22.15 | 0.0 | 9.93 | 11.25 | 18.24 | dragon | 167.88.61.198 |
| 78.65 | trojan | 231.5 | 506.1 | 22.42 | 0.0 | 10.0 | 11.25 | 18.24 | dragon | 167.88.61.52 |
| 78.53 | shadowsocks | 226.0 | 510.2 | 22.55 | 0.0 | 10.0 | 12.84 | 18.24 | dragon | 169.197.142.68 |
| 77.93 | trojan | 256.3 | 496.5 | 21.85 | 0.0 | 9.82 | 11.25 | 18.24 | dragon | 167.88.61.193 |
| 77.84 | shadowsocks | 281.7 | 705.9 | 21.26 | 0.0 | 10.0 | 12.84 | 18.24 | dragon | 137.184.89.151 |
| 77.5 | trojan | 232.6 | 516.8 | 22.39 | 0.0 | 9.92 | 11.25 | 18.24 | dragon | 167.88.61.175 |
| 75.77 | shadowsocks | 309.8 | 753.7 | 20.61 | 0.0 | 10.0 | 12.84 | 18.24 | dragon | 23.150.152.38 |
| 75.58 | shadowsocks | 272.4 | 583.7 | 21.47 | 0.0 | 10.0 | 12.84 | 18.24 | dragon | 95.215.201.18 |
| 74.91 | shadowsocks | 274.2 | 572.3 | 21.43 | 0.0 | 10.0 | 12.84 | 18.24 | dragon | 173.244.56.6 |
| 74.77 | http | 188.6 | 465.1 | 23.41 | 0.0 | 0.0 | 14.38 | 19.48 | ermaozi | 172.64.69.89 |
| 73.54 | shadowsocks | 283.3 | 325.4 | 21.22 | 2.8 | 9.34 | 12.84 | 18.24 | dragon | 149.22.87.241 |
| 72.17 | shadowsocks | 367.6 | 813.8 | 19.27 | 0.0 | 9.86 | 12.84 | 18.24 | dragon | 156.146.38.168 |
| 71.65 | shadowsocks | 367.7 | 825.5 | 19.27 | 0.0 | 9.71 | 12.84 | 18.24 | dragon | 156.146.38.170 |
| 71.22 | trojan | 332.1 | 680.2 | 20.09 | 0.0 | 9.63 | 11.25 | 18.24 | dragon | 216.152.155.23 |
| 70.91 | shadowsocks | 368.9 | 766.7 | 19.24 | 0.0 | 10.0 | 12.84 | 18.24 | dragon | 45.86.51.18 |
| 70.79 | shadowsocks | 320.0 | 664.9 | 20.37 | 0.0 | 9.71 | 12.84 | 18.24 | dragon | 156.146.38.169 |
| 70.66 | shadowsocks | 367.5 | 747.6 | 19.27 | 0.0 | 9.79 | 12.84 | 18.24 | dragon | 172.111.38.72 |
| 70.53 | shadowsocks | 262.4 | 271.1 | 21.7 | 4.83 | 9.33 | 12.84 | 18.24 | dragon | 168.138.205.100 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.971 | 0.976 | 42 | 422 | prefer |
| dragon | 0.912 | 0.834 | 356 | 45062 | prefer |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8568 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 103 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4936 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11568 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5426 | observe |
| barry-far-vless | 0.255 | None | 0 | 5609 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4448 | observe |
| mheidari-all | 0.255 | None | 0 | 14315 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 37 |
| speed | TimeoutError | - | 11 |
| cn-block | ClientOSError | - | 7 |
| speed | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |
| 204 | ProxyError | - | 1 |
| speed | ClientOSError | - | 1 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 89 | 80 | - |
| global | False | 91 | 83 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
