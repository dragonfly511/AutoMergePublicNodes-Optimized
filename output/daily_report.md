# AutoNodes 每日报告

生成时间：2026-11-12 14:56:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 127601 |
| 去重后节点数 | 58781 |
| TCP 可达数 | 3000 |
| 真测通过数 | 98 |
| verified 输出数 | 98 |
| global 输出数 | 99 |
| all 输出数 | 58781 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 27.4 |
| fetch | 5.7 |
| generate | 19.9 |
| geo | 1.6 |
| probe | 84.9 |
| real_test | 41.5 |
| tcp | 195.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 54 | 50 | 4 | 92.6% |
| hysteria2 | 12 | 10 | 2 | 83.3% |
| shadowsocks | 185 | 168 | 17 | 90.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 80 | 56 | 24 | 70.0% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 20 |
| test_one_timeout:15.0s | 17 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 2 |
| speed:TimeoutError | 2 |
| cn-block:ProxyError | 2 |
| 204:TimeoutError | 1 |
| geo:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14603 |
| ConnectionRefusedError | 2303 |
| gaierror | 533 |
| OSError | 339 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.934 | prefer | 54 | 0.926 | 579 |
| dragon | 0.917 | prefer | 281 | 0.84 | 44265 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4998 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2737 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11439 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8655 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6375 |
| barry-far-vless | 0.255 | observe | 0 | None | 6555 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 439 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 434 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 317 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 295 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 294 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 286 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 264 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 259 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 183 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 170 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.0 | 0 | 1 | 1 |
| dragon | 0.84 | 236 | 45 | 281 |
| ermaozi | 0.926 | 50 | 4 | 54 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44265 | yes | 4.59 | 0 |
| mheidari-all | 14228 | yes | 3.11 | 0 |
| SoliSpirit-all | 11439 | yes | 1.99 | 0 |
| Surfboard-tg-mixed | 8655 | yes | 2.4 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.16 | 0 |
| barry-far-vless | 6555 | yes | 0.58 | 0 |
| Surfboard-tg-vless | 6375 | yes | 2.2 | 0 |
| 10ium-ScrapeCategorize-Vless | 4998 | yes | 0.45 | 0 |
| mahdibland-V2RayAggregator | 4618 | yes | 1.72 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.78 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 25 |
| test_one_timeout | 17 |
| cn-block | 4 |
| geo | 2 |
| speed | 2 |
