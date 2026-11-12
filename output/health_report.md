# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-12 23:26:07 |
| 运行耗时 | 401.5s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 127109 |
| 去重后节点 | 58440 |
| TCP 可达 | 3000 |
| 真实可用 | 61 |
| Verified 输出 | 61 |
| Global 输出 | 63 |
| All 输出 | 58440 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.2 |
| geo | 1.8 |
| tcp | 197.9 |
| probe | 91.0 |
| real_test | 49.3 |
| china_check | 32.1 |
| write_verified | 0.0 |
| generate | 23.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 78267 |
| vmess | 18751 |
| trojan | 13929 |
| shadowsocks | 13031 |
| hysteria2 | 2203 |
| tuic | 271 |
| http | 232 |
| shadowsocksr | 229 |
| socks | 90 |
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
| 76.1 | trojan | 194.5 | 518.5 | 23.28 | 0.0 | 6.55 | 10.43 | 18.34 | dragon | 66.163.112.13 |
| 76.05 | trojan | 197.3 | 515.0 | 23.21 | 0.0 | 6.57 | 10.43 | 18.34 | dragon | 66.163.112.147 |
| 75.95 | trojan | 201.5 | 537.3 | 23.11 | 0.0 | 6.57 | 10.43 | 18.34 | dragon | 66.163.112.31 |
| 75.85 | trojan | 205.8 | 539.5 | 23.01 | 0.0 | 6.57 | 10.43 | 18.34 | dragon | 66.163.112.142 |
| 75.43 | shadowsocks | 189.7 | 500.1 | 23.39 | 0.0 | 4.24 | 13.56 | 18.34 | dragon | 38.145.220.193 |
| 75.1 | trojan | 227.6 | 494.0 | 22.51 | 0.0 | 6.48 | 10.43 | 18.34 | dragon | 167.88.61.52 |
| 74.89 | trojan | 242.7 | 512.3 | 22.16 | 0.0 | 6.46 | 10.43 | 18.34 | dragon | 167.88.61.85 |
| 74.54 | trojan | 222.5 | 493.7 | 22.63 | 0.0 | 5.64 | 10.43 | 18.34 | dragon | 167.88.61.175 |
| 74.29 | trojan | 246.4 | 557.9 | 22.07 | 0.0 | 5.95 | 10.43 | 18.34 | dragon | 167.88.61.193 |
| 73.77 | shadowsocks | 192.6 | 513.5 | 23.32 | 0.0 | 3.05 | 13.56 | 18.34 | dragon | 95.215.201.18 |
| 73.54 | trojan | 281.5 | 769.1 | 21.26 | 0.0 | 6.01 | 10.43 | 18.34 | dragon | 66.163.112.121 |
| 72.8 | shadowsocks | 386.1 | 607.3 | 18.84 | 0.0 | 6.56 | 13.56 | 18.34 | dragon | 103.11.76.248 |
| 72.72 | shadowsocks | 228.7 | 615.0 | 22.48 | 0.0 | 2.84 | 13.56 | 18.34 | dragon | 23.150.152.38 |
| 72.7 | http | 212.7 | 518.4 | 22.86 | 0.0 | 0.0 | 13.66 | 18.68 | ermaozi | 172.64.69.89 |
| 72.42 | http | 224.7 | 548.6 | 22.58 | 0.0 | 0.0 | 13.66 | 18.68 | ermaozi | 172.64.68.89 |
| 71.97 | trojan | 249.8 | 539.1 | 22.0 | 0.0 | 6.3 | 10.43 | 18.34 | dragon | 216.106.186.66 |
| 71.48 | shadowsocks | 373.4 | 868.1 | 19.13 | 0.0 | 6.26 | 13.56 | 18.34 | dragon | 167.88.62.56 |
| 70.9 | trojan | 246.9 | 522.3 | 22.06 | 0.0 | 4.91 | 10.43 | 18.34 | dragon | 216.106.186.32 |
| 70.56 | shadowsocks | 341.6 | 871.9 | 19.87 | 0.0 | 6.29 | 13.56 | 18.34 | dragon | 167.17.67.171 |
| 70.55 | shadowsocks | 311.8 | 671.2 | 20.56 | 0.0 | 6.05 | 13.56 | 18.34 | dragon | 185.215.132.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | 0.936 | 313 | 44243 | prefer |
| ermaozi | 0.953 | 0.945 | 55 | 579 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 13866 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4998 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2737 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11356 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8710 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6364 | observe |
| barry-far-vless | 0.255 | None | 0 | 6512 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4582 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 9 |
| 204 | ClientOSError | - | 8 |
| cn-block | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| geo | ClientOSError | - | 1 |
| geo | TimeoutError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 98 | 61 | - |
| global | False | 99 | 63 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
