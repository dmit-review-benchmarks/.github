
你有没有遇到过这种情况——买了一台所谓"优化线路"的VPS，结果晚高峰一到，延迟直接飙到500ms，网页加载慢得跟拨号时代一样？

这不是你运气差，是你踩了坑。

大多数VPS商打出的"中国优化"旗号，其实不过是普通国际线路贴了个标签。而 **DMIT**（dmit.io）这家成立于2018年的主机商，从一开始走的就是另一条路——不比价格，比线路质量。

人家老老实实告诉你：我用的是 CN2 GIA、CMIN2、AS9929 这些精品线路，处理器是 AMD EPYC，不超售。

贵是真贵，但值不值得，得看你是什么人、有什么需求。

这篇文章，就按不同用户群体，帮你把 DMIT 的选择逻辑捋清楚。

---

## DMIT 是什么？先建立基本认知

DMIT 是一家在美国纽约注册（公司编号5246271）、华人创办和运营的 VPS 提供商，面向全球用户，尤其专注于需要连接中国大陆的场景。

目前数据中心覆盖四个地区：
- 美国洛杉矶（LAX）
- 美国圣何塞（SJC）
- 中国香港（HKG）
- 日本东京（TYO）

每个地区又分多个产品线，线路质量不同，价格差异显著。核心硬件全线标配 AMD EPYC 高性能处理器 + 企业级 NVMe SSD，磁盘 I/O 实测平均超过 800MB/s。

支持支付宝、微信、PayPal 付款，有中文客服，IP 被墙可每15天免费更换一次。

---

## 不同用户，应该怎么选 DMIT？

### 用户类型一：科学上网 / 搭梯子用户

这类用户最关心的是：**延迟低、稳定性好、性价比合理**。

对大陆用户来说，延迟直接决定体验。洛杉矶 CN2 GIA 线路（LAX.Pro 系列）是这类用户的传统首选，三网回程均走 CN2 GIA，晚高峰也能保持稳定，延迟通常在 150ms 以内。

想要更好性价比，可以看洛杉矶 Eyeball 系列（LAX.EB），三网回程走 CMIN2，与 CN2 GIA 相比延迟稍高一点，但流量更大、带宽更高，价格相当。

如果对延迟极其敏感，香港 Premium（HKG.Pro）才是终极选择——地理位置近，延迟通常在50ms以内，但价格相对较高。

