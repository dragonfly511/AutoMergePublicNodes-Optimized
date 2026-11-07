# AutoNodes 每日报告

生成时间：2026-11-07 12:46:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127486 |
| 去重后节点数 | 59098 |
| TCP 可达数 | 3000 |
| 真测通过数 | 79 |
| verified 输出数 | 79 |
| global 输出数 | 80 |
| all 输出数 | 59098 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.9 |
| fetch | 5.0 |
| generate | 19.8 |
| geo | 1.6 |
| probe | 94.8 |
| real_test | 42.5 |
| tcp | 196.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 21 | 20 | 1 | 95.2% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 211 | 194 | 17 | 91.9% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 62 | 44 | 18 | 71.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 22 |
| 204:ProxyError | 10 |
| cn-block:ProxyError | 3 |
| speed:ProxyError | 2 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15031 |
| ConnectionRefusedError | 2349 |
| gaierror | 362 |
| OSError | 306 |
| SSRFBlocked | 3 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.949 | prefer | 289 | 0.872 | 45178 |
| ermaozi | 0.934 | prefer | 21 | 0.952 | 515 |
| mheidari-all | 0.287 | observe | 2 | 0.5 | 14331 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4866 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2734 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11009 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8637 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6148 |
| barry-far-vless | 0.255 | observe | 0 | None | 6359 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| ermaozi-get_subscribe | 0.142 | observe | 1 | 0.0 | 0 | 366 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 426 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 421 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 304 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 282 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 281 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 273 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 251 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 246 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 170 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 157 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.5 | 1 | 1 | 2 |
| dragon | 0.872 | 252 | 37 | 289 |
| ermaozi | 0.952 | 20 | 1 | 21 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45178 | yes | 4.37 | 0 |
| mheidari-all | 14331 | yes | 2.56 | 0 |
| SoliSpirit-all | 11009 | yes | 1.18 | 0 |
| Surfboard-tg-mixed | 8637 | yes | 1.91 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.76 | 0 |
| barry-far-vless | 6359 | yes | 0.53 | 0 |
| Surfboard-tg-vless | 6148 | yes | 1.74 | 0 |
| 10ium-ScrapeCategorize-Vless | 4866 | yes | 0.69 | 0 |
| mahdibland-V2RayAggregator | 4522 | yes | 0.09 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.22 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 22 |
| 204 | 11 |
| cn-block | 3 |
| speed | 3 |
| geo | 1 |
