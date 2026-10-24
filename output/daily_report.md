# AutoNodes 每日报告

生成时间：2026-10-24 15:43:30

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 1/93 |
| 原始节点数 | 138792 |
| 去重后节点数 | 58761 |
| TCP 可达数 | 3000 |
| 真测通过数 | 48 |
| verified 输出数 | 48 |
| global 输出数 | 48 |
| all 输出数 | 58761 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.5 |
| fetch | 8.9 |
| generate | 29.1 |
| geo | 1.7 |
| probe | 126.1 |
| real_test | 36.7 |
| tcp | 202.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 18 | 9 | 9 | 50.0% |
| hysteria2 | 14 | 11 | 3 | 78.6% |
| shadowsocks | 130 | 120 | 10 | 92.3% |
| socks | 6 | 2 | 4 | 33.3% |
| trojan | 13 | 8 | 5 | 61.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| geo:ProxyError | 5 |
| 204:ClientOSError | 3 |
| 204:TimeoutError | 3 |
| 204:ProxyError | 2 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 1 |
| speed:ProxyError | 1 |
| speed:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15832 |
| ConnectionRefusedError | 2502 |
| gaierror | 477 |
| OSError | 323 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.947 | prefer | 164 | 0.872 | 45691 |
| ermaozi | 0.498 | observe | 17 | 0.529 | 567 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 24286 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4911 |
| Epodonios-all | 0.255 | observe | 0 | None | 7679 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10364 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5474 |
| barry-far-vless | 0.255 | observe | 0 | None | 5695 |
| xiaoji235-airport-v2ray-all | 0.255 | observe | 0 | None | 6752 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 491 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 382 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 377 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 260 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 238 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 237 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 229 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 207 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 202 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 126 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.0 | 0 | 1 | 1 |
| ermaozi | 0.529 | 9 | 8 | 17 |
| dragon | 0.872 | 143 | 21 | 164 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45691 | yes | 8.26 | 0 |
| mheidari-all | 24286 | yes | 5.63 | 0 |
| SoliSpirit-all | 10364 | yes | 5.27 | 0 |
| Epodonios-all | 7679 | yes | 5.82 | 0 |
| Surfboard-tg-mixed | 7219 | yes | 4.65 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.47 | 0 |
| barry-far-vless | 5695 | yes | 0.71 | 0 |
| Surfboard-tg-vless | 5474 | yes | 3.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 4911 | yes | 2.0 | 0 |
| mahdibland-V2RayAggregator | 4150 | yes | 2.97 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 13 |
| 204 | 8 |
| geo | 5 |
| cn-block | 3 |
| speed | 2 |
