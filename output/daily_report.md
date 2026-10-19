# AutoNodes 每日报告

生成时间：2026-10-19 02:39:24

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 3/90 |
| 原始节点数 | 97404 |
| 去重后节点数 | 27723 |
| TCP 可达数 | 3000 |
| 真测通过数 | 70 |
| verified 输出数 | 70 |
| global 输出数 | 73 |
| all 输出数 | 27723 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 32.0 |
| fetch | 4.2 |
| generate | 8.4 |
| geo | 1.4 |
| probe | 87.0 |
| real_test | 84.3 |
| tcp | 88.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 98 | 90 | 8 | 91.8% |
| hysteria2 | 12 | 10 | 2 | 83.3% |
| shadowsocks | 153 | 142 | 11 | 92.8% |
| socks | 4 | 3 | 1 | 75.0% |
| trojan | 55 | 50 | 5 | 90.9% |
| vless | 303 | 193 | 110 | 63.7% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 64 |
| speed:ClientOSError | 30 |
| geo:ClientOSError | 18 |
| 204:ProxyError | 5 |
| geo:ProxyError | 4 |
| cn-block:TimeoutError | 4 |
| speed:ProxyError | 3 |
| cn-block:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| 204:TimeoutError | 2 |
| geo:TimeoutError | 1 |
| 204:ClientOSError | 1 |
| speed:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7431 |
| ConnectionRefusedError | 1018 |
| OSError | 236 |
| gaierror | 184 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.93 | prefer | 100 | 0.91 | 696 |
| Au1rxx-base64 | 0.905 | prefer | 300 | 0.84 | 1675 |
| Surfboard-tg-mixed | 0.782 | prefer | 112 | 0.705 | 7003 |
| mheidari-all | 0.666 | observe | 114 | 0.588 | 23518 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4983 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 4750 |
| Epodonios-all | 0.255 | observe | 0 | None | 7467 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9938 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5523 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 4 |
| tg-freeiranianv2rey | 0.175 | observe | 0 | None | 0 | 12 |
| tg-freevpnconfigso | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 470 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 361 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 356 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 239 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 217 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 216 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 208 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 186 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 181 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 105 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.588 | 67 | 47 | 114 |
| Surfboard-tg-mixed | 0.705 | 79 | 33 | 112 |
| Au1rxx-base64 | 0.84 | 252 | 48 | 300 |
| ermaozi | 0.91 | 91 | 9 | 100 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23518 | yes | 2.74 | 0 |
| SoliSpirit-all | 9938 | yes | 3.12 | 0 |
| Epodonios-all | 7467 | yes | 3.16 | 0 |
| Surfboard-tg-mixed | 7003 | yes | 2.96 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.3 | 0 |
| barry-far-vless | 5700 | yes | 0.97 | 0 |
| Surfboard-tg-vless | 5523 | yes | 3.66 | 0 |
| 10ium-ScrapeCategorize-Vless | 4983 | yes | 1.79 | 0 |
| DeltaKronecker-all | 4750 | yes | 3.62 | 0 |
| mahdibland-V2RayAggregator | 4246 | yes | 1.1 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 64 |
| speed | 34 |
| geo | 23 |
| cn-block | 8 |
| 204 | 8 |
