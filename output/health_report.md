# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-21 21:09:48 |
| 运行耗时 | 326.1s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 96105 |
| 去重后节点 | 26894 |
| TCP 可达 | 3000 |
| 真实可用 | 97 |
| Verified 输出 | 97 |
| Global 输出 | 104 |
| All 输出 | 26894 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.0 |
| geo | 1.6 |
| tcp | 83.4 |
| probe | 104.0 |
| real_test | 78.9 |
| china_check | 36.8 |
| write_verified | 0.1 |
| generate | 13.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 57123 |
| vmess | 16969 |
| shadowsocks | 11928 |
| trojan | 8439 |
| hysteria2 | 1261 |
| shadowsocksr | 164 |
| http | 121 |
| socks | 56 |
| anytls | 21 |
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
| 77.43 | shadowsocks | 246.9 | 596.3 | 22.06 | 0.0 | 10.0 | 13.89 | 15.48 | Au1rxx-base64 | 149.22.95.183 |
| 74.79 | vless | 221.6 | 549.8 | 22.65 | 0.0 | 8.28 | 8.38 | 15.48 | Au1rxx-base64 | 154.12.38.159 |
| 73.97 | vless | 220.8 | 538.0 | 22.67 | 0.0 | 7.44 | 8.38 | 15.48 | Au1rxx-base64 | 154.12.38.202 |
| 73.59 | shadowsocks | 237.3 | 556.0 | 22.29 | 0.0 | 8.93 | 13.89 | 15.48 | Au1rxx-base64 | 173.244.56.6 |
| 72.82 | shadowsocks | 298.6 | 665.2 | 20.87 | 0.0 | 10.0 | 13.89 | 15.48 | Au1rxx-base64 | 156.146.38.169 |
| 72.58 | shadowsocks | 435.1 | 1157.1 | 17.71 | 0.0 | 10.0 | 13.89 | 15.48 | Au1rxx-base64 | 95.215.201.18 |
| 72.37 | vless | 196.3 | 490.3 | 23.23 | 0.0 | 8.28 | 8.38 | 15.48 | Au1rxx-base64 | 45.76.172.197 |
| 71.5 | vless | 221.9 | 524.7 | 22.64 | 0.0 | 10.0 | 8.38 | 15.48 | Au1rxx-base64 | 195.123.240.65 |
| 71.12 | vless | 213.7 | 546.1 | 22.83 | 0.0 | 7.43 | 8.38 | 15.48 | Au1rxx-base64 | 156.229.164.4 |
| 70.74 | shadowsocks | 296.3 | 349.6 | 20.92 | 1.89 | 9.73 | 13.89 | 15.48 | Au1rxx-base64 | 149.22.87.241 |
| 70.18 | vless | 203.9 | 529.3 | 23.06 | 0.0 | 8.26 | 8.38 | 15.48 | Au1rxx-base64 | 172.236.227.60 |
| 69.88 | shadowsocks | 367.4 | 872.5 | 19.27 | 0.0 | 8.63 | 13.89 | 15.48 | Au1rxx-base64 | 156.146.38.167 |
| 68.59 | shadowsocks | 242.6 | 573.2 | 22.16 | 0.0 | 0.0 | 13.89 | 16.54 | mheidari-all | 173.244.56.9 |
| 68.22 | shadowsocks | 389.4 | 819.4 | 18.76 | 0.0 | 10.0 | 13.89 | 15.48 | Au1rxx-base64 | 37.19.198.243 |
| 68.01 | shadowsocks | 298.1 | 657.0 | 20.88 | 0.0 | 10.0 | 13.89 | 15.48 | Au1rxx-base64 | 156.146.38.170 |
| 67.98 | shadowsocks | 423.3 | 958.5 | 17.98 | 0.0 | 10.0 | 13.89 | 15.48 | Au1rxx-base64 | 185.215.132.9 |
| 67.78 | shadowsocks | 388.2 | 822.2 | 18.79 | 0.0 | 10.0 | 13.89 | 15.48 | Au1rxx-base64 | 37.19.198.160 |
| 67.66 | vless | 217.8 | 601.5 | 22.74 | 0.0 | 0.0 | 8.38 | 16.54 | mheidari-all | 47.251.108.158 |
| 67.6 | shadowsocks | 366.4 | 762.3 | 19.3 | 0.0 | 10.0 | 13.89 | 15.48 | Au1rxx-base64 | 193.151.163.18 |
| 67.45 | shadowsocks | 300.8 | 354.5 | 20.81 | 1.71 | 9.73 | 13.89 | 15.48 | Au1rxx-base64 | 149.22.87.240 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.927 | 0.96 | 25 | 31 | prefer |
| mheidari-all | 0.903 | 0.831 | 77 | 23903 | prefer |
| Au1rxx-base64 | 0.756 | 0.694 | 206 | 1598 | prefer |
| Surfboard-tg-mixed | 0.653 | 0.575 | 80 | 7007 | observe |
| ermaozi-get_subscribe | 0.27 | 1.0 | 1 | 385 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4925 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 4067 | observe |
| Epodonios-all | 0.255 | None | 0 | 7500 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10034 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5519 | observe |
| barry-far-vless | 0.255 | None | 0 | 5734 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4164 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| Au1rxx-clash | 0.239 | None | 0 | 1598 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 63 |
| speed | ClientOSError | - | 12 |
| geo | ClientOSError | - | 12 |
| 204 | TimeoutError | - | 9 |
| 204 | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 5 |
| cn-block | TimeoutError | - | 4 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:45172: bind: address already in use | - | 1 |
| cn-block | ProxyError | - | 1 |
| speed | TimeoutError | - | 1 |
| 204 | ClientOSError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 89 | 97 | - |
| global | False | 94 | 104 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
