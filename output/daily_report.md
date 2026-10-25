# AutoNodes 每日报告

生成时间：2026-10-25 20:40:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 15/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 144306 |
| 去重后节点数 | 59799 |
| TCP 可达数 | 3000 |
| 真测通过数 | 92 |
| verified 输出数 | 92 |
| global 输出数 | 92 |
| all 输出数 | 59799 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 31.9 |
| fetch | 4.9 |
| generate | 17.1 |
| geo | 1.5 |
| probe | 107.4 |
| real_test | 45.6 |
| tcp | 200.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 51 | 51 | 0 | 100.0% |
| hysteria2 | 17 | 14 | 3 | 82.4% |
| shadowsocks | 151 | 135 | 16 | 89.4% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 28 | 26 | 2 | 92.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 19 |
| 204:ClientOSError | 1 |
| geo:TimeoutError | 1 |
| speed:TimeoutError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15789 |
| ConnectionRefusedError | 2372 |
| gaierror | 438 |
| OSError | 320 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | prefer | 51 | 1.0 | 575 |
| dragon | 0.964 | prefer | 205 | 0.888 | 45637 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3849 |
| Epodonios-all | 0.255 | observe | 0 | None | 7913 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10415 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7442 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5721 |
| barry-far-vless | 0.255 | observe | 0 | None | 5934 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 496 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 387 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 382 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 265 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 243 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 242 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 234 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 212 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 207 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 131 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.888 | 182 | 23 | 205 |
| ermaozi | 1.0 | 51 | 0 | 51 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45637 | yes | 4.31 | 0 |
| mheidari-all | 24713 | yes | 3.23 | 0 |
| SoliSpirit-all | 10415 | yes | 1.61 | 0 |
| Epodonios-all | 7913 | yes | 1.57 | 0 |
| Surfboard-tg-mixed | 7442 | yes | 2.44 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.0 | 0 |
| barry-far-vless | 5934 | yes | 1.48 | 0 |
| Surfboard-tg-vless | 5721 | yes | 2.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 1.33 | 0 |
| mahdibland-V2RayAggregator | 4177 | yes | 1.67 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 19 |
| 204 | 1 |
| geo | 1 |
| speed | 1 |
| cn-block | 1 |
