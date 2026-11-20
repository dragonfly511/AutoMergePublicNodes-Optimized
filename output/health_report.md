# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-20 19:51:55 |
| 运行耗时 | 428.3s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 127838 |
| 去重后节点 | 60003 |
| TCP 可达 | 3000 |
| 真实可用 | 63 |
| Verified 输出 | 63 |
| Global 输出 | 70 |
| All 输出 | 60003 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.6 |
| geo | 1.8 |
| tcp | 196.6 |
| probe | 122.1 |
| real_test | 45.2 |
| china_check | 26.7 |
| write_verified | 0.0 |
| generate | 28.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 76941 |
| vmess | 19085 |
| shadowsocks | 14391 |
| trojan | 14355 |
| hysteria2 | 2190 |
| shadowsocksr | 377 |
| socks | 193 |
| http | 166 |
| hysteria | 59 |
| tuic | 53 |
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
| 78.41 | shadowsocks | 326.7 | 580.9 | 20.22 | 0.0 | 10.0 | 13.41 | 18.78 | dragon | 156.146.38.169 |
| 77.92 | shadowsocks | 347.8 | 879.9 | 19.73 | 0.0 | 10.0 | 13.41 | 18.78 | dragon | 37.19.198.236 |
| 77.91 | shadowsocks | 326.3 | 818.3 | 20.22 | 0.0 | 10.0 | 13.41 | 18.78 | dragon | 185.230.230.18 |
| 77.17 | shadowsocks | 337.0 | 589.6 | 19.98 | 0.0 | 10.0 | 13.41 | 18.78 | dragon | 37.19.198.160 |
| 76.58 | shadowsocks | 332.8 | 740.3 | 20.07 | 0.0 | 10.0 | 13.41 | 18.78 | dragon | 193.151.160.9 |
| 76.35 | shadowsocks | 317.8 | 813.2 | 20.42 | 0.0 | 10.0 | 13.41 | 18.78 | dragon | 172.111.38.72 |
| 76.01 | shadowsocks | 408.5 | 1046.9 | 18.32 | 0.0 | 10.0 | 13.41 | 18.78 | dragon | 167.88.62.203 |
| 75.71 | shadowsocks | 267.7 | 682.3 | 21.58 | 0.0 | 5.94 | 13.41 | 18.78 | dragon | 37.19.198.244 |
| 75.1 | shadowsocks | 344.7 | 718.8 | 19.8 | 0.0 | 10.0 | 13.41 | 18.78 | dragon | 193.151.163.18 |
| 75.02 | shadowsocks | 338.0 | 739.9 | 19.95 | 0.0 | 10.0 | 13.41 | 18.78 | dragon | 193.151.160.18 |
| 74.87 | shadowsocks | 310.7 | 782.1 | 20.59 | 0.0 | 6.72 | 13.41 | 18.78 | dragon | 167.17.67.171 |
| 74.81 | shadowsocks | 460.4 | 1257.1 | 17.12 | 0.0 | 10.0 | 13.41 | 18.78 | dragon | 149.40.57.134 |
| 74.53 | shadowsocks | 342.7 | 873.0 | 19.85 | 0.0 | 6.99 | 13.41 | 18.78 | dragon | 149.40.57.135 |
| 74.24 | shadowsocks | 326.3 | 784.5 | 20.22 | 0.0 | 7.0 | 13.41 | 18.78 | dragon | 15.204.246.111 |
| 74.21 | hysteria2 | 490.3 | 1266.6 | 16.43 | 0.0 | 7.65 | 12.35 | 18.78 | dragon | 34.24.25.1 |
| 73.42 | shadowsocks | 370.6 | 774.2 | 19.2 | 0.0 | 10.0 | 13.41 | 18.78 | dragon | 38.121.43.18 |
| 73.22 | shadowsocks | 304.4 | 705.3 | 20.73 | 0.0 | 6.03 | 13.41 | 18.78 | dragon | 200.102.179.179 |
| 72.76 | shadowsocks | 351.7 | 884.7 | 19.64 | 0.0 | 10.0 | 13.41 | 18.78 | dragon | 37.19.198.243 |
| 72.59 | hysteria2 | 342.0 | 619.8 | 19.86 | 0.0 | 7.66 | 12.35 | 18.78 | dragon | 206.189.229.48 |
| 72.47 | shadowsocks | 377.6 | 768.4 | 19.04 | 0.0 | 10.0 | 13.41 | 18.78 | dragon | 167.88.63.99 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.94 | 0.863 | 240 | 44987 | prefer |
| ermaozi | 0.81 | 0.805 | 41 | 492 | prefer |
| Surfboard-tg-mixed | 0.287 | 0.5 | 2 | 8704 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 130 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5045 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2910 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 12061 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5734 | observe |
| barry-far-vless | 0.255 | None | 0 | 5776 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4501 | observe |
| mheidari-all | 0.255 | None | 0 | 14341 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 20 |
| cn-block | ClientOSError | - | 6 |
| 204 | ProxyError | - | 3 |
| geo | ProxyError | - | 3 |
| speed | ProxyError | - | 3 |
| 204 | TimeoutError | - | 2 |
| cn-block | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 85 | 63 | - |
| global | False | 91 | 70 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
