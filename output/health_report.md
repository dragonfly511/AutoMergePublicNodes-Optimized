# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-15 12:26:09 |
| 运行耗时 | 304.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 100008 |
| 去重后节点 | 27884 |
| TCP 可达 | 3000 |
| 真实可用 | 95 |
| Verified 输出 | 95 |
| Global 输出 | 103 |
| All 输出 | 27884 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.5 |
| tcp | 86.4 |
| probe | 105.0 |
| real_test | 64.1 |
| china_check | 25.9 |
| write_verified | 0.2 |
| generate | 13.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59108 |
| vmess | 16442 |
| shadowsocks | 12112 |
| trojan | 10181 |
| hysteria2 | 1167 |
| http | 707 |
| shadowsocksr | 170 |
| socks | 66 |
| anytls | 32 |
| hysteria | 17 |
| tuic | 6 |

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
| 75.37 | shadowsocks | 281.7 | 652.9 | 21.26 | 0.0 | 10.0 | 13.85 | 16.28 | Au1rxx-base64 | 156.146.38.168 |
| 75.29 | shadowsocks | 290.2 | 674.6 | 21.06 | 0.0 | 10.0 | 13.85 | 16.28 | Au1rxx-base64 | 156.146.38.170 |
| 74.2 | shadowsocks | 274.8 | 637.9 | 21.42 | 0.0 | 10.0 | 13.85 | 16.28 | Au1rxx-base64 | 156.146.38.167 |
| 74.03 | shadowsocks | 297.3 | 806.1 | 20.9 | 0.0 | 10.0 | 13.85 | 16.28 | Au1rxx-base64 | 37.19.198.236 |
| 73.09 | shadowsocks | 342.2 | 832.1 | 19.86 | 0.0 | 10.0 | 13.85 | 16.28 | Au1rxx-base64 | 156.146.38.169 |
| 72.53 | http | 292.3 | 747.9 | 21.01 | 0.0 | 0.0 | 14.44 | 19.58 | ermaozi | 147.182.216.4 |
| 71.92 | shadowsocks | 301.8 | 810.0 | 20.79 | 0.0 | 10.0 | 13.85 | 16.28 | Au1rxx-base64 | 37.19.198.160 |
| 71.46 | shadowsocks | 315.8 | 618.0 | 20.47 | 0.0 | 10.0 | 13.85 | 16.28 | Au1rxx-base64 | 173.244.56.9 |
| 71.4 | shadowsocks | 313.9 | 617.1 | 20.51 | 0.0 | 10.0 | 13.85 | 16.28 | Au1rxx-base64 | 173.244.56.6 |
| 70.48 | shadowsocks | 268.4 | 723.2 | 21.57 | 0.0 | 2.78 | 13.85 | 16.28 | Au1rxx-base64 | 37.19.198.243 |
| 70.13 | http | 288.1 | 727.8 | 21.11 | 0.0 | 0.0 | 14.44 | 19.58 | ermaozi | 198.44.138.27 |
| 68.61 | http | 353.6 | 951.2 | 19.59 | 0.0 | 0.0 | 14.44 | 19.58 | ermaozi | 149.88.21.140 |
| 68.18 | shadowsocks | 434.0 | 918.7 | 17.73 | 0.0 | 10.0 | 13.85 | 16.28 | Au1rxx-base64 | 149.22.95.183 |
| 67.89 | shadowsocks | 432.3 | 482.7 | 17.77 | 0.0 | 10.0 | 13.85 | 16.28 | Au1rxx-base64 | 103.11.76.248 |
| 67.81 | shadowsocks | 263.6 | 711.5 | 21.68 | 0.0 | 0.0 | 13.85 | 16.28 | Au1rxx-base64 | 37.19.198.244 |
| 67.57 | hysteria2 | 241.8 | 677.3 | 22.18 | 0.0 | 0.0 | 12.0 | 16.28 | Au1rxx-base64 | 129.213.91.185 |
| 67.5 | http | 399.1 | 960.8 | 18.54 | 0.0 | 0.0 | 14.44 | 19.58 | ermaozi | 129.212.181.253 |
| 67.06 | vless | 269.7 | 635.5 | 21.54 | 0.0 | 0.0 | 9.24 | 16.28 | Au1rxx-base64 | 216.227.161.95 |
| 66.57 | vless | 290.8 | 708.5 | 21.05 | 0.0 | 0.0 | 9.24 | 16.28 | Au1rxx-base64 | 66.70.179.198 |
| 66.52 | vless | 267.4 | 624.2 | 21.59 | 0.0 | 0.0 | 9.24 | 16.28 | Au1rxx-base64 | 195.211.98.43 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | 0.987 | 77 | 703 | prefer |
| Au1rxx-base64 | 0.782 | 0.71 | 307 | 1830 | prefer |
| mheidari-all | 0.6 | 0.522 | 23 | 24080 | observe |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 7139 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5089 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 5147 | observe |
| Epodonios-all | 0.255 | None | 0 | 7652 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10114 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5693 | observe |
| barry-far-vless | 0.255 | None | 0 | 5924 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1830 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 58 |
| speed | ClientOSError | - | 11 |
| 204 | ProxyError | - | 9 |
| 204 | TimeoutError | - | 6 |
| geo | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 5 |
| cn-block | TimeoutError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 95 | 95 | - |
| global | False | 102 | 103 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
