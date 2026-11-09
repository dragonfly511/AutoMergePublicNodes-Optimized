# AutoNodes 每日报告

生成时间：2026-11-09 15:41:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 126187 |
| 去重后节点数 | 58633 |
| TCP 可达数 | 3000 |
| 真测通过数 | 73 |
| verified 输出数 | 73 |
| global 输出数 | 74 |
| all 输出数 | 58633 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 27.5 |
| fetch | 6.5 |
| generate | 22.7 |
| geo | 1.6 |
| probe | 104.4 |
| real_test | 51.1 |
| tcp | 197.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 19 | 18 | 1 | 94.7% |
| hysteria2 | 13 | 9 | 4 | 69.2% |
| shadowsocks | 211 | 191 | 20 | 90.5% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 7 | 4 | 3 | 57.1% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 22 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 2 |
| speed:TimeoutError | 2 |
| cn-block:TimeoutError | 1 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14849 |
| ConnectionRefusedError | 2321 |
| gaierror | 424 |
| OSError | 319 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.954 | prefer | 236 | 0.877 | 45021 |
| ermaozi | 0.896 | prefer | 19 | 0.947 | 518 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14143 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4976 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2754 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11022 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8247 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5893 |
| barry-far-vless | 0.255 | observe | 0 | None | 6048 |

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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 432 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 427 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 310 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 288 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 287 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 279 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 257 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 252 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 176 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 163 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.877 | 207 | 29 | 236 |
| ermaozi | 0.947 | 18 | 1 | 19 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45021 | yes | 5.6 | 0 |
| mheidari-all | 14143 | yes | 3.4 | 0 |
| SoliSpirit-all | 11022 | yes | 2.53 | 0 |
| Surfboard-tg-mixed | 8247 | yes | 2.8 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.02 | 0 |
| barry-far-vless | 6048 | yes | 1.47 | 0 |
| Surfboard-tg-vless | 5893 | yes | 2.95 | 0 |
| 10ium-ScrapeCategorize-Vless | 4976 | yes | 1.32 | 0 |
| mahdibland-V2RayAggregator | 4583 | yes | 1.19 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.88 | 0 |

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
| test_one_timeout | 22 |
| 204 | 3 |
| cn-block | 3 |
| speed | 2 |
