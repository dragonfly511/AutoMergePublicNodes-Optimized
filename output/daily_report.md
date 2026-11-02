# AutoNodes 每日报告

生成时间：2026-11-02 05:07:26

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 17/0 |
| 清理建议：优先/观察 | 2/89 |
| 原始节点数 | 127609 |
| 去重后节点数 | 58153 |
| TCP 可达数 | 3000 |
| 真测通过数 | 64 |
| verified 输出数 | 64 |
| global 输出数 | 65 |
| all 输出数 | 58153 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.2 |
| fetch | 9.1 |
| generate | 30.6 |
| geo | 1.7 |
| probe | 89.8 |
| real_test | 26.7 |
| tcp | 199.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 25 | 24 | 1 | 96.0% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 11 | 11 | 0 | 100.0% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 78 | 73 | 5 | 93.6% |
| vless | 2 | 0 | 2 | 0.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 6 |
| geo:ClientOSError | 3 |
| 204:ClientOSError | 2 |
| speed:ProxyError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14676 |
| ConnectionRefusedError | 2206 |
| gaierror | 441 |
| OSError | 348 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.969 | prefer | 115 | 0.896 | 44543 |
| zhangkai | 0.79 | prefer | 15 | 1.0 | 43 |
| ermaozi-get_subscribe | 0.621 | observe | 11 | 0.909 | 547 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4976 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3716 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10662 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8273 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5823 |
| barry-far-vless | 0.255 | observe | 0 | None | 6036 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 2 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 411 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 406 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 289 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 266 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 258 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 236 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 231 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 155 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 142 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.896 | 103 | 12 | 115 |
| ermaozi-get_subscribe | 0.909 | 10 | 1 | 11 |
| zhangkai | 1.0 | 15 | 0 | 15 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44543 | yes | 7.96 | 0 |
| mheidari-all | 15216 | yes | 4.99 | 0 |
| SoliSpirit-all | 10662 | yes | 2.21 | 0 |
| Surfboard-tg-mixed | 8273 | yes | 3.96 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.08 | 0 |
| barry-far-vless | 6036 | yes | 1.03 | 0 |
| Surfboard-tg-vless | 5823 | yes | 3.67 | 0 |
| 10ium-ScrapeCategorize-Vless | 4976 | yes | 1.28 | 0 |
| mahdibland-V2RayAggregator | 4800 | yes | 3.28 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 2.3 | 0 |

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
| test_one_timeout | 6 |
| geo | 3 |
| 204 | 2 |
| speed | 1 |
| cn-block | 1 |
