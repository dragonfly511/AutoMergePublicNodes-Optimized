# AutoNodes 每日报告

生成时间：2026-10-17 06:22:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 14/1 |
| 清理建议：优先/观察 | 2/90 |
| 原始节点数 | 99657 |
| 去重后节点数 | 27787 |
| TCP 可达数 | 3000 |
| 真测通过数 | 79 |
| verified 输出数 | 79 |
| global 输出数 | 86 |
| all 输出数 | 27787 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 33.9 |
| fetch | 8.2 |
| generate | 13.9 |
| geo | 1.5 |
| probe | 106.7 |
| real_test | 98.8 |
| tcp | 84.4 |
| write_verified | 0.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 99 | 96 | 3 | 97.0% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 150 | 140 | 10 | 93.3% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 19 | 10 | 9 | 52.6% |
| vless | 298 | 140 | 158 | 47.0% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 113 |
| geo:ClientOSError | 22 |
| speed:ClientOSError | 16 |
| 204:ProxyError | 9 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| cn-block:ProxyError | 4 |
| 204:TimeoutError | 3 |
| speed:ClientPayloadError | 2 |
| speed:ProxyError | 1 |
| geo:ProxyError | 1 |
| geo:TimeoutError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6444 |
| ConnectionRefusedError | 1024 |
| OSError | 236 |
| gaierror | 228 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.999 | prefer | 100 | 0.98 | 702 |
| Au1rxx-base64 | 0.845 | prefer | 364 | 0.766 | 1993 |
| Surfboard-tg-mixed | 0.372 | observe | 46 | 0.283 | 7109 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4986 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1993 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 4946 |
| Epodonios-all | 0.255 | observe | 0 | None | 7630 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10064 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5597 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 4 |
| tg-freeiranianv2rey | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 463 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 354 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 349 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 232 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 210 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 209 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 201 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 179 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 174 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 98 | 连续死亡次数 >= 2 |
| downweight | mheidari-all | 0.219 | 70 | 0.129 | 0 | 已测数量 >= 5 且评分偏低 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.129 | 9 | 61 | 70 |
| Surfboard-tg-mixed | 0.283 | 13 | 33 | 46 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| Au1rxx-base64 | 0.766 | 279 | 85 | 364 |
| ermaozi | 0.98 | 98 | 2 | 100 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24092 | yes | 7.03 | 0 |
| SoliSpirit-all | 10064 | yes | 3.62 | 0 |
| Epodonios-all | 7630 | yes | 6.33 | 0 |
| Surfboard-tg-mixed | 7109 | yes | 5.06 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.21 | 0 |
| barry-far-vless | 5847 | yes | 2.23 | 0 |
| Surfboard-tg-vless | 5597 | yes | 4.5 | 0 |
| 10ium-ScrapeCategorize-Vless | 4986 | yes | 1.81 | 0 |
| DeltaKronecker-all | 4946 | yes | 7.04 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 3.98 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 113 |
| geo | 24 |
| speed | 20 |
| 204 | 17 |
| cn-block | 9 |
