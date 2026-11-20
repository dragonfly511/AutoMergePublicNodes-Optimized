# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-20 06:25:31 |
| 运行耗时 | 415.6s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 127466 |
| 去重后节点 | 59583 |
| TCP 可达 | 3000 |
| 真实可用 | 85 |
| Verified 输出 | 85 |
| Global 输出 | 91 |
| All 输出 | 59583 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.7 |
| tcp | 197.6 |
| probe | 109.3 |
| real_test | 43.4 |
| china_check | 33.2 |
| write_verified | 0.0 |
| generate | 24.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77021 |
| vmess | 19032 |
| trojan | 14241 |
| shadowsocks | 14238 |
| hysteria2 | 2145 |
| shadowsocksr | 372 |
| socks | 150 |
| http | 130 |
| hysteria | 55 |
| tuic | 54 |
| anytls | 28 |

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
| 72.08 | http | 250.4 | 611.1 | 21.98 | 0.0 | 0.0 | 13.8 | 18.8 | ermaozi | 172.64.69.89 |
| 71.5 | http | 275.4 | 668.1 | 21.4 | 0.0 | 0.0 | 13.8 | 18.8 | ermaozi | 172.64.68.89 |
| 70.88 | hysteria2 | 386.4 | 1009.4 | 18.83 | 0.0 | 10.0 | 12.69 | 10.36 | dragon | 206.189.229.48 |
| 68.02 | hysteria2 | 421.8 | 1048.5 | 18.01 | 0.0 | 10.0 | 12.69 | 10.36 | dragon | 34.24.25.1 |
| 66.13 | shadowsocks | 306.6 | 811.7 | 20.68 | 0.0 | 7.09 | 12.5 | 10.36 | dragon | 167.88.62.203 |
| 65.88 | http | 404.2 | 950.8 | 18.42 | 0.0 | 0.0 | 13.8 | 18.8 | ermaozi | 38.247.141.135 |
| 64.04 | shadowsocks | 350.0 | 862.4 | 19.68 | 0.0 | 7.18 | 12.5 | 10.36 | dragon | 167.17.67.171 |
| 63.18 | http | 426.7 | 992.1 | 17.9 | 0.0 | 0.0 | 13.8 | 18.8 | ermaozi | 38.95.111.226 |
| 62.65 | shadowsocks | 351.0 | 762.8 | 19.65 | 0.0 | 7.13 | 12.5 | 10.36 | dragon | 193.151.160.9 |
| 62.52 | shadowsocks | 257.0 | 551.5 | 21.83 | 0.0 | 4.52 | 12.5 | 10.36 | dragon | 38.145.220.193 |
| 62.49 | shadowsocks | 252.2 | 542.8 | 21.94 | 0.0 | 4.52 | 12.5 | 10.36 | dragon | 104.238.140.45 |
| 62.33 | shadowsocks | 328.7 | 842.8 | 20.17 | 0.0 | 4.8 | 12.5 | 10.36 | dragon | 38.64.138.135 |
| 62.06 | shadowsocks | 335.1 | 715.8 | 20.02 | 0.0 | 7.14 | 12.5 | 10.36 | dragon | 193.151.160.18 |
| 61.6 | shadowsocks | 318.1 | 718.3 | 20.41 | 0.0 | 7.14 | 12.5 | 10.36 | dragon | 193.151.163.18 |
| 61.58 | shadowsocks | 466.3 | 1233.0 | 16.98 | 0.0 | 7.14 | 12.5 | 10.36 | dragon | 37.19.198.236 |
| 61.48 | shadowsocks | 307.9 | 623.9 | 20.65 | 0.0 | 6.81 | 12.5 | 10.36 | dragon | 95.215.201.18 |
| 61.45 | http | 608.2 | 1593.5 | 13.7 | 0.0 | 0.0 | 13.8 | 18.8 | ermaozi | 149.88.21.129 |
| 61.26 | shadowsocks | 452.7 | 1205.4 | 17.3 | 0.0 | 7.14 | 12.5 | 10.36 | dragon | 37.19.198.160 |
| 61.22 | shadowsocks | 312.1 | 635.2 | 20.55 | 0.0 | 6.75 | 12.5 | 10.36 | dragon | 149.22.95.183 |
| 61.21 | shadowsocks | 336.9 | 874.5 | 19.98 | 0.0 | 7.07 | 12.5 | 10.36 | dragon | 38.128.66.32 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.98 | 1.0 | 24 | 469 | prefer |
| dragon | 0.939 | 0.861 | 288 | 44987 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4935 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2728 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11813 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5726 | observe |
| barry-far-vless | 0.255 | None | 0 | 6117 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4501 | observe |
| mheidari-all | 0.255 | None | 0 | 14360 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 24 |
| cn-block | ClientOSError | - | 6 |
| 204 | TimeoutError | - | 3 |
| cn-block | TimeoutError | - | 3 |
| 204 | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| geo | ClientOSError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 27 | 85 | - |
| global | False | 28 | 91 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
