# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-23 06:33:55 |
| 运行耗时 | 358.3s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 127015 |
| 去重后节点 | 58977 |
| TCP 可达 | 3000 |
| 真实可用 | 69 |
| Verified 输出 | 69 |
| Global 输出 | 69 |
| All 输出 | 58977 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 1.6 |
| tcp | 195.6 |
| probe | 81.4 |
| real_test | 25.3 |
| china_check | 25.2 |
| write_verified | 0.0 |
| generate | 23.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 76225 |
| vmess | 19627 |
| shadowsocks | 14599 |
| trojan | 13257 |
| hysteria2 | 2374 |
| shadowsocksr | 279 |
| http | 260 |
| socks | 225 |
| hysteria | 71 |
| tuic | 56 |
| anytls | 42 |

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
| 80.11 | shadowsocks | 245.6 | 634.2 | 22.09 | 0.0 | 8.39 | 14.13 | 20.0 | dragon | 137.184.89.151 |
| 78.45 | trojan | 244.4 | 486.5 | 22.12 | 0.0 | 5.5 | 14.33 | 20.0 | dragon | 167.88.61.52 |
| 76.39 | trojan | 222.2 | 505.0 | 22.63 | 0.0 | 2.93 | 14.33 | 20.0 | dragon | 167.88.61.85 |
| 74.97 | shadowsocks | 269.5 | 652.3 | 21.54 | 0.0 | 8.3 | 14.13 | 20.0 | dragon | 173.244.56.9 |
| 74.83 | shadowsocks | 291.9 | 732.2 | 21.02 | 0.0 | 8.24 | 14.13 | 20.0 | dragon | 156.146.38.168 |
| 73.85 | hysteria2 | 249.8 | 592.0 | 21.99 | 0.0 | 0.0 | 12.86 | 20.0 | dragon | 66.94.121.46 |
| 73.18 | shadowsocks | 278.5 | 672.3 | 21.33 | 0.0 | 8.28 | 14.13 | 20.0 | dragon | 173.244.56.6 |
| 72.97 | http | 209.3 | 504.8 | 22.93 | 0.0 | 0.0 | 13.8 | 18.74 | ermaozi | 172.64.69.89 |
| 72.33 | shadowsocks | 243.5 | 601.5 | 22.14 | 0.0 | 8.3 | 14.13 | 20.0 | dragon | 23.150.152.38 |
| 71.77 | shadowsocks | 383.6 | 703.4 | 18.9 | 0.0 | 8.98 | 14.13 | 20.0 | dragon | 200.102.179.179 |
| 71.37 | http | 256.8 | 677.1 | 21.83 | 0.0 | 0.0 | 13.8 | 18.74 | ermaozi | 138.199.35.204 |
| 71.35 | http | 257.6 | 692.1 | 21.81 | 0.0 | 0.0 | 13.8 | 18.74 | ermaozi | 138.199.35.211 |
| 71.35 | http | 257.9 | 679.5 | 21.81 | 0.0 | 0.0 | 13.8 | 18.74 | ermaozi | 138.199.35.200 |
| 70.68 | http | 200.2 | 497.3 | 23.14 | 0.0 | 0.0 | 13.8 | 18.74 | ermaozi | 138.199.35.206 |
| 70.59 | trojan | 217.9 | 503.9 | 22.73 | 0.0 | 3.23 | 14.33 | 20.0 | dragon | 167.88.61.20 |
| 69.51 | trojan | 224.3 | 527.2 | 22.59 | 0.0 | 3.21 | 14.33 | 20.0 | dragon | 167.88.61.193 |
| 69.41 | shadowsocks | 496.1 | 1062.4 | 16.29 | 0.0 | 8.97 | 14.13 | 20.0 | dragon | 15.204.247.244 |
| 69.02 | trojan | 377.0 | 772.2 | 19.05 | 0.0 | 5.89 | 14.33 | 20.0 | dragon | 66.163.122.46 |
| 68.91 | shadowsocks | 492.9 | 1057.0 | 16.37 | 0.0 | 8.97 | 14.13 | 20.0 | dragon | 15.204.246.111 |
| 68.7 | trojan | 370.8 | 732.4 | 19.19 | 0.0 | 5.07 | 14.33 | 20.0 | dragon | 170.101.101.237 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.927 | 0.923 | 52 | 486 | prefer |
| dragon | 0.814 | 0.739 | 92 | 43774 | prefer |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 8701 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5069 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2671 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11834 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5650 | observe |
| barry-far-vless | 0.255 | None | 0 | 5831 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4512 | observe |
| mheidari-all | 0.255 | None | 0 | 15418 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 13 |
| test_one_timeout | 15.0s | - | 7 |
| 204 | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:45297: bind: address already in use | - | 1 |
| cn-block | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 100 | 69 | - |
| global | False | 100 | 69 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
