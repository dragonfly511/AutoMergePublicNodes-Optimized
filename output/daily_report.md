# AutoNodes 每日报告

生成时间：2026-10-31 17:06:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 1/89 |
| 原始节点数 | 126231 |
| 去重后节点数 | 58844 |
| TCP 可达数 | 3000 |
| 真测通过数 | 45 |
| verified 输出数 | 45 |
| global 输出数 | 46 |
| all 输出数 | 58844 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 18.2 |
| fetch | 9.0 |
| generate | 30.3 |
| geo | 1.7 |
| probe | 97.4 |
| real_test | 26.1 |
| tcp | 206.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 6 | 4 | 2 | 66.7% |
| hysteria2 | 12 | 9 | 3 | 75.0% |
| shadowsocks | 3 | 3 | 0 | 100.0% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 66 | 50 | 16 | 75.8% |
| vless | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 12 |
| 204:ProxyError | 6 |
| cn-block:ProxyError | 2 |
| 204:ClientOSError | 1 |
| geo:ClientOSError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15038 |
| ConnectionRefusedError | 2304 |
| gaierror | 528 |
| OSError | 330 |
| ConnectionResetError | 4 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.836 | prefer | 88 | 0.761 | 44960 |
| zhangkai | 0.402 | observe | 4 | 1.0 | 43 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4970 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2848 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10683 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7984 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5777 |
| barry-far-vless | 0.255 | observe | 0 | None | 5990 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| ermaozi-get_subscribe | 0.144 | observe | 1 | 0.0 | 0 | 412 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 2 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 515 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 406 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 401 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 284 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 262 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 253 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 231 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 226 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 150 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| dragon | 0.761 | 67 | 21 | 88 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 4 | 0 | 4 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44960 | yes | 7.88 | 0 |
| mheidari-all | 14848 | yes | 5.71 | 0 |
| SoliSpirit-all | 10683 | yes | 4.07 | 0 |
| Surfboard-tg-mixed | 7984 | yes | 3.63 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.51 | 0 |
| barry-far-vless | 5990 | yes | 1.85 | 0 |
| Surfboard-tg-vless | 5777 | yes | 4.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 4970 | yes | 2.16 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 2.13 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.93 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_drop_50pct | verified output dropped from 100 to 45 |
| real_ok_drop_50pct | real-test ok dropped from 100 to 45 |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 12 |
| 204 | 8 |
| cn-block | 2 |
| geo | 1 |
