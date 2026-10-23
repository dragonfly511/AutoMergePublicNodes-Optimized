# AutoNodes 每日报告

生成时间：2026-10-23 07:44:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | critical |
| 健康检查通过 | False |
| 健康源数量 | 93/108 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 1/93 |
| 原始节点数 | 141282 |
| 去重后节点数 | 57939 |
| TCP 可达数 | 3000 |
| 真测通过数 | 108 |
| verified 输出数 | 108 |
| global 输出数 | 110 |
| all 输出数 | 57939 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 23.4 |
| fetch | 8.2 |
| generate | 27.2 |
| geo | 1.7 |
| probe | 127.2 |
| real_test | 51.4 |
| tcp | 201.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 101 | 61 | 40 | 60.4% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 143 | 132 | 11 | 92.3% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 27 | 20 | 7 | 74.1% |
| vless | 38 | 14 | 24 | 36.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 33 |
| 204:ProxyError | 12 |
| cn-block:ProxyError | 10 |
| geo:ProxyError | 10 |
| geo:ClientOSError | 7 |
| speed:ProxyError | 6 |
| speed:ClientOSError | 3 |
| cn-block:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:41196: bind: address already in use | 1 |
| 204:TimeoutError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15792 |
| ConnectionRefusedError | 2553 |
| gaierror | 540 |
| OSError | 331 |
| SSRFBlocked | 1 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.958 | prefer | 186 | 0.882 | 45037 |
| ermaozi | 0.63 | observe | 102 | 0.608 | 609 |
| Surfboard-tg-mixed | 0.441 | observe | 13 | 0.462 | 6999 |
| Au1rxx-base64 | 0.406 | observe | 15 | 0.4 | 1530 |
| mheidari-all | 0.389 | observe | 13 | 0.385 | 23958 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4911 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3641 |
| Epodonios-all | 0.255 | observe | 0 | None | 7509 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10102 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 5 |
| tg-freeiranianv2rey | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 486 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 377 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 372 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 255 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 233 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 232 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 224 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 202 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 197 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 121 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.385 | 5 | 8 | 13 |
| Au1rxx-base64 | 0.4 | 6 | 9 | 15 |
| Surfboard-tg-mixed | 0.462 | 6 | 7 | 13 |
| ermaozi | 0.608 | 62 | 40 | 102 |
| dragon | 0.882 | 164 | 22 | 186 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45037 | yes | 8.13 | 0 |
| mheidari-all | 23958 | yes | 5.95 | 0 |
| SoliSpirit-all | 10102 | yes | 3.27 | 0 |
| Epodonios-all | 7509 | yes | 5.0 | 0 |
| Surfboard-tg-mixed | 6999 | yes | 3.53 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.52 | 0 |
| barry-far-vless | 5662 | yes | 1.69 | 0 |
| Surfboard-tg-vless | 5447 | yes | 3.71 | 0 |
| 10ium-ScrapeCategorize-Vless | 4911 | yes | 0.83 | 0 |
| mahdibland-V2RayAggregator | 4230 | yes | 0.15 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 33 |
| geo | 17 |
| 204 | 14 |
| cn-block | 12 |
| speed | 9 |
| sing-box exited 1 | 1 |
