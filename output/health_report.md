# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-04 23:29:47 |
| 运行耗时 | 409.2s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 126866 |
| 去重后节点 | 58024 |
| TCP 可达 | 3000 |
| 真实可用 | 50 |
| Verified 输出 | 50 |
| Global 输出 | 52 |
| All 输出 | 58024 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.8 |
| tcp | 198.0 |
| probe | 102.9 |
| real_test | 42.2 |
| china_check | 34.6 |
| write_verified | 0.0 |
| generate | 23.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77462 |
| vmess | 18213 |
| trojan | 14918 |
| shadowsocks | 13331 |
| hysteria2 | 2361 |
| shadowsocksr | 230 |
| socks | 110 |
| http | 77 |
| hysteria | 71 |
| tuic | 54 |
| anytls | 39 |

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
| 79.75 | shadowsocks | 225.7 | 509.9 | 22.55 | 0.0 | 10.0 | 13.26 | 18.86 | dragon | 38.145.220.193 |
| 77.33 | trojan | 231.1 | 511.9 | 22.43 | 0.0 | 9.13 | 10.5 | 18.86 | dragon | 167.88.61.20 |
| 77.0 | trojan | 241.6 | 513.9 | 22.19 | 0.0 | 9.46 | 10.5 | 18.86 | dragon | 167.88.61.175 |
| 76.62 | trojan | 239.5 | 525.3 | 22.23 | 0.0 | 9.04 | 10.5 | 18.86 | dragon | 167.88.61.198 |
| 76.47 | shadowsocks | 249.1 | 518.3 | 22.01 | 0.0 | 10.0 | 13.26 | 18.86 | dragon | 103.11.76.248 |
| 76.46 | trojan | 270.5 | 614.0 | 21.52 | 0.0 | 9.41 | 10.5 | 18.86 | dragon | 66.163.114.166 |
| 75.53 | trojan | 270.4 | 609.7 | 21.52 | 0.0 | 9.42 | 10.5 | 18.86 | dragon | 66.163.114.245 |
| 75.5 | trojan | 240.5 | 535.1 | 22.21 | 0.0 | 9.03 | 10.5 | 18.86 | dragon | 167.88.61.85 |
| 75.17 | trojan | 314.6 | 750.2 | 20.49 | 0.0 | 9.02 | 10.5 | 18.86 | dragon | 66.163.114.114 |
| 73.6 | shadowsocks | 197.4 | 528.8 | 23.21 | 0.0 | 2.27 | 13.26 | 18.86 | dragon | 149.22.95.183 |
| 73.42 | trojan | 297.0 | 596.7 | 20.9 | 0.0 | 9.38 | 10.5 | 18.86 | dragon | 66.163.112.13 |
| 73.19 | trojan | 263.2 | 737.3 | 21.68 | 0.0 | 9.65 | 10.5 | 18.86 | dragon | 216.106.186.82 |
| 72.85 | trojan | 320.9 | 563.3 | 20.35 | 0.0 | 9.4 | 10.5 | 18.86 | dragon | 66.163.112.76 |
| 72.64 | trojan | 273.5 | 624.2 | 21.45 | 0.0 | 7.69 | 10.5 | 18.86 | dragon | 66.163.114.106 |
| 71.67 | trojan | 257.2 | 584.3 | 21.82 | 0.0 | 10.0 | 10.5 | 18.86 | dragon | 167.88.61.52 |
| 71.65 | hysteria2 | 203.0 | 556.1 | 23.08 | 0.0 | 0.0 | 10.71 | 18.86 | dragon | 66.94.121.46 |
| 71.46 | trojan | 357.7 | 766.6 | 19.5 | 0.0 | 10.0 | 10.5 | 18.86 | dragon | 66.163.112.121 |
| 71.3 | trojan | 336.7 | 701.1 | 19.98 | 0.0 | 8.96 | 10.5 | 18.86 | dragon | 216.152.155.131 |
| 71.26 | trojan | 294.3 | 597.7 | 20.96 | 0.0 | 9.28 | 10.5 | 18.86 | dragon | 66.163.112.171 |
| 70.94 | trojan | 340.6 | 698.6 | 19.89 | 0.0 | 9.04 | 10.5 | 18.86 | dragon | 216.152.155.23 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.999 | 0.922 | 307 | 44959 | prefer |
| zhangkai | 0.923 | 1.0 | 19 | 43 | prefer |
| Surfboard-tg-mixed | 0.373 | 0.6 | 5 | 8651 | observe |
| mheidari-all | 0.335 | 1.0 | 1 | 14725 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2526 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10844 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6015 | observe |
| barry-far-vless | 0.255 | None | 0 | 6228 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4612 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 15 |
| 204 | ProxyError | - | 5 |
| cn-block | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| speed | TimeoutError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 72 | 50 | - |
| global | False | 73 | 52 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
