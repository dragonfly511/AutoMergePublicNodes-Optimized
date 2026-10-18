# AutoNodes 每日报告

生成时间：2026-10-18 06:21:49

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 98948 |
| 去重后节点数 | 27852 |
| TCP 可达数 | 3000 |
| 真测通过数 | 92 |
| verified 输出数 | 92 |
| global 输出数 | 99 |
| all 输出数 | 27852 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 40.5 |
| fetch | 9.2 |
| generate | 14.0 |
| geo | 1.5 |
| probe | 112.5 |
| real_test | 91.3 |
| tcp | 86.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 100 | 90 | 10 | 90.0% |
| hysteria2 | 19 | 15 | 4 | 78.9% |
| shadowsocks | 146 | 135 | 11 | 92.5% |
| socks | 7 | 5 | 2 | 71.4% |
| trojan | 37 | 16 | 21 | 43.2% |
| vless | 288 | 161 | 127 | 55.9% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 104 |
| geo:ClientOSError | 21 |
| speed:ClientOSError | 14 |
| 204:TimeoutError | 9 |
| 204:ProxyError | 7 |
| cn-block:ClientOSError | 6 |
| cn-block:ProxyError | 5 |
| speed:ProxyError | 3 |
| 204:ClientOSError | 2 |
| geo:TimeoutError | 2 |
| geo:ProxyError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7005 |
| ConnectionRefusedError | 1038 |
| OSError | 235 |
| gaierror | 186 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.931 | prefer | 101 | 0.911 | 710 |
| Au1rxx-base64 | 0.849 | prefer | 356 | 0.781 | 1738 |
| Surfboard-tg-mixed | 0.539 | observe | 72 | 0.458 | 7093 |
| mheidari-all | 0.368 | observe | 64 | 0.281 | 23946 |
| tg-OutlineReleasedKey | 0.257 | observe | 1 | 1.0 | 52 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4983 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 4999 |
| Epodonios-all | 0.255 | observe | 0 | None | 7567 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10022 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-yudou | 0.134 | observe | 1 | 0.0 | 0 | 166 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
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
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 467 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 358 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 353 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 236 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 214 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 213 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 205 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 183 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 178 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 102 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| Barabama-yudou | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.281 | 18 | 46 | 64 |
| Surfboard-tg-mixed | 0.458 | 33 | 39 | 72 |
| tg-oneclickvpnkeys | 0.5 | 1 | 1 | 2 |
| Au1rxx-base64 | 0.781 | 278 | 78 | 356 |
| ermaozi | 0.911 | 92 | 9 | 101 |
| tg-OutlineReleasedKey | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23946 | yes | 6.24 | 0 |
| SoliSpirit-all | 10022 | yes | 4.55 | 0 |
| Epodonios-all | 7567 | yes | 7.4 | 0 |
| Surfboard-tg-mixed | 7093 | yes | 4.88 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.48 | 0 |
| barry-far-vless | 5884 | yes | 2.48 | 0 |
| Surfboard-tg-vless | 5669 | yes | 4.32 | 0 |
| DeltaKronecker-all | 4999 | yes | 6.17 | 0 |
| 10ium-ScrapeCategorize-Vless | 4983 | yes | 2.05 | 0 |
| mahdibland-V2RayAggregator | 4246 | yes | 2.18 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 104 |
| geo | 24 |
| 204 | 18 |
| speed | 17 |
| cn-block | 12 |
