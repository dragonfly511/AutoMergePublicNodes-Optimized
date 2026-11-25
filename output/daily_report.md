# AutoNodes 每日报告

生成时间：2026-11-25 07:44:05

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 122393 |
| 去重后节点数 | 58838 |
| TCP 可达数 | 3000 |
| 真测通过数 | 111 |
| verified 输出数 | 111 |
| global 输出数 | 115 |
| all 输出数 | 58838 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 37.7 |
| fetch | 8.6 |
| generate | 31.1 |
| geo | 1.7 |
| probe | 110.3 |
| real_test | 53.6 |
| tcp | 201.3 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 49 | 47 | 2 | 95.9% |
| hysteria2 | 8 | 7 | 1 | 87.5% |
| shadowsocks | 207 | 188 | 19 | 90.8% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 5 | 4 | 1 | 80.0% |
| vless | 60 | 51 | 9 | 85.0% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 20 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 3 |
| 204:ProxyError | 2 |
| 204:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:40120: bind: address already in use | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15931 |
| ConnectionRefusedError | 2464 |
| gaierror | 715 |
| OSError | 354 |
| ConnectionResetError | 4 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.965 | prefer | 285 | 0.888 | 43982 |
| ermaozi | 0.96 | prefer | 50 | 0.96 | 442 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4839 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11515 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8136 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5440 |
| barry-far-vless | 0.255 | observe | 0 | None | 5649 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4565 |
| mheidari-all | 0.255 | observe | 0 | None | 14996 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 470 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 465 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 348 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 326 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 325 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 317 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 295 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 290 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 214 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 201 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.888 | 253 | 32 | 285 |
| ermaozi | 0.96 | 48 | 2 | 50 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 43982 | yes | 7.79 | 0 |
| mheidari-all | 14996 | yes | 5.2 | 0 |
| SoliSpirit-all | 11515 | yes | 1.73 | 0 |
| Surfboard-tg-mixed | 8136 | yes | 3.71 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.0 | 0 |
| barry-far-vless | 5649 | yes | 1.29 | 0 |
| Surfboard-tg-vless | 5440 | yes | 3.37 | 0 |
| 10ium-ScrapeCategorize-Vless | 4839 | yes | 1.09 | 0 |
| mahdibland-V2RayAggregator | 4565 | yes | 3.05 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.39 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 20 |
| 204 | 7 |
| cn-block | 5 |
| sing-box exited 1 | 1 |
| geo | 1 |
