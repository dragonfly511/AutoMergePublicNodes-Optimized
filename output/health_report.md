# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-23 06:48:50 |
| 运行耗时 | 318.4s |
| 订阅源总数 | 108 |
| 健康订阅源 | 92 |
| 原始节点 | 96274 |
| 去重后节点 | 26716 |
| TCP 可达 | 3000 |
| 真实可用 | 133 |
| Verified 输出 | 133 |
| Global 输出 | 138 |
| All 输出 | 26716 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.8 |
| tcp | 84.6 |
| probe | 100.8 |
| real_test | 84.9 |
| china_check | 25.7 |
| write_verified | 0.1 |
| generate | 13.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57043 |
| vmess | 17178 |
| shadowsocks | 12318 |
| trojan | 7846 |
| hysteria2 | 1348 |
| http | 338 |
| shadowsocksr | 96 |
| socks | 59 |
| anytls | 25 |
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
| 76.62 | hysteria2 | 267.9 | 681.6 | 21.58 | 0.0 | 10.0 | 13.42 | 16.12 | Au1rxx-base64 | 129.213.91.185 |
| 76.39 | shadowsocks | 265.4 | 684.6 | 21.64 | 0.0 | 10.0 | 12.63 | 16.12 | Au1rxx-base64 | 156.146.38.167 |
| 74.59 | shadowsocks | 319.4 | 789.0 | 20.38 | 0.0 | 10.0 | 12.63 | 16.12 | Au1rxx-base64 | 37.19.198.160 |
| 74.49 | shadowsocks | 302.6 | 728.6 | 20.77 | 0.0 | 10.0 | 12.63 | 16.12 | Au1rxx-base64 | 37.19.198.244 |
| 74.26 | shadowsocks | 334.9 | 832.5 | 20.03 | 0.0 | 10.0 | 12.63 | 16.12 | Au1rxx-base64 | 37.19.198.236 |
| 72.5 | shadowsocks | 366.9 | 935.2 | 19.28 | 0.0 | 10.0 | 12.63 | 16.12 | Au1rxx-base64 | 185.215.132.9 |
| 72.33 | shadowsocks | 305.8 | 708.1 | 20.7 | 0.0 | 10.0 | 12.63 | 16.12 | Au1rxx-base64 | 185.230.230.18 |
| 70.69 | shadowsocks | 385.8 | 956.7 | 18.85 | 0.0 | 10.0 | 12.63 | 16.12 | Au1rxx-base64 | 45.86.51.18 |
| 70.6 | vless | 343.0 | 731.2 | 19.84 | 0.0 | 9.74 | 8.31 | 16.12 | Au1rxx-base64 | 66.70.179.198 |
| 70.32 | vless | 329.7 | 694.8 | 20.15 | 0.0 | 10.0 | 8.31 | 16.12 | Au1rxx-base64 | 144.202.126.147 |
| 70.16 | hysteria2 | 274.3 | 679.6 | 21.43 | 0.0 | 0.19 | 13.42 | 16.12 | Au1rxx-base64 | clash2.deep-links.com |
| 70.09 | shadowsocks | 386.3 | 963.9 | 18.84 | 0.0 | 10.0 | 12.63 | 16.12 | Au1rxx-base64 | 15.204.233.41 |
| 69.88 | shadowsocks | 336.3 | 561.7 | 19.99 | 0.0 | 10.0 | 12.63 | 16.12 | Au1rxx-base64 | 173.244.56.9 |
| 69.57 | http | 348.1 | 907.8 | 19.72 | 0.0 | 0.0 | 14.2 | 19.38 | ermaozi | 121.127.34.82 |
| 69.42 | http | 407.8 | 1017.7 | 18.34 | 0.0 | 0.0 | 14.2 | 19.38 | ermaozi | 12.202.180.118 |
| 69.24 | shadowsocks | 386.7 | 896.8 | 18.83 | 0.0 | 10.0 | 12.63 | 16.12 | Au1rxx-base64 | 95.215.201.18 |
| 68.93 | shadowsocks | 259.7 | 642.3 | 21.77 | 0.0 | 10.0 | 12.63 | 16.12 | Au1rxx-base64 | 156.146.38.170 |
| 68.93 | shadowsocks | 417.2 | 1014.4 | 18.12 | 0.0 | 10.0 | 12.63 | 16.12 | Au1rxx-base64 | 193.151.160.9 |
| 68.74 | http | 300.7 | 641.4 | 20.82 | 0.0 | 0.0 | 14.2 | 19.38 | ermaozi | 64.98.50.100 |
| 68.64 | http | 324.5 | 723.8 | 20.27 | 0.0 | 0.0 | 14.2 | 19.38 | ermaozi | 38.247.141.135 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | 1.0 | 99 | 609 | prefer |
| Surfboard-tg-mixed | 0.865 | 0.794 | 63 | 6999 | prefer |
| Au1rxx-base64 | 0.765 | 0.705 | 207 | 1533 | prefer |
| mheidari-all | 0.673 | 0.594 | 165 | 23958 | observe |
| ninja-vless | 0.34 | 0.667 | 3 | 1791 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4911 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3641 | observe |
| Epodonios-all | 0.255 | None | 0 | 7509 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10117 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5447 | observe |
| barry-far-vless | 0.255 | None | 0 | 5666 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4230 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.236 | None | 0 | 1533 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 96 |
| speed | ClientOSError | - | 20 |
| geo | ClientOSError | - | 10 |
| cn-block | ClientOSError | - | 4 |
| 204 | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:40248: bind: address already in use | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 98 | 133 | - |
| global | False | 104 | 138 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
