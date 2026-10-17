# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-17 00:18:52 |
| 运行耗时 | 315.0s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99510 |
| 去重后节点 | 27670 |
| TCP 可达 | 3000 |
| 真实可用 | 86 |
| Verified 输出 | 86 |
| Global 输出 | 93 |
| All 输出 | 27670 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 4.7 |
| geo | 1.4 |
| tcp | 87.5 |
| probe | 92.7 |
| real_test | 88.6 |
| china_check | 32.1 |
| write_verified | 0.0 |
| generate | 8.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 58502 |
| vmess | 16619 |
| shadowsocks | 12003 |
| trojan | 10161 |
| hysteria2 | 1326 |
| http | 631 |
| shadowsocksr | 158 |
| socks | 58 |
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
| 74.45 | http | 199.6 | 515.1 | 23.16 | 0.0 | 0.0 | 14.29 | 20.0 | ermaozi | 138.199.35.216 |
| 74.39 | shadowsocks | 217.9 | 533.9 | 22.73 | 0.0 | 10.0 | 10.8 | 14.86 | Au1rxx-base64 | 173.244.56.6 |
| 74.32 | http | 205.2 | 532.4 | 23.03 | 0.0 | 0.0 | 14.29 | 20.0 | ermaozi | 138.199.35.198 |
| 74.01 | vless | 205.6 | 520.1 | 23.02 | 0.0 | 7.66 | 8.47 | 14.86 | Au1rxx-base64 | 154.29.159.211 |
| 73.9 | vless | 286.9 | 681.6 | 21.14 | 0.0 | 10.0 | 8.47 | 14.86 | Au1rxx-base64 | 147.45.60.160 |
| 73.79 | vless | 210.5 | 522.1 | 22.9 | 0.0 | 7.56 | 8.47 | 14.86 | Au1rxx-base64 | 154.9.241.170 |
| 72.82 | shadowsocks | 264.6 | 639.4 | 21.65 | 0.0 | 10.0 | 10.8 | 14.86 | Au1rxx-base64 | 156.146.38.168 |
| 72.62 | shadowsocks | 259.5 | 626.7 | 21.77 | 0.0 | 10.0 | 10.8 | 14.86 | Au1rxx-base64 | 156.146.38.167 |
| 72.37 | shadowsocks | 262.9 | 633.3 | 21.69 | 0.0 | 10.0 | 10.8 | 14.86 | Au1rxx-base64 | 156.146.38.169 |
| 72.3 | shadowsocks | 286.6 | 440.6 | 21.14 | 0.0 | 10.0 | 10.8 | 14.86 | Au1rxx-base64 | 103.11.76.248 |
| 72.02 | shadowsocks | 221.6 | 549.6 | 22.65 | 0.0 | 7.71 | 10.8 | 14.86 | Au1rxx-base64 | 173.244.56.9 |
| 70.43 | http | 351.5 | 413.4 | 19.64 | 0.0 | 0.0 | 14.29 | 20.0 | ermaozi | 148.135.10.80 |
| 69.63 | shadowsocks | 284.5 | 613.3 | 21.19 | 0.0 | 10.0 | 10.8 | 14.86 | Au1rxx-base64 | 149.22.95.183 |
| 69.12 | vless | 196.3 | 491.0 | 23.23 | 0.0 | 7.56 | 8.47 | 14.86 | Au1rxx-base64 | 45.63.53.81 |
| 68.97 | vless | 253.6 | 550.1 | 21.91 | 0.0 | 7.44 | 8.47 | 14.86 | Au1rxx-base64 | 23.95.222.127 |
| 68.33 | http | 430.0 | 833.5 | 17.82 | 0.0 | 0.0 | 14.29 | 20.0 | ermaozi | 167.88.60.242 |
| 67.53 | shadowsocks | 298.5 | 748.8 | 20.87 | 0.0 | 10.0 | 10.8 | 14.86 | Au1rxx-base64 | 156.146.38.170 |
| 66.94 | hysteria2 | 268.0 | 620.1 | 21.57 | 0.0 | 0.0 | 12.19 | 14.86 | Au1rxx-base64 | 66.94.121.46 |
| 66.81 | hysteria2 | 319.8 | 745.6 | 20.37 | 0.0 | 2.87 | 12.19 | 14.86 | Au1rxx-base64 | 129.213.91.185 |
| 66.35 | shadowsocks | 364.4 | 793.1 | 19.34 | 0.0 | 10.0 | 10.8 | 14.86 | Au1rxx-base64 | 37.19.198.243 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.992 | 0.983 | 59 | 618 | prefer |
| Au1rxx-base64 | 0.927 | 0.849 | 364 | 1995 | prefer |
| Surfboard-tg-mixed | 0.771 | 0.737 | 19 | 7187 | prefer |
| mheidari-all | 0.494 | 0.413 | 143 | 24025 | observe |
| tg-oneclickvpnkeys | 0.324 | 0.75 | 4 | 103 | observe |
| 10ium-HighSpeed | 0.289 | 1.0 | 1 | 839 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5024 | observe |
| Au1rxx-clash | 0.255 | None | 0 | 1995 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 4946 | observe |
| Epodonios-all | 0.255 | None | 0 | 7728 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9883 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5650 | observe |
| barry-far-vless | 0.255 | None | 0 | 5904 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4255 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 74 |
| speed | ClientOSError | - | 36 |
| geo | ClientOSError | - | 14 |
| cn-block | ClientOSError | - | 7 |
| 204 | TimeoutError | - | 5 |
| cn-block | ProxyError | - | 5 |
| speed | TimeoutError | - | 4 |
| geo | ProxyError | - | 1 |
| 204 | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 95 | 86 | - |
| global | False | 97 | 93 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
