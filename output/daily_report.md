# AutoNodes 每日报告

生成时间：2026-11-22 14:23:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127276 |
| 去重后节点数 | 59401 |
| TCP 可达数 | 3000 |
| 真测通过数 | 110 |
| verified 输出数 | 110 |
| global 输出数 | 114 |
| all 输出数 | 59401 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 27.4 |
| fetch | 6.5 |
| generate | 22.6 |
| geo | 1.7 |
| probe | 107.5 |
| real_test | 42.0 |
| tcp | 200.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 10 | 9 | 1 | 90.0% |
| shadowsocks | 213 | 184 | 29 | 86.4% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 1 | 1 | 0 | 100.0% |
| vless | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 18 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 3 |
| 204:ProxyError | 3 |
| speed:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14823 |
| ConnectionRefusedError | 2327 |
| gaierror | 478 |
| OSError | 325 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.975 | prefer | 22 | 1.0 | 415 |
| dragon | 0.935 | prefer | 232 | 0.858 | 44788 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5069 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2671 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11909 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8766 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5701 |
| barry-far-vless | 0.255 | observe | 0 | None | 5881 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4512 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 464 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 459 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 342 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 320 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 319 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 311 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 289 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 284 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 208 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 195 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.5 | 1 | 1 | 2 |
| dragon | 0.858 | 199 | 33 | 232 |
| ermaozi | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44788 | yes | 5.73 | 0 |
| mheidari-all | 14453 | yes | 4.41 | 0 |
| SoliSpirit-all | 11909 | yes | 3.34 | 0 |
| Surfboard-tg-mixed | 8766 | yes | 2.85 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.58 | 0 |
| barry-far-vless | 5881 | yes | 1.01 | 0 |
| Surfboard-tg-vless | 5701 | yes | 2.53 | 0 |
| 10ium-ScrapeCategorize-Vless | 5069 | yes | 1.76 | 0 |
| mahdibland-V2RayAggregator | 4512 | yes | 1.9 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.97 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 18 |
| 204 | 7 |
| cn-block | 7 |
| speed | 2 |
