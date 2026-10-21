# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-21 16:27:06 |
| 运行耗时 | 290.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96616 |
| 去重后节点 | 26908 |
| TCP 可达 | 3000 |
| 真实可用 | 89 |
| Verified 输出 | 89 |
| Global 输出 | 94 |
| All 输出 | 26908 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.6 |
| tcp | 82.3 |
| probe | 101.1 |
| real_test | 62.6 |
| china_check | 21.6 |
| write_verified | 0.0 |
| generate | 13.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57463 |
| vmess | 17063 |
| shadowsocks | 11921 |
| trojan | 8550 |
| hysteria2 | 1248 |
| shadowsocksr | 161 |
| http | 110 |
| socks | 56 |
| anytls | 21 |
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
| 76.06 | shadowsocks | 250.6 | 672.4 | 21.98 | 0.0 | 9.49 | 13.55 | 15.04 | Au1rxx-base64 | 37.19.198.243 |
| 75.77 | shadowsocks | 244.1 | 684.2 | 22.13 | 0.0 | 9.55 | 13.55 | 15.04 | Au1rxx-base64 | 185.230.230.18 |
| 74.83 | shadowsocks | 241.0 | 656.0 | 22.2 | 0.0 | 9.54 | 13.55 | 15.04 | Au1rxx-base64 | 193.151.163.18 |
| 73.69 | shadowsocks | 333.9 | 957.2 | 20.05 | 0.0 | 9.55 | 13.55 | 15.04 | Au1rxx-base64 | 45.86.51.18 |
| 73.0 | shadowsocks | 384.5 | 1082.6 | 18.88 | 0.0 | 9.53 | 13.55 | 15.04 | Au1rxx-base64 | 37.19.198.244 |
| 72.97 | shadowsocks | 281.1 | 638.4 | 21.27 | 0.0 | 9.19 | 13.55 | 15.04 | Au1rxx-base64 | 156.146.38.169 |
| 72.89 | shadowsocks | 285.5 | 610.7 | 21.17 | 0.0 | 8.84 | 13.55 | 15.04 | Au1rxx-base64 | 156.146.38.167 |
| 72.79 | vless | 295.5 | 726.8 | 20.94 | 0.0 | 8.6 | 8.21 | 15.04 | Au1rxx-base64 | 66.70.179.198 |
| 72.27 | vless | 230.7 | 601.7 | 22.44 | 0.0 | 6.58 | 8.21 | 15.04 | Au1rxx-base64 | 195.123.235.183 |
| 71.26 | shadowsocks | 371.7 | 1029.9 | 19.17 | 0.0 | 9.5 | 13.55 | 15.04 | Au1rxx-base64 | 37.19.198.160 |
| 70.56 | shadowsocks | 411.4 | 1068.3 | 18.25 | 0.0 | 9.3 | 13.55 | 15.04 | Au1rxx-base64 | 193.151.160.9 |
| 70.1 | shadowsocks | 381.6 | 967.9 | 18.95 | 0.0 | 9.36 | 13.55 | 15.04 | Au1rxx-base64 | 193.151.160.18 |
| 70.08 | shadowsocks | 258.6 | 718.7 | 21.79 | 0.0 | 0.0 | 13.55 | 18.74 | mheidari-all | 37.19.198.236 |
| 69.67 | http | 237.5 | 660.5 | 22.28 | 0.0 | 0.0 | 14.49 | 18.9 | ermaozi-get_subscribe | 198.44.135.19 |
| 67.53 | shadowsocks | 344.0 | 654.7 | 19.82 | 0.0 | 8.91 | 13.55 | 15.04 | Au1rxx-base64 | 149.22.95.183 |
| 66.43 | hysteria2 | 363.3 | 707.7 | 19.37 | 0.0 | 5.23 | 13.75 | 15.04 | Au1rxx-base64 | 62.210.124.146 |
| 64.95 | shadowsocks | 355.0 | 966.1 | 19.56 | 0.0 | 0.0 | 13.55 | 16.34 | Surfboard-tg-mixed | 185.215.132.18 |
| 64.91 | http | 402.2 | 928.6 | 18.47 | 0.0 | 0.0 | 14.49 | 19.32 | zhangkai | 38.247.141.135 |
| 64.64 | hysteria2 | 256.2 | 675.6 | 21.85 | 0.0 | 0.0 | 13.75 | 15.04 | Au1rxx-base64 | clash2.deep-links.com |
| 64.64 | vless | 309.6 | 680.1 | 20.61 | 0.0 | 7.82 | 8.21 | 15.04 | Au1rxx-base64 | 69.48.201.136 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.932 | 0.963 | 27 | 31 | prefer |
| Surfboard-tg-mixed | 0.875 | 0.81 | 42 | 7070 | prefer |
| mheidari-all | 0.827 | 0.753 | 81 | 24102 | prefer |
| Au1rxx-base64 | 0.774 | 0.713 | 157 | 1579 | prefer |
| ermaozi-get_subscribe | 0.668 | 1.0 | 11 | 385 | observe |
| Au1rxx-clash | 0.383 | 0.75 | 4 | 1568 | observe |
| ninja-vless | 0.327 | 1.0 | 1 | 1791 | observe |
| tg-oneclickvpnkeys | 0.273 | 0.667 | 3 | 108 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4925 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 4067 | observe |
| Epodonios-all | 0.255 | None | 0 | 7559 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10165 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5554 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 41 |
| speed | ClientOSError | - | 8 |
| cn-block | TimeoutError | - | 6 |
| geo | ClientOSError | - | 5 |
| 204 | TimeoutError | - | 5 |
| cn-block | ClientOSError | - | 4 |
| 204 | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | TimeoutError | - | 2 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 122 | 89 | - |
| global | False | 128 | 94 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
