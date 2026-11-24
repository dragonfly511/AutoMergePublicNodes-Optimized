# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-24 09:04:47 |
| 运行耗时 | 396.1s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 124077 |
| 去重后节点 | 59936 |
| TCP 可达 | 3000 |
| 真实可用 | 112 |
| Verified 输出 | 112 |
| Global 输出 | 123 |
| All 输出 | 59936 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.5 |
| tcp | 210.3 |
| probe | 86.4 |
| real_test | 48.8 |
| china_check | 25.3 |
| write_verified | 0.0 |
| generate | 19.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 75669 |
| vmess | 19065 |
| trojan | 13170 |
| shadowsocks | 13044 |
| hysteria2 | 2277 |
| shadowsocksr | 258 |
| http | 209 |
| socks | 202 |
| hysteria | 70 |
| anytls | 61 |
| tuic | 52 |

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
| 74.79 | shadowsocks | 299.2 | 801.4 | 20.85 | 0.0 | 3.84 | 14.1 | 20.0 | dragon | 156.146.38.169 |
| 74.12 | shadowsocks | 305.0 | 695.2 | 20.72 | 0.0 | 3.8 | 14.1 | 20.0 | dragon | 45.86.51.18 |
| 73.79 | shadowsocks | 334.8 | 867.4 | 20.03 | 0.0 | 4.16 | 14.1 | 20.0 | dragon | 67.220.73.178 |
| 73.5 | shadowsocks | 288.7 | 713.5 | 21.09 | 0.0 | 3.74 | 14.1 | 20.0 | dragon | 37.19.198.244 |
| 73.39 | trojan | 315.0 | 839.5 | 20.49 | 0.0 | 4.52 | 13.75 | 20.0 | dragon | 216.152.155.158 |
| 73.25 | shadowsocks | 321.9 | 865.3 | 20.33 | 0.0 | 3.68 | 14.1 | 20.0 | dragon | 38.128.66.32 |
| 72.96 | shadowsocks | 307.6 | 737.5 | 20.66 | 0.0 | 3.7 | 14.1 | 20.0 | dragon | 172.111.38.72 |
| 72.9 | shadowsocks | 249.7 | 534.7 | 22.0 | 0.0 | 3.68 | 14.1 | 20.0 | dragon | 137.184.89.151 |
| 72.8 | shadowsocks | 386.3 | 1058.5 | 18.84 | 0.0 | 3.86 | 14.1 | 20.0 | dragon | 156.146.38.168 |
| 72.57 | http | 294.2 | 757.9 | 20.97 | 0.0 | 0.0 | 14.46 | 19.64 | ermaozi | 172.64.68.89 |
| 72.42 | hysteria2 | 263.4 | 577.6 | 21.68 | 0.0 | 0.7 | 12.27 | 20.0 | dragon | 172.87.24.53 |
| 71.77 | trojan | 308.5 | 592.0 | 20.64 | 0.0 | 4.67 | 13.75 | 20.0 | dragon | 167.88.61.52 |
| 71.72 | http | 330.8 | 833.4 | 20.12 | 0.0 | 0.0 | 14.46 | 19.64 | ermaozi | 172.64.69.89 |
| 71.52 | trojan | 385.5 | 956.4 | 18.85 | 0.0 | 3.98 | 13.75 | 20.0 | dragon | 69.164.240.85 |
| 71.04 | trojan | 307.1 | 580.7 | 20.67 | 0.0 | 6.13 | 13.75 | 20.0 | dragon | 167.88.61.175 |
| 70.41 | shadowsocks | 361.2 | 770.4 | 19.42 | 0.0 | 5.71 | 14.1 | 20.0 | dragon | 169.197.140.247 |
| 70.38 | shadowsocks | 295.9 | 721.0 | 20.93 | 0.0 | 3.7 | 14.1 | 20.0 | dragon | 37.19.198.160 |
| 70.18 | shadowsocks | 326.1 | 727.7 | 20.23 | 0.0 | 3.61 | 14.1 | 20.0 | dragon | 95.215.201.18 |
| 70.11 | shadowsocks | 354.9 | 758.4 | 19.56 | 0.0 | 3.61 | 14.1 | 20.0 | dragon | 193.151.160.9 |
| 69.91 | shadowsocks | 301.0 | 610.1 | 20.81 | 0.0 | 3.5 | 14.1 | 20.0 | dragon | 173.244.56.6 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.953 | 0.955 | 44 | 460 | prefer |
| dragon | 0.863 | 0.785 | 251 | 44710 | prefer |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8220 | observe |
| mahdibland-V2RayAggregator | 0.335 | 1.0 | 1 | 4587 | observe |
| ermaozi-get_subscribe | 0.271 | 1.0 | 1 | 388 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5064 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11659 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5327 | observe |
| barry-far-vless | 0.255 | None | 0 | 5849 | observe |
| mheidari-all | 0.255 | None | 0 | 15386 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 21 |
| 204 | ProxyError | - | 17 |
| cn-block | ClientOSError | - | 9 |
| cn-block | ProxyError | - | 2 |
| cn-block | TimeoutError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48148: bind: address already in use | - | 1 |
| speed | ClientOSError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | TimeoutError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 61 | 112 | - |
| global | False | 65 | 123 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
