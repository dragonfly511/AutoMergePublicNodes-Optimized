# AutoNodes 每日报告

生成时间：2026-11-21 06:16:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127232 |
| 去重后节点数 | 59084 |
| TCP 可达数 | 3000 |
| 真测通过数 | 91 |
| verified 输出数 | 91 |
| global 输出数 | 93 |
| all 输出数 | 59084 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 28.8 |
| fetch | 6.4 |
| generate | 23.1 |
| geo | 1.6 |
| probe | 109.4 |
| real_test | 74.5 |
| tcp | 195.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 11 | 7 | 4 | 63.6% |
| http | 25 | 25 | 0 | 100.0% |
| hysteria2 | 13 | 10 | 3 | 76.9% |
| shadowsocks | 238 | 162 | 76 | 68.1% |
| socks | 9 | 7 | 2 | 77.8% |
| trojan | 3 | 3 | 0 | 100.0% |
| vless | 6 | 5 | 1 | 83.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 70 |
| cn-block:TimeoutError | 6 |
| 204:ClientOSError | 5 |
| cn-block:ClientOSError | 3 |
| speed:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14425 |
| ConnectionRefusedError | 2270 |
| gaierror | 575 |
| OSError | 321 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.979 | prefer | 24 | 1.0 | 443 |
| dragon | 0.769 | prefer | 278 | 0.691 | 44818 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 8565 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14439 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 115 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5045 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2910 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11818 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5496 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 461 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 456 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 339 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 317 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 316 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 308 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 286 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 281 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 205 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 192 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.691 | 192 | 86 | 278 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |
| ermaozi | 1.0 | 24 | 0 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44818 | yes | 5.39 | 0 |
| mheidari-all | 14439 | yes | 3.94 | 0 |
| SoliSpirit-all | 11818 | yes | 3.84 | 0 |
| Surfboard-tg-mixed | 8565 | yes | 2.85 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.75 | 0 |
| barry-far-vless | 5914 | yes | 0.66 | 0 |
| Surfboard-tg-vless | 5496 | yes | 2.99 | 0 |
| 10ium-ScrapeCategorize-Vless | 5045 | yes | 0.82 | 0 |
| mahdibland-V2RayAggregator | 4518 | yes | 2.21 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.19 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 70 |
| cn-block | 9 |
| 204 | 5 |
| speed | 2 |
