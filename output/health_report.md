# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-19 02:39:11 |
| 运行耗时 | 305.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 97404 |
| 去重后节点 | 27723 |
| TCP 可达 | 3000 |
| 真实可用 | 70 |
| Verified 输出 | 70 |
| Global 输出 | 73 |
| All 输出 | 27723 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.2 |
| geo | 1.4 |
| tcp | 88.3 |
| probe | 87.0 |
| real_test | 84.3 |
| china_check | 32.0 |
| write_verified | 0.0 |
| generate | 8.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57179 |
| vmess | 16708 |
| shadowsocks | 11584 |
| trojan | 9550 |
| hysteria2 | 1336 |
| http | 761 |
| shadowsocksr | 164 |
| socks | 70 |
| anytls | 29 |
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
| 78.24 | hysteria2 | 272.6 | 577.8 | 21.47 | 0.0 | 9.98 | 12.27 | 16.5 | Au1rxx-base64 | 66.94.121.46 |
| 78.15 | shadowsocks | 248.5 | 617.9 | 22.02 | 0.0 | 10.0 | 13.63 | 16.5 | Au1rxx-base64 | 156.146.38.168 |
| 77.31 | shadowsocks | 249.8 | 630.0 | 22.0 | 0.0 | 9.18 | 13.63 | 16.5 | Au1rxx-base64 | 156.146.38.167 |
| 77.22 | shadowsocks | 259.1 | 646.0 | 21.78 | 0.0 | 10.0 | 13.63 | 16.5 | Au1rxx-base64 | 156.146.38.170 |
| 75.64 | shadowsocks | 307.2 | 749.2 | 20.67 | 0.0 | 10.0 | 13.63 | 16.5 | Au1rxx-base64 | 37.19.198.160 |
| 73.48 | shadowsocks | 284.0 | 567.4 | 21.2 | 0.0 | 10.0 | 13.63 | 16.5 | Au1rxx-base64 | 173.244.56.6 |
| 72.86 | hysteria2 | 278.7 | 713.1 | 21.33 | 0.0 | 4.26 | 12.27 | 16.5 | Au1rxx-base64 | 129.213.91.185 |
| 71.72 | vless | 287.6 | 730.2 | 21.12 | 0.0 | 7.62 | 8.48 | 16.5 | Au1rxx-base64 | 162.35.126.130 |
| 70.55 | http | 267.4 | 641.0 | 21.59 | 0.0 | 0.0 | 13.24 | 18.22 | ermaozi | 172.64.68.89 |
| 70.47 | shadowsocks | 303.4 | 738.3 | 20.76 | 0.0 | 10.0 | 13.63 | 16.5 | Au1rxx-base64 | 37.19.198.243 |
| 69.98 | trojan | 412.6 | 1029.5 | 18.23 | 0.0 | 8.21 | 11.67 | 16.5 | Au1rxx-base64 | 69.164.240.85 |
| 69.6 | vless | 279.0 | 654.8 | 21.32 | 0.0 | 8.53 | 8.48 | 16.5 | Au1rxx-base64 | 69.48.201.136 |
| 69.06 | vless | 296.3 | 586.3 | 20.92 | 0.0 | 9.82 | 8.48 | 16.5 | Au1rxx-base64 | 45.63.53.81 |
| 68.08 | vless | 360.3 | 798.1 | 19.44 | 0.0 | 7.02 | 8.48 | 16.5 | Au1rxx-base64 | 66.70.179.198 |
| 68.05 | vless | 280.9 | 545.0 | 21.27 | 0.0 | 9.99 | 8.48 | 16.5 | Au1rxx-base64 | 131.143.180.87 |
| 67.77 | vless | 248.0 | 625.8 | 22.04 | 0.0 | 5.75 | 8.48 | 16.5 | Au1rxx-base64 | 181.214.152.137 |
| 67.46 | shadowsocks | 426.1 | 620.3 | 17.91 | 0.0 | 10.0 | 13.63 | 16.5 | Au1rxx-base64 | 103.11.76.248 |
| 67.17 | shadowsocks | 240.2 | 609.6 | 22.22 | 0.0 | 0.0 | 13.63 | 15.32 | Surfboard-tg-mixed | 156.146.38.169 |
| 67.14 | hysteria2 | 518.3 | 884.0 | 15.78 | 0.0 | 9.87 | 12.27 | 16.5 | Au1rxx-base64 | 5.129.235.85 |
| 66.11 | http | 330.1 | 797.3 | 20.14 | 0.0 | 0.0 | 13.24 | 18.22 | ermaozi | 121.127.34.82 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.93 | 0.91 | 100 | 696 | prefer |
| Au1rxx-base64 | 0.905 | 0.84 | 300 | 1675 | prefer |
| Surfboard-tg-mixed | 0.782 | 0.705 | 112 | 7003 | prefer |
| mheidari-all | 0.666 | 0.588 | 114 | 23518 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4983 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 4750 | observe |
| Epodonios-all | 0.255 | None | 0 | 7467 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9938 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5523 | observe |
| barry-far-vless | 0.255 | None | 0 | 5700 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4246 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.242 | None | 0 | 1675 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 64 |
| speed | ClientOSError | - | 30 |
| geo | ClientOSError | - | 18 |
| 204 | ProxyError | - | 5 |
| geo | ProxyError | - | 4 |
| cn-block | TimeoutError | - | 4 |
| speed | ProxyError | - | 3 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 2 |
| geo | TimeoutError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 60 | 70 | - |
| global | False | 63 | 73 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
