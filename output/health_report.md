# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-18 15:26:09 |
| 运行耗时 | 402.4s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 126477 |
| 去重后节点 | 58450 |
| TCP 可达 | 3000 |
| 真实可用 | 123 |
| Verified 输出 | 123 |
| Global 输出 | 125 |
| All 输出 | 58450 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.7 |
| tcp | 198.4 |
| probe | 100.8 |
| real_test | 44.5 |
| china_check | 30.3 |
| write_verified | 0.0 |
| generate | 20.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77041 |
| vmess | 18870 |
| shadowsocks | 14286 |
| trojan | 13583 |
| hysteria2 | 2070 |
| shadowsocksr | 238 |
| socks | 142 |
| http | 113 |
| hysteria | 53 |
| tuic | 52 |
| anytls | 29 |

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
| 75.51 | shadowsocks | 224.6 | 546.1 | 22.58 | 0.0 | 3.42 | 14.26 | 19.92 | dragon | 38.128.66.32 |
| 75.29 | shadowsocks | 239.9 | 591.3 | 22.22 | 0.0 | 3.39 | 14.26 | 19.92 | dragon | 167.88.62.56 |
| 73.21 | shadowsocks | 294.1 | 697.1 | 20.97 | 0.0 | 3.18 | 14.26 | 19.92 | dragon | 185.230.230.18 |
| 72.89 | shadowsocks | 343.4 | 936.0 | 19.83 | 0.0 | 3.38 | 14.26 | 19.92 | dragon | 167.17.67.171 |
| 71.72 | shadowsocks | 311.1 | 733.0 | 20.58 | 0.0 | 3.13 | 14.26 | 19.92 | dragon | 172.111.38.72 |
| 71.39 | shadowsocks | 306.3 | 739.5 | 20.69 | 0.0 | 3.17 | 14.26 | 19.92 | dragon | 37.19.198.244 |
| 71.3 | shadowsocks | 314.0 | 711.7 | 20.51 | 0.0 | 5.17 | 14.26 | 19.92 | dragon | 185.215.132.9 |
| 70.65 | shadowsocks | 319.6 | 692.1 | 20.38 | 0.0 | 3.39 | 14.26 | 19.92 | dragon | 193.151.163.18 |
| 70.51 | shadowsocks | 305.6 | 684.0 | 20.7 | 0.0 | 2.87 | 14.26 | 19.92 | dragon | 185.215.132.18 |
| 70.49 | shadowsocks | 306.4 | 690.9 | 20.68 | 0.0 | 3.11 | 14.26 | 19.92 | dragon | 38.145.220.193 |
| 70.49 | shadowsocks | 312.0 | 712.8 | 20.56 | 0.0 | 3.12 | 14.26 | 19.92 | dragon | 45.86.51.18 |
| 70.26 | hysteria2 | 288.7 | 690.6 | 21.1 | 0.0 | 0.0 | 13.93 | 19.92 | dragon | 206.189.229.48 |
| 70.05 | shadowsocks | 353.2 | 795.4 | 19.6 | 0.0 | 3.23 | 14.26 | 19.92 | dragon | 15.204.247.206 |
| 70.02 | shadowsocks | 244.3 | 511.9 | 22.12 | 0.0 | 3.17 | 14.26 | 19.92 | dragon | 104.238.140.45 |
| 69.85 | shadowsocks | 355.0 | 799.4 | 19.56 | 0.0 | 3.48 | 14.26 | 19.92 | dragon | 15.204.246.111 |
| 69.58 | shadowsocks | 330.4 | 744.2 | 20.13 | 0.0 | 2.98 | 14.26 | 19.92 | dragon | 38.91.107.57 |
| 69.52 | shadowsocks | 406.1 | 958.7 | 18.38 | 0.0 | 3.0 | 14.26 | 19.92 | dragon | 15.204.233.41 |
| 69.49 | shadowsocks | 279.6 | 585.7 | 21.3 | 0.0 | 2.91 | 14.26 | 19.92 | dragon | 137.184.89.151 |
| 69.47 | shadowsocks | 301.5 | 606.0 | 20.8 | 0.0 | 2.99 | 14.26 | 19.92 | dragon | 95.215.201.18 |
| 69.46 | shadowsocks | 314.4 | 746.8 | 20.5 | 0.0 | 3.25 | 14.26 | 19.92 | dragon | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.98 | 0.903 | 258 | 44296 | prefer |
| ermaozi | 0.89 | 0.905 | 21 | 508 | prefer |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 116 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4919 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2925 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11560 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5766 | observe |
| barry-far-vless | 0.255 | None | 0 | 5946 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4458 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 19 |
| 204 | ProxyError | - | 2 |
| 204 | TimeoutError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| 204 | ClientOSError | - | 1 |
| speed | TimeoutError | - | 1 |
| cn-block | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 86 | 123 | - |
| global | False | 87 | 125 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
