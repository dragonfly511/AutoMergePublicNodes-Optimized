# AutoNodes 每日报告

生成时间：2026-10-17 18:15:54

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 99383 |
| 去重后节点数 | 27816 |
| TCP 可达数 | 3000 |
| 真测通过数 | 64 |
| verified 输出数 | 64 |
| global 输出数 | 67 |
| all 输出数 | 27816 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.7 |
| fetch | 7.8 |
| generate | 14.2 |
| geo | 1.5 |
| probe | 113.7 |
| real_test | 70.3 |
| tcp | 83.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 28 | 26 | 2 | 92.9% |
| hysteria2 | 13 | 10 | 3 | 76.9% |
| shadowsocks | 136 | 108 | 28 | 79.4% |
| socks | 2 | 1 | 1 | 50.0% |
| trojan | 14 | 3 | 11 | 21.4% |
| vless | 204 | 113 | 91 | 55.4% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 84 |
| speed:ClientOSError | 15 |
| 204:ProxyError | 9 |
| geo:ClientOSError | 9 |
| 204:TimeoutError | 8 |
| cn-block:ClientOSError | 4 |
| 204:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| speed:ProxyError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6681 |
| ConnectionRefusedError | 1031 |
| gaierror | 249 |
| OSError | 234 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.925 | prefer | 28 | 0.929 | 623 |
| Au1rxx-base64 | 0.733 | prefer | 327 | 0.654 | 1992 |
| mheidari-all | 0.612 | observe | 16 | 0.625 | 23824 |
| Surfboard-tg-mixed | 0.563 | observe | 27 | 0.481 | 7087 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4986 |
| Au1rxx-clash | 0.255 | observe | 0 | None | 1992 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 4999 |
| Epodonios-all | 0.255 | observe | 0 | None | 7677 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10164 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 11 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 4 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 465 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 356 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 351 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 234 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 212 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 211 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 203 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 181 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 176 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 100 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Surfboard-tg-mixed | 0.481 | 13 | 14 | 27 |
| mheidari-all | 0.625 | 10 | 6 | 16 |
| Au1rxx-base64 | 0.654 | 214 | 113 | 327 |
| ermaozi | 0.929 | 26 | 2 | 28 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23824 | yes | 6.7 | 0 |
| SoliSpirit-all | 10164 | yes | 2.99 | 0 |
| Epodonios-all | 7677 | yes | 7.0 | 0 |
| Surfboard-tg-mixed | 7087 | yes | 4.69 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.24 | 0 |
| barry-far-vless | 5866 | yes | 1.58 | 0 |
| Surfboard-tg-vless | 5622 | yes | 4.47 | 0 |
| DeltaKronecker-all | 4999 | yes | 5.84 | 0 |
| 10ium-ScrapeCategorize-Vless | 4986 | yes | 2.15 | 0 |
| mahdibland-V2RayAggregator | 4295 | yes | 1.93 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 84 |
| 204 | 20 |
| speed | 16 |
| geo | 9 |
| cn-block | 7 |
