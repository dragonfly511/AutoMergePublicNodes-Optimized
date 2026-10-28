# AutoNodes 每日报告

生成时间：2026-10-28 22:27:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 15/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 144053 |
| 去重后节点数 | 59128 |
| TCP 可达数 | 3000 |
| 真测通过数 | 68 |
| verified 输出数 | 68 |
| global 输出数 | 69 |
| all 输出数 | 59128 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 30.3 |
| fetch | 5.2 |
| generate | 19.5 |
| geo | 1.6 |
| probe | 90.5 |
| real_test | 35.3 |
| tcp | 204.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 29 | 27 | 2 | 93.1% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 166 | 154 | 12 | 92.8% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 11 | 10 | 1 | 90.9% |
| vless | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 7 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 2 |
| cn-block:ProxyError | 1 |
| speed:ClientOSError | 1 |
| cn-block:TimeoutError | 1 |
| speed:TimeoutError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] create service: initialize outbound[0]: unknown method: o|y | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15903 |
| ConnectionRefusedError | 2249 |
| OSError | 356 |
| gaierror | 314 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.994 | prefer | 196 | 0.918 | 44753 |
| ermaozi | 0.924 | prefer | 29 | 0.931 | 513 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 33849 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5004 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2801 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10359 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7686 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5749 |
| barry-far-vless | 0.255 | observe | 0 | None | 5963 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 506 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 397 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 392 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 275 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 253 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 252 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 244 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 222 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 217 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 141 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.918 | 180 | 16 | 196 |
| ermaozi | 0.931 | 27 | 2 | 29 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44753 | yes | 4.6 | 0 |
| mheidari-all | 33849 | yes | 3.36 | 0 |
| SoliSpirit-all | 10359 | yes | 2.96 | 0 |
| Surfboard-tg-mixed | 7686 | yes | 2.21 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.12 | 0 |
| barry-far-vless | 5963 | yes | 0.32 | 0 |
| Surfboard-tg-vless | 5749 | yes | 1.93 | 0 |
| 10ium-ScrapeCategorize-Vless | 5004 | yes | 0.57 | 0 |
| mahdibland-V2RayAggregator | 4323 | yes | 1.65 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.2 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 7 |
| 204 | 4 |
| cn-block | 4 |
| speed | 2 |
| sing-box exited 1 | 1 |
