# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-11 13:53:30 |
| 运行耗时 | 413.6s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 127876 |
| 去重后节点 | 59802 |
| TCP 可达 | 3000 |
| 真实可用 | 121 |
| Verified 输出 | 121 |
| Global 输出 | 123 |
| All 输出 | 59802 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.7 |
| geo | 1.6 |
| tcp | 199.4 |
| probe | 94.6 |
| real_test | 57.1 |
| china_check | 30.3 |
| write_verified | 0.0 |
| generate | 23.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 79016 |
| vmess | 18045 |
| trojan | 14855 |
| shadowsocks | 13054 |
| hysteria2 | 2144 |
| http | 297 |
| shadowsocksr | 260 |
| socks | 97 |
| hysteria | 42 |
| anytls | 35 |
| tuic | 31 |

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
| 81.92 | trojan | 205.6 | 562.6 | 23.02 | 0.0 | 10.0 | 12.94 | 18.46 | dragon | 216.106.186.66 |
| 81.19 | trojan | 237.1 | 422.3 | 22.29 | 0.0 | 10.0 | 12.94 | 18.46 | dragon | 216.106.186.155 |
| 81.02 | trojan | 236.0 | 627.9 | 22.32 | 0.0 | 9.8 | 12.94 | 18.46 | dragon | 216.106.186.46 |
| 79.47 | shadowsocks | 232.4 | 520.6 | 22.4 | 0.0 | 10.0 | 13.64 | 18.46 | dragon | 38.145.220.193 |
| 79.28 | trojan | 302.5 | 622.0 | 20.78 | 0.0 | 10.0 | 12.94 | 18.46 | dragon | 167.88.61.175 |
| 79.1 | hysteria2 | 328.9 | 597.3 | 20.17 | 0.0 | 10.0 | 11.47 | 18.46 | dragon | 66.94.121.46 |
| 79.05 | trojan | 288.6 | 685.0 | 21.1 | 0.0 | 10.0 | 12.94 | 18.46 | dragon | 167.88.61.85 |
| 75.54 | trojan | 345.8 | 764.9 | 19.77 | 0.0 | 10.0 | 12.94 | 18.46 | dragon | 66.163.112.147 |
| 75.49 | http | 191.3 | 446.6 | 23.35 | 0.0 | 0.0 | 14.64 | 20.0 | ermaozi | 172.64.69.89 |
| 74.46 | trojan | 336.3 | 732.5 | 19.99 | 0.0 | 9.1 | 12.94 | 18.46 | dragon | 66.163.112.31 |
| 74.36 | trojan | 372.4 | 536.5 | 19.16 | 0.0 | 9.45 | 12.94 | 18.46 | dragon | 66.163.112.242 |
| 74.23 | trojan | 236.5 | 520.8 | 22.3 | 0.0 | 9.39 | 12.94 | 18.46 | dragon | 167.88.61.20 |
| 74.12 | trojan | 240.4 | 542.3 | 22.21 | 0.0 | 9.39 | 12.94 | 18.46 | dragon | 167.88.61.198 |
| 74.09 | trojan | 236.7 | 529.5 | 22.3 | 0.0 | 9.39 | 12.94 | 18.46 | dragon | 167.88.61.193 |
| 73.94 | trojan | 281.8 | 636.0 | 21.25 | 0.0 | 10.0 | 12.94 | 18.46 | dragon | 66.163.114.114 |
| 73.89 | trojan | 333.5 | 683.2 | 20.06 | 0.0 | 9.94 | 12.94 | 18.46 | dragon | 216.152.155.59 |
| 73.55 | trojan | 395.5 | 900.9 | 18.62 | 0.0 | 9.31 | 12.94 | 18.46 | dragon | 66.163.112.121 |
| 73.19 | shadowsocks | 492.2 | 644.9 | 16.38 | 0.0 | 9.73 | 13.64 | 18.46 | dragon | 169.197.142.68 |
| 73.05 | trojan | 431.5 | 1017.6 | 17.79 | 0.0 | 9.38 | 12.94 | 18.46 | dragon | 66.163.112.13 |
| 72.49 | trojan | 289.3 | 595.4 | 21.08 | 0.0 | 9.51 | 12.94 | 18.46 | dragon | 66.163.112.142 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.951 | 0.938 | 80 | 608 | prefer |
| dragon | 0.907 | 0.829 | 292 | 45201 | prefer |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4981 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2629 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11142 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8393 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6306 | observe |
| barry-far-vless | 0.255 | None | 0 | 6508 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 29 |
| 204 | ProxyError | - | 15 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42600: bind: address already in use | - | 1 |
| speed | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 108 | 121 | - |
| global | False | 108 | 123 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
