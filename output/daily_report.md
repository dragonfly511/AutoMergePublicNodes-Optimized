# AutoNodes 每日报告

生成时间：2026-11-08 21:57:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 126502 |
| 去重后节点数 | 58460 |
| TCP 可达数 | 3000 |
| 真测通过数 | 92 |
| verified 输出数 | 92 |
| global 输出数 | 93 |
| all 输出数 | 58460 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 37.3 |
| fetch | 7.5 |
| generate | 25.9 |
| geo | 1.6 |
| probe | 114.2 |
| real_test | 46.5 |
| tcp | 193.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| http | 56 | 53 | 3 | 94.6% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 218 | 200 | 18 | 91.7% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 24 | 20 | 4 | 83.3% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 17 |
| 204:ClientOSError | 4 |
| cn-block:ClientOSError | 3 |
| 204:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48016: bind: address already in use | 1 |
| speed:TimeoutError | 1 |
| 204:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14485 |
| ConnectionRefusedError | 2318 |
| gaierror | 473 |
| OSError | 317 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.986 | prefer | 263 | 0.909 | 45021 |
| ermaozi | 0.954 | prefer | 56 | 0.946 | 586 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5035 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3024 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10978 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8189 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5913 |
| barry-far-vless | 0.255 | observe | 0 | None | 6025 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4597 |

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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 430 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 425 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 308 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 286 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 285 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 277 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 255 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 250 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 174 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 161 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.0 | 0 | 1 | 1 |
| dragon | 0.909 | 239 | 24 | 263 |
| ermaozi | 0.946 | 53 | 3 | 56 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45021 | yes | 6.78 | 0 |
| mheidari-all | 13955 | yes | 3.88 | 0 |
| SoliSpirit-all | 10978 | yes | 4.27 | 0 |
| Surfboard-tg-mixed | 8189 | yes | 4.2 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.23 | 0 |
| barry-far-vless | 6025 | yes | 2.14 | 0 |
| Surfboard-tg-vless | 5913 | yes | 3.49 | 0 |
| 10ium-ScrapeCategorize-Vless | 5035 | yes | 2.38 | 0 |
| mahdibland-V2RayAggregator | 4597 | yes | 2.74 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.04 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 17 |
| 204 | 7 |
| cn-block | 3 |
| sing-box exited 1 | 1 |
| speed | 1 |
