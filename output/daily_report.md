# AutoNodes 每日报告

生成时间：2026-10-24 20:33:32

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 2/92 |
| 原始节点数 | 143049 |
| 去重后节点数 | 59962 |
| TCP 可达数 | 3000 |
| 真测通过数 | 45 |
| verified 输出数 | 45 |
| global 输出数 | 46 |
| all 输出数 | 59962 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 23.1 |
| fetch | 5.4 |
| generate | 19.2 |
| geo | 1.5 |
| probe | 112.7 |
| real_test | 35.8 |
| tcp | 203.5 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 24 | 24 | 0 | 100.0% |
| hysteria2 | 16 | 11 | 5 | 68.8% |
| shadowsocks | 143 | 128 | 15 | 89.5% |
| socks | 8 | 3 | 5 | 37.5% |
| trojan | 9 | 5 | 4 | 55.6% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 20 |
| 204:ClientOSError | 3 |
| 204:ProxyError | 2 |
| cn-block:ClientOSError | 2 |
| 204:TimeoutError | 1 |
| cn-block:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15662 |
| ConnectionRefusedError | 2483 |
| gaierror | 501 |
| OSError | 321 |
| SSRFBlocked | 4 |
| ConnectionResetError | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| ermaozi | 0.983 | prefer | 23 | 1.0 | 567 |
| dragon | 0.918 | prefer | 177 | 0.842 | 46036 |
| mheidari-all | 0.335 | observe | 1 | 1.0 | 24512 |
| tg-oneclickvpnkeys | 0.259 | observe | 1 | 1.0 | 107 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4911 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3780 |
| Epodonios-all | 0.255 | observe | 0 | None | 7708 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3999 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10157 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5485 |

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
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 492 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 383 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 378 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 261 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 239 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 238 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 230 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 208 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 203 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 127 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| Surfboard-tg-mixed | 0.0 | 0 | 1 | 1 |
| dragon | 0.842 | 149 | 28 | 177 |
| mheidari-all | 1.0 | 1 | 0 | 1 |
| tg-oneclickvpnkeys | 1.0 | 1 | 0 | 1 |
| ermaozi | 1.0 | 23 | 0 | 23 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 46036 | yes | 5.05 | 0 |
| mheidari-all | 24512 | yes | 3.82 | 0 |
| SoliSpirit-all | 10157 | yes | 2.43 | 0 |
| Epodonios-all | 7708 | yes | 3.15 | 0 |
| Surfboard-tg-mixed | 7114 | yes | 2.11 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 0.98 | 0 |
| barry-far-vless | 5771 | yes | 1.55 | 0 |
| Surfboard-tg-vless | 5485 | yes | 2.29 | 0 |
| 10ium-ScrapeCategorize-Vless | 4911 | yes | 1.47 | 0 |
| mahdibland-V2RayAggregator | 4150 | yes | 0.09 | 0 |

## 趋势报警

| 类型 | 信息 |
| --- | --- |
| verified_downtrend_4_runs | verified output decreased for 4 consecutive runs |

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 20 |
| 204 | 6 |
| cn-block | 3 |
