# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-23 07:43:24 |
| 运行耗时 | 440.3s |
| 订阅源总数 | 108 |
| 健康订阅源 | 93 |
| 原始节点 | 141282 |
| 去重后节点 | 57939 |
| TCP 可达 | 3000 |
| 真实可用 | 108 |
| Verified 输出 | 108 |
| Global 输出 | 110 |
| All 输出 | 57939 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 8.2 |
| geo | 1.7 |
| tcp | 201.0 |
| probe | 127.2 |
| real_test | 51.4 |
| china_check | 23.4 |
| write_verified | 0.0 |
| generate | 27.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 82180 |
| vmess | 22068 |
| shadowsocks | 17789 |
| trojan | 16104 |
| hysteria2 | 2004 |
| http | 339 |
| shadowsocksr | 325 |
| tuic | 254 |
| socks | 129 |
| hysteria | 46 |
| anytls | 44 |

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
| 69.13 | hysteria2 | 255.3 | 680.1 | 21.87 | 0.0 | 6.76 | 14.0 | 10.0 | dragon | 129.213.91.185 |
| 68.3 | http | 389.7 | 901.2 | 18.76 | 0.0 | 0.0 | 14.85 | 20.0 | ermaozi | 38.247.141.135 |
| 67.16 | shadowsocks | 279.4 | 677.1 | 21.31 | 0.0 | 6.77 | 13.08 | 10.0 | dragon | 37.19.198.160 |
| 67.01 | shadowsocks | 285.6 | 730.5 | 21.17 | 0.0 | 6.76 | 13.08 | 10.0 | dragon | 37.19.198.236 |
| 66.95 | shadowsocks | 270.9 | 650.2 | 21.51 | 0.0 | 6.87 | 13.08 | 10.0 | dragon | 156.146.38.170 |
| 66.88 | shadowsocks | 281.2 | 732.0 | 21.27 | 0.0 | 6.53 | 13.08 | 10.0 | dragon | 37.19.198.244 |
| 66.77 | shadowsocks | 276.2 | 703.0 | 21.38 | 0.0 | 6.81 | 13.08 | 10.0 | dragon | 185.230.230.18 |
| 66.75 | shadowsocks | 273.5 | 671.6 | 21.45 | 0.0 | 6.72 | 13.08 | 10.0 | dragon | 185.215.132.18 |
| 65.74 | shadowsocks | 319.6 | 778.4 | 20.38 | 0.0 | 6.78 | 13.08 | 10.0 | dragon | 193.151.163.18 |
| 65.71 | shadowsocks | 270.5 | 657.4 | 21.52 | 0.0 | 6.59 | 13.08 | 10.0 | dragon | 156.146.38.167 |
| 65.07 | shadowsocks | 349.8 | 899.6 | 19.68 | 0.0 | 6.81 | 13.08 | 10.0 | dragon | 45.86.51.18 |
| 64.83 | vless | 290.7 | 691.2 | 21.05 | 0.0 | 0.0 | 7.4 | 17.3 | Surfboard-tg-mixed | 195.123.235.177 |
| 64.78 | shadowsocks | 347.9 | 905.7 | 19.72 | 0.0 | 6.48 | 13.08 | 10.0 | dragon | 185.215.132.9 |
| 63.6 | http | 440.3 | 831.0 | 17.59 | 0.0 | 0.0 | 14.85 | 20.0 | ermaozi | 44.248.167.117 |
| 62.25 | http | 441.2 | 912.2 | 17.56 | 0.0 | 0.0 | 14.85 | 20.0 | ermaozi | 45.63.38.134 |
| 62.07 | http | 520.4 | 1193.3 | 15.73 | 0.0 | 0.0 | 14.85 | 20.0 | ermaozi | 138.199.35.208 |
| 61.97 | http | 527.0 | 1212.8 | 15.58 | 0.0 | 0.0 | 14.85 | 20.0 | ermaozi | 138.199.35.202 |
| 61.81 | http | 524.3 | 1198.5 | 15.64 | 0.0 | 0.0 | 14.85 | 20.0 | ermaozi | 138.199.35.195 |
| 61.79 | http | 534.3 | 1240.1 | 15.41 | 0.0 | 0.0 | 14.85 | 20.0 | ermaozi | 138.199.35.215 |
| 61.74 | shadowsocks | 387.0 | 952.5 | 18.82 | 0.0 | 6.5 | 13.08 | 10.0 | dragon | 193.151.160.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.958 | 0.882 | 186 | 45037 | prefer |
| ermaozi | 0.63 | 0.608 | 102 | 609 | observe |
| Surfboard-tg-mixed | 0.441 | 0.462 | 13 | 6999 | observe |
| Au1rxx-base64 | 0.406 | 0.4 | 15 | 1530 | observe |
| mheidari-all | 0.389 | 0.385 | 13 | 23958 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4911 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3641 | observe |
| Epodonios-all | 0.255 | None | 0 | 7509 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10102 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5447 | observe |
| barry-far-vless | 0.255 | None | 0 | 5662 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4230 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 33 |
| 204 | ProxyError | - | 12 |
| cn-block | ProxyError | - | 10 |
| geo | ProxyError | - | 10 |
| geo | ClientOSError | - | 7 |
| speed | ProxyError | - | 6 |
| speed | ClientOSError | - | 3 |
| cn-block | TimeoutError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:41196: bind: address already in use | - | 1 |
| 204 | TimeoutError | - | 1 |
| 204 | ClientOSError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 133 | 108 | - |
| global | False | 138 | 110 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
