# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-01 12:58:46 |
| 运行耗时 | 393.0s |
| 订阅源总数 | 108 |
| 健康订阅源 | 90 |
| 原始节点 | 126129 |
| 去重后节点 | 58390 |
| TCP 可达 | 3000 |
| 真实可用 | 72 |
| Verified 输出 | 72 |
| Global 输出 | 73 |
| All 输出 | 58390 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| geo | 1.7 |
| tcp | 198.3 |
| probe | 96.5 |
| real_test | 32.3 |
| china_check | 25.2 |
| write_verified | 0.0 |
| generate | 30.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 75841 |
| vmess | 18159 |
| trojan | 16975 |
| shadowsocks | 12079 |
| hysteria2 | 2211 |
| shadowsocksr | 280 |
| tuic | 264 |
| http | 143 |
| socks | 110 |
| hysteria | 42 |
| anytls | 25 |

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
| 83.24 | trojan | 264.5 | 639.8 | 21.66 | 0.0 | 10.0 | 14.08 | 20.0 | dragon | 216.152.155.23 |
| 82.47 | trojan | 254.5 | 601.0 | 21.89 | 0.0 | 10.0 | 14.08 | 20.0 | dragon | 66.163.114.114 |
| 82.32 | trojan | 260.8 | 598.0 | 21.74 | 0.0 | 10.0 | 14.08 | 20.0 | dragon | 66.163.114.132 |
| 79.84 | trojan | 249.4 | 609.3 | 22.0 | 0.0 | 10.0 | 14.08 | 20.0 | dragon | 216.152.155.176 |
| 78.97 | trojan | 363.6 | 652.7 | 19.36 | 0.0 | 10.0 | 14.08 | 20.0 | dragon | 216.152.156.212 |
| 77.43 | trojan | 362.3 | 794.6 | 19.39 | 0.0 | 10.0 | 14.08 | 20.0 | dragon | 169.197.140.169 |
| 77.09 | hysteria2 | 280.2 | 698.1 | 21.29 | 0.0 | 7.03 | 12.27 | 20.0 | dragon | 129.213.91.185 |
| 76.7 | trojan | 275.8 | 610.3 | 21.39 | 0.0 | 3.73 | 14.08 | 20.0 | dragon | 66.163.114.45 |
| 76.5 | trojan | 298.8 | 594.7 | 20.86 | 0.0 | 10.0 | 14.08 | 20.0 | dragon | 66.163.112.121 |
| 75.43 | trojan | 260.1 | 613.2 | 21.76 | 0.0 | 3.68 | 14.08 | 20.0 | dragon | 66.163.114.126 |
| 75.39 | trojan | 305.0 | 613.8 | 20.72 | 0.0 | 10.0 | 14.08 | 20.0 | dragon | 66.163.112.13 |
| 74.96 | trojan | 322.5 | 662.6 | 20.31 | 0.0 | 7.8 | 14.08 | 20.0 | dragon | 216.106.186.33 |
| 74.28 | trojan | 354.8 | 770.8 | 19.56 | 0.0 | 10.0 | 14.08 | 20.0 | dragon | 169.197.140.214 |
| 74.15 | trojan | 351.1 | 765.3 | 19.65 | 0.0 | 8.89 | 14.08 | 20.0 | dragon | 169.197.140.171 |
| 74.03 | trojan | 259.9 | 612.6 | 21.76 | 0.0 | 3.69 | 14.08 | 20.0 | dragon | 66.163.114.245 |
| 73.69 | trojan | 305.1 | 705.7 | 20.72 | 0.0 | 10.0 | 14.08 | 20.0 | dragon | 216.152.156.65 |
| 72.87 | trojan | 289.1 | 582.6 | 21.09 | 0.0 | 3.66 | 14.08 | 20.0 | dragon | 66.163.114.166 |
| 71.9 | trojan | 264.5 | 607.2 | 21.66 | 0.0 | 3.66 | 14.08 | 20.0 | dragon | 66.163.114.106 |
| 71.39 | trojan | 319.9 | 624.2 | 20.37 | 0.0 | 3.49 | 14.08 | 20.0 | dragon | 66.163.112.242 |
| 70.49 | trojan | 311.3 | 616.1 | 20.57 | 0.0 | 3.48 | 14.08 | 20.0 | dragon | 66.163.112.142 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.995 | 1.0 | 38 | 499 | prefer |
| dragon | 0.849 | 0.773 | 128 | 44351 | prefer |
| zhangkai | 0.441 | 1.0 | 5 | 43 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4976 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3716 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10599 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8063 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5660 | observe |
| barry-far-vless | 0.255 | None | 0 | 5850 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4680 | observe |
| mheidari-all | 0.255 | None | 0 | 14747 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 20 |
| 204 | ProxyError | - | 4 |
| speed | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 66 | 72 | - |
| global | False | 66 | 73 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
