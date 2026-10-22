# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-22 21:06:28 |
| 运行耗时 | 306.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96202 |
| 去重后节点 | 26700 |
| TCP 可达 | 3000 |
| 真实可用 | 98 |
| Verified 输出 | 98 |
| Global 输出 | 104 |
| All 输出 | 26700 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.5 |
| tcp | 80.1 |
| probe | 96.8 |
| real_test | 69.6 |
| china_check | 41.5 |
| write_verified | 0.0 |
| generate | 9.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57001 |
| vmess | 17174 |
| shadowsocks | 12343 |
| trojan | 7863 |
| hysteria2 | 1365 |
| http | 298 |
| socks | 58 |
| shadowsocksr | 55 |
| anytls | 22 |
| hysteria | 17 |
| tuic | 6 |

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
| 76.15 | hysteria2 | 278.4 | 587.5 | 21.33 | 0.0 | 9.48 | 13.24 | 15.32 | Au1rxx-base64 | 66.94.121.46 |
| 76.14 | shadowsocks | 240.7 | 589.6 | 22.21 | 0.0 | 9.57 | 13.04 | 15.32 | Au1rxx-base64 | 156.146.38.167 |
| 75.11 | shadowsocks | 252.1 | 633.4 | 21.94 | 0.0 | 9.81 | 13.04 | 15.32 | Au1rxx-base64 | 156.146.38.170 |
| 73.91 | shadowsocks | 309.2 | 754.7 | 20.62 | 0.0 | 10.0 | 13.04 | 15.32 | Au1rxx-base64 | 37.19.198.244 |
| 73.17 | hysteria2 | 262.1 | 657.0 | 21.71 | 0.0 | 9.4 | 13.24 | 15.32 | Au1rxx-base64 | 129.213.91.185 |
| 73.11 | shadowsocks | 292.7 | 700.9 | 21.0 | 0.0 | 9.66 | 13.04 | 15.32 | Au1rxx-base64 | 37.19.198.160 |
| 72.23 | shadowsocks | 364.6 | 921.4 | 19.34 | 0.0 | 9.52 | 13.04 | 15.32 | Au1rxx-base64 | 185.215.132.9 |
| 71.69 | shadowsocks | 393.6 | 1002.1 | 18.67 | 0.0 | 9.56 | 13.04 | 15.32 | Au1rxx-base64 | 45.86.51.18 |
| 71.62 | shadowsocks | 330.9 | 811.8 | 20.12 | 0.0 | 7.34 | 13.04 | 15.32 | Au1rxx-base64 | 37.19.198.243 |
| 71.37 | shadowsocks | 237.2 | 609.0 | 22.29 | 0.0 | 9.72 | 13.04 | 15.32 | Au1rxx-base64 | 156.146.38.169 |
| 70.79 | shadowsocks | 299.7 | 723.3 | 20.84 | 0.0 | 9.57 | 13.04 | 15.32 | Au1rxx-base64 | 193.151.163.18 |
| 70.27 | shadowsocks | 302.4 | 704.3 | 20.78 | 0.0 | 9.62 | 13.04 | 15.32 | Au1rxx-base64 | 185.230.230.18 |
| 70.15 | vless | 292.5 | 582.6 | 21.01 | 0.0 | 10.0 | 8.16 | 15.32 | Au1rxx-base64 | 45.76.172.197 |
| 70.06 | vless | 289.2 | 655.5 | 21.08 | 0.0 | 10.0 | 8.16 | 15.32 | Au1rxx-base64 | 69.48.201.136 |
| 70.0 | shadowsocks | 290.6 | 585.5 | 21.05 | 0.0 | 9.54 | 13.04 | 15.32 | Au1rxx-base64 | 95.215.201.18 |
| 69.65 | vless | 305.6 | 586.6 | 20.7 | 0.0 | 10.0 | 8.16 | 15.32 | Au1rxx-base64 | 144.202.126.147 |
| 69.19 | hysteria2 | 265.6 | 647.8 | 21.63 | 0.0 | 0.0 | 13.24 | 15.32 | Au1rxx-base64 | clash2.deep-links.com |
| 68.99 | shadowsocks | 484.2 | 1274.9 | 16.57 | 0.0 | 9.64 | 13.04 | 15.32 | Au1rxx-base64 | 185.215.132.18 |
| 68.84 | shadowsocks | 305.0 | 731.4 | 20.72 | 0.0 | 9.65 | 13.04 | 15.32 | Au1rxx-base64 | 37.19.198.236 |
| 67.89 | shadowsocks | 434.4 | 1042.0 | 17.72 | 0.0 | 9.48 | 13.04 | 15.32 | Au1rxx-base64 | 193.151.160.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.969 | 0.958 | 72 | 573 | prefer |
| mheidari-all | 0.868 | 0.797 | 64 | 23896 | prefer |
| Au1rxx-base64 | 0.806 | 0.746 | 185 | 1575 | prefer |
| Surfboard-tg-mixed | 0.696 | 0.619 | 84 | 7066 | observe |
| ninja-vless | 0.383 | 1.0 | 2 | 1791 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4176 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3641 | observe |
| Epodonios-all | 0.255 | None | 0 | 7550 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5426 | observe |
| barry-far-vless | 0.255 | None | 0 | 5640 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1575 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 53 |
| speed | ClientOSError | - | 14 |
| cn-block | TimeoutError | - | 6 |
| geo | ClientOSError | - | 6 |
| 204 | ProxyError | - | 4 |
| 204 | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 64 | 98 | - |
| global | False | 68 | 104 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
