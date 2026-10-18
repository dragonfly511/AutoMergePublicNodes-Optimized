# AutoNodes 每日报告

生成时间：2026-10-18 12:18:43

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 98277 |
| 去重后节点数 | 27708 |
| TCP 可达数 | 3000 |
| 真测通过数 | 80 |
| verified 输出数 | 80 |
| global 输出数 | 91 |
| all 输出数 | 27708 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 37.0 |
| fetch | 4.0 |
| generate | 7.7 |
| geo | 1.4 |
| probe | 105.6 |
| real_test | 75.8 |
| tcp | 87.4 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 95 | 89 | 6 | 93.7% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 145 | 128 | 17 | 88.3% |
| socks | 6 | 4 | 2 | 66.7% |
| trojan | 16 | 7 | 9 | 43.8% |
| vless | 197 | 120 | 77 | 60.9% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 52 |
| geo:ClientOSError | 13 |
| 204:ProxyError | 10 |
| speed:ClientOSError | 8 |
| cn-block:TimeoutError | 8 |
| 204:TimeoutError | 7 |
| cn-block:ClientOSError | 6 |
| 204:ClientOSError | 5 |
| speed:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7346 |
| ConnectionRefusedError | 1046 |
| OSError | 234 |
| gaierror | 186 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.958 | prefer | 97 | 0.938 | 710 |
| Au1rxx-base64 | 0.866 | prefer | 312 | 0.792 | 1905 |
| mheidari-all | 0.46 | observe | 17 | 0.412 | 23769 |
| Surfboard-tg-mixed | 0.413 | observe | 46 | 0.326 | 7030 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4983 |
| Epodonios-all | 0.255 | observe | 0 | None | 7561 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9792 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5615 |
| barry-far-vless | 0.255 | observe | 0 | None | 5752 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-PrivateVPNs | 0.175 | observe | 0 | None | 0 | 12 |
| tg-VlessConfig | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 468 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 359 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 354 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 237 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 215 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 214 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 206 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 184 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 179 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 103 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| DeltaKronecker-all | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.326 | 15 | 31 | 46 |
| mheidari-all | 0.412 | 7 | 10 | 17 |
| Au1rxx-base64 | 0.792 | 247 | 65 | 312 |
| ermaozi | 0.938 | 91 | 6 | 97 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23769 | yes | 2.95 | 0 |
| SoliSpirit-all | 9792 | yes | 2.15 | 0 |
| Epodonios-all | 7561 | yes | 3.9 | 0 |
| Surfboard-tg-mixed | 7030 | yes | 2.2 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.61 | 0 |
| barry-far-vless | 5752 | yes | 1.49 | 0 |
| Surfboard-tg-vless | 5615 | yes | 2.39 | 0 |
| 10ium-ScrapeCategorize-Vless | 4983 | yes | 1.39 | 0 |
| DeltaKronecker-all | 4750 | yes | 3.57 | 0 |
| mahdibland-V2RayAggregator | 4246 | yes | 1.81 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 52 |
| 204 | 22 |
| cn-block | 15 |
| geo | 14 |
| speed | 10 |
