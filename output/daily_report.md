# AutoNodes 每日报告

生成时间：2026-10-25 11:05:29

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 15/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 142684 |
| 去重后节点数 | 60342 |
| TCP 可达数 | 3000 |
| 真测通过数 | 99 |
| verified 输出数 | 99 |
| global 输出数 | 100 |
| all 输出数 | 60342 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 26.0 |
| fetch | 6.8 |
| generate | 23.6 |
| geo | 1.6 |
| probe | 118.6 |
| real_test | 50.4 |
| tcp | 211.2 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 91 | 87 | 4 | 95.6% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 142 | 119 | 23 | 83.8% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 10 | 6 | 4 | 60.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 20 |
| 204:ClientOSError | 8 |
| 204:TimeoutError | 2 |
| cn-block:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |
| cn-block:TimeoutError | 1 |
| 204:ProxyError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 16076 |
| ConnectionRefusedError | 2469 |
| gaierror | 441 |
| OSError | 321 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.962 | prefer | 79 | 0.949 | 604 |
| dragon | 0.896 | prefer | 172 | 0.82 | 46036 |
| zhangkai | 0.637 | observe | 12 | 0.917 | 59 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 7259 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 112 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3849 |
| Epodonios-all | 0.255 | observe | 0 | None | 7583 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10206 |

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
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 494 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 385 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 380 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 263 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 241 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 240 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 232 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 210 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 205 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 129 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.82 | 141 | 31 | 172 |
| zhangkai | 0.917 | 11 | 1 | 12 |
| ermaozi | 0.949 | 75 | 4 | 79 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 46036 | yes | 6.11 | 0 |
| mheidari-all | 24013 | yes | 4.54 | 0 |
| SoliSpirit-all | 10206 | yes | 3.62 | 0 |
| Epodonios-all | 7583 | yes | 3.94 | 0 |
| Surfboard-tg-mixed | 7259 | yes | 3.01 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.39 | 0 |
| barry-far-vless | 5633 | yes | 0.65 | 0 |
| Surfboard-tg-vless | 5481 | yes | 2.63 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 2.24 | 0 |
| mahdibland-V2RayAggregator | 4186 | yes | 2.21 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 20 |
| 204 | 11 |
| cn-block | 3 |
| geo | 2 |
