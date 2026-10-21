# AutoNodes 每日报告

生成时间：2026-10-21 11:00:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 5/88 |
| 原始节点数 | 96052 |
| 去重后节点数 | 26942 |
| TCP 可达数 | 3000 |
| 真测通过数 | 122 |
| verified 输出数 | 122 |
| global 输出数 | 128 |
| all 输出数 | 26942 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.0 |
| fetch | 7.5 |
| generate | 14.2 |
| geo | 1.5 |
| probe | 108.6 |
| real_test | 67.6 |
| tcp | 81.3 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 86 | 84 | 2 | 97.7% |
| hysteria2 | 10 | 10 | 0 | 100.0% |
| shadowsocks | 143 | 130 | 13 | 90.9% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 38 | 28 | 10 | 73.7% |
| vless | 157 | 86 | 71 | 54.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 57 |
| speed:ClientOSError | 11 |
| geo:ClientOSError | 9 |
| cn-block:ClientOSError | 5 |
| 204:ProxyError | 4 |
| 204:TimeoutError | 4 |
| cn-block:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6483 |
| ConnectionRefusedError | 1029 |
| OSError | 235 |
| gaierror | 218 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.966 | prefer | 26 | 1.0 | 31 |
| ermaozi-get_subscribe | 0.945 | prefer | 64 | 0.938 | 516 |
| mheidari-all | 0.937 | prefer | 54 | 0.87 | 23726 |
| Surfboard-tg-mixed | 0.817 | prefer | 93 | 0.742 | 6977 |
| Au1rxx-base64 | 0.752 | prefer | 202 | 0.693 | 1528 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4925 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 4067 |
| Epodonios-all | 0.255 | observe | 0 | None | 7465 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10264 |

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
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 478 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 369 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 364 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 247 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 225 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 224 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 216 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 194 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 189 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 113 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.693 | 140 | 62 | 202 |
| Surfboard-tg-mixed | 0.742 | 69 | 24 | 93 |
| mheidari-all | 0.87 | 47 | 7 | 54 |
| ermaozi-get_subscribe | 0.938 | 60 | 4 | 64 |
| zhangkai | 1.0 | 26 | 0 | 26 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23726 | yes | 7.19 | 0 |
| SoliSpirit-all | 10264 | yes | 4.16 | 0 |
| Epodonios-all | 7465 | yes | 5.63 | 0 |
| Surfboard-tg-mixed | 6977 | yes | 4.36 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.61 | 0 |
| barry-far-vless | 5763 | yes | 2.83 | 0 |
| Surfboard-tg-vless | 5462 | yes | 3.84 | 0 |
| 10ium-ScrapeCategorize-Vless | 4925 | yes | 1.57 | 0 |
| mahdibland-V2RayAggregator | 4127 | yes | 1.91 | 0 |
| DeltaKronecker-all | 4067 | yes | 6.24 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 57 |
| speed | 12 |
| 204 | 10 |
| cn-block | 9 |
| geo | 9 |
