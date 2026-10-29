# AutoNodes 每日报告

生成时间：2026-10-29 12:38:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 144498 |
| 去重后节点数 | 59634 |
| TCP 可达数 | 3000 |
| 真测通过数 | 37 |
| verified 输出数 | 37 |
| global 输出数 | 40 |
| all 输出数 | 59634 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.7 |
| fetch | 9.3 |
| generate | 30.4 |
| geo | 1.7 |
| probe | 116.6 |
| real_test | 47.0 |
| tcp | 199.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 23 | 20 | 3 | 87.0% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 153 | 126 | 27 | 82.4% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 22 | 18 | 4 | 81.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 25 |
| cn-block:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| 204:TimeoutError | 2 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| 204:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46904: bind: address already in use | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15244 |
| ConnectionRefusedError | 2315 |
| gaierror | 596 |
| OSError | 355 |
| ConnectionResetError | 2 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.888 | prefer | 191 | 0.812 | 44753 |
| ermaozi | 0.867 | prefer | 24 | 0.875 | 510 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 7779 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2709 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10415 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5820 |
| barry-far-vless | 0.255 | observe | 0 | None | 5941 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4444 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 508 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 399 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 394 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 277 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 255 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 254 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 246 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 224 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 219 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 143 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.812 | 155 | 36 | 191 |
| ermaozi | 0.875 | 21 | 3 | 24 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44753 | yes | 8.47 | 0 |
| mheidari-all | 34088 | yes | 6.61 | 0 |
| SoliSpirit-all | 10415 | yes | 2.09 | 0 |
| Surfboard-tg-mixed | 7779 | yes | 3.77 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.93 | 0 |
| barry-far-vless | 5941 | yes | 1.46 | 0 |
| Surfboard-tg-vless | 5820 | yes | 3.5 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 1.7 | 0 |
| mahdibland-V2RayAggregator | 4444 | yes | 2.11 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.74 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_drop_50pct | verified output dropped from 88 to 37 |
| real_ok_drop_50pct | real-test ok dropped from 88 to 37 |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 25 |
| cn-block | 7 |
| 204 | 6 |
| sing-box exited 1 | 1 |
