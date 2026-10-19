# AutoNodes 每日报告

生成时间：2026-10-19 18:07:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 1/92 |
| 原始节点数 | 94237 |
| 去重后节点数 | 26065 |
| TCP 可达数 | 3000 |
| 真测通过数 | 63 |
| verified 输出数 | 63 |
| global 输出数 | 68 |
| all 输出数 | 26065 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 35.1 |
| fetch | 7.8 |
| generate | 13.0 |
| geo | 1.5 |
| probe | 110.1 |
| real_test | 63.3 |
| tcp | 80.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 15 | 15 | 0 | 100.0% |
| hysteria2 | 19 | 14 | 5 | 73.7% |
| shadowsocks | 108 | 101 | 7 | 93.5% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 13 | 10 | 3 | 76.9% |
| vless | 174 | 110 | 64 | 63.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 46 |
| speed:ClientOSError | 13 |
| 204:TimeoutError | 5 |
| cn-block:TimeoutError | 4 |
| geo:ClientOSError | 4 |
| 204:ProxyError | 3 |
| cn-block:ClientOSError | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:32952: bind: address already in use | 1 |
| speed:ProxyError | 1 |
| 204:ClientOSError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6552 |
| ConnectionRefusedError | 1031 |
| OSError | 239 |
| gaierror | 157 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| Au1rxx-base64 | 0.85 | prefer | 269 | 0.788 | 1598 |
| mheidari-all | 0.642 | observe | 30 | 0.567 | 23148 |
| ermaozi-get_subscribe | 0.569 | observe | 8 | 1.0 | 508 |
| zhangkai | 0.478 | observe | 6 | 1.0 | 27 |
| Surfboard-tg-mixed | 0.407 | observe | 18 | 0.333 | 6948 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 172 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 77 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4940 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3294 |
| Epodonios-all | 0.255 | observe | 0 | None | 7406 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 4 |
| tg-freeiranianv2rey | 0.175 | observe | 0 | None | 0 | 12 |
| tg-freevpnconfigso | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 472 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 363 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 358 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 241 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 219 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 218 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 210 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 188 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 183 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 107 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.333 | 6 | 12 | 18 |
| mheidari-all | 0.567 | 17 | 13 | 30 |
| Au1rxx-base64 | 0.788 | 212 | 57 | 269 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 6 | 0 | 6 |
| ermaozi-get_subscribe | 1.0 | 8 | 0 | 8 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23148 | yes | 5.71 | 0 |
| SoliSpirit-all | 9800 | yes | 6.15 | 0 |
| Epodonios-all | 7406 | yes | 6.0 | 0 |
| Surfboard-tg-mixed | 6948 | yes | 2.97 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.93 | 0 |
| barry-far-vless | 5654 | yes | 2.59 | 0 |
| Surfboard-tg-vless | 5438 | yes | 5.07 | 0 |
| 10ium-ScrapeCategorize-Vless | 4940 | yes | 1.59 | 0 |
| mahdibland-V2RayAggregator | 4314 | yes | 2.34 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.67 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 46 |
| speed | 14 |
| 204 | 9 |
| cn-block | 8 |
| geo | 4 |
| sing-box exited 1 | 1 |
