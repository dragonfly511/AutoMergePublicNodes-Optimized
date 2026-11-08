# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-08 05:11:29 |
| 运行耗时 | 425.9s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 126496 |
| 去重后节点 | 58753 |
| TCP 可达 | 3000 |
| 真实可用 | 86 |
| Verified 输出 | 86 |
| Global 输出 | 86 |
| All 输出 | 58753 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.5 |
| geo | 1.7 |
| tcp | 194.2 |
| probe | 109.8 |
| real_test | 42.5 |
| china_check | 38.7 |
| write_verified | 0.0 |
| generate | 30.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 76856 |
| vmess | 18352 |
| trojan | 14741 |
| shadowsocks | 13348 |
| hysteria2 | 2307 |
| shadowsocksr | 368 |
| http | 254 |
| socks | 132 |
| hysteria | 60 |
| tuic | 45 |
| anytls | 33 |

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
| 81.62 | shadowsocks | 246.2 | 677.1 | 22.08 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 37.19.198.243 |
| 81.14 | shadowsocks | 245.2 | 647.7 | 22.1 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 185.230.230.18 |
| 80.85 | shadowsocks | 257.9 | 669.7 | 21.81 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 38.91.100.39 |
| 80.83 | shadowsocks | 280.3 | 780.8 | 21.29 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 37.19.198.160 |
| 80.65 | shadowsocks | 266.5 | 690.9 | 21.61 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 193.151.163.18 |
| 80.11 | shadowsocks | 289.8 | 713.7 | 21.07 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 193.151.160.18 |
| 80.01 | shadowsocks | 294.2 | 798.4 | 20.97 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 172.111.38.72 |
| 79.98 | shadowsocks | 285.4 | 699.7 | 21.17 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 193.151.160.9 |
| 79.83 | shadowsocks | 284.8 | 674.3 | 21.19 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 51.79.64.198 |
| 79.36 | shadowsocks | 318.0 | 791.7 | 20.42 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 38.128.66.32 |
| 78.93 | shadowsocks | 281.1 | 638.6 | 21.27 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 156.146.38.167 |
| 78.19 | trojan | 317.7 | 694.0 | 20.42 | 0.0 | 8.56 | 12.17 | 19.54 | dragon | 66.163.122.46 |
| 78.0 | shadowsocks | 381.1 | 1054.9 | 18.96 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 45.86.51.18 |
| 77.5 | trojan | 304.6 | 779.4 | 20.73 | 0.0 | 7.56 | 12.17 | 19.54 | dragon | 216.152.155.23 |
| 77.43 | shadowsocks | 362.5 | 951.7 | 19.39 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 149.40.57.138 |
| 77.2 | shadowsocks | 372.4 | 983.1 | 19.16 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 149.40.57.133 |
| 77.18 | shadowsocks | 369.3 | 908.2 | 19.23 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 38.91.107.188 |
| 76.2 | shadowsocks | 392.5 | 974.6 | 18.69 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 156.146.38.169 |
| 75.84 | shadowsocks | 262.8 | 728.3 | 21.7 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 37.19.198.236 |
| 75.7 | shadowsocks | 280.5 | 645.5 | 21.29 | 0.0 | 10.0 | 14.0 | 19.54 | dragon | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.93 | 299 | 45338 | prefer |
| ermaozi | 0.971 | 0.956 | 91 | 613 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 14102 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4866 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2734 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11000 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8112 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5849 | observe |
| barry-far-vless | 0.255 | None | 0 | 6090 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4529 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 12 |
| speed | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 2 |
| 204 | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:37874: bind: address already in use | - | 1 |
| cn-block | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 72 | 86 | - |
| global | False | 74 | 86 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
