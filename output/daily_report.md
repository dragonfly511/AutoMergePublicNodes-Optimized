# AutoNodes 每日报告

生成时间：2026-11-04 05:32:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 128602 |
| 去重后节点数 | 58753 |
| TCP 可达数 | 3000 |
| 真测通过数 | 77 |
| verified 输出数 | 77 |
| global 输出数 | 78 |
| all 输出数 | 58753 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 28.0 |
| fetch | 7.9 |
| generate | 26.4 |
| geo | 1.7 |
| probe | 114.9 |
| real_test | 57.3 |
| tcp | 207.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 21 | 20 | 1 | 95.2% |
| hysteria2 | 15 | 12 | 3 | 80.0% |
| shadowsocks | 240 | 226 | 14 | 94.2% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 11 | 11 | 0 | 100.0% |
| vless | 9 | 2 | 7 | 22.2% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 16 |
| geo:ClientOSError | 4 |
| cn-block:ClientOSError | 2 |
| 204:ProxyError | 1 |
| 204:TimeoutError | 1 |
| 204:ClientOSError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:45452: bind: address already in use | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14627 |
| ConnectionRefusedError | 2375 |
| gaierror | 531 |
| OSError | 317 |
| SSRFBlocked | 2 |
| UnicodeError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.985 | prefer | 281 | 0.907 | 45574 |
| ermaozi | 0.932 | prefer | 20 | 0.95 | 578 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 8544 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 115 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5017 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2526 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10853 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6022 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 416 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 411 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 294 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 272 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 271 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 263 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 241 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 236 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 160 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 147 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.907 | 255 | 26 | 281 |
| ermaozi | 0.95 | 19 | 1 | 20 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45574 | yes | 7.27 | 0 |
| mheidari-all | 15265 | yes | 5.21 | 0 |
| SoliSpirit-all | 10853 | yes | 2.85 | 0 |
| Surfboard-tg-mixed | 8544 | yes | 3.54 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.02 | 0 |
| barry-far-vless | 6238 | yes | 1.18 | 0 |
| Surfboard-tg-vless | 6022 | yes | 3.73 | 0 |
| 10ium-ScrapeCategorize-Vless | 5017 | yes | 0.52 | 0 |
| mahdibland-V2RayAggregator | 4753 | yes | 2.89 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.27 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 16 |
| geo | 4 |
| 204 | 3 |
| cn-block | 3 |
| sing-box exited 1 | 1 |
