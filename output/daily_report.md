# AutoNodes 每日报告

生成时间：2026-11-04 23:30:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 126866 |
| 去重后节点数 | 58024 |
| TCP 可达数 | 3000 |
| 真测通过数 | 50 |
| verified 输出数 | 50 |
| global 输出数 | 52 |
| all 输出数 | 58024 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 34.6 |
| fetch | 6.5 |
| generate | 23.2 |
| geo | 1.8 |
| probe | 102.9 |
| real_test | 42.2 |
| tcp | 198.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 19 | 19 | 0 | 100.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 226 | 209 | 17 | 92.5% |
| socks | 11 | 4 | 7 | 36.4% |
| trojan | 58 | 57 | 1 | 98.3% |
| vless | 1 | 1 | 0 | 100.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 15 |
| 204:ProxyError | 5 |
| cn-block:TimeoutError | 2 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| speed:TimeoutError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14580 |
| ConnectionRefusedError | 2346 |
| gaierror | 435 |
| OSError | 336 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.999 | prefer | 307 | 0.922 | 44959 |
| zhangkai | 0.923 | prefer | 19 | 1.0 | 43 |
| Surfboard-tg-mixed | 0.373 | observe | 5 | 0.6 | 8651 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14725 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2526 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10844 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6015 |
| barry-far-vless | 0.255 | observe | 0 | None | 6228 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 418 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 413 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 296 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 274 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 273 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 265 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 243 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 238 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 162 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 149 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.6 | 3 | 2 | 5 |
| dragon | 0.922 | 283 | 24 | 307 |
| mheidari-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 19 | 0 | 19 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44959 | yes | 5.99 | 0 |
| mheidari-all | 14725 | yes | 3.65 | 0 |
| SoliSpirit-all | 10844 | yes | 1.71 | 0 |
| Surfboard-tg-mixed | 8651 | yes | 2.67 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.35 | 0 |
| barry-far-vless | 6228 | yes | 1.04 | 0 |
| Surfboard-tg-vless | 6015 | yes | 2.87 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 0.82 | 0 |
| mahdibland-V2RayAggregator | 4612 | yes | 2.32 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.89 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 15 |
| 204 | 6 |
| cn-block | 4 |
| speed | 1 |
