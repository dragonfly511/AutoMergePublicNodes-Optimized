# AutoNodes 每日报告

生成时间：2026-11-08 05:12:23

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 126496 |
| 去重后节点数 | 58753 |
| TCP 可达数 | 3000 |
| 真测通过数 | 86 |
| verified 输出数 | 86 |
| global 输出数 | 86 |
| all 输出数 | 58753 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 38.7 |
| fetch | 8.5 |
| generate | 30.5 |
| geo | 1.7 |
| probe | 109.8 |
| real_test | 42.5 |
| tcp | 194.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 91 | 87 | 4 | 95.6% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 209 | 199 | 10 | 95.2% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 66 | 60 | 6 | 90.9% |
| vless | 5 | 2 | 3 | 40.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 12 |
| speed:TimeoutError | 6 |
| 204:ClientOSError | 2 |
| 204:ProxyError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:37874: bind: address already in use | 1 |
| cn-block:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14962 |
| ConnectionRefusedError | 2394 |
| gaierror | 494 |
| OSError | 298 |
| SSRFBlocked | 6 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 299 | 0.93 | 45338 |
| ermaozi | 0.971 | prefer | 91 | 0.956 | 613 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14102 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4866 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2734 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3996 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11000 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8112 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5849 |
| barry-far-vless | 0.255 | observe | 0 | None | 6090 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 428 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 423 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 306 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 284 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 283 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 275 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 253 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 248 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 172 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 159 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.93 | 278 | 21 | 299 |
| ermaozi | 0.956 | 87 | 4 | 91 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45338 | yes | 7.84 | 0 |
| mheidari-all | 14102 | yes | 4.83 | 0 |
| SoliSpirit-all | 11000 | yes | 3.2 | 0 |
| Surfboard-tg-mixed | 8112 | yes | 3.24 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.6 | 0 |
| barry-far-vless | 6090 | yes | 1.19 | 0 |
| Surfboard-tg-vless | 5849 | yes | 3.69 | 0 |
| 10ium-ScrapeCategorize-Vless | 4866 | yes | 1.53 | 0 |
| mahdibland-V2RayAggregator | 4529 | yes | 3.4 | 0 |
| MatinGhanbari-all-sub | 3996 | yes | 1.29 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 12 |
| speed | 6 |
| 204 | 4 |
| sing-box exited 1 | 1 |
| cn-block | 1 |
| geo | 1 |
