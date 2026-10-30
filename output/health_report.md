# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-30 12:28:12 |
| 运行耗时 | 348.4s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 144804 |
| 去重后节点 | 59386 |
| TCP 可达 | 3000 |
| 真实可用 | 63 |
| Verified 输出 | 63 |
| Global 输出 | 64 |
| All 输出 | 59386 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.3 |
| geo | 1.5 |
| tcp | 205.2 |
| probe | 68.3 |
| real_test | 30.6 |
| china_check | 20.1 |
| write_verified | 0.0 |
| generate | 17.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 89577 |
| vmess | 19044 |
| trojan | 18158 |
| shadowsocks | 14609 |
| hysteria2 | 2830 |
| shadowsocksr | 270 |
| http | 106 |
| socks | 89 |
| tuic | 51 |
| hysteria | 40 |
| anytls | 30 |

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
| 81.52 | shadowsocks | 245.2 | 639.8 | 22.1 | 0.0 | 9.89 | 13.73 | 19.8 | dragon | 156.146.38.167 |
| 81.48 | shadowsocks | 249.5 | 629.5 | 22.0 | 0.0 | 9.95 | 13.73 | 19.8 | dragon | 156.146.38.170 |
| 80.12 | trojan | 268.7 | 607.0 | 21.56 | 0.0 | 9.33 | 13.93 | 19.8 | dragon | 66.163.114.45 |
| 79.73 | shadowsocks | 315.1 | 780.4 | 20.48 | 0.0 | 9.72 | 13.73 | 19.8 | dragon | 37.19.198.243 |
| 79.46 | shadowsocks | 244.3 | 611.0 | 22.12 | 0.0 | 9.81 | 13.73 | 19.8 | dragon | 156.146.38.169 |
| 79.41 | trojan | 256.6 | 604.7 | 21.84 | 0.0 | 8.34 | 13.93 | 19.8 | dragon | 66.163.114.126 |
| 79.29 | trojan | 294.1 | 673.5 | 20.97 | 0.0 | 10.0 | 13.93 | 19.8 | dragon | 216.152.156.65 |
| 79.17 | shadowsocks | 285.1 | 686.2 | 21.18 | 0.0 | 9.78 | 13.73 | 19.8 | dragon | 185.215.132.18 |
| 79.04 | shadowsocks | 288.9 | 688.3 | 21.09 | 0.0 | 9.82 | 13.73 | 19.8 | dragon | 185.215.132.9 |
| 78.52 | shadowsocks | 304.8 | 727.8 | 20.72 | 0.0 | 9.44 | 13.73 | 19.8 | dragon | 45.86.51.18 |
| 78.39 | shadowsocks | 295.2 | 707.9 | 20.94 | 0.0 | 9.63 | 13.73 | 19.8 | dragon | 37.19.198.160 |
| 77.74 | shadowsocks | 319.0 | 790.7 | 20.39 | 0.0 | 9.69 | 13.73 | 19.8 | dragon | 37.19.198.244 |
| 77.15 | shadowsocks | 309.2 | 726.0 | 20.62 | 0.0 | 9.44 | 13.73 | 19.8 | dragon | 185.230.230.18 |
| 77.0 | shadowsocks | 316.0 | 700.8 | 20.46 | 0.0 | 9.45 | 13.73 | 19.8 | dragon | 193.151.163.18 |
| 76.62 | shadowsocks | 283.3 | 569.5 | 21.22 | 0.0 | 9.77 | 13.73 | 19.8 | dragon | 95.215.201.18 |
| 76.29 | shadowsocks | 300.9 | 617.6 | 20.81 | 0.0 | 9.77 | 13.73 | 19.8 | dragon | 173.244.56.6 |
| 76.27 | shadowsocks | 251.3 | 631.7 | 21.96 | 0.0 | 9.78 | 13.73 | 19.8 | dragon | 156.146.38.168 |
| 76.11 | shadowsocks | 325.6 | 738.1 | 20.24 | 0.0 | 9.72 | 13.73 | 19.8 | dragon | 193.151.160.18 |
| 76.09 | trojan | 359.6 | 792.4 | 19.45 | 0.0 | 9.41 | 13.93 | 19.8 | dragon | 216.106.186.33 |
| 75.9 | shadowsocks | 289.0 | 580.8 | 21.09 | 0.0 | 9.8 | 13.73 | 19.8 | dragon | 173.244.56.9 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.936 | 0.862 | 116 | 44588 | prefer |
| ermaozi | 0.922 | 0.929 | 28 | 550 | prefer |
| tg-oneclickvpnkeys | 0.314 | 1.0 | 2 | 70 | observe |
| ermaozi-get_subscribe | 0.271 | 1.0 | 1 | 390 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4960 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2724 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10521 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7902 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5822 | observe |
| barry-far-vless | 0.255 | None | 0 | 5942 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4445 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 9 |
| 204 | TimeoutError | - | 5 |
| 204 | ClientOSError | - | 2 |
| 204 | ProxyError | - | 1 |
| cn-block | status | 530 | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 70 | 63 | - |
| global | False | 70 | 64 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
