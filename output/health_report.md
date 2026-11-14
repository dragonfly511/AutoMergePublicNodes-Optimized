# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-14 05:37:19 |
| 运行耗时 | 425.8s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 128227 |
| 去重后节点 | 58679 |
| TCP 可达 | 3000 |
| 真实可用 | 55 |
| Verified 输出 | 55 |
| Global 输出 | 57 |
| All 输出 | 58679 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.9 |
| geo | 1.7 |
| tcp | 195.9 |
| probe | 106.5 |
| real_test | 40.5 |
| china_check | 41.3 |
| write_verified | 0.0 |
| generate | 31.1 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 78153 |
| vmess | 18841 |
| trojan | 14703 |
| shadowsocks | 13576 |
| hysteria2 | 2159 |
| http | 288 |
| shadowsocksr | 226 |
| socks | 114 |
| hysteria | 71 |
| tuic | 55 |
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
| 76.2 | trojan | 319.5 | 647.3 | 20.38 | 0.0 | 9.84 | 12.78 | 20.0 | dragon | 216.106.186.46 |
| 75.68 | trojan | 298.5 | 565.7 | 20.87 | 0.0 | 9.84 | 12.78 | 20.0 | dragon | 216.106.186.155 |
| 74.99 | trojan | 242.1 | 626.3 | 22.17 | 0.0 | 8.62 | 12.78 | 20.0 | dragon | 170.101.101.131 |
| 74.5 | trojan | 305.8 | 621.4 | 20.7 | 0.0 | 7.37 | 12.78 | 20.0 | dragon | 216.106.186.32 |
| 73.83 | trojan | 337.4 | 510.9 | 19.97 | 0.0 | 9.84 | 12.78 | 20.0 | dragon | 216.106.186.66 |
| 72.59 | shadowsocks | 210.8 | 592.0 | 22.9 | 0.0 | 0.0 | 14.19 | 20.0 | dragon | 38.128.66.32 |
| 72.48 | http | 304.6 | 569.3 | 20.73 | 0.0 | 0.0 | 14.47 | 19.78 | ermaozi | 172.64.68.89 |
| 72.34 | http | 310.7 | 830.0 | 20.59 | 0.0 | 0.0 | 14.47 | 19.78 | ermaozi | 172.64.69.89 |
| 72.29 | shadowsocks | 245.2 | 602.1 | 22.1 | 0.0 | 0.0 | 14.19 | 20.0 | dragon | 156.146.38.170 |
| 72.11 | shadowsocks | 309.9 | 711.9 | 20.6 | 0.0 | 3.5 | 14.19 | 20.0 | dragon | 185.215.132.18 |
| 72.03 | hysteria2 | 313.0 | 765.5 | 20.53 | 0.0 | 0.0 | 12.5 | 20.0 | dragon | 206.189.229.48 |
| 71.83 | shadowsocks | 322.2 | 779.8 | 20.32 | 0.0 | 3.45 | 14.19 | 20.0 | dragon | 193.151.160.9 |
| 71.62 | hysteria2 | 347.8 | 849.6 | 19.73 | 0.0 | 0.39 | 12.5 | 20.0 | dragon | 34.24.25.1 |
| 71.58 | trojan | 301.5 | 610.1 | 20.8 | 0.0 | 9.84 | 12.78 | 20.0 | dragon | 216.106.186.33 |
| 71.03 | shadowsocks | 299.9 | 766.5 | 20.84 | 0.0 | 0.0 | 14.19 | 20.0 | dragon | 156.146.38.167 |
| 70.99 | shadowsocks | 279.7 | 683.2 | 21.3 | 0.0 | 0.0 | 14.19 | 20.0 | dragon | 185.230.230.18 |
| 70.75 | shadowsocks | 290.0 | 821.9 | 21.06 | 0.0 | 0.0 | 14.19 | 20.0 | dragon | 67.220.73.178 |
| 70.75 | shadowsocks | 290.2 | 804.9 | 21.06 | 0.0 | 0.0 | 14.19 | 20.0 | dragon | 216.106.178.169 |
| 69.86 | shadowsocks | 328.5 | 860.1 | 20.17 | 0.0 | 0.0 | 14.19 | 20.0 | dragon | 167.17.67.171 |
| 69.84 | shadowsocks | 363.7 | 779.4 | 19.36 | 0.0 | 5.14 | 14.19 | 20.0 | dragon | 95.215.201.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.983 | 0.906 | 245 | 44709 | prefer |
| ermaozi | 0.983 | 0.972 | 71 | 597 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4900 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2734 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11507 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8942 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 6457 | observe |
| barry-far-vless | 0.255 | None | 0 | 6640 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4624 | observe |
| mheidari-all | 0.255 | None | 0 | 13877 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 14 |
| speed | TimeoutError | - | 3 |
| 204 | ClientOSError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48591: bind: address already in use | - | 1 |
| 204 | ProxyError | - | 1 |
| cn-block | ProxyError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 76 | 55 | - |
| global | False | 76 | 57 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
