# AutoNodes 每日报告

生成时间：2026-11-24 22:11:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 122939 |
| 去重后节点数 | 59992 |
| TCP 可达数 | 3000 |
| 真测通过数 | 88 |
| verified 输出数 | 88 |
| global 输出数 | 88 |
| all 输出数 | 59992 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 28.1 |
| fetch | 8.4 |
| generate | 31.9 |
| geo | 1.8 |
| probe | 105.8 |
| real_test | 32.4 |
| tcp | 199.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 10 | 5 | 5 | 50.0% |
| shadowsocks | 220 | 205 | 15 | 93.2% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 18 | 9 | 9 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| 204:ProxyError | 8 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 2 |
| speed:TimeoutError | 2 |
| 204:TimeoutError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15869 |
| ConnectionRefusedError | 2606 |
| gaierror | 864 |
| OSError | 331 |
| SSRFBlocked | 4 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.969 | prefer | 20 | 1.0 | 366 |
| dragon | 0.954 | prefer | 251 | 0.876 | 44710 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14970 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4839 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11536 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8239 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5468 |
| barry-far-vless | 0.255 | observe | 0 | None | 5508 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4546 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 6 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 469 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 464 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 347 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 325 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 324 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 316 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 294 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 289 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 213 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 200 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.876 | 220 | 31 | 251 |
| mheidari-all | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44710 | yes | 7.79 | 0 |
| mheidari-all | 14970 | yes | 3.95 | 0 |
| SoliSpirit-all | 11536 | yes | 2.24 | 0 |
| Surfboard-tg-mixed | 8239 | yes | 4.42 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.98 | 0 |
| barry-far-vless | 5508 | yes | 1.9 | 0 |
| Surfboard-tg-vless | 5468 | yes | 3.37 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 1.3 | 0 |
| mahdibland-V2RayAggregator | 4546 | yes | 2.96 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.63 | 0 |

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
| 204 | 13 |
| test_one_timeout | 13 |
| cn-block | 2 |
| speed | 2 |
| geo | 1 |
