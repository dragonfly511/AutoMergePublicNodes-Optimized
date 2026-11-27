# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-27 20:55:42 |
| 运行耗时 | 333.1s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 123425 |
| 去重后节点 | 58791 |
| TCP 可达 | 3000 |
| 真实可用 | 61 |
| Verified 输出 | 61 |
| Global 输出 | 61 |
| All 输出 | 58791 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.6 |
| geo | 1.5 |
| tcp | 207.3 |
| probe | 67.3 |
| real_test | 15.1 |
| china_check | 19.5 |
| write_verified | 0.0 |
| generate | 17.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 73589 |
| vmess | 19498 |
| shadowsocks | 13890 |
| trojan | 13116 |
| hysteria2 | 2256 |
| shadowsocksr | 290 |
| tuic | 271 |
| http | 208 |
| socks | 191 |
| anytls | 70 |
| hysteria | 46 |

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
| 78.67 | shadowsocks | 239.4 | 607.8 | 22.24 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 156.146.38.169 |
| 78.6 | shadowsocks | 242.4 | 607.9 | 22.17 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 156.146.38.170 |
| 78.58 | shadowsocks | 243.1 | 616.3 | 22.15 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 156.146.38.168 |
| 78.08 | trojan | 382.4 | 979.2 | 18.93 | 0.0 | 10.0 | 13.91 | 18.24 | dragon | 66.23.203.21 |
| 77.58 | shadowsocks | 286.2 | 695.4 | 21.15 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 37.19.198.244 |
| 77.06 | shadowsocks | 285.0 | 690.1 | 21.18 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 37.19.198.236 |
| 76.74 | shadowsocks | 301.1 | 779.6 | 20.81 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 216.106.178.169 |
| 76.63 | shadowsocks | 285.3 | 675.7 | 21.17 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 37.19.198.160 |
| 75.23 | shadowsocks | 309.0 | 696.5 | 20.63 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 172.111.38.72 |
| 73.96 | shadowsocks | 280.2 | 627.0 | 21.29 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 137.184.89.151 |
| 73.92 | shadowsocks | 303.9 | 704.2 | 20.74 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 45.86.51.18 |
| 73.32 | http | 246.2 | 613.4 | 22.08 | 0.0 | 0.0 | 14.32 | 19.42 | ermaozi | 172.64.69.89 |
| 73.1 | shadowsocks | 314.0 | 733.0 | 20.51 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 185.230.230.18 |
| 73.02 | shadowsocks | 288.2 | 605.8 | 21.11 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 95.215.201.18 |
| 72.76 | shadowsocks | 340.2 | 717.7 | 19.9 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 193.151.160.9 |
| 72.73 | shadowsocks | 304.4 | 657.2 | 20.73 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 193.151.163.18 |
| 72.62 | shadowsocks | 288.0 | 681.8 | 21.11 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 37.19.198.243 |
| 72.54 | shadowsocks | 380.5 | 921.1 | 18.97 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 149.40.57.138 |
| 72.17 | shadowsocks | 379.0 | 921.4 | 19.0 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 149.40.57.134 |
| 72.1 | shadowsocks | 345.1 | 719.9 | 19.79 | 0.0 | 10.0 | 12.19 | 18.24 | dragon | 193.151.160.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.996 | 1.0 | 43 | 466 | prefer |
| dragon | 0.955 | 0.889 | 54 | 45062 | prefer |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 8496 | observe |
| mheidari-all | 0.335 | 1.0 | 1 | 14418 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 175 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4895 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11567 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5391 | observe |
| barry-far-vless | 0.255 | None | 0 | 5607 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4459 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ClientOSError | - | 2 |
| test_one_timeout | 15.0s | - | 2 |
| 204 | TimeoutError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 80 | 61 | - |
| global | False | 83 | 61 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
