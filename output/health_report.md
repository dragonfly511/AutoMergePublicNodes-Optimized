# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-22 05:49:06 |
| 运行耗时 | 389.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 128123 |
| 去重后节点 | 59341 |
| TCP 可达 | 3000 |
| 真实可用 | 91 |
| Verified 输出 | 91 |
| Global 输出 | 95 |
| All 输出 | 59341 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.6 |
| geo | 1.5 |
| tcp | 176.4 |
| probe | 101.7 |
| real_test | 48.4 |
| china_check | 37.1 |
| write_verified | 0.0 |
| generate | 19.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77828 |
| vmess | 19230 |
| shadowsocks | 14423 |
| trojan | 13708 |
| hysteria2 | 2095 |
| shadowsocksr | 385 |
| socks | 186 |
| http | 115 |
| hysteria | 69 |
| tuic | 56 |
| anytls | 28 |

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
| 69.86 | http | 206.8 | 496.5 | 22.99 | 0.0 | 0.0 | 14.29 | 18.08 | ermaozi | 172.64.69.89 |
| 69.73 | http | 207.7 | 514.8 | 22.97 | 0.0 | 0.0 | 14.29 | 18.08 | ermaozi | 172.64.68.89 |
| 67.78 | hysteria2 | 226.5 | 512.3 | 22.53 | 0.0 | 9.9 | 9.71 | 11.74 | dragon | 172.87.24.53 |
| 67.7 | vless | 229.7 | 511.4 | 22.46 | 0.0 | 10.0 | 10.0 | 11.74 | dragon | 69.17.3.150 |
| 63.64 | shadowsocks | 272.8 | 573.0 | 21.46 | 0.0 | 10.0 | 11.25 | 11.74 | dragon | 147.224.251.204 |
| 63.55 | vless | 280.4 | 596.2 | 21.29 | 0.0 | 9.22 | 10.0 | 11.74 | dragon | 172.236.231.45 |
| 62.31 | hysteria2 | 255.7 | 636.8 | 21.86 | 0.0 | 0.0 | 9.71 | 11.74 | dragon | 66.94.121.46 |
| 62.25 | shadowsocks | 197.8 | 513.2 | 23.2 | 0.0 | 2.76 | 11.25 | 11.74 | dragon | 149.22.95.183 |
| 60.83 | http | 425.1 | 939.0 | 17.94 | 0.0 | 0.0 | 14.29 | 18.08 | ermaozi | 38.247.141.135 |
| 60.8 | vless | 439.8 | 918.6 | 17.6 | 0.0 | 9.98 | 10.0 | 11.74 | dragon | 67.220.73.204 |
| 60.45 | shadowsocks | 251.4 | 638.3 | 21.96 | 0.0 | 0.0 | 11.25 | 11.74 | dragon | 137.184.89.151 |
| 60.42 | shadowsocks | 227.3 | 538.6 | 22.52 | 0.0 | 0.0 | 11.25 | 11.74 | dragon | 23.150.152.38 |
| 60.23 | shadowsocks | 226.9 | 516.7 | 22.53 | 0.0 | 0.0 | 11.25 | 11.74 | dragon | 104.238.140.45 |
| 59.11 | shadowsocks | 449.0 | 963.8 | 17.38 | 0.0 | 9.08 | 11.25 | 11.74 | dragon | 158.51.121.221 |
| 57.57 | shadowsocks | 275.0 | 570.7 | 21.41 | 0.0 | 1.52 | 11.25 | 11.74 | dragon | 173.244.56.9 |
| 56.9 | shadowsocks | 275.1 | 770.0 | 21.41 | 0.0 | 0.0 | 11.25 | 11.74 | dragon | 38.143.66.146 |
| 56.74 | shadowsocks | 288.3 | 292.5 | 21.1 | 4.03 | 0.0 | 11.25 | 11.74 | dragon | 149.22.87.241 |
| 56.74 | shadowsocks | 369.9 | 712.0 | 19.22 | 0.0 | 9.96 | 11.25 | 11.74 | dragon | 67.220.73.247 |
| 56.47 | hysteria2 | 459.7 | 1081.7 | 17.14 | 0.0 | 2.65 | 9.71 | 11.74 | dragon | 34.24.25.1 |
| 56.19 | hysteria2 | 248.1 | 268.7 | 22.03 | 4.92 | 0.0 | 9.71 | 11.74 | dragon | 8.209.247.109 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.956 | 0.879 | 256 | 44788 | prefer |
| ermaozi | 0.862 | 0.875 | 24 | 399 | prefer |
| zhangkai | 0.654 | 1.0 | 11 | 27 | observe |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 8778 | observe |
| ermaozi-get_subscribe | 0.282 | 0.667 | 3 | 327 | observe |
| tg-oneclickvpnkeys | 0.261 | 1.0 | 1 | 141 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5030 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2989 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 12093 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5942 | observe |
| barry-far-vless | 0.255 | None | 0 | 6124 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4482 | observe |
| mheidari-all | 0.255 | None | 0 | 14302 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 20 |
| cn-block | ClientOSError | - | 4 |
| 204 | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| speed | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 27 | 91 | - |
| global | False | 28 | 95 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
