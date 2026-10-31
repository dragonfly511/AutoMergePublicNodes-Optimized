# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-31 21:18:15 |
| 运行耗时 | 441.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 125151 |
| 去重后节点 | 57788 |
| TCP 可达 | 3000 |
| 真实可用 | 55 |
| Verified 输出 | 55 |
| Global 输出 | 58 |
| All 输出 | 57788 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.2 |
| geo | 1.7 |
| tcp | 197.8 |
| probe | 114.8 |
| real_test | 45.5 |
| china_check | 46.2 |
| write_verified | 0.0 |
| generate | 27.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 75019 |
| vmess | 18125 |
| trojan | 16866 |
| shadowsocks | 12117 |
| hysteria2 | 2163 |
| shadowsocksr | 298 |
| tuic | 264 |
| http | 162 |
| socks | 75 |
| hysteria | 42 |
| anytls | 20 |

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
| 74.31 | trojan | 237.5 | 581.9 | 22.28 | 0.0 | 6.56 | 11.25 | 16.72 | dragon | 216.106.186.33 |
| 71.22 | trojan | 321.0 | 783.6 | 20.35 | 0.0 | 9.46 | 11.25 | 16.72 | dragon | 66.163.114.114 |
| 69.11 | trojan | 349.1 | 614.4 | 19.7 | 0.0 | 9.46 | 11.25 | 16.72 | dragon | 66.163.112.121 |
| 67.87 | trojan | 359.0 | 769.6 | 19.47 | 0.0 | 9.04 | 11.25 | 16.72 | dragon | 216.152.155.23 |
| 66.8 | trojan | 389.2 | 781.1 | 18.77 | 0.0 | 8.92 | 11.25 | 16.72 | dragon | 216.152.156.65 |
| 66.68 | shadowsocks | 229.9 | 540.8 | 22.46 | 0.0 | 0.0 | 12.0 | 16.72 | dragon | 95.215.201.18 |
| 66.67 | trojan | 362.7 | 664.5 | 19.38 | 0.0 | 9.06 | 11.25 | 16.72 | dragon | 216.152.155.176 |
| 65.8 | trojan | 450.5 | 791.7 | 17.35 | 0.0 | 8.85 | 11.25 | 16.72 | dragon | 169.197.140.169 |
| 65.47 | trojan | 393.1 | 783.1 | 18.68 | 0.0 | 8.88 | 11.25 | 16.72 | dragon | 216.152.156.212 |
| 65.38 | shadowsocks | 350.4 | 729.8 | 19.67 | 0.0 | 6.31 | 12.0 | 16.72 | dragon | 185.215.132.9 |
| 64.9 | trojan | 298.4 | 705.7 | 20.87 | 0.0 | 9.45 | 11.25 | 16.72 | dragon | 66.163.114.132 |
| 64.77 | trojan | 385.2 | 751.6 | 18.86 | 0.0 | 8.91 | 11.25 | 16.72 | dragon | 216.152.156.42 |
| 64.64 | hysteria2 | 332.8 | 722.5 | 20.07 | 0.0 | 6.67 | 10.71 | 16.72 | dragon | 129.213.91.185 |
| 63.82 | shadowsocks | 350.6 | 734.0 | 19.66 | 0.0 | 6.31 | 12.0 | 16.72 | dragon | 185.215.132.18 |
| 63.81 | trojan | 403.8 | 726.8 | 18.43 | 0.0 | 9.04 | 11.25 | 16.72 | dragon | 216.152.155.54 |
| 63.48 | shadowsocks | 273.4 | 282.3 | 21.45 | 4.42 | 0.0 | 12.0 | 16.72 | dragon | 149.22.87.240 |
| 63.24 | trojan | 365.1 | 923.4 | 19.33 | 0.0 | 9.46 | 11.25 | 16.72 | dragon | 66.163.112.13 |
| 63.06 | shadowsocks | 289.8 | 646.6 | 21.07 | 0.0 | 0.0 | 12.0 | 16.72 | dragon | 156.146.38.167 |
| 62.77 | hysteria2 | 187.2 | 493.2 | 23.44 | 0.0 | 1.5 | 10.71 | 16.72 | dragon | 179.255.103.55 |
| 62.65 | trojan | 369.1 | 738.3 | 19.23 | 0.0 | 8.43 | 11.25 | 16.72 | dragon | 170.101.101.67 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.91 | 0.833 | 228 | 44351 | prefer |
| zhangkai | 0.723 | 1.0 | 13 | 43 | prefer |
| ermaozi-get_subscribe | 0.271 | 1.0 | 1 | 412 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4970 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2848 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10505 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7936 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5636 | observe |
| barry-far-vless | 0.255 | None | 0 | 5849 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4635 | observe |
| mheidari-all | 0.255 | None | 0 | 14850 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 27 |
| 204 | ProxyError | - | 5 |
| 204 | ClientOSError | - | 3 |
| cn-block | TimeoutError | - | 2 |
| cn-block | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 45 | 55 | - |
| global | False | 46 | 58 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
