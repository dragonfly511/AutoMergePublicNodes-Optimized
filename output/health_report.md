# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-18 19:59:23 |
| 运行耗时 | 286.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 97816 |
| 去重后节点 | 27677 |
| TCP 可达 | 3000 |
| 真实可用 | 60 |
| Verified 输出 | 60 |
| Global 输出 | 63 |
| All 输出 | 27677 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.5 |
| geo | 1.4 |
| tcp | 90.7 |
| probe | 85.9 |
| real_test | 64.2 |
| china_check | 30.8 |
| write_verified | 0.0 |
| generate | 8.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57528 |
| vmess | 16788 |
| shadowsocks | 11726 |
| trojan | 9544 |
| hysteria2 | 1332 |
| http | 613 |
| shadowsocksr | 171 |
| socks | 68 |
| anytls | 22 |
| hysteria | 17 |
| tuic | 7 |

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
| 78.91 | shadowsocks | 230.9 | 618.8 | 22.43 | 0.0 | 10.0 | 13.16 | 17.32 | Au1rxx-base64 | 156.146.38.169 |
| 78.76 | shadowsocks | 227.7 | 606.4 | 22.51 | 0.0 | 9.77 | 13.16 | 17.32 | Au1rxx-base64 | 156.146.38.167 |
| 77.82 | hysteria2 | 290.9 | 727.8 | 21.04 | 0.0 | 8.77 | 12.19 | 17.32 | Au1rxx-base64 | 129.213.91.185 |
| 74.07 | shadowsocks | 325.2 | 762.3 | 20.25 | 0.0 | 10.0 | 13.16 | 17.32 | Au1rxx-base64 | 37.19.198.160 |
| 73.83 | vless | 284.5 | 593.2 | 21.19 | 0.0 | 9.32 | 9.12 | 17.32 | Au1rxx-base64 | 154.9.241.170 |
| 73.77 | shadowsocks | 328.4 | 771.8 | 20.18 | 0.0 | 10.0 | 13.16 | 17.32 | Au1rxx-base64 | 37.19.198.244 |
| 72.97 | vless | 254.3 | 559.7 | 21.89 | 0.0 | 6.91 | 9.12 | 17.32 | Au1rxx-base64 | 45.63.53.81 |
| 72.94 | shadowsocks | 349.2 | 829.6 | 19.7 | 0.0 | 10.0 | 13.16 | 17.32 | Au1rxx-base64 | 37.19.198.236 |
| 72.51 | vless | 309.6 | 754.2 | 20.61 | 0.0 | 9.37 | 9.12 | 17.32 | Au1rxx-base64 | 162.35.126.130 |
| 71.98 | hysteria2 | 314.1 | 599.3 | 20.51 | 0.0 | 4.92 | 12.19 | 17.32 | Au1rxx-base64 | 66.94.121.46 |
| 71.23 | shadowsocks | 339.4 | 672.6 | 19.92 | 0.0 | 10.0 | 13.16 | 17.32 | Au1rxx-base64 | 149.22.95.183 |
| 69.9 | http | 258.1 | 566.3 | 21.8 | 0.0 | 0.0 | 13.92 | 19.16 | ermaozi | 138.199.35.198 |
| 69.77 | http | 261.3 | 573.0 | 21.73 | 0.0 | 0.0 | 13.92 | 19.16 | ermaozi | 138.199.35.216 |
| 68.07 | shadowsocks | 356.4 | 822.3 | 19.53 | 0.0 | 9.9 | 13.16 | 17.32 | Au1rxx-base64 | 198.98.53.130 |
| 67.71 | shadowsocks | 393.1 | 584.2 | 18.68 | 0.0 | 9.83 | 13.16 | 17.32 | Au1rxx-base64 | 103.11.76.248 |
| 67.37 | shadowsocks | 309.9 | 511.3 | 20.6 | 0.0 | 5.18 | 13.16 | 17.32 | Au1rxx-base64 | 173.244.56.9 |
| 67.32 | shadowsocks | 337.0 | 375.0 | 19.98 | 0.94 | 9.58 | 13.16 | 17.32 | Au1rxx-base64 | 149.22.87.241 |
| 66.14 | vless | 351.0 | 711.6 | 19.65 | 0.0 | 9.56 | 9.12 | 17.32 | Au1rxx-base64 | 69.48.201.136 |
| 66.0 | shadowsocks | 340.9 | 383.9 | 19.89 | 0.6 | 9.64 | 13.16 | 17.32 | Au1rxx-base64 | 149.22.87.240 |
| 63.79 | vless | 412.2 | 837.1 | 18.24 | 0.0 | 5.71 | 9.12 | 17.32 | Au1rxx-base64 | 169.40.42.229 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.911 | 0.909 | 33 | 639 | prefer |
| Au1rxx-base64 | 0.825 | 0.758 | 190 | 1742 | prefer |
| Surfboard-tg-mixed | 0.766 | 0.694 | 49 | 7036 | prefer |
| mheidari-all | 0.747 | 0.671 | 70 | 23629 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4983 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 4750 | observe |
| Epodonios-all | 0.255 | None | 0 | 7503 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10062 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5553 | observe |
| barry-far-vless | 0.255 | None | 0 | 5767 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4246 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1742 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 47 |
| speed | ClientOSError | - | 13 |
| geo | ClientOSError | - | 10 |
| 204 | TimeoutError | - | 5 |
| cn-block | TimeoutError | - | 3 |
| 204 | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:49221: bind: address already in use | - | 1 |
| speed | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 80 | 60 | - |
| global | False | 91 | 63 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
