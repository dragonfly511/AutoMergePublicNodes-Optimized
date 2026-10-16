# AutoNodes 每日报告

生成时间：2026-10-16 00:18:40

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 2/92 |
| 原始节点数 | 99664 |
| 去重后节点数 | 27756 |
| TCP 可达数 | 3000 |
| 真测通过数 | 87 |
| verified 输出数 | 87 |
| global 输出数 | 95 |
| all 输出数 | 27756 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.8 |
| fetch | 6.6 |
| generate | 11.2 |
| geo | 1.5 |
| probe | 98.6 |
| real_test | 93.3 |
| tcp | 85.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 67 | 66 | 1 | 98.5% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 144 | 137 | 7 | 95.1% |
| socks | 1 | 0 | 1 | 0.0% |
| trojan | 22 | 17 | 5 | 77.3% |
| vless | 395 | 203 | 192 | 51.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 113 |
| speed:ClientOSError | 36 |
| geo:ClientOSError | 21 |
| 204:ProxyError | 9 |
| cn-block:ClientOSError | 8 |
| 204:TimeoutError | 8 |
| 204:ClientOSError | 4 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 2 |
| geo:TimeoutError | 1 |
| speed:TimeoutError | 1 |
| cn-block:ServerDisconnectedError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6901 |
| ConnectionRefusedError | 1018 |
| OSError | 239 |
| gaierror | 231 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.997 | prefer | 67 | 0.985 | 659 |
| Au1rxx-base64 | 0.852 | prefer | 406 | 0.776 | 1933 |
| mheidari-all | 0.413 | observe | 169 | 0.331 | 24047 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 7135 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5089 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 5147 |
| Epodonios-all | 0.255 | observe | 0 | None | 7682 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 9914 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5628 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 458 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 349 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 344 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 227 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 205 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 204 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 196 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 174 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 169 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 93 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.331 | 56 | 113 | 169 |
| Au1rxx-base64 | 0.776 | 315 | 91 | 406 |
| ermaozi | 0.985 | 66 | 1 | 67 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24047 | yes | 4.77 | 0 |
| SoliSpirit-all | 9914 | yes | 3.82 | 0 |
| Epodonios-all | 7682 | yes | 4.19 | 0 |
| Surfboard-tg-mixed | 7135 | yes | 3.52 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.68 | 0 |
| barry-far-vless | 5879 | yes | 1.25 | 0 |
| Surfboard-tg-vless | 5628 | yes | 3.7 | 0 |
| DeltaKronecker-all | 5147 | yes | 5.58 | 0 |
| 10ium-ScrapeCategorize-Vless | 5089 | yes | 1.15 | 0 |
| mahdibland-V2RayAggregator | 4235 | yes | 1.37 | 0 |

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
| test_one_timeout | 113 |
| speed | 37 |
| geo | 24 |
| 204 | 21 |
| cn-block | 11 |
