# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-23 16:49:03 |
| 运行耗时 | 424.5s |
| 订阅源总数 | 108 |
| 健康订阅源 | 93 |
| 原始节点 | 140766 |
| 去重后节点 | 58341 |
| TCP 可达 | 3000 |
| 真实可用 | 67 |
| Verified 输出 | 67 |
| Global 输出 | 67 |
| All 输出 | 58341 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.8 |
| geo | 1.7 |
| tcp | 203.4 |
| probe | 128.4 |
| real_test | 32.0 |
| china_check | 19.5 |
| write_verified | 0.0 |
| generate | 29.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 81535 |
| vmess | 22221 |
| shadowsocks | 17726 |
| trojan | 16222 |
| hysteria2 | 1986 |
| shadowsocksr | 391 |
| tuic | 254 |
| http | 220 |
| socks | 125 |
| hysteria | 46 |
| anytls | 40 |

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
| 78.08 | shadowsocks | 256.4 | 671.0 | 21.84 | 0.0 | 7.32 | 13.76 | 19.16 | dragon | 37.19.198.244 |
| 78.01 | shadowsocks | 261.1 | 682.9 | 21.73 | 0.0 | 7.36 | 13.76 | 19.16 | dragon | 37.19.198.160 |
| 76.95 | hysteria2 | 254.4 | 684.1 | 21.89 | 0.0 | 7.52 | 13.0 | 19.16 | dragon | 129.213.91.185 |
| 76.38 | shadowsocks | 305.1 | 773.2 | 20.72 | 0.0 | 7.24 | 13.76 | 19.16 | dragon | 193.151.163.18 |
| 76.26 | shadowsocks | 313.3 | 840.4 | 20.52 | 0.0 | 7.32 | 13.76 | 19.16 | dragon | 185.230.230.18 |
| 75.69 | shadowsocks | 337.8 | 936.1 | 19.96 | 0.0 | 7.31 | 13.76 | 19.16 | dragon | 45.86.51.18 |
| 75.43 | shadowsocks | 345.1 | 938.6 | 19.79 | 0.0 | 7.22 | 13.76 | 19.16 | dragon | 185.215.132.18 |
| 75.37 | shadowsocks | 275.2 | 623.4 | 21.41 | 0.0 | 7.25 | 13.76 | 19.16 | dragon | 156.146.38.170 |
| 74.72 | shadowsocks | 279.0 | 635.8 | 21.32 | 0.0 | 7.06 | 13.76 | 19.16 | dragon | 156.146.38.167 |
| 73.97 | shadowsocks | 384.0 | 982.5 | 18.89 | 0.0 | 7.07 | 13.76 | 19.16 | dragon | 193.151.160.9 |
| 73.79 | shadowsocks | 279.1 | 721.8 | 21.32 | 0.0 | 8.55 | 13.76 | 19.16 | dragon | 216.9.225.189 |
| 73.24 | shadowsocks | 265.5 | 713.5 | 21.63 | 0.0 | 7.16 | 13.76 | 19.16 | dragon | 37.19.198.243 |
| 71.85 | shadowsocks | 282.2 | 646.1 | 21.25 | 0.0 | 6.92 | 13.76 | 19.16 | dragon | 156.146.38.168 |
| 70.8 | shadowsocks | 314.2 | 608.2 | 20.5 | 0.0 | 7.05 | 13.76 | 19.16 | dragon | 95.215.201.18 |
| 69.9 | shadowsocks | 337.6 | 678.5 | 19.96 | 0.0 | 6.92 | 13.76 | 19.16 | dragon | 173.244.56.9 |
| 69.71 | shadowsocks | 332.4 | 616.0 | 20.08 | 0.0 | 6.75 | 13.76 | 19.16 | dragon | 173.244.56.6 |
| 68.71 | shadowsocks | 306.2 | 675.1 | 20.69 | 0.0 | 3.55 | 13.76 | 19.16 | dragon | 156.146.38.169 |
| 65.26 | shadowsocks | 501.6 | 1043.9 | 16.17 | 0.0 | 6.51 | 13.76 | 19.16 | dragon | 149.102.132.184 |
| 64.92 | shadowsocks | 537.5 | 1092.8 | 15.33 | 0.0 | 8.23 | 13.76 | 19.16 | dragon | 82.38.31.11 |
| 64.42 | hysteria2 | 364.8 | 702.7 | 19.33 | 0.0 | 0.0 | 13.0 | 19.16 | dragon | 62.210.124.146 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.872 | 0.795 | 171 | 45037 | prefer |
| ermaozi | 0.781 | 0.778 | 27 | 555 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4911 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3871 | observe |
| Epodonios-all | 0.255 | None | 0 | 7353 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10120 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 6855 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5326 | observe |
| barry-far-vless | 0.255 | None | 0 | 5545 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4230 | observe |
| mheidari-all | 0.255 | None | 0 | 23793 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.239 | None | 0 | 1588 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 27 |
| cn-block | ProxyError | - | 6 |
| 204 | ClientOSError | - | 5 |
| 204 | ProxyError | - | 2 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 108 | 67 | - |
| global | False | 110 | 67 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
