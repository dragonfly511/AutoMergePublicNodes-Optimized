# AutoNodes 每日报告

生成时间：2026-10-20 16:10:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 4/89 |
| 原始节点数 | 94114 |
| 去重后节点数 | 26477 |
| TCP 可达数 | 3000 |
| 真测通过数 | 78 |
| verified 输出数 | 78 |
| global 输出数 | 81 |
| all 输出数 | 26477 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.3 |
| fetch | 7.2 |
| generate | 13.4 |
| geo | 1.5 |
| probe | 101.1 |
| real_test | 66.1 |
| tcp | 80.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 37 | 34 | 3 | 91.9% |
| hysteria2 | 12 | 9 | 3 | 75.0% |
| shadowsocks | 119 | 103 | 16 | 86.6% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 34 | 27 | 7 | 79.4% |
| vless | 184 | 119 | 65 | 64.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 64 |
| speed:ClientOSError | 11 |
| 204:ProxyError | 5 |
| geo:ClientOSError | 4 |
| 204:TimeoutError | 3 |
| cn-block:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42989: bind: address already in use | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6506 |
| ConnectionRefusedError | 1043 |
| OSError | 235 |
| gaierror | 216 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.894 | prefer | 26 | 0.923 | 31 |
| mheidari-all | 0.848 | prefer | 67 | 0.776 | 23236 |
| Surfboard-tg-mixed | 0.843 | prefer | 36 | 0.778 | 6911 |
| Au1rxx-base64 | 0.771 | prefer | 249 | 0.719 | 1337 |
| ermaozi-get_subscribe | 0.636 | observe | 10 | 1.0 | 429 |
| Barabama-yudou | 0.262 | observe | 1 | 1.0 | 166 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4967 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3519 |
| Epodonios-all | 0.255 | observe | 0 | None | 7384 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-oneclickvpnkeys | 0.131 | observe | 1 | 0.0 | 0 | 79 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 475 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 366 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 361 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 244 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 222 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 221 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 213 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 191 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 186 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 110 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| Au1rxx-base64 | 0.719 | 179 | 70 | 249 |
| mheidari-all | 0.776 | 52 | 15 | 67 |
| Surfboard-tg-mixed | 0.778 | 28 | 8 | 36 |
| zhangkai | 0.923 | 24 | 2 | 26 |
| Barabama-yudou | 1.0 | 1 | 0 | 1 |
| ermaozi-get_subscribe | 1.0 | 10 | 0 | 10 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23236 | yes | 5.63 | 0 |
| SoliSpirit-all | 9911 | yes | 5.69 | 0 |
| Epodonios-all | 7384 | yes | 5.93 | 0 |
| Surfboard-tg-mixed | 6911 | yes | 3.5 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.98 | 0 |
| barry-far-vless | 5732 | yes | 0.95 | 0 |
| Surfboard-tg-vless | 5515 | yes | 4.19 | 0 |
| 10ium-ScrapeCategorize-Vless | 4967 | yes | 2.91 | 0 |
| mahdibland-V2RayAggregator | 4278 | yes | 3.07 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 64 |
| speed | 11 |
| 204 | 10 |
| cn-block | 6 |
| geo | 4 |
| sing-box exited 1 | 1 |
