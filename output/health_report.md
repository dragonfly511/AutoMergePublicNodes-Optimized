# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-26 12:35:25 |
| 运行耗时 | 391.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 142330 |
| 去重后节点 | 59631 |
| TCP 可达 | 3000 |
| 真实可用 | 113 |
| Verified 输出 | 113 |
| Global 输出 | 113 |
| All 输出 | 59631 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.3 |
| geo | 1.7 |
| tcp | 201.1 |
| probe | 100.6 |
| real_test | 26.0 |
| china_check | 22.7 |
| write_verified | 0.1 |
| generate | 30.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 86239 |
| vmess | 21496 |
| shadowsocks | 17345 |
| trojan | 14178 |
| hysteria2 | 1990 |
| http | 367 |
| shadowsocksr | 276 |
| tuic | 235 |
| socks | 119 |
| hysteria | 48 |
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
| 72.59 | trojan | 395.0 | 1121.3 | 18.63 | 0.0 | 7.11 | 13.85 | 19.0 | dragon | 69.164.240.85 |
| 72.25 | trojan | 453.0 | 795.8 | 17.29 | 0.0 | 10.0 | 13.85 | 19.0 | dragon | 104.19.64.105 |
| 71.6 | http | 288.8 | 817.0 | 21.09 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 198.44.135.19 |
| 70.83 | shadowsocks | 286.5 | 667.3 | 21.15 | 0.0 | 8.08 | 13.33 | 19.0 | dragon | 156.146.38.168 |
| 70.11 | trojan | 446.2 | 768.5 | 17.45 | 0.0 | 7.91 | 13.85 | 19.0 | dragon | 141.193.213.172 |
| 69.96 | trojan | 455.3 | 785.8 | 17.24 | 0.0 | 10.0 | 13.85 | 19.0 | dragon | 104.21.13.204 |
| 69.64 | trojan | 445.7 | 779.3 | 17.46 | 0.0 | 7.93 | 13.85 | 19.0 | dragon | 45.130.125.75 |
| 69.56 | trojan | 546.1 | 1001.9 | 15.14 | 0.0 | 9.85 | 13.85 | 19.0 | dragon | 172.66.40.99 |
| 69.14 | trojan | 457.9 | 798.0 | 17.18 | 0.0 | 7.11 | 13.85 | 19.0 | dragon | 212.183.88.136 |
| 69.06 | trojan | 456.1 | 777.7 | 17.22 | 0.0 | 7.11 | 13.85 | 19.0 | dragon | 172.64.150.28 |
| 68.72 | http | 327.1 | 822.9 | 20.21 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 154.47.25.78 |
| 68.56 | http | 355.5 | 901.9 | 19.55 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 206.223.183.21 |
| 68.46 | trojan | 357.8 | 697.6 | 19.49 | 0.0 | 4.36 | 13.85 | 19.0 | dragon | 216.106.186.33 |
| 68.38 | http | 276.9 | 780.3 | 21.37 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 198.44.135.27 |
| 68.27 | trojan | 450.8 | 792.9 | 17.34 | 0.0 | 6.08 | 13.85 | 19.0 | dragon | 165.215.250.14 |
| 67.77 | trojan | 475.3 | 987.9 | 16.77 | 0.0 | 9.03 | 13.85 | 19.0 | dragon | 45.149.147.213 |
| 67.72 | http | 358.8 | 893.8 | 19.47 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 12.202.180.118 |
| 67.62 | trojan | 551.9 | 868.5 | 15.0 | 0.0 | 9.34 | 13.85 | 19.0 | dragon | 45.87.41.18 |
| 67.56 | trojan | 534.6 | 840.5 | 15.4 | 0.0 | 8.22 | 13.85 | 19.0 | dragon | 89.150.34.41 |
| 67.46 | http | 257.2 | 604.6 | 21.82 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 193.239.236.134 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.988 | 0.971 | 103 | 643 | prefer |
| dragon | 0.818 | 0.746 | 63 | 45637 | prefer |
| Au1rxx-base64 | 0.323 | 1.0 | 1 | 1689 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 167 | observe |
| zhangkai | 0.257 | 1.0 | 1 | 43 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4919 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3004 | observe |
| Epodonios-all | 0.255 | None | 0 | 7666 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10302 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7197 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5522 | observe |
| barry-far-vless | 0.255 | None | 0 | 5877 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4228 | observe |
| mheidari-all | 0.255 | None | 0 | 24314 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 12 |
| 204 | ProxyError | - | 3 |
| 204 | ClientOSError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:35140: bind: address already in use | - | 1 |
| 204 | TimeoutError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 109 | 113 | - |
| global | False | 109 | 113 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
