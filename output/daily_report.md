# AutoNodes 每日报告

生成时间：2026-11-12 00:22:03

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 127283 |
| 去重后节点数 | 58593 |
| TCP 可达数 | 3000 |
| 真测通过数 | 78 |
| verified 输出数 | 78 |
| global 输出数 | 80 |
| all 输出数 | 58593 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 32.1 |
| fetch | 8.8 |
| generate | 31.4 |
| geo | 1.7 |
| probe | 104.6 |
| real_test | 55.3 |
| tcp | 196.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 77 | 74 | 3 | 96.1% |
| hysteria2 | 20 | 18 | 2 | 90.0% |
| shadowsocks | 214 | 200 | 14 | 93.5% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 107 | 94 | 13 | 87.9% |
| vless | 2 | 0 | 2 | 0.0% |
| vmess | 4 | 4 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 17 |
| speed:TimeoutError | 4 |
| cn-block:ClientOSError | 4 |
| geo:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| speed:ClientOSError | 2 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14862 |
| ConnectionRefusedError | 2245 |
| OSError | 335 |
| gaierror | 271 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.986 | prefer | 348 | 0.908 | 44265 |
| ermaozi | 0.974 | prefer | 77 | 0.961 | 608 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 14184 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4981 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2629 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11251 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8641 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6380 |
| barry-far-vless | 0.255 | observe | 0 | None | 6559 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-freeiranianv2rey | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 438 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 433 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 316 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 294 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 293 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 285 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 263 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 258 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 182 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 169 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.908 | 316 | 32 | 348 |
| ermaozi | 0.961 | 74 | 3 | 77 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44265 | yes | 8.68 | 0 |
| mheidari-all | 14184 | yes | 5.42 | 0 |
| SoliSpirit-all | 11251 | yes | 4.42 | 0 |
| Surfboard-tg-mixed | 8641 | yes | 4.12 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.16 | 0 |
| barry-far-vless | 6559 | yes | 3.96 | 0 |
| Surfboard-tg-vless | 6380 | yes | 3.82 | 0 |
| 10ium-ScrapeCategorize-Vless | 4981 | yes | 1.91 | 0 |
| mahdibland-V2RayAggregator | 4595 | yes | 1.83 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 3.24 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 17 |
| speed | 6 |
| cn-block | 5 |
| geo | 4 |
| 204 | 3 |
