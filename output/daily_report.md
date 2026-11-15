# AutoNodes 每日报告

生成时间：2026-11-15 13:45:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 128342 |
| 去重后节点数 | 59201 |
| TCP 可达数 | 3000 |
| 真测通过数 | 66 |
| verified 输出数 | 66 |
| global 输出数 | 67 |
| all 输出数 | 59201 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.9 |
| fetch | 5.5 |
| generate | 19.2 |
| geo | 1.5 |
| probe | 76.3 |
| real_test | 44.8 |
| tcp | 150.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| http | 21 | 20 | 1 | 95.2% |
| hysteria2 | 9 | 8 | 1 | 88.9% |
| shadowsocks | 205 | 184 | 21 | 89.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 47 | 29 | 18 | 61.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 20 |
| 204:ProxyError | 16 |
| 204:TimeoutError | 2 |
| speed:TimeoutError | 2 |
| cn-block:TimeoutError | 1 |
| cn-block:ClientOSError | 1 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 11682 |
| ConnectionRefusedError | 2496 |
| gaierror | 1829 |
| OSError | 628 |
| SSRFBlocked | 8 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.935 | prefer | 21 | 0.952 | 544 |
| dragon | 0.915 | prefer | 264 | 0.837 | 44363 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4916 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3024 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11628 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8859 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6129 |
| barry-far-vless | 0.255 | observe | 0 | None | 6500 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 448 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 443 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 326 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 304 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 303 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 295 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 273 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 192 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 179 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.837 | 221 | 43 | 264 |
| ermaozi | 0.952 | 20 | 1 | 21 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44363 | yes | 4.9 | 0 |
| mheidari-all | 14652 | yes | 2.6 | 0 |
| SoliSpirit-all | 11628 | yes | 2.09 | 0 |
| Surfboard-tg-mixed | 8859 | yes | 2.76 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.76 | 0 |
| barry-far-vless | 6500 | yes | 0.42 | 0 |
| Surfboard-tg-vless | 6129 | yes | 2.28 | 0 |
| 10ium-ScrapeCategorize-Vless | 4916 | yes | 1.27 | 0 |
| mahdibland-V2RayAggregator | 4584 | yes | 1.47 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.14 | 0 |

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
| test_one_timeout | 20 |
| 204 | 18 |
| speed | 3 |
| cn-block | 2 |
| geo | 1 |
