# AutoNodes 每日报告

生成时间：2026-10-29 05:02:12

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 88/108 |
| 清理建议：禁用/降权 | 16/0 |
| 清理建议：优先/观察 | 2/90 |
| 原始节点数 | 144239 |
| 去重后节点数 | 59227 |
| TCP 可达数 | 3000 |
| 真测通过数 | 88 |
| verified 输出数 | 88 |
| global 输出数 | 88 |
| all 输出数 | 59227 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 25.6 |
| fetch | 9.2 |
| generate | 30.7 |
| geo | 1.7 |
| probe | 117.9 |
| real_test | 40.7 |
| tcp | 207.0 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 2 | 0 | 100.0% |
| http | 53 | 53 | 0 | 100.0% |
| hysteria2 | 11 | 10 | 1 | 90.9% |
| shadowsocks | 122 | 101 | 21 | 82.8% |
| socks | 4 | 2 | 2 | 50.0% |
| trojan | 13 | 10 | 3 | 76.9% |
| vless | 1 | 0 | 1 | 0.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 22 |
| geo:ClientOSError | 2 |
| speed:ClientOSError | 2 |
| 204:ClientOSError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15831 |
| ConnectionRefusedError | 2245 |
| gaierror | 404 |
| OSError | 351 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 1.0 | prefer | 53 | 1.0 | 560 |
| dragon | 0.893 | prefer | 153 | 0.817 | 44753 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 5004 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 2801 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10399 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7653 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5723 |
| barry-far-vless | 0.255 | observe | 0 | None | 5902 |
| mahdibland-V2RayAggregator | 0.255 | observe | 0 | None | 4323 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| Epodonios-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| Pawdroid | 0.175 | observe | 0 | None | 0 | 8 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 507 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 398 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 393 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 276 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 254 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 253 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 245 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 223 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 218 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 142 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| dragon | 0.817 | 125 | 28 | 153 |
| ermaozi | 1.0 | 53 | 0 | 53 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 44753 | yes | 8.72 | 0 |
| mheidari-all | 34088 | yes | 6.25 | 0 |
| SoliSpirit-all | 10399 | yes | 3.81 | 0 |
| Surfboard-tg-mixed | 7653 | yes | 4.49 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.3 | 0 |
| barry-far-vless | 5902 | yes | 2.11 | 0 |
| Surfboard-tg-vless | 5723 | yes | 4.69 | 0 |
| 10ium-ScrapeCategorize-Vless | 5004 | yes | 0.58 | 0 |
| mahdibland-V2RayAggregator | 4323 | yes | 3.04 | 0 |
| MatinGhanbari-all-sub | 3999 | yes | 1.85 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 低通过率协议
| 协议 | 通过率 |
| --- | --- |
| vless | 0.0 |

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 22 |
| geo | 2 |
| speed | 2 |
| 204 | 1 |
| cn-block | 1 |
