# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-21 10:59:43 |
| 运行耗时 | 304.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96052 |
| 去重后节点 | 26942 |
| TCP 可达 | 3000 |
| 真实可用 | 122 |
| Verified 输出 | 122 |
| Global 输出 | 128 |
| All 输出 | 26942 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.5 |
| tcp | 81.3 |
| probe | 108.6 |
| real_test | 67.6 |
| china_check | 24.0 |
| write_verified | 0.1 |
| generate | 14.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57199 |
| vmess | 16923 |
| shadowsocks | 11858 |
| trojan | 8409 |
| hysteria2 | 1215 |
| http | 173 |
| shadowsocksr | 165 |
| socks | 63 |
| anytls | 24 |
| hysteria | 17 |
| tuic | 6 |

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
| 79.2 | shadowsocks | 240.8 | 668.0 | 22.2 | 0.0 | 10.0 | 13.98 | 17.02 | Au1rxx-base64 | 37.19.198.244 |
| 78.81 | shadowsocks | 258.0 | 657.4 | 21.81 | 0.0 | 10.0 | 13.98 | 17.02 | Au1rxx-base64 | 37.19.198.243 |
| 77.64 | shadowsocks | 243.5 | 654.2 | 22.14 | 0.0 | 10.0 | 13.98 | 17.02 | Au1rxx-base64 | 185.230.230.18 |
| 76.19 | shadowsocks | 306.0 | 866.6 | 20.69 | 0.0 | 10.0 | 13.98 | 17.02 | Au1rxx-base64 | 45.86.51.18 |
| 75.88 | shadowsocks | 254.6 | 704.7 | 21.88 | 0.0 | 10.0 | 13.98 | 17.02 | Au1rxx-base64 | 37.19.198.160 |
| 75.31 | shadowsocks | 321.2 | 761.2 | 20.34 | 0.0 | 10.0 | 13.98 | 17.02 | Au1rxx-base64 | 156.146.38.167 |
| 75.14 | shadowsocks | 315.3 | 742.3 | 20.48 | 0.0 | 10.0 | 13.98 | 17.02 | Au1rxx-base64 | 156.146.38.170 |
| 74.9 | shadowsocks | 362.0 | 959.3 | 19.4 | 0.0 | 10.0 | 13.98 | 17.02 | Au1rxx-base64 | 185.215.132.18 |
| 74.78 | shadowsocks | 367.1 | 983.8 | 19.28 | 0.0 | 10.0 | 13.98 | 17.02 | Au1rxx-base64 | 185.215.132.9 |
| 73.38 | shadowsocks | 367.1 | 1053.3 | 19.28 | 0.0 | 7.6 | 13.98 | 17.02 | Au1rxx-base64 | 15.204.246.132 |
| 72.0 | http | 282.2 | 764.4 | 21.25 | 0.0 | 0.0 | 14.61 | 19.64 | ermaozi-get_subscribe | 172.64.69.89 |
| 70.97 | shadowsocks | 351.4 | 681.0 | 19.64 | 0.0 | 10.0 | 13.98 | 17.02 | Au1rxx-base64 | 149.22.95.183 |
| 70.59 | http | 302.8 | 723.8 | 20.77 | 0.0 | 0.0 | 14.61 | 19.64 | ermaozi-get_subscribe | 35.183.131.26 |
| 69.9 | vless | 293.4 | 729.1 | 20.99 | 0.0 | 6.08 | 5.81 | 17.02 | Au1rxx-base64 | 66.70.179.198 |
| 69.07 | shadowsocks | 280.9 | 644.3 | 21.28 | 0.0 | 0.0 | 13.98 | 19.7 | Surfboard-tg-mixed | 156.146.38.169 |
| 69.01 | shadowsocks | 256.4 | 675.2 | 21.84 | 0.0 | 0.0 | 13.98 | 19.7 | Surfboard-tg-mixed | 193.151.163.18 |
| 68.61 | shadowsocks | 382.2 | 820.7 | 18.93 | 0.0 | 10.0 | 13.98 | 17.02 | Au1rxx-base64 | 95.215.201.18 |
| 68.24 | http | 358.0 | 868.1 | 19.49 | 0.0 | 0.0 | 14.61 | 19.64 | ermaozi-get_subscribe | 206.223.161.47 |
| 68.03 | http | 314.1 | 656.6 | 20.51 | 0.0 | 0.0 | 14.61 | 19.64 | ermaozi-get_subscribe | 23.133.176.14 |
| 67.53 | http | 516.4 | 1391.6 | 15.82 | 0.0 | 0.0 | 14.61 | 19.64 | ermaozi-get_subscribe | 206.223.183.16 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | 1.0 | 26 | 31 | prefer |
| ermaozi-get_subscribe | 0.945 | 0.938 | 64 | 516 | prefer |
| mheidari-all | 0.937 | 0.87 | 54 | 23726 | prefer |
| Surfboard-tg-mixed | 0.817 | 0.742 | 93 | 6977 | prefer |
| Au1rxx-base64 | 0.752 | 0.693 | 202 | 1528 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4925 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 4067 | observe |
| Epodonios-all | 0.255 | None | 0 | 7465 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10264 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5462 | observe |
| barry-far-vless | 0.255 | None | 0 | 5763 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4127 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 57 |
| speed | ClientOSError | - | 11 |
| geo | ClientOSError | - | 9 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyError | - | 4 |
| 204 | TimeoutError | - | 4 |
| cn-block | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 110 | 122 | - |
| global | False | 114 | 128 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
