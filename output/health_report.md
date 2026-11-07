# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-07 05:17:27 |
| 运行耗时 | 421.9s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 127015 |
| 去重后节点 | 58489 |
| TCP 可达 | 3000 |
| 真实可用 | 89 |
| Verified 输出 | 89 |
| Global 输出 | 92 |
| All 输出 | 58489 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.9 |
| geo | 1.7 |
| tcp | 186.6 |
| probe | 120.1 |
| real_test | 40.1 |
| china_check | 33.3 |
| write_verified | 0.0 |
| generate | 31.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77964 |
| vmess | 18437 |
| trojan | 14182 |
| shadowsocks | 13423 |
| hysteria2 | 2311 |
| shadowsocksr | 232 |
| http | 187 |
| socks | 114 |
| hysteria | 70 |
| tuic | 56 |
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
| 80.73 | trojan | 228.8 | 655.1 | 22.48 | 0.0 | 8.11 | 13.64 | 20.0 | dragon | 66.163.122.25 |
| 79.7 | hysteria2 | 284.4 | 733.2 | 21.19 | 0.0 | 5.51 | 14.0 | 20.0 | dragon | 88.216.195.188 |
| 79.67 | trojan | 312.4 | 703.5 | 20.55 | 0.0 | 7.98 | 13.64 | 20.0 | dragon | 216.152.155.23 |
| 79.14 | trojan | 314.3 | 743.5 | 20.5 | 0.0 | 7.91 | 13.64 | 20.0 | dragon | 169.197.140.171 |
| 79.1 | trojan | 292.9 | 657.5 | 21.0 | 0.0 | 6.96 | 13.64 | 20.0 | dragon | 216.152.155.54 |
| 78.89 | trojan | 307.7 | 725.0 | 20.65 | 0.0 | 8.04 | 13.64 | 20.0 | dragon | 169.197.140.214 |
| 78.73 | trojan | 261.5 | 654.5 | 21.72 | 0.0 | 5.87 | 13.64 | 20.0 | dragon | 216.152.155.158 |
| 78.72 | trojan | 238.4 | 681.8 | 22.26 | 0.0 | 7.32 | 13.64 | 20.0 | dragon | 66.163.122.46 |
| 78.71 | trojan | 302.4 | 737.6 | 20.78 | 0.0 | 9.55 | 13.64 | 20.0 | dragon | 216.152.147.201 |
| 78.57 | trojan | 244.7 | 694.6 | 22.11 | 0.0 | 7.32 | 13.64 | 20.0 | dragon | 66.163.122.7 |
| 78.08 | trojan | 312.3 | 798.3 | 20.55 | 0.0 | 6.39 | 13.64 | 20.0 | dragon | 216.152.155.176 |
| 77.8 | trojan | 316.4 | 809.8 | 20.45 | 0.0 | 6.21 | 13.64 | 20.0 | dragon | 216.152.155.131 |
| 77.53 | trojan | 306.1 | 748.2 | 20.69 | 0.0 | 6.7 | 13.64 | 20.0 | dragon | 170.101.101.131 |
| 77.21 | trojan | 229.6 | 660.1 | 22.46 | 0.0 | 5.61 | 13.64 | 20.0 | dragon | 66.163.122.81 |
| 77.2 | trojan | 305.1 | 737.8 | 20.71 | 0.0 | 5.43 | 13.64 | 20.0 | dragon | 169.197.140.169 |
| 77.0 | trojan | 306.1 | 733.1 | 20.69 | 0.0 | 5.87 | 13.64 | 20.0 | dragon | 169.197.140.224 |
| 77.0 | trojan | 306.5 | 740.7 | 20.68 | 0.0 | 5.73 | 13.64 | 20.0 | dragon | 169.197.140.245 |
| 76.29 | shadowsocks | 295.0 | 727.4 | 20.95 | 0.0 | 5.41 | 14.44 | 20.0 | dragon | 169.197.140.247 |
| 76.23 | shadowsocks | 402.7 | 1074.1 | 18.46 | 0.0 | 7.83 | 14.44 | 20.0 | dragon | 158.51.121.221 |
| 76.16 | shadowsocks | 300.9 | 744.4 | 20.81 | 0.0 | 5.41 | 14.44 | 20.0 | dragon | 38.91.107.57 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | 1.0 | 50 | 562 | prefer |
| dragon | 0.999 | 0.922 | 308 | 45178 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 13634 | observe |
| Surfboard-tg-mixed | 0.287 | 0.5 | 2 | 8637 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4934 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2768 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11015 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6148 | observe |
| barry-far-vless | 0.255 | None | 0 | 6359 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4540 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 13 |
| 204 | ProxyError | - | 3 |
| cn-block | TimeoutError | - | 3 |
| geo | ProxyError | - | 3 |
| speed | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 78 | 89 | - |
| global | False | 78 | 92 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
