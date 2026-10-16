# AutoNodes 每日报告

生成时间：2026-10-16 18:22:18

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 2/92 |
| 原始节点数 | 98871 |
| 去重后节点数 | 27543 |
| TCP 可达数 | 3000 |
| 真测通过数 | 95 |
| verified 输出数 | 95 |
| global 输出数 | 97 |
| all 输出数 | 27543 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 27.6 |
| fetch | 4.8 |
| generate | 9.0 |
| geo | 1.4 |
| probe | 100.8 |
| real_test | 74.6 |
| tcp | 88.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 61 | 59 | 2 | 96.7% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 130 | 94 | 36 | 72.3% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 7 | 7 | 0 | 100.0% |
| vless | 191 | 108 | 83 | 56.5% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 87 |
| geo:ClientOSError | 10 |
| speed:ClientOSError | 9 |
| 204:ProxyError | 6 |
| 204:TimeoutError | 5 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 3 |
| geo:ProxyError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7379 |
| ConnectionRefusedError | 1024 |
| OSError | 235 |
| gaierror | 106 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | prefer | 57 | 1.0 | 618 |
| Au1rxx-base64 | 0.743 | prefer | 304 | 0.664 | 1991 |
| mheidari-all | 0.666 | observe | 27 | 0.593 | 23759 |
| Surfboard-tg-mixed | 0.352 | observe | 11 | 0.364 | 7090 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5024 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1991 |
| Epodonios-all | 0.255 | observe | 0 | None | 7602 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9925 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 461 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 352 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 347 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 230 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 208 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 207 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 199 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 177 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 172 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 96 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| DeltaKronecker-all | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.364 | 4 | 7 | 11 |
| tg-oneclickvpnkeys | 0.5 | 2 | 2 | 4 |
| mheidari-all | 0.593 | 16 | 11 | 27 |
| Au1rxx-base64 | 0.664 | 202 | 102 | 304 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 57 | 0 | 57 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23759 | yes | 3.66 | 0 |
| SoliSpirit-all | 9925 | yes | 2.46 | 0 |
| Epodonios-all | 7602 | yes | 4.48 | 0 |
| Surfboard-tg-mixed | 7090 | yes | 3.8 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.66 | 0 |
| barry-far-vless | 5822 | yes | 1.64 | 0 |
| Surfboard-tg-vless | 5572 | yes | 2.96 | 0 |
| 10ium-ScrapeCategorize-Vless | 5024 | yes | 1.52 | 0 |
| DeltaKronecker-all | 4946 | yes | 4.03 | 0 |
| mahdibland-V2RayAggregator | 4255 | yes | 1.1 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 87 |
| 204 | 14 |
| geo | 11 |
| speed | 9 |
| cn-block | 4 |
