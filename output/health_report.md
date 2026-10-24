# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-24 15:42:38 |
| 运行耗时 | 427.1s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 138792 |
| 去重后节点 | 58761 |
| TCP 可达 | 3000 |
| 真实可用 | 48 |
| Verified 输出 | 48 |
| Global 输出 | 48 |
| All 输出 | 58761 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.9 |
| geo | 1.7 |
| tcp | 202.2 |
| probe | 126.1 |
| real_test | 36.7 |
| china_check | 22.5 |
| write_verified | 0.0 |
| generate | 29.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 85355 |
| vmess | 20813 |
| shadowsocks | 16448 |
| trojan | 13451 |
| hysteria2 | 1979 |
| shadowsocksr | 255 |
| http | 212 |
| socks | 152 |
| hysteria | 47 |
| tuic | 43 |
| anytls | 37 |

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
| 81.66 | shadowsocks | 233.8 | 601.6 | 22.37 | 0.0 | 9.81 | 13.8 | 19.68 | dragon | 156.146.38.168 |
| 76.62 | shadowsocks | 332.0 | 749.0 | 20.09 | 0.0 | 9.48 | 13.8 | 19.68 | dragon | 37.19.198.160 |
| 75.93 | shadowsocks | 283.6 | 575.9 | 21.21 | 0.0 | 9.55 | 13.8 | 19.68 | dragon | 173.244.56.6 |
| 74.66 | trojan | 342.1 | 882.4 | 19.86 | 0.0 | 10.0 | 13.12 | 19.68 | dragon | 66.23.203.21 |
| 74.51 | shadowsocks | 331.1 | 740.1 | 20.11 | 0.0 | 9.07 | 13.8 | 19.68 | dragon | 193.151.160.18 |
| 74.46 | shadowsocks | 301.8 | 578.0 | 20.79 | 0.0 | 9.48 | 13.8 | 19.68 | dragon | 173.244.56.9 |
| 74.41 | shadowsocks | 334.8 | 728.2 | 20.03 | 0.0 | 9.12 | 13.8 | 19.68 | dragon | 185.230.230.18 |
| 74.33 | shadowsocks | 327.4 | 738.2 | 20.2 | 0.0 | 8.41 | 13.8 | 19.68 | dragon | 37.19.198.244 |
| 74.33 | shadowsocks | 335.2 | 739.0 | 20.02 | 0.0 | 9.15 | 13.8 | 19.68 | dragon | 193.151.163.18 |
| 74.25 | shadowsocks | 326.2 | 739.1 | 20.23 | 0.0 | 8.39 | 13.8 | 19.68 | dragon | 37.19.198.243 |
| 74.01 | shadowsocks | 245.9 | 630.6 | 22.09 | 0.0 | 9.82 | 13.8 | 19.68 | dragon | 156.146.38.167 |
| 72.68 | shadowsocks | 328.9 | 751.0 | 20.16 | 0.0 | 8.43 | 13.8 | 19.68 | dragon | 37.19.198.236 |
| 72.4 | shadowsocks | 414.5 | 1000.1 | 18.18 | 0.0 | 9.14 | 13.8 | 19.68 | dragon | 45.86.51.18 |
| 72.28 | shadowsocks | 428.6 | 1017.4 | 17.86 | 0.0 | 9.05 | 13.8 | 19.68 | dragon | 193.151.160.9 |
| 71.69 | shadowsocks | 303.8 | 304.1 | 20.75 | 3.6 | 7.57 | 13.8 | 19.68 | dragon | 149.22.87.240 |
| 69.95 | hysteria2 | 455.8 | 782.0 | 17.23 | 0.0 | 8.07 | 13.0 | 19.68 | dragon | 130.49.161.70 |
| 69.42 | shadowsocks | 448.3 | 919.0 | 17.4 | 0.0 | 8.95 | 13.8 | 19.68 | dragon | 51.222.136.236 |
| 68.46 | hysteria2 | 419.9 | 728.2 | 18.06 | 0.0 | 5.73 | 13.0 | 19.68 | dragon | 62.210.124.146 |
| 67.88 | trojan | 585.3 | 907.8 | 14.23 | 0.0 | 9.85 | 13.12 | 19.68 | dragon | 172.64.150.28 |
| 67.57 | trojan | 591.8 | 883.5 | 14.08 | 0.0 | 9.85 | 13.12 | 19.68 | dragon | 212.183.88.136 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.947 | 0.872 | 164 | 45691 | prefer |
| ermaozi | 0.498 | 0.529 | 17 | 567 | observe |
| mheidari-all | 0.335 | 1.0 | 1 | 24286 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4911 | observe |
| Epodonios-all | 0.255 | None | 0 | 7679 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10364 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5474 | observe |
| barry-far-vless | 0.255 | None | 0 | 5695 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.238 | None | 0 | 1587 | observe |
| Au1rxx-clash | 0.238 | None | 0 | 1587 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 13 |
| geo | ProxyError | - | 5 |
| 204 | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 3 |
| 204 | ProxyError | - | 2 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |
| speed | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 57 | 48 | - |
| global | False | 58 | 48 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
