# AutoNodes 每日报告

生成时间：2026-10-27 04:20:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 15/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 141998 |
| 去重后节点数 | 59042 |
| TCP 可达数 | 3000 |
| 真测通过数 | 106 |
| verified 输出数 | 106 |
| global 输出数 | 106 |
| all 输出数 | 59042 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 21.4 |
| fetch | 9.1 |
| generate | 30.7 |
| geo | 1.7 |
| probe | 100.2 |
| real_test | 31.2 |
| tcp | 203.8 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 49 | 48 | 1 | 98.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 4 | 4 | 0 | 100.0% |
| socks | 8 | 5 | 3 | 62.5% |
| trojan | 86 | 78 | 8 | 90.7% |
| vless | 2 | 1 | 1 | 50.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 11 |
| 204:ProxyError | 2 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15178 |
| ConnectionRefusedError | 2426 |
| gaierror | 608 |
| OSError | 283 |
| SSRFBlocked | 4 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.985 | prefer | 49 | 0.98 | 603 |
| dragon | 0.962 | prefer | 117 | 0.889 | 45531 |
| Au1rxx-base64 | 0.381 | observe | 2 | 1.0 | 1734 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4919 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3004 |
| Epodonios-all | 0.255 | observe | 0 | None | 7632 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10267 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7143 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5408 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 500 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 391 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 386 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 247 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 246 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 238 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 216 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 211 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 135 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.889 | 104 | 13 | 117 |
| ermaozi | 0.98 | 48 | 1 | 49 |
| Au1rxx-base64 | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45531 | yes | 8.31 | 0 |
| mheidari-all | 24431 | yes | 6.06 | 0 |
| SoliSpirit-all | 10267 | yes | 3.39 | 0 |
| Epodonios-all | 7632 | yes | 3.28 | 0 |
| Surfboard-tg-mixed | 7143 | yes | 4.48 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.32 | 0 |
| barry-far-vless | 5620 | yes | 0.94 | 0 |
| Surfboard-tg-vless | 5408 | yes | 3.74 | 0 |
| 10ium-ScrapeCategorize-Vless | 4919 | yes | 1.19 | 0 |
| mahdibland-V2RayAggregator | 4466 | yes | 3.11 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 11 |
| 204 | 2 |
| cn-block | 1 |
