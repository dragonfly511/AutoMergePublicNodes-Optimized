# AutoNodes 每日报告

生成时间：2026-11-25 21:25:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 122532 |
| 去重后节点数 | 59075 |
| TCP 可达数 | 3000 |
| 真测通过数 | 92 |
| verified 输出数 | 92 |
| global 输出数 | 96 |
| all 输出数 | 59075 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 35.7 |
| fetch | 5.5 |
| generate | 18.6 |
| geo | 1.5 |
| probe | 84.6 |
| real_test | 47.4 |
| tcp | 185.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 24 | 22 | 2 | 91.7% |
| hysteria2 | 8 | 6 | 2 | 75.0% |
| shadowsocks | 200 | 176 | 24 | 88.0% |
| socks | 5 | 4 | 1 | 80.0% |
| vless | 54 | 50 | 4 | 92.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 14 |
| 204:ClientOSError | 8 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14763 |
| ConnectionRefusedError | 2602 |
| gaierror | 1212 |
| OSError | 678 |
| SSRFBlocked | 3 |
| ConnectionResetError | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.974 | prefer | 22 | 1.0 | 403 |
| dragon | 0.961 | prefer | 267 | 0.884 | 43982 |
| tg-LonUp_M | 0.318 | observe | 2 | 1.0 | 171 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4958 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11598 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8209 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5378 |
| barry-far-vless | 0.255 | observe | 0 | None | 5559 |
| mheidari-all | 0.255 | observe | 0 | None | 15044 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 471 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 466 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 349 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 327 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 326 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 318 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 296 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 291 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 215 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 202 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mahdibland-V2RayAggregator | 0.0 | 0 | 2 | 2 |
| dragon | 0.884 | 236 | 31 | 267 |
| tg-LonUp_M | 1.0 | 2 | 0 | 2 |
| ermaozi | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 43982 | yes | 4.81 | 0 |
| mheidari-all | 15044 | yes | 3.62 | 0 |
| SoliSpirit-all | 11598 | yes | 1.55 | 0 |
| Surfboard-tg-mixed | 8209 | yes | 2.2 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.32 | 0 |
| barry-far-vless | 5559 | yes | 0.6 | 0 |
| Surfboard-tg-vless | 5378 | yes | 2.04 | 0 |
| 10ium-ScrapeCategorize-Vless | 4958 | yes | 0.8 | 0 |
| mahdibland-V2RayAggregator | 4463 | yes | 1.78 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.66 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 14 |
| test_one_timeout | 14 |
| cn-block | 5 |
