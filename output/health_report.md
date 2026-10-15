# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-15 18:24:54 |
| 运行耗时 | 320.5s |
| 订阅源总数 | 107 |
| 健康订阅源 | 93 |
| 原始节点 | 99920 |
| 去重后节点 | 27707 |
| TCP 可达 | 3000 |
| 真实可用 | 89 |
| Verified 输出 | 89 |
| Global 输出 | 93 |
| All 输出 | 27707 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 7.8 |
| geo | 1.7 |
| tcp | 89.0 |
| probe | 108.3 |
| real_test | 68.6 |
| china_check | 31.3 |
| write_verified | 0.1 |
| generate | 13.8 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 59042 |
| vmess | 16342 |
| shadowsocks | 11996 |
| trojan | 10424 |
| hysteria2 | 1195 |
| http | 648 |
| shadowsocksr | 166 |
| socks | 57 |
| anytls | 27 |
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
| 78.18 | shadowsocks | 214.3 | 527.4 | 22.82 | 0.0 | 10.0 | 13.72 | 15.64 | Au1rxx-base64 | 173.244.56.9 |
| 78.13 | shadowsocks | 216.5 | 531.2 | 22.77 | 0.0 | 10.0 | 13.72 | 15.64 | Au1rxx-base64 | 173.244.56.6 |
| 76.91 | shadowsocks | 269.0 | 636.5 | 21.55 | 0.0 | 10.0 | 13.72 | 15.64 | Au1rxx-base64 | 156.146.38.167 |
| 76.89 | shadowsocks | 270.1 | 636.9 | 21.53 | 0.0 | 10.0 | 13.72 | 15.64 | Au1rxx-base64 | 156.146.38.168 |
| 76.74 | shadowsocks | 271.7 | 641.3 | 21.49 | 0.0 | 10.0 | 13.72 | 15.64 | Au1rxx-base64 | 156.146.38.170 |
| 76.47 | shadowsocks | 264.6 | 625.3 | 21.65 | 0.0 | 10.0 | 13.72 | 15.64 | Au1rxx-base64 | 156.146.38.169 |
| 74.52 | http | 210.9 | 528.9 | 22.9 | 0.0 | 0.0 | 14.62 | 20.0 | ermaozi | 138.199.35.216 |
| 73.38 | shadowsocks | 288.0 | 619.4 | 21.11 | 0.0 | 10.0 | 13.72 | 15.64 | Au1rxx-base64 | 149.22.95.183 |
| 70.99 | http | 251.7 | 657.3 | 21.95 | 0.0 | 0.0 | 14.62 | 20.0 | ermaozi | 138.199.35.198 |
| 69.67 | shadowsocks | 295.9 | 434.4 | 20.93 | 0.0 | 10.0 | 13.72 | 15.64 | Au1rxx-base64 | 103.11.76.248 |
| 69.53 | http | 340.1 | 749.1 | 19.91 | 0.0 | 0.0 | 14.62 | 20.0 | ermaozi | 38.95.111.226 |
| 67.94 | http | 367.6 | 726.6 | 19.27 | 0.0 | 0.0 | 14.62 | 20.0 | ermaozi | 167.88.60.242 |
| 67.68 | shadowsocks | 368.0 | 782.6 | 19.26 | 0.0 | 10.0 | 13.72 | 15.64 | Au1rxx-base64 | 37.19.198.236 |
| 67.33 | vless | 300.8 | 655.0 | 20.81 | 0.0 | 6.58 | 8.23 | 15.64 | Au1rxx-base64 | 216.227.161.95 |
| 66.74 | shadowsocks | 365.3 | 785.8 | 19.32 | 0.0 | 10.0 | 13.72 | 15.64 | Au1rxx-base64 | 37.19.198.160 |
| 65.95 | http | 385.0 | 649.2 | 18.87 | 0.0 | 0.0 | 14.62 | 20.0 | ermaozi | 38.28.193.188 |
| 65.9 | vless | 403.7 | 878.5 | 18.43 | 0.0 | 10.0 | 8.23 | 15.64 | Au1rxx-base64 | 95.111.212.241 |
| 62.59 | hysteria2 | 334.2 | 735.3 | 20.04 | 0.0 | 0.0 | 11.25 | 15.64 | Au1rxx-base64 | 129.213.91.185 |
| 62.41 | vless | 191.5 | 489.3 | 23.34 | 0.0 | 7.09 | 8.23 | 15.64 | Au1rxx-base64 | 216.234.140.15 |
| 62.31 | vless | 246.0 | 599.7 | 22.08 | 0.0 | 0.0 | 8.23 | 12.0 | mheidari-all | 47.251.108.158 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.997 | 0.985 | 66 | 659 | prefer |
| Au1rxx-base64 | 0.772 | 0.705 | 281 | 1732 | prefer |
| mheidari-all | 0.725 | 0.684 | 19 | 24099 | prefer |
| Surfboard-tg-mixed | 0.421 | 0.667 | 6 | 7281 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 5089 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 5147 | observe |
| Epodonios-all | 0.255 | None | 0 | 7794 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10078 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5707 | observe |
| barry-far-vless | 0.255 | None | 0 | 5961 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4235 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-clash | 0.244 | None | 0 | 1732 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 47 |
| 204 | TimeoutError | - | 11 |
| speed | ClientOSError | - | 10 |
| 204 | ProxyError | - | 8 |
| cn-block | ClientOSError | - | 7 |
| geo | ClientOSError | - | 4 |
| cn-block | ProxyError | - | 3 |
| 204 | ClientOSError | - | 2 |
| speed | TimeoutError | - | 1 |
| geo | ProxyError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 95 | 89 | - |
| global | False | 103 | 93 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
