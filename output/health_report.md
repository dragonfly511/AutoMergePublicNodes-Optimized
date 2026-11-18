# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-18 00:50:03 |
| 运行耗时 | 402.1s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 126303 |
| 去重后节点 | 58151 |
| TCP 可达 | 3000 |
| 真实可用 | 86 |
| Verified 输出 | 86 |
| Global 输出 | 87 |
| All 输出 | 58151 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.6 |
| tcp | 189.9 |
| probe | 100.3 |
| real_test | 45.1 |
| china_check | 35.5 |
| write_verified | 0.4 |
| generate | 23.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77429 |
| vmess | 18751 |
| shadowsocks | 13907 |
| trojan | 13519 |
| hysteria2 | 2041 |
| shadowsocksr | 241 |
| socks | 147 |
| http | 135 |
| hysteria | 53 |
| tuic | 53 |
| anytls | 27 |

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
| 74.45 | shadowsocks | 240.5 | 543.6 | 22.21 | 0.0 | 5.65 | 13.19 | 18.62 | dragon | 38.145.220.193 |
| 73.15 | hysteria2 | 220.8 | 498.1 | 22.67 | 0.0 | 0.0 | 12.86 | 18.62 | dragon | 66.94.121.46 |
| 72.03 | shadowsocks | 336.0 | 816.2 | 20.0 | 0.0 | 5.68 | 13.19 | 18.62 | dragon | 169.197.142.68 |
| 71.15 | shadowsocks | 207.7 | 550.6 | 22.97 | 0.0 | 5.87 | 13.19 | 18.62 | dragon | 38.143.66.146 |
| 70.98 | shadowsocks | 237.1 | 532.3 | 22.29 | 0.0 | 5.65 | 13.19 | 18.62 | dragon | 104.238.140.45 |
| 69.79 | shadowsocks | 476.9 | 1289.0 | 16.74 | 0.0 | 5.74 | 13.19 | 18.62 | dragon | 137.184.89.151 |
| 69.21 | hysteria2 | 216.6 | 226.6 | 22.76 | 6.5 | 0.0 | 12.86 | 18.62 | dragon | 8.209.247.109 |
| 68.82 | shadowsocks | 364.8 | 852.5 | 19.33 | 0.0 | 5.5 | 13.19 | 18.62 | dragon | 167.88.62.203 |
| 68.26 | shadowsocks | 274.3 | 602.8 | 21.43 | 0.0 | 5.52 | 13.19 | 18.62 | dragon | 95.215.201.18 |
| 68.15 | shadowsocks | 372.6 | 820.8 | 19.15 | 0.0 | 5.39 | 13.19 | 18.62 | dragon | 156.146.38.170 |
| 68.13 | shadowsocks | 350.3 | 701.2 | 19.67 | 0.0 | 6.47 | 13.19 | 18.62 | dragon | 185.215.132.9 |
| 67.54 | shadowsocks | 392.1 | 927.3 | 18.7 | 0.0 | 5.45 | 13.19 | 18.62 | dragon | 167.17.67.171 |
| 67.28 | shadowsocks | 395.6 | 936.4 | 18.62 | 0.0 | 5.5 | 13.19 | 18.62 | dragon | 167.88.62.56 |
| 66.83 | shadowsocks | 371.5 | 753.8 | 19.18 | 0.0 | 5.35 | 13.19 | 18.62 | dragon | 172.111.38.72 |
| 66.62 | shadowsocks | 330.6 | 686.0 | 20.13 | 0.0 | 5.3 | 13.19 | 18.62 | dragon | 156.146.38.168 |
| 66.33 | shadowsocks | 414.0 | 425.1 | 18.19 | 0.0 | 8.97 | 13.19 | 18.62 | dragon | 149.88.106.74 |
| 66.29 | shadowsocks | 412.4 | 888.7 | 18.23 | 0.0 | 5.44 | 13.19 | 18.62 | dragon | 216.106.178.169 |
| 66.26 | shadowsocks | 293.0 | 693.6 | 20.99 | 0.0 | 4.08 | 13.19 | 18.62 | dragon | 23.150.152.38 |
| 66.26 | hysteria2 | 343.7 | 727.6 | 19.82 | 0.0 | 0.0 | 12.86 | 18.62 | dragon | 206.189.229.48 |
| 65.78 | shadowsocks | 370.5 | 760.4 | 19.2 | 0.0 | 5.28 | 13.19 | 18.62 | dragon | 185.230.230.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.996 | 0.919 | 285 | 44296 | prefer |
| ermaozi | 0.849 | 0.895 | 19 | 502 | prefer |
| tg-ShadowsocksM | 0.69 | 1.0 | 12 | 64 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4928 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2790 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11681 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8416 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5789 | observe |
| barry-far-vless | 0.255 | None | 0 | 5968 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4460 | observe |
| mheidari-all | 0.255 | None | 0 | 14610 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 11 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 4 |
| geo | ClientOSError | - | 3 |
| speed | TimeoutError | - | 2 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 77 | 86 | - |
| global | False | 77 | 87 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
