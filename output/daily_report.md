# AutoNodes 每日报告

生成时间：2026-10-25 15:54:10

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 89/108 |
| 清理建议：禁用/降权 | 15/0 |
| 清理建议：优先/观察 | 2/91 |
| 原始节点数 | 144083 |
| 去重后节点数 | 60371 |
| TCP 可达数 | 3000 |
| 真测通过数 | 63 |
| verified 输出数 | 63 |
| global 输出数 | 63 |
| all 输出数 | 60371 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 24.9 |
| fetch | 9.0 |
| generate | 30.6 |
| geo | 1.8 |
| probe | 128.5 |
| real_test | 41.0 |
| tcp | 216.9 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 1 | 1 | 0 | 100.0% |
| http | 62 | 46 | 16 | 74.2% |
| hysteria2 | 13 | 11 | 2 | 84.6% |
| shadowsocks | 136 | 122 | 14 | 89.7% |
| socks | 7 | 3 | 4 | 42.9% |
| trojan | 7 | 5 | 2 | 71.4% |
| vmess | 1 | 1 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 16 |
| 204:ProxyError | 11 |
| 204:ClientOSError | 5 |
| cn-block:ProxyError | 2 |
| geo:ProxyError | 1 |
| speed:ProxyError | 1 |
| 204:TimeoutError | 1 |
| cn-block:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 16609 |
| ConnectionRefusedError | 2457 |
| OSError | 317 |
| gaierror | 263 |
| ConnectionResetError | 1 |
| SSRFBlocked | 1 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.941 | prefer | 163 | 0.865 | 46036 |
| ermaozi | 0.757 | prefer | 62 | 0.742 | 575 |
| Au1rxx-base64 | 0.378 | observe | 2 | 1.0 | 1658 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4912 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3849 |
| Epodonios-all | 0.255 | observe | 0 | None | 7729 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3997 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10617 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7560 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5715 |

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
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 495 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 386 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 381 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 264 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 242 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 241 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 233 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 211 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 206 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 130 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ermaozi | 0.742 | 46 | 16 | 62 |
| dragon | 0.865 | 141 | 22 | 163 |
| Au1rxx-base64 | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 46036 | yes | 8.25 | 0 |
| mheidari-all | 24301 | yes | 4.91 | 0 |
| SoliSpirit-all | 10617 | yes | 4.66 | 0 |
| Epodonios-all | 7729 | yes | 3.07 | 0 |
| Surfboard-tg-mixed | 7560 | yes | 4.0 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 3.94 | 0 |
| Surfboard-tg-vless | 5715 | yes | 5.94 | 0 |
| barry-far-vless | 5694 | yes | 2.05 | 0 |
| 10ium-ScrapeCategorize-Vless | 4912 | yes | 2.57 | 0 |
| mahdibland-V2RayAggregator | 4186 | yes | 1.74 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| 204 | 17 |
| test_one_timeout | 16 |
| cn-block | 3 |
| geo | 1 |
| speed | 1 |
