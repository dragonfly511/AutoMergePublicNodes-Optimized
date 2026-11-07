# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-07 21:43:02 |
| 运行耗时 | 434.0s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 126936 |
| 去重后节点 | 58653 |
| TCP 可达 | 3000 |
| 真实可用 | 72 |
| Verified 输出 | 72 |
| Global 输出 | 74 |
| All 输出 | 58653 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| geo | 1.8 |
| tcp | 198.7 |
| probe | 113.4 |
| real_test | 47.6 |
| china_check | 33.3 |
| write_verified | 0.0 |
| generate | 30.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77104 |
| vmess | 18449 |
| trojan | 14728 |
| shadowsocks | 13643 |
| hysteria2 | 2262 |
| shadowsocksr | 371 |
| socks | 146 |
| http | 94 |
| hysteria | 58 |
| tuic | 45 |
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
| 80.0 | shadowsocks | 258.5 | 618.6 | 21.79 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 137.184.89.151 |
| 79.27 | trojan | 229.5 | 541.5 | 22.46 | 0.0 | 9.78 | 10.55 | 18.98 | dragon | 66.163.114.245 |
| 77.79 | shadowsocks | 258.4 | 565.6 | 21.8 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 23.150.152.38 |
| 76.48 | trojan | 268.7 | 612.5 | 21.56 | 0.0 | 7.96 | 10.55 | 18.98 | dragon | 216.152.155.23 |
| 76.24 | trojan | 301.5 | 743.4 | 20.8 | 0.0 | 8.41 | 10.55 | 18.98 | dragon | 66.163.114.166 |
| 75.95 | shadowsocks | 311.1 | 699.2 | 20.58 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 37.19.198.243 |
| 75.53 | shadowsocks | 331.3 | 728.7 | 20.11 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 172.111.38.72 |
| 75.52 | shadowsocks | 312.2 | 775.9 | 20.55 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 156.146.38.167 |
| 75.4 | shadowsocks | 326.8 | 751.0 | 20.21 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 37.19.198.236 |
| 75.39 | shadowsocks | 337.7 | 772.2 | 19.96 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 37.19.198.244 |
| 75.34 | shadowsocks | 265.5 | 641.1 | 21.63 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 156.146.38.170 |
| 75.1 | shadowsocks | 326.8 | 724.6 | 20.21 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 185.230.230.18 |
| 74.99 | shadowsocks | 334.3 | 714.1 | 20.04 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 45.86.51.18 |
| 74.94 | shadowsocks | 313.6 | 669.0 | 20.52 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 193.151.163.18 |
| 74.85 | shadowsocks | 368.5 | 867.6 | 19.25 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 37.19.198.160 |
| 74.39 | shadowsocks | 337.8 | 747.0 | 19.96 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 193.151.160.9 |
| 74.37 | trojan | 296.2 | 660.1 | 20.92 | 0.0 | 9.62 | 10.55 | 18.98 | dragon | 170.101.101.112 |
| 73.95 | shadowsocks | 384.6 | 912.6 | 18.87 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 38.121.43.225 |
| 73.9 | shadowsocks | 267.0 | 652.2 | 21.6 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 156.146.38.169 |
| 73.87 | shadowsocks | 273.2 | 574.8 | 21.45 | 0.0 | 10.0 | 13.73 | 18.98 | dragon | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.977 | 0.9 | 299 | 45338 | prefer |
| ermaozi | 0.934 | 0.952 | 21 | 515 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 14235 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4866 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2734 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11058 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8421 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5923 | observe |
| barry-far-vless | 0.255 | None | 0 | 6134 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4529 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 17 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |
| geo | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 79 | 72 | - |
| global | False | 80 | 74 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
