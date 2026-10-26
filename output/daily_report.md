# AutoNodes 每日报告

生成时间：2026-10-26 22:32:19

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 15/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 142481 |
| 去重后节点数 | 58971 |
| TCP 可达数 | 3000 |
| 真测通过数 | 62 |
| verified 输出数 | 62 |
| global 输出数 | 63 |
| all 输出数 | 58971 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.5 |
| fetch | 6.9 |
| generate | 22.8 |
| geo | 1.6 |
| probe | 85.0 |
| real_test | 24.4 |
| tcp | 203.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 36 | 33 | 3 | 91.7% |
| hysteria2 | 11 | 11 | 0 | 100.0% |
| shadowsocks | 7 | 6 | 1 | 85.7% |
| socks | 6 | 2 | 4 | 33.3% |
| trojan | 62 | 60 | 2 | 96.8% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 2 |
| cn-block:ProxyError | 2 |
| test_one_timeout:15.0s | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:32908: bind: address already in use | 1 |
| 204:TimeoutError | 1 |
| speed:ClientOSError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15529 |
| ConnectionRefusedError | 2376 |
| gaierror | 469 |
| OSError | 281 |
| SSRFBlocked | 5 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.991 | prefer | 88 | 0.92 | 45531 |
| ermaozi | 0.917 | prefer | 36 | 0.917 | 564 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4919 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3004 |
| Epodonios-all | 0.255 | observe | 0 | None | 7537 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10741 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7052 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5366 |
| barry-far-vless | 0.255 | observe | 0 | None | 5651 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 10 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 499 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 390 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 385 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 268 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 246 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 245 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 237 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 215 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 210 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 134 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi | 0.917 | 33 | 3 | 36 |
| dragon | 0.92 | 81 | 7 | 88 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45531 | yes | 6.33 | 0 |
| mheidari-all | 24769 | yes | 4.76 | 0 |
| SoliSpirit-all | 10741 | yes | 2.48 | 0 |
| Epodonios-all | 7537 | yes | 1.2 | 0 |
| Surfboard-tg-mixed | 7052 | yes | 2.98 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.27 | 0 |
| barry-far-vless | 5651 | yes | 1.57 | 0 |
| Surfboard-tg-vless | 5366 | yes | 3.1 | 0 |
| 10ium-ScrapeCategorize-Vless | 4919 | yes | 1.03 | 0 |
| mahdibland-V2RayAggregator | 4466 | yes | 2.41 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 3 |
| cn-block | 3 |
| test_one_timeout | 2 |
| sing-box exited 1 | 1 |
| speed | 1 |
