# AutoNodes 每日报告

生成时间：2026-11-19 20:17:50

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/89 |
| 原始节点数 | 128278 |
| 去重后节点数 | 59661 |
| TCP 可达数 | 3000 |
| 真测通过数 | 27 |
| verified 输出数 | 27 |
| global 输出数 | 28 |
| all 输出数 | 59661 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 26.6 |
| fetch | 7.8 |
| generate | 27.6 |
| geo | 1.7 |
| probe | 94.2 |
| real_test | 24.2 |
| tcp | 190.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 9 | 6 | 3 | 66.7% |
| http | 23 | 22 | 1 | 95.7% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 4 | 4 | 0 | 100.0% |
| socks | 6 | 3 | 3 | 50.0% |
| trojan | 60 | 17 | 43 | 28.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 25 |
| test_one_timeout:15.0s | 8 |
| cn-block:ProxyError | 7 |
| geo:ProxyError | 3 |
| 204:TimeoutError | 3 |
| speed:ProxyError | 3 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:42422: bind: address already in use | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14564 |
| ConnectionRefusedError | 2410 |
| gaierror | 657 |
| OSError | 329 |
| ConnectionResetError | 4 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.94 | prefer | 23 | 0.957 | 491 |
| dragon | 0.518 | observe | 87 | 0.437 | 45096 |
| tg-LonUp_M | 0.365 | observe | 3 | 1.0 | 179 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4935 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2728 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 12076 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8602 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5937 |
| barry-far-vless | 0.255 | observe | 0 | None | 5868 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 458 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 453 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 336 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 314 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 313 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 305 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 283 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 278 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 202 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 189 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.0 | 0 | 1 | 1 |
| dragon | 0.437 | 38 | 49 | 87 |
| ermaozi | 0.957 | 22 | 1 | 23 |
| tg-LonUp_M | 1.0 | 3 | 0 | 3 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45096 | yes | 7.19 | 0 |
| mheidari-all | 14706 | yes | 5.55 | 0 |
| SoliSpirit-all | 11871 | yes | 2.78 | 0 |
| Surfboard-tg-mixed | 8602 | yes | 3.88 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.32 | 0 |
| Surfboard-tg-vless | 5937 | yes | 3.41 | 0 |
| barry-far-vless | 5868 | yes | 2.19 | 0 |
| 10ium-ScrapeCategorize-Vless | 4935 | yes | 1.7 | 0 |
| mahdibland-V2RayAggregator | 4507 | yes | 2.8 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.77 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_drop_50pct | verified output dropped from 104 to 27 |
| real_ok_drop_50pct | real-test ok dropped from 104 to 27 |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 29 |
| test_one_timeout | 8 |
| cn-block | 7 |
| geo | 3 |
| speed | 3 |
| sing-box exited 1 | 1 |
