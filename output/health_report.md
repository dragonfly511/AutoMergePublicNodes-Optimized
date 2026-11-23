# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-23 23:40:54 |
| 运行耗时 | 406.1s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 123932 |
| 去重后节点 | 58855 |
| TCP 可达 | 3000 |
| 真实可用 | 61 |
| Verified 输出 | 61 |
| Global 输出 | 65 |
| All 输出 | 58855 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.0 |
| geo | 1.7 |
| tcp | 203.6 |
| probe | 98.2 |
| real_test | 41.6 |
| china_check | 29.5 |
| write_verified | 0.0 |
| generate | 24.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 75593 |
| vmess | 19499 |
| shadowsocks | 13450 |
| trojan | 12292 |
| hysteria2 | 2340 |
| shadowsocksr | 274 |
| socks | 189 |
| http | 121 |
| hysteria | 71 |
| tuic | 52 |
| anytls | 51 |

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
| 77.01 | shadowsocks | 247.5 | 647.8 | 22.05 | 0.0 | 9.44 | 13.24 | 16.28 | dragon | 156.146.38.168 |
| 74.71 | shadowsocks | 335.5 | 905.6 | 20.01 | 0.0 | 9.18 | 13.24 | 16.28 | dragon | 156.146.38.169 |
| 73.94 | shadowsocks | 319.6 | 740.6 | 20.38 | 0.0 | 8.54 | 13.24 | 16.28 | dragon | 185.230.230.18 |
| 72.43 | shadowsocks | 305.6 | 685.6 | 20.7 | 0.0 | 9.18 | 13.24 | 16.28 | dragon | 137.184.89.151 |
| 71.63 | shadowsocks | 252.8 | 647.7 | 21.93 | 0.0 | 9.18 | 13.24 | 16.28 | dragon | 156.146.38.170 |
| 71.12 | shadowsocks | 283.4 | 599.2 | 21.22 | 0.0 | 8.59 | 13.24 | 16.28 | dragon | 95.215.201.18 |
| 70.77 | shadowsocks | 308.4 | 684.8 | 20.64 | 0.0 | 8.78 | 13.24 | 16.28 | dragon | 193.151.163.18 |
| 70.7 | shadowsocks | 311.1 | 691.1 | 20.58 | 0.0 | 8.32 | 13.24 | 16.28 | dragon | 200.102.179.179 |
| 70.46 | shadowsocks | 312.8 | 751.5 | 20.54 | 0.0 | 9.25 | 13.24 | 16.28 | dragon | 172.111.38.72 |
| 70.04 | shadowsocks | 309.8 | 830.1 | 20.61 | 0.0 | 9.11 | 13.24 | 16.28 | dragon | 216.106.178.169 |
| 70.04 | shadowsocks | 340.2 | 775.0 | 19.9 | 0.0 | 8.89 | 13.24 | 16.28 | dragon | 23.150.152.38 |
| 69.8 | shadowsocks | 388.9 | 951.5 | 18.78 | 0.0 | 8.9 | 13.24 | 16.28 | dragon | 149.40.57.134 |
| 69.59 | http | 349.7 | 906.7 | 19.68 | 0.0 | 0.0 | 13.87 | 18.54 | ermaozi | 172.64.68.89 |
| 69.46 | shadowsocks | 392.1 | 954.6 | 18.7 | 0.0 | 8.96 | 13.24 | 16.28 | dragon | 149.40.57.133 |
| 69.43 | shadowsocks | 408.2 | 1018.6 | 18.33 | 0.0 | 8.35 | 13.24 | 16.28 | dragon | 15.204.246.111 |
| 69.36 | shadowsocks | 324.1 | 715.7 | 20.28 | 0.0 | 7.4 | 13.24 | 16.28 | dragon | 15.204.247.206 |
| 69.23 | shadowsocks | 360.9 | 751.8 | 19.42 | 0.0 | 8.55 | 13.24 | 16.28 | dragon | 193.151.160.9 |
| 69.19 | shadowsocks | 382.6 | 848.2 | 18.92 | 0.0 | 7.85 | 13.24 | 16.28 | dragon | 15.204.247.244 |
| 69.03 | shadowsocks | 391.1 | 846.4 | 18.72 | 0.0 | 9.0 | 13.24 | 16.28 | dragon | 167.88.63.99 |
| 69.03 | shadowsocks | 426.7 | 1051.9 | 17.9 | 0.0 | 8.55 | 13.24 | 16.28 | dragon | 45.86.51.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.931 | 290 | 43774 | prefer |
| ermaozi | 0.982 | 1.0 | 27 | 420 | prefer |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 8626 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5064 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11748 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5667 | observe |
| barry-far-vless | 0.255 | None | 0 | 5847 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4514 | observe |
| mheidari-all | 0.255 | None | 0 | 15543 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 9 |
| cn-block | ClientOSError | - | 4 |
| 204 | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:49734: bind: address already in use | - | 1 |
| 204 | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 69 | 61 | - |
| global | False | 69 | 65 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