👉 [查看洛杉矶 CN2 GIA 入门套餐 LAX.Pro.WEE](https://www.dmit.io/aff.php?aff=13832&pid=183)（$36.9/年，性价比首选）

👉 [查看洛杉矶 CMIN2 入门套餐 LAX.EB.WEE](https://www.dmit.io/aff.php?aff=13832&pid=188)（$39.9/年，流量更充裕）

**当前有效优惠码：**
- `LAX-EB-LAUNCH-NON-MONTHLY-RECURRING-20OFF`：洛杉矶 Eyeball 系列季付或年付永久8折（终身循环）
- `2025-TYO-T1-HI-GSL-NON-MONTHLY-30OFF`：东京 Tier 1 季付或年付永久7折

---

### 用户类型二：个人建站 / 内容创作者

建站需求跟梯子不完全一样——你需要稳定的在线率、一定的防 DDoS 能力，以及能解锁 Netflix 等流媒体服务的原生 IP。

DMIT 全线标配原生 IP，实测可解锁 Netflix、TikTok 等主流流媒体（但商家不作保证，以实际测试为准）。

建站首推洛杉矶 Premium Secure 系列（LAX.sPro）——去程接入 Cloudflare Magic Transit（CFMT）的 5Tbps+ DDoS 高级防护，三网回程走 CN2 GIA，兼顾安全和速度。圣何塞 Tier 1（SJC.T1）系列也自带 20Gbps DDoS 防御，价格更实惠，适合对延迟要求不那么极致的建站用户。

👉 [查看高防建站套餐 LAX.sPro.CREATOR](https://www.dmit.io/aff.php?aff=13832&pid=130)（$71.99/季，带 CFMT 防护）

👉 [查看圣何塞 SJC.T1.STARTER](https://www.dmit.io/aff.php?aff=13832&pid=146)（$12.9/月，自带20G防御）

---

### 用户类型三：中小企业 / 跨境电商

跨境电商对网络质量的要求很微妙——你不只需要国内用户访问快，还需要处理各种业务系统，稳定性和可靠性优先于极致性能。

这类用户可以考虑圣何塞 Tier 1 中等配置，或者香港 Eyeball 系列。香港节点地理位置靠近大陆，联通和电信回程直连，适合对亚太地区访问速度有要求的业务场景。

DMIT 官方明确承诺不超售，加上硬件定期升级（老用户同步免费升配），对需要长期稳定运营的企业来说，这一点非常重要。

👉 [查看香港 Eyeball 入门套餐 HKG.EB.TINYv2](https://www.dmit.io/aff.php?aff=13832&pid=154)（$29.9/月）

👉 [查看香港 Premium 套餐 HKG.Pro.TINY](https://www.dmit.io/aff.php?aff=13832&pid=123)（$39.9/月，三网 CN2 GIA 优化）

**当前有效优惠码：**
- `HKG-T1-ANNUALLY-45OFF-RECUR`：香港 Tier 1 年付45%永久折扣，且升级配置（更多 vCPU、双倍硬盘、50%+ 内存）
- `202510_HKG_TYO_PRO_20OFF_RECURRING`：香港/东京 Pro 系列季付及以上8折循环

---

## DMIT 全系套餐价格对比表

以下为 DMIT 当前主要产品线的完整套餐信息，数据基于官方网站，请以官网实时显示为准。

### 🇺🇸 洛杉矶 Premium（LAX.Pro）— 三网 CN2 GIA

| 方案 | 内存 | CPU | 硬盘 | 流量 | 带宽 | 价格 | 购买 |
|------|------|-----|------|------|------|------|------|
| LAX.Pro.WEE | 1G | 1核 | 20G | 500G/月 | 500Mbps | $36.9/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=183) |
| LAX.Pro.MALIBU | 1G | 1核 | 20G | 1T/月 | 1Gbps | $49.9/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=186) |
| LAX.Pro.PalmSpring | 2G | 2核 | 40G | 2T/月 | 2Gbps | $100/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=182) |
| LAX.Pro.TINY | 2G | 1核 | 20G | 1T/月 | 1Gbps | $9.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=100) |
| LAX.Pro.Pocket | 2G | 1核 | 40G | 1.5T/月 | 4Gbps | $14.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=137) |
| LAX.Pro.STARTER | 2G | 2核 | 80G | 3T/月 | 10Gbps | $29.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=56) |
| LAX.Pro.MINI | 4G | 4核 | 80G | 5T/月 | 10Gbps | $58.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=58) |
| LAX.Pro.MICRO | 4G | 4核 | 160G | 7T/月 | 10Gbps | $74.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=81) |
| LAX.Pro.MEDIUM | 8G | 4核 | 160G | 14T/月 | 10Gbps | $168.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=82) |
| LAX.Pro.LARGE | 16G | 8核 | 320G | 25T/月 | 10Gbps | $338.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=61) |
| LAX.Pro.GIANT | 24G | 12核 | 640G | 50T/月 | 10Gbps | $619.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=98) |

### 🇺🇸 洛杉矶 Premium Unmetered（LAX.Pro.u）— CN2 GIA 不限流量

| 方案 | 内存 | CPU | 硬盘 | 流量 | 带宽 | 价格 | 购买 |
|------|------|-----|------|------|------|------|------|
| LAX.Pro.uMINI | 2G | 2核 | 20G | 无限制 | 30Mbps | $239.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=62) |
| LAX.Pro.uMICRO | 8G | 4核 | 50G | 无限制 | 50Mbps | $399.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=64) |
| LAX.Pro.uMEDIUM | 8G | 4核 | 80G | 无限制 | 100Mbps | $799.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=65) |
| LAX.Pro.uLARGE | 16G | 8核 | 100G | 无限制 | 200Mbps | $1399.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=66) |

### 🇺🇸 洛杉矶 Premium Secure（LAX.sPro）— 高防 CN2 GIA

