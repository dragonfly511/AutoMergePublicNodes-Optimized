# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-06 14:01:05 |
| 运行耗时 | 345.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 128555 |
| 去重后节点 | 59352 |
| TCP 可达 | 3000 |
| 真实可用 | 50 |
| Verified 输出 | 50 |
| Global 输出 | 51 |
| All 输出 | 59352 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.6 |
| tcp | 200.3 |
| probe | 70.8 |
| real_test | 26.9 |
| china_check | 22.1 |
| write_verified | 0.0 |
| generate | 18.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 78714 |
| vmess | 18637 |
| trojan | 14706 |
| shadowsocks | 13504 |
| hysteria2 | 2326 |
| shadowsocksr | 209 |
| http | 205 |
| socks | 140 |
| hysteria | 44 |
| anytls | 39 |
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
| 81.45 | trojan | 265.2 | 636.4 | 21.64 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 216.152.155.23 |
| 80.96 | trojan | 259.7 | 579.5 | 21.77 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 66.163.114.45 |
| 80.74 | trojan | 276.4 | 660.5 | 21.38 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 216.152.155.54 |
| 80.14 | trojan | 279.4 | 658.4 | 21.31 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 216.152.155.176 |
| 79.78 | trojan | 272.7 | 655.7 | 21.47 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 216.152.155.158 |
| 78.96 | trojan | 359.6 | 850.7 | 19.45 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 170.101.101.67 |
| 77.81 | trojan | 385.6 | 650.1 | 18.85 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 66.163.114.106 |
| 76.5 | trojan | 335.3 | 762.5 | 20.02 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 216.152.156.212 |
| 76.47 | trojan | 303.5 | 599.4 | 20.75 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 66.163.112.31 |
| 76.44 | trojan | 297.2 | 594.8 | 20.9 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 66.163.112.242 |
| 75.41 | trojan | 355.2 | 768.6 | 19.56 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 169.197.140.214 |
| 75.13 | trojan | 303.7 | 735.2 | 20.75 | 0.0 | 5.72 | 13.43 | 18.88 | dragon | 66.163.114.166 |
| 74.42 | trojan | 339.4 | 523.8 | 19.92 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 216.106.186.82 |
| 74.37 | trojan | 373.5 | 795.5 | 19.13 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 216.238.80.100 |
| 74.3 | trojan | 395.6 | 882.3 | 18.62 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 66.163.112.142 |
| 73.13 | trojan | 323.4 | 626.3 | 20.29 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 66.163.112.121 |
| 73.02 | shadowsocks | 317.6 | 709.5 | 20.43 | 0.0 | 10.0 | 11.88 | 18.88 | dragon | 172.111.38.72 |
| 72.85 | hysteria2 | 219.4 | 577.8 | 22.7 | 0.0 | 0.0 | 12.27 | 18.88 | dragon | 88.216.195.188 |
| 72.84 | hysteria2 | 220.0 | 582.5 | 22.69 | 0.0 | 0.0 | 12.27 | 18.88 | dragon | promo3.goonars.com |
| 72.6 | trojan | 356.9 | 781.1 | 19.52 | 0.0 | 10.0 | 13.43 | 18.88 | dragon | 169.197.140.218 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.993 | 1.0 | 34 | 513 | prefer |
| dragon | 0.793 | 0.717 | 92 | 45886 | prefer |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4934 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2768 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10967 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6268 | observe |
| barry-far-vless | 0.255 | None | 0 | 6479 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4703 | observe |
| mheidari-all | 0.255 | None | 0 | 14174 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 13 |
| test_one_timeout | 15.0s | - | 8 |
| geo | ProxyError | - | 2 |
| cn-block | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 119 | 50 | - |
| global | False | 119 | 51 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
