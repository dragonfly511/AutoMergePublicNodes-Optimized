# AutoNodes 每日报告

生成时间：2026-11-19 07:21:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127250 |
| 去重后节点数 | 59221 |
| TCP 可达数 | 3000 |
| 真测通过数 | 104 |
| verified 输出数 | 104 |
| global 输出数 | 111 |
| all 输出数 | 59221 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 49.4 |
| fetch | 8.7 |
| generate | 31.0 |
| geo | 1.7 |
| probe | 116.8 |
| real_test | 56.4 |
| tcp | 187.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 7 | 3 | 4 | 42.9% |
| http | 26 | 23 | 3 | 88.5% |
| hysteria2 | 12 | 9 | 3 | 75.0% |
| shadowsocks | 232 | 206 | 26 | 88.8% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 16 | 16 | 0 | 100.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 23 |
| cn-block:ClientOSError | 7 |
| 204:ClientOSError | 2 |
| 204:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| speed:TimeoutError | 1 |
| 204:ProxyConnectionError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14313 |
| ConnectionRefusedError | 2379 |
| gaierror | 697 |
| OSError | 328 |
| SSRFBlocked | 4 |
| ConnectionResetError | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.951 | prefer | 269 | 0.874 | 45096 |
| ermaozi | 0.877 | prefer | 26 | 0.885 | 494 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14200 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4919 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2925 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11797 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8472 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5689 |
| barry-far-vless | 0.255 | observe | 0 | None | 5975 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 457 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 452 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 335 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 313 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 312 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 304 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 282 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 277 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 201 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 188 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.874 | 235 | 34 | 269 |
| ermaozi | 0.885 | 23 | 3 | 26 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45096 | yes | 7.73 | 0 |
| mheidari-all | 14200 | yes | 4.76 | 0 |
| SoliSpirit-all | 11797 | yes | 4.47 | 0 |
| Surfboard-tg-mixed | 8472 | yes | 3.67 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.46 | 0 |
| barry-far-vless | 5975 | yes | 2.8 | 0 |
| Surfboard-tg-vless | 5689 | yes | 3.42 | 0 |
| 10ium-ScrapeCategorize-Vless | 4919 | yes | 2.51 | 0 |
| mahdibland-V2RayAggregator | 4458 | yes | 3.13 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.6 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 23 |
| cn-block | 8 |
| 204 | 5 |
| speed | 1 |
