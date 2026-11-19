# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-19 07:20:14 |
| 运行耗时 | 451.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 127250 |
| 去重后节点 | 59221 |
| TCP 可达 | 3000 |
| 真实可用 | 104 |
| Verified 输出 | 104 |
| Global 输出 | 111 |
| All 输出 | 59221 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| geo | 1.7 |
| tcp | 187.6 |
| probe | 116.8 |
| real_test | 56.4 |
| china_check | 49.4 |
| write_verified | 0.0 |
| generate | 31.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77128 |
| vmess | 19047 |
| trojan | 14333 |
| shadowsocks | 13926 |
| hysteria2 | 2099 |
| shadowsocksr | 270 |
| socks | 180 |
| http | 129 |
| hysteria | 56 |
| tuic | 52 |
| anytls | 30 |

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
| 77.35 | shadowsocks | 192.3 | 442.3 | 23.33 | 0.0 | 5.11 | 14.43 | 18.98 | dragon | 137.184.89.151 |
| 75.58 | shadowsocks | 288.2 | 771.9 | 21.11 | 0.0 | 5.56 | 14.43 | 18.98 | dragon | 23.150.152.38 |
| 75.22 | shadowsocks | 249.6 | 606.5 | 22.0 | 0.0 | 3.91 | 14.43 | 18.98 | dragon | 149.22.95.183 |
| 74.3 | trojan | 236.9 | 561.0 | 22.29 | 0.0 | 8.03 | 7.5 | 18.98 | dragon | 66.163.112.171 |
| 73.14 | shadowsocks | 236.2 | 562.8 | 22.31 | 0.0 | 4.42 | 14.43 | 18.98 | dragon | 173.244.56.6 |
| 72.75 | shadowsocks | 232.8 | 552.8 | 22.39 | 0.0 | 5.52 | 14.43 | 18.98 | dragon | 95.215.201.18 |
| 72.65 | shadowsocks | 191.8 | 483.3 | 23.34 | 0.0 | 0.0 | 14.43 | 18.98 | dragon | 38.145.220.193 |
| 72.62 | shadowsocks | 175.9 | 466.2 | 23.71 | 0.0 | 0.0 | 14.43 | 18.98 | dragon | 104.238.140.45 |
| 72.48 | http | 195.2 | 493.1 | 23.26 | 0.0 | 0.0 | 13.64 | 18.58 | ermaozi | 38.95.111.226 |
| 72.18 | http | 186.5 | 474.1 | 23.46 | 0.0 | 0.0 | 13.64 | 18.58 | ermaozi | 172.64.68.89 |
| 70.22 | shadowsocks | 486.6 | 1397.1 | 16.51 | 0.0 | 4.8 | 14.43 | 18.98 | dragon | 169.197.142.68 |
| 69.92 | trojan | 174.2 | 459.4 | 23.74 | 0.0 | 7.2 | 7.5 | 18.98 | dragon | 167.88.61.175 |
| 69.34 | shadowsocks | 388.3 | 932.8 | 18.79 | 0.0 | 4.56 | 14.43 | 18.98 | dragon | 167.88.62.203 |
| 68.25 | shadowsocks | 228.8 | 538.9 | 22.48 | 0.0 | 0.0 | 14.43 | 18.98 | dragon | 173.244.56.9 |
| 68.14 | trojan | 243.9 | 420.2 | 22.13 | 0.0 | 7.03 | 7.5 | 18.98 | dragon | 167.88.61.20 |
| 68.03 | shadowsocks | 302.8 | 360.6 | 20.77 | 1.48 | 3.5 | 14.43 | 18.98 | dragon | 149.22.87.240 |
| 67.66 | shadowsocks | 373.0 | 767.8 | 19.14 | 0.0 | 5.04 | 14.43 | 18.98 | dragon | 172.111.38.72 |
| 67.53 | shadowsocks | 364.0 | 737.7 | 19.35 | 0.0 | 4.58 | 14.43 | 18.98 | dragon | 45.86.51.18 |
| 67.39 | shadowsocks | 295.8 | 671.0 | 20.93 | 0.0 | 5.23 | 14.43 | 18.98 | dragon | 156.146.38.169 |
| 67.33 | trojan | 295.7 | 654.3 | 20.93 | 0.0 | 5.13 | 7.5 | 18.98 | dragon | 66.163.112.76 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.951 | 0.874 | 269 | 45096 | prefer |
| ermaozi | 0.877 | 0.885 | 26 | 494 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 14200 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4919 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2925 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11797 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8472 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5689 | observe |
| barry-far-vless | 0.255 | None | 0 | 5975 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4458 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 23 |
| cn-block | ClientOSError | - | 7 |
| 204 | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | TimeoutError | - | 1 |
| 204 | ProxyConnectionError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 81 | 104 | - |
| global | False | 82 | 111 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
