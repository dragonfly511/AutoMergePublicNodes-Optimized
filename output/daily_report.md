# AutoNodes 每日报告

生成时间：2026-11-10 01:25:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 126665 |
| 去重后节点数 | 58804 |
| TCP 可达数 | 3000 |
| 真测通过数 | 57 |
| verified 输出数 | 57 |
| global 输出数 | 58 |
| all 输出数 | 58804 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 33.0 |
| fetch | 6.5 |
| generate | 23.0 |
| geo | 1.7 |
| probe | 94.0 |
| real_test | 47.6 |
| tcp | 201.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 86 | 84 | 2 | 97.7% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 228 | 212 | 16 | 93.0% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 90 | 82 | 8 | 91.1% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 20 |
| 204:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:36442: bind: address already in use | 1 |
| 204:ClientOSError | 1 |
| cn-block:TimeoutError | 1 |
| speed:TimeoutError | 1 |
| cn-block:ClientOSError | 1 |
| geo:ClientOSError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15343 |
| ConnectionRefusedError | 2419 |
| gaierror | 437 |
| OSError | 303 |
| SSRFBlocked | 2 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.997 | prefer | 337 | 0.92 | 44733 |
| ermaozi | 0.99 | prefer | 87 | 0.977 | 602 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14061 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4976 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2754 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11226 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8250 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6133 |
| barry-far-vless | 0.255 | observe | 0 | None | 6103 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 433 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 428 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 311 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 289 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 288 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 280 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 258 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 253 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 177 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 164 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.92 | 310 | 27 | 337 |
| ermaozi | 0.977 | 85 | 2 | 87 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44733 | yes | 5.67 | 0 |
| mheidari-all | 14061 | yes | 3.99 | 0 |
| SoliSpirit-all | 11226 | yes | 2.23 | 0 |
| Surfboard-tg-mixed | 8250 | yes | 3.47 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.72 | 0 |
| Surfboard-tg-vless | 6133 | yes | 3.05 | 0 |
| barry-far-vless | 6103 | yes | 1.47 | 0 |
| 10ium-ScrapeCategorize-Vless | 4976 | yes | 1.09 | 0 |
| mahdibland-V2RayAggregator | 4583 | yes | 2.24 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.14 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_downtrend_4_runs | verified output decreased for 4 consecutive runs |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 20 |
| 204 | 4 |
| cn-block | 2 |
| sing-box exited 1 | 1 |
| speed | 1 |
| geo | 1 |
