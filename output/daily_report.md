# AutoNodes 每日报告

生成时间：2026-11-11 05:23:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127580 |
| 去重后节点数 | 59612 |
| TCP 可达数 | 3000 |
| 真测通过数 | 108 |
| verified 输出数 | 108 |
| global 输出数 | 108 |
| all 输出数 | 59612 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.5 |
| fetch | 9.0 |
| generate | 31.9 |
| geo | 1.7 |
| probe | 99.0 |
| real_test | 39.0 |
| tcp | 195.0 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 82 | 81 | 1 | 98.8% |
| hysteria2 | 15 | 12 | 3 | 80.0% |
| shadowsocks | 9 | 9 | 0 | 100.0% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 100 | 87 | 13 | 87.0% |
| vmess | 3 | 2 | 1 | 66.7% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 8 |
| 204:ProxyError | 6 |
| 204:ClientOSError | 3 |
| speed:ClientOSError | 1 |
| cn-block:ProxyError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:37994: bind: address already in use | 1 |
| cn-block:TimeoutError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14701 |
| ConnectionRefusedError | 2443 |
| gaierror | 640 |
| OSError | 357 |
| ConnectionResetError | 4 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | prefer | 82 | 0.988 | 601 |
| dragon | 0.923 | prefer | 132 | 0.848 | 45201 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 13964 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4955 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2620 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11127 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8415 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6298 |
| barry-far-vless | 0.255 | observe | 0 | None | 6562 |

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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 436 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 431 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 314 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 292 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 291 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 283 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 256 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 180 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 167 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| dragon | 0.848 | 112 | 20 | 132 |
| ermaozi | 0.988 | 81 | 1 | 82 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45201 | yes | 8.2 | 0 |
| mheidari-all | 13964 | yes | 5.1 | 0 |
| SoliSpirit-all | 11127 | yes | 3.24 | 0 |
| Surfboard-tg-mixed | 8415 | yes | 4.25 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.76 | 0 |
| barry-far-vless | 6562 | yes | 1.41 | 0 |
| Surfboard-tg-vless | 6298 | yes | 3.68 | 0 |
| 10ium-ScrapeCategorize-Vless | 4955 | yes | 0.84 | 0 |
| mahdibland-V2RayAggregator | 4595 | yes | 3.23 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.49 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 9 |
| test_one_timeout | 8 |
| speed | 2 |
| cn-block | 2 |
| sing-box exited 1 | 1 |
