# AutoNodes 每日报告

生成时间：2026-10-21 21:10:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 92/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 3/90 |
| 原始节点数 | 96105 |
| 去重后节点数 | 26894 |
| TCP 可达数 | 3000 |
| 真测通过数 | 97 |
| verified 输出数 | 97 |
| global 输出数 | 104 |
| all 输出数 | 26894 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 36.8 |
| fetch | 8.0 |
| generate | 13.4 |
| geo | 1.6 |
| probe | 104.0 |
| real_test | 78.9 |
| tcp | 83.4 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 29 | 26 | 3 | 89.7% |
| hysteria2 | 13 | 12 | 1 | 92.3% |
| shadowsocks | 142 | 130 | 12 | 91.5% |
| socks | 3 | 0 | 3 | 0.0% |
| trojan | 27 | 13 | 14 | 48.1% |
| vless | 182 | 97 | 85 | 53.3% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 63 |
| speed:ClientOSError | 12 |
| geo:ClientOSError | 12 |
| 204:TimeoutError | 9 |
| 204:ProxyError | 8 |
| cn-block:ClientOSError | 5 |
| cn-block:TimeoutError | 4 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:45172: bind: address already in use | 1 |
| cn-block:ProxyError | 1 |
| speed:TimeoutError | 1 |
| 204:ClientOSError | 1 |
| geo:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6581 |
| ConnectionRefusedError | 1034 |
| OSError | 236 |
| gaierror | 182 |
| SSRFBlocked | 3 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.927 | prefer | 25 | 0.96 | 31 |
| mheidari-all | 0.903 | prefer | 77 | 0.831 | 23903 |
| Au1rxx-base64 | 0.756 | prefer | 206 | 0.694 | 1598 |
| Surfboard-tg-mixed | 0.653 | observe | 80 | 0.575 | 7007 |
| ermaozi-get_subscribe | 0.27 | observe | 1 | 1.0 | 385 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4925 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 4067 |
| Epodonios-all | 0.255 | observe | 0 | None | 7500 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10034 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ConfigV2rayNG | 0.135 | observe | 1 | 0.0 | 0 | 200 |
| tg-V2RAYProxy | 0.136 | observe | 1 | 0.0 | 0 | 217 |
| ninja-vless | 0.161 | observe | 3 | 0.0 | 0 | 1791 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 480 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 371 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 366 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 249 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 227 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 226 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 218 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 196 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 191 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 115 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| tg-V2RAYProxy | 0.0 | 0 | 1 | 1 |
| tg-ConfigV2rayNG | 0.0 | 0 | 1 | 1 |
| ninja-vless | 0.0 | 0 | 3 | 3 |
| tg-oneclickvpnkeys | 0.333 | 1 | 2 | 3 |
| Surfboard-tg-mixed | 0.575 | 46 | 34 | 80 |
| Au1rxx-base64 | 0.694 | 143 | 63 | 206 |
| mheidari-all | 0.831 | 64 | 13 | 77 |
| zhangkai | 0.96 | 24 | 1 | 25 |
| ermaozi-get_subscribe | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23903 | yes | 6.41 | 0 |
| SoliSpirit-all | 10034 | yes | 3.48 | 0 |
| Epodonios-all | 7500 | yes | 5.72 | 0 |
| Surfboard-tg-mixed | 7007 | yes | 4.14 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.8 | 0 |
| barry-far-vless | 5734 | yes | 2.15 | 0 |
| Surfboard-tg-vless | 5519 | yes | 3.65 | 0 |
| 10ium-ScrapeCategorize-Vless | 4925 | yes | 1.89 | 0 |
| mahdibland-V2RayAggregator | 4164 | yes | 0.14 | 0 |
| DeltaKronecker-all | 4067 | yes | 6.65 | 0 |

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
| test_one_timeout | 63 |
| 204 | 18 |
| speed | 13 |
| geo | 13 |
| cn-block | 10 |
| sing-box exited 1 | 1 |
