# AutoNodes 每日报告

生成时间：2026-10-16 12:25:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 2/92 |
| 原始节点数 | 99281 |
| 去重后节点数 | 27679 |
| TCP 可达数 | 3000 |
| 真测通过数 | 93 |
| verified 输出数 | 93 |
| global 输出数 | 99 |
| all 输出数 | 27679 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 32.3 |
| fetch | 4.3 |
| generate | 7.7 |
| geo | 1.4 |
| probe | 105.6 |
| real_test | 83.4 |
| tcp | 87.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 92 | 89 | 3 | 96.7% |
| hysteria2 | 17 | 13 | 4 | 76.5% |
| shadowsocks | 148 | 128 | 20 | 86.5% |
| trojan | 17 | 6 | 11 | 35.3% |
| vless | 209 | 104 | 105 | 49.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 85 |
| speed:ClientOSError | 15 |
| 204:TimeoutError | 10 |
| geo:ClientOSError | 8 |
| cn-block:ClientOSError | 7 |
| cn-block:ProxyError | 6 |
| 204:ProxyError | 5 |
| cn-block:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| speed:TimeoutError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7133 |
| ConnectionRefusedError | 1026 |
| OSError | 238 |
| gaierror | 176 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.995 | prefer | 90 | 0.978 | 693 |
| Au1rxx-base64 | 0.754 | prefer | 345 | 0.675 | 1990 |
| mheidari-all | 0.474 | observe | 15 | 0.467 | 23871 |
| Surfboard-tg-mixed | 0.455 | observe | 30 | 0.367 | 7090 |
| DeltaKronecker-all | 0.349 | observe | 3 | 0.667 | 4946 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5024 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1990 |
| Epodonios-all | 0.255 | observe | 0 | None | 7568 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10091 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 460 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 351 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 346 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 229 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 207 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 206 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 198 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 176 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 171 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 95 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.367 | 11 | 19 | 30 |
| mheidari-all | 0.467 | 7 | 8 | 15 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| DeltaKronecker-all | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.675 | 233 | 112 | 345 |
| ermaozi | 0.978 | 88 | 2 | 90 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23871 | yes | 3.21 | 0 |
| SoliSpirit-all | 10091 | yes | 3.57 | 0 |
| Epodonios-all | 7568 | yes | 3.44 | 0 |
| Surfboard-tg-mixed | 7090 | yes | 2.78 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.7 | 0 |
| barry-far-vless | 5827 | yes | 1.35 | 0 |
| Surfboard-tg-vless | 5572 | yes | 2.61 | 0 |
| 10ium-ScrapeCategorize-Vless | 5024 | yes | 2.5 | 0 |
| DeltaKronecker-all | 4946 | yes | 3.77 | 0 |
| mahdibland-V2RayAggregator | 4265 | yes | 0.87 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 85 |
| 204 | 17 |
| speed | 16 |
| cn-block | 16 |
| geo | 9 |
