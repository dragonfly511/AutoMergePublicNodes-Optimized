# AutoNodes 每日报告

生成时间：2026-10-29 22:41:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 143773 |
| 去重后节点数 | 59198 |
| TCP 可达数 | 3000 |
| 真测通过数 | 69 |
| verified 输出数 | 69 |
| global 输出数 | 70 |
| all 输出数 | 59198 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 27.5 |
| fetch | 6.8 |
| generate | 23.0 |
| geo | 1.6 |
| probe | 98.3 |
| real_test | 39.9 |
| tcp | 201.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 21 | 21 | 0 | 100.0% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 170 | 152 | 18 | 89.4% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 26 | 23 | 3 | 88.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 18 |
| 204:ProxyError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 2 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15327 |
| ConnectionRefusedError | 2419 |
| gaierror | 517 |
| OSError | 324 |
| SSRFBlocked | 3 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.977 | prefer | 21 | 1.0 | 510 |
| dragon | 0.957 | prefer | 218 | 0.881 | 44588 |
| Au1rxx-base64 | 0.324 | observe | 1 | 1.0 | 1725 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2709 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10379 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7758 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5789 |
| barry-far-vless | 0.255 | observe | 0 | None | 6033 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 509 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 400 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 395 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 278 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 256 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 255 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 247 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 225 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 220 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 144 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.881 | 192 | 26 | 218 |
| Au1rxx-base64 | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44588 | yes | 6.05 | 0 |
| mheidari-all | 33474 | yes | 4.47 | 0 |
| SoliSpirit-all | 10379 | yes | 2.93 | 0 |
| Surfboard-tg-mixed | 7758 | yes | 2.99 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.78 | 0 |
| barry-far-vless | 6033 | yes | 0.72 | 0 |
| Surfboard-tg-vless | 5789 | yes | 2.81 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 0.87 | 0 |
| mahdibland-V2RayAggregator | 4444 | yes | 0.27 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.84 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 18 |
| 204 | 6 |
| cn-block | 2 |
