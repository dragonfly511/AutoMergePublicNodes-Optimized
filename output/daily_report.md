# AutoNodes 每日报告

生成时间：2026-11-06 22:56:59

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127016 |
| 去重后节点数 | 58429 |
| TCP 可达数 | 3000 |
| 真测通过数 | 78 |
| verified 输出数 | 78 |
| global 输出数 | 78 |
| all 输出数 | 58429 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 28.9 |
| fetch | 4.5 |
| generate | 18.8 |
| geo | 1.5 |
| probe | 94.3 |
| real_test | 37.7 |
| tcp | 193.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 33 | 32 | 1 | 97.0% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 212 | 205 | 7 | 96.7% |
| socks | 6 | 2 | 4 | 33.3% |
| trojan | 75 | 69 | 6 | 92.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 9 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 3 |
| speed:TimeoutError | 2 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14558 |
| ConnectionRefusedError | 2350 |
| gaierror | 479 |
| OSError | 307 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 305 | 0.951 | 45178 |
| ermaozi | 0.963 | prefer | 33 | 0.97 | 513 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 13728 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4934 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2768 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3995 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10967 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6135 |
| barry-far-vless | 0.255 | observe | 0 | None | 6345 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4540 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 424 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 419 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 302 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 280 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 279 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 271 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 249 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 244 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 168 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 155 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.0 | 0 | 2 | 2 |
| dragon | 0.951 | 290 | 15 | 305 |
| ermaozi | 0.97 | 32 | 1 | 33 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45178 | yes | 4.25 | 0 |
| mheidari-all | 13728 | yes | 2.51 | 0 |
| SoliSpirit-all | 10967 | yes | 2.33 | 0 |
| Surfboard-tg-mixed | 8758 | yes | 2.18 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.41 | 0 |
| barry-far-vless | 6345 | yes | 0.95 | 0 |
| Surfboard-tg-vless | 6135 | yes | 1.85 | 0 |
| 10ium-ScrapeCategorize-Vless | 4934 | yes | 1.21 | 0 |
| mahdibland-V2RayAggregator | 4540 | yes | 0.86 | 0 |
| MatinGhanbari-all-sub | 3995 | yes | 1.26 | 0 |

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
| test_one_timeout | 9 |
| 204 | 8 |
| speed | 2 |
