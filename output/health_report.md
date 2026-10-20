# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-20 02:52:11 |
| 运行耗时 | 328.4s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 94698 |
| 去重后节点 | 26200 |
| TCP 可达 | 3000 |
| 真实可用 | 90 |
| Verified 输出 | 90 |
| Global 输出 | 97 |
| All 输出 | 26200 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.5 |
| tcp | 80.1 |
| probe | 102.2 |
| real_test | 94.9 |
| china_check | 29.4 |
| write_verified | 0.1 |
| generate | 13.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56663 |
| vmess | 17057 |
| shadowsocks | 11240 |
| trojan | 7968 |
| hysteria2 | 1202 |
| http | 276 |
| shadowsocksr | 168 |
| socks | 67 |
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
| 77.97 | shadowsocks | 247.4 | 628.7 | 22.05 | 0.0 | 9.01 | 13.91 | 17.0 | Au1rxx-base64 | 156.146.38.167 |
| 77.79 | shadowsocks | 241.5 | 619.9 | 22.19 | 0.0 | 8.69 | 13.91 | 17.0 | Au1rxx-base64 | 156.146.38.169 |
| 75.3 | shadowsocks | 243.0 | 615.7 | 22.15 | 0.0 | 6.24 | 13.91 | 17.0 | Au1rxx-base64 | 156.146.38.168 |
| 73.82 | vless | 249.1 | 541.7 | 22.01 | 0.0 | 8.84 | 9.46 | 17.0 | Au1rxx-base64 | 144.202.126.147 |
| 73.02 | hysteria2 | 231.7 | 498.9 | 22.42 | 0.0 | 8.76 | 10.71 | 17.0 | Au1rxx-base64 | 179.255.104.98 |
| 72.65 | shadowsocks | 340.8 | 776.8 | 19.89 | 0.0 | 8.84 | 13.91 | 17.0 | Au1rxx-base64 | 37.19.198.244 |
| 71.97 | shadowsocks | 287.4 | 585.3 | 21.13 | 0.0 | 8.74 | 13.91 | 17.0 | Au1rxx-base64 | 173.244.56.9 |
| 71.18 | shadowsocks | 340.1 | 782.1 | 19.91 | 0.0 | 7.96 | 13.91 | 17.0 | Au1rxx-base64 | 37.19.198.236 |
| 71.11 | vless | 266.8 | 547.9 | 21.6 | 0.0 | 8.48 | 9.46 | 17.0 | Au1rxx-base64 | 104.225.239.122 |
| 70.78 | shadowsocks | 340.8 | 771.0 | 19.89 | 0.0 | 8.38 | 13.91 | 17.0 | Au1rxx-base64 | 37.19.198.243 |
| 70.05 | vless | 237.7 | 519.2 | 22.27 | 0.0 | 8.27 | 9.46 | 17.0 | Au1rxx-base64 | 136.175.179.94 |
| 69.96 | vless | 503.6 | 656.8 | 16.12 | 0.0 | 8.84 | 9.46 | 17.0 | Au1rxx-base64 | 45.63.53.81 |
| 68.27 | hysteria2 | 341.7 | 734.6 | 19.87 | 0.0 | 8.85 | 10.71 | 17.0 | Au1rxx-base64 | 66.94.121.46 |
| 68.12 | vless | 317.6 | 625.1 | 20.43 | 0.0 | 7.17 | 9.46 | 17.0 | Au1rxx-base64 | 154.9.241.170 |
| 67.54 | vless | 290.4 | 633.2 | 21.06 | 0.0 | 8.32 | 9.46 | 17.0 | Au1rxx-base64 | 15.204.97.219 |
| 67.42 | vless | 436.2 | 950.3 | 17.68 | 0.0 | 8.44 | 9.46 | 17.0 | Au1rxx-base64 | 209.200.246.148 |
| 66.78 | shadowsocks | 309.3 | 626.8 | 20.62 | 0.0 | 8.8 | 13.91 | 17.0 | Au1rxx-base64 | 149.22.95.183 |
| 66.42 | vless | 370.9 | 851.4 | 19.19 | 0.0 | 8.73 | 9.46 | 17.0 | Au1rxx-base64 | 69.48.201.136 |
| 65.62 | vless | 319.0 | 678.3 | 20.39 | 0.0 | 7.18 | 9.46 | 17.0 | Au1rxx-base64 | 208.84.100.209 |
| 65.03 | shadowsocks | 237.5 | 603.8 | 22.28 | 0.0 | 0.0 | 13.91 | 12.84 | mheidari-all | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.956 | 1.0 | 20 | 27 | prefer |
| ermaozi-get_subscribe | 0.949 | 0.944 | 54 | 510 | prefer |
| Surfboard-tg-mixed | 0.928 | 0.857 | 77 | 6911 | prefer |
| Au1rxx-base64 | 0.818 | 0.763 | 228 | 1420 | prefer |
| mheidari-all | 0.553 | 0.473 | 220 | 23317 | observe |
| SoliSpirit-all | 0.349 | 0.667 | 3 | 10158 | observe |
| 10ium-HighSpeed | 0.345 | 1.0 | 2 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4940 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3294 | observe |
| Epodonios-all | 0.255 | None | 0 | 7516 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5515 | observe |
| barry-far-vless | 0.255 | None | 0 | 5797 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4278 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 113 |
| speed | ClientOSError | - | 33 |
| geo | ClientOSError | - | 19 |
| cn-block | ClientOSError | - | 6 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 3 |
| cn-block | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 2 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 63 | 90 | - |
| global | False | 68 | 97 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
