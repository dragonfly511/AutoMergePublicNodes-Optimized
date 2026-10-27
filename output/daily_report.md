# AutoNodes 每日报告

生成时间：2026-10-27 22:03:57

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 15/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 142067 |
| 去重后节点数 | 58977 |
| TCP 可达数 | 3000 |
| 真测通过数 | 75 |
| verified 输出数 | 75 |
| global 输出数 | 79 |
| all 输出数 | 58977 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 26.6 |
| fetch | 5.7 |
| generate | 19.6 |
| geo | 1.7 |
| probe | 99.0 |
| real_test | 53.3 |
| tcp | 206.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 28 | 28 | 0 | 100.0% |
| hysteria2 | 18 | 16 | 2 | 88.9% |
| shadowsocks | 188 | 149 | 39 | 79.3% |
| socks | 8 | 5 | 3 | 62.5% |
| trojan | 2 | 2 | 0 | 100.0% |
| vless | 66 | 41 | 25 | 62.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 46 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 4 |
| geo:ClientOSError | 4 |
| 204:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| speed:TimeoutError | 2 |
| cn-block:TimeoutError | 2 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15512 |
| ConnectionRefusedError | 2445 |
| gaierror | 432 |
| OSError | 326 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.988 | prefer | 28 | 1.0 | 535 |
| dragon | 0.839 | prefer | 284 | 0.761 | 45232 |
| Surfboard-tg-mixed | 0.287 | observe | 2 | 0.5 | 7532 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4988 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3052 |
| Epodonios-all | 0.255 | observe | 0 | None | 7530 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10257 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5538 |
| barry-far-vless | 0.255 | observe | 0 | None | 5531 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 503 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 394 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 389 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 272 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 250 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 249 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 241 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 219 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 214 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 138 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.5 | 1 | 1 | 2 |
| dragon | 0.761 | 216 | 68 | 284 |
| ermaozi | 1.0 | 28 | 0 | 28 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45232 | yes | 5.03 | 0 |
| mheidari-all | 24397 | yes | 3.8 | 0 |
| SoliSpirit-all | 10257 | yes | 1.56 | 0 |
| Surfboard-tg-mixed | 7532 | yes | 1.95 | 0 |
| Epodonios-all | 7530 | yes | 3.33 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.07 | 0 |
| Surfboard-tg-vless | 5538 | yes | 2.05 | 0 |
| barry-far-vless | 5531 | yes | 0.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 4988 | yes | 1.21 | 0 |
| mahdibland-V2RayAggregator | 4500 | yes | 1.75 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 46 |
| 204 | 10 |
| cn-block | 7 |
| geo | 4 |
| speed | 2 |
