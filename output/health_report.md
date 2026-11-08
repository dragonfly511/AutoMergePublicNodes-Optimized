# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-08 21:56:57 |
| 运行耗时 | 426.9s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 126502 |
| 去重后节点 | 58460 |
| TCP 可达 | 3000 |
| 真实可用 | 92 |
| Verified 输出 | 92 |
| Global 输出 | 93 |
| All 输出 | 58460 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.5 |
| geo | 1.6 |
| tcp | 193.8 |
| probe | 114.2 |
| real_test | 46.5 |
| china_check | 37.3 |
| write_verified | 0.0 |
| generate | 25.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 76757 |
| vmess | 18654 |
| trojan | 14636 |
| shadowsocks | 13330 |
| hysteria2 | 2287 |
| shadowsocksr | 375 |
| http | 214 |
| socks | 93 |
| tuic | 62 |
| hysteria | 60 |
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
| 80.95 | trojan | 200.5 | 520.6 | 23.14 | 0.0 | 9.52 | 11.67 | 19.12 | dragon | 66.163.112.242 |
| 78.11 | trojan | 195.0 | 513.6 | 23.26 | 0.0 | 6.56 | 11.67 | 19.12 | dragon | 66.163.112.76 |
| 77.9 | trojan | 197.9 | 514.5 | 23.2 | 0.0 | 6.41 | 11.67 | 19.12 | dragon | 66.163.112.147 |
| 75.22 | shadowsocks | 189.9 | 505.6 | 23.38 | 0.0 | 3.0 | 13.82 | 19.12 | dragon | 38.145.220.193 |
| 74.13 | shadowsocks | 343.8 | 880.3 | 19.82 | 0.0 | 5.87 | 13.82 | 19.12 | dragon | 103.11.76.248 |
| 73.98 | trojan | 244.8 | 527.2 | 22.11 | 0.0 | 5.85 | 11.67 | 19.12 | dragon | 216.106.186.82 |
| 72.52 | shadowsocks | 197.4 | 478.3 | 23.21 | 0.0 | 5.87 | 13.82 | 19.12 | dragon | 137.175.73.178 |
| 71.86 | hysteria2 | 274.8 | 585.4 | 21.42 | 0.0 | 0.0 | 12.69 | 19.12 | dragon | 66.94.121.46 |
| 71.73 | shadowsocks | 215.5 | 534.2 | 22.79 | 0.0 | 0.0 | 13.82 | 19.12 | dragon | 173.244.56.6 |
| 71.59 | shadowsocks | 199.8 | 520.9 | 23.15 | 0.0 | 0.0 | 13.82 | 19.12 | dragon | 95.215.201.18 |
| 71.49 | trojan | 274.7 | 605.4 | 21.42 | 0.0 | 6.03 | 11.67 | 19.12 | dragon | 216.106.186.33 |
| 71.33 | shadowsocks | 302.3 | 756.1 | 20.78 | 0.0 | 2.61 | 13.82 | 19.12 | dragon | 156.146.38.170 |
| 71.16 | shadowsocks | 218.7 | 535.1 | 22.72 | 0.0 | 0.0 | 13.82 | 19.12 | dragon | 137.184.89.151 |
| 70.69 | shadowsocks | 259.9 | 632.8 | 21.76 | 0.0 | 1.99 | 13.82 | 19.12 | dragon | 156.146.38.168 |
| 70.53 | http | 278.4 | 658.1 | 21.33 | 0.0 | 0.0 | 13.5 | 18.46 | ermaozi | 167.88.60.242 |
| 69.84 | hysteria2 | 289.0 | 648.1 | 21.09 | 0.0 | 0.0 | 12.69 | 19.12 | dragon | promo3.goonars.com |
| 69.7 | hysteria2 | 286.6 | 642.5 | 21.14 | 0.0 | 0.0 | 12.69 | 19.12 | dragon | 88.216.195.188 |
| 69.55 | shadowsocks | 288.2 | 737.3 | 21.11 | 0.0 | 0.0 | 13.82 | 19.12 | dragon | 23.150.152.38 |
| 69.55 | hysteria2 | 288.9 | 212.7 | 21.09 | 7.02 | 2.73 | 12.69 | 19.12 | dragon | 64.90.0.30 |
| 69.51 | shadowsocks | 290.0 | 698.7 | 21.07 | 0.0 | 0.0 | 13.82 | 19.12 | dragon | 167.17.67.171 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.986 | 0.909 | 263 | 45021 | prefer |
| ermaozi | 0.954 | 0.946 | 56 | 586 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5035 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3024 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10978 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8189 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5913 | observe |
| barry-far-vless | 0.255 | None | 0 | 6025 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4597 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |
| 10ium-HighSpeed | 0.209 | None | 0 | 839 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 17 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48016: bind: address already in use | - | 1 |
| speed | TimeoutError | - | 1 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 79 | 92 | - |
| global | False | 81 | 93 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
