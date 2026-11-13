# AutoNodes 每日报告

生成时间：2026-11-13 05:47:02

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 126823 |
| 去重后节点数 | 58440 |
| TCP 可达数 | 3000 |
| 真测通过数 | 60 |
| verified 输出数 | 60 |
| global 输出数 | 60 |
| all 输出数 | 58440 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.5 |
| fetch | 5.5 |
| generate | 20.2 |
| geo | 1.6 |
| probe | 76.1 |
| real_test | 32.9 |
| tcp | 202.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 28 | 27 | 1 | 96.4% |
| hysteria2 | 11 | 11 | 0 | 100.0% |
| shadowsocks | 24 | 24 | 0 | 100.0% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 92 | 86 | 6 | 93.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ClientOSError | 2 |
| speed:TimeoutError | 2 |
| test_one_timeout:15.0s | 2 |
| cn-block:ProxyError | 1 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14837 |
| ConnectionRefusedError | 2318 |
| gaierror | 487 |
| OSError | 348 |
| SSRFBlocked | 5 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 129 | 0.946 | 44243 |
| ermaozi | 0.957 | prefer | 28 | 0.964 | 594 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 13793 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4998 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2737 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11327 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8675 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6119 |
| barry-far-vless | 0.255 | observe | 0 | None | 6543 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 441 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 436 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 319 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 297 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 296 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 288 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 185 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 172 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.946 | 122 | 7 | 129 |
| ermaozi | 0.964 | 27 | 1 | 28 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44243 | yes | 4.93 | 0 |
| mheidari-all | 13793 | yes | 3.7 | 0 |
| SoliSpirit-all | 11327 | yes | 1.46 | 0 |
| Surfboard-tg-mixed | 8675 | yes | 2.91 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.47 | 0 |
| barry-far-vless | 6543 | yes | 1.66 | 0 |
| Surfboard-tg-vless | 6119 | yes | 2.67 | 0 |
| 10ium-ScrapeCategorize-Vless | 4998 | yes | 1.78 | 0 |
| mahdibland-V2RayAggregator | 4582 | yes | 0.19 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.82 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 3 |
| speed | 2 |
| test_one_timeout | 2 |
| cn-block | 1 |
