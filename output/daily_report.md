# AutoNodes 每日报告

生成时间：2026-11-09 05:23:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 123044 |
| 去重后节点数 | 57994 |
| TCP 可达数 | 3000 |
| 真测通过数 | 80 |
| verified 输出数 | 80 |
| global 输出数 | 81 |
| all 输出数 | 57994 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 29.0 |
| fetch | 8.4 |
| generate | 30.3 |
| geo | 1.7 |
| probe | 114.2 |
| real_test | 35.6 |
| tcp | 189.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 21 | 21 | 0 | 100.0% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 218 | 202 | 16 | 92.7% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 9 | 6 | 3 | 66.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 16 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14314 |
| ConnectionRefusedError | 2299 |
| gaierror | 477 |
| OSError | 316 |
| ConnectionResetError | 4 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.984 | prefer | 248 | 0.907 | 45021 |
| ermaozi | 0.977 | prefer | 21 | 1.0 | 519 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 13820 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5035 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10927 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8133 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5838 |
| barry-far-vless | 0.255 | observe | 0 | None | 6048 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4597 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 431 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 426 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 309 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 287 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 286 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 278 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 256 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 251 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 175 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 162 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.907 | 225 | 23 | 248 |
| mheidari-all | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45021 | yes | 7.83 | 0 |
| mheidari-all | 13820 | yes | 5.6 | 0 |
| SoliSpirit-all | 10927 | yes | 4.93 | 0 |
| Surfboard-tg-mixed | 8133 | yes | 3.85 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.79 | 0 |
| barry-far-vless | 6048 | yes | 2.1 | 0 |
| Surfboard-tg-vless | 5838 | yes | 4.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 5035 | yes | 2.55 | 0 |
| mahdibland-V2RayAggregator | 4597 | yes | 3.17 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.88 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 16 |
| 204 | 4 |
| cn-block | 2 |
| geo | 1 |
