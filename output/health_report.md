# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-01 05:05:44 |
| 运行耗时 | 396.6s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 124658 |
| 去重后节点 | 57761 |
| TCP 可达 | 3000 |
| 真实可用 | 66 |
| Verified 输出 | 66 |
| Global 输出 | 66 |
| All 输出 | 57761 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.7 |
| geo | 1.5 |
| tcp | 199.1 |
| probe | 92.4 |
| real_test | 53.5 |
| china_check | 25.8 |
| write_verified | 0.0 |
| generate | 18.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 74843 |
| vmess | 18036 |
| trojan | 16683 |
| shadowsocks | 12000 |
| hysteria2 | 2170 |
| shadowsocksr | 289 |
| tuic | 264 |
| http | 229 |
| socks | 77 |
| hysteria | 42 |
| anytls | 25 |

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
| 77.59 | trojan | 260.0 | 601.0 | 21.76 | 0.0 | 10.0 | 12.44 | 18.2 | dragon | 66.163.114.132 |
| 77.54 | trojan | 257.3 | 597.7 | 21.82 | 0.0 | 10.0 | 12.44 | 18.2 | dragon | 66.163.114.114 |
| 76.78 | trojan | 292.6 | 678.4 | 21.01 | 0.0 | 10.0 | 12.44 | 18.2 | dragon | 216.152.156.42 |
| 76.64 | trojan | 317.2 | 665.3 | 20.44 | 0.0 | 10.0 | 12.44 | 18.2 | dragon | 216.152.156.212 |
| 75.04 | trojan | 297.5 | 665.4 | 20.89 | 0.0 | 10.0 | 12.44 | 18.2 | dragon | 216.152.155.23 |
| 74.41 | trojan | 295.5 | 666.6 | 20.94 | 0.0 | 10.0 | 12.44 | 18.2 | dragon | 216.152.155.176 |
| 73.86 | trojan | 409.1 | 919.6 | 18.31 | 0.0 | 10.0 | 12.44 | 18.2 | dragon | 169.197.140.169 |
| 73.31 | trojan | 297.7 | 674.2 | 20.89 | 0.0 | 10.0 | 12.44 | 18.2 | dragon | 216.152.155.54 |
| 72.56 | hysteria2 | 285.7 | 707.6 | 21.16 | 0.0 | 5.7 | 12.0 | 18.2 | dragon | 129.213.91.185 |
| 72.47 | trojan | 546.2 | 1453.4 | 15.13 | 0.0 | 10.0 | 12.44 | 18.2 | dragon | 216.152.156.65 |
| 72.41 | shadowsocks | 280.9 | 677.6 | 21.27 | 0.0 | 4.8 | 12.64 | 18.2 | dragon | 185.215.132.9 |
| 72.1 | shadowsocks | 280.7 | 682.2 | 21.28 | 0.0 | 4.48 | 12.64 | 18.2 | dragon | 185.215.132.18 |
| 71.33 | trojan | 320.4 | 738.5 | 20.36 | 0.0 | 10.0 | 12.44 | 18.2 | dragon | 169.197.140.214 |
| 70.85 | shadowsocks | 264.7 | 604.0 | 21.65 | 0.0 | 4.68 | 12.64 | 18.2 | dragon | 216.105.168.18 |
| 70.45 | trojan | 334.4 | 730.7 | 20.04 | 0.0 | 10.0 | 12.44 | 18.2 | dragon | 66.163.122.25 |
| 70.26 | trojan | 266.2 | 590.3 | 21.62 | 0.0 | 10.0 | 12.44 | 18.2 | dragon | 66.163.112.121 |
| 70.2 | trojan | 358.1 | 685.3 | 19.49 | 0.0 | 10.0 | 12.44 | 18.2 | dragon | 66.163.122.7 |
| 69.47 | shadowsocks | 222.4 | 607.4 | 22.63 | 0.0 | 0.0 | 12.64 | 18.2 | dragon | 156.146.38.167 |
| 69.36 | shadowsocks | 227.1 | 606.8 | 22.52 | 0.0 | 0.0 | 12.64 | 18.2 | dragon | 156.146.38.169 |
| 69.28 | trojan | 250.0 | 571.7 | 21.99 | 0.0 | 6.4 | 12.44 | 18.2 | dragon | 38.102.234.153 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.925 | 239 | 44351 | prefer |
| ermaozi-get_subscribe | 0.727 | 0.929 | 14 | 558 | prefer |
| zhangkai | 0.313 | 1.0 | 2 | 43 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4970 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2848 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10496 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5637 | observe |
| barry-far-vless | 0.255 | None | 0 | 5805 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4635 | observe |
| mheidari-all | 0.255 | None | 0 | 14646 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 11 |
| 204 | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| 204 | ProxyError | - | 1 |
| geo | ClientOSError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 55 | 66 | - |
| global | False | 58 | 66 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
