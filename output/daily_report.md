# AutoNodes 每日报告

生成时间：2026-11-20 06:26:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127466 |
| 去重后节点数 | 59583 |
| TCP 可达数 | 3000 |
| 真测通过数 | 85 |
| verified 输出数 | 85 |
| global 输出数 | 91 |
| all 输出数 | 59583 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 33.2 |
| fetch | 6.4 |
| generate | 24.1 |
| geo | 1.7 |
| probe | 109.3 |
| real_test | 43.4 |
| tcp | 197.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 24 | 0 | 100.0% |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 243 | 218 | 25 | 89.7% |
| socks | 5 | 2 | 3 | 40.0% |
| vless | 25 | 14 | 11 | 56.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 24 |
| cn-block:ClientOSError | 6 |
| 204:TimeoutError | 3 |
| cn-block:TimeoutError | 3 |
| 204:ProxyError | 2 |
| 204:ClientOSError | 1 |
| geo:ClientOSError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14949 |
| ConnectionRefusedError | 2275 |
| gaierror | 493 |
| OSError | 341 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.98 | prefer | 24 | 1.0 | 469 |
| dragon | 0.939 | prefer | 288 | 0.861 | 44987 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4935 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2728 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11813 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5726 |
| barry-far-vless | 0.255 | observe | 0 | None | 6117 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4501 |
| mheidari-all | 0.255 | observe | 0 | None | 14360 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 459 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 454 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 337 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 315 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 314 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 306 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 284 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 279 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 203 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 190 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.0 | 0 | 1 | 1 |
| dragon | 0.861 | 248 | 40 | 288 |
| ermaozi | 1.0 | 24 | 0 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44987 | yes | 5.92 | 0 |
| mheidari-all | 14360 | yes | 4.38 | 0 |
| SoliSpirit-all | 11813 | yes | 1.93 | 0 |
| Surfboard-tg-mixed | 8500 | yes | 3.39 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.92 | 0 |
| barry-far-vless | 6117 | yes | 0.64 | 0 |
| Surfboard-tg-vless | 5726 | yes | 2.95 | 0 |
| 10ium-ScrapeCategorize-Vless | 4935 | yes | 1.31 | 0 |
| mahdibland-V2RayAggregator | 4501 | yes | 2.28 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.16 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 24 |
| cn-block | 9 |
| 204 | 6 |
| geo | 2 |
