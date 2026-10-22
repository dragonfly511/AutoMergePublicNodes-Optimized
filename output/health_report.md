# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-22 16:26:24 |
| 运行耗时 | 281.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96315 |
| 去重后节点 | 26646 |
| TCP 可达 | 3000 |
| 真实可用 | 64 |
| Verified 输出 | 64 |
| Global 输出 | 68 |
| All 输出 | 26646 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.1 |
| geo | 1.4 |
| tcp | 79.8 |
| probe | 88.5 |
| real_test | 66.3 |
| china_check | 29.2 |
| write_verified | 0.0 |
| generate | 10.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56937 |
| vmess | 17199 |
| shadowsocks | 12428 |
| trojan | 7907 |
| hysteria2 | 1339 |
| http | 239 |
| shadowsocksr | 166 |
| socks | 55 |
| anytls | 22 |
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
| 75.09 | shadowsocks | 258.5 | 703.1 | 21.79 | 0.0 | 9.49 | 13.23 | 14.58 | Au1rxx-base64 | 37.19.198.243 |
| 74.62 | shadowsocks | 247.4 | 655.5 | 22.05 | 0.0 | 9.26 | 13.23 | 14.58 | Au1rxx-base64 | 193.151.163.18 |
| 73.32 | shadowsocks | 315.7 | 916.2 | 20.47 | 0.0 | 9.54 | 13.23 | 14.58 | Au1rxx-base64 | 45.86.51.18 |
| 72.79 | hysteria2 | 227.5 | 606.6 | 22.51 | 0.0 | 9.34 | 12.86 | 14.58 | Au1rxx-base64 | 129.213.91.185 |
| 72.64 | shadowsocks | 338.5 | 917.2 | 19.94 | 0.0 | 9.39 | 13.23 | 14.58 | Au1rxx-base64 | 185.215.132.18 |
| 72.59 | shadowsocks | 342.3 | 933.8 | 19.85 | 0.0 | 9.43 | 13.23 | 14.58 | Au1rxx-base64 | 185.215.132.9 |
| 71.81 | shadowsocks | 283.5 | 647.2 | 21.22 | 0.0 | 9.15 | 13.23 | 14.58 | Au1rxx-base64 | 156.146.38.167 |
| 71.8 | shadowsocks | 231.7 | 672.2 | 22.41 | 0.0 | 6.08 | 13.23 | 14.58 | Au1rxx-base64 | 185.230.230.18 |
| 71.58 | shadowsocks | 260.8 | 716.1 | 21.74 | 0.0 | 6.03 | 13.23 | 14.58 | Au1rxx-base64 | 37.19.198.160 |
| 71.43 | shadowsocks | 383.0 | 988.8 | 18.91 | 0.0 | 9.25 | 13.23 | 14.58 | Au1rxx-base64 | 193.151.160.18 |
| 70.19 | shadowsocks | 286.3 | 661.6 | 21.15 | 0.0 | 8.98 | 13.23 | 14.58 | Au1rxx-base64 | 156.146.38.168 |
| 69.92 | shadowsocks | 380.8 | 970.2 | 18.96 | 0.0 | 9.29 | 13.23 | 14.58 | Au1rxx-base64 | 193.151.160.9 |
| 69.55 | shadowsocks | 284.5 | 643.4 | 21.19 | 0.0 | 9.18 | 13.23 | 14.58 | Au1rxx-base64 | 156.146.38.170 |
| 68.0 | shadowsocks | 242.5 | 657.5 | 22.17 | 0.0 | 0.0 | 13.23 | 16.6 | mheidari-all | 37.19.198.244 |
| 67.98 | vless | 275.0 | 739.4 | 21.41 | 0.0 | 5.79 | 6.2 | 14.58 | Au1rxx-base64 | 195.123.235.183 |
| 67.98 | shadowsocks | 324.3 | 871.1 | 20.27 | 0.0 | 9.4 | 13.23 | 14.58 | Au1rxx-base64 | 64.42.181.102 |
| 67.31 | hysteria2 | 434.6 | 882.9 | 17.72 | 0.0 | 8.43 | 12.86 | 14.58 | Au1rxx-base64 | 173.212.201.85 |
| 67.25 | hysteria2 | 257.8 | 667.0 | 21.81 | 0.0 | 0.0 | 12.86 | 14.58 | Au1rxx-base64 | clash2.deep-links.com |
| 66.65 | shadowsocks | 368.2 | 786.8 | 19.25 | 0.0 | 8.97 | 13.23 | 14.58 | Au1rxx-base64 | 95.215.201.18 |
| 66.41 | vless | 294.3 | 733.4 | 20.97 | 0.0 | 4.66 | 6.2 | 14.58 | Au1rxx-base64 | 66.70.179.198 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.904 | 0.9 | 40 | 573 | prefer |
| Surfboard-tg-mixed | 0.839 | 0.768 | 56 | 7043 | prefer |
| mheidari-all | 0.83 | 0.757 | 70 | 24062 | prefer |
| Au1rxx-base64 | 0.766 | 0.707 | 181 | 1533 | prefer |
| ninja-vless | 0.383 | 1.0 | 2 | 1791 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 171 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5015 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3641 | observe |
| Epodonios-all | 0.255 | None | 0 | 7538 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10202 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5382 | observe |
| barry-far-vless | 0.255 | None | 0 | 5601 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 61 |
| speed | ClientOSError | - | 12 |
| 204 | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| cn-block | TimeoutError | - | 2 |
| geo | ClientOSError | - | 2 |
| cn-block | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 108 | 64 | - |
| global | False | 115 | 68 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
