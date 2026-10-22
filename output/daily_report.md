# AutoNodes 每日报告

生成时间：2026-10-22 02:44:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 91/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 5/88 |
| 原始节点数 | 96930 |
| 去重后节点数 | 27034 |
| TCP 可达数 | 3000 |
| 真测通过数 | 84 |
| verified 输出数 | 84 |
| global 输出数 | 92 |
| all 输出数 | 27034 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 31.6 |
| fetch | 8.7 |
| generate | 14.0 |
| geo | 1.6 |
| probe | 107.3 |
| real_test | 70.0 |
| tcp | 80.8 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 60 | 59 | 1 | 98.3% |
| hysteria2 | 15 | 14 | 1 | 93.3% |
| shadowsocks | 166 | 152 | 14 | 91.6% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 45 | 42 | 3 | 93.3% |
| vless | 261 | 130 | 131 | 49.8% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 84 |
| speed:ClientOSError | 36 |
| geo:ClientOSError | 12 |
| cn-block:ClientOSError | 7 |
| 204:ProxyError | 4 |
| cn-block:TimeoutError | 4 |
| 204:ClientOSError | 3 |
| 204:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6538 |
| ConnectionRefusedError | 1037 |
| OSError | 240 |
| gaierror | 226 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.965 | prefer | 34 | 0.971 | 523 |
| zhangkai | 0.93 | prefer | 26 | 0.962 | 31 |
| Surfboard-tg-mixed | 0.88 | prefer | 53 | 0.811 | 7097 |
| Au1rxx-base64 | 0.791 | prefer | 222 | 0.73 | 1587 |
| mheidari-all | 0.707 | prefer | 215 | 0.628 | 24252 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 92 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4925 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 4067 |
| Epodonios-all | 0.255 | observe | 0 | None | 7591 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
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
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 481 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 372 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 367 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 250 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 228 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 227 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 219 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 197 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 192 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 116 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.628 | 135 | 80 | 215 |
| Au1rxx-base64 | 0.73 | 162 | 60 | 222 |
| Surfboard-tg-mixed | 0.811 | 43 | 10 | 53 |
| zhangkai | 0.962 | 25 | 1 | 26 |
| ermaozi-get_subscribe | 0.971 | 33 | 1 | 34 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24252 | yes | 6.4 | 0 |
| SoliSpirit-all | 10124 | yes | 3.52 | 0 |
| Epodonios-all | 7591 | yes | 5.64 | 0 |
| Surfboard-tg-mixed | 7097 | yes | 4.08 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.04 | 0 |
| barry-far-vless | 5773 | yes | 1.26 | 0 |
| Surfboard-tg-vless | 5559 | yes | 4.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 4925 | yes | 0.5 | 0 |
| mahdibland-V2RayAggregator | 4164 | yes | 3.4 | 0 |
| DeltaKronecker-all | 4067 | yes | 6.48 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 84 |
| speed | 36 |
| geo | 12 |
| cn-block | 11 |
| 204 | 9 |
