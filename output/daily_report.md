# AutoNodes 每日报告

生成时间：2026-11-11 13:54:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 127876 |
| 去重后节点数 | 59802 |
| TCP 可达数 | 3000 |
| 真测通过数 | 121 |
| verified 输出数 | 121 |
| global 输出数 | 123 |
| all 输出数 | 59802 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 30.3 |
| fetch | 6.7 |
| generate | 23.9 |
| geo | 1.6 |
| probe | 94.6 |
| real_test | 57.1 |
| tcp | 199.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 81 | 75 | 6 | 92.6% |
| hysteria2 | 13 | 10 | 3 | 76.9% |
| shadowsocks | 198 | 175 | 23 | 88.4% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 77 | 53 | 24 | 68.8% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 29 |
| 204:ProxyError | 15 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| speed:TimeoutError | 2 |
| cn-block:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42600: bind: address already in use | 1 |
| speed:ClientOSError | 1 |
| 204:TimeoutError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15310 |
| ConnectionRefusedError | 2432 |
| gaierror | 515 |
| OSError | 355 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.951 | prefer | 80 | 0.938 | 608 |
| dragon | 0.907 | prefer | 292 | 0.829 | 45201 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4981 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2629 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11142 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8393 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6306 |
| barry-far-vless | 0.255 | observe | 0 | None | 6508 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-PrivateVPNs | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 437 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 432 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 315 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 293 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 292 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 284 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 262 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 257 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 181 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 168 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.0 | 0 | 1 | 1 |
| dragon | 0.829 | 242 | 50 | 292 |
| ermaozi | 0.938 | 75 | 5 | 80 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45201 | yes | 5.78 | 0 |
| mheidari-all | 14277 | yes | 4.07 | 0 |
| SoliSpirit-all | 11142 | yes | 3.23 | 0 |
| Surfboard-tg-mixed | 8393 | yes | 2.56 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.48 | 0 |
| barry-far-vless | 6508 | yes | 1.87 | 0 |
| Surfboard-tg-vless | 6306 | yes | 2.72 | 0 |
| 10ium-ScrapeCategorize-Vless | 4981 | yes | 1.7 | 0 |
| mahdibland-V2RayAggregator | 4589 | yes | 1.3 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.93 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 29 |
| 204 | 18 |
| cn-block | 5 |
| speed | 3 |
| sing-box exited 1 | 1 |
| geo | 1 |
