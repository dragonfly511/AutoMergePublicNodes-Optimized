# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-16 00:18:20 |
| 运行耗时 | 319.7s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99664 |
| 去重后节点 | 27756 |
| TCP 可达 | 3000 |
| 真实可用 | 87 |
| Verified 输出 | 87 |
| Global 输出 | 95 |
| All 输出 | 27756 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.5 |
| tcp | 85.7 |
| probe | 98.6 |
| real_test | 93.3 |
| china_check | 22.8 |
| write_verified | 0.0 |
| generate | 11.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58803 |
| vmess | 16484 |
| shadowsocks | 11831 |
| trojan | 10410 |
| hysteria2 | 1223 |
| http | 648 |
| shadowsocksr | 158 |
| socks | 57 |
| anytls | 27 |
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
| 76.24 | shadowsocks | 263.6 | 635.1 | 21.68 | 0.0 | 10.0 | 13.12 | 15.44 | Au1rxx-base64 | 156.146.38.167 |
| 75.38 | shadowsocks | 297.2 | 729.3 | 20.9 | 0.0 | 10.0 | 13.12 | 15.44 | Au1rxx-base64 | 37.19.198.243 |
| 75.25 | shadowsocks | 264.7 | 654.4 | 21.65 | 0.0 | 10.0 | 13.12 | 15.44 | Au1rxx-base64 | 156.146.38.170 |
| 74.95 | shadowsocks | 264.4 | 652.0 | 21.66 | 0.0 | 10.0 | 13.12 | 15.44 | Au1rxx-base64 | 156.146.38.168 |
| 73.71 | vless | 227.7 | 617.4 | 22.51 | 0.0 | 7.23 | 8.53 | 15.44 | Au1rxx-base64 | 195.211.98.43 |
| 73.09 | shadowsocks | 300.1 | 769.0 | 20.83 | 0.0 | 10.0 | 13.12 | 15.44 | Au1rxx-base64 | 37.19.198.160 |
| 72.06 | shadowsocks | 293.2 | 740.1 | 20.99 | 0.0 | 10.0 | 13.12 | 15.44 | Au1rxx-base64 | 37.19.198.236 |
| 71.77 | http | 336.7 | 899.9 | 19.98 | 0.0 | 0.0 | 14.35 | 19.94 | ermaozi | 193.239.236.134 |
| 70.85 | http | 355.0 | 927.3 | 19.56 | 0.0 | 0.0 | 14.35 | 19.94 | ermaozi | 198.44.157.19 |
| 70.53 | shadowsocks | 293.9 | 740.0 | 20.97 | 0.0 | 10.0 | 13.12 | 15.44 | Au1rxx-base64 | 37.19.198.244 |
| 70.07 | vless | 309.9 | 785.6 | 20.6 | 0.0 | 10.0 | 8.53 | 15.44 | Au1rxx-base64 | 69.48.201.136 |
| 68.52 | vless | 318.6 | 737.5 | 20.4 | 0.0 | 6.32 | 8.53 | 15.44 | Au1rxx-base64 | 66.70.179.198 |
| 68.26 | http | 310.7 | 735.4 | 20.59 | 0.0 | 0.0 | 14.35 | 19.94 | ermaozi | 35.183.131.26 |
| 67.78 | vless | 392.0 | 996.3 | 18.7 | 0.0 | 6.94 | 8.53 | 15.44 | Au1rxx-base64 | 185.95.231.156 |
| 67.44 | hysteria2 | 275.2 | 725.7 | 21.41 | 0.0 | 2.86 | 9.23 | 15.44 | Au1rxx-base64 | 129.213.91.185 |
| 67.09 | http | 323.2 | 838.5 | 20.3 | 0.0 | 0.0 | 14.35 | 19.94 | ermaozi | 12.202.180.10 |
| 66.69 | http | 308.7 | 726.1 | 20.63 | 0.0 | 0.0 | 14.35 | 19.94 | ermaozi | 206.223.183.13 |
| 66.64 | shadowsocks | 306.4 | 639.3 | 20.69 | 0.0 | 5.46 | 13.12 | 15.44 | Au1rxx-base64 | 149.22.95.183 |
| 66.3 | shadowsocks | 260.7 | 631.6 | 21.74 | 0.0 | 0.0 | 13.12 | 15.44 | Au1rxx-base64 | 156.146.38.169 |
| 66.13 | vless | 360.1 | 887.7 | 19.44 | 0.0 | 7.72 | 8.53 | 15.44 | Au1rxx-base64 | 23.94.251.190 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.997 | 0.985 | 67 | 659 | prefer |
| Au1rxx-base64 | 0.852 | 0.776 | 406 | 1933 | prefer |
| mheidari-all | 0.413 | 0.331 | 169 | 24047 | observe |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 7135 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5089 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 5147 | observe |
| Epodonios-all | 0.255 | None | 0 | 7682 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9914 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5628 | observe |
| barry-far-vless | 0.255 | None | 0 | 5879 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4235 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.252 | None | 0 | 1933 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 113 |
| speed | ClientOSError | - | 36 |
| geo | ClientOSError | - | 21 |
| 204 | ProxyError | - | 9 |
| cn-block | ClientOSError | - | 8 |
| 204 | TimeoutError | - | 8 |
| 204 | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 2 |
| geo | TimeoutError | - | 1 |
| speed | TimeoutError | - | 1 |
| cn-block | ServerDisconnectedError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 89 | 87 | - |
| global | False | 93 | 95 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
