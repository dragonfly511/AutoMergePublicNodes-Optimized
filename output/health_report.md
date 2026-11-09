# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-09 05:22:45 |
| 运行耗时 | 409.0s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 123044 |
| 去重后节点 | 57994 |
| TCP 可达 | 3000 |
| 真实可用 | 80 |
| Verified 输出 | 80 |
| Global 输出 | 81 |
| All 输出 | 57994 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.4 |
| geo | 1.7 |
| tcp | 189.8 |
| probe | 114.2 |
| real_test | 35.6 |
| china_check | 29.0 |
| write_verified | 0.0 |
| generate | 30.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 75497 |
| vmess | 18432 |
| trojan | 13419 |
| shadowsocks | 12676 |
| hysteria2 | 2265 |
| shadowsocksr | 373 |
| http | 136 |
| socks | 90 |
| tuic | 63 |
| hysteria | 62 |
| anytls | 31 |

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
| 79.2 | trojan | 302.2 | 822.7 | 20.78 | 0.0 | 7.68 | 12.12 | 19.72 | dragon | 199.68.156.250 |
| 75.11 | hysteria2 | 236.9 | 605.3 | 22.29 | 0.0 | 1.91 | 12.19 | 19.72 | dragon | 88.216.195.188 |
| 75.04 | shadowsocks | 245.4 | 676.1 | 22.1 | 0.0 | 3.52 | 13.7 | 19.72 | dragon | 37.19.198.243 |
| 74.62 | shadowsocks | 239.2 | 661.1 | 22.24 | 0.0 | 7.96 | 13.7 | 19.72 | dragon | 37.19.198.160 |
| 74.45 | trojan | 230.9 | 642.1 | 22.43 | 0.0 | 7.68 | 12.12 | 19.72 | dragon | 66.163.122.46 |
| 74.42 | trojan | 232.2 | 644.5 | 22.4 | 0.0 | 7.68 | 12.12 | 19.72 | dragon | 66.163.122.113 |
| 73.31 | hysteria2 | 232.5 | 610.3 | 22.4 | 0.0 | 0.0 | 12.19 | 19.72 | dragon | promo3.goonars.com |
| 73.21 | shadowsocks | 285.7 | 648.4 | 21.16 | 0.0 | 6.27 | 13.7 | 19.72 | dragon | 156.146.38.168 |
| 72.04 | shadowsocks | 239.8 | 618.5 | 22.23 | 0.0 | 0.39 | 13.7 | 19.72 | dragon | 37.19.198.236 |
| 71.96 | shadowsocks | 276.7 | 629.3 | 21.37 | 0.0 | 3.07 | 13.7 | 19.72 | dragon | 156.146.38.170 |
| 71.87 | shadowsocks | 268.9 | 730.8 | 21.55 | 0.0 | 7.35 | 13.7 | 19.72 | dragon | 198.98.53.130 |
| 71.83 | trojan | 327.3 | 622.7 | 20.2 | 0.0 | 9.16 | 12.12 | 19.72 | dragon | 66.163.112.242 |
| 71.46 | shadowsocks | 242.4 | 669.7 | 22.17 | 0.0 | 3.52 | 13.7 | 19.72 | dragon | 37.19.198.244 |
| 71.41 | shadowsocks | 244.6 | 610.2 | 22.12 | 0.0 | 0.37 | 13.7 | 19.72 | dragon | 67.220.73.178 |
| 70.68 | shadowsocks | 260.1 | 683.0 | 21.76 | 0.0 | 0.0 | 13.7 | 19.72 | dragon | 38.91.100.39 |
| 70.49 | hysteria2 | 229.4 | 637.7 | 22.47 | 0.0 | 2.11 | 12.19 | 19.72 | dragon | 206.189.229.48 |
| 70.09 | shadowsocks | 285.5 | 699.9 | 21.17 | 0.0 | 0.0 | 13.7 | 19.72 | dragon | 193.151.160.9 |
| 70.02 | shadowsocks | 288.7 | 815.2 | 21.1 | 0.0 | 0.0 | 13.7 | 19.72 | dragon | 45.86.51.18 |
| 69.99 | shadowsocks | 289.9 | 709.3 | 21.07 | 0.0 | 0.0 | 13.7 | 19.72 | dragon | 38.91.107.57 |
| 69.98 | shadowsocks | 290.2 | 718.1 | 21.06 | 0.0 | 0.0 | 13.7 | 19.72 | dragon | 169.197.140.247 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.984 | 0.907 | 248 | 45021 | prefer |
| ermaozi | 0.977 | 1.0 | 21 | 519 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 13820 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5035 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10927 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8133 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5838 | observe |
| barry-far-vless | 0.255 | None | 0 | 6048 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4597 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 16 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 92 | 80 | - |
| global | False | 93 | 81 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
