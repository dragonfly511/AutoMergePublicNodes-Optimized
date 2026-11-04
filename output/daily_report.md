# AutoNodes 每日报告

生成时间：2026-11-04 14:05:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127810 |
| 去重后节点数 | 58870 |
| TCP 可达数 | 3000 |
| 真测通过数 | 72 |
| verified 输出数 | 72 |
| global 输出数 | 73 |
| all 输出数 | 58870 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.5 |
| fetch | 8.8 |
| generate | 30.4 |
| geo | 1.9 |
| probe | 119.3 |
| real_test | 38.4 |
| tcp | 204.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 20 | 19 | 1 | 95.0% |
| hysteria2 | 12 | 9 | 3 | 75.0% |
| shadowsocks | 213 | 189 | 24 | 88.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 8 | 6 | 2 | 75.0% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 22 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 2 |
| 204:TimeoutError | 1 |
| cn-block:TimeoutError | 1 |
| cn-block:ClientOSError | 1 |
| geo:TimeoutError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14209 |
| ConnectionRefusedError | 2432 |
| gaierror | 593 |
| OSError | 316 |
| SSRFBlocked | 3 |
| UnicodeError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.943 | prefer | 239 | 0.866 | 45574 |
| zhangkai | 0.877 | prefer | 19 | 0.947 | 43 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8518 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 130 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2526 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10829 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5997 |
| barry-far-vless | 0.255 | observe | 0 | None | 6238 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 417 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 412 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 295 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 273 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 272 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 264 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 242 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 237 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 161 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 148 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.866 | 207 | 32 | 239 |
| zhangkai | 0.947 | 18 | 1 | 19 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45574 | yes | 7.75 | 0 |
| mheidari-all | 15179 | yes | 5.1 | 0 |
| SoliSpirit-all | 10829 | yes | 5.04 | 0 |
| Surfboard-tg-mixed | 8518 | yes | 4.42 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.71 | 0 |
| barry-far-vless | 6238 | yes | 0.75 | 0 |
| Surfboard-tg-vless | 5997 | yes | 3.61 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 1.03 | 0 |
| mahdibland-V2RayAggregator | 4608 | yes | 3.2 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.41 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 22 |
| 204 | 7 |
| cn-block | 2 |
| geo | 2 |
