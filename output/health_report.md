# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-13 14:16:26 |
| 运行耗时 | 362.0s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 127093 |
| 去重后节点 | 58788 |
| TCP 可达 | 3000 |
| 真实可用 | 93 |
| Verified 输出 | 93 |
| Global 输出 | 95 |
| All 输出 | 58788 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.5 |
| tcp | 174.4 |
| probe | 80.6 |
| real_test | 47.6 |
| china_check | 34.1 |
| write_verified | 0.0 |
| generate | 17.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77626 |
| vmess | 18810 |
| trojan | 14142 |
| shadowsocks | 13331 |
| hysteria2 | 2224 |
| tuic | 271 |
| http | 253 |
| shadowsocksr | 234 |
| socks | 96 |
| hysteria | 71 |
| anytls | 35 |

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
| 83.42 | trojan | 219.4 | 601.5 | 22.7 | 0.0 | 9.34 | 13.88 | 20.0 | dragon | 216.106.186.155 |
| 82.28 | trojan | 268.6 | 517.3 | 21.56 | 0.0 | 9.34 | 13.88 | 20.0 | dragon | 216.106.186.33 |
| 81.41 | shadowsocks | 223.3 | 528.5 | 22.61 | 0.0 | 8.48 | 14.42 | 20.0 | dragon | 38.145.220.193 |
| 79.86 | trojan | 255.2 | 535.1 | 21.87 | 0.0 | 9.14 | 13.88 | 20.0 | dragon | 167.88.61.52 |
| 79.81 | trojan | 369.9 | 956.2 | 19.22 | 0.0 | 9.21 | 13.88 | 20.0 | dragon | 66.163.114.114 |
| 79.35 | trojan | 256.9 | 538.6 | 21.83 | 0.0 | 8.51 | 13.88 | 20.0 | dragon | 167.88.61.193 |
| 78.66 | trojan | 287.1 | 610.5 | 21.13 | 0.0 | 9.05 | 13.88 | 20.0 | dragon | 66.163.112.142 |
| 78.46 | trojan | 286.6 | 602.2 | 21.14 | 0.0 | 9.07 | 13.88 | 20.0 | dragon | 66.163.112.13 |
| 78.36 | trojan | 290.5 | 601.6 | 21.05 | 0.0 | 9.08 | 13.88 | 20.0 | dragon | 66.163.112.31 |
| 78.28 | trojan | 291.1 | 609.8 | 21.04 | 0.0 | 9.07 | 13.88 | 20.0 | dragon | 66.163.112.147 |
| 78.13 | shadowsocks | 231.7 | 554.5 | 22.41 | 0.0 | 5.8 | 14.42 | 20.0 | dragon | 23.150.152.38 |
| 77.98 | trojan | 315.7 | 716.2 | 20.47 | 0.0 | 9.12 | 13.88 | 20.0 | dragon | 167.88.61.85 |
| 77.76 | trojan | 290.6 | 596.9 | 21.05 | 0.0 | 8.54 | 13.88 | 20.0 | dragon | 66.163.112.121 |
| 77.65 | shadowsocks | 353.1 | 463.0 | 19.6 | 0.0 | 10.0 | 14.42 | 20.0 | dragon | 103.11.76.248 |
| 77.34 | trojan | 249.9 | 580.9 | 21.99 | 0.0 | 9.2 | 13.88 | 20.0 | dragon | 66.163.114.132 |
| 76.67 | trojan | 243.4 | 562.7 | 22.14 | 0.0 | 9.2 | 13.88 | 20.0 | dragon | 66.163.114.166 |
| 76.31 | trojan | 315.4 | 678.1 | 20.48 | 0.0 | 7.45 | 13.88 | 20.0 | dragon | 66.163.114.106 |
| 76.13 | hysteria2 | 428.4 | 940.4 | 17.86 | 0.0 | 10.0 | 13.85 | 20.0 | dragon | 34.24.25.1 |
| 75.82 | shadowsocks | 230.5 | 514.5 | 22.44 | 0.0 | 7.27 | 14.42 | 20.0 | dragon | 216.105.168.18 |
| 75.29 | shadowsocks | 264.1 | 574.2 | 21.66 | 0.0 | 5.69 | 14.42 | 20.0 | dragon | 95.215.201.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.962 | 0.885 | 270 | 44243 | prefer |
| ermaozi | 0.955 | 0.963 | 27 | 590 | prefer |
| Surfboard-tg-mixed | 0.438 | 1.0 | 3 | 8804 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4900 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2734 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11382 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6228 | observe |
| barry-far-vless | 0.255 | None | 0 | 6298 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4624 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 20 |
| 204 | ProxyError | - | 4 |
| cn-block | ProxyError | - | 3 |
| speed | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 60 | 93 | - |
| global | False | 60 | 95 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
