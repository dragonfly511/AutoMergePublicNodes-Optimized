# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-16 06:25:43 |
| 运行耗时 | 337.2s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99735 |
| 去重后节点 | 27925 |
| TCP 可达 | 3000 |
| 真实可用 | 104 |
| Verified 输出 | 104 |
| Global 输出 | 112 |
| All 输出 | 27925 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 10.3 |
| geo | 1.5 |
| tcp | 88.7 |
| probe | 110.0 |
| real_test | 86.2 |
| china_check | 28.5 |
| write_verified | 0.0 |
| generate | 12.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58899 |
| vmess | 16436 |
| shadowsocks | 11796 |
| trojan | 10384 |
| hysteria2 | 1205 |
| http | 740 |
| shadowsocksr | 168 |
| socks | 59 |
| anytls | 25 |
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
| 78.84 | shadowsocks | 266.1 | 616.5 | 21.62 | 0.0 | 10.0 | 14.18 | 17.04 | Au1rxx-base64 | 156.146.38.169 |
| 78.77 | shadowsocks | 268.9 | 646.3 | 21.55 | 0.0 | 10.0 | 14.18 | 17.04 | Au1rxx-base64 | 156.146.38.170 |
| 78.57 | shadowsocks | 268.7 | 627.7 | 21.56 | 0.0 | 10.0 | 14.18 | 17.04 | Au1rxx-base64 | 156.146.38.167 |
| 78.03 | hysteria2 | 209.3 | 561.5 | 22.93 | 0.0 | 10.0 | 14.06 | 17.04 | Au1rxx-base64 | 179.255.104.98 |
| 75.47 | vless | 218.5 | 580.9 | 22.72 | 0.0 | 10.0 | 7.71 | 17.04 | Au1rxx-base64 | 216.234.140.15 |
| 74.9 | shadowsocks | 214.0 | 532.3 | 22.82 | 0.0 | 4.86 | 14.18 | 17.04 | Au1rxx-base64 | 173.244.56.9 |
| 74.42 | http | 210.3 | 521.3 | 22.91 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 138.199.35.216 |
| 74.36 | http | 212.9 | 546.2 | 22.85 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 138.199.35.202 |
| 74.33 | shadowsocks | 326.8 | 616.9 | 20.21 | 0.0 | 10.0 | 14.18 | 17.04 | Au1rxx-base64 | 149.22.95.183 |
| 73.97 | http | 229.8 | 521.9 | 22.46 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 138.199.35.210 |
| 73.56 | http | 268.9 | 631.6 | 21.55 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 172.64.68.89 |
| 73.16 | http | 264.8 | 633.4 | 21.65 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 138.199.35.198 |
| 73.14 | http | 222.5 | 512.5 | 22.63 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 138.199.35.206 |
| 72.25 | http | 206.1 | 500.5 | 23.01 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 138.199.35.201 |
| 71.78 | http | 238.1 | 547.1 | 22.27 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 138.199.35.211 |
| 71.5 | shadowsocks | 367.8 | 792.9 | 19.26 | 0.0 | 10.0 | 14.18 | 17.04 | Au1rxx-base64 | 37.19.198.236 |
| 71.31 | http | 215.0 | 518.0 | 22.8 | 0.0 | 0.0 | 14.57 | 19.94 | ermaozi | 138.199.35.199 |
| 71.18 | shadowsocks | 596.9 | 1643.5 | 13.96 | 0.0 | 10.0 | 14.18 | 17.04 | Au1rxx-base64 | 156.146.38.168 |
| 71.02 | shadowsocks | 314.2 | 245.5 | 20.51 | 5.8 | 9.78 | 14.18 | 17.04 | Au1rxx-base64 | 149.22.87.240 |
| 69.95 | shadowsocks | 218.1 | 542.6 | 22.73 | 0.0 | 0.0 | 14.18 | 17.04 | Au1rxx-base64 | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | 0.989 | 89 | 693 | prefer |
| Au1rxx-base64 | 0.823 | 0.745 | 345 | 1992 | prefer |
| Surfboard-tg-mixed | 0.461 | 0.545 | 11 | 7054 | observe |
| mheidari-all | 0.325 | 0.24 | 96 | 23985 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 79 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5024 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1992 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 5147 | observe |
| Epodonios-all | 0.255 | None | 0 | 7651 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10060 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5573 | observe |
| barry-far-vless | 0.255 | None | 0 | 5882 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4265 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 114 |
| geo | ClientOSError | - | 18 |
| speed | ClientOSError | - | 13 |
| cn-block | ClientOSError | - | 7 |
| 204 | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 4 |
| 204 | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 87 | 104 | - |
| global | False | 95 | 112 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
