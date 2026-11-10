# AutoNodes 每日报告

生成时间：2026-11-10 23:04:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127671 |
| 去重后节点数 | 59499 |
| TCP 可达数 | 3000 |
| 真测通过数 | 64 |
| verified 输出数 | 64 |
| global 输出数 | 66 |
| all 输出数 | 59499 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 32.4 |
| fetch | 5.0 |
| generate | 19.3 |
| geo | 1.6 |
| probe | 81.5 |
| real_test | 58.7 |
| tcp | 204.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 70 | 70 | 0 | 100.0% |
| hysteria2 | 19 | 17 | 2 | 89.5% |
| shadowsocks | 222 | 199 | 23 | 89.6% |
| socks | 8 | 3 | 5 | 37.5% |
| trojan | 95 | 90 | 5 | 94.7% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 14 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| cn-block:TimeoutError | 3 |
| speed:ClientOSError | 1 |
| 204:TimeoutError | 1 |
| speed:TimeoutError | 1 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15679 |
| ConnectionRefusedError | 2394 |
| gaierror | 366 |
| OSError | 355 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | prefer | 70 | 1.0 | 619 |
| dragon | 0.976 | prefer | 345 | 0.899 | 45201 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8562 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 13868 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4955 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2620 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11122 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6459 |
| barry-far-vless | 0.255 | observe | 0 | None | 6669 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| chromego_merge | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 435 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 430 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 313 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 291 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 290 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 282 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 260 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 255 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 179 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 166 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.899 | 310 | 35 | 345 |
| mheidari-all | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 70 | 0 | 70 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45201 | yes | 4.42 | 0 |
| mheidari-all | 13868 | yes | 2.93 | 0 |
| SoliSpirit-all | 11122 | yes | 1.98 | 0 |
| Surfboard-tg-mixed | 8562 | yes | 2.22 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.28 | 0 |
| barry-far-vless | 6669 | yes | 0.51 | 0 |
| Surfboard-tg-vless | 6459 | yes | 3.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 4955 | yes | 0.63 | 0 |
| mahdibland-V2RayAggregator | 4595 | yes | 1.63 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.68 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 14 |
| 204 | 10 |
| cn-block | 8 |
| speed | 2 |
| geo | 1 |
