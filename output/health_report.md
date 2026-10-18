# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-18 00:17:53 |
| 运行耗时 | 323.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99128 |
| 去重后节点 | 27746 |
| TCP 可达 | 3000 |
| 真实可用 | 70 |
| Verified 输出 | 70 |
| Global 输出 | 78 |
| All 输出 | 27746 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.5 |
| tcp | 83.9 |
| probe | 98.9 |
| real_test | 93.7 |
| china_check | 28.9 |
| write_verified | 0.0 |
| generate | 10.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58465 |
| vmess | 16763 |
| shadowsocks | 11743 |
| trojan | 9923 |
| hysteria2 | 1351 |
| http | 611 |
| shadowsocksr | 160 |
| socks | 63 |
| anytls | 26 |
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
| 74.69 | vless | 261.2 | 678.1 | 21.73 | 0.0 | 10.0 | 8.3 | 14.66 | Au1rxx-base64 | 147.45.60.160 |
| 74.45 | shadowsocks | 252.1 | 622.6 | 21.94 | 0.0 | 10.0 | 11.85 | 14.66 | Au1rxx-base64 | 156.146.38.168 |
| 73.5 | shadowsocks | 256.9 | 624.3 | 21.83 | 0.0 | 10.0 | 11.85 | 14.66 | Au1rxx-base64 | 156.146.38.169 |
| 73.4 | shadowsocks | 254.2 | 635.9 | 21.89 | 0.0 | 10.0 | 11.85 | 14.66 | Au1rxx-base64 | 156.146.38.170 |
| 72.83 | shadowsocks | 288.6 | 724.2 | 21.1 | 0.0 | 9.92 | 11.85 | 14.66 | Au1rxx-base64 | 37.19.198.236 |
| 72.69 | hysteria2 | 274.9 | 721.6 | 21.41 | 0.0 | 7.12 | 11.0 | 14.66 | Au1rxx-base64 | 129.213.91.185 |
| 72.03 | shadowsocks | 356.7 | 938.0 | 19.52 | 0.0 | 10.0 | 11.85 | 14.66 | Au1rxx-base64 | 37.19.198.244 |
| 70.68 | shadowsocks | 288.8 | 732.4 | 21.09 | 0.0 | 10.0 | 11.85 | 14.66 | Au1rxx-base64 | 37.19.198.160 |
| 70.26 | vless | 258.5 | 636.3 | 21.8 | 0.0 | 10.0 | 8.3 | 14.66 | Au1rxx-base64 | 69.48.201.136 |
| 69.84 | shadowsocks | 292.8 | 735.5 | 21.0 | 0.0 | 6.33 | 11.85 | 14.66 | Au1rxx-base64 | 156.146.38.167 |
| 69.62 | shadowsocks | 244.9 | 597.3 | 22.11 | 0.0 | 10.0 | 11.85 | 14.66 | Au1rxx-base64 | 198.98.53.130 |
| 69.54 | vless | 311.2 | 722.5 | 20.57 | 0.0 | 6.83 | 8.3 | 14.66 | Au1rxx-base64 | 66.70.179.198 |
| 68.7 | shadowsocks | 324.7 | 663.7 | 20.26 | 0.0 | 10.0 | 11.85 | 14.66 | Au1rxx-base64 | 149.22.95.183 |
| 68.69 | shadowsocks | 284.9 | 722.5 | 21.18 | 0.0 | 10.0 | 11.85 | 14.66 | Au1rxx-base64 | 37.19.198.243 |
| 68.16 | vless | 276.9 | 649.6 | 21.37 | 0.0 | 10.0 | 8.3 | 14.66 | Au1rxx-base64 | 208.84.100.209 |
| 67.63 | shadowsocks | 332.9 | 589.5 | 20.07 | 0.0 | 10.0 | 11.85 | 14.66 | Au1rxx-base64 | 173.244.56.6 |
| 67.5 | shadowsocks | 345.1 | 687.9 | 19.79 | 0.0 | 10.0 | 11.85 | 14.66 | Au1rxx-base64 | 173.244.56.9 |
| 66.75 | shadowsocks | 359.1 | 953.2 | 19.46 | 0.0 | 5.28 | 11.85 | 14.66 | Au1rxx-base64 | 15.204.246.132 |
| 64.67 | shadowsocks | 367.2 | 950.8 | 19.28 | 0.0 | 6.38 | 11.85 | 14.66 | Au1rxx-base64 | 64.74.163.69 |
| 64.63 | vless | 329.6 | 617.9 | 20.15 | 0.0 | 6.59 | 8.3 | 14.66 | Au1rxx-base64 | 45.32.69.110 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.996 | 1.0 | 33 | 623 | prefer |
| Au1rxx-base64 | 0.883 | 0.805 | 364 | 1992 | prefer |
| Surfboard-tg-mixed | 0.673 | 0.6 | 25 | 7091 | observe |
| mheidari-all | 0.463 | 0.381 | 181 | 23876 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4986 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1992 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 4999 | observe |
| Epodonios-all | 0.255 | None | 0 | 7586 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9988 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5601 | observe |
| barry-far-vless | 0.255 | None | 0 | 5855 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4295 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 103 |
| speed | ClientOSError | - | 36 |
| geo | ClientOSError | - | 25 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| 204 | ClientOSError | - | 6 |
| 204 | TimeoutError | - | 4 |
| cn-block | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| speed | TimeoutError | - | 2 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 64 | 70 | - |
| global | False | 67 | 78 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