| 方案 | 内存 | CPU | 硬盘 | 流量 | 带宽 | 价格 | 购买 |
|------|------|-----|------|------|------|------|------|
| LAX.sPro.CREATOR | 2G | 2核 | 20G | 1.5T/月 | 100Mbps | $71.99/季 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=130) |

### 🇺🇸 洛杉矶 Eyeball（LAX.EB）— 三网 CMIN2

| 方案 | 内存 | CPU | 硬盘 | 流量 | 带宽 | 价格 | 购买 |
|------|------|-----|------|------|------|------|------|
| LAX.EB.WEE | 1G | 1核 | 20G | 1T/月 | 1Gbps | $39.9/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=188) |
| LAX.EB.CORONA | 1G | 1核 | 20G | 1.5T/月 | 2Gbps | $49.9/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=218) |
| LAX.EB.FONTANA | 2G | 2核 | 40G | 2.5T/月 | 4Gbps | $100/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=219) |
| LAX.EB.TINY | 2G | 1核 | 20G | 1.5T/月 | 2Gbps | $9.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=189) |
| LAX.EB.Pocket | 2G | 1核 | 40G | 3T/月 | 4Gbps | $14.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=190) |
| LAX.EB.STARTER | 2G | 2核 | 80G | 5T/月 | 10Gbps | $29.90/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=191) |
| LAX.EB.MINI | 4G | 4核 | 80G | 10T/月 | 10Gbps | $58.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=192) |
| LAX.EB.MICRO | 4G | 4核 | 160G | 14T/月 | 10Gbps | $74.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=193) |
| LAX.EB.MEDIUM | 8G | 6核 | 160G | 30T/月 | 10Gbps | $168.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=194) |
| LAX.EB.LARGE | 16G | 8核 | 320G | 50T/月 | 10Gbps | $338.88/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=195) |
| LAX.EB.GIANT | 24G | 8核 | 640G | 100T/月 | 10Gbps | $619.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=196) |

### 🇺🇸 圣何塞 Tier 1（SJC.T1）— 附带 20Gbps DDoS 防御

| 方案 | 内存 | CPU | 硬盘 | 流量 | 带宽 | 价格 | 购买 |
|------|------|-----|------|------|------|------|------|
| SJC.T1.WEE | 0.5G | 1核 | 10G | 1T/月 | 10Gbps | $36.9/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=152) |
| SJC.T1.TINY | 0.75G | 1核 | 10G | 2T/月 | 10Gbps | $6.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=145) |
| SJC.T1.STARTER | 1.5G | 1核 | 20G | 4T/月 | 10Gbps | $12.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=146) |
| SJC.T1.MINI | 2G | 2核 | 40G | 8T/月 | 10Gbps | $21.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=147) |
| SJC.T1.MICRO | 4G | 2核 | 80G | 16T/月 | 10Gbps | $32.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=148) |
| SJC.T1.MEDIUM | 4G | 4核 | 120G | 32T/月 | 10Gbps | $49.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=149) |
| SJC.T1.LARGE | 8G | 4核 | 200G | 64T/月 | 10Gbps | $99.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=150) |
| SJC.T1.GIANT | 16G | 8核 | 400G | 128T/月 | 10Gbps | $199.99/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=151) |

### 🇭🇰 香港 Premium（HKG.Pro）— 三网 CN2 GIA / AS9929 / CMI

| 方案 | 内存 | CPU | 硬盘 | 流量 | 带宽 | 价格 | 购买 |
|------|------|-----|------|------|------|------|------|
| HKG.Pro.TINY | 1G | 1核 | 20G | 400G/月 | 1Gbps | $39.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=123) |
| HKG.Pro.STARTER | 2G | 1核 | 40G | 800G/月 | 1Gbps | $79.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=124) |
| HKG.Pro.MINI | 2G | 2核 | 60G | 1.2T/月 | 1Gbps | $119.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=125) |
| HKG.Pro.MICRO | 4G | 4核 | 80G | 1.6T/月 | 1Gbps | $159.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=126) |
| HKG.Pro.MEDIUM | 8G | 4核 | 160G | 1.8T/月 | 1Gbps | $179.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=127) |
| HKG.Pro.LARGE | 16G | 8核 | 320G | 2.4T/月 | 1Gbps | $239.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=128) |
| HKG.Pro.GIANT | 24G | 8核 | 640G | 4.8T/月 | 1Gbps | $499.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=129) |

