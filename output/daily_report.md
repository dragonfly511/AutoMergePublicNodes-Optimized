# AutoNodes 每日报告

生成时间：2026-10-30 22:08:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 125787 |
| 去重后节点数 | 58329 |
| TCP 可达数 | 3000 |
| 真测通过数 | 89 |
| verified 输出数 | 89 |
| global 输出数 | 90 |
| all 输出数 | 58329 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 26.4 |
| fetch | 5.6 |
| generate | 18.7 |
| geo | 1.5 |
| probe | 73.7 |
| real_test | 34.0 |
| tcp | 202.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 27 | 27 | 0 | 100.0% |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 6 | 5 | 1 | 83.3% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 99 | 89 | 10 | 89.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 10 |
| 204:ProxyError | 1 |
| 204:ClientOSError | 1 |
| 204:TimeoutError | 1 |
| cn-block:TimeoutError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14775 |
| ConnectionRefusedError | 2284 |
| gaierror | 524 |
| OSError | 332 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.988 | prefer | 27 | 1.0 | 550 |
| dragon | 0.955 | prefer | 126 | 0.881 | 44960 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4960 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2724 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10588 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7917 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5777 |
| barry-far-vless | 0.255 | observe | 0 | None | 6013 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4459 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 2 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 512 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 403 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 398 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 281 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 259 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 258 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 250 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 228 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 223 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 147 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.881 | 111 | 15 | 126 |
| ermaozi | 1.0 | 27 | 0 | 27 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44960 | yes | 4.61 | 0 |
| mheidari-all | 14611 | yes | 3.24 | 0 |
| SoliSpirit-all | 10588 | yes | 1.89 | 0 |
| Surfboard-tg-mixed | 7917 | yes | 2.28 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.34 | 0 |
| barry-far-vless | 6013 | yes | 0.43 | 0 |
| Surfboard-tg-vless | 5777 | yes | 1.96 | 0 |
| 10ium-ScrapeCategorize-Vless | 4960 | yes | 0.74 | 0 |
| mahdibland-V2RayAggregator | 4459 | yes | 1.78 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.8 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 10 |
| 204 | 3 |
| cn-block | 1 |
| geo | 1 |
