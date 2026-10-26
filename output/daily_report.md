# AutoNodes 每日报告

生成时间：2026-10-26 03:57:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 15/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 143855 |
| 去重后节点数 | 59930 |
| TCP 可达数 | 3000 |
| 真测通过数 | 109 |
| verified 输出数 | 109 |
| global 输出数 | 109 |
| all 输出数 | 59930 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 29.2 |
| fetch | 9.4 |
| generate | 30.4 |
| geo | 1.7 |
| probe | 99.2 |
| real_test | 36.0 |
| tcp | 199.6 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| http | 102 | 100 | 2 | 98.0% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 7 | 7 | 0 | 100.0% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 76 | 71 | 5 | 93.4% |
| vless | 7 | 2 | 5 | 28.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| 204:ClientOSError | 2 |
| speed:ClientOSError | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15430 |
| ConnectionRefusedError | 2384 |
| gaierror | 647 |
| OSError | 323 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.997 | prefer | 102 | 0.98 | 643 |
| dragon | 0.95 | prefer | 113 | 0.876 | 45637 |
| mheidari-all | 0.287 | observe | 2 | 0.5 | 24290 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3849 |
| Epodonios-all | 0.255 | observe | 0 | None | 7848 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10571 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7351 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5665 |

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
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 497 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 388 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 383 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 244 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 243 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 235 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 213 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 208 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 132 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.5 | 1 | 1 | 2 |
| dragon | 0.876 | 99 | 14 | 113 |
| ermaozi | 0.98 | 100 | 2 | 102 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45637 | yes | 8.92 | 0 |
| mheidari-all | 24290 | yes | 5.92 | 0 |
| SoliSpirit-all | 10571 | yes | 4.63 | 0 |
| Epodonios-all | 7848 | yes | 6.33 | 0 |
| Surfboard-tg-mixed | 7351 | yes | 3.66 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.45 | 0 |
| barry-far-vless | 5884 | yes | 2.4 | 0 |
| Surfboard-tg-vless | 5665 | yes | 3.87 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 2.64 | 0 |
| mahdibland-V2RayAggregator | 4177 | yes | 1.87 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 13 |
| 204 | 2 |
| speed | 1 |
| geo | 1 |
