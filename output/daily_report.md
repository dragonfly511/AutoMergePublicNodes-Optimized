# AutoNodes 每日报告

生成时间：2026-11-03 23:07:27

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 17/0 |
| 清理建议：优先/观察 | 2/89 |
| 原始节点数 | 128813 |
| 去重后节点数 | 58756 |
| TCP 可达数 | 3000 |
| 真测通过数 | 73 |
| verified 输出数 | 73 |
| global 输出数 | 75 |
| all 输出数 | 58756 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.9 |
| fetch | 7.8 |
| generate | 25.8 |
| geo | 1.7 |
| probe | 101.0 |
| real_test | 40.2 |
| tcp | 207.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 20 | 20 | 0 | 100.0% |
| hysteria2 | 12 | 10 | 2 | 83.3% |
| shadowsocks | 249 | 237 | 12 | 95.2% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 14 | 14 | 0 | 100.0% |
| vless | 8 | 1 | 7 | 12.5% |
| vmess | 4 | 3 | 1 | 75.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| geo:ClientOSError | 7 |
| test_one_timeout:15.0s | 6 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 2 |
| cn-block:TimeoutError | 1 |
| 204:ClientOSError | 1 |
| speed:ClientOSError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14566 |
| ConnectionRefusedError | 2382 |
| gaierror | 584 |
| OSError | 314 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.999 | prefer | 293 | 0.922 | 45574 |
| ermaozi | 0.945 | prefer | 19 | 1.0 | 592 |
| Surfboard-tg-mixed | 0.335 | observe | 1 | 1.0 | 8582 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 115 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5017 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2526 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10841 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6047 |
| barry-far-vless | 0.255 | observe | 0 | None | 6260 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 415 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 410 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 293 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 271 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 270 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 262 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 240 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 235 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 159 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 146 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.922 | 270 | 23 | 293 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 19 | 0 | 19 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45574 | yes | 6.83 | 0 |
| mheidari-all | 15211 | yes | 5.23 | 0 |
| SoliSpirit-all | 10841 | yes | 2.22 | 0 |
| Surfboard-tg-mixed | 8582 | yes | 2.85 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.37 | 0 |
| barry-far-vless | 6260 | yes | 1.79 | 0 |
| Surfboard-tg-vless | 6047 | yes | 3.27 | 0 |
| 10ium-ScrapeCategorize-Vless | 5017 | yes | 1.56 | 0 |
| mahdibland-V2RayAggregator | 4753 | yes | 2.61 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 1.89 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| geo | 7 |
| 204 | 6 |
| test_one_timeout | 6 |
| cn-block | 3 |
| speed | 1 |
