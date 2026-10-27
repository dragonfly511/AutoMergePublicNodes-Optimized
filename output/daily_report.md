# AutoNodes 每日报告

生成时间：2026-10-27 17:49:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 15/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 142021 |
| 去重后节点数 | 59416 |
| TCP 可达数 | 3000 |
| 真测通过数 | 62 |
| verified 输出数 | 62 |
| global 输出数 | 63 |
| all 输出数 | 59416 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 21.0 |
| fetch | 8.7 |
| generate | 29.8 |
| geo | 1.7 |
| probe | 126.7 |
| real_test | 52.5 |
| tcp | 200.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 27 | 26 | 1 | 96.3% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 143 | 129 | 14 | 90.2% |
| socks | 8 | 3 | 5 | 37.5% |
| trojan | 38 | 15 | 23 | 39.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 28 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 2 |
| geo:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| cn-block:TimeoutError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15167 |
| ConnectionRefusedError | 2473 |
| gaierror | 591 |
| OSError | 284 |
| SSRFBlocked | 5 |
| ConnectionResetError | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.952 | prefer | 27 | 0.963 | 535 |
| dragon | 0.871 | prefer | 204 | 0.794 | 45531 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4988 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3052 |
| Epodonios-all | 0.255 | observe | 0 | None | 7531 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10393 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7059 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5319 |
| barry-far-vless | 0.255 | observe | 0 | None | 5532 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 502 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 393 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 388 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 271 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 249 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 248 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 240 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 218 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 213 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 137 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.794 | 162 | 42 | 204 |
| ermaozi | 0.963 | 26 | 1 | 27 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45531 | yes | 7.56 | 0 |
| mheidari-all | 24511 | yes | 4.87 | 0 |
| SoliSpirit-all | 10393 | yes | 5.51 | 0 |
| Epodonios-all | 7531 | yes | 5.77 | 0 |
| Surfboard-tg-mixed | 7059 | yes | 3.61 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.02 | 0 |
| barry-far-vless | 5532 | yes | 1.28 | 0 |
| Surfboard-tg-vless | 5319 | yes | 3.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 4988 | yes | 1.62 | 0 |
| mahdibland-V2RayAggregator | 4573 | yes | 2.63 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 28 |
| 204 | 8 |
| cn-block | 4 |
| geo | 3 |
