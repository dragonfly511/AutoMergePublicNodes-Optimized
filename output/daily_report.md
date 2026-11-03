# AutoNodes 每日报告

生成时间：2026-11-03 13:57:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 17/0 |
| 清理建议：优先/观察 | 2/89 |
| 原始节点数 | 128487 |
| 去重后节点数 | 58547 |
| TCP 可达数 | 3000 |
| 真测通过数 | 64 |
| verified 输出数 | 64 |
| global 输出数 | 65 |
| all 输出数 | 58547 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 23.9 |
| fetch | 6.7 |
| generate | 23.4 |
| geo | 1.6 |
| probe | 106.5 |
| real_test | 46.6 |
| tcp | 195.7 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 19 | 19 | 0 | 100.0% |
| hysteria2 | 12 | 9 | 3 | 75.0% |
| shadowsocks | 236 | 204 | 32 | 86.4% |
| socks | 10 | 2 | 8 | 20.0% |
| trojan | 39 | 34 | 5 | 87.2% |
| vmess | 3 | 3 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 33 |
| 204:ProxyError | 7 |
| 204:TimeoutError | 3 |
| 204:ClientOSError | 1 |
| geo:TimeoutError | 1 |
| cn-block:ProxyError | 1 |
| speed:ClientOSError | 1 |
| geo:ProxyError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14551 |
| ConnectionRefusedError | 2323 |
| gaierror | 562 |
| OSError | 346 |
| SSRFBlocked | 4 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.918 | prefer | 301 | 0.841 | 45127 |
| ermaozi | 0.912 | prefer | 18 | 1.0 | 592 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8600 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 119 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5017 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2526 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10844 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6192 |
| barry-far-vless | 0.255 | observe | 0 | None | 6407 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 414 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 409 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 292 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 270 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 269 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 239 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 234 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 158 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 145 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.0 | 0 | 1 | 1 |
| dragon | 0.841 | 253 | 48 | 301 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 18 | 0 | 18 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45127 | yes | 6.09 | 0 |
| mheidari-all | 14937 | yes | 3.62 | 0 |
| SoliSpirit-all | 10844 | yes | 2.33 | 0 |
| Surfboard-tg-mixed | 8600 | yes | 3.23 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.15 | 0 |
| barry-far-vless | 6407 | yes | 1.34 | 0 |
| Surfboard-tg-vless | 6192 | yes | 2.57 | 0 |
| 10ium-ScrapeCategorize-Vless | 5017 | yes | 1.49 | 0 |
| mahdibland-V2RayAggregator | 4753 | yes | 1.24 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 2.49 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 33 |
| 204 | 11 |
| geo | 2 |
| speed | 2 |
| cn-block | 1 |
