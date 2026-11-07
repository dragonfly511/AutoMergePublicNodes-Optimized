# AutoNodes 每日报告

生成时间：2026-11-07 05:18:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127015 |
| 去重后节点数 | 58489 |
| TCP 可达数 | 3000 |
| 真测通过数 | 89 |
| verified 输出数 | 89 |
| global 输出数 | 92 |
| all 输出数 | 58489 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 33.3 |
| fetch | 8.9 |
| generate | 31.1 |
| geo | 1.7 |
| probe | 120.1 |
| real_test | 40.1 |
| tcp | 186.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 50 | 50 | 0 | 100.0% |
| hysteria2 | 12 | 12 | 0 | 100.0% |
| shadowsocks | 211 | 199 | 12 | 94.3% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 80 | 70 | 10 | 87.5% |
| vless | 1 | 0 | 1 | 0.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| 204:ProxyError | 3 |
| cn-block:TimeoutError | 3 |
| geo:ProxyError | 3 |
| speed:TimeoutError | 2 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14224 |
| ConnectionRefusedError | 2362 |
| gaierror | 538 |
| OSError | 311 |
| SSRFBlocked | 4 |
| ConnectionResetError | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | prefer | 50 | 1.0 | 562 |
| dragon | 0.999 | prefer | 308 | 0.922 | 45178 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 13634 |
| Surfboard-tg-mixed | 0.287 | observe | 2 | 0.5 | 8637 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4934 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2768 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11015 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6148 |
| barry-far-vless | 0.255 | observe | 0 | None | 6359 |

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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 425 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 420 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 303 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 281 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 280 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 272 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 250 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 245 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 169 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 156 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.5 | 1 | 1 | 2 |
| dragon | 0.922 | 284 | 24 | 308 |
| mheidari-all | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 50 | 0 | 50 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45178 | yes | 8.16 | 0 |
| mheidari-all | 13634 | yes | 5.77 | 0 |
| SoliSpirit-all | 11015 | yes | 5.16 | 0 |
| Surfboard-tg-mixed | 8637 | yes | 3.88 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.1 | 0 |
| barry-far-vless | 6359 | yes | 2.61 | 0 |
| Surfboard-tg-vless | 6148 | yes | 3.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 4934 | yes | 2.84 | 0 |
| mahdibland-V2RayAggregator | 4540 | yes | 3.26 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.94 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 13 |
| 204 | 4 |
| cn-block | 3 |
| geo | 3 |
| speed | 2 |
