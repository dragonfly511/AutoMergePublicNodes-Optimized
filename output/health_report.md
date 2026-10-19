# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-19 18:06:57 |
| 运行耗时 | 311.3s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 94237 |
| 去重后节点 | 26065 |
| TCP 可达 | 3000 |
| 真实可用 | 63 |
| Verified 输出 | 63 |
| Global 输出 | 68 |
| All 输出 | 26065 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.5 |
| tcp | 80.4 |
| probe | 110.1 |
| real_test | 63.3 |
| china_check | 35.1 |
| write_verified | 0.0 |
| generate | 13.0 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 55275 |
| vmess | 16846 |
| shadowsocks | 11520 |
| trojan | 8426 |
| hysteria2 | 1478 |
| http | 390 |
| shadowsocksr | 170 |
| socks | 63 |
| anytls | 46 |
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
| 77.0 | shadowsocks | 253.4 | 697.2 | 21.91 | 0.0 | 8.93 | 13.78 | 16.38 | Au1rxx-base64 | 37.19.198.160 |
| 74.79 | shadowsocks | 253.3 | 699.5 | 21.91 | 0.0 | 6.72 | 13.78 | 16.38 | Au1rxx-base64 | 37.19.198.244 |
| 74.58 | shadowsocks | 262.6 | 719.8 | 21.7 | 0.0 | 6.72 | 13.78 | 16.38 | Au1rxx-base64 | 37.19.198.236 |
| 74.31 | shadowsocks | 288.3 | 663.8 | 21.1 | 0.0 | 9.27 | 13.78 | 16.38 | Au1rxx-base64 | 156.146.38.169 |
| 74.09 | shadowsocks | 320.4 | 888.7 | 20.36 | 0.0 | 9.57 | 13.78 | 16.38 | Au1rxx-base64 | 37.19.198.243 |
| 73.92 | vless | 297.6 | 745.2 | 20.89 | 0.0 | 8.15 | 8.5 | 16.38 | Au1rxx-base64 | 66.70.179.198 |
| 73.08 | shadowsocks | 292.1 | 665.9 | 21.02 | 0.0 | 8.03 | 13.78 | 16.38 | Au1rxx-base64 | 156.146.38.170 |
| 73.03 | shadowsocks | 279.7 | 637.2 | 21.3 | 0.0 | 9.22 | 13.78 | 16.38 | Au1rxx-base64 | 156.146.38.168 |
| 71.13 | shadowsocks | 285.7 | 658.1 | 21.17 | 0.0 | 6.47 | 13.78 | 16.38 | Au1rxx-base64 | 156.146.38.167 |
| 69.9 | hysteria2 | 258.2 | 530.2 | 21.8 | 0.0 | 8.92 | 10.0 | 16.38 | Au1rxx-base64 | 179.255.104.98 |
| 68.94 | vless | 368.1 | 1000.4 | 19.26 | 0.0 | 8.22 | 8.5 | 16.38 | Au1rxx-base64 | 169.40.42.229 |
| 68.33 | shadowsocks | 292.5 | 716.3 | 21.01 | 0.0 | 6.66 | 13.78 | 16.38 | Au1rxx-base64 | 64.74.163.69 |
| 68.01 | hysteria2 | 394.4 | 895.7 | 18.65 | 0.0 | 9.65 | 10.0 | 16.38 | Au1rxx-base64 | 129.213.91.185 |
| 67.2 | vless | 386.0 | 958.3 | 18.84 | 0.0 | 8.14 | 8.5 | 16.38 | Au1rxx-base64 | 209.200.246.148 |
| 66.87 | vless | 381.1 | 627.8 | 18.96 | 0.0 | 8.92 | 8.5 | 16.38 | Au1rxx-base64 | 144.202.126.147 |
| 66.68 | vless | 340.1 | 605.5 | 19.91 | 0.0 | 8.73 | 8.5 | 16.38 | Au1rxx-base64 | 67.220.73.204 |
| 66.61 | vless | 371.8 | 662.3 | 19.17 | 0.0 | 8.87 | 8.5 | 16.38 | Au1rxx-base64 | 154.9.241.170 |
| 65.91 | hysteria2 | 367.0 | 698.9 | 19.28 | 0.0 | 7.39 | 10.0 | 16.38 | Au1rxx-base64 | 62.210.124.146 |
| 64.93 | vless | 338.2 | 618.5 | 19.95 | 0.0 | 8.93 | 8.5 | 16.38 | Au1rxx-base64 | 104.225.239.122 |
| 64.83 | vless | 402.8 | 652.0 | 18.45 | 0.0 | 7.71 | 8.5 | 16.38 | Au1rxx-base64 | 154.29.145.196 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.85 | 0.788 | 269 | 1598 | prefer |
| mheidari-all | 0.642 | 0.567 | 30 | 23148 | observe |
| ermaozi-get_subscribe | 0.569 | 1.0 | 8 | 508 | observe |
| zhangkai | 0.478 | 1.0 | 6 | 27 | observe |
| Surfboard-tg-mixed | 0.407 | 0.333 | 18 | 6948 | observe |
| tg-LonUp_M | 0.262 | 1.0 | 1 | 172 | observe |
| tg-oneclickvpnkeys | 0.258 | 1.0 | 1 | 77 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4940 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3294 | observe |
| Epodonios-all | 0.255 | None | 0 | 7406 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 9800 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5438 | observe |
| barry-far-vless | 0.255 | None | 0 | 5654 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4314 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 46 |
| speed | ClientOSError | - | 13 |
| 204 | TimeoutError | - | 5 |
| cn-block | TimeoutError | - | 4 |
| geo | ClientOSError | - | 4 |
| 204 | ProxyError | - | 3 |
| cn-block | ClientOSError | - | 3 |
| sing-box exited 1 |  [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:32952: bind: address already in use | - | 1 |
| speed | ProxyError | - | 1 |
| 204 | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 88 | 63 | - |
| global | False | 97 | 68 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
