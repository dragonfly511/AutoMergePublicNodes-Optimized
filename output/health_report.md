# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-17 12:19:15 |
| 运行耗时 | 346.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99736 |
| 去重后节点 | 27780 |
| TCP 可达 | 3000 |
| 真实可用 | 92 |
| Verified 输出 | 92 |
| Global 输出 | 96 |
| All 输出 | 27780 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.3 |
| geo | 1.5 |
| tcp | 87.4 |
| probe | 126.8 |
| real_test | 80.5 |
| china_check | 27.4 |
| write_verified | 0.1 |
| generate | 14.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58450 |
| vmess | 16660 |
| shadowsocks | 12065 |
| trojan | 10237 |
| hysteria2 | 1329 |
| http | 717 |
| shadowsocksr | 168 |
| socks | 61 |
| anytls | 26 |
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
| 77.14 | shadowsocks | 243.2 | 575.4 | 22.15 | 0.0 | 8.78 | 13.91 | 16.9 | Au1rxx-base64 | 173.244.56.9 |
| 77.13 | shadowsocks | 241.5 | 571.4 | 22.19 | 0.0 | 8.82 | 13.91 | 16.9 | Au1rxx-base64 | 173.244.56.6 |
| 77.02 | shadowsocks | 274.4 | 674.9 | 21.43 | 0.0 | 8.78 | 13.91 | 16.9 | Au1rxx-base64 | 149.22.95.183 |
| 74.83 | http | 208.8 | 578.7 | 22.94 | 0.0 | 0.0 | 14.41 | 19.98 | ermaozi | voteshirleysew.club |
| 74.52 | http | 201.0 | 516.4 | 23.13 | 0.0 | 0.0 | 14.41 | 19.98 | ermaozi | 138.199.35.198 |
| 74.46 | http | 203.5 | 503.9 | 23.07 | 0.0 | 0.0 | 14.41 | 19.98 | ermaozi | 138.199.35.195 |
| 74.42 | http | 204.9 | 519.3 | 23.03 | 0.0 | 0.0 | 14.41 | 19.98 | ermaozi | 138.199.35.214 |
| 74.4 | http | 205.9 | 517.6 | 23.01 | 0.0 | 0.0 | 14.41 | 19.98 | ermaozi | 138.199.35.197 |
| 74.39 | http | 206.4 | 515.4 | 23.0 | 0.0 | 0.0 | 14.41 | 19.98 | ermaozi | 138.199.35.199 |
| 74.38 | http | 207.0 | 533.3 | 22.99 | 0.0 | 0.0 | 14.41 | 19.98 | ermaozi | 138.199.35.216 |
| 74.3 | http | 210.5 | 535.5 | 22.91 | 0.0 | 0.0 | 14.41 | 19.98 | ermaozi | 138.199.35.205 |
| 73.43 | vless | 242.0 | 622.7 | 22.18 | 0.0 | 7.3 | 7.05 | 16.9 | Au1rxx-base64 | 154.29.159.211 |
| 73.31 | http | 209.7 | 524.6 | 22.92 | 0.0 | 0.0 | 14.41 | 19.98 | ermaozi | 138.199.35.196 |
| 73.27 | http | 211.6 | 529.4 | 22.88 | 0.0 | 0.0 | 14.41 | 19.98 | ermaozi | 138.199.35.212 |
| 73.04 | http | 241.9 | 537.9 | 22.18 | 0.0 | 0.0 | 14.41 | 19.98 | ermaozi | 129.153.93.183 |
| 73.01 | shadowsocks | 325.4 | 754.0 | 20.24 | 0.0 | 8.62 | 13.91 | 16.9 | Au1rxx-base64 | 156.146.38.168 |
| 72.79 | shadowsocks | 365.3 | 517.6 | 19.32 | 0.0 | 7.16 | 13.91 | 16.9 | Au1rxx-base64 | 103.11.76.248 |
| 72.61 | shadowsocks | 318.5 | 721.2 | 20.4 | 0.0 | 8.63 | 13.91 | 16.9 | Au1rxx-base64 | 156.146.38.167 |
| 72.58 | vless | 214.7 | 545.0 | 22.81 | 0.0 | 5.82 | 7.05 | 16.9 | Au1rxx-base64 | 154.9.241.170 |
| 72.47 | http | 203.0 | 519.0 | 23.08 | 0.0 | 0.0 | 14.41 | 19.98 | ermaozi | 138.199.35.208 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.788 | 0.71 | 317 | 1994 | prefer |
| ermaozi | 0.474 | 0.444 | 99 | 702 | observe |
| Surfboard-tg-mixed | 0.421 | 0.333 | 39 | 7171 | observe |
| mheidari-all | 0.373 | 0.6 | 5 | 23889 | observe |
| DeltaKronecker-all | 0.365 | 0.294 | 17 | 4999 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4986 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1994 | observe |
| Epodonios-all | 0.255 | None | 0 | 7611 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10247 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5617 | observe |
| barry-far-vless | 0.255 | None | 0 | 5866 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 88 |
| 204 | ProxyError | - | 56 |
| speed | ClientOSError | - | 12 |
| geo | ClientOSError | - | 10 |
| 204 | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 3 |
| speed | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| geo | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| speed | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 79 | 92 | - |
| global | False | 86 | 96 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
