# AutoNodes 每日报告

生成时间：2026-10-31 21:19:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 125151 |
| 去重后节点数 | 57788 |
| TCP 可达数 | 3000 |
| 真测通过数 | 55 |
| verified 输出数 | 55 |
| global 输出数 | 58 |
| all 输出数 | 57788 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 46.2 |
| fetch | 8.2 |
| generate | 27.6 |
| geo | 1.7 |
| probe | 114.8 |
| real_test | 45.5 |
| tcp | 197.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 15 | 14 | 1 | 93.3% |
| hysteria2 | 18 | 15 | 3 | 83.3% |
| shadowsocks | 163 | 138 | 25 | 84.7% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 39 | 33 | 6 | 84.6% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 27 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 3 |
| cn-block:TimeoutError | 2 |
| cn-block:ClientOSError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14735 |
| ConnectionRefusedError | 2264 |
| gaierror | 521 |
| OSError | 352 |
| SSRFBlocked | 2 |
| ConnectionResetError | 1 |
| UnicodeError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.91 | prefer | 228 | 0.833 | 44351 |
| zhangkai | 0.723 | prefer | 13 | 1.0 | 43 |
| ermaozi-get_subscribe | 0.271 | observe | 1 | 1.0 | 412 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4970 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2848 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10505 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7936 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5636 |
| barry-far-vless | 0.255 | observe | 0 | None | 5849 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-oneclickvpnkeys | 0.132 | observe | 1 | 0.0 | 0 | 108 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 2 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 516 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 407 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 402 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 285 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 263 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 262 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 254 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 232 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 227 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 151 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| dragon | 0.833 | 190 | 38 | 228 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 13 | 0 | 13 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44351 | yes | 6.72 | 0 |
| mheidari-all | 14850 | yes | 5.06 | 0 |
| SoliSpirit-all | 10505 | yes | 5.65 | 0 |
| Surfboard-tg-mixed | 7936 | yes | 3.76 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.0 | 0 |
| barry-far-vless | 5849 | yes | 1.11 | 0 |
| Surfboard-tg-vless | 5636 | yes | 3.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 4970 | yes | 2.19 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 2.5 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.71 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 27 |
| 204 | 8 |
| cn-block | 4 |
