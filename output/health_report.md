# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-17 18:15:30 |
| 运行耗时 | 316.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99383 |
| 去重后节点 | 27816 |
| TCP 可达 | 3000 |
| 真实可用 | 64 |
| Verified 输出 | 64 |
| Global 输出 | 67 |
| All 输出 | 27816 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 83.9 |
| probe | 113.7 |
| real_test | 70.3 |
| china_check | 24.7 |
| write_verified | 0.0 |
| generate | 14.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58332 |
| vmess | 16690 |
| shadowsocks | 12008 |
| trojan | 10105 |
| hysteria2 | 1352 |
| http | 613 |
| shadowsocksr | 175 |
| socks | 59 |
| anytls | 26 |
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
| 74.7 | shadowsocks | 314.0 | 673.2 | 20.51 | 0.0 | 10.0 | 12.43 | 15.76 | Au1rxx-base64 | 37.19.198.236 |
| 74.61 | shadowsocks | 255.3 | 705.0 | 21.87 | 0.0 | 9.55 | 12.43 | 15.76 | Au1rxx-base64 | 37.19.198.160 |
| 73.49 | shadowsocks | 292.1 | 674.2 | 21.02 | 0.0 | 10.0 | 12.43 | 15.76 | Au1rxx-base64 | 156.146.38.169 |
| 73.24 | vless | 247.4 | 649.5 | 22.05 | 0.0 | 10.0 | 8.28 | 15.76 | Au1rxx-base64 | 147.45.60.160 |
| 72.98 | shadowsocks | 288.8 | 669.2 | 21.09 | 0.0 | 10.0 | 12.43 | 15.76 | Au1rxx-base64 | 156.146.38.168 |
| 72.79 | shadowsocks | 254.1 | 702.7 | 21.9 | 0.0 | 10.0 | 12.43 | 15.76 | Au1rxx-base64 | 37.19.198.244 |
| 72.7 | shadowsocks | 296.1 | 679.7 | 20.92 | 0.0 | 10.0 | 12.43 | 15.76 | Au1rxx-base64 | 156.146.38.167 |
| 72.65 | hysteria2 | 238.1 | 678.1 | 22.27 | 0.0 | 4.58 | 11.54 | 15.76 | Au1rxx-base64 | 129.213.91.185 |
| 69.19 | shadowsocks | 335.6 | 686.3 | 20.01 | 0.0 | 10.0 | 12.43 | 15.76 | Au1rxx-base64 | 173.244.56.9 |
| 69.0 | shadowsocks | 344.4 | 712.7 | 19.81 | 0.0 | 10.0 | 12.43 | 15.76 | Au1rxx-base64 | 173.244.56.6 |
| 68.04 | shadowsocks | 519.7 | 1181.5 | 15.75 | 0.0 | 9.6 | 12.43 | 15.76 | Au1rxx-base64 | 15.204.247.206 |
| 67.76 | shadowsocks | 374.5 | 758.2 | 19.11 | 0.0 | 10.0 | 12.43 | 15.76 | Au1rxx-base64 | 149.22.95.183 |
| 67.64 | vless | 352.1 | 839.9 | 19.63 | 0.0 | 10.0 | 8.28 | 15.76 | Au1rxx-base64 | 69.48.201.136 |
| 67.13 | vless | 364.6 | 700.3 | 19.34 | 0.0 | 9.71 | 8.28 | 15.76 | Au1rxx-base64 | 178.17.57.33 |
| 66.79 | shadowsocks | 352.7 | 942.6 | 19.61 | 0.0 | 8.49 | 12.43 | 15.76 | Au1rxx-base64 | 64.74.163.69 |
| 64.96 | hysteria2 | 366.5 | 698.7 | 19.29 | 0.0 | 5.25 | 11.54 | 15.76 | Au1rxx-base64 | 62.210.124.146 |
| 64.89 | vless | 421.5 | 1082.6 | 18.02 | 0.0 | 3.87 | 8.28 | 15.76 | Au1rxx-base64 | 209.200.246.148 |
| 64.55 | vless | 378.4 | 666.5 | 19.02 | 0.0 | 7.78 | 8.28 | 15.76 | Au1rxx-base64 | 154.9.241.170 |
| 64.52 | vless | 359.3 | 649.2 | 19.46 | 0.0 | 8.93 | 8.28 | 15.76 | Au1rxx-base64 | 45.63.53.81 |
| 64.45 | shadowsocks | 408.7 | 773.4 | 18.32 | 0.0 | 8.68 | 12.43 | 15.76 | Au1rxx-base64 | 158.173.20.208 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.925 | 0.929 | 28 | 623 | prefer |
| Au1rxx-base64 | 0.733 | 0.654 | 327 | 1992 | prefer |
| mheidari-all | 0.612 | 0.625 | 16 | 23824 | observe |
| Surfboard-tg-mixed | 0.563 | 0.481 | 27 | 7087 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4986 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1992 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 4999 | observe |
| Epodonios-all | 0.255 | None | 0 | 7677 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10164 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5622 | observe |
| barry-far-vless | 0.255 | None | 0 | 5866 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4295 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 84 |
| speed | ClientOSError | - | 15 |
| 204 | ProxyError | - | 9 |
| geo | ClientOSError | - | 9 |
| 204 | TimeoutError | - | 8 |
| cn-block | ClientOSError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 92 | 64 | - |
| global | False | 96 | 67 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
