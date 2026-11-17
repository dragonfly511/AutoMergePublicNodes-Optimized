# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-17 01:49:58 |
| 运行耗时 | 371.9s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 127540 |
| 去重后节点 | 58452 |
| TCP 可达 | 3000 |
| 真实可用 | 91 |
| Verified 输出 | 91 |
| Global 输出 | 92 |
| All 输出 | 58452 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.8 |
| geo | 1.5 |
| tcp | 172.6 |
| probe | 92.9 |
| real_test | 48.7 |
| china_check | 31.7 |
| write_verified | 0.0 |
| generate | 18.7 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 78242 |
| vmess | 18508 |
| trojan | 13996 |
| shadowsocks | 13741 |
| hysteria2 | 2102 |
| shadowsocksr | 424 |
| http | 256 |
| socks | 123 |
| tuic | 56 |
| hysteria | 56 |
| anytls | 36 |

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
| 73.13 | hysteria2 | 199.4 | 535.3 | 23.16 | 0.0 | 4.13 | 13.0 | 13.84 | dragon | 66.94.121.46 |
| 71.59 | http | 200.8 | 510.7 | 23.13 | 0.0 | 0.0 | 13.12 | 17.94 | ermaozi | 44.248.167.117 |
| 70.98 | shadowsocks | 198.8 | 482.2 | 23.18 | 0.0 | 8.12 | 10.34 | 13.84 | dragon | 137.184.89.151 |
| 69.36 | shadowsocks | 223.8 | 531.6 | 22.6 | 0.0 | 6.8 | 10.34 | 13.84 | dragon | 38.145.220.193 |
| 68.81 | hysteria2 | 267.9 | 259.9 | 21.58 | 5.25 | 7.75 | 13.0 | 13.84 | dragon | 8.209.247.109 |
| 68.27 | trojan | 281.3 | 593.8 | 21.27 | 0.0 | 10.0 | 8.33 | 13.84 | dragon | 66.163.112.121 |
| 68.16 | http | 247.4 | 533.3 | 22.05 | 0.0 | 0.0 | 13.12 | 17.94 | ermaozi | 38.95.111.226 |
| 68.03 | trojan | 287.2 | 605.7 | 21.13 | 0.0 | 10.0 | 8.33 | 13.84 | dragon | 66.163.112.13 |
| 67.56 | shadowsocks | 224.9 | 527.8 | 22.57 | 0.0 | 8.05 | 10.34 | 13.84 | dragon | 23.150.152.38 |
| 67.13 | shadowsocks | 238.1 | 513.2 | 22.27 | 0.0 | 7.95 | 10.34 | 13.84 | dragon | 169.197.142.68 |
| 66.34 | http | 216.1 | 543.1 | 22.78 | 0.0 | 0.0 | 13.12 | 17.94 | ermaozi | 172.64.69.89 |
| 66.08 | http | 306.5 | 697.5 | 20.68 | 0.0 | 0.0 | 13.12 | 17.94 | ermaozi | 138.199.35.216 |
| 65.87 | trojan | 206.0 | 556.1 | 23.01 | 0.0 | 8.19 | 8.33 | 13.84 | dragon | 216.106.186.66 |
| 65.83 | http | 318.7 | 727.4 | 20.4 | 0.0 | 0.0 | 13.12 | 17.94 | ermaozi | 138.199.35.199 |
| 65.76 | http | 314.1 | 715.6 | 20.51 | 0.0 | 0.0 | 13.12 | 17.94 | ermaozi | 138.199.35.198 |
| 65.48 | http | 318.9 | 732.6 | 20.4 | 0.0 | 0.0 | 13.12 | 17.94 | ermaozi | 138.199.35.203 |
| 65.31 | http | 328.0 | 728.2 | 20.19 | 0.0 | 0.0 | 13.12 | 17.94 | ermaozi | 138.199.35.220 |
| 65.18 | http | 312.1 | 722.1 | 20.55 | 0.0 | 0.0 | 13.12 | 17.94 | ermaozi | 138.199.35.205 |
| 64.91 | http | 307.4 | 689.9 | 20.66 | 0.0 | 0.0 | 13.12 | 17.94 | ermaozi | 138.199.35.212 |
| 64.57 | http | 348.1 | 825.8 | 19.72 | 0.0 | 0.0 | 13.12 | 17.94 | ermaozi | 138.199.35.204 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.98 | 0.902 | 307 | 44193 | prefer |
| ermaozi | 0.95 | 0.936 | 78 | 621 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 14735 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4964 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2915 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11573 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8623 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6028 | observe |
| barry-far-vless | 0.255 | None | 0 | 6209 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4545 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 19 |
| geo | ClientOSError | - | 5 |
| 204 | ProxyError | - | 3 |
| 204 | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| geo | ProxyError | - | 1 |
| speed | TimeoutError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 45 | 91 | - |
| global | False | 47 | 92 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
