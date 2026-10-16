# AutoNodes 每日报告

生成时间：2026-10-16 06:26:04

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 2/92 |
| 原始节点数 | 99735 |
| 去重后节点数 | 27925 |
| TCP 可达数 | 3000 |
| 真测通过数 | 104 |
| verified 输出数 | 104 |
| global 输出数 | 112 |
| all 输出数 | 27925 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 28.5 |
| fetch | 10.3 |
| generate | 12.0 |
| geo | 1.5 |
| probe | 110.0 |
| real_test | 86.2 |
| tcp | 88.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 90 | 89 | 1 | 98.9% |
| hysteria2 | 14 | 12 | 2 | 85.7% |
| shadowsocks | 141 | 128 | 13 | 90.8% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 27 | 15 | 12 | 55.6% |
| vless | 269 | 130 | 139 | 48.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 114 |
| geo:ClientOSError | 18 |
| speed:ClientOSError | 13 |
| cn-block:ClientOSError | 7 |
| 204:TimeoutError | 5 |
| cn-block:ProxyError | 4 |
| 204:ProxyError | 3 |
| 204:ClientOSError | 2 |
| geo:ProxyError | 1 |
| cn-block:TimeoutError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7182 |
| ConnectionRefusedError | 1010 |
| OSError | 237 |
| gaierror | 177 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | prefer | 89 | 0.989 | 693 |
| Au1rxx-base64 | 0.823 | prefer | 345 | 0.745 | 1992 |
| Surfboard-tg-mixed | 0.461 | observe | 11 | 0.545 | 7054 |
| mheidari-all | 0.325 | observe | 96 | 0.24 | 23985 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| tg-oneclickvpnkeys | 0.258 | observe | 1 | 1.0 | 79 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5024 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1992 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 5147 |
| Epodonios-all | 0.255 | observe | 0 | None | 7651 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 459 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 350 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 345 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 228 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 206 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 205 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 197 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 175 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 170 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 94 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.24 | 23 | 73 | 96 |
| Surfboard-tg-mixed | 0.545 | 6 | 5 | 11 |
| Au1rxx-base64 | 0.745 | 257 | 88 | 345 |
| ermaozi | 0.989 | 88 | 1 | 89 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23985 | yes | 5.69 | 0 |
| SoliSpirit-all | 10060 | yes | 4.55 | 0 |
| Epodonios-all | 7651 | yes | 6.56 | 0 |
| Surfboard-tg-mixed | 7054 | yes | 4.86 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.8 | 0 |
| barry-far-vless | 5882 | yes | 3.22 | 0 |
| Surfboard-tg-vless | 5573 | yes | 3.95 | 0 |
| DeltaKronecker-all | 5147 | yes | 5.3 | 0 |
| 10ium-ScrapeCategorize-Vless | 5024 | yes | 1.94 | 0 |
| mahdibland-V2RayAggregator | 4265 | yes | 3.31 | 0 |

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
| test_one_timeout | 114 |
| geo | 20 |
| speed | 13 |
| cn-block | 12 |
| 204 | 10 |
