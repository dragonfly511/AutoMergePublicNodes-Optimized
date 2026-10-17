# AutoNodes 每日报告

生成时间：2026-10-17 00:19:07

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 3/90 |
| 原始节点数 | 99510 |
| 去重后节点数 | 27670 |
| TCP 可达数 | 3000 |
| 真测通过数 | 86 |
| verified 输出数 | 86 |
| global 输出数 | 93 |
| all 输出数 | 27670 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 32.1 |
| fetch | 4.7 |
| generate | 8.0 |
| geo | 1.4 |
| probe | 92.7 |
| real_test | 88.6 |
| tcp | 87.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 62 | 61 | 1 | 98.4% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 159 | 152 | 7 | 95.6% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 19 | 15 | 4 | 78.9% |
| vless | 332 | 201 | 131 | 60.5% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 74 |
| speed:ClientOSError | 36 |
| geo:ClientOSError | 14 |
| cn-block:ClientOSError | 7 |
| 204:TimeoutError | 5 |
| cn-block:ProxyError | 5 |
| speed:TimeoutError | 4 |
| geo:ProxyError | 1 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7203 |
| ConnectionRefusedError | 1023 |
| OSError | 234 |
| gaierror | 188 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.992 | prefer | 59 | 0.983 | 618 |
| Au1rxx-base64 | 0.927 | prefer | 364 | 0.849 | 1995 |
| Surfboard-tg-mixed | 0.771 | prefer | 19 | 0.737 | 7187 |
| mheidari-all | 0.494 | observe | 143 | 0.413 | 24025 |
| tg-oneclickvpnkeys | 0.324 | observe | 4 | 0.75 | 103 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5024 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1995 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 4946 |
| Epodonios-all | 0.255 | observe | 0 | None | 7728 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 4 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 462 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 353 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 348 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 231 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 209 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 208 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 200 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 178 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 173 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 97 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.413 | 59 | 84 | 143 |
| Surfboard-tg-mixed | 0.737 | 14 | 5 | 19 |
| tg-oneclickvpnkeys | 0.75 | 3 | 1 | 4 |
| Au1rxx-base64 | 0.849 | 309 | 55 | 364 |
| ermaozi | 0.983 | 58 | 1 | 59 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24025 | yes | 3.49 | 0 |
| SoliSpirit-all | 9883 | yes | 3.54 | 0 |
| Epodonios-all | 7728 | yes | 3.11 | 0 |
| Surfboard-tg-mixed | 7187 | yes | 2.96 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.51 | 0 |
| barry-far-vless | 5904 | yes | 1.8 | 0 |
| Surfboard-tg-vless | 5650 | yes | 2.69 | 0 |
| 10ium-ScrapeCategorize-Vless | 5024 | yes | 1.66 | 0 |
| DeltaKronecker-all | 4946 | yes | 3.88 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 1.94 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 74 |
| speed | 40 |
| geo | 15 |
| cn-block | 12 |
| 204 | 6 |
