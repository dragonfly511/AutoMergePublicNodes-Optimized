# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-24 20:32:59 |
| 运行耗时 | 401.3s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 143049 |
| 去重后节点 | 59962 |
| TCP 可达 | 3000 |
| 真实可用 | 45 |
| Verified 输出 | 45 |
| Global 输出 | 46 |
| All 输出 | 59962 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 5.4 |
| geo | 1.5 |
| tcp | 203.5 |
| probe | 112.7 |
| real_test | 35.8 |
| china_check | 23.1 |
| write_verified | 0.0 |
| generate | 19.2 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 86730 |
| vmess | 21192 |
| shadowsocks | 17165 |
| trojan | 15224 |
| hysteria2 | 1965 |
| shadowsocksr | 269 |
| http | 218 |
| socks | 154 |
| hysteria | 47 |
| tuic | 43 |
| anytls | 42 |

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
| 73.97 | shadowsocks | 228.1 | 589.6 | 22.5 | 0.0 | 2.78 | 13.75 | 18.94 | dragon | 156.146.38.168 |
| 72.78 | shadowsocks | 233.0 | 597.7 | 22.38 | 0.0 | 1.71 | 13.75 | 18.94 | dragon | 156.146.38.170 |
| 71.12 | shadowsocks | 233.8 | 583.9 | 22.36 | 0.0 | 0.5 | 13.75 | 18.94 | dragon | 156.146.38.167 |
| 69.63 | shadowsocks | 299.3 | 728.3 | 20.85 | 0.0 | 0.09 | 13.75 | 18.94 | dragon | 37.19.198.160 |
| 68.9 | shadowsocks | 295.7 | 711.2 | 20.93 | 0.0 | 0.0 | 13.75 | 18.94 | dragon | 37.19.198.244 |
| 68.24 | shadowsocks | 291.8 | 702.0 | 21.02 | 0.0 | 0.04 | 13.75 | 18.94 | dragon | 37.19.198.243 |
| 67.73 | shadowsocks | 352.4 | 886.2 | 19.62 | 0.0 | 0.37 | 13.75 | 18.94 | dragon | 216.9.225.189 |
| 67.49 | shadowsocks | 308.5 | 713.5 | 20.64 | 0.0 | 0.4 | 13.75 | 18.94 | dragon | 185.230.230.18 |
| 67.28 | hysteria2 | 406.2 | 731.2 | 18.37 | 0.0 | 6.48 | 11.25 | 18.94 | dragon | 62.210.124.146 |
| 66.53 | shadowsocks | 327.9 | 654.6 | 20.19 | 0.0 | 0.12 | 13.75 | 18.94 | dragon | 37.19.198.236 |
| 65.82 | shadowsocks | 258.2 | 643.4 | 21.8 | 0.0 | 0.33 | 13.75 | 18.94 | dragon | 156.146.38.169 |
| 65.6 | shadowsocks | 288.2 | 581.5 | 21.11 | 0.0 | 0.31 | 13.75 | 18.94 | dragon | 173.244.56.9 |
| 65.16 | hysteria2 | 502.3 | 958.3 | 16.15 | 0.0 | 6.32 | 11.25 | 18.94 | dragon | 64.188.98.171 |
| 65.01 | shadowsocks | 318.2 | 692.1 | 20.41 | 0.0 | 0.0 | 13.75 | 18.94 | dragon | 193.151.163.18 |
| 64.89 | shadowsocks | 364.2 | 824.7 | 19.35 | 0.0 | 1.33 | 13.75 | 18.94 | dragon | 95.215.201.18 |
| 64.87 | shadowsocks | 543.6 | 1010.9 | 15.2 | 0.0 | 8.93 | 13.75 | 18.94 | dragon | 82.38.31.200 |
| 63.58 | shadowsocks | 542.5 | 965.6 | 15.22 | 0.0 | 8.93 | 13.75 | 18.94 | dragon | 82.38.31.190 |
| 63.56 | shadowsocks | 545.7 | 993.3 | 15.15 | 0.0 | 8.92 | 13.75 | 18.94 | dragon | 82.38.31.214 |
| 63.49 | shadowsocks | 536.4 | 929.2 | 15.36 | 0.0 | 8.93 | 13.75 | 18.94 | dragon | 193.29.139.223 |
| 63.48 | shadowsocks | 416.0 | 1000.1 | 18.15 | 0.0 | 0.36 | 13.75 | 18.94 | dragon | 193.151.160.18 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.983 | 1.0 | 23 | 567 | prefer |
| dragon | 0.918 | 0.842 | 177 | 46036 | prefer |
| mheidari-all | 0.335 | 1.0 | 1 | 24512 | observe |
| tg-oneclickvpnkeys | 0.259 | 1.0 | 1 | 107 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4911 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 3780 | observe |
| Epodonios-all | 0.255 | None | 0 | 7708 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3999 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10157 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5485 | observe |
| barry-far-vless | 0.255 | None | 0 | 5771 | observe |
| mahdibland-V2RayAggregator | 0.255 | None | 0 | 4150 | observe |
| xiaoji235-airport-v2ray-all | 0.255 | None | 0 | 6752 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.24 | None | 0 | 1623 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 20 |
| 204 | ClientOSError | - | 3 |
| 204 | ProxyError | - | 2 |
| cn-block | ClientOSError | - | 2 |
| 204 | TimeoutError | - | 1 |
| cn-block | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 48 | 45 | - |
| global | False | 48 | 46 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
