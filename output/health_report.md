# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-16 15:17:30 |
| 运行耗时 | 385.5s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 127495 |
| 去重后节点 | 58280 |
| TCP 可达 | 3000 |
| 真实可用 | 45 |
| Verified 输出 | 45 |
| Global 输出 | 47 |
| All 输出 | 58280 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| geo | 1.7 |
| tcp | 199.0 |
| probe | 96.4 |
| real_test | 26.7 |
| china_check | 22.7 |
| write_verified | 0.0 |
| generate | 30.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77734 |
| vmess | 18921 |
| trojan | 13975 |
| shadowsocks | 13893 |
| hysteria2 | 2195 |
| shadowsocksr | 376 |
| http | 118 |
| socks | 112 |
| hysteria | 76 |
| tuic | 60 |
| anytls | 35 |

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
| 77.43 | hysteria2 | 275.2 | 669.0 | 21.41 | 0.0 | 4.35 | 13.33 | 19.34 | dragon | 206.189.229.48 |
| 74.22 | trojan | 288.6 | 682.2 | 21.1 | 0.0 | 2.93 | 13.35 | 19.34 | dragon | 170.101.101.53 |
| 73.7 | trojan | 297.6 | 710.7 | 20.89 | 0.0 | 2.95 | 13.35 | 19.34 | dragon | 66.163.114.166 |
| 71.88 | trojan | 259.0 | 594.4 | 21.78 | 0.0 | 0.0 | 13.35 | 19.34 | dragon | 66.163.114.126 |
| 71.8 | shadowsocks | 293.6 | 667.6 | 20.98 | 0.0 | 5.6 | 13.2 | 19.34 | dragon | 185.215.132.18 |
| 71.63 | trojan | 264.7 | 596.7 | 21.65 | 0.0 | 0.0 | 13.35 | 19.34 | dragon | 66.163.114.114 |
| 71.44 | trojan | 377.9 | 863.2 | 19.03 | 0.0 | 8.11 | 13.35 | 19.34 | dragon | 66.163.122.26 |
| 71.09 | trojan | 259.0 | 587.2 | 21.78 | 0.0 | 0.0 | 13.35 | 19.34 | dragon | 66.163.114.45 |
| 70.69 | shadowsocks | 433.7 | 955.2 | 17.74 | 0.0 | 6.81 | 13.2 | 19.34 | dragon | 15.204.247.206 |
| 70.54 | trojan | 255.9 | 582.5 | 21.85 | 0.0 | 2.95 | 13.35 | 19.34 | dragon | 66.163.114.106 |
| 70.05 | trojan | 309.3 | 669.8 | 20.62 | 0.0 | 2.24 | 13.35 | 19.34 | dragon | 170.101.101.211 |
| 69.82 | hysteria2 | 441.8 | 1102.9 | 17.55 | 0.0 | 6.04 | 13.33 | 19.34 | dragon | 34.24.25.1 |
| 69.59 | shadowsocks | 434.1 | 873.5 | 17.73 | 0.0 | 6.39 | 13.2 | 19.34 | dragon | 167.88.63.99 |
| 69.54 | shadowsocks | 270.3 | 570.7 | 21.52 | 0.0 | 6.32 | 13.2 | 19.34 | dragon | 23.150.152.38 |
| 69.29 | trojan | 278.6 | 628.2 | 21.33 | 0.0 | 0.14 | 13.35 | 19.34 | dragon | 170.101.101.112 |
| 68.87 | trojan | 267.4 | 609.3 | 21.59 | 0.0 | 2.96 | 13.35 | 19.34 | dragon | 66.163.114.245 |
| 68.65 | trojan | 296.5 | 691.0 | 20.92 | 0.0 | 0.0 | 13.35 | 19.34 | dragon | 170.101.101.67 |
| 68.57 | shadowsocks | 259.5 | 552.5 | 21.77 | 0.0 | 6.41 | 13.2 | 19.34 | dragon | 216.105.168.18 |
| 68.35 | trojan | 323.2 | 677.2 | 20.3 | 0.0 | 2.89 | 13.35 | 19.34 | dragon | 66.163.112.147 |
| 67.9 | trojan | 359.1 | 777.4 | 19.47 | 0.0 | 2.79 | 13.35 | 19.34 | dragon | 66.163.112.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.897 | 0.909 | 22 | 548 | prefer |
| dragon | 0.692 | 0.614 | 114 | 43748 | observe |
| mheidari-all | 0.335 | 1.0 | 1 | 15005 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 165 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4964 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2915 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11563 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8824 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6113 | observe |
| barry-far-vless | 0.255 | None | 0 | 6293 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4545 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 23 |
| test_one_timeout | 15.0s | - | 13 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:33898: bind: address already in use | - | 1 |
| cn-block | TimeoutError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 71 | 45 | - |
| global | False | 71 | 47 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
