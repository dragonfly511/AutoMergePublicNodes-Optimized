# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-18 06:21:25 |
| 运行耗时 | 356.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98948 |
| 去重后节点 | 27852 |
| TCP 可达 | 3000 |
| 真实可用 | 92 |
| Verified 输出 | 92 |
| Global 输出 | 99 |
| All 输出 | 27852 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.2 |
| geo | 1.5 |
| tcp | 86.9 |
| probe | 112.5 |
| real_test | 91.3 |
| china_check | 40.5 |
| write_verified | 0.0 |
| generate | 14.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58224 |
| vmess | 16716 |
| shadowsocks | 11815 |
| trojan | 9853 |
| hysteria2 | 1304 |
| http | 754 |
| shadowsocksr | 171 |
| socks | 64 |
| anytls | 24 |
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
| 79.12 | shadowsocks | 250.0 | 593.2 | 21.99 | 0.0 | 10.0 | 13.47 | 17.66 | Au1rxx-base64 | 149.22.95.183 |
| 78.4 | shadowsocks | 232.1 | 540.2 | 22.41 | 0.0 | 10.0 | 13.47 | 17.66 | Au1rxx-base64 | 173.244.56.6 |
| 78.07 | shadowsocks | 238.1 | 554.2 | 22.27 | 0.0 | 8.67 | 13.47 | 17.66 | Au1rxx-base64 | 173.244.56.9 |
| 77.14 | vless | 193.1 | 501.6 | 23.31 | 0.0 | 7.82 | 8.35 | 17.66 | Au1rxx-base64 | 45.32.69.110 |
| 76.22 | vless | 204.4 | 511.5 | 23.05 | 0.0 | 8.3 | 8.35 | 17.66 | Au1rxx-base64 | 154.9.241.170 |
| 75.79 | shadowsocks | 321.1 | 537.6 | 20.34 | 0.0 | 10.0 | 13.47 | 17.66 | Au1rxx-base64 | 103.11.76.248 |
| 75.53 | shadowsocks | 291.2 | 651.5 | 21.04 | 0.0 | 10.0 | 13.47 | 17.66 | Au1rxx-base64 | 156.146.38.169 |
| 74.67 | shadowsocks | 295.6 | 670.2 | 20.94 | 0.0 | 10.0 | 13.47 | 17.66 | Au1rxx-base64 | 156.146.38.168 |
| 74.49 | vless | 199.0 | 502.4 | 23.17 | 0.0 | 8.31 | 8.35 | 17.66 | Au1rxx-base64 | 67.209.184.133 |
| 74.45 | http | 208.0 | 533.6 | 22.96 | 0.0 | 0.0 | 14.57 | 19.92 | ermaozi | 138.199.35.198 |
| 74.37 | http | 211.8 | 524.3 | 22.88 | 0.0 | 0.0 | 14.57 | 19.92 | ermaozi | 138.199.35.199 |
| 74.35 | http | 212.2 | 500.9 | 22.86 | 0.0 | 0.0 | 14.57 | 19.92 | ermaozi | 138.199.35.216 |
| 74.28 | http | 237.1 | 673.6 | 22.29 | 0.0 | 0.0 | 14.57 | 19.92 | ermaozi | voteshirleysew.club |
| 74.23 | vless | 196.7 | 505.1 | 23.22 | 0.0 | 10.0 | 8.35 | 17.66 | Au1rxx-base64 | 104.225.239.122 |
| 73.1 | http | 206.0 | 526.4 | 23.01 | 0.0 | 0.0 | 14.57 | 19.92 | ermaozi | 138.199.35.202 |
| 73.09 | http | 223.6 | 563.6 | 22.6 | 0.0 | 0.0 | 14.57 | 19.92 | ermaozi | 138.199.35.215 |
| 72.09 | hysteria2 | 230.9 | 547.6 | 22.43 | 0.0 | 0.0 | 13.0 | 17.66 | Au1rxx-base64 | 66.94.121.46 |
| 71.91 | hysteria2 | 397.5 | 915.4 | 18.58 | 0.0 | 7.51 | 13.0 | 17.66 | Au1rxx-base64 | 129.213.91.185 |
| 71.0 | vless | 319.4 | 720.4 | 20.38 | 0.0 | 7.9 | 8.35 | 17.66 | Au1rxx-base64 | 147.45.60.160 |
| 70.65 | vless | 225.7 | 545.9 | 22.55 | 0.0 | 2.09 | 8.35 | 17.66 | Au1rxx-base64 | 154.12.38.202 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.931 | 0.911 | 101 | 710 | prefer |
| Au1rxx-base64 | 0.849 | 0.781 | 356 | 1738 | prefer |
| Surfboard-tg-mixed | 0.539 | 0.458 | 72 | 7093 | observe |
| mheidari-all | 0.368 | 0.281 | 64 | 23946 | observe |
| tg-OutlineReleasedKey | 0.257 | 1.0 | 1 | 52 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4983 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 4999 | observe |
| Epodonios-all | 0.255 | None | 0 | 7567 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10022 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5669 | observe |
| barry-far-vless | 0.255 | None | 0 | 5884 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4246 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 104 |
| geo | ClientOSError | - | 21 |
| speed | ClientOSError | - | 14 |
| 204 | TimeoutError | - | 9 |
| 204 | ProxyError | - | 7 |
| cn-block | ClientOSError | - | 6 |
| cn-block | ProxyError | - | 5 |
| speed | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| geo | TimeoutError | - | 2 |
| geo | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 70 | 92 | - |
| global | False | 78 | 99 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
