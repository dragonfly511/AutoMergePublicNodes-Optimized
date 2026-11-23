# AutoNodes 每日报告

生成时间：2026-11-23 06:34:35

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127015 |
| 去重后节点数 | 58977 |
| TCP 可达数 | 3000 |
| 真测通过数 | 69 |
| verified 输出数 | 69 |
| global 输出数 | 69 |
| all 输出数 | 58977 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.2 |
| fetch | 6.3 |
| generate | 23.0 |
| geo | 1.6 |
| probe | 81.4 |
| real_test | 25.3 |
| tcp | 195.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 7 | 3 | 4 | 42.9% |
| http | 51 | 48 | 3 | 94.1% |
| hysteria2 | 12 | 9 | 3 | 75.0% |
| shadowsocks | 15 | 14 | 1 | 93.3% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 55 | 39 | 16 | 70.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 13 |
| test_one_timeout:15.0s | 7 |
| 204:ClientOSError | 2 |
| 204:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:45297: bind: address already in use | 1 |
| cn-block:ClientOSError | 1 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14319 |
| ConnectionRefusedError | 2275 |
| gaierror | 669 |
| OSError | 356 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.927 | prefer | 52 | 0.923 | 486 |
| dragon | 0.814 | prefer | 92 | 0.739 | 43774 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 8701 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5069 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2671 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11834 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5650 |
| barry-far-vless | 0.255 | observe | 0 | None | 5831 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4512 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 1 |
| tg-freeiranianv2rey | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 466 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 461 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 344 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 322 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 321 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 313 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 291 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 286 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 210 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 197 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.739 | 68 | 24 | 92 |
| ermaozi | 0.923 | 48 | 4 | 52 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 43774 | yes | 5.59 | 0 |
| mheidari-all | 15418 | yes | 4.33 | 0 |
| SoliSpirit-all | 11834 | yes | 1.81 | 0 |
| Surfboard-tg-mixed | 8701 | yes | 3.85 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.43 | 0 |
| barry-far-vless | 5831 | yes | 1.58 | 0 |
| Surfboard-tg-vless | 5650 | yes | 2.65 | 0 |
| 10ium-ScrapeCategorize-Vless | 5069 | yes | 0.62 | 0 |
| mahdibland-V2RayAggregator | 4512 | yes | 2.16 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.7 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 17 |
| test_one_timeout | 7 |
| cn-block | 2 |
| sing-box exited 1 | 1 |
| geo | 1 |
