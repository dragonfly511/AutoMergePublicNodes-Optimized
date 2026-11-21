# AutoNodes 每日报告

生成时间：2026-11-21 18:58:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/89 |
| 原始节点数 | 127585 |
| 去重后节点数 | 59382 |
| TCP 可达数 | 3000 |
| 真测通过数 | 27 |
| verified 输出数 | 27 |
| global 输出数 | 28 |
| all 输出数 | 59382 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 42.0 |
| fetch | 8.6 |
| generate | 31.4 |
| geo | 1.7 |
| probe | 98.3 |
| real_test | 35.7 |
| tcp | 196.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 6 | 5 | 1 | 83.3% |
| http | 19 | 19 | 0 | 100.0% |
| hysteria2 | 15 | 10 | 5 | 66.7% |
| shadowsocks | 2 | 2 | 0 | 100.0% |
| socks | 8 | 6 | 2 | 75.0% |
| trojan | 40 | 14 | 26 | 35.0% |
| vless | 1 | 1 | 0 | 100.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 18 |
| test_one_timeout:15.0s | 10 |
| cn-block:ProxyError | 3 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14578 |
| ConnectionRefusedError | 2324 |
| gaierror | 572 |
| OSError | 320 |
| SSRFBlocked | 3 |
| ConnectionResetError | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.904 | prefer | 18 | 1.0 | 403 |
| dragon | 0.587 | observe | 67 | 0.507 | 44818 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 8779 |
| mheidari-all | 0.349 | observe | 3 | 0.667 | 14536 |
| ermaozi-get_subscribe | 0.267 | observe | 1 | 1.0 | 303 |
| tg-oneclickvpnkeys | 0.261 | observe | 1 | 1.0 | 141 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5030 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2989 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11899 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 462 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 457 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 340 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 318 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 317 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 309 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 287 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 282 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 206 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 193 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.507 | 34 | 33 | 67 |
| mheidari-all | 0.667 | 2 | 1 | 3 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |
| ermaozi | 1.0 | 18 | 0 | 18 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44818 | yes | 7.78 | 0 |
| mheidari-all | 14536 | yes | 5.16 | 0 |
| SoliSpirit-all | 11899 | yes | 3.63 | 0 |
| Surfboard-tg-mixed | 8779 | yes | 4.03 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.01 | 0 |
| Surfboard-tg-vless | 5784 | yes | 3.39 | 0 |
| barry-far-vless | 5677 | yes | 1.35 | 0 |
| 10ium-ScrapeCategorize-Vless | 5030 | yes | 1.25 | 0 |
| mahdibland-V2RayAggregator | 4482 | yes | 3.05 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.35 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_drop_50pct | verified output dropped from 91 to 27 |
| real_ok_drop_50pct | real-test ok dropped from 91 to 27 |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 19 |
| test_one_timeout | 10 |
| cn-block | 4 |
| geo | 1 |
