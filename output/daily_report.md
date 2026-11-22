# AutoNodes 每日报告

生成时间：2026-11-22 05:49:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 128123 |
| 去重后节点数 | 59341 |
| TCP 可达数 | 3000 |
| 真测通过数 | 91 |
| verified 输出数 | 91 |
| global 输出数 | 95 |
| all 输出数 | 59341 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 37.1 |
| fetch | 5.6 |
| generate | 19.0 |
| geo | 1.5 |
| probe | 101.7 |
| real_test | 48.4 |
| tcp | 176.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 4 | 3 | 1 | 75.0% |
| http | 30 | 29 | 1 | 96.7% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 227 | 207 | 20 | 91.2% |
| socks | 7 | 4 | 3 | 57.1% |
| vless | 16 | 8 | 8 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 20 |
| cn-block:ClientOSError | 4 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 3 |
| speed:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 13258 |
| ConnectionRefusedError | 2369 |
| gaierror | 884 |
| OSError | 565 |
| SSRFBlocked | 4 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.956 | prefer | 256 | 0.879 | 44788 |
| ermaozi | 0.862 | prefer | 24 | 0.875 | 399 |
| zhangkai | 0.654 | observe | 11 | 1.0 | 27 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 8778 |
| ermaozi-get_subscribe | 0.282 | observe | 3 | 0.667 | 327 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 141 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5030 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2989 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 12093 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 463 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 458 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 341 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 319 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 318 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 310 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 288 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 283 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 207 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 194 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.667 | 2 | 1 | 3 |
| ermaozi | 0.875 | 21 | 3 | 24 |
| dragon | 0.879 | 225 | 31 | 256 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 11 | 0 | 11 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44788 | yes | 3.78 | 0 |
| mheidari-all | 14302 | yes | 4.8 | 0 |
| SoliSpirit-all | 12093 | yes | 2.94 | 0 |
| Surfboard-tg-mixed | 8778 | yes | 0.24 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.19 | 0 |
| barry-far-vless | 6124 | yes | 0.34 | 0 |
| Surfboard-tg-vless | 5942 | yes | 0.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 5030 | yes | 0.5 | 0 |
| mahdibland-V2RayAggregator | 4482 | yes | 0.3 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.56 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 20 |
| 204 | 8 |
| cn-block | 5 |
| speed | 2 |
