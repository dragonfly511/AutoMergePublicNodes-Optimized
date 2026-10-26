# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-26 22:31:38 |
| 运行耗时 | 369.0s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 142481 |
| 去重后节点 | 58971 |
| TCP 可达 | 3000 |
| 真实可用 | 62 |
| Verified 输出 | 62 |
| Global 输出 | 63 |
| All 输出 | 58971 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.9 |
| geo | 1.6 |
| tcp | 203.8 |
| probe | 85.0 |
| real_test | 24.4 |
| china_check | 24.5 |
| write_verified | 0.0 |
| generate | 22.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 85929 |
| vmess | 21753 |
| shadowsocks | 16667 |
| trojan | 15360 |
| hysteria2 | 2138 |
| shadowsocksr | 262 |
| http | 142 |
| socks | 127 |
| hysteria | 48 |
| anytls | 41 |
| tuic | 14 |

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
| 71.38 | trojan | 390.9 | 705.4 | 18.73 | 0.0 | 9.42 | 12.31 | 16.36 | dragon | 155.138.138.2 |
| 70.0 | trojan | 401.2 | 594.7 | 18.49 | 0.0 | 9.67 | 12.31 | 16.36 | dragon | 216.106.186.33 |
| 68.93 | trojan | 314.0 | 623.3 | 20.51 | 0.0 | 9.67 | 12.31 | 16.36 | dragon | 216.106.186.32 |
| 68.77 | http | 304.8 | 611.9 | 20.72 | 0.0 | 0.0 | 14.43 | 19.76 | ermaozi | 64.98.50.100 |
| 68.55 | http | 315.6 | 721.0 | 20.47 | 0.0 | 0.0 | 14.43 | 19.76 | ermaozi | 38.247.141.135 |
| 67.31 | hysteria2 | 270.6 | 572.3 | 21.51 | 0.0 | 0.0 | 12.0 | 16.36 | dragon | 66.94.121.46 |
| 65.68 | http | 355.3 | 652.1 | 19.55 | 0.0 | 0.0 | 14.43 | 19.76 | ermaozi | 44.248.167.117 |
| 65.2 | http | 372.5 | 891.2 | 19.16 | 0.0 | 0.0 | 14.43 | 19.76 | ermaozi | 198.44.138.27 |
| 64.08 | trojan | 439.7 | 1158.4 | 17.6 | 0.0 | 5.81 | 12.31 | 16.36 | dragon | 66.23.203.21 |
| 63.61 | trojan | 405.8 | 396.2 | 18.39 | 0.14 | 9.36 | 12.31 | 16.36 | dragon | 45.32.52.173 |
| 63.57 | trojan | 502.4 | 986.6 | 16.15 | 0.0 | 9.2 | 12.31 | 16.36 | dragon | 45.149.147.213 |
| 61.96 | trojan | 589.9 | 905.6 | 14.12 | 0.0 | 9.23 | 12.31 | 16.36 | dragon | 45.87.41.18 |
| 61.87 | hysteria2 | 276.9 | 268.6 | 21.37 | 4.93 | 0.0 | 12.0 | 16.36 | dragon | 8.209.247.109 |
| 61.44 | trojan | 630.9 | 976.6 | 13.17 | 0.0 | 9.38 | 12.31 | 16.36 | dragon | 89.150.34.41 |
| 61.3 | trojan | 569.4 | 1395.9 | 14.6 | 0.0 | 9.66 | 12.31 | 16.36 | dragon | 216.106.186.66 |
| 61.02 | trojan | 696.2 | 1002.2 | 11.66 | 0.0 | 10.0 | 12.31 | 16.36 | dragon | 172.66.40.99 |
| 60.36 | trojan | 453.1 | 1140.7 | 17.29 | 0.0 | 0.61 | 12.31 | 16.36 | dragon | 69.164.240.85 |
| 60.12 | http | 377.0 | 624.6 | 19.05 | 0.0 | 0.0 | 14.43 | 19.76 | ermaozi | 154.81.36.92 |
| 59.42 | trojan | 323.2 | 664.2 | 20.3 | 0.0 | 0.19 | 12.31 | 16.36 | dragon | blog.findlocaljobnetworkandbuildcommunityconnections.com |
| 59.12 | trojan | 656.5 | 1102.2 | 12.58 | 0.0 | 9.05 | 12.31 | 16.36 | dragon | 164.92.223.252 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.991 | 0.92 | 88 | 45531 | prefer |
| ermaozi | 0.917 | 0.917 | 36 | 564 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4919 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3004 | observe |
| Epodonios-all | 0.255 | None | 0 | 7537 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10741 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7052 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5366 | observe |
| barry-far-vless | 0.255 | None | 0 | 5651 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4466 | observe |
| mheidari-all | 0.255 | None | 0 | 24769 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.244 | None | 0 | 1729 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 2 |
| cn-block | ProxyError | - | 2 |
| test_one_timeout | 15.0s | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:32908: bind: address already in use | - | 1 |
| 204 | TimeoutError | - | 1 |
| speed | ClientOSError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 113 | 62 | - |
| global | False | 113 | 63 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
