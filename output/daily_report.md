# AutoNodes 每日报告

生成时间：2026-11-28 07:00:51

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 122089 |
| 去重后节点数 | 57725 |
| TCP 可达数 | 3000 |
| 真测通过数 | 68 |
| verified 输出数 | 68 |
| global 输出数 | 70 |
| all 输出数 | 57725 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 32.9 |
| fetch | 6.0 |
| generate | 22.6 |
| geo | 1.6 |
| probe | 98.5 |
| real_test | 56.2 |
| tcp | 207.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 7 | 7 | 0 | 100.0% |
| shadowsocks | 288 | 235 | 53 | 81.6% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 7 | 5 | 2 | 71.4% |
| vless | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 48 |
| speed:TimeoutError | 4 |
| cn-block:ClientOSError | 3 |
| geo:ClientOSError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15877 |
| ConnectionRefusedError | 2494 |
| gaierror | 858 |
| OSError | 339 |
| SSRFBlocked | 3 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.973 | prefer | 21 | 1.0 | 405 |
| dragon | 0.891 | prefer | 305 | 0.813 | 44346 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8437 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4526 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4895 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11552 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5299 |
| barry-far-vless | 0.255 | observe | 0 | None | 5482 |
| mheidari-all | 0.255 | observe | 0 | None | 14211 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-ShadowsocksM | 0.175 | observe | 0 | None | 0 | 4 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 476 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 471 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 354 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 332 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 331 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 323 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 301 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 296 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 220 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 207 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.813 | 248 | 57 | 305 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 21 | 0 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44346 | yes | 5.62 | 0 |
| mheidari-all | 14211 | yes | 4.21 | 0 |
| SoliSpirit-all | 11552 | yes | 2.28 | 0 |
| Surfboard-tg-mixed | 8437 | yes | 3.01 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.97 | 0 |
| barry-far-vless | 5482 | yes | 1.22 | 0 |
| Surfboard-tg-vless | 5299 | yes | 2.42 | 0 |
| 10ium-ScrapeCategorize-Vless | 4895 | yes | 1.04 | 0 |
| mahdibland-V2RayAggregator | 4526 | yes | 1.68 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.89 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 48 |
| speed | 4 |
| cn-block | 3 |
| geo | 1 |
| 204 | 1 |
