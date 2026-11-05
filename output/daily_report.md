# AutoNodes 每日报告

生成时间：2026-11-05 23:32:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 128359 |
| 去重后节点数 | 59173 |
| TCP 可达数 | 3000 |
| 真测通过数 | 75 |
| verified 输出数 | 75 |
| global 输出数 | 75 |
| all 输出数 | 59173 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.2 |
| fetch | 8.9 |
| generate | 30.6 |
| geo | 1.8 |
| probe | 98.8 |
| real_test | 29.8 |
| tcp | 197.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 52 | 49 | 3 | 94.2% |
| hysteria2 | 19 | 16 | 3 | 84.2% |
| shadowsocks | 21 | 18 | 3 | 85.7% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 85 | 77 | 8 | 90.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 11 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 1 |
| 204:TimeoutError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15158 |
| ConnectionRefusedError | 2528 |
| gaierror | 494 |
| OSError | 337 |
| SSRFBlocked | 4 |
| ConnectionResetError | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.967 | prefer | 51 | 0.961 | 593 |
| dragon | 0.957 | prefer | 128 | 0.883 | 45886 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5039 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2653 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10851 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8690 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6065 |
| barry-far-vless | 0.255 | observe | 0 | None | 6358 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4631 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-oneclickvpnkeys | 0.133 | observe | 1 | 0.0 | 0 | 140 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 421 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 416 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 299 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 277 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 276 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 246 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 241 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 165 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 152 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| dragon | 0.883 | 113 | 15 | 128 |
| ermaozi | 0.961 | 49 | 2 | 51 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45886 | yes | 8.01 | 0 |
| mheidari-all | 14461 | yes | 6.2 | 0 |
| SoliSpirit-all | 10851 | yes | 2.64 | 0 |
| Surfboard-tg-mixed | 8690 | yes | 5.17 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.32 | 0 |
| barry-far-vless | 6358 | yes | 1.59 | 0 |
| Surfboard-tg-vless | 6065 | yes | 3.59 | 0 |
| 10ium-ScrapeCategorize-Vless | 5039 | yes | 1.82 | 0 |
| mahdibland-V2RayAggregator | 4631 | yes | 3.1 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.91 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 11 |
| 204 | 6 |
| speed | 1 |
