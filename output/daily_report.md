# AutoNodes 每日报告

生成时间：2026-10-22 11:00:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 4/89 |
| 原始节点数 | 95606 |
| 去重后节点数 | 26590 |
| TCP 可达数 | 3000 |
| 真测通过数 | 108 |
| verified 输出数 | 108 |
| global 输出数 | 115 |
| all 输出数 | 26590 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.0 |
| fetch | 7.8 |
| generate | 14.2 |
| geo | 1.5 |
| probe | 103.8 |
| real_test | 70.4 |
| tcp | 79.8 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 76 | 72 | 4 | 94.7% |
| hysteria2 | 12 | 11 | 1 | 91.7% |
| shadowsocks | 142 | 126 | 16 | 88.7% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 47 | 38 | 9 | 80.9% |
| vless | 165 | 68 | 97 | 41.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 79 |
| geo:ClientOSError | 12 |
| speed:ClientOSError | 11 |
| 204:ProxyError | 9 |
| cn-block:TimeoutError | 6 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| geo:TimeoutError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6388 |
| ConnectionRefusedError | 1021 |
| gaierror | 263 |
| OSError | 240 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.972 | prefer | 32 | 1.0 | 45 |
| ermaozi-get_subscribe | 0.901 | prefer | 48 | 0.896 | 523 |
| mheidari-all | 0.83 | prefer | 66 | 0.758 | 23951 |
| Au1rxx-base64 | 0.729 | prefer | 209 | 0.67 | 1526 |
| Surfboard-tg-mixed | 0.656 | observe | 90 | 0.578 | 6970 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5015 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3641 |
| Epodonios-all | 0.255 | observe | 0 | None | 7460 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10066 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
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
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 482 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 373 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 368 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 251 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 229 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 228 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 220 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 198 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 193 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 117 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.578 | 52 | 38 | 90 |
| Au1rxx-base64 | 0.67 | 140 | 69 | 209 |
| mheidari-all | 0.758 | 50 | 16 | 66 |
| ermaozi-get_subscribe | 0.896 | 43 | 5 | 48 |
| zhangkai | 1.0 | 32 | 0 | 32 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23951 | yes | 6.45 | 0 |
| SoliSpirit-all | 10066 | yes | 6.44 | 0 |
| Epodonios-all | 7460 | yes | 5.74 | 0 |
| Surfboard-tg-mixed | 6970 | yes | 3.83 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.13 | 0 |
| barry-far-vless | 5666 | yes | 0.81 | 0 |
| Surfboard-tg-vless | 5452 | yes | 4.55 | 0 |
| 10ium-ScrapeCategorize-Vless | 5015 | yes | 1.06 | 0 |
| mahdibland-V2RayAggregator | 4164 | yes | 3.36 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.36 | 0 |

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
| test_one_timeout | 79 |
| geo | 15 |
| 204 | 14 |
| speed | 11 |
| cn-block | 11 |
