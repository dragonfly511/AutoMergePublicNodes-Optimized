# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-22 23:30:31 |
| 运行耗时 | 405.1s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 126801 |
| 去重后节点 | 58875 |
| TCP 可达 | 3000 |
| 真实可用 | 100 |
| Verified 输出 | 100 |
| Global 输出 | 100 |
| All 输出 | 58875 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.1 |
| geo | 1.7 |
| tcp | 196.5 |
| probe | 93.4 |
| real_test | 53.4 |
| china_check | 33.7 |
| write_verified | 0.0 |
| generate | 20.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 76278 |
| vmess | 19548 |
| shadowsocks | 14618 |
| trojan | 13217 |
| hysteria2 | 2350 |
| shadowsocksr | 282 |
| socks | 206 |
| http | 138 |
| hysteria | 71 |
| tuic | 57 |
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
| 79.17 | shadowsocks | 239.5 | 617.7 | 22.23 | 0.0 | 9.33 | 12.91 | 18.7 | dragon | 156.146.38.169 |
| 75.7 | shadowsocks | 335.5 | 835.0 | 20.01 | 0.0 | 9.18 | 12.91 | 18.7 | dragon | 37.19.198.243 |
| 75.68 | shadowsocks | 346.6 | 939.1 | 19.75 | 0.0 | 9.32 | 12.91 | 18.7 | dragon | 156.146.38.168 |
| 75.49 | shadowsocks | 241.6 | 516.3 | 22.19 | 0.0 | 9.06 | 12.91 | 18.7 | dragon | 137.184.89.151 |
| 74.61 | shadowsocks | 322.7 | 654.7 | 20.31 | 0.0 | 8.08 | 12.91 | 18.7 | dragon | 45.86.51.18 |
| 74.37 | shadowsocks | 325.5 | 770.2 | 20.24 | 0.0 | 8.15 | 12.91 | 18.7 | dragon | 185.230.230.18 |
| 73.8 | shadowsocks | 305.9 | 686.8 | 20.7 | 0.0 | 9.03 | 12.91 | 18.7 | dragon | 149.40.57.134 |
| 73.54 | shadowsocks | 323.6 | 697.5 | 20.29 | 0.0 | 8.93 | 12.91 | 18.7 | dragon | 200.102.179.179 |
| 73.18 | shadowsocks | 305.0 | 590.7 | 20.72 | 0.0 | 8.99 | 12.91 | 18.7 | dragon | 173.244.56.6 |
| 73.03 | shadowsocks | 303.9 | 661.6 | 20.74 | 0.0 | 8.17 | 12.91 | 18.7 | dragon | 95.215.201.18 |
| 72.87 | shadowsocks | 364.2 | 861.5 | 19.35 | 0.0 | 8.93 | 12.91 | 18.7 | dragon | 15.204.247.244 |
| 72.79 | shadowsocks | 305.2 | 709.3 | 20.71 | 0.0 | 8.4 | 12.91 | 18.7 | dragon | 193.151.163.18 |
| 72.59 | http | 283.7 | 680.3 | 21.21 | 0.0 | 0.0 | 14.38 | 19.5 | ermaozi | 172.64.68.89 |
| 72.3 | http | 252.8 | 608.9 | 21.92 | 0.0 | 0.0 | 14.38 | 19.5 | ermaozi | 172.64.69.89 |
| 72.21 | shadowsocks | 353.2 | 836.7 | 19.6 | 0.0 | 9.03 | 12.91 | 18.7 | dragon | 149.40.57.138 |
| 72.02 | shadowsocks | 384.2 | 933.1 | 18.88 | 0.0 | 9.03 | 12.91 | 18.7 | dragon | 172.111.38.72 |
| 71.95 | shadowsocks | 365.3 | 869.2 | 19.32 | 0.0 | 9.03 | 12.91 | 18.7 | dragon | 38.91.100.39 |
| 71.84 | shadowsocks | 391.3 | 840.0 | 18.72 | 0.0 | 9.16 | 12.91 | 18.7 | dragon | 38.22.17.129 |
| 71.79 | shadowsocks | 351.3 | 731.0 | 19.65 | 0.0 | 8.5 | 12.91 | 18.7 | dragon | 193.151.160.18 |
| 71.33 | shadowsocks | 376.6 | 786.9 | 19.06 | 0.0 | 9.19 | 12.91 | 18.7 | dragon | 38.121.43.225 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.931 | 334 | 43774 | prefer |
| ermaozi | 0.937 | 0.957 | 23 | 415 | prefer |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 8701 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5069 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2671 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11823 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5650 | observe |
| barry-far-vless | 0.255 | None | 0 | 5844 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4512 | observe |
| mheidari-all | 0.255 | None | 0 | 15428 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 13 |
| 204 | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ClientOSError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 110 | 100 | - |
| global | False | 114 | 100 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
