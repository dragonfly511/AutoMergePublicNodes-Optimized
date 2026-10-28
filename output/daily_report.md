# AutoNodes 每日报告

生成时间：2026-10-28 04:49:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 15/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 142942 |
| 去重后节点数 | 59073 |
| TCP 可达数 | 3000 |
| 真测通过数 | 91 |
| verified 输出数 | 91 |
| global 输出数 | 92 |
| all 输出数 | 59073 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 30.7 |
| fetch | 6.5 |
| generate | 22.8 |
| geo | 1.6 |
| probe | 102.2 |
| real_test | 39.5 |
| tcp | 205.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 53 | 52 | 1 | 98.1% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 168 | 151 | 17 | 89.9% |
| socks | 9 | 4 | 5 | 44.4% |
| trojan | 16 | 13 | 3 | 81.2% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 19 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 2 |
| geo:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15495 |
| ConnectionRefusedError | 2447 |
| gaierror | 534 |
| OSError | 326 |
| SSRFBlocked | 2 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.974 | prefer | 43 | 0.977 | 467 |
| dragon | 0.953 | prefer | 210 | 0.876 | 45232 |
| zhangkai | 0.62 | observe | 10 | 1.0 | 43 |
| Surfboard-tg-mixed | 0.349 | observe | 3 | 0.667 | 7522 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4988 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3052 |
| Epodonios-all | 0.255 | observe | 0 | None | 8008 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10429 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5538 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 504 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 395 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 390 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 273 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 251 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 250 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 242 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 220 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 215 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 139 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.667 | 2 | 1 | 3 |
| dragon | 0.876 | 184 | 26 | 210 |
| ermaozi-get_subscribe | 0.977 | 42 | 1 | 43 |
| zhangkai | 1.0 | 10 | 0 | 10 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45232 | yes | 5.66 | 0 |
| mheidari-all | 24790 | yes | 3.73 | 0 |
| SoliSpirit-all | 10429 | yes | 3.93 | 0 |
| Epodonios-all | 8008 | yes | 3.13 | 0 |
| Surfboard-tg-mixed | 7522 | yes | 3.01 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.19 | 0 |
| barry-far-vless | 5751 | yes | 0.5 | 0 |
| Surfboard-tg-vless | 5538 | yes | 2.83 | 0 |
| 10ium-ScrapeCategorize-Vless | 4988 | yes | 0.35 | 0 |
| mahdibland-V2RayAggregator | 4500 | yes | 2.23 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 19 |
| 204 | 4 |
| cn-block | 3 |
| geo | 2 |
