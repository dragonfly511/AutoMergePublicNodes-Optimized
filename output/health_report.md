# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-06 05:46:11 |
| 运行耗时 | 353.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 128615 |
| 去重后节点 | 59071 |
| TCP 可达 | 3000 |
| 真实可用 | 119 |
| Verified 输出 | 119 |
| Global 输出 | 119 |
| All 输出 | 59071 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.9 |
| geo | 1.5 |
| tcp | 197.8 |
| probe | 70.5 |
| real_test | 32.7 |
| china_check | 26.8 |
| write_verified | 0.0 |
| generate | 19.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 78929 |
| vmess | 18496 |
| trojan | 14777 |
| shadowsocks | 13359 |
| hysteria2 | 2322 |
| http | 269 |
| shadowsocksr | 205 |
| socks | 145 |
| hysteria | 45 |
| anytls | 36 |
| tuic | 32 |

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
| 82.31 | trojan | 240.0 | 548.8 | 22.22 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 66.163.114.126 |
| 82.26 | trojan | 242.4 | 584.4 | 22.17 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 216.152.155.158 |
| 81.84 | trojan | 260.3 | 665.4 | 21.75 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 216.152.155.54 |
| 81.82 | trojan | 261.5 | 648.4 | 21.73 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 216.152.155.59 |
| 81.25 | trojan | 285.7 | 706.9 | 21.16 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 170.101.101.67 |
| 80.54 | trojan | 303.6 | 807.2 | 20.75 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 216.152.155.23 |
| 79.5 | trojan | 345.2 | 523.4 | 19.79 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 66.163.114.114 |
| 79.05 | trojan | 301.2 | 678.8 | 20.81 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 170.101.101.211 |
| 78.67 | trojan | 258.6 | 599.9 | 21.79 | 0.0 | 6.79 | 13.45 | 19.14 | dragon | 66.163.114.166 |
| 77.84 | trojan | 309.6 | 679.0 | 20.61 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 216.152.156.65 |
| 77.65 | trojan | 320.4 | 711.0 | 20.36 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 216.152.156.212 |
| 77.42 | trojan | 308.7 | 686.4 | 20.63 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 216.152.156.42 |
| 76.69 | trojan | 238.5 | 554.4 | 22.26 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 66.163.114.245 |
| 76.3 | trojan | 259.9 | 601.4 | 21.76 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 66.163.114.106 |
| 76.17 | shadowsocks | 313.4 | 710.8 | 20.52 | 0.0 | 10.0 | 12.39 | 19.14 | dragon | 172.111.38.72 |
| 76.11 | trojan | 306.6 | 574.0 | 20.68 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 167.88.61.85 |
| 76.0 | trojan | 296.6 | 687.7 | 20.91 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 216.152.147.152 |
| 75.97 | trojan | 316.6 | 615.7 | 20.45 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 66.163.112.121 |
| 75.82 | trojan | 360.7 | 790.2 | 19.43 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 169.197.140.171 |
| 75.77 | trojan | 348.9 | 751.9 | 19.7 | 0.0 | 10.0 | 13.45 | 19.14 | dragon | 169.197.140.224 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.996 | 0.98 | 101 | 639 | prefer |
| dragon | 0.944 | 0.869 | 130 | 45886 | prefer |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8762 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5039 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2653 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10892 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6268 | observe |
| barry-far-vless | 0.255 | None | 0 | 6478 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4631 | observe |
| mheidari-all | 0.255 | None | 0 | 14233 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 8 |
| cn-block | ProxyError | - | 5 |
| 204 | TimeoutError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:39783: bind: address already in use | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | TimeoutError | - | 1 |
| speed | ClientPayloadError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 75 | 119 | - |
| global | False | 75 | 119 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
