# DMIT 套餐怎么选：Premium、Eyeball、Tier 1 差在哪，AN4 和 AN5 值不值多花 30%？（附洛杉矶全套餐价格表与退款、换 IP 规则）

DMIT 套餐怎么选，三个档位就能覆盖大多数人的情况：预算优先看 Tier 1，国内访问优先看 Premium，流量吃得多而线路可以退一步看 Eyeball。落到具体型号：

- **预算优先**：Tier 1 VOLUME V2C2G，2 核 2GB / 40GB / 5000GB 流量，$14.90/月，不含中国大陆优化。
- **国内访问优先**：Premium AN4 TINY，1 核 2GB / 20GB / 1000GB / 1Gbps，$88.88/年，三网回程走 CN2 GIA。
- **要流量不要顶级线路**：Eyeball AN4 TINY，同样 $88.88/年，配置与 Premium TINY 一致，流量 1500GB、带宽 2Gbps。

真正让人卡住的通常是另外两个问题：Premium 和 Eyeball 价格完全一样，凭什么选；AN4 和 AN5 差三成，多出来的钱换到了什么。这两件事下面单独拆。洛杉矶全部 38 个套餐的价格表在后面，想先看数字可以直接往下翻。

> **选购速览**：国内访问为主的个人节点和中小站点，Premium AN4 TINY（$88.88/年）够用；每月流量超过 1TB 就换 Eyeball AN4 TINY，同价、流量 1.5 倍、带宽翻倍；受众在海外、只要一台稳定的美国机器，Tier 1 V2C2G（$14.90/月）最省钱。
> 👉 [查看 Premium AN4 TINY 年付 $88.88 的当前库存与购买入口](https://www.dmit.io/aff.php?aff=9081&pid=237)

## 洛杉矶全套餐价格表

下面六张表按系列拆开，价格整理自官方定价页，热门档位补货后库存会变，下单页显示的金额和周期才是最终结果。全部机器为 KVM 完全虚拟化，可以自定义内核、开 BBR、装 Docker。

### Premium（LAX.Pro · CN2 GIA · AN4 平台）

| 套餐 | 配置 | 流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| TINY | 1 核 2GB / 20GB | 1000GB / 1Gbps | $88.88/年 | [选 TINY](https://www.dmit.io/aff.php?aff=9081&pid=237) |
| Pocket | 2 核 2GB / 40GB | 1500GB / 4Gbps | $159.98/年 | [选 Pocket](https://www.dmit.io/aff.php?aff=9081&pid=238) |
| STARTER | 2 核 2GB / 80GB | 3000GB / 10Gbps | $29.90/月 | [选 STARTER](https://www.dmit.io/aff.php?aff=9081&pid=239) |
| MINI | 4 核 4GB / 80GB | 5000GB / 10Gbps | $58.88/月 | [选 MINI](https://www.dmit.io/aff.php?aff=9081&pid=240) |
| MICRO | 4 核 4GB / 160GB | 7000GB / 10Gbps | $74.99/月 | [选 MICRO](https://www.dmit.io/aff.php?aff=9081&pid=241) |
| MEDIUM | 6 核 8GB / 160GB | 15000GB / 10Gbps | $168.88/月 | [选 MEDIUM](https://www.dmit.io/aff.php?aff=9081&pid=242) |
| LARGE | 8 核 16GB / 320GB | 25000GB / 10Gbps | $338.88/月 | [选 LARGE](https://www.dmit.io/aff.php?aff=9081&pid=243) |
| GIANT | 12 核 24GB / 640GB | 50000GB / 10Gbps | $619.99/月 | [选 GIANT](https://www.dmit.io/aff.php?aff=9081&pid=244) |

### Premium（AN5 平台 · EPYC 9005 · CN2 GIA）

| 套餐 | 配置 | 流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| TINY | 1 核 2GB / 20GB | 1000GB / 1Gbps | $119.99/年 | [选 TINY](https://www.dmit.io/aff.php?aff=9081&pid=100) |
| Pocket | 2 核 2GB / 40GB | 1500GB / 4Gbps | $203.90/年 | [选 Pocket](https://www.dmit.io/aff.php?aff=9081&pid=137) |
| STARTER | 2 核 2GB / 80GB | 3000GB / 10Gbps | $38.90/月 | [选 STARTER](https://www.dmit.io/aff.php?aff=9081&pid=56) |
| MINI | 4 核 4GB / 80GB | 5000GB / 10Gbps | $76.90/月 | [选 MINI](https://www.dmit.io/aff.php?aff=9081&pid=58) |
| MICRO | 4 核 4GB / 160GB | 7000GB / 10Gbps | $99.90/月 | [选 MICRO](https://www.dmit.io/aff.php?aff=9081&pid=81) |
| MEDIUM | 6 核 8GB / 160GB | 15000GB / 10Gbps | $219.90/月 | [选 MEDIUM](https://www.dmit.io/aff.php?aff=9081&pid=82) |
| GIANT | 12 核 24GB / 640GB | 50000GB / 10Gbps | $839.90/月 | [选 GIANT](https://www.dmit.io/aff.php?aff=9081&pid=98) |

AN5 的 Premium 没有 LARGE 档，8 核 16GB 这一级直接跳到 GIANT。

### Eyeball（LAX.EB · AS9929 + CMIN2 · AN4 平台）

| 套餐 | 配置 | 流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| TINY | 1 核 2GB / 20GB | 1500GB / 2Gbps | $88.88/年 | [选 TINY](https://www.dmit.io/aff.php?aff=9081&pid=245) |
| Pocket | 2 核 2GB / 40GB | 3000GB / 4Gbps | $159.98/年 | [选 Pocket](https://www.dmit.io/aff.php?aff=9081&pid=246) |
| STARTER | 2 核 2GB / 80GB | 5000GB / 10Gbps | $29.90/月 | [选 STARTER](https://www.dmit.io/aff.php?aff=9081&pid=247) |
| MINI | 4 核 4GB / 80GB | 10000GB / 10Gbps | $58.88/月 | [选 MINI](https://www.dmit.io/aff.php?aff=9081&pid=248) |
| MICRO | 4 核 4GB / 160GB | 14000GB / 10Gbps | $74.99/月 | [选 MICRO](https://www.dmit.io/aff.php?aff=9081&pid=249) |
| MEDIUM | 6 核 8GB / 160GB | 30000GB / 10Gbps | $168.88/月 | [选 MEDIUM](https://www.dmit.io/aff.php?aff=9081&pid=250) |
| LARGE | 8 核 16GB / 320GB | 50000GB / 10Gbps | $338.88/月 | [选 LARGE](https://www.dmit.io/aff.php?aff=9081&pid=251) |
| GIANT | 12 核 24GB / 640GB | 100000GB / 10Gbps | $619.99/月 | [选 GIANT](https://www.dmit.io/aff.php?aff=9081&pid=252) |

### Eyeball（AN5 平台 · EPYC 9005）

| 套餐 | 配置 | 流量 / 带宽 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| TINY | 1 核 2GB / 20GB | 1500GB / 2Gbps | $119.99/年 | [选 TINY](https://www.dmit.io/aff.php?aff=9081&pid=189) |
| Pocket | 2 核 2GB / 40GB | 3000GB / 4Gbps | $203.90/年 | [选 Pocket](https://www.dmit.io/aff.php?aff=9081&pid=190) |
| STARTER | 2 核 2GB / 80GB | 5000GB / 10Gbps | $38.90/月 | [选 STARTER](https://www.dmit.io/aff.php?aff=9081&pid=191) |
| MINI | 4 核 4GB / 80GB | 10000GB / 10Gbps | $76.90/月 | [选 MINI](https://www.dmit.io/aff.php?aff=9081&pid=192) |
| MICRO | 4 核 4GB / 160GB | 14000GB / 10Gbps | $99.90/月 | [选 MICRO](https://www.dmit.io/aff.php?aff=9081&pid=193) |
| MEDIUM | 6 核 8GB / 160GB | 30000GB / 10Gbps | $219.90/月 | [选 MEDIUM](https://www.dmit.io/aff.php?aff=9081&pid=194) |
| GIANT | 12 核 24GB / 640GB | 100000GB / 10Gbps | $839.90/月 | [选 GIANT](https://www.dmit.io/aff.php?aff=9081&pid=196) |

### Tier 1 VOLUME（AN5 · 国际线路）

| 套餐 | 配置 | 流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| V2C2G | 2 核 2GB / 40GB | 5000GB | $14.90/月 | [选 V2C2G](https://www.dmit.io/aff.php?aff=9081&pid=169) |
| V2C4G | 2 核 4GB / 80GB | 10000GB | $23.90/月 | [选 V2C4G](https://www.dmit.io/aff.php?aff=9081&pid=170) |
| V4C4G | 4 核 4GB / 120GB | 20000GB | $36.90/月 | [选 V4C4G](https://www.dmit.io/aff.php?aff=9081&pid=171) |
| V4C8G | 4 核 8GB / 160GB | 40000GB | $52.90/月 | [选 V4C8G](https://www.dmit.io/aff.php?aff=9081&pid=180) |
| V8C16G | 8 核 16GB / 240GB | 80000GB | $119.90/月 | [选 V8C16G](https://www.dmit.io/aff.php?aff=9081&pid=172) |
| V12C24G | 12 核 24GB / 320GB | 160000GB | $199.90/月 | [选 V12C24G](https://www.dmit.io/aff.php?aff=9081&pid=173) |

### Tier 1 GENERAL（AN4 · 国际线路）

| 套餐 | 配置 | 流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- |
| G2C4G | 2 核 4GB / 80GB | 4000GB | $16.90/月 | [选 G2C4G](https://www.dmit.io/aff.php?aff=9081&pid=234) |
| G4C8G | 4 核 8GB / 160GB | 8000GB | $36.90/月 | [选 G4C8G](https://www.dmit.io/aff.php?aff=9081&pid=235) |

社区里经常被提到的 Tier 1 WEE（1 核 1GB / 1000GB，$36.90/年）不在上表里。它属于限量款，官方定价页目前的 Tier 1 常规档位从 V2C2G 起。2026 年 9 月有测评频道报道洛杉矶 AS3 平台补过一批货，同批还有月付 $10.90 的 Premium TINY，配的是 EPYC 7003。这类限量款上架没有固定节奏，看到有货再决定，别规划成随时能买。

## 三条产品线到底差在哪

线路不一样，其他都好说。

**Premium（LAX.Pro）** 三网回程全部走 CN2 GIA。电信的 CN2 GIA 是 AS4809，属于电信面向企业的精品承载网，晚高峰普通 163 骨干拥堵时它基本不受影响。这条线是 DMIT 卖得最贵的原因。

**Eyeball（LAX.EB）** 电信和联通走 AS9929，移动走 CMIN2（AS58807）回程。AS9929 是联通的精品网，CMIN2 是移动的精品网，两条都是各自运营商的高优先级通道，只是没有做到三网全 CN2 GIA。路由细节官方会调整，下单前建议看一眼官网的产品说明。

**Tier 1（LAX.T1）** 接的是国际 Tier 1 运营商，对中国大陆没有专项优化。国内访问延迟比前两个系列高，丢包在晚高峰更明显。它的价值在别处：价格最低，流量给得厚，超量之后限速继续跑而不是停机。

按人群分：站点或服务主要给国内用户看，Premium 的溢价花得值；自己一个人用、跑跑脚本、偶尔传大文件，Eyeball 的线路够；受众在海外或者只是要一台美国机器做落地，Tier 1 最划算。

## 同价不同货：Premium 和 Eyeball 一个价，流量差一倍

这是 DMIT 定价里最容易被忽略的一处。AN4 平台上，Premium 和 Eyeball 的八个档位价格完全一致，但配置单上的流量和带宽不是一回事。

| 档位 | 相同价格 | Premium 流量 / 带宽 | Eyeball 流量 / 带宽 |
| --- | --- | --- | --- |
| TINY | $88.88/年 | 1000GB / 1Gbps | 1500GB / 2Gbps |
| Pocket | $159.98/年 | 1500GB / 4Gbps | 3000GB / 4Gbps |
| STARTER | $29.90/月 | 3000GB / 10Gbps | 5000GB / 10Gbps |
| MINI | $58.88/月 | 5000GB / 10Gbps | 10000GB / 10Gbps |
| MICRO | $74.99/月 | 7000GB / 10Gbps | 14000GB / 10Gbps |
| MEDIUM | $168.88/月 | 15000GB / 10Gbps | 30000GB / 10Gbps |
| LARGE | $338.88/月 | 25000GB / 10Gbps | 50000GB / 10Gbps |
| GIANT | $619.99/月 | 50000GB / 10Gbps | 100000GB / 10Gbps |

同一笔钱，买 Premium 等于用一半流量换三网 CN2 GIA，买 Eyeball 等于把线路降一档、流量翻倍。TINY 这一档还多一个带宽差别，1Gbps 对 2Gbps。

判断规则可以写得很直白：

- 每月实际跑不到 800GB，且不能接受晚高峰抖动，选 Premium。省下的流量额度对你没意义，线路稳定性才是你在买的东西。
- 每月流量在 1TB 以上，或者要跑备份、同步、图床、下载中转，选 Eyeball。同一个价格多一倍流量，线路差的那一点在非高峰时段几乎感知不到。
- 主力用户是移动宽带，Eyeball 回程走 CMIN2，这本身就是移动的精品网，和 Premium 的实际差距比电信、联通用户小。

如果拿不准自己的流量水平，先按低一档买，跑一个月看面板统计再决定要不要换。升级可以直接操作，降级得重新下单。

👉 [用 $88.88/年 开通 Eyeball TINY，1500GB 流量 + 2Gbps 带宽](https://www.dmit.io/aff.php?aff=9081&pid=245)

## AN4 和 AN5 差 30% 左右，只换了 CPU

两个平台的配置单几乎一模一样，内存、硬盘、流量、带宽都不变，变的只有处理器：AN4 是 EPYC 9004，AN5 是 EPYC 9005。社区整理的跑分对比里，AN5 单核提升约 50%，多核提升更多，具体数字以实际测试为准。

价格差多少，逐档列出来：

| 档位 | AN4 | AN5 | 差额 | 溢价 |
| --- | --- | --- | --- | --- |
| TINY（年付） | $88.88 | $119.99 | +$31.11 | 约 35% |
| Pocket（年付） | $159.98 | $203.90 | +$43.92 | 约 27% |
| STARTER（月付） | $29.90 | $38.90 | +$9.00 | 约 30% |
| MINI（月付） | $58.88 | $76.90 | +$18.02 | 约 31% |
| MICRO（月付） | $74.99 | $99.90 | +$24.91 | 约 33% |
| MEDIUM（月付） | $168.88 | $219.90 | +$51.02 | 约 30% |
| GIANT（月付） | $619.99 | $839.90 | +$219.91 | 约 35% |

这笔钱该不该花，看你让机器干什么。静态站点、反向代理、代理落地、轻量 API，CPU 大部分时间闲着，AN4 完全够，多花的 30% 换不来任何可感知的差别。编译代码、视频转码、跑数据库、同时开一堆容器、做爬虫或数据处理，CPU 是瓶颈，AN5 的代际提升才兑现得出来。

年付档位差价绝对值不大，TINY 一年多 $31.11；月付高档位差价就是实打实的月支出，GIANT 一档每月多 $219.91，选之前想清楚负载到底吃不吃 CPU。

## 香港和东京：延迟更低，价格另算

洛杉矶到国内主要城市 150–180ms，这个数字在美西机房里算正常。要把延迟压到几十毫秒，只能换机房。香港 Premium 走 CN2 GIA + AS9929 + CMI，实测延迟可以到 30ms 上下；东京 Premium 同样是三网优化线路。

代价在价格上。香港 Premium 入门档 1 核 1GB 就要 $39.9/月上下，是洛杉矶 Premium TINY 年付价的好几倍。东京 Premium 入门约 $21.9/月，比香港便宜，比洛杉矶贵。

香港和东京的套餐变动比洛杉矶频繁，下面这组数字来自单一渠道的整理，只作价格量级参考，实际配置和库存以官网实时显示为准。东京的 Eyeball 系列已经下架，目前只剩 Premium 和 Tier 1。

| 系列 / 套餐 | 配置 | 线路 | 参考价 | 购买 |
| --- | --- | --- | --- | --- |
| 香港 Premium TINY | 1 核 1GB / 1Gbps@500GB | CN2 GIA + AS9929 + CMI | 约 $39.9/月 | [看香港在售档位](https://www.dmit.io/aff.php?aff=9081) |
| 香港 Premium VICTORIA | 1 核 2GB / 500Mbps@800GB | CN2 GIA 直连 | $298.88/年 | [看香港在售档位](https://www.dmit.io/aff.php?aff=9081) |
| 香港 Eyeball 常规 | 1 核 1GB / 1Gbps | CMI 回程 | 约 $16/月 | [看香港在售档位](https://www.dmit.io/aff.php?aff=9081) |
| 香港 Tier 1 WEE | 1 核 1GB / 10Gbps@1000GB | 国际线路 | $36.9/年 | [看香港在售档位](https://www.dmit.io/aff.php?aff=9081) |
| 东京 Premium TINY | 1 核 1GB / 1Gbps@500GB | CN2 GIA + AS9929 + CMI | 约 $21.9/月 | [看东京在售档位](https://www.dmit.io/aff.php?aff=9081) |
| 东京 Premium STARTER | 1 核 2GB / 1Gbps@1000GB | CN2 GIA + AS9929 + CMI | 约 $32.9/月 | [看东京在售档位](https://www.dmit.io/aff.php?aff=9081) |

什么情况下值得上香港：用户全在国内，对首屏时间有硬要求，业务本身能承担每月几十美元的成本。只是自己搭个节点翻墙看视频，洛杉矶 Premium 的年付价能省下十倍开支，150ms 和 30ms 的差别在流媒体场景里没那么致命。

## 下单前必须知道的四个坑

**默认密钥登录，没有密码。** DMIT 不开密码登录，开机后要在控制面板生成密钥对或上传公钥，再用 PuTTY、Xshell 或者系统自带终端连。没碰过 Linux 的人容易卡在这一步，官方有中文教程，照着做十分钟能通。买之前先确认自己手上有一个 SSH 客户端。

**IP 被墙有换 IP 机制。** 每 15 天可以免费换一次 IP，超出频率每次 $5。月付套餐要求剩余有效期大于 15 天才能操作。购买时可以勾选 IP Guarantee+，新开机如果 IP 已经被封，可以免费换一次。这项对拿机器做代理的人影响最大，买之前心里要有数。

**超流量是限速，不是停机。** 洛杉矶 Tier 1 超量后限速到 100Mbps，香港和东京的 Tier 1 限速到 50Mbps。100Mbps 跑个 SSH、轻量站点、日常同步完全撑得住，撑到下个计费周期没问题。这一点比直接断线友好，也是 Tier 1 大流量款值得买的原因之一。

**不超售，所以经常缺货。** DMIT 明确不超售，卖完就等下一批，热门年付款和香港 Premium、洛杉矶 Premium 的部分规格常年缺货，补货没有固定时间表。想买特定型号，关注官方 Telegram 的补货通知比反复刷官网省事。买到之后如果不合适，3 天内且流量使用不超过 30GB 可以全额退款，会扣支付手续费；30 天内按剩余价值退款，退回账户余额免手续费，退回原支付渠道可能产生手续费。

关于稳定性，中文博客作者 P3TERX 公开提到自己有两个业务网站放在 DMIT，评价是「性能高、稳定性一流」。这是一条第三方公开评价，不是官方宣传语，可以当作参考。

👉 [先开一台 Premium AN4 STARTER 月付 $29.90，3 天内不满意可全额退](https://www.dmit.io/aff.php?aff=9081&pid=239)

## 按场景对号入座

| 使用场景 | 推荐档位 | 价格 |
| --- | --- | --- |
| 个人节点，1–2 人用，流量 1TB 以内 | Premium AN4 TINY | $88.88/年 |
| 个人节点，多设备或常看高清 | Eyeball AN4 TINY | $88.88/年 |
| 面向国内受众的站点 | Premium AN4 STARTER / MINI | $29.90 / $58.88 每月 |
| 面向海外受众的站点 | Tier 1 VOLUME V2C2G | $14.90/月 |
| 多人共用、跑 Docker、多个小站 | Premium AN4 MINI（4 核 4GB） | $58.88/月 |
| 大流量但线路要求不高 | Tier 1 VOLUME V4C4G（20TB） | $36.90/月 |
| 计算密集任务 | Premium AN5 STARTER | $38.90/月 |
| 必须低延迟的国内业务 | 香港 Premium | 约 $39.9/月起 |

## 常见问题

**续费会不会涨价？** 本文列的是官网当前标价，续费按官网当期价格结算。下单页会写明计费周期和扣款金额，确认那一步的数字最准。

**能解锁 Netflix 吗？** 洛杉矶是美元原生 IP，社区反馈通常能解锁 Netflix 美区，也有人测过 TikTok。DMIT 官方不以流媒体解锁为卖点，IP 封锁名单会变，买之前用测试 IP 154.17.12.22 自己 ping 一下、跑个解锁脚本更稳妥。

**缺货了怎么办？** 关注官方 Telegram 的补货通知，补货量通常不大。急用的话退一档，比如 Premium TINY 没货就先拿 Eyeball TINY，配置一样、线路差一档，价格相同。

**能升级或降级吗？** 升级可以在面板直接操作，补差价即可。降级要重新购买，所以第一次别直接上年付高档位，先用月付跑一段时间。

**和搬瓦工比怎么样？** 两家都做 CN2 GIA 线路。搬瓦工同类 CN2 GIA 套餐的流量通常给得更多，价格相对亲民；DMIT 的差异在不超售和自有线路，机器上承诺的核数和带宽就是实际分到的资源。预算紧、流量需求大，搬瓦工更合适；在意晚高峰稳定性和资源不缩水，DMIT 值这个价。

**付款和客服呢？** 支持支付宝、PayPal、信用卡。工单系统有中文支持，一般 24 小时内回复，但不提供托管服务，机器上的软件配置得自己来。

## 最后三条规则

只要一台能用的洛杉矶机器，不需要国内优化：Tier 1 V2C2G，$14.90/月，2 核 2GB 配 5000GB 流量，超量限速 100Mbps 不断线。

国内访问是刚需，流量不大：Premium AN4 TINY，$88.88/年，三网回程 CN2 GIA。流量超过 1TB/月就换成同价的 Eyeball AN4 TINY，流量 1500GB、带宽 2Gbps。

CPU 是你的瓶颈：再考虑 AN5，溢价 27%–35%，只在编译、转码、数据库、多容器这类负载上兑现。

下单前确认两件事。注册时关掉代理、用真实网络、信息尽量填真实，风控判定信息异常会直接退款。付款页核对一遍计费周期和金额，年付套餐的显示金额是全年总价，不是月费。

👉 [打开 DMIT 洛杉矶全部套餐页面，按库存和价格下单](https://www.dmit.io/aff.php?aff=9081)
