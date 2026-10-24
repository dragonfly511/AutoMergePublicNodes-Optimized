# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-24 03:55:16 |
| 运行耗时 | 438.9s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 138168 |
| 去重后节点 | 58569 |
| TCP 可达 | 3000 |
| 真实可用 | 82 |
| Verified 输出 | 82 |
| Global 输出 | 83 |
| All 输出 | 58569 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.3 |
| geo | 1.7 |
| tcp | 191.8 |
| probe | 133.3 |
| real_test | 41.1 |
| china_check | 31.7 |
| write_verified | 0.0 |
| generate | 29.9 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 85171 |
| vmess | 20459 |
| shadowsocks | 16365 |
| trojan | 13429 |
| hysteria2 | 1959 |
| shadowsocksr | 259 |
| http | 254 |
| socks | 145 |
| hysteria | 47 |
| tuic | 43 |
| anytls | 37 |

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
| 76.53 | shadowsocks | 244.9 | 544.5 | 22.11 | 0.0 | 10.0 | 13.3 | 19.0 | dragon | 173.244.56.9 |
| 76.45 | shadowsocks | 249.1 | 555.8 | 22.01 | 0.0 | 10.0 | 13.3 | 19.0 | dragon | 173.244.56.6 |
| 75.63 | shadowsocks | 294.7 | 645.2 | 20.96 | 0.0 | 10.0 | 13.3 | 19.0 | dragon | 156.146.38.167 |
| 75.52 | shadowsocks | 297.3 | 665.8 | 20.9 | 0.0 | 10.0 | 13.3 | 19.0 | dragon | 156.146.38.169 |
| 75.18 | shadowsocks | 298.1 | 674.3 | 20.88 | 0.0 | 10.0 | 13.3 | 19.0 | dragon | 156.146.38.168 |
| 74.92 | http | 198.4 | 510.1 | 23.18 | 0.0 | 0.0 | 14.3 | 19.94 | ermaozi | 172.64.68.89 |
| 74.09 | http | 234.6 | 613.8 | 22.35 | 0.0 | 0.0 | 14.3 | 19.94 | ermaozi | 172.64.69.89 |
| 73.7 | trojan | 237.8 | 581.3 | 22.27 | 0.0 | 7.93 | 12.0 | 19.0 | dragon | 216.106.186.33 |
| 73.54 | http | 253.8 | 569.1 | 21.9 | 0.0 | 0.0 | 14.3 | 19.94 | ermaozi | 44.248.167.117 |
| 73.47 | hysteria2 | 239.6 | 553.2 | 22.23 | 0.0 | 0.0 | 13.24 | 19.0 | dragon | 66.94.121.46 |
| 71.84 | shadowsocks | 369.7 | 763.3 | 19.22 | 0.0 | 9.93 | 13.3 | 19.0 | dragon | 37.19.198.243 |
| 71.48 | shadowsocks | 381.1 | 777.6 | 18.96 | 0.0 | 9.88 | 13.3 | 19.0 | dragon | 185.230.230.18 |
| 71.45 | shadowsocks | 383.7 | 792.2 | 18.9 | 0.0 | 10.0 | 13.3 | 19.0 | dragon | 37.19.198.160 |
| 70.99 | shadowsocks | 421.9 | 971.5 | 18.01 | 0.0 | 10.0 | 13.3 | 19.0 | dragon | 185.215.132.9 |
| 70.53 | http | 297.7 | 716.5 | 20.89 | 0.0 | 0.0 | 14.3 | 19.94 | ermaozi | 44.229.69.166 |
| 70.11 | shadowsocks | 399.1 | 768.7 | 18.54 | 0.0 | 9.87 | 13.3 | 19.0 | dragon | 193.151.163.18 |
| 69.89 | shadowsocks | 373.7 | 777.5 | 19.13 | 0.0 | 9.92 | 13.3 | 19.0 | dragon | 37.19.198.244 |
| 69.6 | http | 406.9 | 1136.8 | 18.36 | 0.0 | 0.0 | 14.3 | 19.94 | ermaozi | 138.199.35.195 |
| 69.32 | http | 418.8 | 1164.2 | 18.08 | 0.0 | 0.0 | 14.3 | 19.94 | ermaozi | 138.199.35.197 |
| 69.2 | hysteria2 | 229.5 | 230.8 | 22.47 | 6.34 | 0.0 | 13.24 | 19.0 | dragon | 45.32.10.7 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.926 | 0.85 | 193 | 45691 | prefer |
| ermaozi | 0.524 | 0.5 | 80 | 608 | observe |
| tg-oneclickvpnkeys | 0.315 | 1.0 | 2 | 92 | observe |
| mheidari-all | 0.287 | 0.5 | 2 | 23800 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4911 | observe |
| Epodonios-all | 0.255 | None | 0 | 7650 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10227 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7159 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5520 | observe |
| barry-far-vless | 0.255 | None | 0 | 5734 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4117 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.236 | None | 0 | 1532 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| 204 | ProxyError | - | 37 |
| test_one_timeout | 15.0s | - | 21 |
| 204 | TimeoutError | - | 5 |
| speed | ClientOSError | - | 3 |
| cn-block | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46399: bind: address already in use | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 67 | 82 | - |
| global | False | 69 | 83 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
