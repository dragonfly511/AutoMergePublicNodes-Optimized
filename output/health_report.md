# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-02 05:06:32 |
| 运行耗时 | 379.4s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 127609 |
| 去重后节点 | 58153 |
| TCP 可达 | 3000 |
| 真实可用 | 64 |
| Verified 输出 | 64 |
| Global 输出 | 65 |
| All 输出 | 58153 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.1 |
| geo | 1.7 |
| tcp | 199.2 |
| probe | 89.8 |
| real_test | 26.7 |
| china_check | 22.2 |
| write_verified | 0.0 |
| generate | 30.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77157 |
| vmess | 18172 |
| trojan | 16591 |
| shadowsocks | 12643 |
| hysteria2 | 2323 |
| shadowsocksr | 245 |
| http | 209 |
| socks | 130 |
| tuic | 66 |
| hysteria | 39 |
| anytls | 34 |

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
| 85.32 | trojan | 183.5 | 482.2 | 23.53 | 0.0 | 10.0 | 14.45 | 19.84 | dragon | 167.88.61.20 |
| 83.82 | trojan | 246.6 | 570.6 | 22.07 | 0.0 | 10.0 | 14.45 | 19.84 | dragon | 66.163.112.31 |
| 83.51 | trojan | 175.5 | 473.8 | 23.72 | 0.0 | 10.0 | 14.45 | 19.84 | dragon | 167.88.61.175 |
| 83.23 | trojan | 241.0 | 549.6 | 22.2 | 0.0 | 9.72 | 14.45 | 19.84 | dragon | 66.163.112.142 |
| 83.16 | trojan | 177.8 | 473.2 | 23.66 | 0.0 | 9.71 | 14.45 | 19.84 | dragon | 167.88.61.193 |
| 82.36 | trojan | 267.6 | 664.9 | 21.58 | 0.0 | 8.99 | 14.45 | 19.84 | dragon | 216.106.186.33 |
| 82.18 | trojan | 238.1 | 575.6 | 22.27 | 0.0 | 8.12 | 14.45 | 19.84 | dragon | 216.106.186.32 |
| 82.11 | trojan | 245.7 | 583.0 | 22.09 | 0.0 | 8.23 | 14.45 | 19.84 | dragon | blog.findlocaljobnetworkandbuildcommunityconnections.com |
| 81.82 | trojan | 271.6 | 624.4 | 21.49 | 0.0 | 10.0 | 14.45 | 19.84 | dragon | 66.163.114.114 |
| 80.19 | trojan | 270.4 | 627.8 | 21.52 | 0.0 | 8.17 | 14.45 | 19.84 | dragon | 66.163.114.166 |
| 80.08 | trojan | 244.6 | 550.1 | 22.12 | 0.0 | 8.26 | 14.45 | 19.84 | dragon | 66.163.112.13 |
| 79.9 | trojan | 262.9 | 584.6 | 21.69 | 0.0 | 8.42 | 14.45 | 19.84 | dragon | resources.findlocaljobnetworkandbuildcommunityconnections.com |
| 79.23 | trojan | 248.7 | 553.2 | 22.02 | 0.0 | 8.26 | 14.45 | 19.84 | dragon | 66.163.112.76 |
| 78.78 | trojan | 245.7 | 600.7 | 22.09 | 0.0 | 9.9 | 14.45 | 19.84 | dragon | 216.106.186.82 |
| 78.27 | trojan | 179.4 | 485.4 | 23.62 | 0.0 | 5.86 | 14.45 | 19.84 | dragon | 167.88.61.198 |
| 78.25 | trojan | 200.0 | 498.1 | 23.15 | 0.0 | 8.31 | 14.45 | 19.84 | dragon | vpn.liumr.top |
| 78.08 | trojan | 225.1 | 598.0 | 22.57 | 0.0 | 8.72 | 14.45 | 19.84 | dragon | 186.241.105.213 |
| 77.71 | trojan | 284.7 | 671.9 | 21.19 | 0.0 | 8.26 | 14.45 | 19.84 | dragon | 66.163.112.121 |
| 77.48 | trojan | 264.4 | 611.1 | 21.66 | 0.0 | 8.18 | 14.45 | 19.84 | dragon | 66.163.114.132 |
| 77.28 | trojan | 245.1 | 594.0 | 22.1 | 0.0 | 8.39 | 14.45 | 19.84 | dragon | www.findlocaljobnetworkandbuildcommunityconnections.com |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.969 | 0.896 | 115 | 44543 | prefer |
| zhangkai | 0.79 | 1.0 | 15 | 43 | prefer |
| ermaozi-get_subscribe | 0.621 | 0.909 | 11 | 547 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4976 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3716 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10662 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8273 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5823 | observe |
| barry-far-vless | 0.255 | None | 0 | 6036 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4800 | observe |
| mheidari-all | 0.255 | None | 0 | 15216 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 6 |
| geo | ClientOSError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 48 | 64 | - |
| global | False | 51 | 65 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
