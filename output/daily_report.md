# AutoNodes 每日报告

生成时间：2026-11-24 09:05:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 124077 |
| 去重后节点数 | 59936 |
| TCP 可达数 | 3000 |
| 真测通过数 | 112 |
| verified 输出数 | 112 |
| global 输出数 | 123 |
| all 输出数 | 59936 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.3 |
| fetch | 4.8 |
| generate | 19.0 |
| geo | 1.5 |
| probe | 86.4 |
| real_test | 48.8 |
| tcp | 210.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 3 | 1 | 75.0% |
| http | 45 | 43 | 2 | 95.6% |
| hysteria2 | 6 | 5 | 1 | 83.3% |
| shadowsocks | 207 | 177 | 30 | 85.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 33 | 13 | 20 | 39.4% |
| vless | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 21 |
| 204:ProxyError | 17 |
| cn-block:ClientOSError | 9 |
| cn-block:ProxyError | 2 |
| cn-block:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48148: bind: address already in use | 1 |
| speed:ClientOSError | 1 |
| 204:ClientOSError | 1 |
| speed:TimeoutError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 16687 |
| ConnectionRefusedError | 2533 |
| gaierror | 550 |
| OSError | 325 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.953 | prefer | 44 | 0.955 | 460 |
| dragon | 0.863 | prefer | 251 | 0.785 | 44710 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8220 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4587 |
| ermaozi-get_subscribe | 0.271 | observe | 1 | 1.0 | 388 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5064 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11659 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5327 |
| barry-far-vless | 0.255 | observe | 0 | None | 5849 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 468 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 463 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 346 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 324 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 323 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 315 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 293 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 288 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 212 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 199 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.785 | 197 | 54 | 251 |
| ermaozi | 0.955 | 42 | 2 | 44 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44710 | yes | 4.3 | 0 |
| mheidari-all | 15386 | yes | 3.17 | 0 |
| SoliSpirit-all | 11659 | yes | 0.75 | 0 |
| Surfboard-tg-mixed | 8220 | yes | 1.83 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.17 | 0 |
| barry-far-vless | 5849 | yes | 0.43 | 0 |
| Surfboard-tg-vless | 5327 | yes | 2.08 | 0 |
| 10ium-ScrapeCategorize-Vless | 5064 | yes | 1.41 | 0 |
| mahdibland-V2RayAggregator | 4587 | yes | 1.59 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.22 | 0 |

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
| test_one_timeout | 21 |
| 204 | 19 |
| cn-block | 13 |
| speed | 2 |
| sing-box exited 1 | 1 |
