# AutoNodes 每日报告

生成时间：2026-11-16 15:18:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 1/88 |
| 原始节点数 | 127495 |
| 去重后节点数 | 58280 |
| TCP 可达数 | 3000 |
| 真测通过数 | 45 |
| verified 输出数 | 45 |
| global 输出数 | 47 |
| all 输出数 | 58280 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.7 |
| fetch | 8.7 |
| generate | 30.2 |
| geo | 1.7 |
| probe | 96.4 |
| real_test | 26.7 |
| tcp | 199.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 22 | 20 | 2 | 90.9% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 27 | 19 | 8 | 70.4% |
| socks | 5 | 1 | 4 | 20.0% |
| trojan | 70 | 39 | 31 | 55.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 23 |
| test_one_timeout:15.0s | 13 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 2 |
| 204:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:33898: bind: address already in use | 1 |
| cn-block:TimeoutError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14229 |
| ConnectionRefusedError | 2282 |
| gaierror | 670 |
| OSError | 331 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.897 | prefer | 22 | 0.909 | 548 |
| dragon | 0.692 | observe | 114 | 0.614 | 43748 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 15005 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 165 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4964 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2915 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11563 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8824 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6113 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 451 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 446 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 329 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 307 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 306 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 298 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 276 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 271 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 195 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 182 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.614 | 70 | 44 | 114 |
| ermaozi | 0.909 | 20 | 2 | 22 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 43748 | yes | 8.15 | 0 |
| mheidari-all | 15005 | yes | 6.29 | 0 |
| SoliSpirit-all | 11563 | yes | 3.0 | 0 |
| Surfboard-tg-mixed | 8824 | yes | 5.04 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.14 | 0 |
| barry-far-vless | 6293 | yes | 1.41 | 0 |
| Surfboard-tg-vless | 6113 | yes | 3.45 | 0 |
| 10ium-ScrapeCategorize-Vless | 4964 | yes | 1.08 | 0 |
| mahdibland-V2RayAggregator | 4545 | yes | 3.03 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.16 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 27 |
| test_one_timeout | 13 |
| cn-block | 4 |
| sing-box exited 1 | 1 |
| speed | 1 |
