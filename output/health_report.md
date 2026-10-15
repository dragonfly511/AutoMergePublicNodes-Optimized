# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-15 11:37:21 |
| 运行耗时 | 307.6s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99891 |
| 去重后节点 | 27872 |
| TCP 可达 | 3000 |
| 真实可用 | 95 |
| Verified 输出 | 95 |
| Global 输出 | 102 |
| All 输出 | 27872 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 85.5 |
| probe | 105.1 |
| real_test | 68.1 |
| china_check | 25.7 |
| write_verified | 0.0 |
| generate | 13.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59046 |
| vmess | 16422 |
| shadowsocks | 12077 |
| trojan | 10188 |
| hysteria2 | 1161 |
| http | 706 |
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
| 71.83 | shadowsocks | 263.8 | 713.2 | 21.67 | 0.0 | 10.0 | 12.74 | 16.42 | Au1rxx-base64 | 37.19.198.236 |
| 71.36 | shadowsocks | 315.3 | 621.9 | 20.48 | 0.0 | 10.0 | 12.74 | 16.42 | Au1rxx-base64 | 156.146.38.167 |
| 71.31 | shadowsocks | 281.1 | 649.8 | 21.27 | 0.0 | 10.0 | 12.74 | 16.42 | Au1rxx-base64 | 156.146.38.168 |
| 71.03 | shadowsocks | 337.9 | 661.4 | 19.96 | 0.0 | 10.0 | 12.74 | 16.42 | Au1rxx-base64 | 156.146.38.169 |
| 70.92 | vless | 326.5 | 725.0 | 20.22 | 0.0 | 7.53 | 9.47 | 16.42 | Au1rxx-base64 | 193.233.202.250 |
| 70.15 | shadowsocks | 331.0 | 651.7 | 20.12 | 0.0 | 10.0 | 12.74 | 16.42 | Au1rxx-base64 | 173.244.56.9 |
| 70.1 | http | 275.4 | 700.9 | 21.4 | 0.0 | 0.0 | 13.9 | 19.12 | ermaozi | 147.182.216.4 |
| 68.68 | shadowsocks | 371.9 | 727.0 | 19.17 | 0.0 | 10.0 | 12.74 | 16.42 | Au1rxx-base64 | 149.22.95.183 |
| 68.3 | http | 280.7 | 741.6 | 21.28 | 0.0 | 0.0 | 13.9 | 19.12 | ermaozi | 149.88.21.140 |
| 68.24 | shadowsocks | 314.2 | 859.7 | 20.5 | 0.0 | 10.0 | 12.74 | 16.42 | Au1rxx-base64 | 37.19.198.160 |
| 67.82 | hysteria2 | 250.0 | 704.4 | 21.99 | 0.0 | 0.0 | 10.91 | 16.42 | Au1rxx-base64 | 129.213.91.185 |
| 67.71 | shadowsocks | 355.5 | 707.1 | 19.55 | 0.0 | 10.0 | 12.74 | 16.42 | Au1rxx-base64 | 156.146.38.170 |
| 67.57 | vless | 405.7 | 818.7 | 18.39 | 0.0 | 9.26 | 9.47 | 16.42 | Au1rxx-base64 | 178.17.57.33 |
| 67.51 | vless | 354.6 | 949.5 | 19.57 | 0.0 | 2.05 | 9.47 | 16.42 | Au1rxx-base64 | 185.95.231.156 |
| 67.45 | vless | 268.6 | 630.0 | 21.56 | 0.0 | 0.0 | 9.47 | 16.42 | Au1rxx-base64 | 216.227.161.95 |
| 67.31 | shadowsocks | 324.5 | 662.4 | 20.27 | 0.0 | 10.0 | 12.74 | 16.42 | Au1rxx-base64 | 103.214.109.45 |
| 67.2 | vless | 387.7 | 803.7 | 18.8 | 0.0 | 7.56 | 9.47 | 16.42 | Au1rxx-base64 | 51.79.31.36 |
| 67.07 | http | 396.2 | 957.1 | 18.61 | 0.0 | 0.0 | 13.9 | 19.12 | ermaozi | 129.212.181.253 |
| 66.97 | shadowsocks | 257.6 | 700.0 | 21.81 | 0.0 | 0.0 | 12.74 | 16.42 | Au1rxx-base64 | 37.19.198.244 |
| 66.4 | shadowsocks | 268.1 | 724.5 | 21.57 | 0.0 | 4.49 | 12.74 | 16.42 | Au1rxx-base64 | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.979 | 0.963 | 80 | 703 | prefer |
| Au1rxx-base64 | 0.814 | 0.742 | 326 | 1830 | prefer |
| mheidari-all | 0.716 | 0.65 | 20 | 24005 | prefer |
| Surfboard-tg-mixed | 0.391 | 1.0 | 2 | 7139 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5089 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 5147 | observe |
| Epodonios-all | 0.255 | None | 0 | 7652 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10113 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5693 | observe |
| barry-far-vless | 0.255 | None | 0 | 5924 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4338 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.248 | None | 0 | 1830 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 58 |
| speed | ClientOSError | - | 14 |
| cn-block | ClientOSError | - | 5 |
| 204 | ProxyError | - | 5 |
| geo | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| cn-block | TimeoutError | - | 2 |
| 204 | TimeoutError | - | 2 |
| speed | TimeoutError | - | 2 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 100 | 95 | - |
| global | False | 104 | 102 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
