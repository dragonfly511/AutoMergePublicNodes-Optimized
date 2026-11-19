# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-19 20:17:00 |
| 运行耗时 | 372.6s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 128278 |
| 去重后节点 | 59661 |
| TCP 可达 | 3000 |
| 真实可用 | 27 |
| Verified 输出 | 27 |
| Global 输出 | 28 |
| All 输出 | 59661 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.7 |
| tcp | 190.5 |
| probe | 94.2 |
| real_test | 24.2 |
| china_check | 26.6 |
| write_verified | 0.0 |
| generate | 27.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 78230 |
| vmess | 19002 |
| trojan | 14242 |
| shadowsocks | 14033 |
| hysteria2 | 2091 |
| shadowsocksr | 268 |
| socks | 144 |
| http | 128 |
| hysteria | 59 |
| tuic | 52 |
| anytls | 29 |

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
| 79.32 | trojan | 182.7 | 462.2 | 23.55 | 0.0 | 5.08 | 14.17 | 19.02 | dragon | 167.88.61.193 |
| 77.61 | hysteria2 | 168.2 | 477.8 | 23.88 | 0.0 | 10.0 | 10.71 | 19.02 | dragon | starlink-ft.251313.xyz |
| 76.51 | shadowsocks | 259.7 | 702.3 | 21.77 | 0.0 | 6.95 | 13.27 | 19.02 | dragon | 23.150.152.38 |
| 76.2 | shadowsocks | 249.7 | 604.0 | 22.0 | 0.0 | 6.4 | 13.27 | 19.02 | dragon | 149.22.95.183 |
| 76.07 | trojan | 188.3 | 478.9 | 23.42 | 0.0 | 6.96 | 14.17 | 19.02 | dragon | 167.88.61.175 |
| 76.02 | trojan | 186.0 | 467.6 | 23.47 | 0.0 | 6.86 | 14.17 | 19.02 | dragon | 167.88.61.20 |
| 73.75 | trojan | 182.7 | 464.0 | 23.55 | 0.0 | 4.51 | 14.17 | 19.02 | dragon | 167.88.61.85 |
| 73.43 | trojan | 179.9 | 469.6 | 23.61 | 0.0 | 4.13 | 14.17 | 19.02 | dragon | 167.88.61.198 |
| 71.09 | http | 198.1 | 482.7 | 23.19 | 0.0 | 0.0 | 12.86 | 17.54 | ermaozi | 172.64.68.89 |
| 70.31 | trojan | 332.9 | 334.1 | 20.07 | 2.47 | 7.81 | 14.17 | 19.02 | dragon | 193.123.160.109 |
| 69.68 | hysteria2 | 295.1 | 726.1 | 20.95 | 0.0 | 0.0 | 10.71 | 19.02 | dragon | 66.94.121.46 |
| 69.52 | http | 192.6 | 489.6 | 23.32 | 0.0 | 0.0 | 12.86 | 17.54 | ermaozi | 172.64.69.89 |
| 68.27 | trojan | 179.6 | 454.4 | 23.62 | 0.0 | 4.52 | 14.17 | 19.02 | dragon | 167.88.61.52 |
| 67.93 | trojan | 582.1 | 1317.5 | 14.3 | 0.0 | 9.85 | 14.17 | 19.02 | dragon | 69.164.240.85 |
| 66.51 | hysteria2 | 228.8 | 234.3 | 22.48 | 6.22 | 0.0 | 10.71 | 19.02 | dragon | 8.209.247.109 |
| 65.3 | shadowsocks | 458.0 | 900.5 | 17.18 | 0.0 | 6.15 | 13.27 | 19.02 | dragon | 38.121.43.231 |
| 65.2 | trojan | 433.6 | 461.1 | 17.74 | 0.0 | 4.61 | 14.17 | 19.02 | dragon | 158.247.253.243 |
| 64.74 | hysteria2 | 343.6 | 718.5 | 19.82 | 0.0 | 0.0 | 10.71 | 19.02 | dragon | 206.189.229.48 |
| 64.67 | trojan | 516.5 | 1369.1 | 15.82 | 0.0 | 3.12 | 14.17 | 19.02 | dragon | 66.163.112.142 |
| 62.81 | trojan | 524.5 | 730.1 | 15.64 | 0.0 | 4.47 | 14.17 | 19.02 | dragon | 45.63.30.142 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.94 | 0.957 | 23 | 491 | prefer |
| dragon | 0.518 | 0.437 | 87 | 45096 | observe |
| tg-LonUp_M | 0.365 | 1.0 | 3 | 179 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4935 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2728 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 12076 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8602 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5937 | observe |
| barry-far-vless | 0.255 | None | 0 | 5868 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4507 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 25 |
| test_one_timeout | 15.0s | - | 8 |
| cn-block | ProxyError | - | 7 |
| geo | ProxyError | - | 3 |
| 204 | TimeoutError | - | 3 |
| speed | ProxyError | - | 3 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42422: bind: address already in use | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 104 | 27 | - |
| global | False | 111 | 28 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
