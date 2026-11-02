# AutoNodes 每日报告

生成时间：2026-11-02 15:10:29

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 17/0 |
| 清理建议：优先/观察 | 1/90 |
| 原始节点数 | 126088 |
| 去重后节点数 | 58171 |
| TCP 可达数 | 3000 |
| 真测通过数 | 30 |
| verified 输出数 | 30 |
| global 输出数 | 30 |
| all 输出数 | 58171 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 23.2 |
| fetch | 8.4 |
| generate | 29.4 |
| geo | 1.7 |
| probe | 98.2 |
| real_test | 24.4 |
| tcp | 195.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 10 | 3 | 7 | 30.0% |
| http | 19 | 19 | 0 | 100.0% |
| hysteria2 | 16 | 15 | 1 | 93.8% |
| shadowsocks | 5 | 5 | 0 | 100.0% |
| socks | 5 | 0 | 5 | 0.0% |
| trojan | 57 | 48 | 9 | 84.2% |
| vless | 2 | 0 | 2 | 0.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 11 |
| 204:ProxyError | 5 |
| speed:ClientOSError | 5 |
| geo:ClientOSError | 2 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14250 |
| ConnectionRefusedError | 2285 |
| gaierror | 523 |
| OSError | 351 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.871 | prefer | 89 | 0.798 | 44543 |
| zhangkai | 0.689 | observe | 12 | 1.0 | 43 |
| ermaozi-get_subscribe | 0.428 | observe | 13 | 0.538 | 403 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14979 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4941 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2726 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10679 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8264 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 412 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 407 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 290 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 259 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 237 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 232 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 156 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 143 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.538 | 7 | 6 | 13 |
| dragon | 0.798 | 71 | 18 | 89 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 12 | 0 | 12 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44543 | yes | 7.76 | 0 |
| mheidari-all | 14979 | yes | 4.78 | 0 |
| SoliSpirit-all | 10679 | yes | 3.14 | 0 |
| Surfboard-tg-mixed | 8264 | yes | 3.52 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.71 | 0 |
| barry-far-vless | 6057 | yes | 1.37 | 0 |
| Surfboard-tg-vless | 5844 | yes | 3.75 | 0 |
| 10ium-ScrapeCategorize-Vless | 4941 | yes | 1.15 | 0 |
| mahdibland-V2RayAggregator | 4726 | yes | 1.48 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.98 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_drop_50pct | verified output dropped from 64 to 30 |
| real_ok_drop_50pct | real-test ok dropped from 64 to 30 |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |
| vless | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 11 |
| 204 | 6 |
| speed | 5 |
| geo | 2 |
