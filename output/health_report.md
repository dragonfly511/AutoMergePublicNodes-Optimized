# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-08 13:04:03 |
| 运行耗时 | 430.0s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 127282 |
| 去重后节点 | 59317 |
| TCP 可达 | 3000 |
| 真实可用 | 79 |
| Verified 输出 | 79 |
| Global 输出 | 81 |
| All 输出 | 59317 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.6 |
| geo | 1.7 |
| tcp | 198.1 |
| probe | 115.2 |
| real_test | 44.2 |
| china_check | 31.7 |
| write_verified | 0.0 |
| generate | 30.5 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77490 |
| vmess | 18335 |
| trojan | 14843 |
| shadowsocks | 13401 |
| hysteria2 | 2329 |
| shadowsocksr | 376 |
| http | 252 |
| socks | 120 |
| hysteria | 57 |
| tuic | 45 |
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
| 83.65 | trojan | 176.4 | 473.3 | 23.69 | 0.0 | 10.0 | 13.46 | 20.0 | dragon | 167.88.61.52 |
| 82.96 | trojan | 249.5 | 597.2 | 22.0 | 0.0 | 10.0 | 13.46 | 20.0 | dragon | 216.106.186.66 |
| 82.55 | shadowsocks | 235.3 | 556.7 | 22.33 | 0.0 | 10.0 | 14.22 | 20.0 | dragon | 173.244.56.6 |
| 82.38 | trojan | 264.8 | 602.6 | 21.65 | 0.0 | 10.0 | 13.46 | 20.0 | dragon | 66.163.114.245 |
| 82.33 | shadowsocks | 223.0 | 633.2 | 22.61 | 0.0 | 10.0 | 14.22 | 20.0 | dragon | 137.184.89.151 |
| 82.0 | trojan | 235.8 | 546.3 | 22.32 | 0.0 | 8.72 | 13.46 | 20.0 | dragon | 66.163.112.142 |
| 81.95 | trojan | 238.0 | 549.0 | 22.27 | 0.0 | 8.72 | 13.46 | 20.0 | dragon | 66.163.112.31 |
| 81.95 | trojan | 238.1 | 545.8 | 22.27 | 0.0 | 8.72 | 13.46 | 20.0 | dragon | 66.163.112.242 |
| 81.94 | shadowsocks | 240.1 | 673.1 | 22.22 | 0.0 | 10.0 | 14.22 | 20.0 | dragon | 169.197.142.68 |
| 81.91 | trojan | 238.5 | 547.1 | 22.26 | 0.0 | 8.72 | 13.46 | 20.0 | dragon | 66.163.112.171 |
| 81.74 | trojan | 172.6 | 468.0 | 23.78 | 0.0 | 10.0 | 13.46 | 20.0 | dragon | 167.88.61.175 |
| 81.74 | trojan | 244.4 | 556.1 | 22.12 | 0.0 | 8.72 | 13.46 | 20.0 | dragon | 66.163.112.76 |
| 81.5 | trojan | 257.4 | 523.5 | 21.82 | 0.0 | 8.72 | 13.46 | 20.0 | dragon | 66.163.112.147 |
| 81.21 | trojan | 175.1 | 478.4 | 23.73 | 0.0 | 9.44 | 13.46 | 20.0 | dragon | 167.88.61.193 |
| 81.14 | shadowsocks | 274.5 | 682.1 | 21.42 | 0.0 | 10.0 | 14.22 | 20.0 | dragon | 23.150.152.38 |
| 81.02 | trojan | 248.2 | 576.8 | 22.03 | 0.0 | 8.72 | 13.46 | 20.0 | dragon | 66.163.112.121 |
| 80.32 | trojan | 243.5 | 590.9 | 22.14 | 0.0 | 9.22 | 13.46 | 20.0 | dragon | 216.106.186.46 |
| 79.91 | trojan | 238.8 | 548.2 | 22.25 | 0.0 | 8.72 | 13.46 | 20.0 | dragon | 66.163.112.13 |
| 79.5 | trojan | 271.0 | 598.8 | 21.5 | 0.0 | 9.16 | 13.46 | 20.0 | dragon | 66.163.114.132 |
| 78.45 | shadowsocks | 278.1 | 682.3 | 21.34 | 0.0 | 10.0 | 14.22 | 20.0 | dragon | 149.22.95.183 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.956 | 0.879 | 281 | 45338 | prefer |
| ermaozi | 0.923 | 0.929 | 28 | 586 | prefer |
| mheidari-all | 0.391 | 1.0 | 2 | 14505 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5035 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3024 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10990 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8136 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5786 | observe |
| barry-far-vless | 0.255 | None | 0 | 5999 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4635 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 22 |
| 204 | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 2 |
| geo | ProxyError | - | 2 |
| cn-block | TimeoutError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 86 | 79 | - |
| global | False | 86 | 81 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
