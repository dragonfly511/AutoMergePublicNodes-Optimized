# AutoNodes 每日报告

生成时间：2026-10-31 11:59:31

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 126213 |
| 去重后节点数 | 58834 |
| TCP 可达数 | 3000 |
| 真测通过数 | 100 |
| verified 输出数 | 100 |
| global 输出数 | 102 |
| all 输出数 | 58834 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.9 |
| fetch | 6.4 |
| generate | 23.8 |
| geo | 1.6 |
| probe | 79.8 |
| real_test | 30.8 |
| tcp | 198.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 55 | 53 | 2 | 96.4% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 5 | 3 | 2 | 60.0% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 75 | 62 | 13 | 82.7% |
| vless | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 12 |
| 204:ProxyError | 2 |
| 204:ClientOSError | 2 |
| 204:TimeoutError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:47328: bind: address already in use | 1 |
| geo:ClientOSError | 1 |
| cn-block:ClientOSError | 1 |
| cn-block:TimeoutError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14463 |
| ConnectionRefusedError | 2359 |
| gaierror | 623 |
| OSError | 334 |
| SSRFBlocked | 3 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.989 | prefer | 54 | 0.981 | 622 |
| dragon | 0.87 | prefer | 98 | 0.796 | 44960 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4970 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2848 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10588 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7861 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5698 |
| barry-far-vless | 0.255 | observe | 0 | None | 5912 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4635 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-oneclickvpnkeys | 0.131 | observe | 1 | 0.0 | 0 | 98 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 2 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 514 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 405 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 400 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 283 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 260 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 252 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 230 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 225 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 149 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.0 | 0 | 1 | 1 |
| tg-oneclickvpnkeys | 0.0 | 0 | 1 | 1 |
| dragon | 0.796 | 78 | 20 | 98 |
| ermaozi | 0.981 | 53 | 1 | 54 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44960 | yes | 5.75 | 0 |
| mheidari-all | 14723 | yes | 3.59 | 0 |
| SoliSpirit-all | 10588 | yes | 2.23 | 0 |
| Surfboard-tg-mixed | 7861 | yes | 2.98 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.89 | 0 |
| barry-far-vless | 5912 | yes | 0.55 | 0 |
| Surfboard-tg-vless | 5698 | yes | 2.62 | 0 |
| 10ium-ScrapeCategorize-Vless | 4970 | yes | 0.88 | 0 |
| mahdibland-V2RayAggregator | 4635 | yes | 2.34 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.95 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |
| vless | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 12 |
| 204 | 6 |
| geo | 2 |
| cn-block | 2 |
| sing-box exited 1 | 1 |
