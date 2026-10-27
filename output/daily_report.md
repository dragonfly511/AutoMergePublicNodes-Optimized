# AutoNodes 每日报告

生成时间：2026-10-27 11:54:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 15/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 141936 |
| 去重后节点数 | 59339 |
| TCP 可达数 | 3000 |
| 真测通过数 | 99 |
| verified 输出数 | 99 |
| global 输出数 | 99 |
| all 输出数 | 59339 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.9 |
| fetch | 5.2 |
| generate | 18.6 |
| geo | 1.5 |
| probe | 70.5 |
| real_test | 45.6 |
| tcp | 213.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 86 | 83 | 3 | 96.5% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 4 | 4 | 0 | 100.0% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 49 | 32 | 17 | 65.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 15 |
| 204:TimeoutError | 4 |
| cn-block:TimeoutError | 2 |
| 204:ProxyError | 1 |
| speed:ClientOSError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 16206 |
| ConnectionRefusedError | 2402 |
| OSError | 282 |
| gaierror | 241 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.979 | prefer | 86 | 0.965 | 603 |
| dragon | 0.802 | prefer | 77 | 0.727 | 45531 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4988 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3052 |
| Epodonios-all | 0.255 | observe | 0 | None | 7509 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10244 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7059 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5319 |
| barry-far-vless | 0.255 | observe | 0 | None | 5497 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 501 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 392 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 387 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 270 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 248 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 247 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 239 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 217 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 212 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 136 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.727 | 56 | 21 | 77 |
| ermaozi | 0.965 | 83 | 3 | 86 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45531 | yes | 4.55 | 0 |
| mheidari-all | 24516 | yes | 2.99 | 0 |
| SoliSpirit-all | 10244 | yes | 1.06 | 0 |
| Epodonios-all | 7509 | yes | 1.66 | 0 |
| Surfboard-tg-mixed | 7059 | yes | 2.22 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.85 | 0 |
| barry-far-vless | 5497 | yes | 0.58 | 0 |
| Surfboard-tg-vless | 5319 | yes | 1.91 | 0 |
| 10ium-ScrapeCategorize-Vless | 4988 | yes | 0.8 | 0 |
| mahdibland-V2RayAggregator | 4573 | yes | 1.6 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 15 |
| 204 | 5 |
| cn-block | 3 |
| speed | 1 |
