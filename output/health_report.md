# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-29 12:37:53 |
| 运行耗时 | 427.5s |
| 订阅源总数 | 108 |
| 健康订阅源 | 88 |
| 原始节点 | 144498 |
| 去重后节点 | 59634 |
| TCP 可达 | 3000 |
| 真实可用 | 37 |
| Verified 输出 | 37 |
| Global 输出 | 40 |
| All 输出 | 59634 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.3 |
| geo | 1.7 |
| tcp | 199.9 |
| probe | 116.6 |
| real_test | 47.0 |
| china_check | 22.7 |
| write_verified | 0.0 |
| generate | 30.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 90778 |
| vmess | 18951 |
| trojan | 16954 |
| shadowsocks | 14193 |
| hysteria2 | 3018 |
| shadowsocksr | 249 |
| http | 148 |
| socks | 95 |
| tuic | 45 |
| hysteria | 35 |
| anytls | 32 |

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
| 75.76 | shadowsocks | 310.5 | 692.7 | 20.59 | 0.0 | 8.97 | 12.34 | 17.86 | dragon | 198.98.53.130 |
| 75.72 | shadowsocks | 244.5 | 675.0 | 22.12 | 0.0 | 7.4 | 12.34 | 17.86 | dragon | 37.19.198.236 |
| 75.65 | shadowsocks | 247.8 | 676.6 | 22.04 | 0.0 | 7.41 | 12.34 | 17.86 | dragon | 37.19.198.244 |
| 75.49 | shadowsocks | 254.2 | 677.9 | 21.89 | 0.0 | 7.4 | 12.34 | 17.86 | dragon | 37.19.198.160 |
| 75.41 | shadowsocks | 239.5 | 649.8 | 22.23 | 0.0 | 7.48 | 12.34 | 17.86 | dragon | 185.230.230.18 |
| 75.01 | shadowsocks | 253.5 | 659.8 | 21.91 | 0.0 | 7.4 | 12.34 | 17.86 | dragon | 193.151.163.18 |
| 74.43 | shadowsocks | 300.4 | 828.6 | 20.83 | 0.0 | 7.4 | 12.34 | 17.86 | dragon | 37.19.198.243 |
| 73.51 | shadowsocks | 321.9 | 870.9 | 20.33 | 0.0 | 7.48 | 12.34 | 17.86 | dragon | 45.86.51.18 |
| 73.04 | hysteria2 | 252.3 | 693.7 | 21.94 | 0.0 | 3.05 | 12.69 | 17.86 | dragon | 129.213.91.185 |
| 72.7 | shadowsocks | 278.4 | 639.3 | 21.33 | 0.0 | 7.3 | 12.34 | 17.86 | dragon | 156.146.38.168 |
| 72.08 | shadowsocks | 374.5 | 961.7 | 19.11 | 0.0 | 7.32 | 12.34 | 17.86 | dragon | 193.151.160.9 |
| 71.97 | shadowsocks | 278.1 | 631.1 | 21.34 | 0.0 | 7.27 | 12.34 | 17.86 | dragon | 156.146.38.170 |
| 71.32 | shadowsocks | 387.1 | 1000.1 | 18.82 | 0.0 | 7.32 | 12.34 | 17.86 | dragon | 193.151.160.18 |
| 69.82 | shadowsocks | 283.9 | 657.2 | 21.21 | 0.0 | 7.28 | 12.34 | 17.86 | dragon | 156.146.38.167 |
| 69.6 | http | 420.8 | 1095.5 | 18.04 | 0.0 | 0.0 | 14.73 | 20.0 | ermaozi | 154.47.25.78 |
| 68.64 | shadowsocks | 311.2 | 593.8 | 20.57 | 0.0 | 7.16 | 12.34 | 17.86 | dragon | 173.244.56.9 |
| 68.54 | hysteria2 | 256.2 | 671.0 | 21.85 | 0.0 | 0.0 | 12.69 | 20.0 | ermaozi | 130.94.16.109 |
| 67.99 | shadowsocks | 345.3 | 675.1 | 19.78 | 0.0 | 7.52 | 12.34 | 17.86 | dragon | 149.22.95.183 |
| 67.92 | shadowsocks | 317.6 | 618.2 | 20.43 | 0.0 | 7.59 | 12.34 | 17.86 | dragon | 173.244.56.6 |
| 67.44 | shadowsocks | 282.6 | 647.8 | 21.24 | 0.0 | 7.27 | 12.34 | 17.86 | dragon | 156.146.38.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.888 | 0.812 | 191 | 44753 | prefer |
| ermaozi | 0.867 | 0.875 | 24 | 510 | prefer |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 7779 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5005 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2709 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10415 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5820 | observe |
| barry-far-vless | 0.255 | None | 0 | 5941 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4444 | observe |
| mheidari-all | 0.255 | None | 0 | 34088 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.244 | None | 0 | 1723 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1723 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 25 |
| cn-block | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 2 |
| cn-block | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| 204 | ProxyError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46904: bind: address already in use | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 88 | 37 | - |
| global | False | 88 | 40 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