### 🇭🇰 香港 Eyeball（HKG.EB）

| 方案 | 内存 | CPU | 硬盘 | 流量 | 带宽 | 价格 | 购买 |
|------|------|-----|------|------|------|------|------|
| HKG.EB.TINYv2 | 1G | 1核 | 20G | 1T/月 | 1Gbps | $29.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=154) |
| HKG.EB.STARTERv2 | 2G | 1核 | 40G | 2T/月 | 2Gbps | $59.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=155) |
| HKG.EB.MINIv2 | 2G | 2核 | 60G | 3T/月 | 2Gbps | $89.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=156) |
| HKG.EB.MICROv2 | 4G | 4核 | 80G | 4T/月 | 4Gbps | $129.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=157) |
| HKG.EB.MEDIUMv2 | 8G | 4核 | 160G | 6T/月 | 4Gbps | $199.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=158) |
| HKG.EB.LARGEv2 | 16G | 4核 | 320G | 12T/月 | 4Gbps | $389.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=159) |
| HKG.EB.GIANTv2 | 24G | 8核 | 640G | 24T/月 | 4Gbps | $789.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=160) |

### 🇭🇰 香港 Tier 1（HKG.T1）— 国际线路

| 方案 | 内存 | CPU | 硬盘 | 流量 | 带宽 | 价格 | 购买 |
|------|------|-----|------|------|------|------|------|
| HKG.T1.WEE | 1G | 1核 | 20G | 1T/月 | 10Gbps | $36.9/年 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=197) |
| HKG.T1.TINY | 1G | 1核 | 20G | 2T/月 | 10Gbps | $6.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=198) |
| HKG.T1.STARTER | 2G | 1核 | 40G | 4T/月 | 10Gbps | $12.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=199) |
| HKG.T1.MINI | 2G | 2核 | 60G | 8T/月 | 10Gbps | $21.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=200) |
| HKG.T1.MICRO | 4G | 4核 | 80G | 16T/月 | 10Gbps | $32.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=201) |
| HKG.T1.MEDIUM | 8G | 4核 | 160G | 32T/月 | 10Gbps | $49.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=202) |
| HKG.T1.LARGE | 16G | 8核 | 320G | 64T/月 | 10Gbps | $99.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=203) |
| HKG.T1.GIANT | 24G | 8核 | 640G | 128T/月 | 10Gbps | $199.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=204) |

### 🇯🇵 东京 Premium（TYO.Pro）— CN2 GIA / AS9929 / CMI

