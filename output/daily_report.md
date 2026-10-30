# AutoNodes 每日报告

生成时间：2026-10-30 05:00:58

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 144340 |
| 去重后节点数 | 59354 |
| TCP 可达数 | 3000 |
| 真测通过数 | 70 |
| verified 输出数 | 70 |
| global 输出数 | 70 |
| all 输出数 | 59354 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 23.8 |
| fetch | 5.4 |
| generate | 18.8 |
| geo | 1.5 |
| probe | 89.8 |
| real_test | 36.7 |
| tcp | 204.6 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 20 | 19 | 1 | 95.0% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 163 | 150 | 13 | 92.0% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 26 | 25 | 1 | 96.2% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| 204:ClientOSError | 2 |
| 204:ProxyError | 1 |
| 204:TimeoutError | 1 |
| geo:ClientOSError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15790 |
| ConnectionRefusedError | 2407 |
| gaierror | 416 |
| OSError | 322 |
| SSRFBlocked | 5 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.99 | prefer | 210 | 0.914 | 44588 |
| ermaozi | 0.93 | prefer | 20 | 0.95 | 515 |
| Au1rxx-base64 | 0.324 | observe | 1 | 1.0 | 1726 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5005 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2709 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10496 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7756 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5729 |
| barry-far-vless | 0.255 | observe | 0 | None | 5941 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-ShadowsocksM | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 510 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 401 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 396 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 279 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 257 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 256 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 248 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 226 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 221 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 145 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.914 | 192 | 18 | 210 |
| ermaozi | 0.95 | 19 | 1 | 20 |
| Au1rxx-base64 | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44588 | yes | 4.83 | 0 |
| mheidari-all | 34034 | yes | 3.26 | 0 |
| SoliSpirit-all | 10496 | yes | 0.76 | 0 |
| Surfboard-tg-mixed | 7756 | yes | 2.18 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.02 | 0 |
| barry-far-vless | 5941 | yes | 0.89 | 0 |
| Surfboard-tg-vless | 5729 | yes | 1.89 | 0 |
| 10ium-ScrapeCategorize-Vless | 5005 | yes | 0.4 | 0 |
| mahdibland-V2RayAggregator | 4444 | yes | 1.67 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.99 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 13 |
| 204 | 4 |
| geo | 1 |
| cn-block | 1 |
