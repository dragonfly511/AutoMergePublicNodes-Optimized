# AutoNodes 每日报告

生成时间：2026-10-19 11:45:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 95360 |
| 去重后节点数 | 26177 |
| TCP 可达数 | 3000 |
| 真测通过数 | 88 |
| verified 输出数 | 88 |
| global 输出数 | 97 |
| all 输出数 | 26177 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 31.1 |
| fetch | 4.0 |
| generate | 7.6 |
| geo | 1.5 |
| probe | 86.3 |
| real_test | 76.7 |
| tcp | 81.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 99 | 97 | 2 | 98.0% |
| hysteria2 | 16 | 11 | 5 | 68.8% |
| shadowsocks | 133 | 123 | 10 | 92.5% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 21 | 12 | 9 | 57.1% |
| vless | 201 | 114 | 87 | 56.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 64 |
| geo:ClientOSError | 15 |
| speed:ClientOSError | 10 |
| cn-block:TimeoutError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ProxyError | 5 |
| 204:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| geo:TimeoutError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6557 |
| ConnectionRefusedError | 1023 |
| OSError | 239 |
| gaierror | 197 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.998 | prefer | 100 | 0.98 | 696 |
| Au1rxx-base64 | 0.819 | prefer | 299 | 0.753 | 1716 |
| mheidari-all | 0.64 | observe | 23 | 0.565 | 23446 |
| Surfboard-tg-mixed | 0.533 | observe | 51 | 0.451 | 6867 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4940 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3294 |
| Epodonios-all | 0.255 | observe | 0 | None | 7331 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9767 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5407 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-PrivateVPNs | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 471 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 362 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 357 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 240 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 218 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 217 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 209 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 187 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 182 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 106 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.451 | 23 | 28 | 51 |
| mheidari-all | 0.565 | 13 | 10 | 23 |
| Au1rxx-base64 | 0.753 | 225 | 74 | 299 |
| ermaozi | 0.98 | 98 | 2 | 100 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23446 | yes | 3.25 | 0 |
| SoliSpirit-all | 9767 | yes | 2.4 | 0 |
| Epodonios-all | 7331 | yes | 2.78 | 0 |
| Surfboard-tg-mixed | 6867 | yes | 1.96 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.22 | 0 |
| barry-far-vless | 5622 | yes | 1.52 | 0 |
| Surfboard-tg-vless | 5407 | yes | 2.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 4940 | yes | 1.82 | 0 |
| mahdibland-V2RayAggregator | 4314 | yes | 1.79 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.07 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 64 |
| geo | 17 |
| cn-block | 13 |
| speed | 10 |
| 204 | 10 |
