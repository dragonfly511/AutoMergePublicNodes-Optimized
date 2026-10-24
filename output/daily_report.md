# AutoNodes 每日报告

生成时间：2026-10-24 10:39:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 1/93 |
| 原始节点数 | 138286 |
| 去重后节点数 | 58672 |
| TCP 可达数 | 3000 |
| 真测通过数 | 57 |
| verified 输出数 | 57 |
| global 输出数 | 58 |
| all 输出数 | 58672 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 23.1 |
| fetch | 8.5 |
| generate | 26.0 |
| geo | 1.8 |
| probe | 122.7 |
| real_test | 51.8 |
| tcp | 202.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 53 | 34 | 19 | 64.2% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 136 | 126 | 10 | 92.6% |
| socks | 9 | 4 | 5 | 44.4% |
| trojan | 6 | 6 | 0 | 100.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 12 |
| geo:ProxyError | 7 |
| cn-block:ProxyError | 7 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 2 |
| cn-block:TimeoutError | 1 |
| speed:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 16036 |
| ConnectionRefusedError | 2467 |
| gaierror | 425 |
| OSError | 322 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.984 | prefer | 165 | 0.909 | 45691 |
| ermaozi | 0.635 | observe | 52 | 0.615 | 608 |
| tg-oneclickvpnkeys | 0.316 | observe | 2 | 1.0 | 113 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4911 |
| Epodonios-all | 0.255 | observe | 0 | None | 7652 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10213 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7180 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5436 |
| barry-far-vless | 0.255 | observe | 0 | None | 5737 |

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
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 490 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 381 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 376 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 259 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 237 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 236 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 228 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 206 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 201 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 125 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi | 0.615 | 32 | 20 | 52 |
| dragon | 0.909 | 150 | 15 | 165 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45691 | yes | 7.39 | 0 |
| mheidari-all | 23868 | yes | 5.72 | 0 |
| SoliSpirit-all | 10213 | yes | 2.26 | 0 |
| Epodonios-all | 7652 | yes | 2.91 | 0 |
| Surfboard-tg-mixed | 7180 | yes | 3.31 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.95 | 0 |
| barry-far-vless | 5737 | yes | 0.78 | 0 |
| Surfboard-tg-vless | 5436 | yes | 3.7 | 0 |
| 10ium-ScrapeCategorize-Vless | 4911 | yes | 1.16 | 0 |
| mahdibland-V2RayAggregator | 4150 | yes | 0.58 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 12 |
| cn-block | 10 |
| geo | 7 |
| 204 | 5 |
| speed | 1 |
