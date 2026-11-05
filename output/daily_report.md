# AutoNodes 每日报告

生成时间：2026-11-05 14:22:25

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127670 |
| 去重后节点数 | 58320 |
| TCP 可达数 | 3000 |
| 真测通过数 | 51 |
| verified 输出数 | 51 |
| global 输出数 | 51 |
| all 输出数 | 58320 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 23.7 |
| fetch | 5.2 |
| generate | 19.5 |
| geo | 1.5 |
| probe | 71.5 |
| real_test | 25.0 |
| tcp | 202.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| http | 23 | 20 | 3 | 87.0% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 2 | 2 | 0 | 100.0% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 70 | 57 | 13 | 81.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 9 |
| test_one_timeout:15.0s | 5 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| 204:ClientOSError | 1 |
| 204:TimeoutError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14856 |
| ConnectionRefusedError | 2380 |
| gaierror | 565 |
| OSError | 337 |
| SSRFBlocked | 4 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.884 | prefer | 90 | 0.811 | 44959 |
| ermaozi | 0.864 | prefer | 23 | 0.87 | 593 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 8706 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5039 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2653 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10862 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6147 |
| barry-far-vless | 0.255 | observe | 0 | None | 6241 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| ermaozi-get_subscribe | 0.142 | observe | 1 | 0.0 | 0 | 370 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 420 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 415 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 298 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 276 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 275 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 245 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 240 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 164 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 151 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| dragon | 0.811 | 73 | 17 | 90 |
| ermaozi | 0.87 | 20 | 3 | 23 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44959 | yes | 4.49 | 0 |
| mheidari-all | 14729 | yes | 3.1 | 0 |
| SoliSpirit-all | 10862 | yes | 2.36 | 0 |
| Surfboard-tg-mixed | 8706 | yes | 2.35 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.53 | 0 |
| barry-far-vless | 6241 | yes | 1.01 | 0 |
| Surfboard-tg-vless | 6147 | yes | 2.52 | 0 |
| 10ium-ScrapeCategorize-Vless | 5039 | yes | 1.12 | 0 |
| mahdibland-V2RayAggregator | 4612 | yes | 1.15 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.9 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 11 |
| test_one_timeout | 5 |
| cn-block | 2 |
| geo | 2 |
| speed | 1 |
