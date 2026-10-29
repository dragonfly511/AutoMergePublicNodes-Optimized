# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-29 05:01:18 |
| 运行耗时 | 432.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 144239 |
| 去重后节点 | 59227 |
| TCP 可达 | 3000 |
| 真实可用 | 88 |
| Verified 输出 | 88 |
| Global 输出 | 88 |
| All 输出 | 59227 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.2 |
| geo | 1.7 |
| tcp | 207.0 |
| probe | 117.9 |
| real_test | 40.7 |
| china_check | 25.6 |
| write_verified | 0.0 |
| generate | 30.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 90878 |
| vmess | 18894 |
| trojan | 16593 |
| shadowsocks | 14182 |
| hysteria2 | 3049 |
| shadowsocksr | 240 |
| http | 203 |
| socks | 87 |
| tuic | 45 |
| hysteria | 35 |
| anytls | 33 |

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
| 76.4 | trojan | 348.4 | 892.9 | 19.71 | 0.0 | 7.12 | 12.69 | 19.88 | dragon | 66.23.203.21 |
| 76.04 | shadowsocks | 252.8 | 542.9 | 21.93 | 0.0 | 7.93 | 13.84 | 19.88 | dragon | 216.105.168.18 |
| 75.63 | shadowsocks | 236.2 | 598.6 | 22.31 | 0.0 | 3.6 | 13.84 | 19.88 | dragon | 156.146.38.168 |
| 75.46 | shadowsocks | 243.6 | 590.7 | 22.14 | 0.0 | 3.6 | 13.84 | 19.88 | dragon | 156.146.38.170 |
| 74.69 | shadowsocks | 303.3 | 299.6 | 20.76 | 3.76 | 7.95 | 13.84 | 19.88 | dragon | 149.22.87.204 |
| 73.39 | trojan | 305.4 | 638.4 | 20.71 | 0.0 | 6.37 | 12.69 | 19.88 | dragon | 216.106.186.32 |
| 73.24 | hysteria2 | 251.0 | 573.1 | 21.97 | 0.0 | 2.2 | 13.0 | 19.88 | dragon | 66.94.121.46 |
| 73.17 | hysteria2 | 251.6 | 249.4 | 21.95 | 5.65 | 0.0 | 13.0 | 19.88 | dragon | 8.209.247.109 |
| 71.0 | trojan | 267.3 | 634.8 | 21.59 | 0.0 | 4.34 | 12.69 | 19.88 | dragon | 216.152.155.23 |
| 70.97 | trojan | 267.2 | 644.8 | 21.59 | 0.0 | 4.31 | 12.69 | 19.88 | dragon | 216.152.155.54 |
| 70.93 | shadowsocks | 278.9 | 596.5 | 21.32 | 0.0 | 4.09 | 13.84 | 19.88 | dragon | 95.215.201.18 |
| 70.92 | shadowsocks | 279.0 | 588.2 | 21.32 | 0.0 | 3.52 | 13.84 | 19.88 | dragon | 173.244.56.9 |
| 70.29 | shadowsocks | 251.0 | 609.3 | 21.97 | 0.0 | 3.6 | 13.84 | 19.88 | dragon | 156.146.38.167 |
| 70.24 | http | 300.0 | 744.4 | 20.83 | 0.0 | 0.0 | 13.55 | 18.48 | ermaozi | 38.247.141.135 |
| 69.89 | shadowsocks | 298.0 | 634.6 | 20.88 | 0.0 | 8.34 | 13.84 | 19.88 | dragon | 198.98.53.130 |
| 69.69 | shadowsocks | 279.9 | 591.0 | 21.3 | 0.0 | 4.04 | 13.84 | 19.88 | dragon | 173.244.56.6 |
| 69.28 | shadowsocks | 334.5 | 752.4 | 20.03 | 0.0 | 3.32 | 13.84 | 19.88 | dragon | 37.19.198.244 |
| 68.85 | shadowsocks | 338.4 | 737.5 | 19.94 | 0.0 | 3.3 | 13.84 | 19.88 | dragon | 185.230.230.18 |
| 68.79 | shadowsocks | 346.5 | 756.9 | 19.76 | 0.0 | 3.33 | 13.84 | 19.88 | dragon | 37.19.198.236 |
| 68.52 | shadowsocks | 333.2 | 750.0 | 20.07 | 0.0 | 3.33 | 13.84 | 19.88 | dragon | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | 1.0 | 53 | 560 | prefer |
| dragon | 0.893 | 0.817 | 153 | 44753 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5004 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2801 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10399 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7653 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5723 | observe |
| barry-far-vless | 0.255 | None | 0 | 5902 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4323 | observe |
| mheidari-all | 0.255 | None | 0 | 34088 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.243 | None | 0 | 1694 | observe |
| Au1rxx-clash | 0.243 | None | 0 | 1694 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 22 |
| geo | ClientOSError | - | 2 |
| speed | ClientOSError | - | 2 |
| 204 | ClientOSError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 68 | 88 | - |
| global | False | 69 | 88 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
