# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-22 02:43:51 |
| 运行耗时 | 314.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 91 |
| 原始节点 | 96930 |
| 去重后节点 | 27034 |
| TCP 可达 | 3000 |
| 真实可用 | 84 |
| Verified 输出 | 84 |
| Global 输出 | 92 |
| All 输出 | 27034 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| geo | 1.6 |
| tcp | 80.8 |
| probe | 107.3 |
| real_test | 70.0 |
| china_check | 31.6 |
| write_verified | 0.1 |
| generate | 14.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57649 |
| vmess | 17017 |
| shadowsocks | 12106 |
| trojan | 8428 |
| hysteria2 | 1271 |
| http | 195 |
| shadowsocksr | 165 |
| socks | 55 |
| anytls | 21 |
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
| 76.35 | shadowsocks | 267.8 | 718.4 | 21.58 | 0.0 | 10.0 | 13.65 | 15.12 | Au1rxx-base64 | 37.19.198.243 |
| 76.12 | shadowsocks | 256.3 | 673.1 | 21.85 | 0.0 | 10.0 | 13.65 | 15.12 | Au1rxx-base64 | 193.151.163.18 |
| 75.3 | shadowsocks | 255.1 | 677.0 | 21.87 | 0.0 | 8.66 | 13.65 | 15.12 | Au1rxx-base64 | 37.19.198.244 |
| 74.21 | shadowsocks | 278.4 | 617.9 | 21.33 | 0.0 | 10.0 | 13.65 | 15.12 | Au1rxx-base64 | 156.146.38.167 |
| 72.24 | shadowsocks | 315.5 | 849.7 | 20.47 | 0.0 | 10.0 | 13.65 | 15.12 | Au1rxx-base64 | 198.98.53.130 |
| 71.71 | shadowsocks | 266.8 | 714.5 | 21.6 | 0.0 | 5.34 | 13.65 | 15.12 | Au1rxx-base64 | 37.19.198.160 |
| 71.4 | shadowsocks | 306.6 | 823.3 | 20.68 | 0.0 | 5.95 | 13.65 | 15.12 | Au1rxx-base64 | 37.19.198.236 |
| 69.66 | shadowsocks | 288.3 | 669.5 | 21.1 | 0.0 | 10.0 | 13.65 | 15.12 | Au1rxx-base64 | 156.146.38.168 |
| 68.62 | hysteria2 | 420.1 | 760.5 | 18.05 | 0.0 | 9.58 | 13.0 | 15.12 | Au1rxx-base64 | 185.156.44.99 |
| 68.59 | shadowsocks | 353.5 | 673.9 | 19.6 | 0.0 | 10.0 | 13.65 | 15.12 | Au1rxx-base64 | 149.22.95.183 |
| 67.87 | hysteria2 | 426.6 | 901.6 | 17.9 | 0.0 | 7.82 | 13.0 | 15.12 | Au1rxx-base64 | 5.129.235.85 |
| 67.86 | vless | 304.7 | 735.1 | 20.73 | 0.0 | 5.09 | 7.99 | 15.12 | Au1rxx-base64 | 66.70.179.198 |
| 67.85 | shadowsocks | 403.3 | 891.4 | 18.44 | 0.0 | 10.0 | 13.65 | 15.12 | Au1rxx-base64 | 95.215.201.18 |
| 67.78 | shadowsocks | 382.4 | 978.0 | 18.93 | 0.0 | 5.79 | 13.65 | 15.12 | Au1rxx-base64 | 193.151.160.18 |
| 67.27 | vless | 342.4 | 622.1 | 19.85 | 0.0 | 10.0 | 7.99 | 15.12 | Au1rxx-base64 | 45.32.69.110 |
| 66.8 | shadowsocks | 353.6 | 883.9 | 19.59 | 0.0 | 0.0 | 13.65 | 18.06 | mheidari-all | 51.222.136.236 |
| 66.51 | shadowsocks | 285.6 | 654.9 | 21.17 | 0.0 | 5.05 | 13.65 | 15.12 | Au1rxx-base64 | 156.146.38.169 |
| 66.38 | shadowsocks | 283.8 | 647.8 | 21.21 | 0.0 | 8.42 | 13.65 | 15.12 | Au1rxx-base64 | 156.146.38.170 |
| 65.9 | hysteria2 | 387.4 | 333.5 | 18.81 | 2.49 | 8.67 | 13.0 | 15.12 | Au1rxx-base64 | 38.175.202.26 |
| 65.59 | hysteria2 | 272.6 | 686.0 | 21.47 | 0.0 | 0.0 | 13.0 | 15.12 | Au1rxx-base64 | clash2.deep-links.com |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.965 | 0.971 | 34 | 523 | prefer |
| zhangkai | 0.93 | 0.962 | 26 | 31 | prefer |
| Surfboard-tg-mixed | 0.88 | 0.811 | 53 | 7097 | prefer |
| Au1rxx-base64 | 0.791 | 0.73 | 222 | 1587 | prefer |
| mheidari-all | 0.707 | 0.628 | 215 | 24252 | prefer |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 92 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4925 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 4067 | observe |
| Epodonios-all | 0.255 | None | 0 | 7591 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10124 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5559 | observe |
| barry-far-vless | 0.255 | None | 0 | 5773 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4164 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 84 |
| speed | ClientOSError | - | 36 |
| geo | ClientOSError | - | 12 |
| cn-block | ClientOSError | - | 7 |
| 204 | ProxyError | - | 4 |
| cn-block | TimeoutError | - | 4 |
| 204 | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 97 | 84 | - |
| global | False | 104 | 92 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
