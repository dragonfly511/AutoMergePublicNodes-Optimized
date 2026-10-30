# AutoNodes 每日报告

生成时间：2026-10-30 12:28:42

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 144804 |
| 去重后节点数 | 59386 |
| TCP 可达数 | 3000 |
| 真测通过数 | 63 |
| verified 输出数 | 63 |
| global 输出数 | 64 |
| all 输出数 | 59386 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 20.1 |
| fetch | 5.3 |
| generate | 17.5 |
| geo | 1.5 |
| probe | 68.3 |
| real_test | 30.6 |
| tcp | 205.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 31 | 29 | 2 | 93.5% |
| hysteria2 | 14 | 9 | 5 | 64.3% |
| shadowsocks | 34 | 31 | 3 | 91.2% |
| socks | 4 | 0 | 4 | 0.0% |
| trojan | 62 | 58 | 4 | 93.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 9 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 2 |
| 204:ProxyError | 1 |
| cn-block:status | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15906 |
| ConnectionRefusedError | 2434 |
| gaierror | 396 |
| OSError | 332 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.936 | prefer | 116 | 0.862 | 44588 |
| ermaozi | 0.922 | prefer | 28 | 0.929 | 550 |
| tg-oneclickvpnkeys | 0.314 | observe | 2 | 1.0 | 70 |
| ermaozi-get_subscribe | 0.271 | observe | 1 | 1.0 | 390 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4960 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2724 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10521 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7902 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5822 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-PrivateVPNs | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 511 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 402 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 397 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 280 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 258 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 257 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 249 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 227 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 222 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 146 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.0 | 0 | 1 | 1 |
| dragon | 0.862 | 100 | 16 | 116 |
| ermaozi | 0.929 | 26 | 2 | 28 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44588 | yes | 4.56 | 0 |
| mheidari-all | 34171 | yes | 3.44 | 0 |
| SoliSpirit-all | 10521 | yes | 1.25 | 0 |
| Surfboard-tg-mixed | 7902 | yes | 2.42 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.64 | 0 |
| barry-far-vless | 5942 | yes | 1.02 | 0 |
| Surfboard-tg-vless | 5822 | yes | 1.74 | 0 |
| 10ium-ScrapeCategorize-Vless | 4960 | yes | 0.79 | 0 |
| mahdibland-V2RayAggregator | 4445 | yes | 1.55 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.29 | 0 |

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
| test_one_timeout | 9 |
| 204 | 8 |
| cn-block | 2 |
