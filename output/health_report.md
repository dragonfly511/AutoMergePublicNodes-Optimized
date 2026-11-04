# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-04 05:31:56 |
| 运行耗时 | 443.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 128602 |
| 去重后节点 | 58753 |
| TCP 可达 | 3000 |
| 真实可用 | 77 |
| Verified 输出 | 77 |
| Global 输出 | 78 |
| All 输出 | 58753 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.9 |
| geo | 1.7 |
| tcp | 207.6 |
| probe | 114.9 |
| real_test | 57.3 |
| china_check | 28.0 |
| write_verified | 0.0 |
| generate | 26.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 78739 |
| vmess | 17751 |
| trojan | 16113 |
| shadowsocks | 13148 |
| hysteria2 | 2278 |
| shadowsocksr | 229 |
| socks | 109 |
| http | 94 |
| hysteria | 54 |
| tuic | 54 |
| anytls | 33 |

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
| 77.96 | trojan | 293.2 | 662.6 | 20.99 | 0.0 | 7.92 | 14.06 | 19.98 | dragon | 170.101.101.53 |
| 75.16 | trojan | 265.4 | 624.3 | 21.63 | 0.0 | 3.99 | 14.06 | 19.98 | dragon | 216.152.155.158 |
| 73.37 | hysteria2 | 223.5 | 595.3 | 22.6 | 0.0 | 0.0 | 11.79 | 19.98 | dragon | 88.216.195.188 |
| 72.7 | trojan | 447.0 | 1169.2 | 17.43 | 0.0 | 4.23 | 14.06 | 19.98 | dragon | 66.23.203.21 |
| 72.35 | shadowsocks | 243.3 | 606.1 | 22.15 | 0.0 | 0.0 | 14.22 | 19.98 | dragon | 156.146.38.170 |
| 72.34 | shadowsocks | 243.4 | 619.6 | 22.14 | 0.0 | 0.0 | 14.22 | 19.98 | dragon | 156.146.38.167 |
| 71.3 | hysteria2 | 226.9 | 608.4 | 22.53 | 0.0 | 0.0 | 11.79 | 19.98 | dragon | promo3.goonars.com |
| 71.08 | shadowsocks | 297.8 | 763.8 | 20.88 | 0.0 | 0.0 | 14.22 | 19.98 | dragon | 156.146.38.169 |
| 70.41 | hysteria2 | 235.6 | 509.9 | 22.32 | 0.0 | 0.0 | 11.79 | 19.98 | dragon | 67.216.207.144 |
| 70.0 | shadowsocks | 307.6 | 747.9 | 20.66 | 0.0 | 0.0 | 14.22 | 19.98 | dragon | 37.19.198.243 |
| 69.46 | shadowsocks | 289.7 | 694.5 | 21.07 | 0.0 | 0.0 | 14.22 | 19.98 | dragon | 37.19.198.160 |
| 69.41 | shadowsocks | 370.8 | 920.2 | 19.19 | 0.0 | 0.3 | 14.22 | 19.98 | dragon | 216.9.225.189 |
| 69.35 | shadowsocks | 242.6 | 607.0 | 22.16 | 0.0 | 0.0 | 14.22 | 19.98 | dragon | 67.220.73.178 |
| 68.47 | hysteria2 | 381.2 | 746.6 | 18.95 | 0.0 | 0.0 | 11.79 | 19.98 | dragon | 66.94.121.46 |
| 68.42 | shadowsocks | 329.7 | 823.8 | 20.15 | 0.0 | 0.0 | 14.22 | 19.98 | dragon | 37.19.198.244 |
| 68.38 | shadowsocks | 293.3 | 657.7 | 20.99 | 0.0 | 0.0 | 14.22 | 19.98 | dragon | 185.215.132.9 |
| 68.26 | shadowsocks | 300.7 | 672.1 | 20.82 | 0.0 | 0.0 | 14.22 | 19.98 | dragon | 172.111.38.72 |
| 68.24 | shadowsocks | 311.9 | 781.3 | 20.56 | 0.0 | 0.0 | 14.22 | 19.98 | dragon | 38.128.66.32 |
| 67.95 | shadowsocks | 286.9 | 654.0 | 21.14 | 0.0 | 0.0 | 14.22 | 19.98 | dragon | 149.40.57.135 |
| 67.95 | shadowsocks | 325.3 | 860.1 | 20.25 | 0.0 | 0.0 | 14.22 | 19.98 | dragon | 167.88.62.203 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.985 | 0.907 | 281 | 45574 | prefer |
| ermaozi | 0.932 | 0.95 | 20 | 578 | prefer |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 8544 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 115 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5017 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2526 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3996 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10853 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6022 | observe |
| barry-far-vless | 0.255 | None | 0 | 6238 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4753 | observe |
| mheidari-all | 0.255 | None | 0 | 15265 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 16 |
| geo | ClientOSError | - | 4 |
| cn-block | ClientOSError | - | 2 |
| 204 | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |
| 204 | ClientOSError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:45452: bind: address already in use | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 73 | 77 | - |
| global | False | 75 | 78 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
