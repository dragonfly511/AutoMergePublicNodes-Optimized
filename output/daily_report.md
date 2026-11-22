# AutoNodes 每日报告

生成时间：2026-11-22 23:31:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 126801 |
| 去重后节点数 | 58875 |
| TCP 可达数 | 3000 |
| 真测通过数 | 100 |
| verified 输出数 | 100 |
| global 输出数 | 100 |
| all 输出数 | 58875 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 33.7 |
| fetch | 6.1 |
| generate | 20.4 |
| geo | 1.7 |
| probe | 93.4 |
| real_test | 53.4 |
| tcp | 196.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 12 | 6 | 6 | 50.0% |
| http | 23 | 22 | 1 | 95.7% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 240 | 227 | 13 | 94.6% |
| socks | 6 | 5 | 1 | 83.3% |
| trojan | 65 | 63 | 2 | 96.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| speed:ClientOSError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14361 |
| ConnectionRefusedError | 2283 |
| gaierror | 592 |
| OSError | 352 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 334 | 0.931 | 43774 |
| ermaozi | 0.937 | prefer | 23 | 0.957 | 415 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 8701 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5069 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2671 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11823 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5650 |
| barry-far-vless | 0.255 | observe | 0 | None | 5844 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4512 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 1 |
| tg-freeiranianv2rey | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 465 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 460 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 343 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 321 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 320 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 312 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 290 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 285 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 209 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 196 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.931 | 311 | 23 | 334 |
| ermaozi | 0.957 | 22 | 1 | 23 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 43774 | yes | 5.4 | 0 |
| mheidari-all | 15428 | yes | 4.11 | 0 |
| SoliSpirit-all | 11823 | yes | 1.73 | 0 |
| Surfboard-tg-mixed | 8701 | yes | 2.84 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.45 | 0 |
| barry-far-vless | 5844 | yes | 0.65 | 0 |
| Surfboard-tg-vless | 5650 | yes | 2.26 | 0 |
| 10ium-ScrapeCategorize-Vless | 5069 | yes | 0.49 | 0 |
| mahdibland-V2RayAggregator | 4512 | yes | 0.36 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.93 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 13 |
| 204 | 6 |
| cn-block | 4 |
| speed | 1 |
