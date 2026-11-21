# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-21 18:57:37 |
| 运行耗时 | 413.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 127585 |
| 去重后节点 | 59382 |
| TCP 可达 | 3000 |
| 真实可用 | 27 |
| Verified 输出 | 27 |
| Global 输出 | 28 |
| All 输出 | 59382 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.6 |
| geo | 1.7 |
| tcp | 196.1 |
| probe | 98.3 |
| real_test | 35.7 |
| china_check | 42.0 |
| write_verified | 0.0 |
| generate | 31.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77127 |
| vmess | 19199 |
| shadowsocks | 14769 |
| trojan | 13732 |
| hysteria2 | 2062 |
| shadowsocksr | 250 |
| socks | 181 |
| http | 121 |
| hysteria | 61 |
| tuic | 53 |
| anytls | 30 |

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
| 74.81 | http | 193.8 | 501.7 | 23.29 | 0.0 | 0.0 | 14.44 | 19.58 | ermaozi | 172.64.68.89 |
| 69.5 | trojan | 188.0 | 484.9 | 23.43 | 0.0 | 1.19 | 12.0 | 15.38 | dragon | 167.88.61.193 |
| 67.39 | trojan | 180.7 | 467.2 | 23.6 | 0.0 | 1.91 | 12.0 | 15.38 | dragon | 167.88.61.20 |
| 66.92 | trojan | 172.5 | 454.3 | 23.78 | 0.0 | 1.26 | 12.0 | 15.38 | dragon | 167.88.61.52 |
| 66.91 | trojan | 180.3 | 457.1 | 23.6 | 0.0 | 1.43 | 12.0 | 15.38 | dragon | 167.88.61.85 |
| 66.87 | trojan | 182.2 | 468.7 | 23.56 | 0.0 | 1.43 | 12.0 | 15.38 | dragon | 167.88.61.175 |
| 64.97 | http | 418.5 | 933.2 | 18.09 | 0.0 | 0.0 | 14.44 | 19.58 | ermaozi | 38.247.141.135 |
| 63.91 | trojan | 486.5 | 1039.1 | 16.52 | 0.0 | 9.25 | 12.0 | 15.38 | dragon | 69.164.240.85 |
| 62.84 | shadowsocks | 389.0 | 745.8 | 18.77 | 0.0 | 8.66 | 10.19 | 15.38 | dragon | 185.215.132.18 |
| 61.5 | hysteria2 | 336.6 | 715.9 | 19.99 | 0.0 | 0.0 | 11.0 | 15.38 | dragon | 206.189.229.48 |
| 61.41 | shadowsocks | 467.5 | 937.2 | 16.96 | 0.0 | 9.28 | 10.19 | 15.38 | dragon | 38.22.17.214 |
| 61.29 | trojan | 186.9 | 461.3 | 23.45 | 0.0 | 1.89 | 12.0 | 15.38 | dragon | 167.88.61.198 |
| 61.06 | vless | 401.5 | 456.7 | 18.48 | 0.0 | 8.82 | 11.25 | 15.38 | dragon | 172.237.14.205 |
| 56.14 | http | 640.5 | 944.4 | 12.95 | 0.0 | 0.0 | 14.44 | 19.58 | ermaozi | 34.249.214.108 |
| 54.86 | trojan | 432.9 | 467.9 | 17.76 | 0.0 | 0.02 | 12.0 | 15.38 | dragon | 158.247.253.243 |
| 54.76 | hysteria2 | 486.3 | 778.7 | 16.52 | 0.0 | 0.0 | 11.0 | 15.38 | dragon | 66.94.121.46 |
| 54.44 | http | 684.2 | 993.1 | 11.94 | 0.0 | 0.0 | 14.44 | 19.58 | ermaozi | 84.17.47.124 |
| 54.38 | http | 684.5 | 973.5 | 11.93 | 0.0 | 0.0 | 14.44 | 19.58 | ermaozi | 158.173.154.5 |
| 54.28 | http | 689.3 | 971.4 | 11.82 | 0.0 | 0.0 | 14.44 | 19.58 | ermaozi | 158.173.154.1 |
| 53.99 | http | 699.8 | 1041.1 | 11.58 | 0.0 | 0.0 | 14.44 | 19.58 | ermaozi | 84.17.47.148 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.904 | 1.0 | 18 | 403 | prefer |
| dragon | 0.587 | 0.507 | 67 | 44818 | observe |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 8779 | observe |
| mheidari-all | 0.349 | 0.667 | 3 | 14536 | observe |
| ermaozi-get_subscribe | 0.267 | 1.0 | 1 | 303 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 141 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5030 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2989 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11899 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5784 | observe |
| barry-far-vless | 0.255 | None | 0 | 5677 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4482 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 18 |
| test_one_timeout | 15.0s | - | 10 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 91 | 27 | - |
| global | False | 93 | 28 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