| 方案 | 内存 | CPU | 硬盘 | 流量 | 带宽 | 价格 | 购买 |
|------|------|-----|------|------|------|------|------|
| TYO.Pro.TINY | 0.75G | 1核 | 15G | 300G/月 | 100Mbps | $19.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=138) |
| TYO.Pro.STARTER | 1.5G | 1核 | 20G | 500G/月 | 100Mbps | $32.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=139) |
| TYO.Pro.MINI | 2G | 2核 | 40G | 1T/月 | 100Mbps | $69.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=140) |
| TYO.Pro.MICRO | 4G | 2核 | 40G | 2T/月 | 100Mbps | $139.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=141) |
| TYO.Pro.MEDIUM | 4G | 4核 | 60G | 3T/月 | 100Mbps | $199.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=142) |
| TYO.Pro.LARGE | 8G | 4核 | 100G | 5T/月 | 100Mbps | $329.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=143) |
| TYO.Pro.GIANT | 16G | 8核 | 200G | 10T/月 | 100Mbps | $659.9/月 |  [立即购买](https://www.dmit.io/aff.php?aff=13832&pid=144) |

> ⚠️ 部分热门套餐（尤其年付特惠款）库存有限，随时可能售罄，有购买计划的建议不要犹豫太久。

---

## 一张图说清楚：你该选哪个产品线？

| 需求场景 | 推荐产品线 | 核心优势 |
|---------|-----------|--------|
| 科学上网，追求稳定低延迟 | LAX.Pro / LAX.EB | CN2 GIA / CMIN2，晚高峰稳定 |
| 高防建站，防 DDoS | LAX.sPro / SJC.T1 | CFMT 5Tbps+ / 20Gbps 防御 |
| 极低延迟，连大陆速度最快 | HKG.Pro | 地理位置近，<50ms |
| 预算有限，入门体验 | SJC.T1 / HKG.T1 | 价格低，T1 国际线路 |
| 东亚用户服务，游戏服 | TYO.Pro | AS9929 + CN2 GIA，日本节点 |
| 无限流量业务需求 | LAX.Pro.u | CN2 GIA + 无限流量 |

---

## 用了三年的真实感受

一位使用 DMIT 超过三年的站长这样描述他的体验：

最初选择 DMIT，是因为他们是带宽上游提供商，能直接控制线路质量，而不是倒卖别人的资源。用下来之后，印象最深的有几点——晚高峰完全感受不到波动，从中国访问的延迟一直维持在150ms以内；去年项目需要扩容内存，联系客服后不到一小时就完成了升配，只收了配置差价；碰到一次小规模 DDoS，防护系统自动介入，网站几乎没有中断。

当然 DMIT 也有不那么完美的地方。香港和东京节点在2025年底遭遇过持续的 DDoS 攻击，部分用户经历了网络波动。不过他们的处理方式赢得了不少好评——主动给受影响用户提供了免费补偿服务器，并同步升级了网络基础设施。这种透明的态度，在国内外主机商里算是少见的。

---

## 快速决策指南

**问自己三个问题：**

1. **你在哪里？用户在哪里？** 如果你在大陆，服务国内用户，香港 Pro 延迟最低；如果服务全球但需要对中国友好，洛杉矶 CN2 GIA 是性价比更高的选择。

2. **你的预算底线是多少？** 年付入门价从 $36.9 起（LAX.Pro.WEE），月付最低 $6.9（SJC.T1.TINY），拿来体验完全够。

3. **你更怕延迟高，还是怕被打？** 怕延迟高选 Pro 系列，怕被 DDoS 选 sPro 或 SJC.T1。

想不清楚的话，从圣何塞 T1 的 TINY 套餐入手，$6.9/月成本极低，感受一下再做决定。

👉 [浏览 DMIT 全部套餐](https://www.dmit.io/aff.php?aff=13832)

---

## 当前可用优惠码汇总

| 优惠码 | 适用范围 | 折扣 |
|--------|---------|------|
| `LAX-EB-LAUNCH-NON-MONTHLY-RECURRING-20OFF` | 洛杉矶 Eyeball 系列（季付/年付） | 永久8折循环 |
| `2025-TYO-T1-HI-GSL-NON-MONTHLY-30OFF` | 东京 Tier 1（季付/年付） | 永久7折循环 |
| `2025-TYO-T1-HI-GSL-MONTHLY-10OFF` | 东京 Tier 1（月付） | 9折 |
| `HKG-T1-ANNUALLY-45OFF-RECUR` | 香港 Tier 1（年付） | 永久55折 + 升配 |
| `202510_HKG_TYO_PRO_20OFF_RECURRING` | 香港/东京 Pro 系列（季付及以上） | 永久8折循环 |
| `2025-XMAS-LAX-T1-10-OFF-RECURRING` | 洛杉矶 T1 系列 | 9折循环 |
| `SJC-Unmetered-Annually-30OFF` | 圣何塞不限流量套餐（年付） | 7折 |

> 优惠码数量有限，具体有效期和库存以官网实时情况为准，使用前建议先验证。

---

DMIT 不是那种让你一看价格就心动的选择，但如果你对网络质量有真实需求，折腾过那些"便宜但不稳定"的服务，或许会觉得——这钱花得值。

👉 [立即前往 DMIT 查看最新套餐与促销](https://www.dmit.io/aff.php?aff=13832)
