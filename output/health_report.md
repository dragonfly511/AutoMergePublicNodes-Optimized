# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-25 03:54:04 |
| 运行耗时 | 448.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 142469 |
| 去重后节点 | 60019 |
| TCP 可达 | 3000 |
| 真实可用 | 91 |
| Verified 输出 | 91 |
| Global 输出 | 92 |
| All 输出 | 60019 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.1 |
| geo | 1.6 |
| tcp | 209.2 |
| probe | 117.2 |
| real_test | 51.8 |
| china_check | 38.1 |
| write_verified | 0.0 |
| generate | 23.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 85965 |
| vmess | 21096 |
| shadowsocks | 17296 |
| trojan | 15305 |
| hysteria2 | 1963 |
| http | 283 |
| shadowsocksr | 275 |
| socks | 153 |
| hysteria | 47 |
| anytls | 43 |
| tuic | 43 |

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
| 73.98 | http | 210.7 | 493.1 | 22.9 | 0.0 | 0.0 | 14.42 | 19.66 | ermaozi | 138.199.35.201 |
| 73.93 | http | 212.9 | 500.2 | 22.85 | 0.0 | 0.0 | 14.42 | 19.66 | ermaozi | 138.199.35.206 |
| 73.82 | http | 217.4 | 500.4 | 22.74 | 0.0 | 0.0 | 14.42 | 19.66 | ermaozi | 138.199.35.214 |
| 73.78 | http | 219.2 | 562.2 | 22.7 | 0.0 | 0.0 | 14.42 | 19.66 | ermaozi | 138.199.35.217 |
| 73.33 | http | 238.7 | 625.1 | 22.25 | 0.0 | 0.0 | 14.42 | 19.66 | ermaozi | 138.199.35.210 |
| 73.33 | http | 239.0 | 621.8 | 22.25 | 0.0 | 0.0 | 14.42 | 19.66 | ermaozi | 138.199.35.202 |
| 73.32 | http | 239.1 | 620.9 | 22.24 | 0.0 | 0.0 | 14.42 | 19.66 | ermaozi | 138.199.35.208 |
| 73.3 | http | 240.1 | 630.0 | 22.22 | 0.0 | 0.0 | 14.42 | 19.66 | ermaozi | 138.199.35.212 |
| 73.3 | http | 257.4 | 577.6 | 21.82 | 0.0 | 0.0 | 14.42 | 19.66 | ermaozi | 44.229.69.166 |
| 72.64 | http | 285.9 | 551.3 | 21.16 | 0.0 | 0.0 | 14.42 | 19.66 | ermaozi | 44.248.167.117 |
| 71.28 | http | 241.1 | 623.9 | 22.2 | 0.0 | 0.0 | 14.42 | 19.66 | ermaozi | 138.199.35.213 |
| 70.0 | hysteria2 | 228.7 | 240.2 | 22.48 | 5.99 | 0.0 | 10.0 | 18.36 | dragon | vp3.yysyy.online |
| 68.91 | trojan | 258.0 | 640.6 | 21.8 | 0.0 | 8.07 | 8.18 | 18.36 | dragon | 216.106.186.32 |
| 68.51 | http | 340.7 | 727.5 | 19.89 | 0.0 | 0.0 | 14.42 | 19.66 | ermaozi | 45.63.38.134 |
| 68.5 | trojan | 241.1 | 593.5 | 22.2 | 0.0 | 7.26 | 8.18 | 18.36 | dragon | 216.106.186.33 |
| 67.98 | shadowsocks | 302.2 | 752.8 | 20.78 | 0.0 | 0.0 | 13.34 | 18.36 | dragon | 95.215.201.18 |
| 67.61 | http | 334.2 | 633.0 | 20.04 | 0.0 | 0.0 | 14.42 | 19.66 | ermaozi | 64.98.50.100 |
| 66.0 | shadowsocks | 291.6 | 664.7 | 21.03 | 0.0 | 0.0 | 13.34 | 18.36 | dragon | 156.146.38.167 |
| 65.36 | shadowsocks | 321.9 | 751.8 | 20.33 | 0.0 | 0.0 | 13.34 | 18.36 | dragon | 156.146.38.170 |
| 65.24 | hysteria2 | 226.0 | 236.0 | 22.55 | 6.15 | 0.0 | 10.0 | 18.36 | dragon | 45.32.10.7 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.964 | 0.951 | 81 | 604 | prefer |
| dragon | 0.962 | 0.886 | 185 | 46036 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 24115 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 107 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4911 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3780 | observe |
| Epodonios-all | 0.255 | None | 0 | 7585 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10198 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7102 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5419 | observe |
| barry-far-vless | 0.255 | None | 0 | 5635 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4150 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 13 |
| 204 | ProxyError | - | 5 |
| 204 | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:36896: bind: address already in use | - | 1 |
| cn-block | ClientOSError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| 204 | TimeoutError | - | 1 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 45 | 91 | - |
| global | False | 46 | 92 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
