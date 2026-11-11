# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-11 05:22:38 |
| 运行耗时 | 401.2s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 127580 |
| 去重后节点 | 59612 |
| TCP 可达 | 3000 |
| 真实可用 | 108 |
| Verified 输出 | 108 |
| Global 输出 | 108 |
| All 输出 | 59612 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| geo | 1.7 |
| tcp | 195.0 |
| probe | 99.0 |
| real_test | 39.0 |
| china_check | 25.5 |
| write_verified | 0.1 |
| generate | 31.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 78603 |
| vmess | 18091 |
| trojan | 14981 |
| shadowsocks | 12996 |
| hysteria2 | 2150 |
| http | 297 |
| shadowsocksr | 256 |
| socks | 102 |
| hysteria | 41 |
| anytls | 36 |
| tuic | 27 |

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
| 82.55 | trojan | 263.5 | 642.2 | 21.68 | 0.0 | 9.78 | 14.07 | 19.52 | dragon | 216.152.155.59 |
| 82.5 | trojan | 265.7 | 585.0 | 21.63 | 0.0 | 9.78 | 14.07 | 19.52 | dragon | 216.152.155.158 |
| 82.48 | trojan | 276.0 | 654.4 | 21.39 | 0.0 | 10.0 | 14.07 | 19.52 | dragon | 216.152.156.49 |
| 82.41 | trojan | 278.9 | 667.7 | 21.32 | 0.0 | 10.0 | 14.07 | 19.52 | dragon | 170.101.101.19 |
| 80.55 | trojan | 307.6 | 737.3 | 20.66 | 0.0 | 9.76 | 14.07 | 19.52 | dragon | 169.197.140.245 |
| 80.23 | trojan | 319.5 | 788.4 | 20.38 | 0.0 | 8.76 | 14.07 | 19.52 | dragon | 170.101.101.67 |
| 80.16 | trojan | 316.3 | 760.3 | 20.46 | 0.0 | 8.61 | 14.07 | 19.52 | dragon | 170.101.101.131 |
| 80.07 | shadowsocks | 260.4 | 671.3 | 21.75 | 0.0 | 9.91 | 13.39 | 19.52 | dragon | 15.204.233.41 |
| 80.02 | shadowsocks | 259.1 | 636.8 | 21.78 | 0.0 | 9.83 | 13.39 | 19.52 | dragon | 185.215.132.9 |
| 79.98 | trojan | 330.7 | 836.0 | 20.12 | 0.0 | 8.77 | 14.07 | 19.52 | dragon | 216.152.155.54 |
| 79.96 | shadowsocks | 261.9 | 640.2 | 21.72 | 0.0 | 9.83 | 13.39 | 19.52 | dragon | 185.215.132.18 |
| 79.73 | trojan | 291.7 | 690.1 | 21.03 | 0.0 | 8.61 | 14.07 | 19.52 | dragon | 170.101.101.53 |
| 79.32 | trojan | 313.3 | 795.0 | 20.52 | 0.0 | 8.54 | 14.07 | 19.52 | dragon | 216.152.155.23 |
| 79.05 | trojan | 330.1 | 818.7 | 20.14 | 0.0 | 8.43 | 14.07 | 19.52 | dragon | 170.101.101.112 |
| 78.98 | shadowsocks | 300.6 | 743.0 | 20.82 | 0.0 | 9.75 | 13.39 | 19.52 | dragon | 38.91.107.57 |
| 78.86 | trojan | 357.7 | 878.8 | 19.5 | 0.0 | 8.59 | 14.07 | 19.52 | dragon | 169.197.140.171 |
| 78.58 | trojan | 292.5 | 593.1 | 21.01 | 0.0 | 10.0 | 14.07 | 19.52 | dragon | 66.163.114.106 |
| 78.47 | trojan | 312.1 | 729.6 | 20.55 | 0.0 | 8.4 | 14.07 | 19.52 | dragon | 169.197.140.218 |
| 78.01 | shadowsocks | 262.6 | 699.1 | 21.7 | 0.0 | 9.9 | 13.39 | 19.52 | dragon | 15.204.246.132 |
| 77.99 | trojan | 254.1 | 697.6 | 21.9 | 0.0 | 10.0 | 14.07 | 19.52 | dragon | 66.163.122.81 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | 0.988 | 82 | 601 | prefer |
| dragon | 0.923 | 0.848 | 132 | 45201 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 13964 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4955 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2620 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11127 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8415 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6298 | observe |
| barry-far-vless | 0.255 | None | 0 | 6562 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4595 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 8 |
| 204 | ProxyError | - | 6 |
| 204 | ClientOSError | - | 3 |
| speed | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:37994: bind: address already in use | - | 1 |
| cn-block | TimeoutError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 64 | 108 | - |
| global | False | 66 | 108 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
