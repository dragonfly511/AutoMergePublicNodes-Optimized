# AutoNodes 每日报告

生成时间：2026-11-15 05:35:21

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 19/0 |
| 清理建议：优先/观察 | 2/87 |
| 原始节点数 | 127464 |
| 去重后节点数 | 58627 |
| TCP 可达数 | 3000 |
| 真测通过数 | 84 |
| verified 输出数 | 84 |
| global 输出数 | 84 |
| all 输出数 | 58627 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 31.4 |
| fetch | 5.0 |
| generate | 19.4 |
| geo | 1.7 |
| probe | 89.2 |
| real_test | 36.3 |
| tcp | 198.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 0 | 1 | 0.0% |
| http | 40 | 39 | 1 | 97.5% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 201 | 189 | 12 | 94.0% |
| socks | 5 | 4 | 1 | 80.0% |
| trojan | 57 | 49 | 8 | 86.0% |
| vless | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 13 |
| 204:ProxyError | 7 |
| geo:ClientOSError | 2 |
| speed:TimeoutError | 2 |
| 204:TimeoutError | 2 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 14508 |
| ConnectionRefusedError | 2291 |
| gaierror | 817 |
| OSError | 340 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.991 | prefer | 279 | 0.914 | 44363 |
| ermaozi | 0.975 | prefer | 40 | 0.975 | 576 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 13787 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4966 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2652 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 11652 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 9013 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6319 |
| barry-far-vless | 0.255 | observe | 0 | None | 6499 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-VmessProtocol | 0.025 | observe | 0 | None | 1 | 0 |
| ermaozi-get_subscribe | 0.145 | observe | 1 | 0.0 | 0 | 434 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| ripaojiedian-freenode | 0.175 | observe | 0 | None | 0 | 12 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 447 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 442 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 325 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 303 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 302 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 294 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 272 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 267 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 191 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 178 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi-get_subscribe | 0.0 | 0 | 1 | 1 |
| dragon | 0.914 | 255 | 24 | 279 |
| ermaozi | 0.975 | 39 | 1 | 40 |
| mheidari-all | 1.0 | 1 | 0 | 1 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44363 | yes | 4.31 | 0 |
| mheidari-all | 13787 | yes | 2.61 | 0 |
| SoliSpirit-all | 11652 | yes | 1.62 | 0 |
| Surfboard-tg-mixed | 9013 | yes | 2.18 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.74 | 0 |
| barry-far-vless | 6499 | yes | 0.94 | 0 |
| Surfboard-tg-vless | 6319 | yes | 2.01 | 0 |
| 10ium-ScrapeCategorize-Vless | 4966 | yes | 0.65 | 0 |
| mahdibland-V2RayAggregator | 4551 | yes | 0.13 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.53 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.0 |
| anytls | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 13 |
| 204 | 9 |
| geo | 2 |
| speed | 2 |
