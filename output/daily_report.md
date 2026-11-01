# AutoNodes 每日报告

生成时间：2026-11-01 21:56:52

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 17/0 |
| 清理建议：优先/观察 | 2/89 |
| 原始节点数 | 127442 |
| 去重后节点数 | 58085 |
| TCP 可达数 | 3000 |
| 真测通过数 | 48 |
| verified 输出数 | 48 |
| global 输出数 | 51 |
| all 输出数 | 58085 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 30.7 |
| fetch | 9.2 |
| generate | 30.7 |
| geo | 1.7 |
| probe | 96.7 |
| real_test | 27.8 |
| tcp | 191.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 3 | 0 | 100.0% |
| http | 21 | 19 | 2 | 90.5% |
| hysteria2 | 21 | 18 | 3 | 85.7% |
| shadowsocks | 13 | 12 | 1 | 92.3% |
| socks | 4 | 0 | 4 | 0.0% |
| trojan | 80 | 78 | 2 | 97.5% |
| vless | 1 | 0 | 1 | 0.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 5 |
| cn-block:ProxyError | 4 |
| 204:ClientOSError | 3 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 13947 |
| ConnectionRefusedError | 2225 |
| gaierror | 522 |
| OSError | 348 |
| SSRFBlocked | 5 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.992 | prefer | 123 | 0.919 | 44543 |
| ermaozi-get_subscribe | 0.861 | prefer | 18 | 0.944 | 499 |
| zhangkai | 0.313 | observe | 2 | 1.0 | 43 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4976 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3716 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10614 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8273 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5823 |
| barry-far-vless | 0.255 | observe | 0 | None | 5986 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 2 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 410 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 405 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 288 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 265 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 257 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 235 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 230 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 154 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 141 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.0 | 0 | 1 | 1 |
| mahdibland-V2RayAggregator | 0.0 | 0 | 1 | 1 |
| dragon | 0.919 | 113 | 10 | 123 |
| ermaozi-get_subscribe | 0.944 | 17 | 1 | 18 |
| zhangkai | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44543 | yes | 8.81 | 0 |
| mheidari-all | 15206 | yes | 5.22 | 0 |
| SoliSpirit-all | 10614 | yes | 3.84 | 0 |
| Surfboard-tg-mixed | 8273 | yes | 4.06 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.59 | 0 |
| barry-far-vless | 5986 | yes | 1.25 | 0 |
| Surfboard-tg-vless | 5823 | yes | 3.72 | 0 |
| 10ium-ScrapeCategorize-Vless | 4976 | yes | 1.7 | 0 |
| mahdibland-V2RayAggregator | 4800 | yes | 0.52 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 1.79 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |
| vless | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 5 |
| cn-block | 4 |
| 204 | 3 |
| geo | 1 |
