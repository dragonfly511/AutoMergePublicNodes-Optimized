# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-07 12:45:44 |
| 运行耗时 | 384.6s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 127486 |
| 去重后节点 | 59098 |
| TCP 可达 | 3000 |
| 真实可用 | 79 |
| Verified 输出 | 79 |
| Global 输出 | 80 |
| All 输出 | 59098 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.6 |
| tcp | 196.2 |
| probe | 94.8 |
| real_test | 42.5 |
| china_check | 24.9 |
| write_verified | 0.0 |
| generate | 19.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 78240 |
| vmess | 18409 |
| trojan | 14514 |
| shadowsocks | 13377 |
| hysteria2 | 2314 |
| shadowsocksr | 232 |
| http | 132 |
| socks | 114 |
| hysteria | 57 |
| tuic | 56 |
| anytls | 41 |

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
| 78.58 | trojan | 221.1 | 590.4 | 22.66 | 0.0 | 5.45 | 12.99 | 19.98 | dragon | 216.152.155.176 |
| 78.27 | hysteria2 | 268.7 | 776.6 | 21.56 | 0.0 | 3.8 | 13.93 | 19.98 | dragon | 88.216.195.188 |
| 77.58 | trojan | 204.1 | 584.7 | 23.05 | 0.0 | 4.06 | 12.99 | 19.98 | dragon | 216.152.155.131 |
| 77.32 | trojan | 326.0 | 871.1 | 20.23 | 0.0 | 6.62 | 12.99 | 19.98 | dragon | 170.101.101.67 |
| 76.39 | trojan | 247.8 | 636.0 | 22.04 | 0.0 | 6.88 | 12.99 | 19.98 | dragon | 170.101.101.19 |
| 75.69 | trojan | 275.2 | 541.1 | 21.41 | 0.0 | 6.29 | 12.99 | 19.98 | dragon | 216.152.155.54 |
| 75.44 | shadowsocks | 342.0 | 891.1 | 19.86 | 0.0 | 6.02 | 14.08 | 19.98 | dragon | 158.51.121.221 |
| 75.26 | trojan | 237.7 | 606.5 | 22.28 | 0.0 | 5.88 | 12.99 | 19.98 | dragon | 170.101.101.131 |
| 74.96 | trojan | 332.0 | 821.2 | 20.09 | 0.0 | 6.37 | 12.99 | 19.98 | dragon | 66.163.122.46 |
| 74.95 | trojan | 344.3 | 815.2 | 19.81 | 0.0 | 6.45 | 12.99 | 19.98 | dragon | 169.197.140.171 |
| 74.59 | shadowsocks | 271.2 | 646.9 | 21.5 | 0.0 | 3.53 | 14.08 | 19.98 | dragon | 38.22.17.214 |
| 74.59 | trojan | 293.9 | 656.8 | 20.97 | 0.0 | 4.0 | 12.99 | 19.98 | dragon | 216.152.156.212 |
| 74.52 | trojan | 314.7 | 827.3 | 20.49 | 0.0 | 6.56 | 12.99 | 19.98 | dragon | 170.101.101.53 |
| 74.49 | trojan | 283.3 | 656.7 | 21.22 | 0.0 | 3.81 | 12.99 | 19.98 | dragon | 216.152.156.65 |
| 74.45 | trojan | 462.7 | 598.5 | 17.07 | 0.0 | 6.91 | 12.99 | 19.98 | dragon | 216.152.155.23 |
| 74.31 | trojan | 257.5 | 610.3 | 21.82 | 0.0 | 7.02 | 12.99 | 19.98 | dragon | 66.163.114.45 |
| 74.22 | trojan | 241.9 | 626.2 | 22.18 | 0.0 | 4.57 | 12.99 | 19.98 | dragon | 170.101.101.211 |
| 73.96 | hysteria2 | 334.3 | 785.3 | 20.04 | 0.0 | 3.18 | 13.93 | 19.98 | dragon | 66.94.121.46 |
| 73.7 | shadowsocks | 334.9 | 728.0 | 20.03 | 0.0 | 7.11 | 14.08 | 19.98 | dragon | 88.216.254.18 |
| 73.69 | trojan | 383.2 | 935.5 | 18.91 | 0.0 | 6.6 | 12.99 | 19.98 | dragon | 169.197.140.214 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.949 | 0.872 | 289 | 45178 | prefer |
| ermaozi | 0.934 | 0.952 | 21 | 515 | prefer |
| mheidari-all | 0.287 | 0.5 | 2 | 14331 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4866 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2734 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11009 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8637 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6148 | observe |
| barry-far-vless | 0.255 | None | 0 | 6359 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4522 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 22 |
| 204 | ProxyError | - | 10 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 89 | 79 | - |
| global | False | 92 | 80 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
