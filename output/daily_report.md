# AutoNodes 每日报告

生成时间：2026-10-31 04:46:08

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 125511 |
| 去重后节点数 | 58450 |
| TCP 可达数 | 3000 |
| 真测通过数 | 133 |
| verified 输出数 | 133 |
| global 输出数 | 133 |
| all 输出数 | 58450 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 29.7 |
| fetch | 5.0 |
| generate | 18.8 |
| geo | 1.5 |
| probe | 70.1 |
| real_test | 35.1 |
| tcp | 204.1 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 5 | 4 | 1 | 80.0% |
| http | 91 | 87 | 4 | 95.6% |
| hysteria2 | 14 | 14 | 0 | 100.0% |
| shadowsocks | 4 | 2 | 2 | 50.0% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 96 | 90 | 6 | 93.8% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 9 |
| 204:ClientOSError | 1 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:45552: bind: address already in use | 1 |
| geo:ClientOSError | 1 |
| 204:TimeoutError | 1 |
| speed:TimeoutError | 1 |
| speed:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15003 |
| ConnectionRefusedError | 2273 |
| gaierror | 482 |
| OSError | 342 |
| SSRFBlocked | 3 |
| UnicodeError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.982 | prefer | 120 | 0.908 | 44960 |
| ermaozi | 0.971 | prefer | 91 | 0.956 | 622 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4960 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2724 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10522 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7827 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5680 |
| barry-far-vless | 0.255 | observe | 0 | None | 5895 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-ConfigWireguard | 0.175 | observe | 0 | None | 0 | 2 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 513 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 404 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 399 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 282 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 260 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 259 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 251 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 229 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 224 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 148 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.908 | 109 | 11 | 120 |
| ermaozi | 0.956 | 87 | 4 | 91 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44960 | yes | 4.02 | 0 |
| mheidari-all | 14594 | yes | 4.24 | 0 |
| SoliSpirit-all | 10522 | yes | 2.41 | 0 |
| Surfboard-tg-mixed | 7827 | yes | 2.31 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.03 | 0 |
| barry-far-vless | 5895 | yes | 0.98 | 0 |
| Surfboard-tg-vless | 5680 | yes | 2.2 | 0 |
| 10ium-ScrapeCategorize-Vless | 4960 | yes | 1.13 | 0 |
| mahdibland-V2RayAggregator | 4459 | yes | 0.13 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 0.85 | 0 |

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
| test_one_timeout | 9 |
| 204 | 2 |
| speed | 2 |
| sing-box exited 1 | 1 |
| geo | 1 |
