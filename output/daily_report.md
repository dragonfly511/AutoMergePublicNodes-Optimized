# AutoNodes 每日报告

生成时间：2026-10-21 16:27:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 4/89 |
| 原始节点数 | 96616 |
| 去重后节点数 | 26908 |
| TCP 可达数 | 3000 |
| 真测通过数 | 89 |
| verified 输出数 | 89 |
| global 输出数 | 94 |
| all 输出数 | 26908 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 21.6 |
| fetch | 7.2 |
| generate | 13.7 |
| geo | 1.6 |
| probe | 101.1 |
| real_test | 62.6 |
| tcp | 82.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 41 | 39 | 2 | 95.1% |
| hysteria2 | 14 | 11 | 3 | 78.6% |
| shadowsocks | 133 | 124 | 9 | 93.2% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 27 | 14 | 13 | 51.9% |
| vless | 109 | 61 | 48 | 56.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 41 |
| speed:ClientOSError | 8 |
| cn-block:TimeoutError | 6 |
| geo:ClientOSError | 5 |
| 204:TimeoutError | 5 |
| cn-block:ClientOSError | 4 |
| 204:ProxyError | 3 |
| 204:ClientOSError | 2 |
| geo:TimeoutError | 2 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6579 |
| ConnectionRefusedError | 1047 |
| OSError | 236 |
| gaierror | 212 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.932 | prefer | 27 | 0.963 | 31 |
| Surfboard-tg-mixed | 0.875 | prefer | 42 | 0.81 | 7070 |
| mheidari-all | 0.827 | prefer | 81 | 0.753 | 24102 |
| Au1rxx-base64 | 0.774 | prefer | 157 | 0.713 | 1579 |
| ermaozi-get_subscribe | 0.668 | observe | 11 | 1.0 | 385 |
| Au1rxx-clash | 0.383 | observe | 4 | 0.75 | 1568 |
| ninja-vless | 0.327 | observe | 1 | 1.0 | 1791 |
| tg-oneclickvpnkeys | 0.273 | observe | 3 | 0.667 | 108 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4925 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 5 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 479 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 370 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 365 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 248 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 226 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 225 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 217 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 195 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 190 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 114 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.713 | 112 | 45 | 157 |
| Au1rxx-clash | 0.75 | 3 | 1 | 4 |
| mheidari-all | 0.753 | 61 | 20 | 81 |
| Surfboard-tg-mixed | 0.81 | 34 | 8 | 42 |
| zhangkai | 0.963 | 26 | 1 | 27 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ninja-vless | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 11 | 0 | 11 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24102 | yes | 5.54 | 0 |
| SoliSpirit-all | 10165 | yes | 5.47 | 0 |
| Epodonios-all | 7559 | yes | 4.89 | 0 |
| Surfboard-tg-mixed | 7070 | yes | 4.37 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 5.1 | 0 |
| barry-far-vless | 5768 | yes | 2.8 | 0 |
| Surfboard-tg-vless | 5554 | yes | 4.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 4925 | yes | 2.01 | 0 |
| mahdibland-V2RayAggregator | 4127 | yes | 0.65 | 0 |
| DeltaKronecker-all | 4067 | yes | 6.16 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 41 |
| 204 | 10 |
| cn-block | 10 |
| speed | 9 |
| geo | 7 |
