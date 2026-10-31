# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-31 11:58:50 |
| 运行耗时 | 364.3s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 126213 |
| 去重后节点 | 58834 |
| TCP 可达 | 3000 |
| 真实可用 | 100 |
| Verified 输出 | 100 |
| Global 输出 | 102 |
| All 输出 | 58834 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.6 |
| tcp | 198.9 |
| probe | 79.8 |
| real_test | 30.8 |
| china_check | 22.9 |
| write_verified | 0.0 |
| generate | 23.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 76412 |
| vmess | 17889 |
| trojan | 16355 |
| shadowsocks | 12483 |
| hysteria2 | 2251 |
| http | 338 |
| shadowsocksr | 269 |
| socks | 94 |
| tuic | 53 |
| hysteria | 41 |
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
| 72.95 | trojan | 342.3 | 608.2 | 19.86 | 0.0 | 10.0 | 13.93 | 19.64 | dragon | 167.88.61.20 |
| 72.95 | trojan | 381.7 | 337.1 | 18.94 | 2.36 | 7.08 | 13.93 | 19.64 | dragon | 125.227.86.45 |
| 72.36 | trojan | 305.9 | 642.4 | 20.7 | 0.0 | 3.93 | 13.93 | 19.64 | dragon | 66.163.114.45 |
| 71.56 | trojan | 355.6 | 685.0 | 19.55 | 0.0 | 6.31 | 13.93 | 19.64 | dragon | 216.106.186.33 |
| 70.74 | trojan | 306.0 | 737.9 | 20.7 | 0.0 | 1.23 | 13.93 | 19.64 | dragon | 169.197.140.169 |
| 70.74 | trojan | 442.2 | 779.8 | 17.54 | 0.0 | 7.51 | 13.93 | 19.64 | dragon | 212.183.88.136 |
| 70.42 | http | 365.8 | 994.4 | 19.31 | 0.0 | 0.0 | 14.19 | 19.42 | ermaozi | 172.64.68.89 |
| 70.25 | hysteria2 | 274.7 | 588.9 | 21.42 | 0.0 | 3.86 | 14.06 | 19.64 | dragon | 179.255.103.55 |
| 69.71 | trojan | 443.0 | 955.6 | 17.52 | 0.0 | 6.4 | 13.93 | 19.64 | dragon | 66.23.203.21 |
| 69.56 | trojan | 304.1 | 737.0 | 20.74 | 0.0 | 1.23 | 13.93 | 19.64 | dragon | 169.197.140.245 |
| 69.47 | trojan | 472.3 | 847.4 | 16.85 | 0.0 | 7.92 | 13.93 | 19.64 | dragon | 45.130.125.190 |
| 69.38 | trojan | 468.9 | 842.6 | 16.92 | 0.0 | 6.89 | 13.93 | 19.64 | dragon | 162.159.244.91 |
| 69.25 | trojan | 446.5 | 772.6 | 17.44 | 0.0 | 9.13 | 13.93 | 19.64 | dragon | 45.130.125.69 |
| 69.23 | trojan | 331.8 | 633.9 | 20.1 | 0.0 | 6.24 | 13.93 | 19.64 | dragon | 66.163.112.142 |
| 69.11 | trojan | 467.1 | 843.4 | 16.97 | 0.0 | 7.47 | 13.93 | 19.64 | dragon | 104.18.37.228 |
| 68.99 | http | 364.5 | 890.1 | 19.34 | 0.0 | 0.0 | 14.19 | 19.42 | ermaozi | 12.202.180.10 |
| 68.94 | hysteria2 | 503.5 | 1037.7 | 16.12 | 0.0 | 6.28 | 14.06 | 19.64 | dragon | 130.49.161.70 |
| 68.59 | trojan | 440.5 | 769.6 | 17.58 | 0.0 | 5.35 | 13.93 | 19.64 | dragon | 104.17.121.9 |
| 68.58 | trojan | 467.1 | 747.1 | 16.96 | 0.0 | 7.92 | 13.93 | 19.64 | dragon | 45.130.125.75 |
| 68.33 | trojan | 474.7 | 869.4 | 16.79 | 0.0 | 9.13 | 13.93 | 19.64 | dragon | 104.25.124.54 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.989 | 0.981 | 54 | 622 | prefer |
| dragon | 0.87 | 0.796 | 98 | 44960 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4970 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2848 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10588 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7861 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5698 | observe |
| barry-far-vless | 0.255 | None | 0 | 5912 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4635 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 12 |
| 204 | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:47328: bind: address already in use | - | 1 |
| geo | ClientOSError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 133 | 100 | - |
| global | False | 133 | 102 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
