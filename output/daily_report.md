# AutoNodes 每日报告

生成时间：2026-11-01 05:06:15

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 124658 |
| 去重后节点数 | 57761 |
| TCP 可达数 | 3000 |
| 真测通过数 | 66 |
| verified 输出数 | 66 |
| global 输出数 | 66 |
| all 输出数 | 57761 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.8 |
| fetch | 5.7 |
| generate | 18.7 |
| geo | 1.5 |
| probe | 92.4 |
| real_test | 53.5 |
| tcp | 199.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 0 | 2 | 0.0% |
| http | 15 | 14 | 1 | 93.3% |
| hysteria2 | 20 | 17 | 3 | 85.0% |
| shadowsocks | 167 | 157 | 10 | 94.0% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 47 | 45 | 2 | 95.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 11 |
| 204:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| 204:ProxyError | 1 |
| geo:ClientOSError | 1 |
| cn-block:ClientOSError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14908 |
| ConnectionRefusedError | 2272 |
| gaierror | 494 |
| OSError | 350 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 239 | 0.925 | 44351 |
| ermaozi-get_subscribe | 0.727 | prefer | 14 | 0.929 | 558 |
| zhangkai | 0.313 | observe | 2 | 1.0 | 43 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4970 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2848 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10496 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5637 |
| barry-far-vless | 0.255 | observe | 0 | None | 5805 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4635 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 2 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 517 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 408 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 403 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 286 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 264 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 263 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 255 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 233 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 228 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 152 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.0 | 0 | 1 | 1 |
| dragon | 0.925 | 221 | 18 | 239 |
| ermaozi-get_subscribe | 0.929 | 13 | 1 | 14 |
| zhangkai | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44351 | yes | 4.79 | 0 |
| mheidari-all | 14646 | yes | 3.38 | 0 |
| SoliSpirit-all | 10496 | yes | 3.03 | 0 |
| Surfboard-tg-mixed | 7809 | yes | 2.33 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.01 | 0 |
| barry-far-vless | 5805 | yes | 1.12 | 0 |
| Surfboard-tg-vless | 5637 | yes | 2.43 | 0 |
| 10ium-ScrapeCategorize-Vless | 4970 | yes | 1.5 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 1.91 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.26 | 0 |

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
| test_one_timeout | 11 |
| 204 | 6 |
| cn-block | 2 |
| geo | 1 |
