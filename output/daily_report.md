# AutoNodes 每日报告

生成时间：2026-10-15 11:37:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 13/0 |
| 清理建议：优先/观察 | 3/91 |
| 原始节点数 | 99891 |
| 去重后节点数 | 27872 |
| TCP 可达数 | 3000 |
| 真测通过数 | 95 |
| verified 输出数 | 95 |
| global 输出数 | 102 |
| all 输出数 | 27872 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.7 |
| fetch | 7.8 |
| generate | 13.8 |
| geo | 1.5 |
| probe | 105.1 |
| real_test | 68.1 |
| tcp | 85.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 78 | 76 | 2 | 97.4% |
| hysteria2 | 8 | 7 | 1 | 87.5% |
| shadowsocks | 128 | 119 | 9 | 93.0% |
| socks | 3 | 1 | 2 | 33.3% |
| trojan | 10 | 6 | 4 | 60.0% |
| vless | 201 | 124 | 77 | 61.7% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 58 |
| speed:ClientOSError | 14 |
| cn-block:ClientOSError | 5 |
| 204:ProxyError | 5 |
| geo:ClientOSError | 3 |
| cn-block:ProxyError | 2 |
| cn-block:TimeoutError | 2 |
| 204:TimeoutError | 2 |
| speed:TimeoutError | 2 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6722 |
| ConnectionRefusedError | 1041 |
| OSError | 234 |
| gaierror | 221 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.979 | prefer | 80 | 0.963 | 703 |
| Au1rxx-base64 | 0.814 | prefer | 326 | 0.742 | 1830 |
| mheidari-all | 0.716 | prefer | 20 | 0.65 | 24005 |
| Surfboard-tg-mixed | 0.391 | observe | 2 | 1.0 | 7139 |
| 10ium-HighSpeed | 0.289 | observe | 1 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5089 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 5147 |
| Epodonios-all | 0.255 | observe | 0 | None | 7652 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10113 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ArV2ray | 0.025 | observe | 0 | None | 1 | 0 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 9 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-DirectVPN | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 455 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 346 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 341 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 224 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 202 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 201 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 193 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 171 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 166 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 90 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.65 | 13 | 7 | 20 |
| Au1rxx-base64 | 0.742 | 242 | 84 | 326 |
| ermaozi | 0.963 | 77 | 3 | 80 |
| 10ium-HighSpeed | 1.0 | 1 | 0 | 1 |
| Surfboard-tg-mixed | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 24005 | yes | 6.47 | 0 |
| SoliSpirit-all | 10113 | yes | 3.56 | 0 |
| Epodonios-all | 7652 | yes | 7.09 | 0 |
| Surfboard-tg-mixed | 7139 | yes | 4.66 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.17 | 0 |
| barry-far-vless | 5924 | yes | 2.22 | 0 |
| Surfboard-tg-vless | 5693 | yes | 6.67 | 0 |
| DeltaKronecker-all | 5147 | yes | 6.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 5089 | yes | 2.01 | 0 |
| mahdibland-V2RayAggregator | 4338 | yes | 1.26 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 58 |
| speed | 16 |
| cn-block | 9 |
| 204 | 8 |
| geo | 4 |
