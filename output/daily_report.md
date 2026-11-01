# AutoNodes 每日报告

生成时间：2026-11-01 12:59:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/108 |
| 清理建议：禁用/降权 | 17/0 |
| 清理建议：优先/观察 | 2/89 |
| 原始节点数 | 126129 |
| 去重后节点数 | 58390 |
| TCP 可达数 | 3000 |
| 真测通过数 | 72 |
| verified 输出数 | 72 |
| global 输出数 | 73 |
| all 输出数 | 58390 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.2 |
| fetch | 8.7 |
| generate | 30.1 |
| geo | 1.7 |
| probe | 96.5 |
| real_test | 32.3 |
| tcp | 198.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 43 | 43 | 0 | 100.0% |
| hysteria2 | 15 | 10 | 5 | 66.7% |
| shadowsocks | 13 | 10 | 3 | 76.9% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 94 | 75 | 19 | 79.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 20 |
| 204:ProxyError | 4 |
| speed:ProxyError | 1 |
| geo:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| 204:TimeoutError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14812 |
| ConnectionRefusedError | 2311 |
| gaierror | 501 |
| OSError | 356 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.995 | prefer | 38 | 1.0 | 499 |
| dragon | 0.849 | prefer | 128 | 0.773 | 44351 |
| zhangkai | 0.441 | observe | 5 | 1.0 | 43 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4976 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3716 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10599 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8063 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5660 |
| barry-far-vless | 0.255 | observe | 0 | None | 5850 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 2 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-ShadowsocksM | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 409 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 404 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 287 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 265 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 264 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 256 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 234 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 229 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 153 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 140 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.773 | 99 | 29 | 128 |
| zhangkai | 1.0 | 5 | 0 | 5 |
| ermaozi-get_subscribe | 1.0 | 38 | 0 | 38 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44351 | yes | 7.8 | 0 |
| mheidari-all | 14747 | yes | 6.06 | 0 |
| SoliSpirit-all | 10599 | yes | 3.48 | 0 |
| Surfboard-tg-mixed | 8063 | yes | 4.06 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.01 | 0 |
| barry-far-vless | 5850 | yes | 1.16 | 0 |
| Surfboard-tg-vless | 5660 | yes | 3.79 | 0 |
| 10ium-ScrapeCategorize-Vless | 4976 | yes | 1.53 | 0 |
| mahdibland-V2RayAggregator | 4680 | yes | 2.15 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.24 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 20 |
| 204 | 5 |
| cn-block | 2 |
| speed | 1 |
| geo | 1 |
