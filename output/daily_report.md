# AutoNodes 每日报告

生成时间：2026-11-18 00:50:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 126303 |
| 去重后节点数 | 58151 |
| TCP 可达数 | 3000 |
| 真测通过数 | 86 |
| verified 输出数 | 86 |
| global 输出数 | 87 |
| all 输出数 | 58151 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 35.5 |
| fetch | 6.4 |
| generate | 23.4 |
| geo | 1.6 |
| probe | 100.3 |
| real_test | 45.1 |
| tcp | 189.9 |
| write_verified | 0.4 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 7 | 5 | 2 | 71.4% |
| http | 31 | 29 | 2 | 93.5% |
| hysteria2 | 12 | 12 | 0 | 100.0% |
| shadowsocks | 241 | 230 | 11 | 95.4% |
| socks | 3 | 2 | 1 | 66.7% |
| vless | 21 | 12 | 9 | 57.1% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 11 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 4 |
| geo:ClientOSError | 3 |
| speed:TimeoutError | 2 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14144 |
| ConnectionRefusedError | 2216 |
| gaierror | 630 |
| OSError | 352 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.996 | prefer | 285 | 0.919 | 44296 |
| ermaozi | 0.849 | prefer | 19 | 0.895 | 502 |
| tg-ShadowsocksM | 0.69 | observe | 12 | 1.0 | 64 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4928 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2790 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11681 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8416 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5789 |
| barry-far-vless | 0.255 | observe | 0 | None | 5968 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| chromego_merge | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 454 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 449 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 332 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 310 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 309 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 301 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 279 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 274 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 198 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 185 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi | 0.895 | 17 | 2 | 19 |
| dragon | 0.919 | 262 | 23 | 285 |
| tg-ShadowsocksM | 1.0 | 12 | 0 | 12 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44296 | yes | 5.75 | 0 |
| mheidari-all | 14610 | yes | 4.29 | 0 |
| SoliSpirit-all | 11681 | yes | 2.02 | 0 |
| Surfboard-tg-mixed | 8416 | yes | 3.97 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.71 | 0 |
| barry-far-vless | 5968 | yes | 1.2 | 0 |
| Surfboard-tg-vless | 5789 | yes | 2.44 | 0 |
| 10ium-ScrapeCategorize-Vless | 4928 | yes | 1.01 | 0 |
| mahdibland-V2RayAggregator | 4460 | yes | 2.22 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.86 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 11 |
| 204 | 5 |
| cn-block | 4 |
| geo | 3 |
| speed | 2 |
