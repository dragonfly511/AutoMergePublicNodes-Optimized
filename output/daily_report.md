# AutoNodes 每日报告

生成时间：2026-11-10 14:40:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127000 |
| 去重后节点数 | 59063 |
| TCP 可达数 | 3000 |
| 真测通过数 | 77 |
| verified 输出数 | 77 |
| global 输出数 | 78 |
| all 输出数 | 59063 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 32.1 |
| fetch | 8.6 |
| generate | 30.7 |
| geo | 1.7 |
| probe | 107.1 |
| real_test | 45.7 |
| tcp | 204.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 69 | 64 | 5 | 92.8% |
| hysteria2 | 15 | 12 | 3 | 80.0% |
| shadowsocks | 201 | 185 | 16 | 92.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 59 | 48 | 11 | 81.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 15 |
| 204:ProxyError | 6 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 3 |
| geo:ProxyError | 3 |
| 204:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15490 |
| ConnectionRefusedError | 2469 |
| gaierror | 514 |
| OSError | 300 |
| ConnectionResetError | 4 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.968 | prefer | 276 | 0.891 | 44733 |
| ermaozi | 0.94 | prefer | 69 | 0.928 | 619 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| mheidari-all | 0.259 | observe | 3 | 0.333 | 14274 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4955 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2620 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11070 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8433 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6281 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| chromego_merge | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 434 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 429 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 312 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 290 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 289 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 281 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 259 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 254 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 178 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 165 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.333 | 1 | 2 | 3 |
| dragon | 0.891 | 246 | 30 | 276 |
| ermaozi | 0.928 | 64 | 5 | 69 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44733 | yes | 7.8 | 0 |
| mheidari-all | 14274 | yes | 4.85 | 0 |
| SoliSpirit-all | 11070 | yes | 3.07 | 0 |
| Surfboard-tg-mixed | 8433 | yes | 3.99 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.68 | 0 |
| barry-far-vless | 6343 | yes | 1.35 | 0 |
| Surfboard-tg-vless | 6281 | yes | 3.38 | 0 |
| 10ium-ScrapeCategorize-Vless | 4955 | yes | 0.81 | 0 |
| mahdibland-V2RayAggregator | 4667 | yes | 2.96 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.43 | 0 |

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
| test_one_timeout | 15 |
| 204 | 11 |
| speed | 6 |
| geo | 3 |
| cn-block | 2 |
