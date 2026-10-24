# AutoNodes 每日报告

生成时间：2026-10-24 03:56:09

## 摘要

| 指标 | 值 |
| --- | --- |
| 健康状态 | warning |
| 健康检查通过 | True |
| 健康源数量 | 87/108 |
| 清理建议：禁用/降权 | 14/0 |
| 清理建议：优先/观察 | 1/93 |
| 原始节点数 | 138168 |
| 去重后节点数 | 58569 |
| TCP 可达数 | 3000 |
| 真测通过数 | 82 |
| verified 输出数 | 82 |
| global 输出数 | 83 |
| all 输出数 | 58569 |
| all 输出模式 | full |

## 阶段耗时

| 阶段 | 秒 |
| --- | --- |
| china_check | 31.7 |
| fetch | 9.3 |
| generate | 29.9 |
| geo | 1.7 |
| probe | 133.3 |
| real_test | 41.1 |
| tcp | 191.8 |
| write_verified | 0.0 |

## 协议通过率

| 协议 | 已测 | 通过 | 失败 | 通过率 |
| --- | --- | --- | --- | --- |
| anytls | 2 | 1 | 1 | 50.0% |
| http | 82 | 42 | 40 | 51.2% |
| hysteria2 | 17 | 15 | 2 | 88.2% |
| shadowsocks | 153 | 133 | 20 | 86.9% |
| socks | 5 | 3 | 2 | 60.0% |
| trojan | 15 | 11 | 4 | 73.3% |
| vless | 1 | 0 | 1 | 0.0% |
| vmess | 2 | 2 | 0 | 100.0% |

## 主要真测错误

| 错误 | 数量 |
| --- | --- |
| 204:ProxyError | 37 |
| test_one_timeout:15.0s | 21 |
| 204:TimeoutError | 5 |
| speed:ClientOSError | 3 |
| cn-block:ClientOSError | 2 |
| sing-box exited 1: [31mFATAL[0m[0000] start service: start inbound: start inbound/socks[socks-in]: listen tcp 127.0.0.1:46399: bind: address already in use | 1 |
| 204:ClientOSError | 1 |

## TCP 预筛选错误

| 错误 | 数量 |
| --- | --- |
| TimeoutError | 15059 |
| ConnectionRefusedError | 2504 |
| gaierror | 726 |
| OSError | 324 |
| SSRFBlocked | 5 |
| ConnectionResetError | 2 |

## 高评分订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 解析数 |
| --- | --- | --- | --- | --- | --- |
| dragon | 0.926 | prefer | 193 | 0.85 | 45691 |
| ermaozi | 0.524 | observe | 80 | 0.5 | 608 |
| tg-oneclickvpnkeys | 0.315 | observe | 2 | 1.0 | 92 |
| mheidari-all | 0.287 | observe | 2 | 0.5 | 23800 |
| 10ium-ScrapeCategorize-Vless | 0.255 | observe | 0 | None | 4911 |
| Epodonios-all | 0.255 | observe | 0 | None | 7650 |
| MatinGhanbari-all-sub | 0.255 | observe | 0 | None | 3998 |
| SoliSpirit-all | 0.255 | observe | 0 | None | 10227 |
| Surfboard-tg-mixed | 0.255 | observe | 0 | None | 7159 |
| Surfboard-tg-vless | 0.255 | observe | 0 | None | 5520 |

## 需关注订阅源

| 订阅源 | 评分 | 建议 | 已测 | 通过率 | 连续死亡 | 解析数 |
| --- | --- | --- | --- | --- | --- | --- |
| Barabama-we | 0.025 | observe | 0 | None | 1 | 0 |
| Barabama-yudou | 0.025 | observe | 0 | None | 1 | 0 |
| DeltaKronecker-all | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-nodefree | 0.025 | observe | 0 | None | 1 | 0 |
| barabama-yudou66 | 0.025 | observe | 0 | None | 1 | 0 |
| tg-ViProxys | 0.025 | observe | 0 | None | 1 | 0 |
| tg-proxy_kafee | 0.025 | observe | 0 | None | 1 | 0 |
| Mr8AHAL | 0.175 | observe | 0 | None | 0 | 1 |
| ninja-hy2 | 0.175 | observe | 0 | None | 0 | 3 |
| ninja-tuic | 0.175 | observe | 0 | None | 0 | 1 |

## 订阅源清理建议

| 分类 | 订阅源 | 评分 | 已测 | 通过率 | 连续死亡 | 原因 |
| --- | --- | --- | --- | --- | --- | --- |
| disable | tg-V2rayngVpn | 0.0 | 0 | None | 489 | 连续死亡次数 >= 2 |
| disable | tg-Letiranbreath | 0.0 | 0 | None | 380 | 连续死亡次数 >= 2 |
| disable | snakem982 | 0.0 | 0 | None | 375 | 连续死亡次数 >= 2 |
| disable | tg-ernoxin_shop | 0.0 | 0 | None | 258 | 连续死亡次数 >= 2 |
| disable | abc-configs-readme-latest30 | 0.0 | 0 | None | 236 | 连续死亡次数 >= 2 |
| disable | tg-abc_configs | 0.0 | 0 | None | 235 | 连续死亡次数 >= 2 |
| disable | tg-Parsashonam | 0.0 | 0 | None | 227 | 连续死亡次数 >= 2 |
| disable | nscl5-all | 0.0 | 0 | None | 205 | 连续死亡次数 >= 2 |
| disable | mfuu-v2ray | 0.0 | 0 | None | 200 | 连续死亡次数 >= 2 |
| disable | tg-CaV2ray | 0.0 | 0 | None | 124 | 连续死亡次数 >= 2 |

## 真测通过率较低的订阅源

| 订阅源 | 通过率 | 通过 | 失败 | 已测 |
| --- | --- | --- | --- | --- |
| mheidari-all | 0.5 | 1 | 1 | 2 |
| ermaozi | 0.5 | 40 | 40 | 80 |
| dragon | 0.85 | 164 | 29 | 193 |
| tg-oneclickvpnkeys | 1.0 | 2 | 0 | 2 |

## 解析节点数较高的订阅源

| 订阅源 | 节点数 | 是否正常 | 耗时 | 连续死亡 |
| --- | --- | --- | --- | --- |
| dragon | 45691 | yes | 8.01 | 0 |
| mheidari-all | 23800 | yes | 6.27 | 0 |
| SoliSpirit-all | 10227 | yes | 3.52 | 0 |
| Epodonios-all | 7650 | yes | 8.26 | 0 |
| Surfboard-tg-mixed | 7159 | yes | 4.21 | 0 |
| xiaoji235-airport-v2ray-all | 6752 | yes | 2.33 | 0 |
| barry-far-vless | 5734 | yes | 1.17 | 0 |
| Surfboard-tg-vless | 5520 | yes | 3.67 | 0 |
| 10ium-ScrapeCategorize-Vless | 4911 | yes | 2.52 | 0 |
| mahdibland-V2RayAggregator | 4117 | yes | 0.4 | 0 |

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
| 204 | 43 |
| test_one_timeout | 21 |
| speed | 3 |
| cn-block | 2 |
| sing-box exited 1 | 1 |
