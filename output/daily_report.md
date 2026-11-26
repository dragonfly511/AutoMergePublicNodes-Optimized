# AutoNodes 每日报告

生成时间：2026-11-26 21:13:41

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 122584 |
| 去重后节点数 | 58269 |
| TCP 可达数 | 3000 |
| 真测通过数 | 89 |
| verified 输出数 | 89 |
| global 输出数 | 91 |
| all 输出数 | 58269 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.1 |
| fetch | 8.3 |
| generate | 30.1 |
| geo | 1.7 |
| probe | 106.5 |
| real_test | 38.0 |
| tcp | 199.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 22 | 22 | 0 | 100.0% |
| hysteria2 | 13 | 7 | 6 | 53.8% |
| shadowsocks | 206 | 177 | 29 | 85.9% |
| socks | 4 | 4 | 0 | 100.0% |
| trojan | 2 | 2 | 0 | 100.0% |
| vless | 22 | 16 | 6 | 72.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 18 |
| 204:ClientOSError | 6 |
| 204:ProxyError | 5 |
| 204:TimeoutError | 4 |
| cn-block:ClientOSError | 3 |
| speed:TimeoutError | 3 |
| speed:ClientOSError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 16229 |
| ConnectionRefusedError | 2522 |
| gaierror | 673 |
| OSError | 348 |
| ConnectionResetError | 2 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.974 | prefer | 22 | 1.0 | 393 |
| dragon | 0.912 | prefer | 248 | 0.835 | 43754 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 170 |
| tg-proxy_mtm | 0.258 | observe | 1 | 1.0 | 67 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4936 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11794 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8568 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5426 |
| barry-far-vless | 0.255 | observe | 0 | None | 5607 |

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
| disable | tg-Letiranbreath | 0.0 | 0 | None | 473 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 468 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 351 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 329 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 328 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 320 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 298 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 293 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 217 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 204 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.835 | 207 | 41 | 248 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| tg-proxy_mtm | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 22 | 0 | 22 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 43754 | yes | 7.62 | 0 |
| mheidari-all | 14669 | yes | 4.7 | 0 |
| SoliSpirit-all | 11794 | yes | 2.36 | 0 |
| Surfboard-tg-mixed | 8568 | yes | 4.17 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.84 | 0 |
| barry-far-vless | 5607 | yes | 0.69 | 0 |
| Surfboard-tg-vless | 5426 | yes | 3.8 | 0 |
| 10ium-ScrapeCategorize-Vless | 4936 | yes | 0.92 | 0 |
| mahdibland-V2RayAggregator | 4485 | yes | 2.76 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.24 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 18 |
| 204 | 15 |
| cn-block | 4 |
| speed | 4 |
