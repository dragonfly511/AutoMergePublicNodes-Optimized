# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-09 15:40:42 |
| 运行耗时 | 411.4s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 126187 |
| 去重后节点 | 58633 |
| TCP 可达 | 3000 |
| 真实可用 | 73 |
| Verified 输出 | 73 |
| Global 输出 | 74 |
| All 输出 | 58633 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.5 |
| geo | 1.6 |
| tcp | 197.6 |
| probe | 104.4 |
| real_test | 51.1 |
| china_check | 27.5 |
| write_verified | 0.0 |
| generate | 22.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 76729 |
| vmess | 18631 |
| trojan | 14535 |
| shadowsocks | 13348 |
| hysteria2 | 2243 |
| shadowsocksr | 371 |
| http | 91 |
| socks | 88 |
| tuic | 61 |
| hysteria | 60 |
| anytls | 30 |

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
| 79.66 | trojan | 195.2 | 521.7 | 23.26 | 0.0 | 9.67 | 9.55 | 19.68 | dragon | 66.163.112.242 |
| 76.84 | shadowsocks | 315.0 | 802.3 | 20.49 | 0.0 | 7.33 | 13.84 | 19.68 | dragon | 103.11.76.248 |
| 72.93 | shadowsocks | 184.4 | 486.4 | 23.51 | 0.0 | 0.0 | 13.84 | 19.68 | dragon | 38.145.220.193 |
| 72.42 | shadowsocks | 210.9 | 519.9 | 22.9 | 0.0 | 0.0 | 13.84 | 19.68 | dragon | 173.244.56.6 |
| 72.33 | shadowsocks | 193.2 | 525.2 | 23.31 | 0.0 | 0.0 | 13.84 | 19.68 | dragon | 95.215.201.18 |
| 70.85 | hysteria2 | 291.3 | 636.2 | 21.04 | 0.0 | 0.0 | 13.0 | 19.68 | dragon | promo3.goonars.com |
| 69.97 | shadowsocks | 282.5 | 279.1 | 21.24 | 4.53 | 1.94 | 13.84 | 19.68 | dragon | 149.22.87.240 |
| 69.93 | shadowsocks | 270.2 | 643.5 | 21.52 | 0.0 | 0.0 | 13.84 | 19.68 | dragon | 167.17.67.171 |
| 69.72 | http | 304.7 | 672.3 | 20.72 | 0.0 | 0.0 | 14.35 | 19.54 | ermaozi | 38.247.141.135 |
| 69.09 | hysteria2 | 279.9 | 623.5 | 21.3 | 0.0 | 0.0 | 13.0 | 19.68 | dragon | 88.216.195.188 |
| 68.96 | shadowsocks | 262.9 | 544.2 | 21.69 | 0.0 | 1.17 | 13.84 | 19.68 | dragon | 149.22.95.183 |
| 68.62 | shadowsocks | 218.3 | 500.0 | 22.73 | 0.0 | 0.0 | 13.84 | 19.68 | dragon | 169.197.142.68 |
| 68.45 | shadowsocks | 360.8 | 983.4 | 19.43 | 0.0 | 0.0 | 13.84 | 19.68 | dragon | 137.184.89.151 |
| 67.93 | shadowsocks | 340.0 | 851.2 | 19.91 | 0.0 | 0.0 | 13.84 | 19.68 | dragon | 167.88.62.203 |
| 67.75 | shadowsocks | 395.9 | 1024.9 | 18.61 | 0.0 | 0.0 | 13.84 | 19.68 | dragon | 156.146.38.170 |
| 67.24 | hysteria2 | 387.3 | 912.3 | 18.81 | 0.0 | 0.0 | 13.0 | 19.68 | dragon | 34.24.25.1 |
| 66.04 | shadowsocks | 263.5 | 637.1 | 21.68 | 0.0 | 3.87 | 13.84 | 19.68 | dragon | 156.146.38.168 |
| 66.04 | hysteria2 | 327.8 | 734.0 | 20.19 | 0.0 | 0.0 | 13.0 | 19.68 | dragon | 206.189.229.48 |
| 65.74 | shadowsocks | 257.5 | 625.3 | 21.82 | 0.0 | 0.0 | 13.84 | 19.68 | dragon | 156.146.38.167 |
| 65.18 | shadowsocks | 250.5 | 681.9 | 21.98 | 0.0 | 0.0 | 13.84 | 19.68 | dragon | 23.150.152.38 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.954 | 0.877 | 236 | 45021 | prefer |
| ermaozi | 0.896 | 0.947 | 19 | 518 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 14143 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4976 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2754 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11022 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8247 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5893 | observe |
| barry-far-vless | 0.255 | None | 0 | 6048 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4583 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 22 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |
| cn-block | TimeoutError | - | 1 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 80 | 73 | - |
| global | False | 81 | 74 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
