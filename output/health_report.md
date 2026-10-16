# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-16 18:22:03 |
| 运行耗时 | 306.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 98871 |
| 去重后节点 | 27543 |
| TCP 可达 | 3000 |
| 真实可用 | 95 |
| Verified 输出 | 95 |
| Global 输出 | 97 |
| All 输出 | 27543 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.8 |
| geo | 1.4 |
| tcp | 88.1 |
| probe | 100.8 |
| real_test | 74.6 |
| china_check | 27.6 |
| write_verified | 0.0 |
| generate | 9.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58106 |
| vmess | 16415 |
| shadowsocks | 12122 |
| trojan | 10021 |
| hysteria2 | 1302 |
| http | 630 |
| shadowsocksr | 164 |
| socks | 59 |
| anytls | 29 |
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
| 75.94 | shadowsocks | 251.2 | 627.1 | 21.96 | 0.0 | 10.0 | 12.9 | 15.08 | Au1rxx-base64 | 156.146.38.168 |
| 75.92 | shadowsocks | 252.1 | 633.0 | 21.94 | 0.0 | 10.0 | 12.9 | 15.08 | Au1rxx-base64 | 156.146.38.167 |
| 75.89 | hysteria2 | 281.7 | 720.4 | 21.26 | 0.0 | 10.0 | 11.05 | 15.08 | Au1rxx-base64 | 129.213.91.185 |
| 75.85 | shadowsocks | 255.4 | 630.6 | 21.87 | 0.0 | 10.0 | 12.9 | 15.08 | Au1rxx-base64 | 156.146.38.169 |
| 73.23 | shadowsocks | 312.2 | 757.6 | 20.55 | 0.0 | 10.0 | 12.9 | 15.08 | Au1rxx-base64 | 37.19.198.236 |
| 72.28 | vless | 275.3 | 678.0 | 21.41 | 0.0 | 10.0 | 7.46 | 15.08 | Au1rxx-base64 | 147.45.60.160 |
| 72.12 | shadowsocks | 383.4 | 991.2 | 18.9 | 0.0 | 10.0 | 12.9 | 15.08 | Au1rxx-base64 | 37.19.198.243 |
| 69.88 | shadowsocks | 288.8 | 581.6 | 21.09 | 0.0 | 8.77 | 12.9 | 15.08 | Au1rxx-base64 | 173.244.56.9 |
| 69.62 | shadowsocks | 300.5 | 599.4 | 20.82 | 0.0 | 10.0 | 12.9 | 15.08 | Au1rxx-base64 | 173.244.56.6 |
| 68.48 | shadowsocks | 315.5 | 769.7 | 20.47 | 0.0 | 10.0 | 12.9 | 15.08 | Au1rxx-base64 | 37.19.198.244 |
| 68.09 | shadowsocks | 386.2 | 870.7 | 18.84 | 0.0 | 10.0 | 12.9 | 15.08 | Au1rxx-base64 | 149.22.95.183 |
| 67.94 | http | 414.5 | 1016.9 | 18.18 | 0.0 | 0.0 | 14.36 | 19.9 | ermaozi | 12.202.180.118 |
| 67.36 | shadowsocks | 340.6 | 852.1 | 19.89 | 0.0 | 10.0 | 12.9 | 15.08 | Au1rxx-base64 | 37.19.198.160 |
| 65.68 | vless | 336.5 | 760.0 | 19.99 | 0.0 | 6.86 | 7.46 | 15.08 | Au1rxx-base64 | 66.70.179.198 |
| 65.32 | hysteria2 | 453.6 | 882.5 | 17.28 | 0.0 | 9.55 | 11.05 | 15.08 | Au1rxx-base64 | 62.210.124.146 |
| 64.89 | vless | 306.5 | 559.8 | 20.68 | 0.0 | 6.79 | 7.46 | 15.08 | Au1rxx-base64 | 154.29.159.211 |
| 64.85 | vless | 335.2 | 815.2 | 20.02 | 0.0 | 10.0 | 7.46 | 15.08 | Au1rxx-base64 | 69.48.201.136 |
| 63.93 | shadowsocks | 620.3 | 1240.6 | 13.42 | 0.0 | 10.0 | 12.9 | 15.08 | Au1rxx-base64 | 51.222.136.236 |
| 63.74 | http | 515.0 | 1273.8 | 15.86 | 0.0 | 0.0 | 14.36 | 19.9 | ermaozi | 206.223.161.47 |
| 63.7 | http | 377.3 | 917.9 | 19.04 | 0.0 | 0.0 | 14.36 | 19.9 | ermaozi | 198.44.135.19 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | 1.0 | 57 | 618 | prefer |
| Au1rxx-base64 | 0.743 | 0.664 | 304 | 1991 | prefer |
| mheidari-all | 0.666 | 0.593 | 27 | 23759 | observe |
| Surfboard-tg-mixed | 0.352 | 0.364 | 11 | 7090 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5024 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1991 | observe |
| Epodonios-all | 0.255 | None | 0 | 7602 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9925 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5572 | observe |
| barry-far-vless | 0.255 | None | 0 | 5822 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 87 |
| geo | ClientOSError | - | 10 |
| speed | ClientOSError | - | 9 |
| 204 | ProxyError | - | 6 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 3 |
| geo | ProxyError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 93 | 95 | - |
| global | False | 99 | 97 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
