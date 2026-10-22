# AutoNodes 每日报告

生成时间：2026-10-22 21:06:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 3/90 |
| 原始节点数 | 96202 |
| 去重后节点数 | 26700 |
| TCP 可达数 | 3000 |
| 真测通过数 | 98 |
| verified 输出数 | 98 |
| global 输出数 | 104 |
| all 输出数 | 26700 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 41.5 |
| fetch | 7.1 |
| generate | 9.8 |
| geo | 1.5 |
| probe | 96.8 |
| real_test | 69.6 |
| tcp | 80.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 73 | 70 | 3 | 95.9% |
| hysteria2 | 17 | 16 | 1 | 94.1% |
| shadowsocks | 150 | 127 | 23 | 84.7% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 31 | 23 | 8 | 74.2% |
| vless | 137 | 76 | 61 | 55.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 53 |
| speed:ClientOSError | 14 |
| cn-block:TimeoutError | 6 |
| geo:ClientOSError | 6 |
| 204:ProxyError | 4 |
| 204:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| cn-block:ClientOSError | 2 |
| geo:ProxyError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6506 |
| ConnectionRefusedError | 1051 |
| OSError | 240 |
| gaierror | 230 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.969 | prefer | 72 | 0.958 | 573 |
| mheidari-all | 0.868 | prefer | 64 | 0.797 | 23896 |
| Au1rxx-base64 | 0.806 | prefer | 185 | 0.746 | 1575 |
| Surfboard-tg-mixed | 0.696 | observe | 84 | 0.619 | 7066 |
| ninja-vless | 0.383 | observe | 2 | 1.0 | 1791 |
| mahdibland-V2RayAggregator | 0.335 | observe | 1 | 1.0 | 4176 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3641 |
| Epodonios-all | 0.255 | observe | 0 | None | 7550 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 5 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 484 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 375 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 370 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 253 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 231 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 230 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 222 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 200 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 195 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 119 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| SoliSpirit-all | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.619 | 52 | 32 | 84 |
| Au1rxx-base64 | 0.746 | 138 | 47 | 185 |
| mheidari-all | 0.797 | 51 | 13 | 64 |
| ermaozi | 0.958 | 69 | 3 | 72 |
| mahdibland-V2RayAggregator | 1.0 | 1 | 0 | 1 |
| ninja-vless | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23896 | yes | 3.71 | 0 |
| SoliSpirit-all | 10034 | yes | 3.66 | 0 |
| Epodonios-all | 7550 | yes | 3.87 | 0 |
| Surfboard-tg-mixed | 7066 | yes | 4.07 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.29 | 0 |
| barry-far-vless | 5640 | yes | 0.39 | 0 |
| Surfboard-tg-vless | 5426 | yes | 4.94 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 0.58 | 0 |
| mahdibland-V2RayAggregator | 4176 | yes | 2.51 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.7 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 53 |
| speed | 14 |
| 204 | 11 |
| cn-block | 11 |
| geo | 8 |
