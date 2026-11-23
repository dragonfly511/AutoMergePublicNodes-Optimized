# AutoNodes 每日报告

生成时间：2026-11-23 23:41:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 123932 |
| 去重后节点数 | 58855 |
| TCP 可达数 | 3000 |
| 真测通过数 | 61 |
| verified 输出数 | 61 |
| global 输出数 | 65 |
| all 输出数 | 58855 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 29.5 |
| fetch | 7.0 |
| generate | 24.5 |
| geo | 1.7 |
| probe | 98.2 |
| real_test | 41.6 |
| tcp | 203.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 26 | 26 | 0 | 100.0% |
| hysteria2 | 9 | 8 | 1 | 88.9% |
| shadowsocks | 215 | 203 | 12 | 94.4% |
| socks | 7 | 5 | 2 | 71.4% |
| trojan | 58 | 54 | 4 | 93.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 9 |
| cn-block:ClientOSError | 4 |
| 204:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:49734: bind: address already in use | 1 |
| 204:ClientOSError | 1 |
| 204:TimeoutError | 1 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14992 |
| ConnectionRefusedError | 2331 |
| gaierror | 493 |
| OSError | 356 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 290 | 0.931 | 43774 |
| ermaozi | 0.982 | prefer | 27 | 1.0 | 420 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 8626 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5064 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11748 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5667 |
| barry-far-vless | 0.255 | observe | 0 | None | 5847 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4514 |
| mheidari-all | 0.255 | observe | 0 | None | 15543 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 467 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 462 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 345 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 323 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 322 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 314 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 292 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 287 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 211 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 198 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.931 | 270 | 20 | 290 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |
| ermaozi | 1.0 | 27 | 0 | 27 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 43774 | yes | 5.84 | 0 |
| mheidari-all | 15543 | yes | 6.26 | 0 |
| SoliSpirit-all | 11748 | yes | 3.69 | 0 |
| Surfboard-tg-mixed | 8626 | yes | 4.03 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.54 | 0 |
| barry-far-vless | 5847 | yes | 0.91 | 0 |
| Surfboard-tg-vless | 5667 | yes | 2.91 | 0 |
| 10ium-ScrapeCategorize-Vless | 5064 | yes | 2.05 | 0 |
| mahdibland-V2RayAggregator | 4514 | yes | 2.37 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.71 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_downtrend_4_runs | verified output decreased for 4 consecutive runs |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 9 |
| cn-block | 5 |
| 204 | 4 |
| sing-box exited 1 | 1 |
| geo | 1 |
