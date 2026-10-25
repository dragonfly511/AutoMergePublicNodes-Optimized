# AutoNodes 每日报告

生成时间：2026-10-25 03:54:45

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 2/92 |
| 原始节点数 | 142469 |
| 去重后节点数 | 60019 |
| TCP 可达数 | 3000 |
| 真测通过数 | 91 |
| verified 输出数 | 91 |
| global 输出数 | 92 |
| all 输出数 | 60019 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 38.1 |
| fetch | 7.1 |
| generate | 23.7 |
| geo | 1.6 |
| probe | 117.2 |
| real_test | 51.8 |
| tcp | 209.2 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 80 | 76 | 4 | 95.0% |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 153 | 139 | 14 | 90.8% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 11 | 8 | 3 | 72.7% |
| vless | 1 | 1 | 0 | 100.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| 204:ProxyError | 5 |
| 204:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:36896: bind: address already in use | 1 |
| cn-block:ClientOSError | 1 |
| cn-block:TimeoutError | 1 |
| 204:TimeoutError | 1 |
| geo:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15767 |
| ConnectionRefusedError | 2483 |
| gaierror | 568 |
| OSError | 319 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.964 | prefer | 81 | 0.951 | 604 |
| dragon | 0.962 | prefer | 185 | 0.886 | 46036 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 24115 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 107 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4911 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3780 |
| Epodonios-all | 0.255 | observe | 0 | None | 7585 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10198 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7102 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 493 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 384 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 379 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 262 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 240 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 239 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 231 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 209 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 204 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 128 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.886 | 164 | 21 | 185 |
| ermaozi | 0.951 | 77 | 4 | 81 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 46036 | yes | 6.44 | 0 |
| mheidari-all | 24115 | yes | 4.58 | 0 |
| SoliSpirit-all | 10198 | yes | 2.53 | 0 |
| Epodonios-all | 7585 | yes | 1.68 | 0 |
| Surfboard-tg-mixed | 7102 | yes | 2.96 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.68 | 0 |
| barry-far-vless | 5635 | yes | 0.87 | 0 |
| Surfboard-tg-vless | 5419 | yes | 2.59 | 0 |
| 10ium-ScrapeCategorize-Vless | 4911 | yes | 1.03 | 0 |
| mahdibland-V2RayAggregator | 4150 | yes | 2.35 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 13 |
| 204 | 8 |
| cn-block | 2 |
| sing-box exited 1 | 1 |
| geo | 1 |
