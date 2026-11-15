# AutoNodes 每日报告

生成时间：2026-11-15 22:45:14

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 127859 |
| 去重后节点数 | 58100 |
| TCP 可达数 | 3000 |
| 真测通过数 | 85 |
| verified 输出数 | 85 |
| global 输出数 | 91 |
| all 输出数 | 58100 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 31.9 |
| fetch | 33.9 |
| generate | 17.9 |
| geo | 1.5 |
| probe | 95.4 |
| real_test | 60.8 |
| tcp | 199.7 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 0 | 2 | 0.0% |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 17 | 17 | 0 | 100.0% |
| shadowsocks | 225 | 151 | 74 | 67.1% |
| socks | 3 | 2 | 1 | 66.7% |
| trojan | 74 | 59 | 15 | 79.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 71 |
| 204:ProxyError | 9 |
| cn-block:TimeoutError | 6 |
| 204:ClientOSError | 2 |
| cn-block:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42601: bind: address already in use | 1 |
| speed:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14251 |
| ConnectionRefusedError | 2167 |
| gaierror | 606 |
| OSError | 332 |
| SSRFBlocked | 6 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.98 | prefer | 22 | 1.0 | 544 |
| dragon | 0.793 | prefer | 319 | 0.715 | 43748 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 8984 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14826 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4916 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3024 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11600 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6249 |
| barry-far-vless | 0.255 | observe | 0 | None | 6342 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 449 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 444 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 327 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 305 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 304 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 296 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 274 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 193 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 180 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| xiaoji235-airport-v2ray-all | 0.0 | 0 | 1 | 1 |
| dragon | 0.715 | 228 | 91 | 319 |
| mheidari-all | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |
| ermaozi | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44363 | yes | 49.76 | 0 |
| mheidari-all | 14826 | yes | 3.57 | 0 |
| SoliSpirit-all | 11600 | yes | 1.08 | 0 |
| Surfboard-tg-mixed | 8984 | yes | 2.28 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.5 | 0 |
| barry-far-vless | 6342 | yes | 0.3 | 0 |
| Surfboard-tg-vless | 6249 | yes | 2.02 | 0 |
| 10ium-ScrapeCategorize-Vless | 4916 | yes | 0.8 | 0 |
| mahdibland-V2RayAggregator | 4550 | yes | 1.65 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.47 | 0 |

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
| test_one_timeout | 71 |
| 204 | 11 |
| cn-block | 8 |
| sing-box exited 1 | 1 |
| speed | 1 |
