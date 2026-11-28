# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-28 07:00:12 |
| 运行耗时 | 424.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 122089 |
| 去重后节点 | 57725 |
| TCP 可达 | 3000 |
| 真实可用 | 68 |
| Verified 输出 | 68 |
| Global 输出 | 70 |
| All 输出 | 57725 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.0 |
| geo | 1.6 |
| tcp | 207.1 |
| probe | 98.5 |
| real_test | 56.2 |
| china_check | 32.9 |
| write_verified | 0.0 |
| generate | 22.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 72994 |
| vmess | 19956 |
| shadowsocks | 13717 |
| trojan | 12303 |
| hysteria2 | 2411 |
| shadowsocksr | 254 |
| socks | 178 |
| http | 148 |
| anytls | 62 |
| hysteria | 44 |
| tuic | 22 |

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
| 82.47 | hysteria2 | 196.7 | 507.2 | 23.22 | 0.0 | 10.0 | 11.25 | 19.1 | dragon | 172.87.24.53 |
| 79.87 | shadowsocks | 196.2 | 521.8 | 23.24 | 0.0 | 8.18 | 13.85 | 19.1 | dragon | 95.215.201.18 |
| 79.05 | shadowsocks | 254.1 | 618.9 | 21.9 | 0.0 | 8.22 | 13.85 | 19.1 | dragon | 156.146.38.168 |
| 78.98 | shadowsocks | 256.3 | 628.2 | 21.84 | 0.0 | 8.19 | 13.85 | 19.1 | dragon | 156.146.38.169 |
| 78.35 | shadowsocks | 258.0 | 689.2 | 21.81 | 0.0 | 8.09 | 13.85 | 19.1 | dragon | 23.150.152.38 |
| 77.98 | shadowsocks | 252.0 | 617.3 | 21.94 | 0.0 | 7.94 | 13.85 | 19.1 | dragon | 156.146.38.170 |
| 77.91 | shadowsocks | 212.6 | 530.9 | 22.86 | 0.0 | 8.1 | 13.85 | 19.1 | dragon | 173.244.56.9 |
| 75.76 | hysteria2 | 234.8 | 238.2 | 22.34 | 6.07 | 8.99 | 11.25 | 19.1 | dragon | 8.209.247.109 |
| 75.7 | shadowsocks | 178.6 | 476.2 | 23.64 | 0.0 | 8.11 | 13.85 | 19.1 | dragon | 216.105.168.18 |
| 74.84 | http | 217.3 | 528.6 | 22.75 | 0.0 | 0.0 | 14.67 | 19.92 | ermaozi | 172.64.69.89 |
| 73.95 | shadowsocks | 276.3 | 613.0 | 21.38 | 0.0 | 8.19 | 13.85 | 19.1 | dragon | 108.181.88.2 |
| 72.95 | shadowsocks | 193.0 | 467.0 | 23.31 | 0.0 | 0.69 | 13.85 | 19.1 | dragon | 49.51.39.148 |
| 72.82 | shadowsocks | 332.1 | 701.6 | 20.09 | 0.0 | 8.43 | 13.85 | 19.1 | dragon | 37.19.198.236 |
| 72.75 | shadowsocks | 343.5 | 733.4 | 19.83 | 0.0 | 8.55 | 13.85 | 19.1 | dragon | 172.111.38.72 |
| 72.69 | shadowsocks | 330.5 | 669.7 | 20.13 | 0.0 | 7.98 | 13.85 | 19.1 | dragon | 185.215.132.9 |
| 72.69 | shadowsocks | 341.8 | 732.3 | 19.86 | 0.0 | 8.55 | 13.85 | 19.1 | dragon | 185.230.230.18 |
| 72.18 | shadowsocks | 345.8 | 743.4 | 19.77 | 0.0 | 8.43 | 13.85 | 19.1 | dragon | 37.19.198.244 |
| 72.12 | shadowsocks | 214.6 | 533.7 | 22.81 | 0.0 | 0.36 | 13.85 | 19.1 | dragon | 173.244.56.6 |
| 71.94 | shadowsocks | 356.5 | 728.3 | 19.53 | 0.0 | 7.92 | 13.85 | 19.1 | dragon | 193.151.160.9 |
| 71.84 | shadowsocks | 394.7 | 951.9 | 18.64 | 0.0 | 8.01 | 13.85 | 19.1 | dragon | 149.40.57.133 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.973 | 1.0 | 21 | 405 | prefer |
| dragon | 0.891 | 0.813 | 305 | 44346 | prefer |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8437 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4526 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4895 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11552 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5299 | observe |
| barry-far-vless | 0.255 | None | 0 | 5482 | observe |
| mheidari-all | 0.255 | None | 0 | 14211 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 48 |
| speed | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| geo | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 61 | 68 | - |
| global | False | 61 | 70 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
