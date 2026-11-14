# AutoNodes 每日报告

生成时间：2026-11-14 22:13:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 127380 |
| 去重后节点数 | 58604 |
| TCP 可达数 | 3000 |
| 真测通过数 | 54 |
| verified 输出数 | 54 |
| global 输出数 | 55 |
| all 输出数 | 58604 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 32.7 |
| fetch | 8.5 |
| generate | 30.6 |
| geo | 1.7 |
| probe | 107.3 |
| real_test | 50.3 |
| tcp | 187.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 25 | 24 | 1 | 96.0% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 225 | 198 | 27 | 88.0% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 75 | 64 | 11 | 85.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 23 |
| speed:TimeoutError | 7 |
| 204:ProxyError | 5 |
| 204:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| geo:ClientOSError | 1 |
| cn-block:TimeoutError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 13384 |
| ConnectionRefusedError | 2344 |
| gaierror | 1146 |
| OSError | 353 |
| SSRFBlocked | 7 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.947 | prefer | 25 | 0.96 | 527 |
| dragon | 0.946 | prefer | 319 | 0.868 | 44363 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4966 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2652 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11797 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 9013 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6319 |
| barry-far-vless | 0.255 | observe | 0 | None | 6499 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4551 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| chromego_merge | 0.025 | observe | 0 | None | 1 | 0 |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 446 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 441 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 324 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 302 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 301 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 293 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 271 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 190 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 177 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.868 | 277 | 42 | 319 |
| ermaozi | 0.96 | 24 | 1 | 25 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44363 | yes | 7.93 | 0 |
| mheidari-all | 13757 | yes | 5.96 | 0 |
| SoliSpirit-all | 11797 | yes | 2.69 | 0 |
| Surfboard-tg-mixed | 9013 | yes | 4.02 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.23 | 0 |
| barry-far-vless | 6499 | yes | 1.44 | 0 |
| Surfboard-tg-vless | 6319 | yes | 3.38 | 0 |
| 10ium-ScrapeCategorize-Vless | 4966 | yes | 0.81 | 0 |
| mahdibland-V2RayAggregator | 4551 | yes | 2.89 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.89 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 23 |
| 204 | 10 |
| speed | 7 |
| cn-block | 2 |
| geo | 1 |
