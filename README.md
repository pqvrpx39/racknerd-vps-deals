# RackNerd便宜VPS：$11.29/年起的年付特价全对比，续费不涨价，按用途选对配置

RackNerd 的便宜 VPS 属于少数经得起推敲的那种：入门 KVM 套餐年付 $11.29，折合每月不到一美元，续费按同一价格走。很多人不敢碰低价 VPS，担心的无非三件事——首年低价第二年翻倍、超售到没法用、商家说没就没。这三件事在 RackNerd 身上恰好都有明确答案，下面把当前在售的价格、选择逻辑和几个容易踩的细节一次说清。

> **选购速览**：只跑 VPN、机器人、监控这类单一任务，选 1 GB 套餐（**$11.29/年**）就够了；要开网站、挂容器或服务多个用户，直接上 3.5 GB（2 核 CPU、7 TB 月流量，$32.49/年），这也是卖得最多的一档。所有年付特价续费同价。👉 [查看 RackNerd 当前年付特价](https://bit.ly/my-rn)

## RackNerd 便宜 VPS 是真便宜，还是首年套路？

判断标准看续费价：当前主推的年付特价续费按原价续，没有“第一年给甜头、第二年找回来”的操作。作为参照，同样 1 GB 内存的入门机型在 DigitalOcean 大约要 $72/年，这里是 $11.29，差出六倍多。

便宜的原因不神秘。RackNerd 自己持有硬件，不当地转售商，利润率压得薄，规模上来后单台成本还在往下走。公司 2019 年成立，CEO Dustin Cisneros 会直接在 LowEndTalk 这类论坛回帖；2024、2025 连续两年进入 Inc. 5000，2026 年第三次登上 Inc. Regionals Pacific 榜单。对一家年付十几美元的商家，这类稳定性信号比跑分更有参考价值。

每档套餐的底层配置一致：KVM 全虚拟化（分配的内存归你独享，可以跑 Docker）、RAID-10 SSD（既做条带又做镜像，坏一块盘数据不丢）、1Gbps 端口、1 个独立 IPv4、完整 root 权限、SolusVM 面板和 DDoS 防护。付款后多数情况下 60 秒内自动开通。

想先花最小的成本试水，入门档是全场风险最低的选择：👉 [用 $11.29/年开通 1 GB 套餐](https://my.racknerd.com/cart.php?a=add&pid=903&aff=16470)

## 当前在售的年付特价：配置与价格全表

目前主推的新年促销档年付 KVM 特价共 5 档，从 $11.29/年到 $59.99/年，全部续费同价。价格均为美元，年付一次性支付。

| 套餐 | CPU / 内存 | SSD 存储 | 月流量 | 年付价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| 1 GB | 1 vCPU / 1 GB | 24 GB | 2 TB | $11.29/年 | [ 开通 1 GB](https://my.racknerd.com/cart.php?a=add&pid=903&aff=16470) |
| 2 GB | 1 vCPU / 2 GB | 40 GB | 3.5 TB | $18.29/年 | [ 开通 2 GB](https://my.racknerd.com/cart.php?a=add&pid=904&aff=16470) |
| 3.5 GB（最热门） | 2 vCPU / 3.5 GB | 65 GB | 7 TB | $32.49/年 | [ 开通 3.5 GB](https://my.racknerd.com/cart.php?a=add&pid=905&aff=16470) |
| 4 GB | 3 vCPU / 4 GB | 105 GB | 9 TB | $43.88/年 | [ 开通 4 GB](https://my.racknerd.com/cart.php?a=add&pid=906&aff=16470) |
| 6 GB | 4 vCPU / 6 GB | 140 GB | 12 TB | $59.99/年 | [ 开通 6 GB](https://my.racknerd.com/cart.php?a=add&pid=907&aff=16470) |

下单时自选机房。系统支持 CentOS、RockyLinux、AlmaLinux、Fedora、Debian、Ubuntu，可随时在 SolusVM 面板里重装；重启、设置 rDNS 也都在面板里完成，不用开工单等回复。

### 常驻特价页的另一批套餐

RackNerd 的特价页上还常年挂着另一批年付套餐，和新年档并存。区别在配比：SSD 给得小一点，流量给得多一点，价格整体略高。除非你想要 8 GB 内存这一档（新年档没有 8 GB），否则一般新年档更划算。

| 套餐 | CPU / 内存 | SSD 存储 | 月流量 | 年付价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| 1 GB | 1 vCPU / 1 GB | 20 GB | 3 TB | $21.99/年 | [ 开通 1 GB](https://my.racknerd.com/aff.php?aff=16470&pid=952) |
| 2 GB | 2 vCPU / 2 GB | 35 GB | 5 TB | $35.99/年 | [ 开通 2 GB](https://my.racknerd.com/aff.php?aff=16470&pid=953) |
| 4 GB | 3 vCPU / 4 GB | 60 GB | 7 TB | $59.99/年 | [ 开通 4 GB](https://my.racknerd.com/aff.php?aff=16470&pid=954) |
| 6 GB | 6 vCPU / 6 GB | 100 GB | 12 TB | $89.99/年 | [ 开通 6 GB](https://my.racknerd.com/aff.php?aff=16470&pid=955) |
| 8 GB | 7 vCPU / 8 GB | 150 GB | 20 TB | $119.99/年 | [ 开通 8 GB](https://my.racknerd.com/aff.php?aff=16470&pid=956) |

另外，此前黑五批次的套餐也曾长期挂售，个别配置的单位价格更低——比如 1 GB（25 GB SSD、2 TB 流量）$10.60/年，或 8 GB（150 GB SSD、20 TB 流量）$62.49/年。下单前把几批价格都过一遍再动手，不算浪费时间。

## 月付套餐和 Windows VPS：谁需要，多少钱

多数人用不上这两条产品线。月付序列的单价远高于年付特价，只适合完全不确定会用多久的场景；Windows VPS 按月计费，留给确实需要 Windows 环境的人。

月付 KVM 序列如下（512 MB 档是例外，按年收）：

| 套餐 | CPU / 内存 | SSD 存储 | 月流量 | 价格 | 购买 |
| --- | --- | --- | --- | --- | --- |
| 512 MB | 1 vCore / 512 MB | 30 GB | 500 GB | $26.99/年 | [ 开通](https://my.racknerd.com/cart.php?a=add&pid=1&aff=16470) |
| 1 GB | 2 vCore / 1 GB | 50 GB | 1 TB | $17.99/月 | [ 开通](https://my.racknerd.com/cart.php?a=add&pid=20&aff=16470) |
| 2 GB | 3 vCore / 2 GB | 75 GB | 2 TB | $20.59/月 | [ 开通](https://my.racknerd.com/cart.php?a=add&pid=21&aff=16470) |
| 4 GB | 4 vCore / 4 GB | 130 GB | 3 TB | $24.59/月 | [ 开通](https://my.racknerd.com/cart.php?a=add&pid=22&aff=16470) |
| 6 GB | 5 vCore / 6 GB | 170 GB | 4 TB | $27.59/月 | [ 开通](https://my.racknerd.com/cart.php?a=add&pid=23&aff=16470) |
| 8 GB | 6 vCore / 8 GB | 220 GB | 5 TB | $36.59/月 | [ 开通](https://my.racknerd.com/cart.php?a=add&pid=24&aff=16470) |
| 12 GB | 7 vCore / 12 GB | 300 GB | 6 TB | $55.99/月 | [ 开通](https://my.racknerd.com/cart.php?a=add&pid=25&aff=16470) |

512 MB 这一档要留意：它挂在月付序列里，实际按年收 $26.99，约合 $2.25/月，页面上容易看错。同样是 1 GB 内存，月付线要 $17.99 一个月，年付特价是 $11.29 一年——打算长期跑的项目没有理由选月付。

Windows VPS 跑在 AMD Ryzen 3900X 上，配 NVMe 存储，含完整管理员权限和远程桌面：

| 套餐 | CPU / 内存 | NVMe 存储 | 月流量 | 月付价格 |
| --- | --- | --- | --- | --- |
| Windows Basic | 1 vCore / 2 GB | 35 GB | 2 TB | $27.59/月 |
| Windows Standard | 2 vCores / 4 GB | 55 GB | 3 TB | $30.59/月 |
| Windows Plus | 2 vCores / 6 GB | 80 GB | 4 TB | $35.59/月 |
| Windows Pro | 3 vCores / 8 GB | 110 GB | 5 TB | $44.59/月 |
| Windows Enterprise | 4 vCores / 12 GB | 150 GB | 6 TB | $64.59/月 |

Windows 线有专门的终身 7 折码（见下文优惠码部分），折后价格会好看不少：👉 [查看 RackNerd Windows VPS 与全部套餐价格](https://bit.ly/my-rn)

## 怎么选套餐：按用途对号入座

大多数个人用途在 1 GB 到 3.5 GB 之间就能解决，真正的分界线是要不要第二颗 CPU 核心。

- 单一轻量任务（个人 VPN、DNS 解析、Telegram 机器人、cron 定时任务、监控节点）：1 GB，$11.29/年，够用，别加钱。
- WordPress 博客、Nextcloud、小型游戏服务器、日常开发环境：2 GB，$18.29/年，内存宽裕一倍，体验差别明显。
- 容器化服务、有并发请求的自托管工具、小型应用服务器：3.5 GB（2 核），$32.49/年。两颗核心是这档与低配档的实质区别，也是它卖得最好的原因。
- Discourse 论坛、重型 CMS、打算长期跑的生产服务：4 GB（3 核）$43.88/年，或 6 GB（4 核）$59.99/年，后者折合约 $5/月。

4 GB 和 6 GB 之间差 $16.11/年，买到的是 1 颗核心和 35 GB SSD。没有明确的数据库压力或并发需求，4 GB 就到头了。

确定要 2 核的话可以直接下单：👉 [直达 3.5 GB 年付特价（$32.49/年）](https://my.racknerd.com/cart.php?a=add&pid=905&aff=16470)

## 机房怎么选：面向亚洲优先洛杉矶

RackNerd 在 20 个地区运营 21 个数据中心：北美有洛杉矶（两个机房）、圣何塞、西雅图、达拉斯、芝加哥、亚特兰大、阿什本、纽约、新泽西、坦帕、迈阿密、多伦多、蒙特利尔；欧洲有阿姆斯特丹、伦敦、都柏林、斯特拉斯堡、法兰克福；亚洲有新加坡。机房在下单时选定，之后更换需要重装，所以值得先想清楚。

访问方向决定选择。服务亚洲用户或从国内访问，选洛杉矶的 Asia-optimized 线路，或新加坡机房；欧洲用户居多就选阿姆斯特丹、伦敦或法兰克福；纯美国业务，洛杉矶 DC-02 和圣何塞是最常见的两处。

还有一个容易被漏看的点：洛杉矶和法国机房可以免费申请 IPv6，最多 100 个地址。很多低价 VPS 要么不提供 IPv6，要么单独收费，这对需要 v6 出口或折腾邮件服务的用户有实际意义。

## 优惠码：什么时候有用，什么时候白忙

先说结论：年付特价本身就是优惠价，结账时基本就是页面标价；优惠码的价值在月付、Windows VPS 和独立服务器上。一个订单只能用一个码，结账页别反复试码浪费时间。

| 优惠码 | 折扣 | 适用范围 |
| --- | --- | --- |
| INTENSEINVESTOR | 循环 7 折 | KVM VPS 与 Windows VPS（月付、年付均适用） |
| WIN-30OFF | 终身 7 折 | Windows VPS |
| MYPHPNOTES | 终身 7 折 | 共享主机与 VPS |
| 15OFFDEDI | 终身 85 折 | 全部独立服务器 |
| HYBRID10OFF | 终身 9 折 | 混合独立服务器 |
| RESELLER15OFF | 终身 85 折 | 分销主机 |

给确实需要独立服务器的人，当前有三台特价：Xeon E3-1240 V3（4 核 3.4 GHz / 32 GB 内存 / 1 TB SSD + 3 TB HDD，1Gbps 不限流量）$64.95/月；AMD Ryzen 7600（6 核 3.8 GHz / 64 GB / 1 TB NVMe）$109.95/月；双路 E5-2683 v4（32 核 / 256 GB / 2×2 TB SSD）$209/月。独服需要 24–72 小时装机，结账用 15OFFDEDI 可以终身 85 折。预算够不到独服又想要独享资源，混合独立服务器 $39/月起，即时开通。官网还有 cPanel 共享主机和机柜托管（1U 起 $99/月）两条线，和本文主题关系不大，就不展开了。

## 适合谁买，谁该绕开

RackNerd 的定位是“自己动手”的基础设施，几类人买它最值：跑测试环境和 staging 的开发者；自托管个人工具、VPN、机器人和 home lab 的折腾党；不想为企业级定价买单的自由职业者和小商家；需要 7×24 挂着的自动化任务；以及想在 AWS 账单之前先验证想法的 MicroSaaS 尝试者。

有几类需求该直接绕开。需要托管式支持和 SLA 保障的生产环境，这类低价 VPS 给不了；需要 S3 兼容对象存储或负载均衡的项目，RackNerd 不提供这两类产品；习惯现代面板体验的用户也会别扭——SolusVM 重启、重装、rDNS 都能用，但界面确实停留在上一个年代。

## 常见问题

**续费会涨价吗？**
年付特价续费同价，第一年 $11.29，第二年还是 $11.29。这也是它和多数“首年特价”商家最不一样的地方。

**能装 Docker 吗？**
能。KVM 全虚拟化，内存独享，Docker 和自定义内核都能跑；特殊系统镜像可以通过工单申请挂载自定义 ISO。

**下单后多久能用？**
Linux VPS 多数情况下 60 秒内自动开通；独立服务器需要 24–72 小时装机。

**黑五那种更低的价还会出现吗？**
RackNerd 的习惯是几批促销同时挂售，黑五批次过去也曾长期在线。想拿最低的单位价格，就把新年档、常驻特价页和黑五残留配置都对比一遍再下单。

## 下单前最后两件事

一是机房：面向亚洲的流量选洛杉矶（Asia-optimized）或新加坡，欧洲方向再看阿姆斯特丹、法兰克福，选错要重装才能换。二是优惠码和年付特价二选一，不要指望叠加。

按用途一句话分：单一轻量任务选 1 GB（$11.29/年），要并发和容器就上 3.5 GB（$32.49/年，2 核 7 TB），这是全场单位配置最均衡的一档。👉 [查看 RackNerd 年付特价并选好机房开通](https://bit.ly/my-rn)
