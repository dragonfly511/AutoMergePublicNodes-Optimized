# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-20 21:08:23 |
| 运行耗时 | 306.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 94580 |
| 去重后节点 | 26432 |
| TCP 可达 | 3000 |
| 真实可用 | 82 |
| Verified 输出 | 82 |
| Global 输出 | 83 |
| All 输出 | 26432 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.5 |
| tcp | 82.6 |
| probe | 104.8 |
| real_test | 54.7 |
| china_check | 41.8 |
| write_verified | 0.0 |
| generate | 13.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56383 |
| vmess | 16877 |
| shadowsocks | 11685 |
| trojan | 8107 |
| hysteria2 | 1139 |
| shadowsocksr | 163 |
| http | 97 |
| socks | 70 |
| anytls | 36 |
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
| 75.15 | shadowsocks | 259.5 | 713.4 | 21.77 | 0.0 | 9.07 | 12.89 | 15.42 | Au1rxx-base64 | 37.19.198.243 |
| 72.89 | vless | 305.6 | 764.4 | 20.7 | 0.0 | 7.09 | 9.68 | 15.42 | Au1rxx-base64 | 66.70.179.198 |
| 71.96 | shadowsocks | 257.2 | 711.8 | 21.82 | 0.0 | 9.33 | 12.89 | 15.42 | Au1rxx-base64 | 185.230.230.18 |
| 71.65 | shadowsocks | 304.6 | 711.9 | 20.73 | 0.0 | 8.79 | 12.89 | 15.42 | Au1rxx-base64 | 156.146.38.167 |
| 71.42 | vless | 252.4 | 704.3 | 21.93 | 0.0 | 4.39 | 9.68 | 15.42 | Au1rxx-base64 | 162.35.126.130 |
| 71.37 | shadowsocks | 407.0 | 1087.3 | 18.36 | 0.0 | 9.2 | 12.89 | 15.42 | Au1rxx-base64 | 51.222.136.236 |
| 70.92 | shadowsocks | 304.3 | 708.1 | 20.73 | 0.0 | 8.97 | 12.89 | 15.42 | Au1rxx-base64 | 156.146.38.168 |
| 69.94 | shadowsocks | 277.6 | 759.4 | 21.35 | 0.0 | 9.28 | 12.89 | 15.42 | Au1rxx-base64 | 37.19.198.160 |
| 69.37 | vless | 390.8 | 993.3 | 18.73 | 0.0 | 6.59 | 9.68 | 15.42 | Au1rxx-base64 | 209.200.246.148 |
| 69.03 | shadowsocks | 333.7 | 955.2 | 20.05 | 0.0 | 5.17 | 12.89 | 15.42 | Au1rxx-base64 | 15.204.246.132 |
| 66.77 | shadowsocks | 380.3 | 959.3 | 18.97 | 0.0 | 6.99 | 12.89 | 15.42 | Au1rxx-base64 | 193.151.160.9 |
| 66.16 | hysteria2 | 413.8 | 818.0 | 18.2 | 0.0 | 8.23 | 10.71 | 15.42 | Au1rxx-base64 | 66.94.121.46 |
| 66.11 | vless | 343.2 | 818.7 | 19.83 | 0.0 | 7.63 | 9.68 | 15.42 | Au1rxx-base64 | 69.48.201.136 |
| 66.08 | trojan | 405.7 | 1112.4 | 18.39 | 0.0 | 8.6 | 11.67 | 15.42 | Au1rxx-base64 | 69.164.240.85 |
| 65.88 | vless | 372.7 | 690.8 | 19.15 | 0.0 | 8.18 | 9.68 | 15.42 | Au1rxx-base64 | 154.29.145.196 |
| 65.59 | shadowsocks | 267.8 | 721.6 | 21.58 | 0.0 | 9.28 | 12.89 | 15.42 | Au1rxx-base64 | 37.19.198.236 |
| 65.44 | vless | 475.3 | 1257.7 | 16.77 | 0.0 | 6.8 | 9.68 | 15.42 | Au1rxx-base64 | 169.40.42.229 |
| 65.37 | shadowsocks | 335.1 | 842.8 | 20.02 | 0.0 | 0.0 | 12.89 | 16.96 | mheidari-all | 15.204.247.206 |
| 64.78 | shadowsocks | 472.2 | 1323.2 | 16.85 | 0.0 | 7.12 | 12.89 | 15.42 | Au1rxx-base64 | 185.215.132.9 |
| 64.71 | shadowsocks | 289.7 | 669.0 | 21.07 | 0.0 | 0.0 | 12.89 | 16.96 | mheidari-all | 156.146.38.170 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.963 | 1.0 | 24 | 31 | prefer |
| mheidari-all | 0.927 | 0.854 | 96 | 23621 | prefer |
| Surfboard-tg-mixed | 0.856 | 0.786 | 56 | 6945 | prefer |
| Au1rxx-base64 | 0.809 | 0.754 | 187 | 1438 | prefer |
| tg-oneclickvpnkeys | 0.403 | 1.0 | 4 | 74 | observe |
| ninja-vless | 0.327 | 1.0 | 1 | 1791 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| ermaozi-get_subscribe | 0.272 | 1.0 | 1 | 429 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4967 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3519 | observe |
| Epodonios-all | 0.255 | None | 0 | 7425 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9870 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5487 | observe |
| barry-far-vless | 0.255 | None | 0 | 5701 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 49 |
| speed | ClientOSError | - | 9 |
| geo | ClientOSError | - | 3 |
| 204 | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | TimeoutError | - | 1 |
| cn-block | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 78 | 82 | - |
| global | False | 81 | 83 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
