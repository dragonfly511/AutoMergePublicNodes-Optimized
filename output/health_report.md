# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-19 11:45:07 |
| 运行耗时 | 288.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 95360 |
| 去重后节点 | 26177 |
| TCP 可达 | 3000 |
| 真实可用 | 88 |
| Verified 输出 | 88 |
| Global 输出 | 97 |
| All 输出 | 26177 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.0 |
| geo | 1.5 |
| tcp | 81.4 |
| probe | 86.3 |
| real_test | 76.7 |
| china_check | 31.1 |
| write_verified | 0.0 |
| generate | 7.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55511 |
| vmess | 16616 |
| shadowsocks | 11638 |
| trojan | 8987 |
| hysteria2 | 1554 |
| http | 766 |
| shadowsocksr | 172 |
| socks | 64 |
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
| 80.1 | shadowsocks | 242.7 | 612.8 | 22.16 | 0.0 | 10.0 | 13.84 | 18.1 | Au1rxx-base64 | 156.146.38.167 |
| 80.02 | shadowsocks | 246.2 | 650.2 | 22.08 | 0.0 | 10.0 | 13.84 | 18.1 | Au1rxx-base64 | 156.146.38.168 |
| 76.7 | shadowsocks | 353.4 | 716.9 | 19.6 | 0.0 | 10.0 | 13.84 | 18.1 | Au1rxx-base64 | 37.19.198.160 |
| 76.05 | vless | 293.7 | 743.0 | 20.98 | 0.0 | 8.43 | 9.54 | 18.1 | Au1rxx-base64 | 162.35.126.130 |
| 76.0 | shadowsocks | 246.7 | 636.8 | 22.07 | 0.0 | 5.99 | 13.84 | 18.1 | Au1rxx-base64 | 156.146.38.169 |
| 74.44 | shadowsocks | 303.1 | 744.9 | 20.76 | 0.0 | 5.74 | 13.84 | 18.1 | Au1rxx-base64 | 37.19.198.236 |
| 73.94 | shadowsocks | 352.5 | 694.7 | 19.62 | 0.0 | 10.0 | 13.84 | 18.1 | Au1rxx-base64 | 37.19.198.243 |
| 73.77 | vless | 357.7 | 800.3 | 19.5 | 0.0 | 10.0 | 9.54 | 18.1 | Au1rxx-base64 | 66.70.179.198 |
| 73.72 | shadowsocks | 319.7 | 644.4 | 20.38 | 0.0 | 9.7 | 13.84 | 18.1 | Au1rxx-base64 | 149.22.95.183 |
| 73.62 | vless | 315.2 | 593.6 | 20.48 | 0.0 | 10.0 | 9.54 | 18.1 | Au1rxx-base64 | 69.48.201.136 |
| 73.59 | vless | 335.2 | 704.8 | 20.02 | 0.0 | 9.84 | 9.54 | 18.1 | Au1rxx-base64 | 45.63.53.81 |
| 73.05 | shadowsocks | 303.9 | 748.7 | 20.74 | 0.0 | 5.87 | 13.84 | 18.1 | Au1rxx-base64 | 37.19.198.244 |
| 71.41 | vless | 420.9 | 1040.6 | 18.03 | 0.0 | 9.7 | 9.54 | 18.1 | Au1rxx-base64 | 147.182.212.232 |
| 71.31 | http | 268.4 | 668.0 | 21.56 | 0.0 | 0.0 | 13.65 | 18.6 | ermaozi | 172.64.68.89 |
| 69.87 | shadowsocks | 475.8 | 1114.4 | 16.76 | 0.0 | 10.0 | 13.84 | 18.1 | Au1rxx-base64 | 51.222.136.236 |
| 69.47 | vless | 459.7 | 1015.0 | 17.14 | 0.0 | 8.74 | 9.54 | 18.1 | Au1rxx-base64 | 209.200.246.148 |
| 69.3 | hysteria2 | 469.2 | 1073.6 | 16.92 | 0.0 | 10.0 | 11.79 | 18.1 | Au1rxx-base64 | 129.213.91.185 |
| 69.08 | hysteria2 | 342.7 | 711.0 | 19.84 | 0.0 | 6.12 | 11.79 | 18.1 | Au1rxx-base64 | 66.94.121.46 |
| 68.83 | shadowsocks | 409.1 | 539.8 | 18.31 | 0.0 | 10.0 | 13.84 | 18.1 | Au1rxx-base64 | 103.11.76.248 |
| 68.78 | vless | 319.2 | 513.9 | 20.39 | 0.0 | 10.0 | 9.54 | 18.1 | Au1rxx-base64 | 131.143.180.87 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.998 | 0.98 | 100 | 696 | prefer |
| Au1rxx-base64 | 0.819 | 0.753 | 299 | 1716 | prefer |
| mheidari-all | 0.64 | 0.565 | 23 | 23446 | observe |
| Surfboard-tg-mixed | 0.533 | 0.451 | 51 | 6867 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4940 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3294 | observe |
| Epodonios-all | 0.255 | None | 0 | 7331 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9767 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5407 | observe |
| barry-far-vless | 0.255 | None | 0 | 5622 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4314 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1717 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 64 |
| geo | ClientOSError | - | 15 |
| speed | ClientOSError | - | 10 |
| cn-block | TimeoutError | - | 6 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyError | - | 5 |
| 204 | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | TimeoutError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 70 | 88 | - |
| global | False | 73 | 97 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
