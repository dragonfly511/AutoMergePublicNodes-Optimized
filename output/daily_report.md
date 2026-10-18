# AutoNodes 每日报告

生成时间：2026-10-18 19:59:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 4/89 |
| 原始节点数 | 97816 |
| 去重后节点数 | 27677 |
| TCP 可达数 | 3000 |
| 真测通过数 | 60 |
| verified 输出数 | 60 |
| global 输出数 | 63 |
| all 输出数 | 27677 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 30.8 |
| fetch | 4.5 |
| generate | 8.5 |
| geo | 1.4 |
| probe | 85.9 |
| real_test | 64.2 |
| tcp | 90.7 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 32 | 29 | 3 | 90.6% |
| hysteria2 | 9 | 8 | 1 | 88.9% |
| shadowsocks | 129 | 118 | 11 | 91.5% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 7 | 6 | 1 | 85.7% |
| vless | 159 | 90 | 69 | 56.6% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 47 |
| speed:ClientOSError | 13 |
| geo:ClientOSError | 10 |
| 204:TimeoutError | 5 |
| cn-block:TimeoutError | 3 |
| 204:ProxyError | 2 |
| geo:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:49221: bind: address already in use | 1 |
| speed:ProxyError | 1 |
| cn-block:ProxyError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 7668 |
| ConnectionRefusedError | 993 |
| OSError | 235 |
| gaierror | 90 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.911 | prefer | 33 | 0.909 | 639 |
| Au1rxx-base64 | 0.825 | prefer | 190 | 0.758 | 1742 |
| Surfboard-tg-mixed | 0.766 | prefer | 49 | 0.694 | 7036 |
| mheidari-all | 0.747 | prefer | 70 | 0.671 | 23629 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4983 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 4750 |
| Epodonios-all | 0.255 | observe | 0 | None | 7503 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10062 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5553 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 12 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 4 |
| tg-freeiranianv2rey | 0.175 | observe | 0 | None | 0 | 12 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 469 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 360 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 355 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 238 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 216 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 215 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 207 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 185 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 180 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 104 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.671 | 47 | 23 | 70 |
| Surfboard-tg-mixed | 0.694 | 34 | 15 | 49 |
| Au1rxx-base64 | 0.758 | 144 | 46 | 190 |
| ermaozi | 0.909 | 30 | 3 | 33 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23629 | yes | 3.38 | 0 |
| SoliSpirit-all | 10062 | yes | 2.81 | 0 |
| Epodonios-all | 7503 | yes | 3.55 | 0 |
| Surfboard-tg-mixed | 7036 | yes | 2.37 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.78 | 0 |
| barry-far-vless | 5767 | yes | 1.09 | 0 |
| Surfboard-tg-vless | 5553 | yes | 2.25 | 0 |
| 10ium-ScrapeCategorize-Vless | 4983 | yes | 1.9 | 0 |
| DeltaKronecker-all | 4750 | yes | 3.97 | 0 |
| mahdibland-V2RayAggregator | 4246 | yes | 1.9 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 47 |
| speed | 14 |
| geo | 12 |
| 204 | 7 |
| cn-block | 6 |
| sing-box exited 1 | 1 |
