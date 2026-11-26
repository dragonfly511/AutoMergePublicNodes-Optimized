# AutoNodes 每日报告

生成时间：2026-11-26 07:32:16

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 122533 |
| 去重后节点数 | 57951 |
| TCP 可达数 | 3000 |
| 真测通过数 | 35 |
| verified 输出数 | 35 |
| global 输出数 | 35 |
| all 输出数 | 57951 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.4 |
| fetch | 8.3 |
| generate | 29.6 |
| geo | 1.7 |
| probe | 100.0 |
| real_test | 22.7 |
| tcp | 197.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 19 | 19 | 0 | 100.0% |
| hysteria2 | 8 | 7 | 1 | 87.5% |
| shadowsocks | 49 | 47 | 2 | 95.9% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 1 | 0 | 1 | 0.0% |
| vless | 35 | 26 | 9 | 74.3% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 9 |
| 204:ProxyError | 3 |
| 204:ClientOSError | 1 |
| 204:TimeoutError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 16045 |
| ConnectionRefusedError | 2545 |
| gaierror | 663 |
| OSError | 350 |
| SSRFBlocked | 2 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.938 | prefer | 19 | 1.0 | 406 |
| dragon | 0.922 | prefer | 99 | 0.848 | 43754 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 8442 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4958 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11584 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5447 |
| barry-far-vless | 0.255 | observe | 0 | None | 5694 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4463 |
| mheidari-all | 0.255 | observe | 0 | None | 14817 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 472 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 467 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 350 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 328 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 327 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 319 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 297 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 292 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 216 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 203 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.848 | 84 | 15 | 99 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |
| ermaozi | 1.0 | 19 | 0 | 19 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 43754 | yes | 7.69 | 0 |
| mheidari-all | 14817 | yes | 5.88 | 0 |
| SoliSpirit-all | 11584 | yes | 2.49 | 0 |
| Surfboard-tg-mixed | 8442 | yes | 3.49 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.59 | 0 |
| barry-far-vless | 5694 | yes | 1.79 | 0 |
| Surfboard-tg-vless | 5447 | yes | 3.69 | 0 |
| 10ium-ScrapeCategorize-Vless | 4958 | yes | 2.02 | 0 |
| mahdibland-V2RayAggregator | 4463 | yes | 3.0 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 2.11 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_drop_50pct | verified output dropped from 92 to 35 |
| real_ok_drop_50pct | real-test ok dropped from 92 to 35 |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| trojan | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 9 |
| 204 | 5 |
| geo | 1 |
