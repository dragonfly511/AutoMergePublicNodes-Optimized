# AutoNodes 每日报告

生成时间：2026-10-28 12:29:13

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 15/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 143389 |
| 去重后节点数 | 59264 |
| TCP 可达数 | 3000 |
| 真测通过数 | 72 |
| verified 输出数 | 72 |
| global 输出数 | 75 |
| all 输出数 | 59264 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.4 |
| fetch | 6.5 |
| generate | 23.6 |
| geo | 1.6 |
| probe | 108.0 |
| real_test | 48.7 |
| tcp | 206.8 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 29 | 27 | 2 | 93.1% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 125 | 111 | 14 | 88.8% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 60 | 43 | 17 | 71.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 20 |
| 204:TimeoutError | 8 |
| cn-block:ClientOSError | 3 |
| 204:ProxyError | 2 |
| 204:ClientOSError | 2 |
| cn-block:TimeoutError | 2 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15423 |
| ConnectionRefusedError | 2498 |
| gaierror | 599 |
| OSError | 328 |
| SSRFBlocked | 5 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.924 | prefer | 29 | 0.931 | 513 |
| dragon | 0.901 | prefer | 205 | 0.824 | 45232 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 7544 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5004 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2801 |
| Epodonios-all | 0.255 | observe | 0 | None | 8035 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10603 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5575 |
| barry-far-vless | 0.255 | observe | 0 | None | 5789 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 505 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 396 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 391 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 274 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 252 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 251 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 243 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 221 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 216 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 140 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.824 | 169 | 36 | 205 |
| ermaozi | 0.931 | 27 | 2 | 29 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45232 | yes | 5.67 | 0 |
| mheidari-all | 24702 | yes | 4.09 | 0 |
| SoliSpirit-all | 10603 | yes | 4.21 | 0 |
| Epodonios-all | 8035 | yes | 3.97 | 0 |
| Surfboard-tg-mixed | 7544 | yes | 2.65 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.77 | 0 |
| barry-far-vless | 5789 | yes | 0.99 | 0 |
| Surfboard-tg-vless | 5575 | yes | 2.47 | 0 |
| 10ium-ScrapeCategorize-Vless | 5004 | yes | 1.15 | 0 |
| mahdibland-V2RayAggregator | 4500 | yes | 1.89 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 20 |
| 204 | 12 |
| cn-block | 5 |
| geo | 1 |
