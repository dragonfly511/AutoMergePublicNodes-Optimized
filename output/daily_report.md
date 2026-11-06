# AutoNodes 每日报告

生成时间：2026-11-06 14:01:38

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 18/0 |
| 清理建议：优先/观察 | 2/88 |
| 原始节点数 | 128555 |
| 去重后节点数 | 59352 |
| TCP 可达数 | 3000 |
| 真测通过数 | 50 |
| verified 输出数 | 50 |
| global 输出数 | 51 |
| all 输出数 | 59352 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 22.1 |
| fetch | 5.1 |
| generate | 18.8 |
| geo | 1.6 |
| probe | 70.8 |
| real_test | 26.9 |
| tcp | 200.3 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 33 | 33 | 0 | 100.0% |
| hysteria2 | 16 | 14 | 2 | 87.5% |
| shadowsocks | 14 | 13 | 1 | 92.9% |
| socks | 2 | 0 | 2 | 0.0% |
| trojan | 60 | 38 | 22 | 63.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 13 |
| test_one_timeout:15.0s | 8 |
| geo:ProxyError | 2 |
| cn-block:ProxyError | 1 |
| 204:ClientOSError | 1 |
| speed:ProxyError | 1 |
| 204:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15651 |
| ConnectionRefusedError | 2528 |
| gaierror | 406 |
| OSError | 340 |
| SSRFBlocked | 3 |
| ConnectionResetError | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.993 | prefer | 34 | 1.0 | 513 |
| dragon | 0.793 | prefer | 92 | 0.717 | 45886 |
| xiaoji235-airport-v2ray-all | 0.335 | observe | 1 | 1.0 | 6752 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4934 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2768 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10967 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 6268 |
| barry-far-vless | 0.255 | observe | 0 | None | 6479 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4703 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| tg-ConfigWireguard | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ShadowsocksM | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 7 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 11 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 423 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 418 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 301 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 279 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 278 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 270 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 248 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 243 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 167 | 连续死亡次数 >= 2 |
| disable | tg-AzadNet | 0.0 | 0 | None | 154 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.0 | 0 | 1 | 1 |
| dragon | 0.717 | 66 | 26 | 92 |
| xiaoji235-airport-v2ray-all | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 34 | 0 | 34 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45886 | yes | 4.65 | 0 |
| mheidari-all | 14174 | yes | 3.4 | 0 |
| SoliSpirit-all | 10967 | yes | 1.98 | 0 |
| Surfboard-tg-mixed | 8762 | yes | 2.89 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.07 | 0 |
| barry-far-vless | 6479 | yes | 0.22 | 0 |
| Surfboard-tg-vless | 6268 | yes | 2.24 | 0 |
| 10ium-ScrapeCategorize-Vless | 4934 | yes | 0.87 | 0 |
| mahdibland-V2RayAggregator | 4703 | yes | 0.12 | 0 |
| MatinGhanbari-all-sub | 3997 | yes | 0.76 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_drop_50pct | verified output dropped from 119 to 50 |
| real_ok_drop_50pct | real-test ok dropped from 119 to 50 |

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| socks | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 15 |
| test_one_timeout | 8 |
| geo | 2 |
| cn-block | 1 |
| speed | 1 |
