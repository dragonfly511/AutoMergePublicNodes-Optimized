# AutoNodes 每日报告

生成时间：2026-11-06 05:46:44

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 128615 |
| 去重后节点数 | 59071 |
| TCP 可达数 | 3000 |
| 真测通过数 | 119 |
| verified 输出数 | 119 |
| global 输出数 | 119 |
| all 输出数 | 59071 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 26.8 |
| fetch | 4.9 |
| generate | 19.5 |
| geo | 1.5 |
| probe | 70.5 |
| real_test | 32.7 |
| tcp | 197.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 101 | 99 | 2 | 98.0% |
| hysteria2 | 20 | 17 | 3 | 85.0% |
| shadowsocks | 22 | 18 | 4 | 81.8% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 84 | 76 | 8 | 90.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 8 |
| cn-block:ProxyError | 5 |
| 204:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:39783: bind: address already in use | 1 |
| 204:ClientOSError | 1 |
| speed:TimeoutError | 1 |
| speed:ClientPayloadError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15392 |
| ConnectionRefusedError | 2502 |
| gaierror | 448 |
| OSError | 336 |
| ConnectionResetError | 1 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.996 | prefer | 101 | 0.98 | 639 |
| dragon | 0.944 | prefer | 130 | 0.869 | 45886 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8762 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5039 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2653 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10892 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6268 |
| barry-far-vless | 0.255 | observe | 0 | None | 6478 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 422 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 417 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 300 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 278 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 277 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 247 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 242 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 166 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 153 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.869 | 113 | 17 | 130 |
| ermaozi | 0.98 | 99 | 2 | 101 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45886 | yes | 4.29 | 0 |
| mheidari-all | 14233 | yes | 2.73 | 0 |
| SoliSpirit-all | 10892 | yes | 2.12 | 0 |
| Surfboard-tg-mixed | 8762 | yes | 2.23 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.78 | 0 |
| barry-far-vless | 6478 | yes | 0.4 | 0 |
| Surfboard-tg-vless | 6268 | yes | 1.78 | 0 |
| 10ium-ScrapeCategorize-Vless | 5039 | yes | 0.55 | 0 |
| mahdibland-V2RayAggregator | 4631 | yes | 1.6 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.24 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 8 |
| cn-block | 5 |
| 204 | 3 |
| speed | 2 |
| sing-box exited 1 | 1 |
