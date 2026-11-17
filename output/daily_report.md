# AutoNodes 每日报告

生成时间：2026-11-17 15:47:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 126636 |
| 去重后节点数 | 58509 |
| TCP 可达数 | 3000 |
| 真测通过数 | 77 |
| verified 输出数 | 77 |
| global 输出数 | 77 |
| all 输出数 | 58509 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.5 |
| fetch | 5.2 |
| generate | 19.3 |
| geo | 1.5 |
| probe | 101.9 |
| real_test | 41.3 |
| tcp | 196.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 23 | 20 | 3 | 87.0% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 205 | 181 | 24 | 88.3% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 12 | 5 | 7 | 41.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 19 |
| speed:TimeoutError | 5 |
| 204:ProxyError | 5 |
| 204:TimeoutError | 2 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| geo:ClientOSError | 1 |
| cn-block:ClientOSError | 1 |
| speed:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14653 |
| ConnectionRefusedError | 2217 |
| gaierror | 510 |
| OSError | 332 |
| SSRFBlocked | 5 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.931 | prefer | 233 | 0.854 | 44193 |
| ermaozi | 0.854 | prefer | 22 | 0.864 | 517 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4601 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14572 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 172 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4928 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2790 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11523 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8546 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 453 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 448 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 331 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 309 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 308 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 300 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 278 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 273 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 197 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 184 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.854 | 199 | 34 | 233 |
| ermaozi | 0.864 | 19 | 3 | 22 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44193 | yes | 4.49 | 0 |
| mheidari-all | 14572 | yes | 3.35 | 0 |
| SoliSpirit-all | 11523 | yes | 2.26 | 0 |
| Surfboard-tg-mixed | 8546 | yes | 2.02 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.36 | 0 |
| barry-far-vless | 6032 | yes | 0.53 | 0 |
| Surfboard-tg-vless | 5851 | yes | 2.31 | 0 |
| 10ium-ScrapeCategorize-Vless | 4928 | yes | 1.58 | 0 |
| mahdibland-V2RayAggregator | 4601 | yes | 0.34 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.42 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 19 |
| 204 | 8 |
| speed | 6 |
| cn-block | 2 |
| geo | 2 |
