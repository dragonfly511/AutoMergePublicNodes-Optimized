# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-14 13:17:01 |
| 运行耗时 | 408.6s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 127937 |
| 去重后节点 | 58935 |
| TCP 可达 | 3000 |
| 真实可用 | 56 |
| Verified 输出 | 56 |
| Global 输出 | 56 |
| All 输出 | 58935 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.8 |
| geo | 1.7 |
| tcp | 191.3 |
| probe | 106.1 |
| real_test | 37.7 |
| china_check | 32.1 |
| write_verified | 0.0 |
| generate | 30.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77868 |
| vmess | 18747 |
| trojan | 14909 |
| shadowsocks | 13535 |
| hysteria2 | 2183 |
| shadowsocksr | 226 |
| http | 182 |
| socks | 118 |
| hysteria | 61 |
| tuic | 55 |
| anytls | 53 |

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
| 76.52 | trojan | 243.6 | 658.9 | 22.14 | 0.0 | 7.22 | 11.0 | 19.66 | dragon | 66.163.122.26 |
| 75.64 | hysteria2 | 329.5 | 856.9 | 20.15 | 0.0 | 2.9 | 13.93 | 19.66 | dragon | 34.24.25.1 |
| 74.95 | hysteria2 | 234.1 | 654.9 | 22.36 | 0.0 | 0.0 | 13.93 | 19.66 | dragon | 206.189.229.48 |
| 74.85 | trojan | 357.8 | 900.3 | 19.5 | 0.0 | 7.19 | 11.0 | 19.66 | dragon | 216.152.155.50 |
| 73.79 | shadowsocks | 294.1 | 722.8 | 20.97 | 0.0 | 4.0 | 13.88 | 19.66 | dragon | 193.151.160.9 |
| 73.38 | trojan | 419.8 | 1106.0 | 18.06 | 0.0 | 7.16 | 11.0 | 19.66 | dragon | 216.152.155.23 |
| 73.24 | http | 262.6 | 709.8 | 21.7 | 0.0 | 0.0 | 14.38 | 19.66 | ermaozi | 172.64.68.89 |
| 73.14 | http | 266.7 | 716.6 | 21.6 | 0.0 | 0.0 | 14.38 | 19.66 | ermaozi | 172.64.69.89 |
| 72.73 | trojan | 235.7 | 648.0 | 22.32 | 0.0 | 7.25 | 11.0 | 19.66 | dragon | 66.163.122.81 |
| 72.56 | trojan | 243.6 | 662.8 | 22.14 | 0.0 | 7.26 | 11.0 | 19.66 | dragon | 66.163.122.30 |
| 71.86 | trojan | 357.6 | 683.8 | 19.5 | 0.0 | 9.72 | 11.0 | 19.66 | dragon | 216.106.186.32 |
| 71.81 | trojan | 323.6 | 711.8 | 20.29 | 0.0 | 7.04 | 11.0 | 19.66 | dragon | 66.163.114.114 |
| 71.71 | trojan | 364.5 | 678.2 | 19.34 | 0.0 | 9.63 | 11.0 | 19.66 | dragon | 216.106.186.155 |
| 71.37 | shadowsocks | 235.2 | 644.6 | 22.33 | 0.0 | 0.0 | 13.88 | 19.66 | dragon | 185.230.230.18 |
| 71.32 | shadowsocks | 299.5 | 674.2 | 20.84 | 0.0 | 7.06 | 13.88 | 19.66 | dragon | 38.22.17.219 |
| 71.31 | shadowsocks | 237.8 | 648.7 | 22.27 | 0.0 | 0.0 | 13.88 | 19.66 | dragon | 172.111.38.72 |
| 71.15 | shadowsocks | 244.7 | 631.7 | 22.11 | 0.0 | 0.0 | 13.88 | 19.66 | dragon | 149.40.57.133 |
| 71.07 | shadowsocks | 248.3 | 645.5 | 22.03 | 0.0 | 0.0 | 13.88 | 19.66 | dragon | 193.151.163.18 |
| 70.95 | shadowsocks | 253.4 | 632.9 | 21.91 | 0.0 | 0.0 | 13.88 | 19.66 | dragon | 67.220.73.178 |
| 70.92 | shadowsocks | 255.0 | 666.7 | 21.88 | 0.0 | 0.0 | 13.88 | 19.66 | dragon | 15.204.247.124 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.962 | 0.885 | 270 | 44709 | prefer |
| ermaozi | 0.906 | 0.917 | 24 | 527 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 14251 | observe |
| Surfboard-tg-mixed | 0.287 | 0.5 | 2 | 8883 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4966 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2652 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11479 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6276 | observe |
| barry-far-vless | 0.255 | None | 0 | 6459 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4551 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 13 |
| 204 | ProxyError | - | 11 |
| 204 | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| 204 | TimeoutError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 55 | 56 | - |
| global | False | 57 | 56 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
