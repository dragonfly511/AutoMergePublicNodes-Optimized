# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-04 14:04:19 |
| 运行耗时 | 425.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 127810 |
| 去重后节点 | 58870 |
| TCP 可达 | 3000 |
| 真实可用 | 72 |
| Verified 输出 | 72 |
| Global 输出 | 73 |
| All 输出 | 58870 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.8 |
| geo | 1.9 |
| tcp | 204.3 |
| probe | 119.3 |
| real_test | 38.4 |
| china_check | 22.5 |
| write_verified | 0.0 |
| generate | 30.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 78528 |
| vmess | 17530 |
| trojan | 15808 |
| shadowsocks | 13138 |
| hysteria2 | 2236 |
| shadowsocksr | 228 |
| socks | 110 |
| http | 72 |
| hysteria | 68 |
| tuic | 54 |
| anytls | 38 |

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
| 72.49 | hysteria2 | 236.0 | 604.7 | 22.32 | 0.0 | 0.0 | 11.47 | 19.7 | dragon | 88.216.195.188 |
| 71.94 | shadowsocks | 242.4 | 663.3 | 22.17 | 0.0 | 0.0 | 14.07 | 19.7 | dragon | 37.19.198.243 |
| 71.88 | shadowsocks | 244.8 | 671.4 | 22.11 | 0.0 | 0.0 | 14.07 | 19.7 | dragon | 37.19.198.244 |
| 71.52 | shadowsocks | 238.7 | 647.1 | 22.25 | 0.0 | 0.0 | 14.07 | 19.7 | dragon | 185.230.230.18 |
| 71.52 | shadowsocks | 260.3 | 671.3 | 21.75 | 0.0 | 0.0 | 14.07 | 19.7 | dragon | 37.19.198.160 |
| 70.9 | shadowsocks | 265.8 | 659.8 | 21.63 | 0.0 | 0.0 | 14.07 | 19.7 | dragon | 193.151.163.18 |
| 70.74 | hysteria2 | 271.5 | 544.7 | 21.49 | 0.0 | 3.11 | 11.47 | 19.7 | dragon | 67.216.207.144 |
| 70.72 | shadowsocks | 230.3 | 632.8 | 22.45 | 0.0 | 0.0 | 14.07 | 19.7 | dragon | 172.111.38.72 |
| 70.38 | shadowsocks | 287.9 | 701.1 | 21.11 | 0.0 | 0.0 | 14.07 | 19.7 | dragon | 193.151.160.18 |
| 70.01 | shadowsocks | 261.0 | 693.7 | 21.74 | 0.0 | 0.0 | 14.07 | 19.7 | dragon | 149.40.57.134 |
| 69.13 | trojan | 379.9 | 907.5 | 18.98 | 0.0 | 2.51 | 13.85 | 19.7 | dragon | 66.23.203.21 |
| 69.11 | shadowsocks | 296.8 | 729.3 | 20.91 | 0.0 | 0.0 | 14.07 | 19.7 | dragon | 169.197.140.247 |
| 68.97 | shadowsocks | 284.4 | 619.6 | 21.19 | 0.0 | 0.0 | 14.07 | 19.7 | dragon | 156.146.38.169 |
| 68.88 | shadowsocks | 352.7 | 1008.0 | 19.61 | 0.0 | 0.0 | 14.07 | 19.7 | dragon | 15.204.233.41 |
| 68.87 | shadowsocks | 295.6 | 657.8 | 20.94 | 0.0 | 0.0 | 14.07 | 19.7 | dragon | 156.146.38.167 |
| 68.8 | shadowsocks | 351.0 | 872.8 | 19.65 | 0.0 | 2.43 | 14.07 | 19.7 | dragon | 167.17.67.171 |
| 68.68 | shadowsocks | 310.9 | 726.8 | 20.58 | 0.0 | 0.0 | 14.07 | 19.7 | dragon | 193.151.160.9 |
| 68.27 | shadowsocks | 339.2 | 903.2 | 19.93 | 0.0 | 0.07 | 14.07 | 19.7 | dragon | 149.40.57.133 |
| 68.2 | shadowsocks | 344.1 | 847.1 | 19.81 | 0.0 | 0.12 | 14.07 | 19.7 | dragon | 38.64.138.135 |
| 68.1 | shadowsocks | 347.9 | 850.0 | 19.73 | 0.0 | 0.1 | 14.07 | 19.7 | dragon | 216.106.178.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.943 | 0.866 | 239 | 45574 | prefer |
| zhangkai | 0.877 | 0.947 | 19 | 43 | prefer |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8518 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 130 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2526 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10829 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5997 | observe |
| barry-far-vless | 0.255 | None | 0 | 6238 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4608 | observe |
| mheidari-all | 0.255 | None | 0 | 15179 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 22 |
| 204 | ProxyError | - | 4 |
| 204 | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| geo | TimeoutError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 77 | 72 | - |
| global | False | 78 | 73 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
