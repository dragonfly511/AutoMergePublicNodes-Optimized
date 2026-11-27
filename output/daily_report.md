# AutoNodes 每日报告

生成时间：2026-11-27 07:30:11

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 123429 |
| 去重后节点数 | 58453 |
| TCP 可达数 | 3000 |
| 真测通过数 | 80 |
| verified 输出数 | 80 |
| global 输出数 | 83 |
| all 输出数 | 58453 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 34.9 |
| fetch | 8.5 |
| generate | 29.9 |
| geo | 1.4 |
| probe | 110.6 |
| real_test | 68.1 |
| tcp | 210.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 42 | 41 | 1 | 97.6% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 286 | 233 | 53 | 81.5% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 53 | 50 | 3 | 94.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 37 |
| speed:TimeoutError | 11 |
| cn-block:ClientOSError | 7 |
| speed:ProxyError | 1 |
| 204:TimeoutError | 1 |
| 204:ProxyError | 1 |
| speed:ClientOSError | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 17281 |
| ConnectionRefusedError | 2494 |
| gaierror | 386 |
| OSError | 343 |
| SSRFBlocked | 4 |
| ConnectionResetError | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.971 | prefer | 42 | 0.976 | 422 |
| dragon | 0.912 | prefer | 356 | 0.834 | 45062 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8568 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 103 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4936 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11568 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5426 |
| barry-far-vless | 0.255 | observe | 0 | None | 5609 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4448 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 474 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 469 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 352 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 330 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 329 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 321 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 299 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 294 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 218 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 205 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.834 | 297 | 59 | 356 |
| ermaozi | 0.976 | 41 | 1 | 42 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45062 | yes | 7.62 | 0 |
| mheidari-all | 14315 | yes | 5.81 | 0 |
| SoliSpirit-all | 11568 | yes | 2.4 | 0 |
| Surfboard-tg-mixed | 8568 | yes | 3.68 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.92 | 0 |
| barry-far-vless | 5609 | yes | 0.97 | 0 |
| Surfboard-tg-vless | 5426 | yes | 3.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 4936 | yes | 1.2 | 0 |
| mahdibland-V2RayAggregator | 4448 | yes | 3.16 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.0 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 37 |
| speed | 13 |
| cn-block | 7 |
| 204 | 2 |
| geo | 1 |
