# AutoNodes 每日报告

生成时间：2026-11-20 19:52:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127838 |
| 去重后节点数 | 60003 |
| TCP 可达数 | 3000 |
| 真测通过数 | 63 |
| verified 输出数 | 63 |
| global 输出数 | 70 |
| all 输出数 | 60003 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 26.7 |
| fetch | 7.6 |
| generate | 28.2 |
| geo | 1.8 |
| probe | 122.1 |
| real_test | 45.2 |
| tcp | 196.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 41 | 34 | 7 | 82.9% |
| hysteria2 | 16 | 16 | 0 | 100.0% |
| shadowsocks | 203 | 177 | 26 | 87.2% |
| socks | 5 | 2 | 3 | 40.0% |
| vless | 18 | 12 | 6 | 66.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 20 |
| cn-block:ClientOSError | 6 |
| 204:ProxyError | 3 |
| geo:ProxyError | 3 |
| speed:ProxyError | 3 |
| 204:TimeoutError | 2 |
| cn-block:TimeoutError | 2 |
| cn-block:ProxyError | 1 |
| geo:ClientOSError | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15003 |
| ConnectionRefusedError | 2365 |
| gaierror | 578 |
| OSError | 341 |
| ConnectionResetError | 2 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.94 | prefer | 240 | 0.863 | 44987 |
| ermaozi | 0.81 | prefer | 41 | 0.805 | 492 |
| Surfboard-tg-mixed | 0.287 | observe | 2 | 0.5 | 8704 |
| tg-oneclickvpnkeys | 0.26 | observe | 1 | 1.0 | 130 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5045 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2910 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 12061 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5734 |
| barry-far-vless | 0.255 | observe | 0 | None | 5776 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 460 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 455 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 338 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 316 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 315 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 307 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 285 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 280 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 204 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 191 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.5 | 1 | 1 | 2 |
| ermaozi | 0.805 | 33 | 8 | 41 |
| dragon | 0.863 | 207 | 33 | 240 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44987 | yes | 7.06 | 0 |
| mheidari-all | 14341 | yes | 4.05 | 0 |
| SoliSpirit-all | 12061 | yes | 2.74 | 0 |
| Surfboard-tg-mixed | 8704 | yes | 3.19 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.4 | 0 |
| barry-far-vless | 5776 | yes | 0.96 | 0 |
| Surfboard-tg-vless | 5734 | yes | 4.36 | 0 |
| 10ium-ScrapeCategorize-Vless | 5045 | yes | 0.74 | 0 |
| mahdibland-V2RayAggregator | 4501 | yes | 2.79 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.46 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 20 |
| cn-block | 9 |
| 204 | 6 |
| geo | 4 |
| speed | 3 |
