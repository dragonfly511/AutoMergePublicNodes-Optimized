# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-27 22:03:23 |
| 运行耗时 | 412.4s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 142067 |
| 去重后节点 | 58977 |
| TCP 可达 | 3000 |
| 真实可用 | 75 |
| Verified 输出 | 75 |
| Global 输出 | 79 |
| All 输出 | 58977 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.7 |
| tcp | 206.6 |
| probe | 99.0 |
| real_test | 53.3 |
| china_check | 26.6 |
| write_verified | 0.0 |
| generate | 19.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 85420 |
| vmess | 21488 |
| shadowsocks | 16444 |
| trojan | 16057 |
| hysteria2 | 2038 |
| shadowsocksr | 272 |
| http | 117 |
| socks | 99 |
| hysteria | 46 |
| anytls | 43 |
| tuic | 43 |

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
| 71.93 | hysteria2 | 328.5 | 289.8 | 20.17 | 4.13 | 7.84 | 14.0 | 17.42 | dragon | 8.209.247.109 |
| 71.01 | vless | 220.0 | 497.8 | 22.69 | 0.0 | 3.4 | 7.5 | 17.42 | dragon | 47.251.108.158 |
| 70.11 | http | 219.3 | 452.8 | 22.7 | 0.0 | 0.0 | 13.97 | 19.04 | ermaozi | 154.81.36.92 |
| 69.04 | hysteria2 | 315.3 | 700.4 | 20.48 | 0.0 | 8.66 | 14.0 | 17.42 | dragon | 129.213.91.185 |
| 68.44 | vless | 336.6 | 738.4 | 19.99 | 0.0 | 7.28 | 7.5 | 17.42 | dragon | 44.248.233.99 |
| 68.19 | trojan | 216.4 | 510.7 | 22.77 | 0.0 | 10.0 | 6.0 | 17.42 | dragon | 45.32.135.70 |
| 68.07 | shadowsocks | 260.8 | 628.0 | 21.74 | 0.0 | 0.0 | 13.45 | 17.42 | dragon | 156.146.38.168 |
| 68.06 | shadowsocks | 258.4 | 615.1 | 21.8 | 0.0 | 0.0 | 13.45 | 17.42 | dragon | 156.146.38.170 |
| 68.04 | shadowsocks | 264.0 | 667.9 | 21.67 | 0.0 | 0.0 | 13.45 | 17.42 | dragon | 103.11.76.248 |
| 67.88 | trojan | 213.6 | 499.0 | 22.83 | 0.0 | 10.0 | 6.0 | 17.42 | dragon | 149.28.214.139 |
| 67.57 | shadowsocks | 284.3 | 758.9 | 21.2 | 0.0 | 0.0 | 13.45 | 17.42 | dragon | 95.215.201.18 |
| 67.32 | vless | 349.6 | 701.3 | 19.68 | 0.0 | 8.02 | 7.5 | 17.42 | dragon | 195.211.98.43 |
| 66.2 | hysteria2 | 512.2 | 858.2 | 15.92 | 0.0 | 7.75 | 14.0 | 17.42 | dragon | 62.210.124.146 |
| 65.69 | shadowsocks | 401.1 | 897.0 | 18.49 | 0.0 | 5.42 | 13.45 | 17.42 | dragon | 185.230.230.18 |
| 65.62 | vless | 354.5 | 886.7 | 19.57 | 0.0 | 7.38 | 7.5 | 17.42 | dragon | 23.95.222.127 |
| 65.58 | hysteria2 | 561.5 | 1034.6 | 14.78 | 0.0 | 7.54 | 14.0 | 17.42 | dragon | 64.188.98.171 |
| 65.57 | hysteria2 | 319.8 | 582.0 | 20.38 | 0.0 | 2.71 | 14.0 | 17.42 | dragon | starlink-ft.251313.xyz |
| 65.36 | http | 346.7 | 678.7 | 19.75 | 0.0 | 0.0 | 13.97 | 19.04 | ermaozi | 64.98.50.100 |
| 65.15 | shadowsocks | 484.3 | 955.5 | 16.57 | 0.0 | 8.2 | 13.45 | 17.42 | dragon | 15.204.246.132 |
| 65.03 | shadowsocks | 404.0 | 968.7 | 18.43 | 0.0 | 3.81 | 13.45 | 17.42 | dragon | 185.215.132.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.988 | 1.0 | 28 | 535 | prefer |
| dragon | 0.839 | 0.761 | 284 | 45232 | prefer |
| Surfboard-tg-mixed | 0.287 | 0.5 | 2 | 7532 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4988 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3052 | observe |
| Epodonios-all | 0.255 | None | 0 | 7530 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10257 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5538 | observe |
| barry-far-vless | 0.255 | None | 0 | 5531 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4500 | observe |
| mheidari-all | 0.255 | None | 0 | 24397 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.244 | None | 0 | 1730 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 46 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| geo | ClientOSError | - | 4 |
| 204 | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |
| cn-block | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 62 | 75 | - |
| global | False | 63 | 79 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
