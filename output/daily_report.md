# AutoNodes 每日报告

生成时间：2026-10-22 16:26:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 4/89 |
| 原始节点数 | 96315 |
| 去重后节点数 | 26646 |
| TCP 可达数 | 3000 |
| 真测通过数 | 64 |
| verified 输出数 | 64 |
| global 输出数 | 68 |
| all 输出数 | 26646 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 29.2 |
| fetch | 5.1 |
| generate | 10.6 |
| geo | 1.4 |
| probe | 88.5 |
| real_test | 66.3 |
| tcp | 79.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 40 | 36 | 4 | 90.0% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 136 | 119 | 17 | 87.5% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 46 | 32 | 14 | 69.6% |
| vless | 112 | 61 | 51 | 54.5% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 61 |
| speed:ClientOSError | 12 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 2 |
| cn-block:TimeoutError | 2 |
| geo:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| geo:TimeoutError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6481 |
| ConnectionRefusedError | 1027 |
| gaierror | 257 |
| OSError | 239 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.904 | prefer | 40 | 0.9 | 573 |
| Surfboard-tg-mixed | 0.839 | prefer | 56 | 0.768 | 7043 |
| mheidari-all | 0.83 | prefer | 70 | 0.757 | 24062 |
| Au1rxx-base64 | 0.766 | prefer | 181 | 0.707 | 1533 |
| ninja-vless | 0.383 | observe | 2 | 1.0 | 1791 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 171 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3641 |
| Epodonios-all | 0.255 | observe | 0 | None | 7538 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigV2rayNG | 0.135 | observe | 1 | 0.0 | 0 | 200 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 483 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 374 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 369 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 252 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 230 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 229 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 221 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 199 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 194 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 118 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| Au1rxx-base64 | 0.707 | 128 | 53 | 181 |
| mheidari-all | 0.757 | 53 | 17 | 70 |
| Surfboard-tg-mixed | 0.768 | 43 | 13 | 56 |
| ermaozi | 0.9 | 36 | 4 | 40 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ninja-vless | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24062 | yes | 3.81 | 0 |
| SoliSpirit-all | 10202 | yes | 4.44 | 0 |
| Epodonios-all | 7538 | yes | 3.1 | 0 |
| Surfboard-tg-mixed | 7043 | yes | 2.63 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.05 | 0 |
| barry-far-vless | 5601 | yes | 0.89 | 0 |
| Surfboard-tg-vless | 5382 | yes | 2.76 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 2.66 | 0 |
| mahdibland-V2RayAggregator | 4164 | yes | 0.28 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.95 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 61 |
| speed | 12 |
| 204 | 8 |
| cn-block | 5 |
| geo | 3 |
