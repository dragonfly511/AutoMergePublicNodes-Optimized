# AutoNodes 每日报告

生成时间：2026-10-23 21:16:39

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 90/108 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 2/92 |
| 原始节点数 | 138420 |
| 去重后节点数 | 58550 |
| TCP 可达数 | 3000 |
| 真测通过数 | 67 |
| verified 输出数 | 67 |
| global 输出数 | 69 |
| all 输出数 | 58550 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 21.9 |
| fetch | 6.6 |
| generate | 18.4 |
| geo | 1.6 |
| probe | 116.7 |
| real_test | 50.4 |
| tcp | 196.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 41 | 40 | 1 | 97.6% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 139 | 124 | 15 | 89.2% |
| socks | 6 | 2 | 4 | 33.3% |
| trojan | 13 | 11 | 2 | 84.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 12 |
| 204:ProxyError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ClientOSError | 2 |
| cn-block:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15622 |
| ConnectionRefusedError | 2489 |
| gaierror | 444 |
| OSError | 321 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.997 | prefer | 38 | 1.0 | 555 |
| dragon | 0.95 | prefer | 175 | 0.874 | 45691 |
| tg-oneclickvpnkeys | 0.272 | observe | 3 | 0.667 | 92 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4911 |
| Epodonios-all | 0.255 | observe | 0 | None | 7680 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10312 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7184 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5437 |
| barry-far-vless | 0.255 | observe | 0 | None | 5798 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 488 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 379 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 374 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 257 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 235 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 234 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 226 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 204 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 199 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 123 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.667 | 2 | 1 | 3 |
| dragon | 0.874 | 153 | 22 | 175 |
| ermaozi | 1.0 | 38 | 0 | 38 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45691 | yes | 6.63 | 0 |
| mheidari-all | 23638 | yes | 3.57 | 0 |
| SoliSpirit-all | 10312 | yes | 2.2 | 0 |
| Epodonios-all | 7680 | yes | 1.79 | 0 |
| Surfboard-tg-mixed | 7184 | yes | 2.38 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.33 | 0 |
| barry-far-vless | 5798 | yes | 0.42 | 0 |
| Surfboard-tg-vless | 5437 | yes | 2.21 | 0 |
| 10ium-ScrapeCategorize-Vless | 4911 | yes | 0.86 | 0 |
| mahdibland-V2RayAggregator | 4117 | yes | 1.72 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 12 |
| 204 | 7 |
| cn-block | 4 |
