# AutoNodes 健康报告

## 总览

| 指标 | 数值 |
| --- | --- |
| 版本 | 2.4.0 |
| 更新时间 | 2026-10-31 17:05:53 |
| 运行耗时 | 389.5s |
| 订阅源总数 | 108 |
| 健康订阅源 | 89 |
| 原始节点 | 126231 |
| 去重后节点 | 58844 |
| TCP 可达 | 3000 |
| 真实可用 | 45 |
| Verified 输出 | 45 |
| Global 输出 | 46 |
| All 输出 | 58844 |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| fetch | 9.0 |
| geo | 1.7 |
| tcp | 206.8 |
| probe | 97.4 |
| real_test | 26.1 |
| china_check | 18.2 |
| write_verified | 0.0 |
| generate | 30.3 |

## 协议分布

| 协议 | 数量 |
| --- | --- |
| vless | 76338 |
| vmess | 17930 |
| trojan | 16738 |
| shadowsocks | 12394 |
| hysteria2 | 2209 |
| shadowsocksr | 250 |
| http | 162 |
| socks | 91 |
| tuic | 51 |
| hysteria | 40 |
| anytls | 28 |

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
| 79.78 | trojan | 179.9 | 488.7 | 23.61 | 0.0 | 10.0 | 12.27 | 17.4 | dragon | 167.88.61.20 |
| 71.02 | trojan | 302.7 | 705.6 | 20.77 | 0.0 | 4.04 | 12.27 | 17.4 | dragon | 66.163.114.45 |
| 70.35 | trojan | 245.1 | 579.3 | 22.1 | 0.0 | 1.08 | 12.27 | 17.4 | dragon | 216.106.186.32 |
| 68.49 | trojan | 235.6 | 544.8 | 22.32 | 0.0 | 0.0 | 12.27 | 17.4 | dragon | 66.163.112.31 |
| 67.1 | trojan | 241.1 | 556.0 | 22.2 | 0.0 | 7.2 | 12.27 | 17.4 | dragon | 66.163.112.142 |
| 65.72 | trojan | 182.6 | 494.0 | 23.55 | 0.0 | 0.0 | 12.27 | 17.4 | dragon | 167.88.61.175 |
| 65.2 | trojan | 493.1 | 601.5 | 16.36 | 0.0 | 6.78 | 12.27 | 17.4 | dragon | 216.106.186.33 |
| 64.64 | trojan | 508.0 | 1246.0 | 16.02 | 0.0 | 6.73 | 12.27 | 17.4 | dragon | 66.23.203.21 |
| 63.87 | trojan | 296.3 | 668.1 | 20.92 | 0.0 | 0.0 | 12.27 | 17.4 | dragon | us003.421421.xyz |
| 63.07 | trojan | 176.1 | 476.4 | 23.7 | 0.0 | 0.08 | 12.27 | 17.4 | dragon | 167.88.61.85 |
| 61.97 | trojan | 241.3 | 559.4 | 22.19 | 0.0 | 1.11 | 12.27 | 17.4 | dragon | 66.163.112.242 |
| 60.73 | trojan | 404.8 | 814.8 | 18.41 | 0.0 | 6.32 | 12.27 | 17.4 | dragon | 130.94.19.95 |
| 60.7 | trojan | 617.4 | 929.7 | 13.49 | 0.0 | 6.97 | 12.27 | 17.4 | dragon | 162.159.244.91 |
| 60.12 | hysteria2 | 562.7 | 1000.4 | 14.75 | 0.0 | 4.14 | 12.19 | 17.4 | dragon | 130.49.161.70 |
| 59.87 | trojan | 658.4 | 1006.8 | 12.54 | 0.0 | 6.98 | 12.27 | 17.4 | dragon | 104.18.37.228 |
| 59.86 | trojan | 623.1 | 932.9 | 13.35 | 0.0 | 7.14 | 12.27 | 17.4 | dragon | 45.130.125.75 |
| 59.48 | trojan | 641.7 | 951.8 | 12.92 | 0.0 | 6.09 | 12.27 | 17.4 | dragon | 104.17.121.9 |
| 59.47 | trojan | 626.5 | 921.6 | 13.28 | 0.0 | 7.8 | 12.27 | 17.4 | dragon | 104.27.0.1 |
| 59.36 | trojan | 633.3 | 889.6 | 13.12 | 0.0 | 7.84 | 12.27 | 17.4 | dragon | 104.25.240.193 |
| 59.21 | trojan | 422.3 | 823.6 | 18.0 | 0.0 | 0.0 | 12.27 | 17.4 | dragon | 169.197.140.169 |

## 来源质量排行

| 来源 | 评分 | 通过率 | 测试数 | 解析节点 | 建议 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.836 | 0.761 | 88 | 44960 | prefer |
| zhangkai | 0.402 | 1.0 | 4 | 43 | observe |
| xiaoji235-airport-v2ray-all | 0.335 | 1.0 | 1 | 6752 | observe |
| 10ium-ScrapeCategorize-Vless | 0.255 | None | 0 | 4970 | observe |
| DeltaKronecker-all | 0.255 | None | 0 | 2848 | observe |
| MatinGhanbari-all-sub | 0.255 | None | 0 | 3998 | observe |
| SoliSpirit-all | 0.255 | None | 0 | 10683 | observe |
| Surfboard-tg-mixed | 0.255 | None | 0 | 7984 | observe |
| Surfboard-tg-vless | 0.255 | None | 0 | 5777 | observe |
| barry-far-vless | 0.255 | None | 0 | 5990 | observe |
| mheidari-all | 0.255 | None | 0 | 14848 | observe |
| ninja-vless | 0.247 | None | 0 | 1791 | observe |
| Au1rxx-base64 | 0.245 | None | 0 | 1751 | observe |
| Au1rxx-clash | 0.245 | None | 0 | 1751 | observe |
| moneyfly1-collectSub | 0.222 | None | 0 | 1164 | observe |

## 真实测试失败原因

| 目标 | 原因 | 状态/值 | 数量 |
| --- | --- | --- | --- |
| test_one_timeout | 15.0s | - | 12 |
| 204 | ProxyError | - | 6 |
| cn-block | ProxyError | - | 2 |
| 204 | ClientOSError | - | 1 |
| geo | ClientOSError | - | 1 |
| 204 | TimeoutError | - | 1 |

## 输出保护

| 前缀 | 是否保留旧输出 | 上一轮数量 | 本轮建议数量 | 保护比例 |
| --- | --- | --- | --- | --- |
| verified | False | 100 | 45 | - |
| global | False | 102 | 46 | - |

---

此文件由 `core.report.write_health_report()` 自动生成。
