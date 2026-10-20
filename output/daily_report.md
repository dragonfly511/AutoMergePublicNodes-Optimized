# AutoNodes 每日报告

生成时间：2026-10-20 02:52:34

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 93/107 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 4/89 |
| 原始节点数 | 94698 |
| 去重后节点数 | 26200 |
| TCP 可达数 | 3000 |
| 真测通过数 | 90 |
| verified 输出数 | 90 |
| global 输出数 | 97 |
| all 输出数 | 26200 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 29.4 |
| fetch | 7.2 |
| generate | 13.1 |
| geo | 1.5 |
| probe | 102.2 |
| real_test | 94.9 |
| tcp | 80.1 |
| write_verified | 0.1 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| http | 73 | 71 | 2 | 97.3% |
| hysteria2 | 15 | 13 | 2 | 86.7% |
| shadowsocks | 146 | 135 | 11 | 92.5% |
| socks | 5 | 2 | 3 | 40.0% |
| trojan | 64 | 57 | 7 | 89.1% |
| vless | 300 | 139 | 161 | 46.3% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| test_one_timeout:15.0s | 113 |
| speed:ClientOSError | 33 |
| geo:ClientOSError | 19 |
| cn-block:ClientOSError | 6 |
| 204:ProxyError | 4 |
| cn-block:ProxyError | 3 |
| cn-block:TimeoutError | 3 |
| 204:ClientOSError | 2 |
| 204:TimeoutError | 2 |
| geo:TimeoutError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 6468 |
| ConnectionRefusedError | 1031 |
| gaierror | 240 |
| OSError | 235 |
| SSRFBlocked | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| zhangkai | 0.956 | prefer | 20 | 1.0 | 27 |
| ermaozi-get_subscribe | 0.949 | prefer | 54 | 0.944 | 510 |
| Surfboard-tg-mixed | 0.928 | prefer | 77 | 0.857 | 6911 |
| Au1rxx-base64 | 0.818 | prefer | 228 | 0.763 | 1420 |
| mheidari-all | 0.553 | observe | 220 | 0.473 | 23317 |
| SoliSpirit-all | 0.349 | observe | 3 | 0.667 | 10158 |
| 10ium-HighSpeed | 0.345 | observe | 2 | 1.0 | 839 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4940 |
| DeltaKronecker-all | 0.255 | observe | 0 | None | 3294 |
| Epodonios-all | 0.255 | observe | 0 | None | 7516 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |
| tg-Ahmedhamoomi_Servers | 0.175 | observe | 0 | None | 0 | 2 |
| tg-BESTFORBEST66 | 0.175 | observe | 0 | None | 0 | 8 |
| tg-DarkVPNpro | 0.175 | observe | 0 | None | 0 | 7 |
| tg-GrizzlyVPN | 0.175 | observe | 0 | None | 0 | 1 |
| tg-VmessProtocol | 0.175 | observe | 0 | None | 0 | 4 |
| tg-freeiranianv2rey | 0.175 | observe | 0 | None | 0 | 12 |
| tg-freevpnconfigso | 0.175 | observe | 0 | None | 0 | 2 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 473 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 364 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 359 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 242 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 220 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 219 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 211 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 189 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 184 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 108 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| ninja-vless | 0.0 | 0 | 1 | 1 |
| mheidari-all | 0.473 | 104 | 116 | 220 |
| SoliSpirit-all | 0.667 | 2 | 1 | 3 |
| Au1rxx-base64 | 0.763 | 174 | 54 | 228 |
| Surfboard-tg-mixed | 0.857 | 66 | 11 | 77 |
| ermaozi-get_subscribe | 0.944 | 51 | 3 | 54 |
| 10ium-HighSpeed | 1.0 | 2 | 0 | 2 |
| zhangkai | 1.0 | 20 | 0 | 20 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| mheidari-all | 23317 | yes | 5.42 | 0 |
| SoliSpirit-all | 10158 | yes | 4.96 | 0 |
| Epodonios-all | 7516 | yes | 7.3 | 0 |
| Surfboard-tg-mixed | 6911 | yes | 6.53 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 1.55 | 0 |
| barry-far-vless | 5797 | yes | 0.84 | 0 |
| Surfboard-tg-vless | 5515 | yes | 6.09 | 0 |
| 10ium-ScrapeCategorize-Vless | 4940 | yes | 2.69 | 0 |
| mahdibland-V2RayAggregator | 4278 | yes | 3.19 | 0 |
| MatinGhanbari-all-sub | 3998 | yes | 0.63 | 0 |

## 趋势报警

无趋势报警。

## 健康报警

### 真测错误报警
| 错误 | 数量 |
| --- | --- |
| test_one_timeout | 113 |
| speed | 33 |
| geo | 20 |
| cn-block | 12 |
| 204 | 8 |
