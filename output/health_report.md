# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-03 23:06:42 |
| 运行耗时 | 409.1s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 128813 |
| 去重后节点 | 58756 |
| TCP 可达 | 3000 |
| 真实可用 | 73 |
| Verified 输出 | 73 |
| Global 输出 | 75 |
| All 输出 | 58756 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.7 |
| tcp | 207.7 |
| probe | 101.0 |
| real_test | 40.2 |
| china_check | 24.9 |
| write_verified | 0.0 |
| generate | 25.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 78802 |
| vmess | 17768 |
| trojan | 16241 |
| shadowsocks | 13125 |
| hysteria2 | 2283 |
| shadowsocksr | 236 |
| socks | 109 |
| http | 93 |
| hysteria | 66 |
| tuic | 53 |
| anytls | 37 |

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
| 72.93 | hysteria2 | 183.2 | 481.2 | 23.54 | 0.0 | 4.32 | 10.71 | 18.36 | dragon | 67.216.207.144 |
| 72.47 | hysteria2 | 232.5 | 539.0 | 22.4 | 0.0 | 2.1 | 10.71 | 18.36 | dragon | 66.94.121.46 |
| 72.46 | shadowsocks | 277.2 | 705.2 | 21.36 | 0.0 | 4.32 | 12.92 | 18.36 | dragon | 103.11.76.248 |
| 72.32 | shadowsocks | 217.8 | 533.0 | 22.74 | 0.0 | 2.3 | 12.92 | 18.36 | dragon | 173.244.56.6 |
| 72.16 | shadowsocks | 203.1 | 531.0 | 23.08 | 0.0 | 2.3 | 12.92 | 18.36 | dragon | 95.215.201.18 |
| 71.46 | shadowsocks | 209.0 | 477.3 | 22.94 | 0.0 | 4.74 | 12.92 | 18.36 | dragon | 169.197.142.68 |
| 70.54 | shadowsocks | 294.7 | 764.6 | 20.96 | 0.0 | 2.3 | 12.92 | 18.36 | dragon | 173.244.56.9 |
| 70.46 | shadowsocks | 242.7 | 584.7 | 22.16 | 0.0 | 4.52 | 12.92 | 18.36 | dragon | 137.184.89.151 |
| 69.83 | shadowsocks | 268.9 | 724.1 | 21.55 | 0.0 | 4.5 | 12.92 | 18.36 | dragon | 23.150.152.38 |
| 68.48 | shadowsocks | 264.6 | 634.8 | 21.65 | 0.0 | 0.0 | 12.92 | 18.36 | dragon | 156.146.38.169 |
| 68.14 | shadowsocks | 208.2 | 514.3 | 22.96 | 0.0 | 0.0 | 12.92 | 18.36 | dragon | 96.45.186.114 |
| 67.4 | hysteria2 | 277.2 | 620.8 | 21.36 | 0.0 | 0.0 | 10.71 | 18.36 | dragon | 88.216.195.188 |
| 67.39 | shadowsocks | 267.0 | 642.1 | 21.6 | 0.0 | 0.0 | 12.92 | 18.36 | dragon | 156.146.38.167 |
| 67.05 | http | 324.0 | 735.7 | 20.28 | 0.0 | 0.0 | 14.29 | 18.24 | ermaozi | 38.247.141.135 |
| 66.1 | shadowsocks | 193.2 | 506.0 | 23.31 | 0.0 | 3.2 | 12.92 | 18.36 | dragon | 38.145.220.193 |
| 66.1 | trojan | 416.1 | 864.5 | 18.14 | 0.0 | 5.62 | 12.8 | 18.36 | dragon | 170.101.101.53 |
| 66.07 | shadowsocks | 263.6 | 629.8 | 21.68 | 0.0 | 0.0 | 12.92 | 18.36 | dragon | 156.146.38.170 |
| 65.91 | shadowsocks | 291.6 | 630.0 | 21.03 | 0.0 | 1.98 | 12.92 | 18.36 | dragon | 149.22.95.183 |
| 65.85 | shadowsocks | 370.0 | 929.4 | 19.21 | 0.0 | 3.5 | 12.92 | 18.36 | dragon | 167.88.62.56 |
| 65.18 | hysteria2 | 237.3 | 241.1 | 22.28 | 5.96 | 0.0 | 10.71 | 18.36 | dragon | 8.209.247.109 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.999 | 0.922 | 293 | 45574 | prefer |
| ermaozi | 0.945 | 1.0 | 19 | 592 | prefer |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8582 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 115 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5017 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2526 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10841 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6047 | observe |
| barry-far-vless | 0.255 | None | 0 | 6260 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4753 | observe |
| mheidari-all | 0.255 | None | 0 | 15211 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| geo | ClientOSError | - | 7 |
| test_one_timeout | 15.0s | - | 6 |
| 204 | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| cn-block | TimeoutError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 64 | 73 | - |
| global | False | 65 | 75 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
