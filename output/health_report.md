# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-21 06:15:37 |
| 运行耗时 | 439.2s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 127232 |
| 去重后节点 | 59084 |
| TCP 可达 | 3000 |
| 真实可用 | 91 |
| Verified 输出 | 91 |
| Global 输出 | 93 |
| All 输出 | 59084 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.4 |
| geo | 1.6 |
| tcp | 195.3 |
| probe | 109.4 |
| real_test | 74.5 |
| china_check | 28.8 |
| write_verified | 0.0 |
| generate | 23.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 76557 |
| vmess | 19416 |
| shadowsocks | 14736 |
| trojan | 13778 |
| hysteria2 | 2062 |
| shadowsocksr | 246 |
| socks | 158 |
| http | 138 |
| hysteria | 61 |
| tuic | 51 |
| anytls | 29 |

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
| 70.11 | shadowsocks | 215.4 | 578.9 | 22.79 | 0.0 | 0.0 | 13.02 | 18.8 | dragon | 104.238.140.45 |
| 68.4 | http | 206.6 | 538.3 | 22.99 | 0.0 | 0.0 | 12.21 | 16.2 | ermaozi | 38.95.111.226 |
| 68.26 | shadowsocks | 445.4 | 962.9 | 17.47 | 0.0 | 8.4 | 13.02 | 18.8 | dragon | 185.215.132.18 |
| 68.05 | hysteria2 | 407.8 | 983.0 | 18.34 | 0.0 | 0.0 | 14.17 | 18.8 | dragon | 206.189.229.48 |
| 67.54 | shadowsocks | 261.6 | 639.7 | 21.72 | 0.0 | 0.0 | 13.02 | 18.8 | dragon | 156.146.38.170 |
| 67.2 | shadowsocks | 313.6 | 787.7 | 20.52 | 0.0 | 0.0 | 13.02 | 18.8 | dragon | 173.244.56.9 |
| 66.96 | hysteria2 | 230.4 | 233.3 | 22.44 | 6.25 | 0.0 | 14.17 | 18.8 | dragon | 8.209.247.109 |
| 66.35 | http | 317.1 | 832.3 | 20.44 | 0.0 | 0.0 | 12.21 | 16.2 | ermaozi | 172.64.68.89 |
| 66.04 | vless | 315.5 | 619.7 | 20.48 | 0.0 | 6.68 | 9.75 | 18.8 | dragon | 179.254.92.134 |
| 66.03 | shadowsocks | 391.8 | 1067.5 | 18.71 | 0.0 | 0.0 | 13.02 | 18.8 | dragon | 23.150.152.38 |
| 65.49 | shadowsocks | 282.6 | 289.6 | 21.24 | 4.14 | 0.0 | 13.02 | 18.8 | dragon | jpa.123069.xyz |
| 64.91 | shadowsocks | 440.3 | 1202.6 | 17.59 | 0.0 | 0.0 | 13.02 | 18.8 | dragon | 137.184.89.151 |
| 64.62 | shadowsocks | 474.3 | 1271.1 | 16.8 | 0.0 | 0.0 | 13.02 | 18.8 | dragon | 173.244.56.6 |
| 64.58 | shadowsocks | 259.8 | 641.9 | 21.76 | 0.0 | 0.0 | 13.02 | 18.8 | dragon | 156.146.38.168 |
| 63.86 | shadowsocks | 507.3 | 1384.6 | 16.04 | 0.0 | 0.0 | 13.02 | 18.8 | dragon | 156.146.38.169 |
| 63.14 | shadowsocks | 336.1 | 715.5 | 20.0 | 0.0 | 0.0 | 13.02 | 18.8 | dragon | 37.19.198.243 |
| 63.1 | shadowsocks | 429.4 | 1096.9 | 17.84 | 0.0 | 0.0 | 13.02 | 18.8 | dragon | 167.88.62.203 |
| 62.9 | vless | 426.3 | 918.6 | 17.91 | 0.0 | 6.68 | 9.75 | 18.8 | dragon | 179.254.92.190 |
| 62.89 | shadowsocks | 288.2 | 616.9 | 21.11 | 0.0 | 0.0 | 13.02 | 18.8 | dragon | 149.22.95.183 |
| 62.75 | shadowsocks | 304.9 | 360.1 | 20.72 | 1.49 | 0.0 | 13.02 | 18.8 | dragon | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.979 | 1.0 | 24 | 443 | prefer |
| dragon | 0.769 | 0.691 | 278 | 44818 | prefer |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 8565 | observe |
| mheidari-all | 0.335 | 1.0 | 1 | 14439 | observe |
| tg-oneclickvpnkeys | 0.26 | 1.0 | 1 | 115 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5045 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2910 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11818 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5496 | observe |
| barry-far-vless | 0.255 | None | 0 | 5914 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4518 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 70 |
| cn-block | TimeoutError | - | 6 |
| 204 | ClientOSError | - | 5 |
| cn-block | ClientOSError | - | 3 |
| speed | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 63 | 91 | - |
| global | False | 70 | 93 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
