# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-11-19 00:07:05 |
| 运行耗时 | 407.7s |
| 订阅源总数 | 108 |
| 健康订阅源 | 87 |
| 原始节点 | 127631 |
| 去重后节点 | 59195 |
| TCP 可达 | 3000 |
| 真实可用 | 81 |
| Verified 输出 | 81 |
| Global 输出 | 82 |
| All 输出 | 59195 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.3 |
| geo | 8.3 |
| tcp | 188.5 |
| probe | 105.2 |
| real_test | 39.4 |
| china_check | 36.8 |
| write_verified | 0.0 |
| generate | 23.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 77577 |
| vmess | 19036 |
| trojan | 14261 |
| shadowsocks | 13988 |
| hysteria2 | 2103 |
| shadowsocksr | 269 |
| socks | 148 |
| http | 112 |
| hysteria | 54 |
| tuic | 52 |
| anytls | 31 |

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
| 75.8 | shadowsocks | 251.3 | 622.5 | 21.96 | 0.0 | 5.05 | 13.69 | 19.6 | dragon | 185.230.230.18 |
| 75.49 | shadowsocks | 267.9 | 670.7 | 21.58 | 0.0 | 5.12 | 13.69 | 19.6 | dragon | 172.111.38.72 |
| 74.12 | shadowsocks | 323.8 | 827.4 | 20.28 | 0.0 | 5.05 | 13.69 | 19.6 | dragon | 38.91.100.39 |
| 73.73 | shadowsocks | 261.9 | 672.0 | 21.71 | 0.0 | 5.05 | 13.69 | 19.6 | dragon | 193.151.163.18 |
| 73.69 | shadowsocks | 345.1 | 915.0 | 19.79 | 0.0 | 5.11 | 13.69 | 19.6 | dragon | 15.204.247.206 |
| 73.58 | shadowsocks | 343.9 | 914.0 | 19.82 | 0.0 | 4.97 | 13.69 | 19.6 | dragon | 149.40.57.138 |
| 73.49 | shadowsocks | 262.1 | 682.5 | 21.71 | 0.0 | 4.99 | 13.69 | 19.6 | dragon | 149.40.57.134 |
| 73.46 | shadowsocks | 345.6 | 874.0 | 19.78 | 0.0 | 4.89 | 13.69 | 19.6 | dragon | 38.128.66.32 |
| 73.35 | shadowsocks | 350.5 | 866.3 | 19.66 | 0.0 | 4.9 | 13.69 | 19.6 | dragon | 216.106.178.169 |
| 72.69 | shadowsocks | 317.0 | 768.6 | 20.44 | 0.0 | 4.98 | 13.69 | 19.6 | dragon | 51.222.12.127 |
| 72.38 | shadowsocks | 352.9 | 877.8 | 19.61 | 0.0 | 4.79 | 13.69 | 19.6 | dragon | 167.88.62.203 |
| 71.81 | shadowsocks | 304.7 | 687.2 | 20.72 | 0.0 | 4.88 | 13.69 | 19.6 | dragon | 193.151.160.9 |
| 71.65 | shadowsocks | 231.8 | 598.5 | 22.41 | 0.0 | 4.95 | 13.69 | 19.6 | dragon | 198.98.53.130 |
| 71.36 | shadowsocks | 246.4 | 654.3 | 22.07 | 0.0 | 0.0 | 13.69 | 19.6 | dragon | 37.19.198.243 |
| 71.34 | shadowsocks | 247.6 | 651.5 | 22.05 | 0.0 | 0.0 | 13.69 | 19.6 | dragon | 37.19.198.236 |
| 71.3 | hysteria2 | 296.8 | 827.0 | 20.91 | 0.0 | 0.0 | 11.79 | 19.6 | dragon | 206.189.229.48 |
| 71.28 | shadowsocks | 250.0 | 661.1 | 21.99 | 0.0 | 0.0 | 13.69 | 19.6 | dragon | 37.19.198.244 |
| 71.21 | shadowsocks | 321.6 | 773.8 | 20.33 | 0.0 | 4.76 | 13.69 | 19.6 | dragon | 156.146.38.169 |
| 71.2 | shadowsocks | 321.9 | 767.3 | 20.33 | 0.0 | 4.97 | 13.69 | 19.6 | dragon | 51.222.141.125 |
| 70.65 | shadowsocks | 255.7 | 626.0 | 21.86 | 0.0 | 0.0 | 13.69 | 19.6 | dragon | 15.204.246.111 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.949 | 0.871 | 310 | 45096 | prefer |
| ermaozi | 0.929 | 0.95 | 20 | 508 | prefer |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4919 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2925 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3997 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 11962 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 8521 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5794 | observe |
| barry-far-vless | 0.255 | None | 0 | 5945 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4458 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 23 |
| speed | ClientOSError | - | 8 |
| 204 | ProxyError | - | 4 |
| cn-block | ClientOSError | - | 3 |
| geo | ClientOSError | - | 3 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 123 | 81 | - |
| global | False | 125 | 82 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
