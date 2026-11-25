# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-25 07:43:10 |
| 运行耗时 | 444.3s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 122393 |
| 去重后节点 | 58838 |
| TCP 可达 | 3000 |
| 真实可用 | 111 |
| Verified 输出 | 111 |
| Global 输出 | 115 |
| All 输出 | 58838 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.6 |
| geo | 1.7 |
| tcp | 201.3 |
| probe | 110.3 |
| real_test | 53.6 |
| china_check | 37.7 |
| write_verified | 0.1 |
| generate | 31.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 74323 |
| vmess | 19296 |
| shadowsocks | 12967 |
| trojan | 12662 |
| hysteria2 | 2341 |
| shadowsocksr | 234 |
| http | 198 |
| socks | 196 |
| hysteria | 62 |
| anytls | 59 |
| tuic | 55 |

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
| 81.41 | shadowsocks | 180.6 | 468.4 | 23.6 | 0.0 | 9.31 | 13.92 | 19.08 | dragon | 104.238.140.45 |
| 80.63 | shadowsocks | 226.7 | 523.6 | 22.53 | 0.0 | 9.1 | 13.92 | 19.08 | dragon | 173.244.56.6 |
| 80.09 | shadowsocks | 236.1 | 631.0 | 22.31 | 0.0 | 9.28 | 13.92 | 19.08 | dragon | 23.150.152.38 |
| 80.0 | shadowsocks | 241.7 | 686.3 | 22.18 | 0.0 | 9.32 | 13.92 | 19.08 | dragon | 137.184.89.151 |
| 79.38 | shadowsocks | 266.2 | 529.7 | 21.62 | 0.0 | 9.26 | 13.92 | 19.08 | dragon | 95.215.201.18 |
| 79.18 | shadowsocks | 277.4 | 763.4 | 21.36 | 0.0 | 9.32 | 13.92 | 19.08 | dragon | 169.197.142.68 |
| 77.59 | shadowsocks | 251.9 | 570.3 | 21.95 | 0.0 | 6.64 | 13.92 | 19.08 | dragon | 149.22.95.183 |
| 77.13 | trojan | 174.3 | 461.4 | 23.74 | 0.0 | 9.31 | 7.5 | 19.08 | dragon | 167.88.61.85 |
| 76.62 | shadowsocks | 252.3 | 514.1 | 21.94 | 0.0 | 9.29 | 13.92 | 19.08 | dragon | 173.244.56.9 |
| 76.01 | shadowsocks | 295.7 | 668.8 | 20.93 | 0.0 | 8.87 | 13.92 | 19.08 | dragon | 156.146.38.169 |
| 75.7 | shadowsocks | 303.5 | 692.9 | 20.75 | 0.0 | 8.88 | 13.92 | 19.08 | dragon | 156.146.38.168 |
| 75.58 | hysteria2 | 262.3 | 540.6 | 21.71 | 0.0 | 8.29 | 7.5 | 19.08 | dragon | 66.94.121.46 |
| 74.58 | http | 190.1 | 470.3 | 23.38 | 0.0 | 0.0 | 14.32 | 19.38 | ermaozi | 172.64.69.89 |
| 74.54 | vless | 178.8 | 500.2 | 23.64 | 0.0 | 9.32 | 7.5 | 19.08 | dragon | 147.224.54.25 |
| 74.3 | vless | 188.8 | 488.6 | 23.41 | 0.0 | 9.31 | 7.5 | 19.08 | dragon | 179.254.94.184 |
| 74.06 | http | 191.0 | 487.6 | 23.36 | 0.0 | 0.0 | 14.32 | 19.38 | ermaozi | 38.95.111.226 |
| 73.91 | vless | 205.5 | 523.8 | 23.02 | 0.0 | 9.31 | 7.5 | 19.08 | dragon | 172.235.50.209 |
| 73.89 | vless | 206.3 | 520.3 | 23.0 | 0.0 | 9.31 | 7.5 | 19.08 | dragon | 172.235.36.11 |
| 73.88 | vless | 206.6 | 515.2 | 22.99 | 0.0 | 9.31 | 7.5 | 19.08 | dragon | 172.236.239.126 |
| 73.88 | vless | 206.7 | 513.3 | 22.99 | 0.0 | 9.31 | 7.5 | 19.08 | dragon | 172.236.238.71 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.965 | 0.888 | 285 | 43982 | prefer |
| ermaozi | 0.96 | 0.96 | 50 | 442 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4839 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11515 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8136 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5440 | observe |
| barry-far-vless | 0.255 | None | 0 | 5649 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4565 | observe |
| mheidari-all | 0.255 | None | 0 | 14996 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 20 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyError | - | 2 |
| 204 | TimeoutError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:40120: bind: address already in use | - | 1 |
| geo | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 88 | 111 | - |
| global | False | 88 | 115 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
