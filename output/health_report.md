# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-26 07:31:22 |
| 运行耗时 | 384.4s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 122533 |
| 去重后节点 | 57951 |
| TCP 可达 | 3000 |
| 真实可用 | 35 |
| Verified 输出 | 35 |
| Global 输出 | 35 |
| All 输出 | 57951 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.3 |
| geo | 1.7 |
| tcp | 197.7 |
| probe | 100.0 |
| real_test | 22.7 |
| china_check | 24.4 |
| write_verified | 0.0 |
| generate | 29.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 74074 |
| vmess | 19894 |
| shadowsocks | 13161 |
| trojan | 12217 |
| hysteria2 | 2223 |
| tuic | 272 |
| shadowsocksr | 237 |
| socks | 212 |
| http | 137 |
| anytls | 64 |
| hysteria | 42 |

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
| 80.81 | shadowsocks | 230.2 | 604.4 | 22.45 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 156.146.38.169 |
| 78.29 | shadowsocks | 261.2 | 568.7 | 21.73 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 173.244.56.6 |
| 77.82 | vless | 294.5 | 601.8 | 20.96 | 0.0 | 10.0 | 13.66 | 19.22 | dragon | 172.235.40.143 |
| 77.57 | vless | 304.4 | 664.7 | 20.73 | 0.0 | 10.0 | 13.66 | 19.22 | dragon | 166.0.25.92 |
| 77.2 | shadowsocks | 364.4 | 901.7 | 19.34 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 149.40.57.133 |
| 76.96 | shadowsocks | 375.0 | 948.6 | 19.1 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 149.40.57.138 |
| 76.65 | shadowsocks | 227.9 | 496.0 | 22.5 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 137.184.89.151 |
| 76.64 | shadowsocks | 308.6 | 708.2 | 20.63 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 185.230.230.18 |
| 76.6 | shadowsocks | 302.1 | 682.2 | 20.78 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 45.86.51.18 |
| 76.23 | shadowsocks | 329.2 | 714.2 | 20.16 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 193.151.160.9 |
| 76.2 | shadowsocks | 311.6 | 711.3 | 20.56 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 172.111.38.72 |
| 76.19 | shadowsocks | 408.1 | 1050.1 | 18.33 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 149.40.57.134 |
| 76.18 | shadowsocks | 303.0 | 700.7 | 20.76 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 37.19.198.160 |
| 75.09 | shadowsocks | 268.1 | 578.4 | 21.57 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 216.106.178.169 |
| 74.84 | shadowsocks | 299.5 | 700.4 | 20.84 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 23.150.152.38 |
| 74.27 | shadowsocks | 319.8 | 695.0 | 20.37 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 193.151.163.18 |
| 74.22 | shadowsocks | 335.2 | 741.2 | 20.02 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 193.151.160.18 |
| 74.05 | hysteria2 | 354.7 | 600.3 | 19.57 | 0.0 | 10.0 | 10.5 | 19.22 | dragon | 66.94.121.46 |
| 73.7 | vless | 298.0 | 632.2 | 20.88 | 0.0 | 7.83 | 13.66 | 19.22 | dragon | 172.235.32.253 |
| 73.69 | shadowsocks | 338.5 | 750.0 | 19.94 | 0.0 | 10.0 | 13.14 | 19.22 | dragon | 169.197.142.68 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.938 | 1.0 | 19 | 406 | prefer |
| dragon | 0.922 | 0.848 | 99 | 43754 | prefer |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 8442 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4958 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11584 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5447 | observe |
| barry-far-vless | 0.255 | None | 0 | 5694 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4463 | observe |
| mheidari-all | 0.255 | None | 0 | 14817 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 9 |
| 204 | ProxyError | - | 3 |
| 204 | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 92 | 35 | - |
| global | False | 96 | 35 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
