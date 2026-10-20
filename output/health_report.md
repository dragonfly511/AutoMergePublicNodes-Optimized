# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-20 10:48:24 |
| 运行耗时 | 310.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 94094 |
| 去重后节点 | 26444 |
| TCP 可达 | 3000 |
| 真实可用 | 118 |
| Verified 输出 | 118 |
| Global 输出 | 121 |
| All 输出 | 26444 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.6 |
| tcp | 80.0 |
| probe | 102.9 |
| real_test | 77.0 |
| china_check | 31.1 |
| write_verified | 0.1 |
| generate | 11.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55945 |
| vmess | 16905 |
| shadowsocks | 11192 |
| trojan | 8368 |
| hysteria2 | 1119 |
| http | 278 |
| shadowsocksr | 165 |
| socks | 65 |
| anytls | 34 |
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
| 78.83 | shadowsocks | 219.7 | 544.6 | 22.69 | 0.0 | 10.0 | 13.78 | 16.36 | Au1rxx-base64 | 173.244.56.9 |
| 73.42 | shadowsocks | 269.0 | 635.0 | 21.55 | 0.0 | 10.0 | 13.78 | 16.36 | Au1rxx-base64 | 156.146.38.167 |
| 72.85 | vless | 216.2 | 509.2 | 22.77 | 0.0 | 8.77 | 6.95 | 16.36 | Au1rxx-base64 | 47.251.108.158 |
| 70.39 | hysteria2 | 200.6 | 504.8 | 23.13 | 0.0 | 0.0 | 12.35 | 18.56 | Surfboard-tg-mixed | 179.255.104.98 |
| 70.16 | shadowsocks | 257.2 | 625.0 | 21.82 | 0.0 | 0.0 | 13.78 | 18.56 | Surfboard-tg-mixed | 156.146.38.169 |
| 70.01 | http | 287.1 | 679.8 | 21.13 | 0.0 | 0.0 | 14.4 | 18.98 | ermaozi-get_subscribe | 167.88.60.242 |
| 69.67 | trojan | 314.1 | 570.1 | 20.51 | 0.0 | 9.06 | 13.18 | 16.36 | Au1rxx-base64 | 216.106.186.32 |
| 69.6 | shadowsocks | 367.7 | 808.1 | 19.27 | 0.0 | 9.05 | 13.78 | 16.36 | Au1rxx-base64 | 37.19.198.160 |
| 68.98 | shadowsocks | 391.2 | 877.3 | 18.72 | 0.0 | 9.05 | 13.78 | 16.36 | Au1rxx-base64 | 37.19.198.243 |
| 68.46 | shadowsocks | 417.2 | 959.8 | 18.12 | 0.0 | 9.05 | 13.78 | 16.36 | Au1rxx-base64 | 37.19.198.244 |
| 67.83 | http | 403.1 | 1130.6 | 18.45 | 0.0 | 0.0 | 14.4 | 18.98 | ermaozi-get_subscribe | 138.199.35.212 |
| 65.89 | vless | 289.1 | 682.9 | 21.09 | 0.0 | 0.0 | 6.95 | 18.56 | Surfboard-tg-mixed | 147.45.60.160 |
| 65.58 | http | 354.5 | 759.2 | 19.57 | 0.0 | 0.0 | 14.4 | 18.98 | ermaozi-get_subscribe | 198.44.138.27 |
| 65.56 | http | 435.6 | 1226.7 | 17.7 | 0.0 | 0.0 | 14.4 | 19.12 | zhangkai | 138.199.35.214 |
| 65.54 | http | 421.6 | 1182.2 | 18.02 | 0.0 | 0.0 | 14.4 | 19.12 | zhangkai | 138.199.35.209 |
| 65.21 | shadowsocks | 399.6 | 978.4 | 18.53 | 0.0 | 9.07 | 13.78 | 16.36 | Au1rxx-base64 | 185.215.132.9 |
| 65.2 | vless | 317.0 | 547.3 | 20.44 | 0.0 | 8.8 | 6.95 | 16.36 | Au1rxx-base64 | 15.204.97.216 |
| 64.97 | shadowsocks | 358.3 | 779.1 | 19.48 | 0.0 | 9.07 | 13.78 | 16.36 | Au1rxx-base64 | 185.230.230.18 |
| 64.83 | shadowsocks | 318.5 | 544.4 | 20.4 | 0.0 | 0.0 | 13.78 | 18.56 | Surfboard-tg-mixed | 103.11.76.248 |
| 64.76 | shadowsocks | 382.1 | 930.6 | 18.93 | 0.0 | 8.71 | 13.78 | 16.36 | Au1rxx-base64 | 185.215.132.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.991 | 0.926 | 54 | 23400 | prefer |
| ermaozi-get_subscribe | 0.967 | 0.963 | 54 | 510 | prefer |
| zhangkai | 0.956 | 1.0 | 20 | 27 | prefer |
| Au1rxx-base64 | 0.784 | 0.739 | 222 | 1180 | prefer |
| Surfboard-tg-mixed | 0.658 | 0.58 | 81 | 6911 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4967 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3519 | observe |
| Epodonios-all | 0.255 | None | 0 | 7377 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9888 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5515 | observe |
| barry-far-vless | 0.255 | None | 0 | 5733 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4278 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.222 | None | 0 | 1180 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 56 |
| speed | ClientOSError | - | 12 |
| geo | ClientOSError | - | 9 |
| 204 | ProxyError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| 204 | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 3 |
| speed | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:32205: bind: address already in use | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42974: bind: address already in use | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |
| speed | TimeoutError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 90 | 118 | - |
| global | False | 97 | 121 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
