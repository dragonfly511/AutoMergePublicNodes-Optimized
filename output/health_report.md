# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-17 15:46:47 |
| 运行耗时 | 391.2s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 126636 |
| 去重后节点 | 58509 |
| TCP 可达 | 3000 |
| 真实可用 | 77 |
| Verified 输出 | 77 |
| Global 输出 | 77 |
| All 输出 | 58509 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.2 |
| geo | 1.5 |
| tcp | 196.6 |
| probe | 101.9 |
| real_test | 41.3 |
| china_check | 25.5 |
| write_verified | 0.0 |
| generate | 19.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77537 |
| vmess | 18682 |
| trojan | 13904 |
| shadowsocks | 13596 |
| hysteria2 | 2053 |
| shadowsocksr | 420 |
| http | 188 |
| socks | 112 |
| tuic | 54 |
| hysteria | 54 |
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
| 79.57 | shadowsocks | 211.1 | 552.3 | 22.89 | 0.0 | 7.27 | 14.31 | 19.6 | dragon | 95.215.201.18 |
| 78.29 | shadowsocks | 220.2 | 493.6 | 22.68 | 0.0 | 7.13 | 14.31 | 19.6 | dragon | 169.197.142.68 |
| 77.53 | shadowsocks | 296.3 | 766.6 | 20.92 | 0.0 | 7.2 | 14.31 | 19.6 | dragon | 23.150.152.38 |
| 75.3 | shadowsocks | 218.2 | 489.0 | 22.73 | 0.0 | 7.12 | 14.31 | 19.6 | dragon | 137.184.89.151 |
| 73.18 | shadowsocks | 357.3 | 907.3 | 19.51 | 0.0 | 7.01 | 14.31 | 19.6 | dragon | 167.88.62.203 |
| 72.86 | http | 227.5 | 518.1 | 22.51 | 0.0 | 0.0 | 13.85 | 19.0 | ermaozi | 172.64.68.89 |
| 72.47 | shadowsocks | 183.6 | 487.9 | 23.53 | 0.0 | 0.27 | 14.31 | 19.6 | dragon | 38.145.220.193 |
| 71.73 | shadowsocks | 344.2 | 730.0 | 19.81 | 0.0 | 6.74 | 14.31 | 19.6 | dragon | 45.86.51.18 |
| 71.46 | shadowsocks | 347.7 | 743.0 | 19.73 | 0.0 | 6.74 | 14.31 | 19.6 | dragon | 172.111.38.72 |
| 71.41 | shadowsocks | 343.4 | 759.5 | 19.83 | 0.0 | 6.58 | 14.31 | 19.6 | dragon | 193.151.160.18 |
| 71.39 | hysteria2 | 320.3 | 684.6 | 20.36 | 0.0 | 2.24 | 13.33 | 19.6 | dragon | 206.189.229.48 |
| 71.37 | shadowsocks | 346.9 | 748.6 | 19.75 | 0.0 | 6.48 | 14.31 | 19.6 | dragon | 193.151.160.9 |
| 70.98 | shadowsocks | 354.5 | 746.9 | 19.57 | 0.0 | 6.78 | 14.31 | 19.6 | dragon | 38.91.107.188 |
| 70.87 | shadowsocks | 388.5 | 895.7 | 18.78 | 0.0 | 6.77 | 14.31 | 19.6 | dragon | 38.128.66.32 |
| 70.82 | shadowsocks | 343.0 | 733.9 | 19.84 | 0.0 | 6.4 | 14.31 | 19.6 | dragon | 185.230.230.18 |
| 70.25 | shadowsocks | 414.3 | 951.7 | 18.19 | 0.0 | 7.06 | 14.31 | 19.6 | dragon | 38.22.17.129 |
| 70.05 | shadowsocks | 269.3 | 625.6 | 21.54 | 0.0 | 7.03 | 14.31 | 19.6 | dragon | 156.146.38.170 |
| 69.82 | shadowsocks | 353.1 | 703.4 | 19.61 | 0.0 | 6.49 | 14.31 | 19.6 | dragon | 193.151.163.18 |
| 69.46 | shadowsocks | 451.8 | 1115.0 | 17.32 | 0.0 | 6.79 | 14.31 | 19.6 | dragon | 149.40.57.133 |
| 68.72 | shadowsocks | 268.1 | 629.7 | 21.57 | 0.0 | 7.04 | 14.31 | 19.6 | dragon | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.931 | 0.854 | 233 | 44193 | prefer |
| ermaozi | 0.854 | 0.864 | 22 | 517 | prefer |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4601 | observe |
| mheidari-all | 0.335 | 1.0 | 1 | 14572 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 172 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4928 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2790 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11523 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8546 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5851 | observe |
| barry-far-vless | 0.255 | None | 0 | 6032 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 19 |
| speed | TimeoutError | - | 5 |
| 204 | ProxyError | - | 5 |
| 204 | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| speed | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 91 | 77 | - |
| global | False | 92 | 77 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
