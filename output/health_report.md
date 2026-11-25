# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-25 21:25:01 |
| 运行耗时 | 378.2s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 122532 |
| 去重后节点 | 59075 |
| TCP 可达 | 3000 |
| 真实可用 | 92 |
| Verified 输出 | 92 |
| Global 输出 | 96 |
| All 输出 | 59075 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.5 |
| geo | 1.5 |
| tcp | 185.0 |
| probe | 84.6 |
| real_test | 47.4 |
| china_check | 35.7 |
| write_verified | 0.0 |
| generate | 18.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 74363 |
| vmess | 19231 |
| shadowsocks | 13167 |
| trojan | 12696 |
| hysteria2 | 2329 |
| shadowsocksr | 233 |
| socks | 179 |
| http | 145 |
| hysteria | 70 |
| anytls | 64 |
| tuic | 55 |

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
| 83.14 | hysteria2 | 213.4 | 568.6 | 22.84 | 0.0 | 10.0 | 12.0 | 19.3 | dragon | 66.94.121.46 |
| 80.37 | hysteria2 | 294.2 | 717.3 | 20.97 | 0.0 | 10.0 | 12.0 | 19.3 | dragon | 172.87.24.53 |
| 79.56 | shadowsocks | 228.4 | 537.4 | 22.49 | 0.0 | 10.0 | 13.56 | 19.3 | dragon | 23.150.152.38 |
| 79.27 | shadowsocks | 296.5 | 748.5 | 20.91 | 0.0 | 10.0 | 13.56 | 19.3 | dragon | 137.184.89.151 |
| 79.13 | vless | 205.8 | 543.9 | 23.01 | 0.0 | 9.24 | 12.58 | 19.3 | dragon | 15.204.97.216 |
| 77.83 | shadowsocks | 264.9 | 569.9 | 21.65 | 0.0 | 10.0 | 13.56 | 19.3 | dragon | 95.215.201.18 |
| 76.8 | shadowsocks | 295.8 | 651.2 | 20.93 | 0.0 | 10.0 | 13.56 | 19.3 | dragon | 169.197.142.68 |
| 76.3 | vless | 309.1 | 649.4 | 20.62 | 0.0 | 10.0 | 12.58 | 19.3 | dragon | 172.235.40.143 |
| 76.17 | shadowsocks | 214.2 | 564.9 | 22.82 | 0.0 | 4.49 | 13.56 | 19.3 | dragon | 149.22.95.183 |
| 76.07 | shadowsocks | 278.1 | 585.0 | 21.34 | 0.0 | 10.0 | 13.56 | 19.3 | dragon | 173.244.56.6 |
| 74.98 | shadowsocks | 243.8 | 668.8 | 22.13 | 0.0 | 9.49 | 13.56 | 19.3 | dragon | 38.143.66.146 |
| 74.55 | vless | 287.6 | 603.2 | 21.12 | 0.0 | 10.0 | 12.58 | 19.3 | dragon | 172.236.238.71 |
| 74.37 | vless | 301.1 | 659.2 | 20.81 | 0.0 | 10.0 | 12.58 | 19.3 | dragon | 172.235.32.253 |
| 74.27 | vless | 311.2 | 681.0 | 20.57 | 0.0 | 10.0 | 12.58 | 19.3 | dragon | 172.233.139.98 |
| 74.26 | vless | 282.5 | 585.2 | 21.24 | 0.0 | 10.0 | 12.58 | 19.3 | dragon | 172.235.50.209 |
| 74.23 | shadowsocks | 334.0 | 699.2 | 20.05 | 0.0 | 10.0 | 13.56 | 19.3 | dragon | 156.146.38.168 |
| 73.93 | shadowsocks | 339.2 | 720.1 | 19.93 | 0.0 | 10.0 | 13.56 | 19.3 | dragon | 156.146.38.170 |
| 73.88 | vless | 289.4 | 612.0 | 21.08 | 0.0 | 10.0 | 12.58 | 19.3 | dragon | 172.236.233.130 |
| 73.8 | vless | 282.1 | 584.5 | 21.25 | 0.0 | 10.0 | 12.58 | 19.3 | dragon | 172.236.241.130 |
| 73.77 | vless | 295.3 | 633.6 | 20.94 | 0.0 | 10.0 | 12.58 | 19.3 | dragon | 172.236.239.126 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.974 | 1.0 | 22 | 403 | prefer |
| dragon | 0.961 | 0.884 | 267 | 43982 | prefer |
| tg-LonUp_M | 0.318 | 1.0 | 2 | 171 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4958 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11598 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8209 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5378 | observe |
| barry-far-vless | 0.255 | None | 0 | 5559 | observe |
| mheidari-all | 0.255 | None | 0 | 15044 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 14 |
| 204 | ClientOSError | - | 8 |
| 204 | ProxyError | - | 6 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 111 | 92 | - |
| global | False | 115 | 96 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
