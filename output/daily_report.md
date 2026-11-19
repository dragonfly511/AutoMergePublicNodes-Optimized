# AutoNodes 每日报告

生成时间：2026-11-19 00:07:46

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 127631 |
| 去重后节点数 | 59195 |
| TCP 可达数 | 3000 |
| 真测通过数 | 81 |
| verified 输出数 | 81 |
| global 输出数 | 82 |
| all 输出数 | 59195 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 36.8 |
| fetch | 6.3 |
| generate | 23.3 |
| geo | 8.3 |
| probe | 105.2 |
| real_test | 39.4 |
| tcp | 188.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 8 | 3 | 5 | 37.5% |
| http | 20 | 19 | 1 | 95.0% |
| hysteria2 | 14 | 13 | 1 | 92.9% |
| shadowsocks | 260 | 251 | 9 | 96.5% |
| socks | 3 | 1 | 2 | 33.3% |
| vless | 25 | 1 | 24 | 4.0% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 23 |
| speed:ClientOSError | 8 |
| 204:ProxyError | 4 |
| cn-block:ClientOSError | 3 |
| geo:ClientOSError | 3 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14616 |
| ConnectionRefusedError | 2337 |
| gaierror | 593 |
| OSError | 325 |
| SSRFBlocked | 4 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.949 | prefer | 310 | 0.871 | 45096 |
| ermaozi | 0.929 | prefer | 20 | 0.95 | 508 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4919 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2925 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11962 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 8521 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5794 |
| barry-far-vless | 0.255 | observe | 0 | None | 5945 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4458 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-golestan_vpn | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| tg-shadowproxy66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 456 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 451 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 334 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 312 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 311 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 303 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 281 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 276 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 200 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 187 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.0 | 0 | 1 | 1 |
| dragon | 0.871 | 270 | 40 | 310 |
| ermaozi | 0.95 | 19 | 1 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45096 | yes | 5.88 | 0 |
| mheidari-all | 14261 | yes | 4.53 | 0 |
| SoliSpirit-all | 11962 | yes | 2.83 | 0 |
| Surfboard-tg-mixed | 8521 | yes | 3.1 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.9 | 0 |
| barry-far-vless | 5945 | yes | 0.79 | 0 |
| Surfboard-tg-vless | 5794 | yes | 2.65 | 0 |
| 10ium-ScrapeCategorize-Vless | 4919 | yes | 1.91 | 0 |
| mahdibland-V2RayAggregator | 4458 | yes | 2.18 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.6 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.04 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 23 |
| speed | 8 |
| 204 | 5 |
| cn-block | 3 |
| geo | 3 |
