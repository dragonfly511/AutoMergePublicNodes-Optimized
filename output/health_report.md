# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-10 01:25:12 |
| 运行耗时 | 407.5s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 126665 |
| 去重后节点 | 58804 |
| TCP 可达 | 3000 |
| 真实可用 | 57 |
| Verified 输出 | 57 |
| Global 输出 | 58 |
| All 输出 | 58804 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.7 |
| tcp | 201.7 |
| probe | 94.0 |
| real_test | 47.6 |
| china_check | 33.0 |
| write_verified | 0.0 |
| generate | 23.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77872 |
| vmess | 18183 |
| trojan | 14746 |
| shadowsocks | 12765 |
| hysteria2 | 2256 |
| shadowsocksr | 380 |
| http | 246 |
| socks | 73 |
| hysteria | 65 |
| tuic | 51 |
| anytls | 28 |

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
| 79.8 | shadowsocks | 242.3 | 660.3 | 22.17 | 0.0 | 9.53 | 13.52 | 19.08 | dragon | 95.215.201.18 |
| 75.37 | trojan | 214.9 | 481.1 | 22.8 | 0.0 | 8.19 | 8.33 | 19.08 | dragon | 167.88.61.193 |
| 74.86 | trojan | 239.8 | 656.5 | 22.23 | 0.0 | 7.72 | 8.33 | 19.08 | dragon | 66.163.112.147 |
| 74.6 | trojan | 251.1 | 694.1 | 21.97 | 0.0 | 7.72 | 8.33 | 19.08 | dragon | 66.163.112.121 |
| 74.51 | trojan | 254.8 | 686.8 | 21.88 | 0.0 | 7.72 | 8.33 | 19.08 | dragon | 66.163.112.142 |
| 74.29 | trojan | 245.8 | 672.7 | 22.09 | 0.0 | 7.72 | 8.33 | 19.08 | dragon | 66.163.112.76 |
| 74.22 | trojan | 267.9 | 716.3 | 21.58 | 0.0 | 7.73 | 8.33 | 19.08 | dragon | 66.163.112.13 |
| 74.01 | trojan | 276.3 | 760.2 | 21.38 | 0.0 | 7.72 | 8.33 | 19.08 | dragon | 66.163.112.242 |
| 73.67 | trojan | 226.2 | 504.7 | 22.54 | 0.0 | 8.22 | 8.33 | 19.08 | dragon | 167.88.61.85 |
| 73.3 | trojan | 276.6 | 612.3 | 21.38 | 0.0 | 8.14 | 8.33 | 19.08 | dragon | 66.163.114.114 |
| 72.89 | trojan | 275.8 | 611.6 | 21.39 | 0.0 | 7.99 | 8.33 | 19.08 | dragon | 216.106.186.82 |
| 72.87 | trojan | 273.5 | 618.5 | 21.45 | 0.0 | 8.03 | 8.33 | 19.08 | dragon | 66.163.114.132 |
| 72.69 | trojan | 222.3 | 516.9 | 22.63 | 0.0 | 8.15 | 8.33 | 19.08 | dragon | 167.88.61.198 |
| 72.63 | trojan | 229.7 | 515.3 | 22.46 | 0.0 | 5.58 | 8.33 | 19.08 | dragon | 167.88.61.52 |
| 72.5 | trojan | 259.6 | 577.3 | 21.77 | 0.0 | 8.1 | 8.33 | 19.08 | dragon | 66.163.114.245 |
| 72.43 | trojan | 276.0 | 612.7 | 21.39 | 0.0 | 8.1 | 8.33 | 19.08 | dragon | 66.163.114.126 |
| 71.85 | trojan | 252.7 | 667.4 | 21.93 | 0.0 | 7.72 | 8.33 | 19.08 | dragon | 66.163.112.31 |
| 71.52 | shadowsocks | 209.8 | 518.6 | 22.92 | 0.0 | 0.0 | 13.52 | 19.08 | dragon | 173.244.56.6 |
| 71.41 | trojan | 248.9 | 665.3 | 22.02 | 0.0 | 7.72 | 8.33 | 19.08 | dragon | 66.163.112.171 |
| 71.0 | trojan | 246.8 | 534.5 | 22.07 | 0.0 | 8.2 | 8.33 | 19.08 | dragon | 216.106.186.33 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.997 | 0.92 | 337 | 44733 | prefer |
| ermaozi | 0.99 | 0.977 | 87 | 602 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 14061 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4976 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2754 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11226 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8250 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6133 | observe |
| barry-far-vless | 0.255 | None | 0 | 6103 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4583 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 20 |
| 204 | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:36442: bind: address already in use | - | 1 |
| 204 | ClientOSError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| speed | TimeoutError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| geo | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 73 | 57 | - |
| global | False | 74 | 58 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
