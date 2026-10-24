# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-24 10:39:01 |
| 运行耗时 | 436.6s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 138286 |
| 去重后节点 | 58672 |
| TCP 可达 | 3000 |
| 真实可用 | 57 |
| Verified 输出 | 57 |
| Global 输出 | 58 |
| All 输出 | 58672 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.5 |
| geo | 1.8 |
| tcp | 202.8 |
| probe | 122.7 |
| real_test | 51.8 |
| china_check | 23.1 |
| write_verified | 0.0 |
| generate | 26.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 85068 |
| vmess | 20590 |
| shadowsocks | 16394 |
| trojan | 13450 |
| hysteria2 | 1968 |
| http | 287 |
| shadowsocksr | 258 |
| socks | 144 |
| hysteria | 47 |
| tuic | 43 |
| anytls | 37 |

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
| 77.65 | shadowsocks | 310.1 | 576.0 | 20.6 | 0.0 | 9.56 | 12.97 | 18.52 | dragon | 156.146.38.168 |
| 77.63 | shadowsocks | 318.2 | 589.0 | 20.41 | 0.0 | 9.73 | 12.97 | 18.52 | dragon | 156.146.38.169 |
| 77.29 | shadowsocks | 333.1 | 838.3 | 20.07 | 0.0 | 9.73 | 12.97 | 18.52 | dragon | 156.146.38.167 |
| 74.25 | shadowsocks | 331.0 | 652.1 | 20.12 | 0.0 | 9.68 | 12.97 | 18.52 | dragon | 173.244.56.9 |
| 74.24 | hysteria2 | 363.4 | 873.1 | 19.36 | 0.0 | 6.74 | 12.63 | 18.52 | dragon | 129.213.91.185 |
| 73.8 | shadowsocks | 251.7 | 600.8 | 21.95 | 0.0 | 9.67 | 12.97 | 18.52 | dragon | 173.244.56.6 |
| 71.91 | shadowsocks | 435.6 | 1087.1 | 17.69 | 0.0 | 10.0 | 12.97 | 18.52 | dragon | 185.215.132.18 |
| 71.88 | shadowsocks | 359.2 | 767.7 | 19.46 | 0.0 | 9.96 | 12.97 | 18.52 | dragon | 185.230.230.18 |
| 71.41 | shadowsocks | 370.0 | 809.5 | 19.21 | 0.0 | 9.39 | 12.97 | 18.52 | dragon | 37.19.198.160 |
| 71.09 | shadowsocks | 371.8 | 814.5 | 19.17 | 0.0 | 9.19 | 12.97 | 18.52 | dragon | 37.19.198.244 |
| 70.96 | shadowsocks | 372.6 | 818.8 | 19.15 | 0.0 | 9.19 | 12.97 | 18.52 | dragon | 37.19.198.243 |
| 70.8 | shadowsocks | 435.5 | 1041.3 | 17.7 | 0.0 | 9.98 | 12.97 | 18.52 | dragon | 193.151.160.18 |
| 70.77 | shadowsocks | 439.2 | 1057.0 | 17.61 | 0.0 | 9.99 | 12.97 | 18.52 | dragon | 193.151.160.9 |
| 70.57 | shadowsocks | 367.7 | 769.7 | 19.27 | 0.0 | 9.55 | 12.97 | 18.52 | dragon | 193.151.163.18 |
| 69.75 | shadowsocks | 442.1 | 1029.9 | 17.54 | 0.0 | 9.96 | 12.97 | 18.52 | dragon | 45.86.51.18 |
| 69.57 | hysteria2 | 361.0 | 719.4 | 19.42 | 0.0 | 0.0 | 12.63 | 18.52 | dragon | 66.94.121.46 |
| 69.11 | shadowsocks | 265.9 | 635.6 | 21.62 | 0.0 | 0.0 | 12.97 | 18.52 | dragon | 156.146.38.170 |
| 68.73 | hysteria2 | 481.5 | 795.5 | 16.63 | 0.0 | 9.06 | 12.63 | 18.52 | dragon | 130.49.161.70 |
| 67.94 | shadowsocks | 367.9 | 803.6 | 19.26 | 0.0 | 9.23 | 12.97 | 18.52 | dragon | 37.19.198.236 |
| 66.54 | shadowsocks | 443.0 | 1101.3 | 17.52 | 0.0 | 9.55 | 12.97 | 18.52 | dragon | 185.215.132.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.984 | 0.909 | 165 | 45691 | prefer |
| ermaozi | 0.635 | 0.615 | 52 | 608 | observe |
| tg-oneclickvpnkeys | 0.316 | 1.0 | 2 | 113 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4911 | observe |
| Epodonios-all | 0.255 | None | 0 | 7652 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10213 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7180 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5436 | observe |
| barry-far-vless | 0.255 | None | 0 | 5737 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4150 | observe |
| mheidari-all | 0.255 | None | 0 | 23868 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.238 | None | 0 | 1579 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 12 |
| geo | ProxyError | - | 7 |
| cn-block | ProxyError | - | 7 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 2 |
| cn-block | TimeoutError | - | 1 |
| speed | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 82 | 57 | - |
| global | False | 83 | 58 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
