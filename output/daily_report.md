# AutoNodes 每日报告

生成时间：2026-10-20 10:48:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 4/89 |
| 原始节点数 | 94094 |
| 去重后节点数 | 26444 |
| TCP 可达数 | 3000 |
| 真测通过数 | 118 |
| verified 输出数 | 118 |
| global 输出数 | 121 |
| all 输出数 | 26444 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 31.1 |
| fetch | 6.5 |
| generate | 11.5 |
| geo | 1.6 |
| probe | 102.9 |
| real_test | 77.0 |
| tcp | 80.0 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 74 | 72 | 2 | 97.3% |
| hysteria2 | 12 | 9 | 3 | 75.0% |
| shadowsocks | 134 | 120 | 14 | 89.6% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 31 | 20 | 11 | 64.5% |
| vless | 180 | 111 | 69 | 61.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 56 |
| speed:ClientOSError | 12 |
| geo:ClientOSError | 9 |
| 204:ProxyError | 5 |
| cn-block:ClientOSError | 5 |
| 204:ClientOSError | 3 |
| 204:TimeoutError | 3 |
| speed:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:32205: bind: address already in use | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42974: bind: address already in use | 1 |
| geo:ProxyError | 1 |
| cn-block:ProxyError | 1 |
| speed:TimeoutError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6535 |
| ConnectionRefusedError | 1037 |
| OSError | 236 |
| gaierror | 222 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| mheidari-all | 0.991 | prefer | 54 | 0.926 | 23400 |
| ermaozi-get_subscribe | 0.967 | prefer | 54 | 0.963 | 510 |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 27 |
| Au1rxx-base64 | 0.784 | prefer | 222 | 0.739 | 1180 |
| Surfboard-tg-mixed | 0.658 | observe | 81 | 0.58 | 6911 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4967 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3519 |
| Epodonios-all | 0.255 | observe | 0 | None | 7377 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9888 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 474 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 365 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 360 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 243 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 221 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 220 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 212 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 190 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 185 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 109 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 2 | 2 |
| Surfboard-tg-mixed | 0.58 | 47 | 34 | 81 |
| Au1rxx-base64 | 0.739 | 164 | 58 | 222 |
| mheidari-all | 0.926 | 50 | 4 | 54 |
| ermaozi-get_subscribe | 0.963 | 52 | 2 | 54 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23400 | yes | 5.85 | 0 |
| SoliSpirit-all | 9888 | yes | 5.99 | 0 |
| Epodonios-all | 7377 | yes | 4.64 | 0 |
| Surfboard-tg-mixed | 6911 | yes | 3.48 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.92 | 0 |
| barry-far-vless | 5733 | yes | 1.59 | 0 |
| Surfboard-tg-vless | 5515 | yes | 4.41 | 0 |
| 10ium-ScrapeCategorize-Vless | 4967 | yes | 1.4 | 0 |
| mahdibland-V2RayAggregator | 4278 | yes | 2.27 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.54 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 56 |
| speed | 15 |
| 204 | 11 |
| geo | 10 |
| cn-block | 7 |
| sing-box exited 1 | 2 |
