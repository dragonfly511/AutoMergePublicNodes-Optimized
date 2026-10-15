# AutoNodes 每日报告

生成时间：2026-10-15 12:26:33

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 2/92 |
| 原始节点数 | 100008 |
| 去重后节点数 | 27884 |
| TCP 可达数 | 3000 |
| 真测通过数 | 95 |
| verified 输出数 | 95 |
| global 输出数 | 103 |
| all 输出数 | 27884 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.9 |
| fetch | 7.9 |
| generate | 13.9 |
| geo | 1.5 |
| probe | 105.0 |
| real_test | 64.1 |
| tcp | 86.4 |
| write_verified | 0.2 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 76 | 75 | 1 | 98.7% |
| hysteria2 | 10 | 8 | 2 | 80.0% |
| shadowsocks | 127 | 117 | 10 | 92.1% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 9 | 4 | 5 | 44.4% |
| vless | 184 | 101 | 83 | 54.9% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 58 |
| speed:ClientOSError | 11 |
| 204:ProxyError | 9 |
| 204:TimeoutError | 6 |
| geo:ClientOSError | 5 |
| cn-block:ClientOSError | 5 |
| cn-block:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6899 |
| ConnectionRefusedError | 1035 |
| gaierror | 242 |
| OSError | 233 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | prefer | 77 | 0.987 | 703 |
| Au1rxx-base64 | 0.782 | prefer | 307 | 0.71 | 1830 |
| mheidari-all | 0.6 | observe | 23 | 0.522 | 24080 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 7139 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5089 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 5147 |
| Epodonios-all | 0.255 | observe | 0 | None | 7652 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10114 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5693 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 456 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 347 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 342 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 225 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 203 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 202 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 194 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 172 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 167 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 91 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.522 | 12 | 11 | 23 |
| Au1rxx-base64 | 0.71 | 218 | 89 | 307 |
| ermaozi | 0.987 | 76 | 1 | 77 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24080 | yes | 7.58 | 0 |
| SoliSpirit-all | 10114 | yes | 3.37 | 0 |
| Epodonios-all | 7652 | yes | 5.18 | 0 |
| Surfboard-tg-mixed | 7139 | yes | 4.4 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.04 | 0 |
| barry-far-vless | 5924 | yes | 2.09 | 0 |
| Surfboard-tg-vless | 5693 | yes | 4.61 | 0 |
| DeltaKronecker-all | 5147 | yes | 5.62 | 0 |
| 10ium-ScrapeCategorize-Vless | 5089 | yes | 1.32 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 3.67 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 58 |
| 204 | 17 |
| speed | 11 |
| cn-block | 10 |
| geo | 6 |
