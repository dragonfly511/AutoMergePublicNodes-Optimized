# AutoNodes 每日报告

生成时间：2026-11-14 05:38:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 128227 |
| 去重后节点数 | 58679 |
| TCP 可达数 | 3000 |
| 真测通过数 | 55 |
| verified 输出数 | 55 |
| global 输出数 | 57 |
| all 输出数 | 58679 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 41.3 |
| fetch | 8.9 |
| generate | 31.1 |
| geo | 1.7 |
| probe | 106.5 |
| real_test | 40.5 |
| tcp | 195.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 70 | 68 | 2 | 97.1% |
| hysteria2 | 12 | 12 | 0 | 100.0% |
| shadowsocks | 212 | 197 | 15 | 92.9% |
| socks | 4 | 1 | 3 | 25.0% |
| trojan | 13 | 10 | 3 | 76.9% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 14 |
| speed:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:48591: bind: address already in use | 1 |
| 204:ProxyError | 1 |
| cn-block:ProxyError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14400 |
| ConnectionRefusedError | 2193 |
| gaierror | 773 |
| OSError | 339 |
| SSRFBlocked | 5 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.983 | prefer | 245 | 0.906 | 44709 |
| ermaozi | 0.983 | prefer | 71 | 0.972 | 597 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4900 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2734 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11507 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8942 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6457 |
| barry-far-vless | 0.255 | observe | 0 | None | 6640 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4624 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 444 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 439 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 322 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 300 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 299 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 291 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 264 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 188 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 175 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.906 | 222 | 23 | 245 |
| ermaozi | 0.972 | 69 | 2 | 71 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44709 | yes | 8.09 | 0 |
| mheidari-all | 13877 | yes | 4.57 | 0 |
| SoliSpirit-all | 11507 | yes | 3.1 | 0 |
| Surfboard-tg-mixed | 8942 | yes | 3.65 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.18 | 0 |
| barry-far-vless | 6640 | yes | 2.41 | 0 |
| Surfboard-tg-vless | 6457 | yes | 4.01 | 0 |
| 10ium-ScrapeCategorize-Vless | 4900 | yes | 2.63 | 0 |
| mahdibland-V2RayAggregator | 4624 | yes | 3.28 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.93 | 0 |

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
| test_one_timeout | 14 |
| 204 | 4 |
| speed | 3 |
| cn-block | 3 |
| sing-box exited 1 | 1 |
