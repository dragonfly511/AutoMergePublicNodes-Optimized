# AutoNodes 每日报告

生成时间：2026-10-26 12:36:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 15/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 142330 |
| 去重后节点数 | 59631 |
| TCP 可达数 | 3000 |
| 真测通过数 | 113 |
| verified 输出数 | 113 |
| global 输出数 | 113 |
| all 输出数 | 59631 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.7 |
| fetch | 9.3 |
| generate | 30.4 |
| geo | 1.7 |
| probe | 100.6 |
| real_test | 26.0 |
| tcp | 201.1 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 3 | 2 | 1 | 66.7% |
| http | 104 | 101 | 3 | 97.1% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 5 | 2 | 3 | 40.0% |
| socks | 7 | 3 | 4 | 42.9% |
| trojan | 37 | 31 | 6 | 83.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 12 |
| 204:ProxyError | 3 |
| 204:ClientOSError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:35140: bind: address already in use | 1 |
| 204:TimeoutError | 1 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15843 |
| ConnectionRefusedError | 2389 |
| gaierror | 478 |
| OSError | 321 |
| SSRFBlocked | 3 |
| ConnectionResetError | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.988 | prefer | 103 | 0.971 | 643 |
| dragon | 0.818 | prefer | 63 | 0.746 | 45637 |
| Au1rxx-base64 | 0.323 | observe | 1 | 1.0 | 1689 |
| tg-LonUp_M | 0.262 | observe | 1 | 1.0 | 167 |
| zhangkai | 0.257 | observe | 1 | 1.0 | 43 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4919 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3004 |
| Epodonios-all | 0.255 | observe | 0 | None | 7666 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10302 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 498 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 389 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 384 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 245 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 244 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 236 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 214 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 209 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 133 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.746 | 47 | 16 | 63 |
| ermaozi | 0.971 | 100 | 3 | 103 |
| Au1rxx-base64 | 1.0 | 1 | 0 | 1 |
| tg-LonUp_M | 1.0 | 1 | 0 | 1 |
| zhangkai | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45637 | yes | 8.73 | 0 |
| mheidari-all | 24314 | yes | 6.19 | 0 |
| SoliSpirit-all | 10302 | yes | 3.92 | 0 |
| Epodonios-all | 7666 | yes | 4.58 | 0 |
| Surfboard-tg-mixed | 7197 | yes | 3.84 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.25 | 0 |
| barry-far-vless | 5877 | yes | 1.45 | 0 |
| Surfboard-tg-vless | 5522 | yes | 3.6 | 0 |
| 10ium-ScrapeCategorize-Vless | 4919 | yes | 1.68 | 0 |
| mahdibland-V2RayAggregator | 4228 | yes | 2.72 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 12 |
| 204 | 5 |
| sing-box exited 1 | 1 |
| geo | 1 |
