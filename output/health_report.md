# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-23 21:16:06 |
| 运行耗时 | 412.2s |
| 订阅源总数 | 108 |
| 健康订阅源 | 91 |
| 原始节点 | 138420 |
| 去重后节点 | 58550 |
| TCP 可达 | 3000 |
| 真实可用 | 67 |
| Verified 输出 | 67 |
| Global 输出 | 69 |
| All 输出 | 58550 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.6 |
| geo | 1.6 |
| tcp | 196.7 |
| probe | 116.7 |
| real_test | 50.4 |
| china_check | 21.9 |
| write_verified | 0.0 |
| generate | 18.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 85216 |
| vmess | 20724 |
| shadowsocks | 16255 |
| trojan | 13538 |
| hysteria2 | 1957 |
| shadowsocksr | 262 |
| http | 201 |
| socks | 143 |
| hysteria | 47 |
| tuic | 43 |
| anytls | 34 |

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
| 76.06 | shadowsocks | 320.8 | 839.8 | 20.35 | 0.0 | 10.0 | 12.27 | 17.44 | dragon | 156.146.38.167 |
| 74.69 | hysteria2 | 329.1 | 856.3 | 20.16 | 0.0 | 5.73 | 12.86 | 17.44 | dragon | 129.213.91.185 |
| 74.63 | shadowsocks | 340.3 | 816.4 | 19.9 | 0.0 | 10.0 | 12.27 | 17.44 | dragon | 37.19.198.160 |
| 74.62 | shadowsocks | 325.0 | 733.8 | 20.25 | 0.0 | 10.0 | 12.27 | 17.44 | dragon | 185.230.230.18 |
| 74.24 | shadowsocks | 327.9 | 810.9 | 20.19 | 0.0 | 9.47 | 12.27 | 17.44 | dragon | 37.19.198.244 |
| 74.12 | shadowsocks | 338.3 | 838.9 | 19.95 | 0.0 | 10.0 | 12.27 | 17.44 | dragon | 156.146.38.169 |
| 74.0 | shadowsocks | 362.0 | 910.4 | 19.4 | 0.0 | 10.0 | 12.27 | 17.44 | dragon | 185.215.132.18 |
| 73.9 | shadowsocks | 327.8 | 833.0 | 20.19 | 0.0 | 10.0 | 12.27 | 17.44 | dragon | 156.146.38.168 |
| 73.41 | shadowsocks | 339.6 | 782.7 | 19.92 | 0.0 | 10.0 | 12.27 | 17.44 | dragon | 193.151.163.18 |
| 72.76 | shadowsocks | 394.1 | 965.5 | 18.65 | 0.0 | 10.0 | 12.27 | 17.44 | dragon | 185.215.132.9 |
| 71.18 | shadowsocks | 382.4 | 929.1 | 18.93 | 0.0 | 10.0 | 12.27 | 17.44 | dragon | 45.86.51.18 |
| 71.15 | shadowsocks | 490.5 | 1286.5 | 16.42 | 0.0 | 9.45 | 12.27 | 17.44 | dragon | 37.19.198.243 |
| 70.39 | shadowsocks | 431.7 | 1058.3 | 17.78 | 0.0 | 10.0 | 12.27 | 17.44 | dragon | 193.151.160.18 |
| 70.25 | shadowsocks | 305.8 | 593.2 | 20.7 | 0.0 | 9.83 | 12.27 | 17.44 | dragon | 173.244.56.9 |
| 70.18 | shadowsocks | 328.8 | 609.1 | 20.17 | 0.0 | 9.98 | 12.27 | 17.44 | dragon | 173.244.56.6 |
| 69.67 | shadowsocks | 420.3 | 1029.3 | 18.05 | 0.0 | 10.0 | 12.27 | 17.44 | dragon | 193.151.160.9 |
| 69.15 | shadowsocks | 347.9 | 832.2 | 19.73 | 0.0 | 9.48 | 12.27 | 17.44 | dragon | 37.19.198.236 |
| 67.67 | hysteria2 | 527.8 | 692.0 | 15.56 | 0.0 | 9.64 | 12.86 | 17.44 | dragon | 130.49.161.70 |
| 67.5 | shadowsocks | 258.8 | 641.4 | 21.79 | 0.0 | 0.0 | 12.27 | 17.44 | dragon | 156.146.38.170 |
| 66.15 | shadowsocks | 334.3 | 324.7 | 20.04 | 2.82 | 8.32 | 12.27 | 17.44 | dragon | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.997 | 1.0 | 38 | 555 | prefer |
| dragon | 0.95 | 0.874 | 175 | 45691 | prefer |
| tg-oneclickvpnkeys | 0.272 | 0.667 | 3 | 92 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4911 | observe |
| Epodonios-all | 0.255 | None | 0 | 7680 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10312 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7184 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5437 | observe |
| barry-far-vless | 0.255 | None | 0 | 5798 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4117 | observe |
| mheidari-all | 0.255 | None | 0 | 23638 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.238 | None | 0 | 1565 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 12 |
| 204 | ProxyError | - | 4 |
| 204 | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| cn-block | TimeoutError | - | 2 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 67 | 67 | - |
| global | False | 67 | 69 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
