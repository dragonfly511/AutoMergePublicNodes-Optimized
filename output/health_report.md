# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-20 16:10:29 |
| 运行耗时 | 294.9s |
| 订阅源总数 | 107 |
| 健康订阅源 | 92 |
| 原始节点 | 94114 |
| 去重后节点 | 26477 |
| TCP 可达 | 3000 |
| 真实可用 | 78 |
| Verified 输出 | 78 |
| Global 输出 | 81 |
| All 输出 | 26477 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.2 |
| geo | 1.5 |
| tcp | 80.5 |
| probe | 101.1 |
| real_test | 66.1 |
| china_check | 25.3 |
| write_verified | 0.0 |
| generate | 13.4 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 56050 |
| vmess | 16826 |
| shadowsocks | 11219 |
| trojan | 8387 |
| hysteria2 | 1141 |
| http | 211 |
| shadowsocksr | 158 |
| socks | 63 |
| anytls | 36 |
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
| 76.78 | shadowsocks | 260.5 | 716.1 | 21.75 | 0.0 | 10.0 | 13.35 | 15.68 | Au1rxx-base64 | 37.19.198.244 |
| 74.37 | vless | 293.4 | 743.1 | 20.99 | 0.0 | 8.47 | 9.23 | 15.68 | Au1rxx-base64 | 195.123.235.183 |
| 74.17 | vless | 264.1 | 626.4 | 21.66 | 0.0 | 8.64 | 9.23 | 15.68 | Au1rxx-base64 | 195.211.98.43 |
| 73.62 | shadowsocks | 280.1 | 629.9 | 21.29 | 0.0 | 10.0 | 13.35 | 15.68 | Au1rxx-base64 | 156.146.38.167 |
| 71.6 | shadowsocks | 246.4 | 675.1 | 22.07 | 0.0 | 10.0 | 13.35 | 15.68 | Au1rxx-base64 | 185.230.230.18 |
| 71.46 | shadowsocks | 252.6 | 653.9 | 21.93 | 0.0 | 10.0 | 13.35 | 15.68 | Au1rxx-base64 | 185.215.132.18 |
| 71.38 | vless | 272.5 | 733.4 | 21.47 | 0.0 | 10.0 | 9.23 | 15.68 | Au1rxx-base64 | 104.243.44.241 |
| 71.02 | shadowsocks | 286.1 | 652.4 | 21.16 | 0.0 | 7.9 | 13.35 | 15.68 | Au1rxx-base64 | 156.146.38.169 |
| 71.01 | shadowsocks | 256.4 | 711.5 | 21.84 | 0.0 | 0.0 | 13.35 | 19.82 | mheidari-all | 37.19.198.236 |
| 71.01 | shadowsocks | 256.7 | 715.6 | 21.84 | 0.0 | 0.0 | 13.35 | 19.82 | mheidari-all | 37.19.198.243 |
| 71.0 | vless | 479.1 | 1311.0 | 16.69 | 0.0 | 9.4 | 9.23 | 15.68 | Au1rxx-base64 | 169.40.42.229 |
| 69.42 | shadowsocks | 291.7 | 712.8 | 21.02 | 0.0 | 9.21 | 13.35 | 15.68 | Au1rxx-base64 | 193.151.160.9 |
| 69.04 | shadowsocks | 320.7 | 908.3 | 20.35 | 0.0 | 9.16 | 13.35 | 15.68 | Au1rxx-base64 | 45.86.51.18 |
| 68.45 | vless | 376.2 | 941.4 | 19.07 | 0.0 | 9.35 | 9.23 | 15.68 | Au1rxx-base64 | 209.200.246.148 |
| 67.64 | shadowsocks | 287.0 | 651.9 | 21.13 | 0.0 | 0.0 | 13.35 | 19.82 | mheidari-all | 156.146.38.170 |
| 67.32 | vless | 380.3 | 871.2 | 18.97 | 0.0 | 10.0 | 9.23 | 15.68 | Au1rxx-base64 | 69.48.201.136 |
| 66.95 | shadowsocks | 316.1 | 753.9 | 20.46 | 0.0 | 0.0 | 13.35 | 19.82 | mheidari-all | 156.146.38.168 |
| 66.77 | shadowsocks | 375.3 | 768.7 | 19.09 | 0.0 | 8.58 | 13.35 | 15.68 | Au1rxx-base64 | 173.244.56.9 |
| 66.41 | shadowsocks | 417.3 | 779.3 | 18.12 | 0.0 | 9.99 | 13.35 | 15.68 | Au1rxx-base64 | 158.173.20.208 |
| 66.37 | vless | 428.4 | 878.0 | 17.86 | 0.0 | 10.0 | 9.23 | 15.68 | Au1rxx-base64 | 154.40.55.185 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.894 | 0.923 | 26 | 31 | prefer |
| mheidari-all | 0.848 | 0.776 | 67 | 23236 | prefer |
| Surfboard-tg-mixed | 0.843 | 0.778 | 36 | 6911 | prefer |
| Au1rxx-base64 | 0.771 | 0.719 | 249 | 1337 | prefer |
| ermaozi-get_subscribe | 0.636 | 1.0 | 10 | 429 | observe |
| Barabama-yudou | 0.262 | 1.0 | 1 | 166 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4967 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3519 | observe |
| Epodonios-all | 0.255 | None | 0 | 7384 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9911 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5515 | observe |
| barry-far-vless | 0.255 | None | 0 | 5732 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4278 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 64 |
| speed | ClientOSError | - | 11 |
| 204 | ProxyError | - | 5 |
| geo | ClientOSError | - | 4 |
| 204 | TimeoutError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 2 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42989: bind: address already in use | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 118 | 78 | - |
| global | False | 121 | 81 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
