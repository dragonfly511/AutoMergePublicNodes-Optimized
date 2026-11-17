# AutoNodes 每日报告

生成时间：2026-11-17 01:50:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 127540 |
| 去重后节点数 | 58452 |
| TCP 可达数 | 3000 |
| 真测通过数 | 91 |
| verified 输出数 | 91 |
| global 输出数 | 92 |
| all 输出数 | 58452 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 31.7 |
| fetch | 5.8 |
| generate | 18.7 |
| geo | 1.5 |
| probe | 92.9 |
| real_test | 48.7 |
| tcp | 172.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 76 | 71 | 5 | 93.4% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 238 | 228 | 10 | 95.8% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 45 | 32 | 13 | 71.1% |
| vless | 3 | 1 | 2 | 33.3% |
| vmess | 2 | 1 | 1 | 50.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 19 |
| geo:ClientOSError | 5 |
| 204:ProxyError | 3 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |
| speed:TimeoutError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 12835 |
| ConnectionRefusedError | 2266 |
| gaierror | 1067 |
| OSError | 613 |
| SSRFBlocked | 5 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.98 | prefer | 307 | 0.902 | 44193 |
| ermaozi | 0.95 | prefer | 78 | 0.936 | 621 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14735 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4964 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2915 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11573 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8623 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6028 |
| barry-far-vless | 0.255 | observe | 0 | None | 6209 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 452 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 447 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 330 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 308 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 307 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 299 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 277 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 272 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 196 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 183 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.902 | 277 | 30 | 307 |
| ermaozi | 0.936 | 73 | 5 | 78 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44193 | yes | 5.06 | 0 |
| mheidari-all | 14735 | yes | 3.82 | 0 |
| SoliSpirit-all | 11573 | yes | 1.34 | 0 |
| Surfboard-tg-mixed | 8623 | yes | 2.7 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.58 | 0 |
| barry-far-vless | 6209 | yes | 0.51 | 0 |
| Surfboard-tg-vless | 6028 | yes | 2.5 | 0 |
| 10ium-ScrapeCategorize-Vless | 4964 | yes | 0.64 | 0 |
| mahdibland-V2RayAggregator | 4545 | yes | 0.13 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.72 | 0 |

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
| test_one_timeout | 19 |
| 204 | 6 |
| geo | 6 |
| cn-block | 3 |
| speed | 1 |
