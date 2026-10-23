# AutoNodes 每日报告

生成时间：2026-10-23 16:49:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | critical |
| 健康检查通过 | False |
| 健康源数量 | 93/108 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 2/92 |
| 原始节点数 | 140766 |
| 去重后节点数 | 58341 |
| TCP 可达数 | 3000 |
| 真测通过数 | 67 |
| verified 输出数 | 67 |
| global 输出数 | 67 |
| all 输出数 | 58341 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 19.5 |
| fetch | 9.8 |
| generate | 29.6 |
| geo | 1.7 |
| probe | 128.4 |
| real_test | 32.0 |
| tcp | 203.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 27 | 21 | 6 | 77.8% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 130 | 107 | 23 | 82.3% |
| socks | 7 | 4 | 3 | 57.1% |
| trojan | 20 | 12 | 8 | 60.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 27 |
| cn-block:ProxyError | 6 |
| 204:ClientOSError | 5 |
| 204:ProxyError | 2 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 16160 |
| ConnectionRefusedError | 2552 |
| gaierror | 395 |
| OSError | 332 |
| SSRFBlocked | 5 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.872 | prefer | 171 | 0.795 | 45037 |
| ermaozi | 0.781 | prefer | 27 | 0.778 | 555 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4911 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3871 |
| Epodonios-all | 0.255 | observe | 0 | None | 7353 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10120 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 6855 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5326 |
| barry-far-vless | 0.255 | observe | 0 | None | 5545 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
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
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 487 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 378 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 373 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 256 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 234 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 233 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 225 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 203 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 198 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 122 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi | 0.778 | 21 | 6 | 27 |
| dragon | 0.795 | 136 | 35 | 171 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45037 | yes | 9.49 | 0 |
| mheidari-all | 23793 | yes | 6.41 | 0 |
| SoliSpirit-all | 10120 | yes | 4.08 | 0 |
| Epodonios-all | 7353 | yes | 7.49 | 0 |
| Surfboard-tg-mixed | 6855 | yes | 4.51 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.87 | 0 |
| barry-far-vless | 5545 | yes | 1.32 | 0 |
| Surfboard-tg-vless | 5326 | yes | 3.96 | 0 |
| 10ium-ScrapeCategorize-Vless | 4911 | yes | 1.91 | 0 |
| mahdibland-V2RayAggregator | 4230 | yes | 2.94 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 27 |
| 204 | 8 |
| cn-block | 6 |
