# AutoNodes 每日报告

生成时间：2026-11-13 23:30:20

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 128722 |
| 去重后节点数 | 58751 |
| TCP 可达数 | 3000 |
| 真测通过数 | 76 |
| verified 输出数 | 76 |
| global 输出数 | 76 |
| all 输出数 | 58751 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 32.0 |
| fetch | 7.6 |
| generate | 25.9 |
| geo | 1.7 |
| probe | 102.5 |
| real_test | 48.1 |
| tcp | 194.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 3 | 2 | 60.0% |
| http | 55 | 54 | 1 | 98.2% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 220 | 209 | 11 | 95.0% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 25 | 22 | 3 | 88.0% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| 204:ClientOSError | 3 |
| 204:TimeoutError | 1 |
| cn-block:ClientOSError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14529 |
| ConnectionRefusedError | 2181 |
| gaierror | 640 |
| OSError | 329 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 270 | 0.933 | 44709 |
| ermaozi | 0.989 | prefer | 55 | 0.982 | 590 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14267 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4900 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2734 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11654 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8942 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6457 |
| barry-far-vless | 0.255 | observe | 0 | None | 6639 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 443 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 438 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 321 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 299 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 298 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 290 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 263 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 187 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 174 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.933 | 252 | 18 | 270 |
| ermaozi | 0.982 | 54 | 1 | 55 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44709 | yes | 7.08 | 0 |
| mheidari-all | 14267 | yes | 4.29 | 0 |
| SoliSpirit-all | 11654 | yes | 2.84 | 0 |
| Surfboard-tg-mixed | 8942 | yes | 2.83 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.35 | 0 |
| barry-far-vless | 6639 | yes | 1.21 | 0 |
| Surfboard-tg-vless | 6457 | yes | 3.33 | 0 |
| 10ium-ScrapeCategorize-Vless | 4900 | yes | 1.01 | 0 |
| mahdibland-V2RayAggregator | 4624 | yes | 2.95 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.82 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 13 |
| 204 | 4 |
| cn-block | 1 |
| speed | 1 |
