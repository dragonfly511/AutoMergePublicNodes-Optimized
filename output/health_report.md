# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-28 04:48:39 |
| 运行耗时 | 408.4s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 142942 |
| 去重后节点 | 59073 |
| TCP 可达 | 3000 |
| 真实可用 | 91 |
| Verified 输出 | 91 |
| Global 输出 | 92 |
| All 输出 | 59073 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.6 |
| tcp | 205.1 |
| probe | 102.2 |
| real_test | 39.5 |
| china_check | 30.7 |
| write_verified | 0.0 |
| generate | 22.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 86068 |
| vmess | 21419 |
| shadowsocks | 16633 |
| trojan | 16183 |
| hysteria2 | 1976 |
| shadowsocksr | 269 |
| http | 162 |
| socks | 101 |
| hysteria | 46 |
| tuic | 43 |
| anytls | 42 |

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
| 74.18 | hysteria2 | 276.5 | 264.9 | 21.38 | 5.07 | 6.1 | 12.75 | 16.78 | dragon | 8.209.247.109 |
| 69.51 | shadowsocks | 308.1 | 701.3 | 20.65 | 0.0 | 7.01 | 11.84 | 16.78 | dragon | 185.230.230.18 |
| 68.76 | shadowsocks | 309.6 | 739.8 | 20.61 | 0.0 | 5.62 | 11.84 | 16.78 | dragon | 216.9.225.189 |
| 68.32 | shadowsocks | 366.8 | 928.2 | 19.29 | 0.0 | 5.68 | 11.84 | 16.78 | dragon | 185.215.132.18 |
| 67.05 | shadowsocks | 390.3 | 928.9 | 18.74 | 0.0 | 6.71 | 11.84 | 16.78 | dragon | 15.204.246.132 |
| 66.99 | shadowsocks | 233.5 | 603.5 | 22.37 | 0.0 | 0.0 | 11.84 | 16.78 | dragon | 156.146.38.168 |
| 66.88 | shadowsocks | 238.5 | 599.5 | 22.26 | 0.0 | 0.0 | 11.84 | 16.78 | dragon | 156.146.38.170 |
| 66.04 | hysteria2 | 400.2 | 718.1 | 18.52 | 0.0 | 5.56 | 12.75 | 16.78 | dragon | 62.210.124.146 |
| 65.75 | shadowsocks | 409.4 | 982.9 | 18.3 | 0.0 | 6.62 | 11.84 | 16.78 | dragon | 15.204.233.41 |
| 65.01 | shadowsocks | 294.5 | 710.7 | 20.96 | 0.0 | 0.0 | 11.84 | 16.78 | dragon | 37.19.198.160 |
| 64.9 | shadowsocks | 295.4 | 720.2 | 20.94 | 0.0 | 0.0 | 11.84 | 16.78 | dragon | 37.19.198.243 |
| 64.9 | shadowsocks | 299.1 | 727.5 | 20.85 | 0.0 | 0.0 | 11.84 | 16.78 | dragon | 37.19.198.236 |
| 64.87 | shadowsocks | 292.0 | 703.1 | 21.02 | 0.0 | 0.0 | 11.84 | 16.78 | dragon | 37.19.198.244 |
| 64.6 | hysteria2 | 484.3 | 933.3 | 16.57 | 0.0 | 5.8 | 12.75 | 16.78 | dragon | 64.188.98.171 |
| 64.41 | trojan | 338.8 | 292.7 | 19.94 | 4.02 | 2.15 | 11.25 | 16.78 | dragon | 125.227.86.45 |
| 64.0 | shadowsocks | 307.8 | 717.3 | 20.65 | 0.0 | 0.0 | 11.84 | 16.78 | dragon | 193.151.163.18 |
| 63.88 | shadowsocks | 238.4 | 610.6 | 22.26 | 0.0 | 0.0 | 11.84 | 16.78 | dragon | 156.146.38.169 |
| 63.81 | shadowsocks | 241.4 | 598.7 | 22.19 | 0.0 | 0.0 | 11.84 | 16.78 | dragon | 156.146.38.167 |
| 63.23 | hysteria2 | 361.1 | 731.8 | 19.42 | 0.0 | 0.0 | 12.75 | 16.78 | dragon | 66.94.121.46 |
| 60.56 | shadowsocks | 368.5 | 911.3 | 19.25 | 0.0 | 0.0 | 11.84 | 16.78 | dragon | 45.86.51.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.974 | 0.977 | 43 | 467 | prefer |
| dragon | 0.953 | 0.876 | 210 | 45232 | prefer |
| zhangkai | 0.62 | 1.0 | 10 | 43 | observe |
| Surfboard-tg-mixed | 0.349 | 0.667 | 3 | 7522 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4988 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3052 | observe |
| Epodonios-all | 0.255 | None | 0 | 8008 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10429 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5538 | observe |
| barry-far-vless | 0.255 | None | 0 | 5751 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4500 | observe |
| mheidari-all | 0.255 | None | 0 | 24790 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 19 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| geo | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 75 | 91 | - |
| global | False | 79 | 92 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
