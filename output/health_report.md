# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-24 22:10:23 |
| 运行耗时 | 407.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 122939 |
| 去重后节点 | 59992 |
| TCP 可达 | 3000 |
| 真实可用 | 88 |
| Verified 输出 | 88 |
| Global 输出 | 88 |
| All 输出 | 59992 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.4 |
| geo | 1.8 |
| tcp | 199.3 |
| probe | 105.8 |
| real_test | 32.4 |
| china_check | 28.1 |
| write_verified | 0.0 |
| generate | 31.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 74896 |
| vmess | 19035 |
| trojan | 13148 |
| shadowsocks | 12860 |
| hysteria2 | 2307 |
| shadowsocksr | 245 |
| socks | 163 |
| http | 106 |
| anytls | 66 |
| hysteria | 61 |
| tuic | 52 |

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
| 77.01 | shadowsocks | 230.9 | 628.1 | 22.43 | 0.0 | 8.54 | 12.78 | 17.26 | dragon | 37.19.198.244 |
| 76.54 | shadowsocks | 240.8 | 645.1 | 22.2 | 0.0 | 8.8 | 12.78 | 17.26 | dragon | 172.111.38.72 |
| 75.8 | shadowsocks | 242.2 | 668.0 | 22.17 | 0.0 | 8.09 | 12.78 | 17.26 | dragon | 185.230.230.18 |
| 75.55 | shadowsocks | 260.6 | 670.2 | 21.75 | 0.0 | 8.26 | 12.78 | 17.26 | dragon | 149.40.57.135 |
| 75.03 | shadowsocks | 230.1 | 634.0 | 22.45 | 0.0 | 8.54 | 12.78 | 17.26 | dragon | 37.19.198.160 |
| 74.53 | shadowsocks | 315.5 | 851.2 | 20.48 | 0.0 | 8.51 | 12.78 | 17.26 | dragon | 15.204.233.41 |
| 74.22 | shadowsocks | 332.3 | 884.0 | 20.08 | 0.0 | 8.6 | 12.78 | 17.26 | dragon | 38.91.100.39 |
| 74.03 | shadowsocks | 309.1 | 832.3 | 20.62 | 0.0 | 7.87 | 12.78 | 17.26 | dragon | 149.40.57.138 |
| 73.91 | shadowsocks | 334.0 | 891.5 | 20.05 | 0.0 | 8.32 | 12.78 | 17.26 | dragon | 149.40.57.134 |
| 73.7 | shadowsocks | 333.5 | 848.5 | 20.06 | 0.0 | 9.1 | 12.78 | 17.26 | dragon | 38.64.138.135 |
| 73.01 | shadowsocks | 375.0 | 1019.7 | 19.1 | 0.0 | 8.37 | 12.78 | 17.26 | dragon | 15.204.246.132 |
| 72.51 | shadowsocks | 343.2 | 710.7 | 19.83 | 0.0 | 8.6 | 12.78 | 17.26 | dragon | 169.197.140.247 |
| 72.18 | shadowsocks | 321.7 | 725.6 | 20.33 | 0.0 | 7.45 | 12.78 | 17.26 | dragon | 193.151.160.9 |
| 72.12 | shadowsocks | 331.3 | 743.8 | 20.11 | 0.0 | 7.78 | 12.78 | 17.26 | dragon | 38.91.107.57 |
| 71.94 | shadowsocks | 235.3 | 647.7 | 22.33 | 0.0 | 8.57 | 12.78 | 17.26 | dragon | 37.19.198.243 |
| 71.77 | shadowsocks | 263.4 | 659.6 | 21.68 | 0.0 | 8.33 | 12.78 | 17.26 | dragon | 200.102.179.179 |
| 71.7 | shadowsocks | 332.9 | 884.1 | 20.07 | 0.0 | 8.41 | 12.78 | 17.26 | dragon | 15.204.246.107 |
| 71.7 | shadowsocks | 419.8 | 1143.1 | 18.06 | 0.0 | 8.1 | 12.78 | 17.26 | dragon | 193.151.163.18 |
| 71.69 | shadowsocks | 245.1 | 680.1 | 22.1 | 0.0 | 8.55 | 12.78 | 17.26 | dragon | 37.19.198.236 |
| 71.6 | shadowsocks | 292.8 | 678.9 | 21.0 | 0.0 | 7.31 | 12.78 | 17.26 | dragon | 156.146.38.168 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.969 | 1.0 | 20 | 366 | prefer |
| dragon | 0.954 | 0.876 | 251 | 44710 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 14970 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4839 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11536 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8239 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5468 | observe |
| barry-far-vless | 0.255 | None | 0 | 5508 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4546 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 13 |
| 204 | ProxyError | - | 8 |
| 204 | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| speed | TimeoutError | - | 2 |
| 204 | TimeoutError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 112 | 88 | - |
| global | False | 123 | 88 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
