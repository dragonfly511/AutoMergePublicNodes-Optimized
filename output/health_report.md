# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-30 22:07:40 |
| 运行耗时 | 362.3s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 125787 |
| 去重后节点 | 58329 |
| TCP 可达 | 3000 |
| 真实可用 | 89 |
| Verified 输出 | 89 |
| Global 输出 | 90 |
| All 输出 | 58329 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.5 |
| tcp | 202.3 |
| probe | 73.7 |
| real_test | 34.0 |
| china_check | 26.4 |
| write_verified | 0.0 |
| generate | 18.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 76875 |
| vmess | 18268 |
| trojan | 15377 |
| shadowsocks | 12423 |
| hysteria2 | 2258 |
| shadowsocksr | 258 |
| http | 111 |
| socks | 94 |
| tuic | 53 |
| hysteria | 40 |
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
| 80.58 | trojan | 200.0 | 548.2 | 23.15 | 0.0 | 7.38 | 13.83 | 18.72 | dragon | 216.106.186.33 |
| 77.71 | trojan | 281.3 | 269.6 | 21.27 | 4.89 | 7.19 | 13.83 | 18.72 | dragon | 125.227.86.45 |
| 73.94 | trojan | 246.0 | 676.4 | 22.08 | 0.0 | 1.81 | 13.83 | 18.72 | dragon | 216.106.186.32 |
| 71.85 | http | 233.7 | 535.4 | 22.37 | 0.0 | 0.0 | 13.64 | 18.44 | ermaozi | 44.248.167.117 |
| 71.71 | trojan | 280.1 | 623.9 | 21.29 | 0.0 | 2.8 | 13.83 | 18.72 | dragon | 66.163.114.45 |
| 71.33 | trojan | 240.4 | 534.1 | 22.21 | 0.0 | 10.0 | 13.83 | 18.72 | dragon | 167.88.61.20 |
| 69.82 | hysteria2 | 234.9 | 620.0 | 22.34 | 0.0 | 0.38 | 9.38 | 18.72 | dragon | 66.94.121.46 |
| 67.99 | trojan | 292.7 | 595.9 | 21.0 | 0.0 | 5.69 | 13.83 | 18.72 | dragon | 66.163.112.142 |
| 66.05 | trojan | 308.4 | 318.8 | 20.64 | 3.04 | 0.0 | 13.83 | 18.72 | dragon | 45.32.52.173 |
| 65.21 | trojan | 236.7 | 524.9 | 22.3 | 0.0 | 0.26 | 13.83 | 18.72 | dragon | 167.88.61.85 |
| 64.34 | trojan | 560.1 | 646.5 | 14.81 | 0.0 | 6.5 | 13.83 | 18.72 | dragon | 199.232.78.120 |
| 64.19 | trojan | 289.4 | 588.7 | 21.08 | 0.0 | 0.0 | 13.83 | 18.72 | dragon | 66.163.112.31 |
| 63.59 | trojan | 613.9 | 915.1 | 13.57 | 0.0 | 6.74 | 13.83 | 18.72 | dragon | 162.159.244.91 |
| 63.49 | trojan | 644.8 | 958.2 | 12.85 | 0.0 | 7.5 | 13.83 | 18.72 | dragon | 212.183.88.136 |
| 63.47 | trojan | 615.6 | 925.9 | 13.53 | 0.0 | 6.58 | 13.83 | 18.72 | dragon | 104.16.71.213 |
| 63.34 | trojan | 288.7 | 590.6 | 21.09 | 0.0 | 1.39 | 13.83 | 18.72 | dragon | 66.163.112.242 |
| 63.3 | hysteria2 | 216.8 | 509.9 | 22.76 | 0.0 | 4.57 | 9.38 | 18.72 | dragon | 179.255.103.55 |
| 62.67 | trojan | 405.7 | 893.2 | 18.39 | 0.0 | 4.64 | 13.83 | 18.72 | dragon | 66.23.203.21 |
| 62.19 | hysteria2 | 388.3 | 908.6 | 18.79 | 0.0 | 0.0 | 9.38 | 18.72 | dragon | 129.213.91.185 |
| 61.42 | trojan | 685.3 | 1015.1 | 11.91 | 0.0 | 6.5 | 13.83 | 18.72 | dragon | 151.101.36.120 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.988 | 1.0 | 27 | 550 | prefer |
| dragon | 0.955 | 0.881 | 126 | 44960 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4960 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2724 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10588 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7917 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5777 | observe |
| barry-far-vless | 0.255 | None | 0 | 6013 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4459 | observe |
| mheidari-all | 0.255 | None | 0 | 14611 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 10 |
| 204 | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 63 | 89 | - |
| global | False | 64 | 90 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
