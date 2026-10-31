# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-31 04:45:36 |
| 运行耗时 | 364.2s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 125511 |
| 去重后节点 | 58450 |
| TCP 可达 | 3000 |
| 真实可用 | 133 |
| Verified 输出 | 133 |
| Global 输出 | 133 |
| All 输出 | 58450 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.0 |
| geo | 1.5 |
| tcp | 204.1 |
| probe | 70.1 |
| real_test | 35.1 |
| china_check | 29.7 |
| write_verified | 0.0 |
| generate | 18.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 76419 |
| vmess | 18291 |
| trojan | 15383 |
| shadowsocks | 12443 |
| hysteria2 | 2235 |
| shadowsocksr | 263 |
| http | 257 |
| socks | 97 |
| tuic | 54 |
| hysteria | 41 |
| anytls | 28 |

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
| 73.78 | trojan | 340.0 | 298.6 | 19.91 | 3.8 | 6.18 | 13.37 | 19.1 | dragon | 125.227.86.45 |
| 72.7 | trojan | 259.8 | 617.9 | 21.76 | 0.0 | 1.47 | 13.37 | 19.1 | dragon | 66.163.114.45 |
| 72.26 | trojan | 363.0 | 980.0 | 19.38 | 0.0 | 6.41 | 13.37 | 19.1 | dragon | 66.23.203.21 |
| 71.53 | trojan | 334.0 | 671.3 | 20.05 | 0.0 | 6.53 | 13.37 | 19.1 | dragon | 216.106.186.33 |
| 71.22 | http | 358.4 | 969.7 | 19.48 | 0.0 | 0.0 | 14.48 | 19.76 | ermaozi | 23.133.176.14 |
| 71.18 | trojan | 267.4 | 589.2 | 21.59 | 0.0 | 6.86 | 13.37 | 19.1 | dragon | 66.163.112.142 |
| 70.67 | trojan | 342.7 | 728.9 | 19.84 | 0.0 | 8.49 | 13.37 | 19.1 | dragon | 167.88.61.20 |
| 70.44 | trojan | 346.6 | 726.8 | 19.75 | 0.0 | 8.36 | 13.37 | 19.1 | dragon | 66.163.122.25 |
| 70.18 | trojan | 268.0 | 557.8 | 21.57 | 0.0 | 3.09 | 13.37 | 19.1 | dragon | 66.163.112.242 |
| 69.96 | trojan | 359.7 | 695.6 | 19.45 | 0.0 | 8.42 | 13.37 | 19.1 | dragon | 66.163.122.113 |
| 69.77 | http | 369.5 | 709.6 | 19.22 | 0.0 | 0.0 | 14.48 | 19.76 | ermaozi | 172.64.68.89 |
| 69.69 | hysteria2 | 347.3 | 612.9 | 19.74 | 0.0 | 0.0 | 12.35 | 19.1 | dragon | 129.213.91.185 |
| 67.27 | http | 432.9 | 1165.0 | 17.76 | 0.0 | 0.0 | 14.48 | 19.76 | ermaozi | 38.247.141.135 |
| 66.99 | trojan | 371.2 | 789.7 | 19.19 | 0.0 | 2.79 | 13.37 | 19.1 | dragon | 216.106.186.32 |
| 66.82 | trojan | 321.0 | 744.2 | 20.35 | 0.0 | 0.84 | 13.37 | 19.1 | dragon | 169.197.140.169 |
| 66.29 | trojan | 327.8 | 754.9 | 20.19 | 0.0 | 1.6 | 13.37 | 19.1 | dragon | 169.197.140.245 |
| 66.26 | shadowsocks | 418.2 | 1000.1 | 18.1 | 0.0 | 5.79 | 11.25 | 19.1 | dragon | 15.204.233.41 |
| 66.19 | trojan | 404.4 | 521.3 | 18.42 | 0.0 | 4.92 | 13.37 | 19.1 | dragon | 151.101.36.120 |
| 65.63 | hysteria2 | 217.0 | 501.6 | 22.75 | 0.0 | 2.88 | 12.35 | 19.1 | dragon | 179.255.103.55 |
| 65.42 | trojan | 304.9 | 698.3 | 20.72 | 0.0 | 0.56 | 13.37 | 19.1 | dragon | 66.163.112.31 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.982 | 0.908 | 120 | 44960 | prefer |
| ermaozi | 0.971 | 0.956 | 91 | 622 | prefer |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4960 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2724 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10522 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7827 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5680 | observe |
| barry-far-vless | 0.255 | None | 0 | 5895 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4459 | observe |
| mheidari-all | 0.255 | None | 0 | 14594 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 9 |
| 204 | ClientOSError | - | 1 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:45552: bind: address already in use | - | 1 |
| geo | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |
| speed | TimeoutError | - | 1 |
| speed | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 89 | 133 | - |
| global | False | 90 | 133 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
