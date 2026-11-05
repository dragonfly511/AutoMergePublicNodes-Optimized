# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-05 05:49:36 |
| 运行耗时 | 388.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 127236 |
| 去重后节点 | 58014 |
| TCP 可达 | 3000 |
| 真实可用 | 40 |
| Verified 输出 | 40 |
| Global 输出 | 40 |
| All 输出 | 58014 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.7 |
| geo | 1.8 |
| tcp | 204.8 |
| probe | 97.8 |
| real_test | 21.0 |
| china_check | 24.9 |
| write_verified | 0.0 |
| generate | 29.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77744 |
| vmess | 18140 |
| trojan | 14949 |
| shadowsocks | 13406 |
| hysteria2 | 2392 |
| shadowsocksr | 236 |
| socks | 107 |
| http | 98 |
| hysteria | 75 |
| tuic | 54 |
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
| 82.16 | trojan | 236.4 | 489.7 | 22.31 | 0.0 | 8.79 | 14.5 | 19.98 | dragon | 167.88.61.198 |
| 81.61 | trojan | 237.9 | 513.5 | 22.27 | 0.0 | 8.79 | 14.5 | 19.98 | dragon | 167.88.61.85 |
| 81.2 | trojan | 275.6 | 624.6 | 21.4 | 0.0 | 8.78 | 14.5 | 19.98 | dragon | 66.163.114.114 |
| 81.03 | trojan | 268.0 | 759.2 | 21.57 | 0.0 | 7.48 | 14.5 | 19.98 | dragon | 216.106.186.32 |
| 80.61 | trojan | 304.9 | 732.1 | 20.72 | 0.0 | 8.77 | 14.5 | 19.98 | dragon | 167.88.61.20 |
| 80.26 | trojan | 301.3 | 593.4 | 20.8 | 0.0 | 8.7 | 14.5 | 19.98 | dragon | 66.163.114.245 |
| 80.12 | trojan | 269.5 | 615.0 | 21.54 | 0.0 | 8.62 | 14.5 | 19.98 | dragon | 66.163.114.166 |
| 79.64 | shadowsocks | 230.0 | 514.2 | 22.45 | 0.0 | 8.66 | 13.82 | 19.98 | dragon | 38.145.220.193 |
| 79.25 | trojan | 208.3 | 573.1 | 22.96 | 0.0 | 7.31 | 14.5 | 19.98 | dragon | 216.106.186.66 |
| 79.0 | trojan | 298.7 | 614.2 | 20.86 | 0.0 | 10.0 | 14.5 | 19.98 | dragon | 66.163.112.121 |
| 78.9 | trojan | 201.6 | 552.9 | 23.11 | 0.0 | 8.81 | 14.5 | 19.98 | dragon | 216.106.186.82 |
| 78.54 | trojan | 230.5 | 506.4 | 22.44 | 0.0 | 10.0 | 14.5 | 19.98 | dragon | 167.88.61.52 |
| 78.28 | trojan | 317.8 | 754.3 | 20.42 | 0.0 | 7.64 | 14.5 | 19.98 | dragon | 66.163.114.106 |
| 78.23 | trojan | 239.0 | 527.8 | 22.24 | 0.0 | 7.13 | 14.5 | 19.98 | dragon | 167.88.61.193 |
| 77.49 | trojan | 293.9 | 605.7 | 20.97 | 0.0 | 8.68 | 14.5 | 19.98 | dragon | 66.163.112.13 |
| 77.23 | trojan | 232.3 | 510.3 | 22.4 | 0.0 | 8.72 | 14.5 | 19.98 | dragon | 167.88.61.175 |
| 76.66 | trojan | 359.4 | 683.7 | 19.46 | 0.0 | 10.0 | 14.5 | 19.98 | dragon | 216.152.155.158 |
| 76.6 | trojan | 294.8 | 600.2 | 20.95 | 0.0 | 8.7 | 14.5 | 19.98 | dragon | 66.163.112.76 |
| 76.46 | trojan | 291.6 | 588.1 | 21.03 | 0.0 | 7.02 | 14.5 | 19.98 | dragon | 66.163.112.242 |
| 76.01 | trojan | 334.7 | 722.3 | 20.03 | 0.0 | 7.73 | 14.5 | 19.98 | dragon | 66.163.112.142 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.947 | 0.873 | 118 | 44959 | prefer |
| ermaozi | 0.795 | 0.8 | 20 | 555 | prefer |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8675 | observe |
| mheidari-all | 0.335 | 1.0 | 1 | 14576 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2526 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10857 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6030 | observe |
| barry-far-vless | 0.255 | None | 0 | 6243 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4612 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 6 |
| test_one_timeout | 15.0s | - | 6 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:36608: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 50 | 40 | - |
| global | False | 52 | 40 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
