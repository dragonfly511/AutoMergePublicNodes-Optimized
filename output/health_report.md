# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-15 22:44:42 |
| 运行耗时 | 441.2s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 127859 |
| 去重后节点 | 58100 |
| TCP 可达 | 3000 |
| 真实可用 | 85 |
| Verified 输出 | 85 |
| Global 输出 | 91 |
| All 输出 | 58100 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 33.9 |
| geo | 1.5 |
| tcp | 199.7 |
| probe | 95.4 |
| real_test | 60.8 |
| china_check | 31.9 |
| write_verified | 0.1 |
| generate | 17.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77834 |
| vmess | 18836 |
| shadowsocks | 14128 |
| trojan | 14050 |
| hysteria2 | 2230 |
| shadowsocksr | 377 |
| http | 116 |
| socks | 110 |
| hysteria | 81 |
| tuic | 61 |
| anytls | 36 |

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
| 76.14 | shadowsocks | 234.2 | 605.5 | 22.36 | 0.0 | 6.07 | 13.41 | 18.3 | dragon | 156.146.38.170 |
| 73.06 | hysteria2 | 280.7 | 676.6 | 21.28 | 0.0 | 2.21 | 12.27 | 18.3 | dragon | 206.189.229.48 |
| 72.88 | shadowsocks | 241.5 | 628.6 | 22.19 | 0.0 | 2.98 | 13.41 | 18.3 | dragon | 156.146.38.169 |
| 71.54 | shadowsocks | 228.3 | 538.8 | 22.49 | 0.0 | 1.84 | 13.41 | 18.3 | dragon | 38.128.66.32 |
| 71.48 | hysteria2 | 265.2 | 603.7 | 21.64 | 0.0 | 2.42 | 12.27 | 18.3 | dragon | 66.94.121.46 |
| 71.37 | shadowsocks | 329.9 | 798.0 | 20.14 | 0.0 | 6.47 | 13.41 | 18.3 | dragon | 15.204.246.132 |
| 70.93 | shadowsocks | 283.7 | 756.7 | 21.21 | 0.0 | 3.01 | 13.41 | 18.3 | dragon | 156.146.38.168 |
| 70.82 | http | 296.3 | 728.2 | 20.92 | 0.0 | 0.0 | 13.7 | 18.7 | ermaozi | 172.64.69.89 |
| 70.34 | shadowsocks | 300.5 | 682.3 | 20.82 | 0.0 | 4.24 | 13.41 | 18.3 | dragon | 185.215.132.18 |
| 69.97 | trojan | 322.0 | 712.9 | 20.32 | 0.0 | 6.96 | 9.18 | 18.3 | dragon | 66.163.122.26 |
| 69.94 | shadowsocks | 308.6 | 708.0 | 20.63 | 0.0 | 2.1 | 13.41 | 18.3 | dragon | 45.86.51.18 |
| 69.85 | shadowsocks | 316.6 | 721.5 | 20.45 | 0.0 | 4.38 | 13.41 | 18.3 | dragon | 15.204.247.124 |
| 68.8 | trojan | 253.5 | 580.3 | 21.91 | 0.0 | 2.91 | 9.18 | 18.3 | dragon | 66.163.114.106 |
| 68.42 | shadowsocks | 245.4 | 530.2 | 22.1 | 0.0 | 1.65 | 13.41 | 18.3 | dragon | 137.184.89.151 |
| 68.34 | shadowsocks | 317.4 | 731.8 | 20.43 | 0.0 | 1.91 | 13.41 | 18.3 | dragon | 185.230.230.18 |
| 68.31 | shadowsocks | 326.5 | 730.2 | 20.22 | 0.0 | 3.74 | 13.41 | 18.3 | dragon | 193.151.160.18 |
| 67.99 | trojan | 243.5 | 561.4 | 22.14 | 0.0 | 2.87 | 9.18 | 18.3 | dragon | 66.163.114.166 |
| 67.68 | trojan | 289.1 | 626.6 | 21.09 | 0.0 | 1.61 | 9.18 | 18.3 | dragon | 170.101.101.112 |
| 67.61 | hysteria2 | 300.0 | 716.5 | 20.83 | 0.0 | 4.51 | 12.27 | 18.3 | dragon | 192.255.152.147 |
| 67.51 | shadowsocks | 316.3 | 704.6 | 20.46 | 0.0 | 1.78 | 13.41 | 18.3 | dragon | 193.151.163.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.98 | 1.0 | 22 | 544 | prefer |
| dragon | 0.793 | 0.715 | 319 | 43748 | prefer |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 8984 | observe |
| mheidari-all | 0.335 | 1.0 | 1 | 14826 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4916 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3024 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11600 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6249 | observe |
| barry-far-vless | 0.255 | None | 0 | 6342 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4550 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 71 |
| 204 | ProxyError | - | 9 |
| cn-block | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42601: bind: address already in use | - | 1 |
| speed | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 66 | 85 | - |
| global | False | 67 | 91 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
