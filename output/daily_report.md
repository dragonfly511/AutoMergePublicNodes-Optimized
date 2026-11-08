# AutoNodes 每日报告

生成时间：2026-11-08 13:04:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127282 |
| 去重后节点数 | 59317 |
| TCP 可达数 | 3000 |
| 真测通过数 | 79 |
| verified 输出数 | 79 |
| global 输出数 | 81 |
| all 输出数 | 59317 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 31.7 |
| fetch | 8.6 |
| generate | 30.5 |
| geo | 1.7 |
| probe | 115.2 |
| real_test | 44.2 |
| tcp | 198.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 28 | 26 | 2 | 92.9% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 201 | 186 | 15 | 92.5% |
| socks | 6 | 2 | 4 | 33.3% |
| trojan | 61 | 48 | 13 | 78.7% |
| vless | 2 | 1 | 1 | 50.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 22 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 2 |
| cn-block:TimeoutError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15244 |
| ConnectionRefusedError | 2380 |
| gaierror | 469 |
| OSError | 293 |
| SSRFBlocked | 4 |
| ConnectionResetError | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.956 | prefer | 281 | 0.879 | 45338 |
| ermaozi | 0.923 | prefer | 28 | 0.929 | 586 |
| mheidari-all | 0.391 | observe | 2 | 1.0 | 14505 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5035 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3024 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10990 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8136 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5786 |

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
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 429 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 424 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 307 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 285 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 284 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 276 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 254 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 249 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 173 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 160 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.879 | 247 | 34 | 281 |
| ermaozi | 0.929 | 26 | 2 | 28 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45338 | yes | 7.9 | 0 |
| mheidari-all | 14505 | yes | 4.9 | 0 |
| SoliSpirit-all | 10990 | yes | 3.63 | 0 |
| Surfboard-tg-mixed | 8136 | yes | 3.57 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.49 | 0 |
| barry-far-vless | 5999 | yes | 1.41 | 0 |
| Surfboard-tg-vless | 5786 | yes | 4.06 | 0 |
| 10ium-ScrapeCategorize-Vless | 5035 | yes | 1.92 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 2.55 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.0 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 22 |
| 204 | 8 |
| cn-block | 4 |
| geo | 2 |
