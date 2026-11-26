# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-26 21:12:48 |
| 运行耗时 | 408.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 122584 |
| 去重后节点 | 58269 |
| TCP 可达 | 3000 |
| 真实可用 | 89 |
| Verified 输出 | 89 |
| Global 输出 | 91 |
| All 输出 | 58269 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.3 |
| geo | 1.7 |
| tcp | 199.1 |
| probe | 106.5 |
| real_test | 38.0 |
| china_check | 25.1 |
| write_verified | 0.0 |
| generate | 30.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 73681 |
| vmess | 20036 |
| shadowsocks | 13477 |
| trojan | 12300 |
| hysteria2 | 2209 |
| tuic | 272 |
| shadowsocksr | 227 |
| socks | 185 |
| http | 108 |
| anytls | 56 |
| hysteria | 33 |

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
| 80.76 | shadowsocks | 240.8 | 648.9 | 22.2 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 37.19.198.160 |
| 80.75 | shadowsocks | 241.4 | 643.6 | 22.19 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 37.19.198.244 |
| 80.4 | shadowsocks | 235.1 | 642.2 | 22.34 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 185.230.230.18 |
| 80.33 | shadowsocks | 238.0 | 642.8 | 22.27 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 45.86.51.18 |
| 80.28 | shadowsocks | 240.0 | 620.7 | 22.22 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 193.151.163.18 |
| 80.11 | shadowsocks | 247.6 | 638.7 | 22.05 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 149.40.57.138 |
| 78.86 | shadowsocks | 236.7 | 638.1 | 22.3 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 37.19.198.236 |
| 78.08 | shadowsocks | 335.2 | 912.4 | 20.02 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 149.40.57.134 |
| 78.05 | shadowsocks | 336.5 | 891.1 | 19.99 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 38.91.100.39 |
| 78.0 | shadowsocks | 338.7 | 542.5 | 19.94 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 172.111.38.72 |
| 77.89 | shadowsocks | 235.2 | 636.9 | 22.33 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 37.19.198.243 |
| 77.71 | shadowsocks | 307.9 | 785.6 | 20.65 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 216.106.178.169 |
| 77.69 | shadowsocks | 315.1 | 715.3 | 20.48 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 193.151.160.9 |
| 77.52 | shadowsocks | 315.9 | 721.3 | 20.46 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 193.151.160.18 |
| 77.11 | shadowsocks | 262.1 | 659.6 | 21.71 | 0.0 | 7.61 | 14.12 | 18.44 | dragon | 200.102.179.179 |
| 76.98 | shadowsocks | 377.7 | 953.9 | 19.04 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 51.222.141.125 |
| 75.73 | shadowsocks | 285.7 | 647.4 | 21.16 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 156.146.38.169 |
| 75.29 | shadowsocks | 255.0 | 643.6 | 21.87 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 149.40.57.133 |
| 75.1 | shadowsocks | 400.0 | 960.3 | 18.52 | 0.0 | 10.0 | 14.12 | 18.44 | dragon | 162.251.62.31 |
| 73.89 | hysteria2 | 291.0 | 601.7 | 21.04 | 0.0 | 7.07 | 12.0 | 18.44 | dragon | 66.94.121.46 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.974 | 1.0 | 22 | 393 | prefer |
| dragon | 0.912 | 0.835 | 248 | 43754 | prefer |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 170 | observe |
| tg-proxy_mtm | 0.258 | 1.0 | 1 | 67 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4936 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11794 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8568 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5426 | observe |
| barry-far-vless | 0.255 | None | 0 | 5607 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4485 | observe |
| mheidari-all | 0.255 | None | 0 | 14669 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 18 |
| 204 | ClientOSError | - | 6 |
| 204 | ProxyError | - | 5 |
| 204 | TimeoutError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| speed | TimeoutError | - | 3 |
| speed | ClientOSError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 35 | 89 | - |
| global | False | 35 | 91 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
