# AutoNodes 每日报告

生成时间：2026-11-13 14:17:00

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 127093 |
| 去重后节点数 | 58788 |
| TCP 可达数 | 3000 |
| 真测通过数 | 93 |
| verified 输出数 | 93 |
| global 输出数 | 95 |
| all 输出数 | 58788 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 34.1 |
| fetch | 5.8 |
| generate | 17.9 |
| geo | 1.5 |
| probe | 80.6 |
| real_test | 47.6 |
| tcp | 174.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 27 | 26 | 1 | 96.3% |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 207 | 189 | 18 | 91.3% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 50 | 39 | 11 | 78.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 20 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 3 |
| speed:ClientOSError | 2 |
| 204:TimeoutError | 2 |
| 204:ClientOSError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 12665 |
| ConnectionRefusedError | 2460 |
| gaierror | 1386 |
| OSError | 613 |
| SSRFBlocked | 7 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.962 | prefer | 270 | 0.885 | 44243 |
| ermaozi | 0.955 | prefer | 27 | 0.963 | 590 |
| Surfboard-tg-mixed | 0.438 | observe | 3 | 1.0 | 8804 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4900 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2734 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11382 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6228 |
| barry-far-vless | 0.255 | observe | 0 | None | 6298 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4624 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 442 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 437 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 320 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 298 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 297 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 289 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 262 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 186 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 173 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.0 | 0 | 1 | 1 |
| dragon | 0.885 | 239 | 31 | 270 |
| ermaozi | 0.963 | 26 | 1 | 27 |
| Surfboard-tg-mixed | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44243 | yes | 4.98 | 0 |
| mheidari-all | 14067 | yes | 3.0 | 0 |
| SoliSpirit-all | 11382 | yes | 2.04 | 0 |
| Surfboard-tg-mixed | 8804 | yes | 2.34 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.7 | 0 |
| barry-far-vless | 6298 | yes | 0.74 | 0 |
| Surfboard-tg-vless | 6228 | yes | 2.15 | 0 |
| 10ium-ScrapeCategorize-Vless | 4900 | yes | 0.88 | 0 |
| mahdibland-V2RayAggregator | 4624 | yes | 1.84 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.6 | 0 |

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
| 204 | 7 |
| speed | 3 |
| cn-block | 3 |
