# AutoNodes 每日报告

生成时间：2026-10-17 12:19:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 1/92 |
| 原始节点数 | 99736 |
| 去重后节点数 | 27780 |
| TCP 可达数 | 3000 |
| 真测通过数 | 92 |
| verified 输出数 | 92 |
| global 输出数 | 96 |
| all 输出数 | 27780 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 27.4 |
| fetch | 8.3 |
| generate | 14.2 |
| geo | 1.5 |
| probe | 126.8 |
| real_test | 80.5 |
| tcp | 87.4 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 100 | 43 | 57 | 43.0% |
| hysteria2 | 11 | 9 | 2 | 81.8% |
| shadowsocks | 138 | 115 | 23 | 83.3% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 28 | 10 | 18 | 35.7% |
| vless | 199 | 110 | 89 | 55.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 88 |
| 204:ProxyError | 56 |
| speed:ClientOSError | 12 |
| geo:ClientOSError | 10 |
| 204:TimeoutError | 8 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 1 |
| cn-block:TimeoutError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6765 |
| ConnectionRefusedError | 1026 |
| OSError | 236 |
| gaierror | 185 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.788 | prefer | 317 | 0.71 | 1994 |
| ermaozi | 0.474 | observe | 99 | 0.444 | 702 |
| Surfboard-tg-mixed | 0.421 | observe | 39 | 0.333 | 7171 |
| mheidari-all | 0.373 | observe | 5 | 0.6 | 23889 |
| DeltaKronecker-all | 0.365 | observe | 17 | 0.294 | 4999 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4986 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1994 |
| Epodonios-all | 0.255 | observe | 0 | None | 7611 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10247 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 464 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 355 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 350 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 233 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 211 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 210 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 202 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 180 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 175 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 99 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.294 | 5 | 12 | 17 |
| tg-oneclickvpnkeys | 0.333 | 1 | 2 | 3 |
| Surfboard-tg-mixed | 0.333 | 13 | 26 | 39 |
| ermaozi | 0.444 | 44 | 55 | 99 |
| mheidari-all | 0.6 | 3 | 2 | 5 |
| Au1rxx-base64 | 0.71 | 225 | 92 | 317 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23889 | yes | 7.16 | 0 |
| SoliSpirit-all | 10247 | yes | 4.87 | 0 |
| Epodonios-all | 7611 | yes | 7.39 | 0 |
| Surfboard-tg-mixed | 7171 | yes | 5.32 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.72 | 0 |
| barry-far-vless | 5866 | yes | 3.21 | 0 |
| Surfboard-tg-vless | 5617 | yes | 5.06 | 0 |
| DeltaKronecker-all | 4999 | yes | 7.48 | 0 |
| 10ium-ScrapeCategorize-Vless | 4986 | yes | 2.91 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 4.06 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 88 |
| 204 | 69 |
| speed | 16 |
| geo | 11 |
| cn-block | 7 |
