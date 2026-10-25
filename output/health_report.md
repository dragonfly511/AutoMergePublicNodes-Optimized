# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-25 15:53:15 |
| 运行耗时 | 452.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 144083 |
| 去重后节点 | 60371 |
| TCP 可达 | 3000 |
| 真实可用 | 63 |
| Verified 输出 | 63 |
| Global 输出 | 63 |
| All 输出 | 60371 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| geo | 1.8 |
| tcp | 216.9 |
| probe | 128.5 |
| real_test | 41.0 |
| china_check | 24.9 |
| write_verified | 0.0 |
| generate | 30.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 86924 |
| vmess | 21468 |
| shadowsocks | 17620 |
| trojan | 15246 |
| hysteria2 | 1999 |
| http | 275 |
| shadowsocksr | 270 |
| socks | 150 |
| hysteria | 47 |
| tuic | 43 |
| anytls | 41 |

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
| 72.54 | http | 262.1 | 646.3 | 21.71 | 0.0 | 0.0 | 14.19 | 19.24 | ermaozi | 44.248.167.117 |
| 71.37 | trojan | 210.0 | 532.8 | 22.92 | 0.0 | 6.28 | 8.75 | 17.92 | dragon | 216.106.186.32 |
| 65.88 | http | 398.1 | 962.1 | 18.56 | 0.0 | 0.0 | 14.19 | 19.24 | ermaozi | 138.199.35.214 |
| 65.73 | trojan | 458.4 | 603.8 | 17.17 | 0.0 | 6.39 | 8.75 | 17.92 | dragon | 216.106.186.33 |
| 64.95 | hysteria2 | 453.9 | 678.1 | 17.27 | 0.0 | 4.72 | 13.24 | 17.92 | dragon | 152.67.115.203 |
| 63.87 | shadowsocks | 280.2 | 566.7 | 21.29 | 0.0 | 0.0 | 12.5 | 17.92 | dragon | 173.244.56.9 |
| 63.33 | http | 316.7 | 649.4 | 20.45 | 0.0 | 0.0 | 14.19 | 19.24 | ermaozi | 64.98.50.100 |
| 63.18 | http | 454.5 | 1020.4 | 17.26 | 0.0 | 0.0 | 14.19 | 19.24 | ermaozi | 38.247.141.135 |
| 62.45 | shadowsocks | 316.9 | 652.2 | 20.44 | 0.0 | 0.0 | 12.5 | 17.92 | dragon | 156.146.38.168 |
| 62.41 | shadowsocks | 320.1 | 693.3 | 20.37 | 0.0 | 0.0 | 12.5 | 17.92 | dragon | 156.146.38.170 |
| 62.37 | shadowsocks | 317.0 | 688.2 | 20.44 | 0.0 | 0.0 | 12.5 | 17.92 | dragon | 156.146.38.167 |
| 62.16 | hysteria2 | 548.5 | 967.9 | 15.08 | 0.0 | 4.82 | 13.24 | 17.92 | dragon | 64.188.98.171 |
| 62.07 | shadowsocks | 370.9 | 872.1 | 19.19 | 0.0 | 0.0 | 12.5 | 17.92 | dragon | 95.215.201.18 |
| 61.98 | hysteria2 | 451.7 | 763.2 | 17.32 | 0.0 | 4.84 | 13.24 | 17.92 | dragon | 62.210.124.146 |
| 61.88 | hysteria2 | 580.8 | 1024.9 | 14.33 | 0.0 | 4.73 | 13.24 | 17.92 | dragon | 2.26.3.75 |
| 61.4 | shadowsocks | 261.7 | 262.0 | 21.72 | 5.17 | 0.0 | 12.5 | 17.92 | dragon | 149.22.87.241 |
| 60.55 | http | 784.3 | 2275.0 | 9.62 | 0.0 | 0.0 | 14.19 | 19.24 | ermaozi | 45.63.38.134 |
| 60.14 | shadowsocks | 377.7 | 771.8 | 19.03 | 0.0 | 0.0 | 12.5 | 17.92 | dragon | 37.19.198.160 |
| 60.09 | shadowsocks | 371.9 | 772.6 | 19.17 | 0.0 | 0.0 | 12.5 | 17.92 | dragon | 185.230.230.18 |
| 60.09 | shadowsocks | 372.1 | 776.7 | 19.16 | 0.0 | 0.0 | 12.5 | 17.92 | dragon | 216.9.225.189 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.941 | 0.865 | 163 | 46036 | prefer |
| ermaozi | 0.757 | 0.742 | 62 | 575 | prefer |
| Au1rxx-base64 | 0.378 | 1.0 | 2 | 1658 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3849 | observe |
| Epodonios-all | 0.255 | None | 0 | 7729 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10617 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7560 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5715 | observe |
| barry-far-vless | 0.255 | None | 0 | 5694 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4186 | observe |
| mheidari-all | 0.255 | None | 0 | 24301 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 16 |
| 204 | ProxyError | - | 11 |
| 204 | ClientOSError | - | 5 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |
| cn-block | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 99 | 63 | - |
| global | False | 100 | 63 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
