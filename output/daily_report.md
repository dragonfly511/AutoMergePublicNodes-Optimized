# AutoNodes 每日报告

生成时间：2026-10-15 18:25:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 3/91 |
| 原始节点数 | 99920 |
| 去重后节点数 | 27707 |
| TCP 可达数 | 3000 |
| 真测通过数 | 89 |
| verified 输出数 | 89 |
| global 输出数 | 93 |
| all 输出数 | 27707 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 31.3 |
| fetch | 7.8 |
| generate | 13.8 |
| geo | 1.7 |
| probe | 108.3 |
| real_test | 68.6 |
| tcp | 89.0 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 67 | 65 | 2 | 97.0% |
| hysteria2 | 11 | 7 | 4 | 63.6% |
| shadowsocks | 118 | 104 | 14 | 88.1% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 10 | 8 | 2 | 80.0% |
| vless | 165 | 94 | 71 | 57.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 47 |
| 204:TimeoutError | 11 |
| speed:ClientOSError | 10 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 7 |
| geo:ClientOSError | 4 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| speed:TimeoutError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7264 |
| ConnectionRefusedError | 1018 |
| OSError | 234 |
| gaierror | 189 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.997 | prefer | 66 | 0.985 | 659 |
| Au1rxx-base64 | 0.772 | prefer | 281 | 0.705 | 1732 |
| mheidari-all | 0.725 | prefer | 19 | 0.684 | 24099 |
| Surfboard-tg-mixed | 0.421 | observe | 6 | 0.667 | 7281 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5089 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 5147 |
| Epodonios-all | 0.255 | observe | 0 | None | 7794 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10078 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5707 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-oneclickvpnkeys | 0.131 | observe | 1 | 0.0 | 0 | 89 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 457 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 348 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 343 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 226 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 204 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 203 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 195 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 173 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 168 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 92 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.667 | 4 | 2 | 6 |
| mheidari-all | 0.684 | 13 | 6 | 19 |
| Au1rxx-base64 | 0.705 | 198 | 83 | 281 |
| ermaozi | 0.985 | 65 | 1 | 66 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24099 | yes | 7.21 | 0 |
| SoliSpirit-all | 10078 | yes | 2.38 | 0 |
| Epodonios-all | 7794 | yes | 6.08 | 0 |
| Surfboard-tg-mixed | 7281 | yes | 5.41 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.73 | 0 |
| barry-far-vless | 5961 | yes | 1.08 | 0 |
| Surfboard-tg-vless | 5707 | yes | 4.21 | 0 |
| DeltaKronecker-all | 5147 | yes | 7.32 | 0 |
| 10ium-ScrapeCategorize-Vless | 5089 | yes | 0.56 | 0 |
| mahdibland-V2RayAggregator | 4235 | yes | 3.48 | 0 |

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
| test_one_timeout | 47 |
| 204 | 21 |
| speed | 11 |
| cn-block | 10 |
| geo | 5 |
