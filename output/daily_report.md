# AutoNodes 每日报告

生成时间：2026-11-18 15:26:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 126477 |
| 去重后节点数 | 58450 |
| TCP 可达数 | 3000 |
| 真测通过数 | 123 |
| verified 输出数 | 123 |
| global 输出数 | 125 |
| all 输出数 | 58450 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 30.3 |
| fetch | 6.0 |
| generate | 20.7 |
| geo | 1.7 |
| probe | 100.8 |
| real_test | 44.5 |
| tcp | 198.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 3 | 2 | 60.0% |
| http | 21 | 19 | 2 | 90.5% |
| hysteria2 | 12 | 10 | 2 | 83.3% |
| shadowsocks | 227 | 208 | 19 | 91.6% |
| socks | 7 | 5 | 2 | 71.4% |
| vless | 9 | 7 | 2 | 77.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 19 |
| 204:ProxyError | 2 |
| 204:TimeoutError | 2 |
| cn-block:ClientOSError | 2 |
| 204:ClientOSError | 1 |
| speed:TimeoutError | 1 |
| cn-block:ProxyError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14931 |
| ConnectionRefusedError | 2227 |
| gaierror | 475 |
| OSError | 353 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.98 | prefer | 258 | 0.903 | 44296 |
| ermaozi | 0.89 | prefer | 21 | 0.905 | 508 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 116 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4919 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2925 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11560 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5766 |
| barry-far-vless | 0.255 | observe | 0 | None | 5946 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4458 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 455 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 450 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 333 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 311 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 310 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 302 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 280 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 275 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 199 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 186 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.0 | 0 | 1 | 1 |
| dragon | 0.903 | 233 | 25 | 258 |
| ermaozi | 0.905 | 19 | 2 | 21 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44296 | yes | 5.36 | 0 |
| mheidari-all | 14408 | yes | 3.32 | 0 |
| SoliSpirit-all | 11560 | yes | 2.14 | 0 |
| Surfboard-tg-mixed | 8446 | yes | 2.63 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.88 | 0 |
| barry-far-vless | 5946 | yes | 0.37 | 0 |
| Surfboard-tg-vless | 5766 | yes | 2.8 | 0 |
| 10ium-ScrapeCategorize-Vless | 4919 | yes | 0.97 | 0 |
| mahdibland-V2RayAggregator | 4458 | yes | 2.07 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.44 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 19 |
| 204 | 5 |
| cn-block | 4 |
| speed | 1 |
