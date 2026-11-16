# AutoNodes 每日报告

生成时间：2026-11-16 05:33:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 126757 |
| 去重后节点数 | 57886 |
| TCP 可达数 | 3000 |
| 真测通过数 | 71 |
| verified 输出数 | 71 |
| global 输出数 | 71 |
| all 输出数 | 57886 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.8 |
| fetch | 6.2 |
| generate | 22.7 |
| geo | 1.7 |
| probe | 79.6 |
| real_test | 24.5 |
| tcp | 199.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 22 | 20 | 2 | 90.9% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 23 | 21 | 2 | 91.3% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 107 | 96 | 11 | 89.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| 204:ProxyError | 4 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14231 |
| ConnectionRefusedError | 2178 |
| gaierror | 592 |
| OSError | 329 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.967 | prefer | 149 | 0.893 | 43748 |
| ermaozi | 0.894 | prefer | 22 | 0.909 | 471 |
| mheidari-all | 0.391 | observe | 2 | 1.0 | 14209 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8824 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4916 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2960 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11554 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6113 |
| barry-far-vless | 0.255 | observe | 0 | None | 6294 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 3 |
| tg-freeiranianv2rey | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 450 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 445 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 328 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 306 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 305 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 297 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 275 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 270 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 194 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 181 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.893 | 133 | 16 | 149 |
| ermaozi | 0.909 | 20 | 2 | 22 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 43748 | yes | 5.73 | 0 |
| mheidari-all | 14209 | yes | 4.37 | 0 |
| SoliSpirit-all | 11554 | yes | 2.43 | 0 |
| Surfboard-tg-mixed | 8824 | yes | 3.4 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.71 | 0 |
| barry-far-vless | 6294 | yes | 1.13 | 0 |
| Surfboard-tg-vless | 6113 | yes | 3.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 4916 | yes | 0.97 | 0 |
| mahdibland-V2RayAggregator | 4550 | yes | 1.56 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.95 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 13 |
| 204 | 5 |
