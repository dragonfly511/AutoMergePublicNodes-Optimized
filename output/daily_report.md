# AutoNodes 每日报告

生成时间：2026-10-23 06:49:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 3/90 |
| 原始节点数 | 96274 |
| 去重后节点数 | 26716 |
| TCP 可达数 | 3000 |
| 真测通过数 | 133 |
| verified 输出数 | 133 |
| global 输出数 | 138 |
| all 输出数 | 26716 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.7 |
| fetch | 7.2 |
| generate | 13.4 |
| geo | 1.8 |
| probe | 100.8 |
| real_test | 84.9 |
| tcp | 84.6 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 98 | 98 | 0 | 100.0% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 154 | 135 | 19 | 87.7% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 42 | 35 | 7 | 83.3% |
| vless | 227 | 112 | 115 | 49.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 96 |
| speed:ClientOSError | 20 |
| geo:ClientOSError | 10 |
| cn-block:ClientOSError | 4 |
| 204:TimeoutError | 3 |
| cn-block:ProxyError | 2 |
| 204:ProxyError | 2 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:40248: bind: address already in use | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6642 |
| ConnectionRefusedError | 1042 |
| OSError | 237 |
| gaierror | 167 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | prefer | 99 | 1.0 | 609 |
| Surfboard-tg-mixed | 0.865 | prefer | 63 | 0.794 | 6999 |
| Au1rxx-base64 | 0.765 | prefer | 207 | 0.705 | 1533 |
| mheidari-all | 0.673 | observe | 165 | 0.594 | 23958 |
| ninja-vless | 0.34 | observe | 3 | 0.667 | 1791 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4911 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3641 |
| Epodonios-all | 0.255 | observe | 0 | None | 7509 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10117 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
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
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 485 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 376 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 371 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 254 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 232 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 231 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 223 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 201 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 196 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 120 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.594 | 98 | 67 | 165 |
| ninja-vless | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.705 | 146 | 61 | 207 |
| Surfboard-tg-mixed | 0.794 | 50 | 13 | 63 |
| ermaozi | 1.0 | 99 | 0 | 99 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23958 | yes | 5.7 | 0 |
| SoliSpirit-all | 10117 | yes | 6.75 | 0 |
| Epodonios-all | 7509 | yes | 5.89 | 0 |
| Surfboard-tg-mixed | 6999 | yes | 6.71 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.34 | 0 |
| barry-far-vless | 5666 | yes | 2.69 | 0 |
| Surfboard-tg-vless | 5447 | yes | 4.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 4911 | yes | 4.87 | 0 |
| mahdibland-V2RayAggregator | 4230 | yes | 3.68 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.77 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 96 |
| speed | 20 |
| geo | 13 |
| 204 | 7 |
| cn-block | 6 |
| sing-box exited 1 | 1 |
