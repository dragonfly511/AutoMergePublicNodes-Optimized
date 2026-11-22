# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-22 14:23:12 |
| 运行耗时 | 408.4s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 127276 |
| 去重后节点 | 59401 |
| TCP 可达 | 3000 |
| 真实可用 | 110 |
| Verified 输出 | 110 |
| Global 输出 | 114 |
| All 输出 | 59401 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.7 |
| tcp | 200.6 |
| probe | 107.5 |
| real_test | 42.0 |
| china_check | 27.4 |
| write_verified | 0.0 |
| generate | 22.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 76929 |
| vmess | 19332 |
| shadowsocks | 14524 |
| trojan | 13542 |
| hysteria2 | 2102 |
| shadowsocksr | 372 |
| socks | 175 |
| http | 141 |
| hysteria | 73 |
| tuic | 57 |
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
| 70.89 | shadowsocks | 243.2 | 627.4 | 22.15 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 156.146.38.169 |
| 69.67 | http | 298.5 | 761.8 | 20.87 | 0.0 | 0.0 | 14.06 | 17.24 | ermaozi | 172.64.68.89 |
| 68.82 | shadowsocks | 278.6 | 662.6 | 21.33 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 37.19.198.244 |
| 68.79 | shadowsocks | 312.2 | 816.9 | 20.55 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 167.17.67.171 |
| 68.33 | shadowsocks | 332.1 | 897.1 | 20.09 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 167.88.62.56 |
| 68.2 | shadowsocks | 247.3 | 576.3 | 22.05 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 67.220.73.178 |
| 68.05 | hysteria2 | 405.8 | 673.7 | 18.38 | 0.0 | 6.99 | 12.0 | 19.12 | dragon | 172.87.24.53 |
| 68.04 | shadowsocks | 344.7 | 903.8 | 19.8 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 167.88.62.203 |
| 67.5 | http | 305.7 | 782.8 | 20.7 | 0.0 | 0.0 | 14.06 | 17.24 | ermaozi | 172.64.69.89 |
| 66.68 | shadowsocks | 312.6 | 720.5 | 20.54 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 185.230.230.18 |
| 66.61 | shadowsocks | 294.7 | 702.6 | 20.96 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 45.86.51.18 |
| 66.56 | shadowsocks | 317.3 | 710.2 | 20.43 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 15.204.246.108 |
| 66.56 | shadowsocks | 343.7 | 920.5 | 19.82 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 156.146.38.168 |
| 66.12 | shadowsocks | 358.0 | 806.7 | 19.49 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 200.102.179.179 |
| 65.99 | shadowsocks | 311.6 | 669.7 | 20.56 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 185.215.132.9 |
| 65.98 | shadowsocks | 352.8 | 630.0 | 19.61 | 0.0 | 2.61 | 13.62 | 19.12 | dragon | 149.22.95.183 |
| 65.83 | shadowsocks | 314.6 | 732.7 | 20.49 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 149.40.57.135 |
| 65.8 | shadowsocks | 278.2 | 582.7 | 21.34 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 95.215.201.18 |
| 65.5 | shadowsocks | 282.6 | 624.1 | 21.24 | 0.0 | 5.36 | 13.62 | 19.12 | dragon | 67.220.73.247 |
| 65.49 | shadowsocks | 304.4 | 655.4 | 20.73 | 0.0 | 0.0 | 13.62 | 19.12 | dragon | 137.184.89.151 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.975 | 1.0 | 22 | 415 | prefer |
| dragon | 0.935 | 0.858 | 232 | 44788 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5069 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2671 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11909 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8766 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5701 | observe |
| barry-far-vless | 0.255 | None | 0 | 5881 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4512 | observe |
| mheidari-all | 0.255 | None | 0 | 14453 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 18 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyError | - | 3 |
| speed | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 91 | 110 | - |
| global | False | 95 | 114 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
