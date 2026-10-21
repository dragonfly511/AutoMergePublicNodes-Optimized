# AutoNodes 每日报告

生成时间：2026-10-21 02:46:28

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 4/89 |
| 原始节点数 | 95196 |
| 去重后节点数 | 26625 |
| TCP 可达数 | 3000 |
| 真测通过数 | 110 |
| verified 输出数 | 110 |
| global 输出数 | 114 |
| all 输出数 | 26625 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 33.6 |
| fetch | 7.6 |
| generate | 13.7 |
| geo | 1.5 |
| probe | 102.4 |
| real_test | 78.9 |
| tcp | 81.2 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 74 | 73 | 1 | 98.6% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 159 | 149 | 10 | 93.7% |
| socks | 6 | 5 | 1 | 83.3% |
| trojan | 38 | 35 | 3 | 92.1% |
| vless | 269 | 104 | 165 | 38.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 90 |
| speed:ClientOSError | 37 |
| geo:ClientOSError | 31 |
| 204:ProxyError | 6 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 4 |
| 204:TimeoutError | 4 |
| cn-block:TimeoutError | 3 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6554 |
| ConnectionRefusedError | 1014 |
| OSError | 234 |
| gaierror | 185 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.985 | prefer | 72 | 0.917 | 7115 |
| ermaozi-get_subscribe | 0.982 | prefer | 50 | 0.98 | 516 |
| zhangkai | 0.966 | prefer | 26 | 1.0 | 31 |
| Au1rxx-base64 | 0.851 | prefer | 172 | 0.797 | 1439 |
| mheidari-all | 0.497 | observe | 238 | 0.416 | 23653 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4967 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3519 |
| Epodonios-all | 0.255 | observe | 0 | None | 7598 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

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
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 5 |
| tg-freeiranianv2rey | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 477 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 368 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 363 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 246 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 224 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 223 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 215 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 193 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 188 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 112 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.416 | 99 | 139 | 238 |
| Au1rxx-base64 | 0.797 | 137 | 35 | 172 |
| Surfboard-tg-mixed | 0.917 | 66 | 6 | 72 |
| ermaozi-get_subscribe | 0.98 | 49 | 1 | 50 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 26 | 0 | 26 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23653 | yes | 5.24 | 0 |
| SoliSpirit-all | 10013 | yes | 2.66 | 0 |
| Epodonios-all | 7598 | yes | 5.45 | 0 |
| Surfboard-tg-mixed | 7115 | yes | 3.92 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.53 | 0 |
| barry-far-vless | 5764 | yes | 0.47 | 0 |
| Surfboard-tg-vless | 5552 | yes | 4.17 | 0 |
| 10ium-ScrapeCategorize-Vless | 4967 | yes | 1.26 | 0 |
| mahdibland-V2RayAggregator | 4127 | yes | 3.31 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.03 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 90 |
| speed | 37 |
| geo | 31 |
| 204 | 14 |
| cn-block | 9 |
