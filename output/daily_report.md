# AutoNodes 每日报告

生成时间：2026-11-14 13:17:56

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 127937 |
| 去重后节点数 | 58935 |
| TCP 可达数 | 3000 |
| 真测通过数 | 56 |
| verified 输出数 | 56 |
| global 输出数 | 56 |
| all 输出数 | 58935 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 32.1 |
| fetch | 8.8 |
| generate | 30.9 |
| geo | 1.7 |
| probe | 106.1 |
| real_test | 37.7 |
| tcp | 191.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 24 | 22 | 2 | 91.7% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 200 | 185 | 15 | 92.5% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 52 | 37 | 15 | 71.2% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| 204:ProxyError | 11 |
| 204:ClientOSError | 2 |
| speed:TimeoutError | 2 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| 204:TimeoutError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14132 |
| ConnectionRefusedError | 2252 |
| gaierror | 880 |
| OSError | 336 |
| SSRFBlocked | 4 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.962 | prefer | 270 | 0.885 | 44709 |
| ermaozi | 0.906 | prefer | 24 | 0.917 | 527 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14251 |
| Surfboard-tg-mixed | 0.287 | observe | 2 | 0.5 | 8883 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4966 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2652 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11479 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6276 |
| barry-far-vless | 0.255 | observe | 0 | None | 6459 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 445 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 440 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 323 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 301 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 300 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 292 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 270 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 265 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 189 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 176 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.5 | 1 | 1 | 2 |
| dragon | 0.885 | 239 | 31 | 270 |
| ermaozi | 0.917 | 22 | 2 | 24 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44709 | yes | 8.1 | 0 |
| mheidari-all | 14251 | yes | 5.1 | 0 |
| SoliSpirit-all | 11479 | yes | 3.32 | 0 |
| Surfboard-tg-mixed | 8883 | yes | 3.91 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.79 | 0 |
| barry-far-vless | 6459 | yes | 1.14 | 0 |
| Surfboard-tg-vless | 6276 | yes | 3.56 | 0 |
| 10ium-ScrapeCategorize-Vless | 4966 | yes | 1.39 | 0 |
| mahdibland-V2RayAggregator | 4551 | yes | 3.14 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.49 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 14 |
| test_one_timeout | 13 |
| cn-block | 3 |
| speed | 2 |
| geo | 2 |
