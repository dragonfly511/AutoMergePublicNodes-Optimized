# AutoNodes 每日报告

生成时间：2026-10-20 21:08:47

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 4/89 |
| 原始节点数 | 94580 |
| 去重后节点数 | 26432 |
| TCP 可达数 | 3000 |
| 真测通过数 | 82 |
| verified 输出数 | 82 |
| global 输出数 | 83 |
| all 输出数 | 26432 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 41.8 |
| fetch | 7.2 |
| generate | 13.4 |
| geo | 1.5 |
| probe | 104.8 |
| real_test | 54.7 |
| tcp | 82.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 29 | 29 | 0 | 100.0% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 134 | 125 | 9 | 93.3% |
| socks | 8 | 3 | 5 | 37.5% |
| trojan | 32 | 25 | 7 | 78.1% |
| vless | 154 | 103 | 51 | 66.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 49 |
| speed:ClientOSError | 9 |
| geo:ClientOSError | 3 |
| 204:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| geo:ProxyError | 1 |
| 204:TimeoutError | 1 |
| 204:ClientOSError | 1 |
| speed:TimeoutError | 1 |
| cn-block:ProxyError | 1 |
| speed:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6755 |
| ConnectionRefusedError | 1011 |
| OSError | 234 |
| gaierror | 137 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.963 | prefer | 24 | 1.0 | 31 |
| mheidari-all | 0.927 | prefer | 96 | 0.854 | 23621 |
| Surfboard-tg-mixed | 0.856 | prefer | 56 | 0.786 | 6945 |
| Au1rxx-base64 | 0.809 | prefer | 187 | 0.754 | 1438 |
| tg-oneclickvpnkeys | 0.403 | observe | 4 | 1.0 | 74 |
| ninja-vless | 0.327 | observe | 1 | 1.0 | 1791 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| ermaozi-get_subscribe | 0.272 | observe | 1 | 1.0 | 429 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4967 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3519 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 5 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 476 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 367 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 362 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 245 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 223 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 222 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 214 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 192 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 187 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 111 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| Au1rxx-base64 | 0.754 | 141 | 46 | 187 |
| Surfboard-tg-mixed | 0.786 | 44 | 12 | 56 |
| mheidari-all | 0.854 | 82 | 14 | 96 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| ninja-vless | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 4 | 0 | 4 |
| zhangkai | 1.0 | 24 | 0 | 24 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23621 | yes | 5.4 | 0 |
| SoliSpirit-all | 9870 | yes | 5.87 | 0 |
| Epodonios-all | 7425 | yes | 4.72 | 0 |
| Surfboard-tg-mixed | 6945 | yes | 4.29 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.36 | 0 |
| barry-far-vless | 5701 | yes | 1.14 | 0 |
| Surfboard-tg-vless | 5487 | yes | 4.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 4967 | yes | 2.86 | 0 |
| mahdibland-V2RayAggregator | 4127 | yes | 0.2 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.94 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 49 |
| speed | 11 |
| 204 | 5 |
| geo | 4 |
| cn-block | 4 |
