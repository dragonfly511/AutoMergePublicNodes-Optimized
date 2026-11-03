# AutoNodes 每日报告

生成时间：2026-11-03 00:50:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 17/0 |
| 清理建议：优先/观察 | 2/89 |
| 原始节点数 | 126970 |
| 去重后节点数 | 58398 |
| TCP 可达数 | 3000 |
| 真测通过数 | 59 |
| verified 输出数 | 59 |
| global 输出数 | 61 |
| all 输出数 | 58398 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 34.8 |
| fetch | 5.1 |
| generate | 18.7 |
| geo | 1.6 |
| probe | 100.2 |
| real_test | 47.7 |
| tcp | 193.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 18 | 17 | 1 | 94.4% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 252 | 231 | 21 | 91.7% |
| socks | 13 | 2 | 11 | 15.4% |
| trojan | 35 | 29 | 6 | 82.9% |
| vless | 1 | 1 | 0 | 100.0% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 26 |
| 204:ProxyError | 6 |
| 204:ClientOSError | 4 |
| 204:TimeoutError | 2 |
| cn-block:ClientOSError | 2 |
| geo:ClientOSError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14555 |
| ConnectionRefusedError | 2289 |
| gaierror | 466 |
| OSError | 351 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.953 | prefer | 322 | 0.876 | 45127 |
| zhangkai | 0.809 | prefer | 17 | 0.941 | 43 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14971 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 139 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4941 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2726 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10707 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8355 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5917 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 413 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 408 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 291 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 260 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 238 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 233 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 157 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 144 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi | 0.5 | 1 | 1 | 2 |
| dragon | 0.876 | 282 | 40 | 322 |
| zhangkai | 0.941 | 16 | 1 | 17 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45127 | yes | 4.48 | 0 |
| mheidari-all | 14971 | yes | 3.16 | 0 |
| SoliSpirit-all | 10707 | yes | 2.26 | 0 |
| Surfboard-tg-mixed | 8355 | yes | 2.27 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.97 | 0 |
| barry-far-vless | 6131 | yes | 0.71 | 0 |
| Surfboard-tg-vless | 5917 | yes | 2.79 | 0 |
| 10ium-ScrapeCategorize-Vless | 4941 | yes | 0.83 | 0 |
| mahdibland-V2RayAggregator | 4734 | yes | 1.29 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.6 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 26 |
| 204 | 12 |
| cn-block | 3 |
| geo | 1 |
