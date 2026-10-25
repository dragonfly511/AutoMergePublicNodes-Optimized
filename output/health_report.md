# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-25 11:04:47 |
| 运行耗时 | 438.3s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 142684 |
| 去重后节点 | 60342 |
| TCP 可达 | 3000 |
| 真实可用 | 99 |
| Verified 输出 | 99 |
| Global 输出 | 100 |
| All 输出 | 60342 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 6.8 |
| geo | 1.6 |
| tcp | 211.2 |
| probe | 118.6 |
| real_test | 50.4 |
| china_check | 26.0 |
| write_verified | 0.1 |
| generate | 23.6 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 85950 |
| vmess | 21188 |
| shadowsocks | 17338 |
| trojan | 15352 |
| hysteria2 | 1982 |
| http | 312 |
| shadowsocksr | 270 |
| socks | 159 |
| hysteria | 47 |
| anytls | 43 |
| tuic | 43 |

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
| 71.11 | shadowsocks | 235.6 | 608.9 | 22.32 | 0.0 | 0.0 | 13.55 | 19.24 | dragon | 156.146.38.167 |
| 71.04 | shadowsocks | 238.6 | 591.4 | 22.25 | 0.0 | 0.0 | 13.55 | 19.24 | dragon | 156.146.38.170 |
| 70.96 | http | 332.1 | 859.1 | 20.09 | 0.0 | 0.0 | 14.09 | 19.28 | ermaozi | 23.133.176.14 |
| 70.92 | shadowsocks | 243.9 | 638.8 | 22.13 | 0.0 | 0.0 | 13.55 | 19.24 | dragon | 156.146.38.168 |
| 69.28 | shadowsocks | 292.2 | 706.7 | 21.01 | 0.0 | 0.0 | 13.55 | 19.24 | dragon | 37.19.198.236 |
| 68.88 | http | 364.7 | 824.4 | 19.34 | 0.0 | 0.0 | 14.09 | 19.28 | ermaozi | 12.202.180.10 |
| 68.84 | shadowsocks | 312.1 | 709.3 | 20.55 | 0.0 | 0.0 | 13.55 | 19.24 | dragon | 185.230.230.18 |
| 68.79 | http | 291.2 | 618.5 | 21.04 | 0.0 | 0.0 | 14.09 | 19.28 | ermaozi | 64.98.50.100 |
| 68.75 | shadowsocks | 299.0 | 726.0 | 20.86 | 0.0 | 0.0 | 13.55 | 19.24 | dragon | 37.19.198.160 |
| 68.44 | shadowsocks | 297.6 | 728.5 | 20.89 | 0.0 | 0.0 | 13.55 | 19.24 | dragon | 216.9.225.189 |
| 68.23 | shadowsocks | 292.2 | 715.8 | 21.01 | 0.0 | 0.0 | 13.55 | 19.24 | dragon | 37.19.198.244 |
| 67.82 | shadowsocks | 248.4 | 615.4 | 22.03 | 0.0 | 0.0 | 13.55 | 19.24 | dragon | 156.146.38.169 |
| 67.81 | shadowsocks | 293.8 | 720.3 | 20.98 | 0.0 | 0.0 | 13.55 | 19.24 | dragon | 37.19.198.243 |
| 67.62 | shadowsocks | 316.7 | 745.4 | 20.45 | 0.0 | 0.0 | 13.55 | 19.24 | dragon | 193.151.163.18 |
| 67.05 | http | 290.5 | 582.9 | 21.05 | 0.0 | 0.0 | 14.09 | 19.28 | ermaozi | 138.199.35.201 |
| 67.02 | http | 294.8 | 596.4 | 20.95 | 0.0 | 0.0 | 14.09 | 19.28 | ermaozi | 138.199.35.206 |
| 67.02 | http | 295.1 | 604.3 | 20.95 | 0.0 | 0.0 | 14.09 | 19.28 | ermaozi | 138.199.35.212 |
| 67.0 | http | 287.9 | 571.1 | 21.11 | 0.0 | 0.0 | 14.09 | 19.28 | ermaozi | 138.199.35.214 |
| 66.97 | http | 290.6 | 582.3 | 21.05 | 0.0 | 0.0 | 14.09 | 19.28 | ermaozi | 138.199.35.208 |
| 66.97 | http | 299.7 | 611.2 | 20.84 | 0.0 | 0.0 | 14.09 | 19.28 | ermaozi | 138.199.35.210 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.962 | 0.949 | 79 | 604 | prefer |
| dragon | 0.896 | 0.82 | 172 | 46036 | prefer |
| zhangkai | 0.637 | 0.917 | 12 | 59 | observe |
| Surfboard-tg-mixed | 0.335 | 1.0 | 1 | 7259 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 112 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4912 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3849 | observe |
| Epodonios-all | 0.255 | None | 0 | 7583 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10206 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5481 | observe |
| barry-far-vless | 0.255 | None | 0 | 5633 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4186 | observe |
| mheidari-all | 0.255 | None | 0 | 24013 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 20 |
| 204 | ClientOSError | - | 8 |
| 204 | TimeoutError | - | 2 |
| cn-block | ClientOSError | - | 1 |
| cn-block | ProxyError | - | 1 |
| geo | ProxyError | - | 1 |
| cn-block | TimeoutError | - | 1 |
| 204 | ProxyError | - | 1 |
| geo | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 91 | 99 | - |
| global | False | 92 | 100 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
