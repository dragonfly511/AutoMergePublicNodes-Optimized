# AutoNodes 每日报告

生成时间：2026-11-12 23:26:48

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 127109 |
| 去重后节点数 | 58440 |
| TCP 可达数 | 3000 |
| 真测通过数 | 61 |
| verified 输出数 | 61 |
| global 输出数 | 63 |
| all 输出数 | 58440 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 32.1 |
| fetch | 6.2 |
| generate | 23.0 |
| geo | 1.8 |
| probe | 91.0 |
| real_test | 49.3 |
| tcp | 197.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 55 | 52 | 3 | 94.5% |
| hysteria2 | 13 | 13 | 0 | 100.0% |
| shadowsocks | 225 | 209 | 16 | 92.9% |
| socks | 1 | 1 | 0 | 100.0% |
| trojan | 74 | 70 | 4 | 94.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 9 |
| 204:ClientOSError | 8 |
| cn-block:ProxyError | 1 |
| cn-block:ClientOSError | 1 |
| cn-block:TimeoutError | 1 |
| geo:ClientOSError | 1 |
| geo:TimeoutError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14520 |
| ConnectionRefusedError | 2338 |
| gaierror | 640 |
| OSError | 351 |
| SSRFBlocked | 5 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 1.0 | prefer | 313 | 0.936 | 44243 |
| ermaozi | 0.953 | prefer | 55 | 0.945 | 579 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 13866 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4998 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2737 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11356 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8710 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6364 |
| barry-far-vless | 0.255 | observe | 0 | None | 6512 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 6 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 440 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 435 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 318 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 296 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 295 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 287 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 265 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 260 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 184 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 171 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.936 | 293 | 20 | 313 |
| ermaozi | 0.945 | 52 | 3 | 55 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44243 | yes | 5.57 | 0 |
| mheidari-all | 13866 | yes | 3.72 | 0 |
| SoliSpirit-all | 11356 | yes | 2.23 | 0 |
| Surfboard-tg-mixed | 8710 | yes | 3.91 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.94 | 0 |
| barry-far-vless | 6512 | yes | 1.27 | 0 |
| Surfboard-tg-vless | 6364 | yes | 2.51 | 0 |
| 10ium-ScrapeCategorize-Vless | 4998 | yes | 1.12 | 0 |
| mahdibland-V2RayAggregator | 4582 | yes | 2.17 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.87 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 9 |
| 204 | 8 |
| cn-block | 3 |
| geo | 2 |
| speed | 1 |
