# AutoNodes 每日报告

生成时间：2026-11-05 05:50:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127236 |
| 去重后节点数 | 58014 |
| TCP 可达数 | 3000 |
| 真测通过数 | 40 |
| verified 输出数 | 40 |
| global 输出数 | 40 |
| all 输出数 | 58014 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.9 |
| fetch | 8.7 |
| generate | 29.7 |
| geo | 1.8 |
| probe | 97.8 |
| real_test | 21.0 |
| tcp | 204.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 20 | 16 | 4 | 80.0% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 3 | 3 | 0 | 100.0% |
| socks | 6 | 5 | 1 | 83.3% |
| trojan | 93 | 81 | 12 | 87.1% |
| vless | 2 | 1 | 1 | 50.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 6 |
| test_one_timeout:15.0s | 6 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:36608: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15073 |
| ConnectionRefusedError | 2310 |
| OSError | 336 |
| gaierror | 264 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.947 | prefer | 118 | 0.873 | 44959 |
| ermaozi | 0.795 | prefer | 20 | 0.8 | 555 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8675 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14576 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2526 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10857 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6030 |
| barry-far-vless | 0.255 | observe | 0 | None | 6243 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 4 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 419 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 414 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 297 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 275 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 274 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 244 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 239 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 163 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 150 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi | 0.8 | 16 | 4 | 20 |
| dragon | 0.873 | 103 | 15 | 118 |
| mheidari-all | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44959 | yes | 8.03 | 0 |
| mheidari-all | 14576 | yes | 6.04 | 0 |
| SoliSpirit-all | 10857 | yes | 2.92 | 0 |
| Surfboard-tg-mixed | 8675 | yes | 3.77 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.41 | 0 |
| barry-far-vless | 6243 | yes | 1.69 | 0 |
| Surfboard-tg-vless | 6030 | yes | 4.03 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 0.97 | 0 |
| mahdibland-V2RayAggregator | 4612 | yes | 2.63 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.5 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_downtrend_4_runs | verified output decreased for 4 consecutive runs |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 8 |
| test_one_timeout | 6 |
| cn-block | 2 |
| geo | 2 |
| sing-box exited 1 | 1 |
