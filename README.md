## Hackintosh黑苹果长期维护机型EFI及安装教程整理

[![img](https://img.shields.io/github/stars/daliansky/Hackintosh.svg?color=ff69b4&label=%E7%82%B9%E8%B5%9E&logoColor=ff69b4&style=social)](https://github.com/daliansky/Hackintosh) [![img](https://img.shields.io/github/followers/daliansky.svg?label=%E7%B2%89%E4%B8%9D&logoColor=success&style=social)](https://github.com/daliansky/Hackintosh) ![img](https://img.shields.io/github/contributors/daliansky/Hackintosh.svg?color=red&label=%E8%B4%A1%E7%8C%AE%E4%BA%BA%E6%95%B0) [![img](https://img.shields.io/github/last-commit/daliansky/Hackintosh.svg?color=orange&label=%E6%9C%80%E8%BF%91%E6%8F%90%E4%BA%A4)](https://github.com/daliansky/Hackintosh) [![img](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu/)

## English Version: [Hackintosh long-term maintenance model EFI and installation tutorial](README_en.md)

## 黑苹果长期维护机型整理

> by @[我意](https://github.com/y010204025)
>
> 整理这份清单的目的：在于给想体验黑苹果的人一个方向，也想减少大家重复造轮子，节约大家的时间。
>
> 所有文件均归属于原作者，本清单只列出链接。如果您不希望你的链接被这份清单收录，请发送邮件到 [y010204025@126.com](mailto:y010204025@126.com),我将移除链接
> 清单收录了 4 个月以内的有人长期维护并更新过 EFI 的机型链接，如果有新的链接希望收录到这份清单，请发送邮件到 [y010204025@126.com](mailto:y010204025@126.com)
>
> 致谢：感谢一直为黑苹果进行开发的各位开发者和愿意共享出 EFI 文件的开发者，谢谢！
> 最近有部分github作者删除了repo,有失效的请大家反馈，我会及时跟进删除相关链接。

- 建议大家使用[yandex搜索引擎](https://yandex.ru)、[github](https://github.com)先搜索下有没有自己的机型，型号一样，机型配置有差异可以忽略，使用你的机器型号+clover、型号+EFI、型号+mac、型号+Hackintosh等进行搜索。例如我最近更新了 elitebook840g3、840g4等几个机型的 EFI，就可以使用840g3+clover 840g3+EFI 等关键词进行搜索。

- 黑苹果论坛：

  - **国内** [远景论坛](http://bbs.pcbeta.com)、[威锋论坛](http://bbs.feng.com)
  - **国外** [insanelymac 论坛](https://www.insanelymac.com/forum/)、[tonymacx86论坛](https://www.tonymacx86.com/)、[德国黑苹果论坛](https://www.hackintosh-forum.de/)、[俄罗斯黑苹果论坛](https://www.applelife.ru)、[法国黑苹果论坛](https://www.hackintosh-montreal.com)、 [osxlatitude论坛](https://osxlatitude.com/forums/)

- 一些黑苹果常用的软件或者驱动开发者的主页，希望大家能及时更新驱动和软件，驱动需要自己去对应驱动开发者的主页去更新。
  
- *[RehabMan](https://bitbucket.org/RehabMan/)* 维护了很多黑苹果驱动和相关补丁
- *[Vit9696](https://github.com/acidanthera)* lilu和相关插件、applealc的主要开发或维护者
- *[Clover更新地址](https://sourceforge.net/projects/cloverefiboot/)* Clover团队更新 clover的主要发布渠道
- *[常用软件和驱动清单](./LinkList.md)* 整理了常用软件和驱动的主要发佈地址，持续修改……

 *关于黑苹果，希望大家能摆正心态，容忍小问题的存在，某些功能无法实现或者是体验不好「触摸板、指点杆、触摸屏、雷电端口等等」，系统运行不稳定，容易卡机或者死机或者是开机不认引导、升级系统失败等都属于正常现象。 **每次升级前请先从各种驱动了解本次升级有没有大的改动，在升级前首先升级 Clover 和相关的 kext 驱动，需要添加补丁或者是更新补丁的请做好相关工作，不要等著出了问题再去寻找解决方案。** 在自己遇到问题的时候，请先通过网络寻找解决办法，无法解决再询问别人，请别人帮忙解决问题的时候，首先端正自己的态度，把问题描述清楚，能提供 log 日志或者是相关文件的先提供文件，提供不了文件的拍照拍清楚。*

**解决问题，需要努力的是自己，不是让别人帮你努力；帮你解答是情分，不是义务**

**为了感谢这份清单内机型的维护人员的长期的付出，希望大家在下载 EFI 的时候点一下 'star',顺便可以点一下 'watch',这样你将会收到你关注机型 efi 的更新提醒，这是对维护人员的一种肯定和鼓励。**

**感谢各位维护人员的辛勤付出，希望在更新时能够提供必要的更新内容说明，在引用别人的补丁、或者是某些特殊版本的驱动是给出驱动的来源链接，必要时还请加入一些 credit，黑苹果更多的是大家群策群力、开放共享努力的结果。**

*希望整个黑苹果领域能够进入良性循环状态，不用再重复造很多轮子，也希望那些使用别人成果收费的人，必要时还请留出文件来源和相关致谢。*

## 同步更新：[黑果小兵的部落阁](<https://blog.daliansky.net/Hackintosh-long-term-maintenance-model-checklist.html>)

## 机型讨论：[远景pcbeta.com](<http://bbs.pcbeta.com/viewthread-1795904-1-1.html>)

<details>
<summary>更新日志</summary>
<pre><code>
更新日期：
- 2018年10月06日
- 2018年12月25日
- 2019年01月15日
- 2019年3月1日 by @[黑果小兵](https://github.com/daliansky)
  - 按机型重新排版
  - 将该文档上传到[仓库](https://github.com/daliansky/Hackintosh)，方便其它人提交合并，共同维护
- 2019年3月21日
- 发布到[博客](https://blog.daliansky.net)
  - 添加底噪的[黑苹果合集](https://zhih.me/hackintosh/)
  - 添加`华为 Matebook X Pro`
- 2019年4月2日
  - 添加部分新机型
  - 将多于2个机型的品牌独立出来，方便检索
- 2019年4月15日
  - 按品牌拆分表格，方便索引
  - 添加部分新机型
- 2019年5月9日
  - 新增机型：`Mechrevo X9Ti R` / `Mechrevo Z2 G` 等
- 2019年7月3日 by [Cruii](https://github.com/Cruii)
  - 新增机型：`暗影精灵2Pro`(HP OMEN 15-ax225TX)
- 2019年7月19日 by [lgs3137](https://github.com/lgs3137)
  - 新增机型：`暗影精灵I`(惠普PAVILION Gaming NB 15-ak039TX)
- 2019年8月15日
  - 新增机型：ASUS X299 PRIME DELUXE II + i9 7980XE + Radeon VII
- 2019年8月16日
  - 新增机型：MSI X370 KRAIT GAMING + 1700X + RADEON VEGA64
  - 新增机型：ASROCK X570 TAICHI + 3700X + RADEON VEGA64，兼容ASROCK X570 
- 2019年9月1日 by [lgs3137](https://github.com/lgs3137)
  - 新增机型：`ASUS Y5000U`(X507UBR)
- 2019年9月7日 by [lgs3137](https://github.com/lgs3137)
  - 新增机型：`Acer P258-MG`
- 2019年9月17日 by [skyline75489](https://github.com/skyline75489)
  - 新增机型：`MSI GE63 Raider RGB 8RE`
- 2019年10月5日 by [sarkrui](https://github.com/sarkrui)
  - 新增机型：ASRock Z390M Pro4 + i7-9700K + Sapphire RX580 Nitro+ 8G
- 2019年10月5日 by [我意](https://github.com/y010204025)
  - 新增机型：lenovo miix4(700)、miix510、E470
- 2019年10月28日 by [W-MS](https://github.com/W-MS)
  - 新增机型：Dell OptiPlex 7060 and 7070
  - 增加新版本支持： Dell OptiPlex 9020
- 2019年11月4日 by [YGQ8988](https://github.com/YGQ8988)
  - 新增机型：HP ProBook 430 G6
- 2019年11月14日
  - 新增机型：Lenovo Y9000X
- 2019年11月21日
  - 新增机型：Dell XPS 15 7590
- 2020年1月18日
  - 新增机型：DELL系列/Lenovo系列等机型
- 2020年3月8日
  - 新增机型：华为Matebook 14 2020款
- 2020年4月8日
  - 新增机型：联想Miix 720/YOGA 910等机型
- 2020年5月5日
  - 新增机型：联想M710Q等
  - 将台式机品牌重新分类、整理，便于查看相关信息
- 2020年6月8日
  - 新增机型：新增Z490等部分台式机型
- 2020年6月10日
  - 新增机型：新增Lenovo Thinkcentre M910x等部分新机型
- 2020年6月12日
  - 新增机型：新增DELL 9020 MT/SFF/USFF/Micro机型，基于OpenCore
- 2020年6月19日
  - 新增机型：新增部分台式机型，基于OpenCore
- 2020年6月23日
	- 新增机型：新增Dell Latitude E7390等部分新机型
- 2020年6月30日
  - 新增机型：B460 / Z490 以及其它笔记本机型
- 2020年7月5日
	- 新增机型：新增ThinkPad T470p、ASUS-Prime-Z390M-PLUS、神舟战神z7-kp7sc、ASRock-B365M-ITX-AC等部分新机型
- 2020年7月31日
  - 新增机型：新增对`Big Sur`等机型的支持，新增部分新机型
- 2020年8月6日
  - 新增机型：新增B460/Z490等新机型
- 2020年8月17日
  - 新增机型：新增B450等部分机型
- 2020年8月31日
  - 新增机型：新增战神Z7、G8系列部分机型，具体请看commit
- 2020年9月15日
	- 新增机型：Lenovo 天逸 510S Mini
</code></pre>
</details>



## 笔记本部分机型

### Acer 宏碁

| 机型名称                 | 发布地址                                                     | 教程地址                                                     | 备注                        |
| ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | --------------------------- |
| Acer A315-53G            | [链接](https://github.com/hanngoc1406/ACER-A315-53G-Hackintosh-Opencore) |                                                              |                             |
| Acer Aspire 3 A315-51    | [链接](https://github.com/ZeroInfinityXDA/Acer-A315-51-Hackintosh) |                                                              |                             |
| Acer Aspire A515-51G     | [链接](https://github.com/h-okon/Acer-Aspire-A515-Hackintosh) |                                                              |                             |
| Acer Aspire A515-51G     | [链接](https://github.com/Siddhesh1197/Acer-A515-51G-Hackintosh) | [链接](https://github.com/Siddhesh1197/Acer-A515-51G-Hackintosh/blob/master/README.md) |                             |
| Acer A515-51G-58VH       | [链接](https://github.com/Rodrigmatrix/Acer-A515-51G-58VH)   |                                                              |                             |
| Acer A715                | [链接](https://github.com/WangGang-a1/Acer-A715-EFI)         |                                                              |                             |
| Acer Aspire E1-471G      | [链接](https://github.com/matthew728960/Clover-ACER-E1-471G) | [链接](https://github.com/matthew728960/Clover-ACER-E1-471G/blob/master/README.md) | ACER Aspire E1-471g         |
| Acer Aspire E5-471G      | [链接](https://github.com/THLIVSQAZ/ACER-E5-471G-OpenCore) [链接](https://github.com/THLIVSQAZ/ACER-E5-471G-Clover) |                                                              |                             |
| Acer Aspire E5 475G      | [链接](https://github.com/hilmanshini/Acer-Aspire-E5-475G-Clover-Hackintosh) |                                                              |                             |
| Acer Aspire E5-476G     | [链接](https://github.com/budhilaw/Acer-E5-476G-Hackintosh) [链接](https://github.com/rockavoldy/Acer-E5-476G-Hackintosh) |                                                              | link = i5-8250U; link2 = i3-6006U, OpenCore                    |
| Acer Aspire E5-571-5552  | [链接](https://github.com/GaryDoooo/acer_e51_osx)            |                                                              |                             |
| Acer Aspire E1-571G      | [链接](https://github.com/DiogoSilva48/Acer-E1-571G-Hackintosh) |                                                              |                             |
| Acer Aspire E1-572G      | [链接](https://github.com/TonyStark10006/Acer_E1-572G_Hackintosh_EFI) |                                                              |                             |
| Acer ES1-572-37pz        | [链接](https://github.com/joodrew/hackintosh-acer-es1-572-37pz) |                                                              |                             |
| Acer F5-573G             | [链接](https://github.com/johnnywolinger/ACER-F5-573G-Hackintosh) |                                                              |                             |
| Acer F5-573G-55PJ        | [链接](https://github.com/zoothz/Hackintosh-acer-f5-573g-55pj) |                                                              |                             |
| Acer F5-573g-75A3        | [链接](https://github.com/vinicioslc/HACKINTOSH-ACER-F5-573G-75A3) |                                                              |                             |
| Acer Nitro 5 AN515-52 | [链接](https://github.com/tien191web/Acer-Nitro5-AN515-52-EFIhackintosh) | | |
| Acer Nitro 5-an515-54-58CL | [链接](https://github.com/YuryRegis/Acer-Nitro5-AN515-54-58CL) | | |
| Acer nitro 5 an517-51    | [链接](https://github.com/SaeedHaidar/Nitro-5-an517-51-Hackintosh) |                                                              |                             |
| Acer Predator Helios 300 | [链接](https://github.com/PruvostMaxime/Hackintosh-Predator-300) [链接](https://github.com/KadeReolance/Predator-Helios-300-OpenCore-0.6.2) |                                                              |                             |
| Acer Swift 3             | [链接](https://github.com/FallenChromium/Acer-Swift3-2018-hackintosh) |                                                              | SF315-51-518S               |
| Acer Swift 3 52G         | [链接](https://github.com/geekcjj/Clover-Acer-Swift3-SF315-52G) |                                                              | Acer-Swift3-SF315-52G       |
| Acer Swift 3 SF314-55G   | [链接](https://github.com/cjtim/SF314-55G-hackintosh) [链接](https://github.com/cjtim/SF314-55G-hackintosh) |                                                              | Acer Swift 3 2019 SF314-55G |
| ACER Veriton D430 Gen4/6 | [链接](https://github.com/SummerEmber/ACER-Veriton-D430-Gen4) [链接](https://github.com/SummerEmber/ACER-Veriton-D430-Gen6) |                                                              |                             |
| Acer V3-471G             | [链接](https://github.com/oneveb/Acer-V3-471G)               |                                                              |                             |
| Acer V3-572G-51MR        | [链接](https://github.com/AnoldmanLiSir/Acer-V3-572G-51MR)   | [链接](https://github.com/AnoldmanLiSir/Acer-V3-572G-51MR/blob/master/README.md) |                             |
| Acer V5-572              | [链接](https://github.com/7ack/Acer-V5-572-Hackintosh)       | [链接](https://github.com/7ack/Acer-V5-572-Hackintosh/blob/master/readme.md) |                             |
| Acer Aspire V5-573P | [链接](https://github.com/xtrs84zk/Aspire-V5-573P-Hackintosh) |  | |
| Acer VN7-793g            | [链接](https://github.com/cedric-bour/Acer-VN7-793g-Hackintosh) |                                                              |                             |
| Acer-K50-10-525V         | [链接](https://github.com/mingslife/Acer-K50-10-525V-Hackintosh) |                                                              |                             |
| 宏碁暗影骑士3            | [链接](https://github.com/Chakid/Acer-VX15-Hackintosh)       |                                                              |                             |
| ACER-ASPIRE-C24-865      | [链接](https://github.com/Sevendaye/ACER-ASPIRE-C24-865-Clover) |                                                              |                             |
| ACER Travelmate P248     | [链接](https://github.com/jamesciq/Acer-Travelmate-P248-hackintosh-EFI) |                                                              |                             |
| Acer P258-MG             | [链接](https://github.com/lgs3137/ACER_P258_MG-macOS)        |                                                              |                             |

### Asus 华硕

| 机型名称                          | 发布地址                                                     | 教程地址                                                     | 备注                                                         |
| --------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Asus A43SJ                        | [链接](https://github.com/badruzeus/Hackintosh-Asus-A43SJ)   | [链接](https://github.com/badruzeus/Hackintosh-Asus-A43SJ/blob/master/README.md) | Asus A43SJ                                                   |
| Asus A411UF                       | [链接](https://github.com/faizauthar12/Asus_A411UF_Hackintosh) |                                                              |                                                              |
| Asus A442UF                       | [链接](https://github.com/ryansat/Hackintosh-A442UF)         |                                                              |                                                              |
| Asus A442URR                      | [链接](https://github.com/hammerrrr/efi-asus-x442urr-hackintosh) |                                                              | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Asus A455LA                       | [链接](https://github.com/brilliantedgar/Hackintosh-A455LA-Intel-Core-i3-5005U) | [链接](https://github.com/brilliantedgar/Hackintosh-A455LA-Intel-Core-i3-5005U/blob/master/README.md) | Asus S455LA                                                  |
| Asus A455LF-WX039D Series         | [链接](https://github.com/asepms92/Hackintosh-Asus-A455LF-Notebook) |                                                              |                                                              |
| Asus A456UF(X456UF)               | [链接](https://github.com/alfinauzikri/Asus-A456UF-Hackintosh) |                                                              |                                                              |
| Asus A550JK4200                   | [链接](https://github.com/hehuapei/ASUS-a550jk-4200---macOS) |                                                              |                                                              |
| Asus F455LD                       | [链接](https://github.com/athlonreg/Asus-F455LD-i5-4210u)    |                                                              |                                                              |
| Asus FX504GE-ES72                 | [链接](https://github.com/MegaStood/Hackintosh-FX504GE-ES72) |                                                              |                                                              |
| Asus FX505GD                      | [链接](https://github.com/kreactnative/hackintosh-mojave-fx505gd) |                                                              | ASUS TUF GAMING FX505GD-BQ071T                               |
| Asus F556U (X556UQK)              | [链接](https://github.com/systemfaliure/Asus-X556UQK-hackintosh#Asus-f556u-x556uqk---high-sierra-hackintosh) | [链接](https://github.com/systemfaliure/Asus-X556UQK-hackintosh/blob/master/README.md) | Asus F556U (X556UQK)                                         |
| Asus FX50J                        | [链接](https://github.com/Xc2333/Hackintosh-Asus-FX50J)      |                                                              |                                                              |
| Asus FX50V                        | [链接](https://github.com/Cyberhan123/Hackintosh-ASUS--FX50V) |                                                              |                                                              |
| FX86FE（FX505GE）                 | [链接](https://github.com/EricCui2333/FX86FE-OpenCore-0.5.5) |                                                              |                                                              |
| Asus FX533VD                      | [链接](https://github.com/kue-kid/Asus-FX533VD-HACKINTOSH)   |                                                              |                                                              |
| Asus GL503GE                      | [链接](https://github.com/Bimoaryo5/ASUS-GL503GE-Hackintosh-master) |                                                              |                                                              |
| Asus FX86FE（飞行堡垒6）                      | [链接](https://github.com/MEMUZE-Hackintosh/ASUS-FX86FE-OC) |                                                              |                                                              |
| Asus GL551JW                      | [链接](https://github.com/zacharyrs/GL551JW-Hackintosh)      |                                                              |                                                              |
| Asus GL552VW                      | [链接](https://github.com/originman521/Hackintosh-ASUS-FXPRO-GL552VW) |                                                              | 飞行堡垒2016 FXPRO                                           |
| Asus G60VW                        | [链接](https://github.com/PtNan/G60VW-Hackintosh)            |                                                              |                                                              |
| Asus K501LB                       | [链接](https://github.com/ApolloRisky/EFI_Clover-Asus-K501LB-Mojave) |                                                              |                                                              |
| ASUS K555UB Series                | [链接](https://github.com/sutsurup/ASUS-K555UB-Hackintosh)   | [链接](https://github.com/sutsurup/ASUS-K555UB-Hackintosh/blob/master/README.md) | XO092T - XO093T - XO096T - XO097T<br />XO066T - XO198T - XO266T - XO099D - XO227D |
| Asus K55VD                        | [链接](https://github.com/southernvevo/Asus-K55VD-HACKINTOSH) | [链接](https://github.com/southernvevo/Asus-K55VD-HACKINTOSH/blob/master/README.md) | Asus K55VD                                                   |
| Asus K555LD                       | [链接](https://github.com/kongbg/asus-k555ld-4210U)          | [链接](https://github.com/kongbg/asus-k555ld-4210U/blob/master/README.md) | Asus K555LD                                                  |
| Asus Laptop N56VZ                 | [链接](https://github.com/signxer/N56VZ-Hackintosh)          |                                                              |                                                              |
| Asus P8P67 PRO                    | [链接](https://github.com/rafaelmaeuer/Asus-P8P67Pro-Hackintosh) | [链接](https://github.com/rafaelmaeuer/Asus-P8P67Pro-Hackintosh/blob/master/readme.md) |                                                              |
| Asus R414U                        | [链接](https://github.com/srole-xiaoxian/ASUS-R414U-Clover)  | [链接](https://github.com/LHB6540/Asus-R414-Hackintosh-10.15.4) | 10.13&10.15                                                  |
| Asus ROG GL552JX                  | [链接](https://github.com/javanesse/Asus-ROG-GL552JX-High-Sierra-10.13-Hackintosh) | [链接](https://github.com/javanesse/Asus-ROG-GL552JX-High-Sierra-10.13-Hackintosh/blob/master/README.md) | Asus ROG GL552JX                                             |
| Asus ROG GL552VX                  | [链接](https://github.com/xuanquydsr/Gl552VX-Mojave) [链接](https://github.com/ifuncoding/EFI-OC-ROG-gl552vx) |                                                              |                                                              |
| Asus ROG GL553VD                  | [链接](https://github.com/MohammadtaghiFarkhondekar/macOS-Mojave-For-Asus-ROG-GL553VD) |                                                              |                                                              |
| Asus ROG Strix Hero II GL504GM | [链接](https://github.com/664235822/EFI-OpenCore) | | 华硕玩家国度ROG魔霸2 |
| Asus ROG Zephyrus M GM501GS       | [链接](https://github.com/kylergib/Asus-Zephyrus-M-gm501gs-Mojave) |                                                              |                                                              |
| Asus ROG Zephyrus S GX531GS       | [链接](https://github.com/williambj1/Hackintosh-EFI-Asus-Zephyrus-S-GX531) |                                                              | 华硕玩家国度冰刃 3                                           |
| Asus ROG GX701                    | [链接](https://github.com/laeo/hackintosh-rog-gx701-efi)     |                                                              |                                                              |
| ASUS S4000VA                      | [链接](https://github.com/stonexing/Asus-S4000VA8550-Hackintosh) |                                                              | 华硕灵耀 i7-8550U                                            |
| Asus S4100V                       | [链接](https://github.com/loong1992/Asus_S4100VN8250U_Hackintosh) |                                                              |                                                              |
| Asus S510UQ                       | [链接](https://github.com/KINGKONG2808/Hackintosh_ASUSS510UQ) [链接](https://github.com/JoK3rLeE/Asus-S510UQ-BQ178T) |                                                              |                                                              |
| Asus S5300FN                      | [链接](https://github.com/Jie2GG/Hackintosh-ASUS-S5300FN)    |                                                              | 华硕灵耀2代                                                  |
| Asus S530UN                       | [链接](https://github.com/tunglamvghy/AsusS530UN-hackintosh) |                                                              |                                                              |
| Asus TP300LD                      | [链接](https://github.com/danang-id/ASUS-TP300LD-ESP)        |                                                              |                                                              |
| Asus TUF Gaming FX504             | [链接](https://github.com/PoomSmart/Asus-FX504GE-Hackintosh) [链接](https://github.com/angeljavan/AUSU-FX80GE-FX504Ge-efi) | [链接](https://github.com/PoomSmart/Asus-FX504GE-Hackintosh/blob/master/README.md) | 华硕 FX80GE FX504GE                                          |
| ASUS TUF504GD                     | [链接](https://github.com/zzNuAzz/EFI-hackintosh-tuf-504gd-Clover) |                                                              |                                                              |
| Asus UX461UA                      | [链接](https://github.com/UdaraWanasinghe/Asus-UX461UA-OpenCore-EFI) |                                                              |                                                              |
| Asus UX501JW                      | [链接](https://github.com/firefly917/Hackintosh_Asus-UX501JW_Mojave) |                                                              |                                                              |
| Asus VivoBook 15 X510UQ / S5100UQ | [链接](https://github.com/wishayne/hackintosh-Asus-S5100UQ-X510UQ) |                                                              | |
| ASUS Vivobook S13 S330FN		| [链接](https://github.com/deniro98/s330fn) |                                                              | |
| Asus X441U                        | [链接](https://github.com/jundanaalbasyir/Hackintosh-Asus-X441U) |                                                              | 华硕 adol I330FN                                                             |
| Asus X441UB                       | [链接](https://github.com/alfinauzikri/Asus-X441UB-Hackintosh) |                                                              |                                                              |
| Asus X441UV                       | [链接](https://github.com/MinorityCode/asus-x441uv-hackintosh-files) |                                                              |                                                              |
| Asus A442URR                      | [链接](https://github.com/hammerrrr/efi-asus-x442urr-hackintosh) |                                                              |                                                              |
| Asus VivoBook FL8000UQ            | [链接](https://github.com/KKKIIINNN/ASUS-FL8000UQ-Hackintosh/releases)  | [链接](https://github.com/KKKIIINNN/ASUS-FL8000UQ-Hackintosh)    | ASUS FL8000UQ i7-8550U GeForce 940MX                  |
| Asus VivoBook Max X441UVK         | [链接](https://alfinauzikri.github.io/Asus-Vivobook-Max-X441UVK-Hackintosh/) |                                                              |                                                              |
| Asus VivoBook S15 S510UA          | [链接](https://github.com/tctien342/Asus-Vivobook-S510UA-High-Sierra-10.13-Hackintosh) | [链接](https://github.com/tctien342/Asus-Vivobook-S510UA-High-Sierra-10.13-Hackintosh/blob/master/README.md) | Vivobook S510UA                                              |
| Asus Vivobook S530UA BQ100T       | [链接](https://github.com/superzeldalink/Asus-Vivobook-S530-hackintosh) |                                                              |                                                              |
| Asus Vivobook S510UNR - BQ114     | [链接](https://github.com/dayfly/Asus-S510UN-EFI)            |                                                              |                                                              |
| Asus VivoBook X510UQR             | [链接](https://github.com/nguyentrucxinh/Asus-VivoBook-X510UQR-Hackintosh) | [链接](https://github.com/nguyentrucxinh/Asus-VivoBook-X510UQR-Hackintosh/blob/master/README.md) |                                                              |
| Asus VivoBook Y5000U (X507UBR)    | [链接](https://github.com/lgs3137/ASUS_Y5000U_X507UBR-macOS) |                                                              |                                                              |
| Asus W419LD                       | [链接](https://github.com/Yasin27878/Hackintosh-ASUS-W419LD) |                                                              |                                                              |
| Asus X45C                         | [链接](https://github.com/ipang-dwi/efi-high-sierra)         |                                                              |                                                              |
| Asus X450JB                       | [链接](https://github.com/xiaoMGitHub/Asus_X450JB_Hackintosh) |                                                              |                                                              |
| Asus X455LA | [链接](https://github.com/FajarBaiz/X455LA-EFI-HACKINTOSH) | | |
| Asus X455LJ                       | [链接](https://github.com/umarhadi/asus-x455lj-mojave)       |                                                              |                                                              |
| Asus X542UN                       | [链接](https://github.com/yCatDev/asus_x542un-hackintosh)    |                                                              |                                                              |
| Asus X550JX                       | [链接](https://github.com/gaoliang/Asus-X550JX-Hackintosh)   |                                                              |                                                              |
| Asus X555LB                       | [链接](https://github.com/emre1393/Asus-x555lb-mojave-efi)   |                                                              |                                                              |
| Asus X550VX                       | [链接](https://github.com/lramadhan/hackintosh-asus-x550vx)  |                                                              |                                                              |
| Asus X550VXK                      | [链接](https://github.com/Giovix92/efi_x550vxk)              |                                                              |                                                              |
| Asus X556UAK | [链接](https://github.com/sumukshashidhar/asus-x556-uak-efi-configuration) | | |
| Asus X556UJ | [链接](https://github.com/milanista18/ASUSX556UJ) | | |
| Asus X556UQ                       | [链接](https://github.com/IlhamSevensky/ASUS-X556UQ-HACKINTOSH) |                                                              | A556U                                                        |
| Asus X556UV                       | [链接](https://github.com/Amview/ASUS-X556UV-Hackintosh)     |                                                              |                                                              |
| Asus X75VC-TY056D                 | [链接](https://github.com/Jesterjke/ASUS-X75VC-Hackintosh)   |                                                              |                                                              |
| Asus X751LJ                       | [链接](https://github.com/leandro1988n/ASUS-X751LJ-Hackintosh) |                                                              |                                                              |
| Asus ZenBook 系列                 | [链接](https://github.com/hieplpvip/Asus-ZENBOOK-HACKINTOSH) | [链接](https://www.tonymacx86.com/threads/guide-Asus-zenbook-using-clover-uefi-hotpatch.257448/) | 支持型号: UX310 - UX330 - UX330<br />UX410 - UX430 - UX430   |
| Asus ZenBook Flip UX360UAK        | [链接](https://github.com/Frizz925/UX360UAK-Hackintosh)      | [链接](https://github.com/Frizz925/UX360UAK-Hackintosh/blob/master/README.md) |                                                              |
| Asus ZenBook UX32VD               | [链接](https://github.com/rafaelmaeuer/Asus-UX32VD-Hackintosh) | [链接](https://github.com/rafaelmaeuer/Asus-UX32VD-Hackintosh/blob/master/readme.md) | Asus UX32VD                                                  |
| Asus ZenBook UX330UAK             | [链接](https://github.com/Rybo713/UX330UA-macOS)             | [链接](https://github.com/Rybo713/UX330UA-macOS/blob/master/README.md) | Asus UX330UAK (Kabylake）                                    |
| Asus Zenbook UX331 | [链接](https://github.com/VortexisTV/Asus-Zenbook-UX331-Hackintosh) |  |  |
| Asus Zenbook UX450FDX             | [链接](https://github.com/xvAcid/Hackintosh_Zenbook_UX450FDX) |                                                              |                                                              |
| Asus Zenbook 3 UX490              | [链接](https://github.com/VillenaDeveloper/asus-ux490-hackintosh) |                                                              |                                                              |
| Asus ux305fa                      | [链接](https://github.com/nganhquoc95/clover-ux305fa)        |                                                              |                                                              |
| 华硕zx50jx4200                    | [链接](https://github.com/sxz799/zx50jx4200_hackintosh)      |                                                              |                                                              |
| 华硕A407UB                        | [链接](https://github.com/xinguisoft/Hackintosh-EFI-Asus-A407UB/) |                                                              |                                                              |
| 玩家国度枪神3                     | [链接](https://github.com/DongLinghe/ROG-SCAR-III-Hackintosh-EFI) |                                                              | 这个应该是华硕的吧                                           |
|                                   |                                                              |                                                              |                                                              |

### DELL 戴尔

| 机型名称                         | 发布地址                                                     | 教程地址                                                     | 备注                                                         |
| -------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Alienware 17 R4 i7-7700HQ        | [链接](https://github.com/RockJesus/Alienware-17-R4-I7-7700HQ-MacOS-High-Sierra) | [链接](https://github.com/RockJesus/Alienware-17-R4-I7-7700HQ-MacOS-High-Sierra/blob/master/README.md) | 外星人 17 R4，网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Alienware Aurora-R7              | [链接](https://github.com/jianghaizhi/DELL-Alienware-Aurora-R7-macOS) |                                                              |                                                              |
| Alienware-Aurora-R6/R7/R8        | [链接](https://github.com/jianghaizhi/DELL-Alienware-Aurora-R7-macOS) |                                                              |                                                              |
| **Alienware外星人更多机型**      | [链接](https://github.com/RockJesus/Alienware-Hackintosh)    |                                                              | 引用自：RockJesus维护的仓库                                  |
| DELL Latitude E7440              | [链接](https://github.com/ameeno/Dell-E7440-Hackintosh)      |                                                              |                                                              |
| Dell G3 3579                     | [链接](https://github.com/JiangHoumin/Dell_G3_3579_Hackintosh) [链接](https://github.com/CerteKim/Dell-G3-3579-Hackintosh-Clover) [链接](https://github.com/CerteKim/Dell-G3-3579-Hackintosh-OpenCore) <br />[链接](https://github.com/tonyleelyy/OpenCore-Hackintosh-Dell-G3-3579) [链接](https://github.com/MicalShow/DELL-G3-3579-Opencore-Big-Sur)[链接](https://github.com/VersionZKP2356/Dell-G3-3579-OpenCore-Boot-File) |                                                              | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html)；<br />链接3,4为`OpenCore`；<br />链接5支持`BigSur` |
| Dell G3 3590                     | [链接](https://github.com/shadowsss/hackintosh-Dell-3590)    |                                                              |                                                              |
| Dell G3 3779                     | [链接](https://github.com/djlucas123456/Dell-G3-3779-Mojave-Catalina-Clover-) |                                                              |                                                              |
| Dell G5 5587                     | [链接](https://github.com/Sosueyakiko/Clover_EFI-For-DELL-G5-5587) |                                                              | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html)； |
| Dell G7 7588                     | [链接](https://github.com/geraldoandradee/Hackintosh-Dell-G7-7588) [链接](https://github.com/flyfeng2002/FYQ-Hackintosh) [链接](https://github.com/Juan-VC/Hackintosh-macOS-Dell-G7-7588) |                                                              | 链接2和链接3包括`OpenCore`                                   |
| Dell Inspiron 14 5447            | [链接](https://github.com/SinhLv/Dell-Ins-14-5447-hackintosh) | [链接](https://github.com/SinhLv/Dell-Ins-14-5447-hackintosh/blob/master/README.md) | Dell-Ins-14-5447                                             |
| Dell Inspiron 14 7447            | [链接](https://github.com/Am1nCmd/Dell-Inspiron-14-7447-Pandora-Hackintosh) | [链接](https://github.com/Am1nCmd/Dell-Inspiron-14-7447-Pandora-Hackintosh/blob/master/README.md) | Dell-Inspiron-14-7447                                        |
| Dell Inspiron 15 7000 (i7-8550U) | [链接](https://github.com/athlonreg/Dell-Inspiron-15-7000-i7-8550u) |                                                              |                                                              |
| Dell Inspiron 3442               | [链接](https://github.com/kkzzhizhou/Dell-3443-Hackintosh)   | [链接](https://github.com/kkzzhizhou/Dell-3443-Hackintosh/blob/master/README.md) | Dell 3443                                                    |
| Dell Inspiron 3443               | [链接](https://github.com/kkzzhizhou/Dell-3443-Hackintosh)   |                                                              |                                                              |
| Dell Inspiron 3543               | [链接](https://github.com/arisskz6/Dell-3543-Hackintosh) [链接](https://github.com/meikeeit/Hackintosh_Dell3543) |                                                              |                                                              |
| Dell Inspiron 3559 | [链接](https://github.com/WenQinghua/dell-Inspiron-3559-EFI) | | |
| Dell Inspiron 3568               | [链接](https://github.com/YGQ8988/dell-3568)                 | [链接](https://github.com/YGQ8988/dell-3568)                 | Dell Inspiron 3568                                           |
| Dell Inspiron 3670               | [链接](https://github.com/inyan600/Dell-Inspiron-3670-Hackintosh) |                                                              |                                                              |
| Dell Inspiron 5370               | [链接](https://github.com/dreamwhite/dell-inspiron-5370-hackintosh) |                                                              |                                                              |
| Dell Inspiron 5420               | [链接](https://github.com/jasper-wan/Dell-Inspiron-5420-Hackintosh) |                                                              |                                                              |
| Dell Inspiron 5447               | [链接](https://github.com/SinhLv/Dell-Ins-14-5447-hackintosh) [链接](https://github.com/Jay-Wang-zechong/inspiron-14-5447-hacintosh-EFI-clover) |                                                              |                                                              |
| Dell Inspiron 5459               | [链接](https://github.com/lzhoang2601/Dell-Insprison-5459-Hackintosh) |                                                              |                                                              |
| Dell Inspiron 5488               | [链接](https://github.com/daggeryu/DELL-inspiron-5488)       |                                                              |                                                              |
| Dell Inspiron 5537               | [链接](https://github.com/thedeadfish59/Dell_Inspiron_5537-Hackintosh) |                                                              |                                                              |
| Dell Inspiron 5548(4528S)        | [链接](https://github.com/yuppiesnotzhuhao/Hackintosh-Dell-Inspiron-5548) |                                                              |                                                              |
| Dell Inspiron 5558	|[链接](https://github.com/jance-hui/DELL-5558-EFI)		|		|		|
| Dell Inspiron 5559               | [链接](https://github.com/cbabb/dell-5559)                   |                                                              | Dell 5559                                                    |
| Dell Inspiron 5566               | [链接](https://github.com/matheusliraofficial/inspiron-5566-hackintosh) |                                                              |                                                              |
| Dell Inspiron 5567               | [链接](https://github.com/MuntashirAkon/HackintoshDellInspiron5567) |                                                              | i3-7100u, Intel HD620                                        |
| Dell Inspiron 5570               | [链接](https://github.com/Mateo1234454545/Dell-5570-hackintosh) [链接](https://github.com/stayboogy/Hackintosh_Dell-Inspiron-5570_Catalina) |                                                              |                                                              |
| Dell Inspiron 5577               | [链接](https://github.com/imAmouse/Clover-EFI-For-Dell-5577) [链接](https://github.com/sachangregory/Dell-Inspiron-5577-Hackintosh) |                                                              |                                                              |
| Dell Inspiron 5584               | [链接](https://github.com/Hackintoshlifeit/DELL-Inspiron-5584) |                                                              |                                                              |
| Dell Inspiron 7000 系列          | [链接](https://github.com/daliansky/dell7000)                | [链接](https://github.com/daliansky/dell7000/blob/master/README.md) | Dell Inspiron 7000 I/II (7x60/7x72)<br />网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Dell Inspiron 7348               | [链接](https://github.com/MoozIiSP/dell-7348-hackintosh)     |                                                              |                                                              |
| Dell Inspiron 14 7447 Pandora    | [链接](https://github.com/Am1nCmd/Dell-Inspiron-14-7447-Pandora-Hackintosh) |                                                              |                                                              |
| Dell Inspiron 7460 和 7560       | [链接](https://github.com/xzhih/dell-7460-7560-hackintosh) [链接](https://github.com/HowieHye/Dell-7460-Hackintosh-OC) | [链接](https://github.com/xzhih/dell-7460-7560-hackintosh/blob/master/README.md) | 戴尔 7460 和 7560，网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html)<br /> |
| Dell Inspiron 7472               | [链接](https://github.com/ic005k/DELL7472)                   |                                                              | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Dell Inspiron 7472/7572          | [链接](https://github.com/lyngogogog/Dell-7472-7572-Hackintosh-EFI) |                                                              | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Dell Inspiron 7548               | [链接](https://github.com/mbrula/hackintosh-dell-inspiron)   |                                                              |                                                              |
| Dell Inspiron 7559               | [链接](https://github.com/crackself/Dell-7559-Hackintosh) [链接](https://github.com/JiangHoumin/Dell_G3_3579_Hackintosh) [链接](https://github.com/fengwenhua/dell-7559-hackintosh) | [链接](https://github.com/crackself/Dell-7559-Hackintosh/blob/Hotpatch/README.md) | Dell 7559，网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Dell Inspiron 7567               | [链接](https://github.com/Doapeat/Dell7567)                  |                                                              |                                                              |
| Dell Inspiron 7570               | [链接](https://github.com/duongle305/Dell-7570-Hackintosh)   |                                                              |                                                              |
| Dell Inspiron 7577               | [链接](https://github.com/yakimka/Hackintosh-Dell-7577) [链接](https://github.com/lersy/Dell-7577-Hackintosh-macos-Opencore) |                                                              |                                                              |
| Dell Inspiron 7580               | [链接](https://github.com/rogerioadris/hackintosh-dell-7580) [链接](https://github.com/ppjjhh/Hackintosh-Dell-Inspiron-7580) |                                                              |                                                              |
| Dell Inspiron 7590               | [链接](https://github.com/lcyf9102s/dell-inspiron7590-i5-1050-hackintosh-cloverEFI) [链接](https://github.com/Pinming/Dell-Inspiron-7590-Hackintosh-Opencore) |                                                              | 链接2支持`Big Sur`                                           |
| Dell Inspiron 7591               | [链接](https://github.com/tctien342/Dell-Inspiron-7591-Hackintosh) [链接](https://github.com/Skimige/Inspiron-759x-Hackintosh) [链接](https://github.com/Pinming/Dell-Inspiron-7590-Hackintosh-Opencore) |                                                              | 链接3支持`Big Sur`                                           |
| Dell Latitude 3440               | [链接](https://github.com/Yash-Garg/OpenCore-Latitude3440-EFI) |                                                              |                                                              |
| Dell Latitude E5270              | [链接](https://github.com/thebinh-lg051/Dell-Latitude-E5270-Hackintosh) |                                                              |                                                              |
| Dell Latitude E5290              | [链接](https://github.com/laelsirus/Dell-Latitude-5290-2-in-1-UHD620-iGPU-CLOVER) | [链接](https://github.https://github.com/laelsirus/Dell-Latitude-5290-2-in-1-UHD620-iGPU-CLOVER/blob/master/README.md) | Dell-Latitude-5290                                           |
| Dell Latitude 5290 2-in-1        | [链接](https://github.com/laelsirus/Dell-Latitude-5290-2-in-1-UHD620-iGPU-CLOVER) |                                                              |                                                              |
| Dell Latitude E5400              | [链接](https://github.com/gouiferda/dell-5400-hackintoch)    |                                                              |                                                              |
| Dell Latitude E5440              | [链接](https://github.com/soejin/hackintosh-dell-e5440)      |                                                              | Dell E5440                                                   |
| Dell Latitude E5470              | [链接](https://github.com/txt1994/dell_latitude5470_i7-6820hq) |                                                              |                                                              |
| Dell Latitude E5490              | [链接](https://github.com/lijun215021/DELL-5490-hackintosh)  |                                                              |                                                              |
| Dell Latitude E5591              | [链接](https://github.com/geowoden/DELL-Latitude-5591_osx-clover) |                                                              |                                                              |
| Dell Latitude E6330              | [链接](https://github.com/BladeScraper-Designs/Dell-Latitude-E6330-Mojave-Hackintosh-EFI) |                                                              |                                                              |
| Dell Latitude E6430              | [链接](https://github.com/kinoute/Hack-Dell-Latitude-E6430)  |                                                              |                                                              |
| Dell Latitude E7250              | [链接](https://github.com/SkyrilHD/Dell-E7250-Hackintosh)    |                                                              |                                                              |
| Dell Latitude E7280              | [链接](https://github.com/conradlyn/Hackintosh-EFI-Dell-Latitude_7280) |                                                              |                                                              |
| Dell Latitude E7370              | [链接](https://github.com/mikeTOliu/dell-latitude7370-Hackintosh-EFI-backup) [链接](https://github.com/gazzmanzx6/OC_Dell_Latitude_7370) |                                                              |                                                              |
| Dell Latitude E7390                        | [链接](https://github.com/Swung0x48/Dell-Latitude-7490-Hackintosh-EFI) |                                                              |                                                              基于 Latitude 7490。 不保证 7390 可用。（可在issue中提出7390的问题）|
| Dell Latitude E7440                        | [链接](https://github.com/ameeno/Dell-E7440-Hackintosh)      |                                                              |                                                              |
| Dell Latitude E7450                        | [链接](https://github.com/rahmadsandy/Dell-E7450-DW1530-Catalina) |                                                              |                                                              |
| Dell Latitude E7480                        | [链接](https://github.com/TranNgocKhoa/Dell-Latitude-7480-Hackintosh) |                                                              |                                                              |
| Dell Latitude E7490                        | [链接](https://github.com/Swung0x48/Dell-Latitude-7490-Hackintosh-EFI) |                                                              |                                                              |
| Dell OptiPlex 3050                         | [链接](https://github.com/Leif160519/Dell-OptiPlex-3050-EFI) | [链接](https://github.com/Leif160519/Dell-OptiPlex-3050-EFI/blob/master/README.md) |                                                              |
| Dell OptiPlex 3060                         | [链接](https://github.com/Drovosek01/hackintosh_DELL_OptiPlex_3060_i5-8500) |                                                              |                                                              |
| Dell OptiPlex 3060 MFF                     | [链接](https://github.com/Hackintoshlifeit/DELL-Optiplex-3060-MFF) |                                                              |                                                              |
| Dell Optiplex 7020                         | [链接](https://github.com/zearp/optimac)                     |                                                              |                                                              |
| Dell OptiPlex 7070 mff                     | [链接](https://github.com/liaoyudong2/Dell-7070-mff-hackintosh) |                                                              |                                                              |
| Dell OptiPlex 7070 SFF                     | [链接](https://github.com/webleon/Hackintosh-OptiPlex-7070-SFF) |                                                              |                                                              |
| Dell OptiPlex 9020                         | [链接](https://github.com/kyroschow/Dell-Optiplex-9020-Hackintosh-Clover-EFI) |                                                              |                                                              |
| Dell OptiPlex 9020 OpenCore                | [链接](https://github.com/li3p/dell-optiplex-9020-hackintosh-opencore) | [链接](https://github.com/li3p/dell-optiplex-9020-hackintosh-opencore/blob/master/README.md) | 支持MT/SFF/USFF/Micro所有机型                                |
| Dell Precision 5510                        | [链接](https://github.com/soulomoon/Dell-Precision-5510-OSX) [链接](https://github.com/PLChinDev/Dell-Precision-5510-Mojave) |                                                              | Dell-Precision-5510<br />链接2支持`Catalina`                 |
| Dell Precision 5591                        | [链接](https://github.com/n0faith/Dell-Precision-5591-Hackintosh) |                                                              |                                                              |
| Dell Precision M3800<br />Dell XPS 15-9530 | [链接](https://github.com/syscl/M3800)                       | [链接](https://github.com/syscl/M3800/blob/M3800/README.md)  | Dell M3800 和 XPS 9530                                       |
| Dell Vostro 3490                           | [链接](https://github.com/FaneCH/Vostro-3490-hackintosh)     |                                                              | I5-10210u                                                    |
| Dell Vostro 3578                           | [链接](https://github.com/ABCDFAS/dell-vostro-3578-hackintosh-clover-efi) |                                                              |                                                              |
| Dell Vostro 5370                           | [链接](https://github.com/hellmonky/Hackintosh/tree/master/dell-vostro-5370) |                                                              |                                                              |
| Dell Vostro 5471                           | [链接](https://github.com/Hackintoshlifeit/DELL-Vostro-5471) |                                                              |                                                              |
| Dell Vostro 14 5490                      | [链接](https://github.com/msdnna/Dell-Vostro-14-5490-Hackintosh) |                                                              | i5-10210U / **i7-10510U**                                    |
| Dell Vostro 5568 | [链接](https://github.com/dungnt11/dell-5568-efi-10.15.6) | |  |
| Dell Vostro 5581                           | [链接](https://github.com/nghetienhiep/Dell-Vostro-5581-Hackintosh) |                                                              |                                                              |
| Dell XPS 15 7590                           | [链接](https://github.com/daliansky/XPS15-7590-Hackintosh)[OC版,维护的比较用心](https://github.com/gorquan/OC-XPS-7590)   |                                                              | Dell XPS 15 7590，网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Dell XPS13  9343                           | [链接](https://github.com/SiGae/macOS-Mojave-on-xps-13-9343) | [链接](https://github.com/haos001/XPS13-9343-Clover)         |                                                              |
| Dell XPS 9350                              | [链接](https://github.com/syscl/XPS9350-macOS)               | [链接](https://github.com/syscl/XPS9350-macOS/blob/master/README.md) | Dell XPS 9350                                                |
| Dell XPS 9360                              | [链接](https://github.com/hoanX/xps13-9360-i7-7560u)         | [链接](https://github.com/hoanX/xps13-9360-i7-7560u/blob/master/README.md) | Dell XPS 9360，网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Dell XPS 9360                              | [链接](https://github.com/ymmshi/XPS-9360) [链接](https://github.com/MasonGao/XPS-9360-Hackintosh) <br />[链接](https://github.com/the-marcus/XPS-9360-hackintosh) [链接](https://github.com/the-darkvoid/XPS9360-macOS) <br />[链接](https://github.com/0xHJK/XPS13-9360-i5-8250U-macOS) [链接](https://github.com/samuelshi/XPS13-9360) | [链接](https://github.com/ymmshi/XPS-9360/blob/master/README.md) | Dell XPS 9360，网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Dell XPS 9370                              | [链接](https://github.com/jieelin/XPS9370-Hackintosh)        |                                                              |                                                              |
| Dell XPS 9380                              | [链接](https://github.com/wdubaiyu/Hackintosh-Dell-XPS-9380) |                                                              |                                                              |
| Dell XPS 9530                              | [链接](https://github.com/the-darkvoid/XPS9530-OSX/tree/10.13) | [链接](https://www.tonymacx86.com/threads/guide-dell-xps-9530-clover-uefi-hotpatch.235558/) | XPS 9530                                                     |
| Dell XPS 9550                              | [链接](https://github.com/wmchris/DellXPS15-9550-OSX) [链接](https://github.com/corenel/XPS9550-macOS)[链接](https://github.com/xxxzc/xps15-9550-macos) | [链接](https://github.com/wmchris/DellXPS15-9550-OSX/blob/10.14/README.md) [链接](https://github.com/corenel/XPS9550-macOS/blob/master/README.md) | Dell XPS 9550                                                |
| Dell XPS 9559                              | [链接](https://github.com/darwinboaventura/Dell-XPS-9559-EFIs) |                                                              |                                                              |
| Dell XPS 9560                              | [链接](https://github.com/gunslinger23/XPS15-9560-High-Sierra) | [链接](https://github.com/gunslinger23/XPS15-9560-High-Sierra/blob/master/README.md) | Dell XPS 9560，网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Dell XPS 9570                              | [链接](https://github.com/Xigtun/xps-9570-mojave) [链接](https://github.com/bavariancake/XPS9570-macOS) <br />[链接](https://github.com/LuletterSoul/Dell-XPS-15-9570-macOS-Mojave) |                                                              | 感谢：[LuletterSoul](https://github.com/LuletterSoul)，网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |

### Gigabyte 技嘉

| 机型名称           | 发布地址                                                 | 教程地址                                                     | 备注 |
| ------------------ | -------------------------------------------------------- | ------------------------------------------------------------ | ---- |
| Gigabyte Aero 15X  | [链接](https://github.com/zacmks/Hackintosh-Aero-15X)    | [链接](https://github.com/zacmks/Hackintosh-Aero-15X/blob/master/README.md) |      |
| Gigabyte Aero 15W  | [链接](https://github.com/Errrneist/Hackintosh-Aero-15W) |                                                              |      |
| Gigabyte Sabre 15K | [链接](https://github.com/gnehs/Sabre15KClover)          |                                                              |      |

### Hasse 神舟

| 机型名称                    | 发布地址                                                     | 教程地址                                           | 备注                                                         |
| --------------------------- | ------------------------------------------------------------ | -------------------------------------------------- | ------------------------------------------------------------ |
| 神舟A480B                   | [链接](https://github.com/wklxd/A480B)                       |                                                    |                                                              |
| 战神 K610D-i5D3             | [链接](https://github.com/1zilc/K610d-i5-d3-10.14.5-efi-clover) |                                                    |                                                              |
| 战神 K650D                  | [链接](https://github.com/wklesss/k650D-Hackintosh)          |                                                    | 战神 K650D                                                   |
| 战神 K650D-SL5S1            | [链接](http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1800662) | [链接](https://blog.nyaasu.top/front-end/111.html) | EFI文件部分有效，无线网卡和电池无法驱动                      |
| 战神 K650D-i5D2             | [链接](https://github.com/ivothgle/Hackintosh)               |                                                    |                                                              |
| 战神 K680E-G6D1             | [链接](https://github.com/Vnzen/Hackintosh_hasee_k680e-g6d1_clover) |                                                    |                                                              |
| 战神 K770E-i7D1             | [链接](https://github.com/Gitawake/Hasee-K770e-i7-D1-Clover) |                                                    | 准系统型号：蓝天 P170SM-A                                    |
| 战神 Z6-SL5D1               | [链接](https://github.com/Measureless/Hackintosh_Hasee_Z6-SL5D1) |                                                    | 准系统型号： 蓝天 	N151RD-HM170                           |
| 战神 Z7-KP7D1 <br> Z7-KP7S1 | [链接](https://github.com/ConnersHua/Clevo-P65xHP-Hackintosh) [链接](https://github.com/hevervie/Hackintosh_HASEE_Z6-KP7S1) |                                                    | 准系统型号：蓝天 P65xHP                                      |
| 战神 Z7-SP5D1               | [链接](https://github.com/moonheart/Hackintosh-P65xRP6-Z7-SP5D1) |                                                    |                                                              |
| 战神 Z7(M)-KP7/5GZ          | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)  | 准系统型号：同方 GK5CN6X, GK5CN5X                            |
| 战神 Z7(M)-KP7/5Z           | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)  | 准系统型号：同方 GK5CN6X, GK5CN5X                            |
| 战神 Z7-KP7EC               | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)  | 准系统型号：同方 GJ5CN64                                     |
| 战神 Z7(M)-KP7/5GC          | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)  | 准系统型号：同方 GJ5CN64, GI5CN54, by @kirainmoe             |
| 战神 Z7M-KP5GC              | [链接](https://github.com/CharlesZhou959/Hasee-Z7M-KP5GC-Hackintosh) |                                                    | 准系统型号：同方 GI5CN54, by @CharlesZhou959                 |
| 战神 Z7(M)-KP7/5GA          | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)  | 准系统型号：同方 GJ5CN64, GI5CN54                            |
| 战神 Z7(M)-KP7/5GE          | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)  | 准系统型号：同方 GJ5CN64, GI5CN54                            |
| 战神 Z7(M)-KP7/5GH          | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)  | 准系统型号：同方 GJ5CN64, GI5CN54                            |
| 战神 Z7-CT7/5GK             | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)  | 准系统型号：同方 GK5CP6X                                     |
| 战神 Z7M-CT7GS              | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)  | 准系统型号：同方 GK5CP5X                                     |
| 战神 Z7(M)-CT7/5GA          | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)  | 准系统型号：同方 GK5CP6V, GK5CP5V                            |
| 战神 Z7(M)-CT7/5VH          | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)  | 准系统型号：同方 GK5CP6V, GK5CP5V                            |
| 战神 G7-CT7VK               | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)  | 准系统型号：同方 GK7CP6R                                     |
| 战神 G7-CT7RA               | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)  | 准系统型号：同方 GK7CP6R                                     |
| 战神 Z7(M)-CT7/5NA          | [链接](https://github.com/bufsnake/Z7-CT7NA-HackIntosh)      |                                                    | 准系统型号：	蓝天 NH50Rx                                  |
| 战神 Z7(M)-CT7/5NA (NK/NT)  | [链接](https://github.com/a328661276/Clevo-NH50-NH70-Hackintosh-macOS10.15.3) |                                                    | 准系统型号：蓝天 NH5xRD/RC/RA/RH(Q)                          |
| 战神 G7-CT7NA (NK/NT)       | [链接](https://github.com/a328661276/Clevo-NH50-NH70-Hackintosh-macOS10.15.3) |                                                    | 准系统型号：蓝天 NH70RD_RC_RA_RH(Q)                          |
| 战神 G8-CT7NA (NK/NT)       | [链接](https://github.com/a328661276/Clevo-NH50-NH70-Hackintosh-macOS10.15.3) |                                                    | 准系统型号：蓝天 NH70RD_RC_RA_RH(Q)                          |
| 战神 GX8-CP5/CR6            | [链接](https://github.com/JokerHYC/P775TM-HACKINTOSH)        |                                                    | 准系统型号：蓝天 P775TM <br>     未来人类X711，炫龙V87等使用蓝天 p775tm 模具的 10 系显卡都支持 |
| 战神Z6-KP7S1                | [链接](https://github.com/hevervie/Hackintosh_HASEE_Z6-KP7S1) |                                                    |                                                              |
| 战神 ZX7-CP5SC              | [链接](https://github.com/bavelee/NB5TK1_TJ1-Hackintosh/)    | [链接](https://bavelee.cn/archives/60.html)        | 准系统型号：蓝天 NB50/60 TJ1/TK1                             |
| 战神 ZX6-CP5S1              | [链接](https://github.com/bavelee/NB5TK1_TJ1-Hackintosh/)    | [链接](https://bavelee.cn/archives/60.html)        | 准系统型号：蓝天 NB50/60 TJ1/TK1                             |
| 战神 K680E-G6E3/G6D3        | [链接](https://github.com/bavelee/NB5TK1_TJ1-Hackintosh/)    | [链接](https://bavelee.cn/archives/60.html)        | 准系统型号：蓝天 NB50/60 TJ1/TK1                             |
| 战神 TX7-CT5DS              | [链接](http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1843619&highlight=%C9%F1%D6%DB) |                                                    | 准系统型号：蓝天 N960TC                                      |
| 战神Z7M-KP7GT              | [链接](https://github.com/Xin9912/Hackintosh) |                                                    |                                       |
| Hases-z7-kp7sc              | [链接](https://github.com/Bluestar-coder/Hases-z7-kp7sc-10.15.4-OC) |                                    |                             |
| 精盾 T96E                   | [链接](https://github.com/L0ngxhn/Hackintosh-Hasee-T96E)     |                                                    | 准系统型号：蓝天 P950EP6                                     |
| 精盾 K590S                  | [链接](https://github.com/JokerHYC/K590S-HACKINTOSH)         |                                                    | 准系统型号：	蓝天 W350ET                                  |
| 战神Z7(M)-CT7(5NA/NK/NT)/G7/G8-CT7-NA-NK                 | [链接](https://github.com/MichaelPan1026/Clevo-NH50-NH70-Hackintosh)         |                                                    | 准系统型号：	蓝天 NH50,NH70Rx系列，这命名太他喵的乱了                                  |



### HP 惠普

| 机型名称                                      | 发布地址                                                     | 教程地址                                                     | 备注                                                         |
| --------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| HP ProBook/EliteBook<br />ZBook 系列          | [链接](https://github.com/RehabMan/HP-ProBook-4x30s-DSDT-Patch) | [链接](https://www.tonymacx86.com/threads/guide-hp-probook-elitebook-zbook-using-clover-uefi-hotpatch.261719/) | 除 8x60W,8x70W 系列之外的机型，<br />二代 CPU 及之前的机型仅支持到 10.13.x |
| HP Envy Haswell J/K/Q/N<br />系列笔记本       | [链接](https://github.com/RehabMan/HP-Envy-DSDT-Patch)       | [链接](https://www.tonymacx86.com/threads/guide-hp-envy-haswell-series-j-k-q-n-using-clover-uefi.261724/) | 仅 4 代 envy 机型                                            |
| HP 15 D062TU                                  | [链接](https://github.com/trqukhanh0104/hp-15-d062tu-hackintosh) [链接](https://github.com/khanhtran-cse/hp-15-d062tu-hackintosh) |                                                              |                                                              |
| HP Laptop 14S-DQ1013TU                        | [链接](https://github.com/ferdy42id/hackintosh-14s-dq1013tu) |                                                              |                                                              |
| HP Laptop 15-da0233ur                         | [链接](https://github.com/DmitriyyyyS/Hackintosh-HP-Laptop-15-da0233ur) |                                                              | i3-7020U                                                     |
| HP 17 BY0062ST                                | [链接](https://github.com/emilevirus/HP-BY00000-HACKINTOSH)  |                                                              |                                                              |
| HP Envy 13 ad024TU                            | [链接](https://github.com/Astrobr/HackintoshForEnvy13-ad0xx) |                                                              |                                                              |
| HP Envy 13 ad1xxx                             | [链接](https://github.com/ArisHub/Hackintosh_Envy13_10.13.6-10.14.4) | [链接](https://github.com/ArisHub/Hackintosh_Envy13_10.13.6/blob/master/README.md) | 惠普 envy13                                                  |
| HP Envy 13 model ah0002la                     | [链接](https://github.com/jomarnavarro/hp-envy-clover)       |                                                              |                                                              |
| HP Envy15 as109tu                             | [链接](https://github.com/TianNes/Hackintosh-Clover)         |                                                              |                                                              |
| HP Envy 15 as110tu                            | [链接](https://github.com/wing-ho/HP-AS110TU-Hackintosh)     |                                                              |                                                              |
| HP Envy x360 15-aq160sa                       | [链接](https://github.com/KaylumJ/Hackintosh-HP-Envy-x360)   |                                                              |                                                              |
| HP Envy DV6 7303ef                            | [链接](https://github.com/TehOrange/hackintosh_configs/tree/master/HP-Envy-DV6-7303ef) |                                                              |                                                              |
| HP Omen AX205                                 | [链接](https://github.com/donxp/HP-OMEN-AX205-HACKINTOSH)    |                                                              |                                                              |
| Hp Omen Ce020tx                               | [链接](https://github.com/thanatath/hp-omen-ce020tx-mojave-osx) |                                                              |                                                              |
| HP Omen Laptop 15-ce0xx                       | [链接](https://github.com/shimakazechan/OMEN-by-HP-Laptop-15-ce007TX-Hackintosh) [链接](https://github.com/t-shao/-Hackintosh-OMEN_by_HP_Laptop_15-ce0xx) |                                                              |                                                              |
| HP 250 G2                                     | [链接](https://github.com/MrPotatoBobx/hp250g2opencore)      |                                                              |                                                              |
| HP 250 G6                                     | [链接](https://github.com/snajdovski/HP-250-G6-Mojave-EFI)   |                                                              |                                                              |
| HP 348 G5                                     | [链接](https://github.com/zsakvo/hp-348-g5-hackintosh)       |                                                              |                                                              |
| HP Probook 430 G5                             | [链接](https://github.com/asafscode/HP-Probook-430-G5-Hackintosh) [链接](https://github.com/GoProgrammer/HP-Probook-430-G5-Hackintosh) |                                                              |                                                              |
| HP ProBook 430 G6                             | [链接](https://github.com/YGQ8988/HP-ProBook430G6)           |                                                              | i5-8265U 已卸载内置镁光nvme SSD(此硬盘不识别)                |
| HP ProBook 440 G2                             | [链接](https://github.com/Chexier/HP440-hackintosh)          |                                                              |                                                              |
| HP ProBook 650 G1                             | [链接](https://github.com/Hologos/hackintosh-hp-probook-650-g1) |                                                              |                                                              |
| HP 840-G1                                     | [链接](https://github.com/blint01/hackintosh-mojave-HP-840-G1) | [链接](https://github.com/blint01/hackintosh-mojave-HP-840-G1/blob/master/README.md) |                                                              |
| HP Elitebook 840 G2                           | [链接](https://github.com/AktasC/Hackintosh-Elitebook-840-G2-Broadwell) |                                                              |                                                              |
| HP EliteBook 840 G3                           | [链接](https://github.com/GGorAA/Hackintosh-840)             |                                                              | Big Sur                                                      |
| HP prodesk 600g1-DM/800g1-DM			| [链接](https://github.com/LomotHo/Hackintosh-600g1-DM-4670t)	|[链接](https://github.com/LomotHo/Hackintosh-600g1-DM-4670t/blob/master/README-zh.md)			|		|
| HP Pavilion 15-au028ur                        | [链接](https://github.com/Drovosek01/hackintosh_HP_Pavilion_15-au028ur_i5-6200U/blob/master/docs/ENG/README.md) |                                                              |                                                              |
| HP Pavilion 15 au067tx                        | [链接](https://github.com/FzeNiX/HPPavilion15-au067tx-Mojave-Hackintosh) |                                                              |                                                              |
| HP Pavilion15 AU157TX                         | [链接](https://github.com/sxrhd/HP-AU157TX-EFI)              |                                                              |                                                              |
| HP Pavillion ck069tx                          | [链接](https://github.com/Blizzard57/Hackintosh)             |                                                              |                                                              |
| HP Pavilion 15 cs1xxx                         | [链接](https://github.com/JaeSeoKim/HP-Pavilion-Laptop-15-cs1xxx-Hackintosh) |                                                              |                                                              |
| Hp Spectre X360                               | [链接](https://github.com/Just-maple/Hp-spectre-X360-hackintosh) |                                                              |                                                              |
| HP Spectre X360 15-bl112dx                    | [链接](https://github.com/WoadZS/HP-Spectre-X360-15-Hackintosh) |                                                              |                                                              |
| HP Spectre X360 13 late 2018                  | [链接](https://github.com/SeptemberHX/HP-Spectre-X360-13-late-2018-Hackintosh) |                                                              |                                                              |
| EliteDesk 800-G3-Mini                         | [链接](https://github.com/francoisminh/Hackintosh-EliteDesk-800-G3-Mini-65W) | [链接](https://github.com/francoisminh/Hackintosh-EliteDesk-800-G3-Mini-65W/blob/master/README.md) |                                                              |
| HP Zhan 66 Pro G1                             | [链接1](https://github.com/A-Linz/Hackintosh-HP-Zhan-66-Pro-G1) [链接2](https://github.com/RenAmamiya/HP-Zhan-66-Pro-G1) |                                                              |                                                              |
| HP ZHAN 66 PRO 14 G2                          | [链接](https://github.com/peihexian/HP-ZHAN-66-Pro-14-G2)    |                                                              |                                                              |
| HP ZHAN99 WorkStation G1                      | [链接](https://github.com/MacsedProtoss/hackintosh)          |                                                              | HP ZBook 15v G5                                              |
| 暗影精灵4 i5-8300H GTX1050Ti                  | [链接](https://github.com/canwdev/omen15dc-hackintosh) [OC版](https://github.com/ReekyStive/hp-omen-15-hackintosh)       |                                                              |                                                              |
| 暗影精灵2                                     | [链接](https://github.com/Arecall/-Mac-os)                   |                                                              |                                                              |
| 惠普暗影精灵2 15-ax015TX                      | [链接](https://github.com/a13134455667/HP-15-ax015TX-MAC10.15.4-OC-EFI) |                                                              | OpenCore 0.6.0 / Big Sur                                     |
| 暗影精灵 II 代Pro <br />HP OMEN 15-ax214TX    | [链接](https://github.com/ZGGSONG/HP-OMEN-15-ax214TX-Hackintosh) |                                                              |                                                              |
| 暗影精灵2 Pro HP OMEN 15-ax225TX              | [链接](https://github.com/Cruii/HP-OMEN-15-ax225TX) [链接](https://github.com/XStar-Dev/HP_OMEN-2Pro_Hackintosh) |                                                              |                                                              |
| HP暗影精灵3                                   | [链接](https://github.com/bessyjl/HP-OMEN-3-Hackintosh)      |                                                              | 还有挖坑的，看看啥时候能埋人                                 |
| 惠普光影精灵3(HP Pavilion 15-cb0xx)           | [链接](https://github.com/zty199/HP_Pavilion_15-cb073tx_Hackintosh) |                                                              | 希望能继续维护                                               |
| 暗影精灵I (惠普PAVILION Gaming NB 15-ak039TX) | [链接](https://github.com/lgs3137/PAVILION_Gaming_NB-macOS)  |                                                              | 除了独显、Intel无线网卡，其他功能模块正常(包括HDMI视频)      |
| HP Pavillion Gaming Laptop 15-cx0xxx          | [链接](https://github.com/mechtifs/hackintosh-clover-hp-pavillion-15-cx0xxx) |                                                              | 光影精靈4代                                                  |
| 惠普光影精靈5                                 | [链接](https://github.com/Tonymiugrey/Garden-by-miugrey)     |                                                              | 內含搞定PM981的補丁，可以試試                                |
| HP Omen 15 DC                                 | [链接](https://github.com/kirainmoe/hp-omen15-dc-macos)      |                                                              | 暗影精灵 4 GTX1060 144Hz 版，由于物理屏蔽核显，只能安装 10.13.6 |

### Huawei 华为

| 机型名称                 | 发布地址                                                     | 教程地址                                                     | 备注                                                         |
| ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 华为 Matebook X Pro 2019 | [链接](https://github.com/laozhiang/MateBook_X_Pro_2019-Hackintosh) | [链接](https://github.com/laozhiang/MateBook_X_Pro_2019-Hackintosh) | 华为 Matebook X Pro 2019                                     |
| 华为 Matebook X Pro      | [链接](https://github.com/gnodipac886/MatebookXPro-hackintosh) [链接](https://github.com/gnodipac886/MatebookXPro-hackintosh) | [链接](https://github.com/gnodipac886/MatebookXPro-hackintosh/blob/master/README-CN.md) | 华为 Matebook X Pro 2018                                     |
| 华为 Matebook X          | [链接](https://github.com/4323770/Hackintosh-For-Matebook-X) |                                                              |                                                              |
| 华为 Matebook 13         | [链接](https://github.com/FIU001/huawei-matebook-13-) [链接](https://github.com/Edoardo001/Matebook-13-Hackintosh)<br />[链接](https://github.com/ske1996/matebook-13-2019-oc-efi) |                                                              |                                                              |
| 华为 Matebook 14         | [链接](https://github.com/frezs/MateBook14-Hackintosh)       |                                                              |                                                              |
| 华为 Matebook D          | [链接](https://github.com/MOJUNSHOU/MateBooK-D) [链接](https://github.com/Zero-zer0/Matebook_D_2018_Hackintosh_OpenCore) |                                                              | 华为MateBook D2018 i5-8250U 15.6寸<br />网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| 荣耀 Magicbook           | [链接](https://github.com/hjmmc/Honor-Magicbook) [链接](https://github.com/buseQ/magicbook-hackintosh-opencore-i7-8550u) | [链接](https://github.com/hjmmc/Honor-Magicbook/blob/master/README_CN.md) | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| 荣耀 Magicbook-Pro-16.1  | [链接](https://github.com/GatesYang/Magicbook-Pro-16.1-Hackintosh) |                                                              |                                                              |
| 华为 Matebook 14 2020款  | [链接](https://github.com/Zero-zer0/Matebook_13_14_2020_Hackintosh_OpenCore) |                                                              | 华为 Matebook 13 / 14 2020 十代 通用                         |

### Lenovo 联想

| 机型名称                           | 发布地址                                                     | 教程地址                                                     | 备注                                                         |
| ---------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Lenovo Flex 15                     | [链接](https://github.com/aytic/Lenovo-Flex-15-Hackintosh)   | [链接](https://github.com/aytic/Lenovo-Flex-15-Hackintosh/blob/master/README.md) | Lenovo Flex 15                                               |
| Lenovo Ideapad S145-15IWL          | [链接](https://github.com/boffik/LenovoS145-15IWL_OpenCore)  |                                                              |                                                              |
| Lenovo Ideapad 310-14IKB           | [链接](https://github.com/29satnam/LenovoHackintosh)         | [链接](https://github.com/29satnam/LenovoHackintosh/blob/master/README.md) |                                                              |
| Lenovo Ideapad 320-15ISK           | [链接](https://github.com/gajjartejas/Lenovo-Ideapad-320-15ISK-Laptop-Hackintosh) |                                                              |                                                              |
| Lenovo Ideapad 330s-14IKB          | [链接](https://github.com/chrisru26/LenovoIdeapad330s-14ikb-Hackintosh) |                                                              |                                                              |
| Lenovo Ideapad S340                | [链接](https://github.com/4mitabh/Ideapad_S340) [链接](https://github.com/IvanAleksandrov94/Lenovo-s340-Big-Sur-OpenCore-i5-8265u) |                                                              |                                                              |
| Lenovo Ideapad 510-15IKB           | [链接](https://github.com/trgcyln/Lenovo-Hackintosh)         |                                                              |                                                              |
| Lenovo Ideapad 700-15ISK           | [链接](https://github.com/athlonreg/Lenovo-XiaoXin700-15ISK) | [链接](https://github.com/athlonreg/Lenovo-XiaoXin700-15ISK/blob/master/README.md) | Lenovo-XiaoXin700-15ISK                                      |
| Lenovo Ideapad 720s 13IKB          | [链接](https://github.com/xiaominglei001/ideapad-720s-13IKB) |                                                              | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Lenovo Flex 3-1580                 | [链接](https://github.com/gdllzkusi/Lenovo-Fex3-1580-hackintosh) |                                                              |                                                              |
| Lenovo G40-70M                     | [链接](https://github.com/jinmu333/Lenovo_G40_70M_EFI)       |                                                              |                                                              |
| Lenovo G400                        | [链接](https://github.com/autersu/Lenovo_G400_EFI)           |                                                              |                                                              |
| Lenovo G480                        | [链接](https://github.com/KoenZhang/Lenovo-G480-EFI-OpenCore) |                                                              |                                                              |
| Lenovo G50-80                      | [链接](https://github.com/upupming/Lenovo-G50-80-Clover)     |                                                              |                                                              |
| Lenovo G510                        | [链接](https://github.com/Z39/G510-OS-X-Clover-Hotpatch)     | [链接](https://github.com/Z39/G510-OS-X-Clover-Hotpatch/blob/master/README-CN.md) | 感谢：[39军小兵张](http://i.pcbeta.com/space-uid-4472739.html) |
| 联想flex3-1470/i5 5200u-hd5500     | [链接](https://github.com/xl120022/FLEX-3-1470-Mac-10.15.3-efi) |                                                              |                                                              |
| ThinkPad E440                      | [链接](https://github.com/ZzMark/Thinkpad-E440-Hackintosh)   |                                                              |                                                              |
| ThinkPad E450C                     | [链接](https://github.com/zhangxuan1340/Hackintosh_E450C)    |                                                              |                                                              |
| ThinkPad E470                      | [链接](https://github.com/y010204025/E470-clover)            |                                                              |                                                              |
| ThinkPad E480                      | [链接](https://github.com/aliyoge/Hackintosh-ThinkPad-E480)  | [链接](https://github.com/aliyoge/Hackintosh-ThinkPad-E480/blob/master/README.md) |                                                              |
| ThinkPad E490                      | [链接](https://github.com/dievdmitry/Thinkpad-E490-hackintosh) |                                                              |                                                              |
| ThinkPad E540                      | [链接](https://github.com/wwbhl/E540)                        |                                                              |                                                              |
| ThinkPad E550                      | [链接](https://github.com/the-braveknight/Lenovo-ThinkPad-E550-DSDT-Patch) | [链接](https://www.tonymacx86.com/threads/guide-lenovo-thinkpad-e550-haswell-using-clover-uefi-10-11.214675/) | E550 四代 CPU                                                |
| ThinkPad E560                      | [链接](https://github.com/rsdev69/Lenovo-E560-Clover)        | [链接](https://www.tonymacx86.com/threads/stable-lenovo-e560-full-work.248842/) |                                                              |
| ThinkPad E570                      | [链接](https://github.com/SysConKonn/E570-Hackintosh)        | [链接](https://www.tonymacx86.com/threads/stable-lenovo-e560-full-work.248842/) |                                                              |
| ThinkPad L440                      | [链接](https://github.com/BesnikRrustemi/Lenovo-ThinkPad-L440) |                                                              |                                                              |
| ThinkPad L490                      | [链接](https://github.com/twislyn/Hackintosh-ThinkPad-L490)  | [链接](https://github.com/twislyn/Hackintosh-ThinkPad-L490/blob/master/README.md) |                                                              |
| Lenovo miix 520                    | [链接](https://github.com/acai66/lenovo-miix-520-hackintosh-10.14-CLOVER) |                                                              |                                                              |
| ThinkPad P51                       | [链接](https://github.com/MirkoCovizzi/thinkpad-p51-hackintosh) | [链接](https://github.com/MirkoCovizzi/thinkpad-p51-hackintosh/blob/master/README.md) | Thinkpad P51                                                 |
| ThinkPad P52                       | [链接](https://github.com/liuyishengalan/ThinkPad-P52-Hackintosh-10.14.X-)  [P52/P53/P72/P73](https://github.com/liuyishengalan/ThinkPad-P52-P53-P72-P73-Hackintosh-10.15.x) |                                                              | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| 锐 7000                            | [链接](https://github.com/839891627/Lenovo_RUI7000_Hackintosh) |                                                              | 联想 80WB 笔记本电脑                                         |
| ThinkPad S1 2017                   | [链接](https://github.com/bugprogrammer/hackintosh/tree/ThinkPad-S1-2017) |                                                              | ThinkPad S1 2017                                             |
| ThinkPad S1 2018                   | [链接](https://github.com/bugprogrammer/hackintosh/tree/ThinkPad-S1-2018) |                                                              | ThinkPad S1 2018                                             |
| ThinkPad T420 系列                 | [链接](https://github.com/tluck/Lenovo-T420-Clover)          | [链接](https://www.insanelymac.com/forum/topic/285678-lenovo-thinkpad-t420-with-uefi-only/?page=20&tab=comments#comment-1952283) | 包含 T420、T420s、T520、X220X220，<br />可通过修改支持到 10.14.x |
| ThinkPad T430                      | [链接](https://github.com/hai666l/T430-EFI)                  |                                                              |                                                              |
| ThinkPad T430s                     | [链接](https://github.com/hunga1ok/hackintosh-t430si7vga-clover-config) |                                                              |                                                              |
| ThinkPad T440s                     | [链接](https://github.com/thebinh-lg051/ThinkPad-T440s-Hackintosh) |                                                              |                                                              |
| ThinkPad T440p                     | [链接](https://github.com/evy0311/t440p) [链接](https://github.com/jloisel/t440p) [链接](https://github.com/notthebee/t440p-hackintosh) | [链接](https://github.com/evy0311/t440p/blob/master/README.md) |                                                              |
| ThinkPad T450                      | [链接](https://github.com/jsassu20/ThinkPad-T450-Mojave)     |                                                              |                                                              |
| ThinkPad T450s                     | [链接](https://github.com/EchoEsprit/Hackintosh-Catalina-OpenCore-Lenovo-T450s-efi) [链接](https://github.com/jianzhao0806/ThinkPad-T450S-Hackintosh) |                                                              |                                                              |
| ThinkPad T460 系列                 | [链接](https://github.com/tluck/Lenovo-T460-Clover)          | [链接](http://www.insanelymac.com/forum/topic/315451-guide-lenovo-t460-macos-with-clover/) | 可支持 T460、T560、T470<br /> 和 T470p4 款机型               |
| ThinkPad T460p                     | [链接](https://github.com/totemofwolf/Thinkpad-T460p-OSX-EFI) |                                                              |                                                              |
| ThinkPad T460s                     | [链接](https://github.com/nicogig/T460s-Clover) [链接](https://github.com/simprecicchiani/Thinkpad-T460s-macOS-OpenCore) |                                                              |                                                              |
| Thinkpad T470                      | [链接](https://github.com/nguyenduy98/Hackintosh) [链接-OC](https://github.com/evlon/t470p-oc) |                                                              | I7-7500u                                                     |
| Thinkpad T470S                     | [链接](https://github.com/Altairko/Lenovo-T470s-Clover) [链接](https://github.com/YBN-JUAN/T470s-OpenCore-EFI) |                                                              | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) `00JT494`联想版 |
| ThinkPad T470p                     | [链接](https://github.com/lohcve/EFI_T470P)                  | [链接](https://github.com/lohcve/EFI_T470P/blob/master/README.md) | ThinkPad T470p                                               |
| ThinkPad T480                      | [链接](https://github.com/rhkjyn/T480-Hackintosh-FULL)       |                                                              | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| ThinkPad T480s                     | [链接](https://github.com/kk1987/T480s-hackintosh)           | [链接](https://github.com/kk1987/T480s-hackintosh/blob/master/README.md) | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| ThinkPad T480s                     | [链接](https://github.com/kk1987/T480s-hackintosh) [链接](https://github.com/linusyang92/macOS-ThinkPad-T480s) <br />[链接](https://github.com/samuelshi/Thinkpad-T480S) | [链接](https://github.com/linusyang92/macOS-ThinkPad-T480s/blob/master/README.md) [链接](https://github.com/kk1987/T480s-hackintosh/blob/master/README.md) | ThinkPad T480s<br />网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| ThinkPad T530                      | [链接](https://github.com/m1qnet/ThinkPad-T530-Hackintosh)   |                                                              |                                                              |
| ThinkPad T570                      | [链接](https://github.com/zxr615/ThinkPadT570_EFI)           |                                                              |                                                              |
| ThinkPad T580                      | [链接](https://github.com/CrazyPegAsus/ThinkPad-T580-Hackintosh) |                                                              | 鸣谢：[CrazyPegasus](https://github.com/CrazyPegasus)        |
| Lenovo U330/U430/U530 系列         | [链接](https://github.com/RehabMan/Lenovo-U430-Touch-DSDT-Patch) | [链接](https://www.tonymacx86.com/threads/guide-lenovo-ideapad-u330-u430-u530-using-clover-uefi.261722/) |                                                              |
| Lenovo V1000                       | [链接](https://github.com/LiuJiangshan/Lenovo-V1000-FHD)     |                                                              | 联想小新笔记本V1000 FHD                                      |
| Lenovo V3000                       | [链接](https://github.com/Xc2333/Hackintosh-Lenovo-v3000-ISE) | [链接](https://github.com/Xc2333/Hackintosh-Lenovo-v3000-ISE/blob/master/README.md) | Lenovo V3000                                                 |
| Lenovo V310 15iKB                  | [链接](https://github.com/jacobmesier/V310-Hackintosh)       |                                                              |                                                              |
| Lenovo V330 15IKB                  | [链接](https://github.com/BesnikRrustemi/Lenovo-V330-15IKB)  | [链接](https://www.tonymacx86.com/threads/guide-lenovo-v330-15ikb-using-clover-uefi-hotpatch.265841/) |                                                              |
| Lenovo ThinkPad W530               | [链接](https://github.com/nghiant96/EFI-Thinkpad-W530-Hackintosh) |                                                              |                                                              |
| Lenovo-WEI6(威6)                   | [链接](https://github.com/Tamshen/Lenovo-WEI6-Pro-13-IWL-Hackintosh) |                                                              | **Lenovo Thinkbook 13S**                                     |
| Lenovo xiaoxin air13 6th           | [链接](https://github.com/gdllzkusi/Lenovo-xiaoxin-air13-6th-Hackintosh) |                                                              | Intel 酷睿i5 6200U                                           |
| Lenovo XiaoXin Air 13 IWL          | [链接](https://github.com/daliansky/Lenovo-Air13-IWL) [链接](https://github.com/darpaxyz/Lenovo-Air13-IWL-Hackintosh) <br />[链接](https://github.com/xlivans/Air13IWL) | [链接](https://blog.daliansky.net/Lenovo-Xiaoxin-Air-13-macOS-Mojave-installation-tutorial.html) | 联想小新 Air 13 2018 IWL<br />网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Lenovo XiaoXin Air15 IKBR          | [链接](https://github.com/czy1024/XiaoXin-Air15-IKBR-2018-EFI) |                                                              |                                                              |
| Lenovo XiaoXin14 IWL 2019          | [链接](https://github.com/superbboy/Lenovo-XIAOXIN-14-2019-IWL-Hackintosh) [链接](https://github.com/4flr/XiaoXin-14IWL-2019-Hackintosh) |                                                              | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Lenovo XiaoXin Air 14 2019 IML     | [链接](https://github.com/lietxia/XiaoXinAir14IML_2019_hackintosh) |                                                              | 小新 Air14-2019 IML 10代 i5-10210u                           |
| Lenovo XiaoXin Pro 13 2019         | [链接](https://github.com/daliansky/XiaoXinPro-13-2019-hackintosh) |                                                              | 联想小新Pro 2019，网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Lenovo XiaoXin Chao 5000           | [链接](https://github.com/Xc2333/Hackintosh-Lenovo-chao5000) |                                                              | 联想潮 5000                                                  |
| Lenovo XiaoXin Rui 7000            | [链接](https://github.com/Erf172/Lenovo_XiaoXin_Rui7000_Hackintosh) | [链接](https://github.com/Erf172/Lenovo_XiaoXin_Rui7000_Hackintosh/blob/10.12/README.md) |                                                              |
| Lenovo XiaoXin Chao 7000           | [链接](https://github.com/penghubingzhou/Lenovo-Xiaoxin-Chao-7000--EFI) | [链接](https://github.com/penghubingzhou/Lenovo-Xiaoxin-Chao-7000--EFI/blob/master/Readme.md) | 联想小新潮 7000，已支持 14 寸、<br />12.5 寸、13.3 寸，15 寸以及 <br />13.3 寸的完美支持后续会添加，<br />请期待…… |
| ThinkPad X1 3rd                    | [链接](https://github.com/shockingpants/ThinkpadX1Y3)        | [链接](https://www.tonymacx86.com/threads/guide-thinkpad-x1-yoga-3rd-gen-20ld-with-mojave.261823/) | ThinkPad X1 3 代                                             |
| ThinkPad X1 Carbon 2015            | [链接](https://github.com/transtone/hackintosh/tree/master/x1c-2015) [链接](https://github.com/Derekxxzzyy/Thinkpad-X1-Carbon-3rd-Hackintosh-OC-EFI) |                                                              |                                                              |
| ThinkPad X1 Carbon 5th gen         | [链接](https://github.com/B0hrer/Thinkpad-x1c-5th-gen-Hackintosh) |                                                              | (5th gen, released 2017)                                     |
| ThinkPad X1 Carbon 6th Gen         | [链接](https://github.com/tylernguyen/x1c6-hackintosh) [链接](https://github.com/RyoIkarashi/hackintosh-x1c6-with-native-wifi-card) | [链接](https://github.com/tylernguyen/x1c6-hackintosh/blob/master/README.md) | Thinkpad X1 Carbon 6th Gen                                   |
| ThinkPad X1 Yoga / Carbon          | [链接](https://github.com/LukaJankovic/Thinkpad-X1-20FQ-Hackintosh) | [链接](https://github.com/LukaJankovic/Thinkpad-X1-20FQ-Hackintosh/blob/master/README.md) | Thinkpad X1 Yoga / Carbon                                    |
| ThinkPad X1 Yoga 2018              | [链接](https://github.com/Jamesxxx1997/thinkpad-x1-yoga-2018-hackintosh) |                                                              |                                                              |
| ThinkPad X1 Extreme                | [链接](https://github.com/Errrneist/Hackintosh-Thinkpad-X1-Extreme) [链接](https://github.com/zysuper/Thinkpad-X1-extreme-EFI) | [链接](https://www.tonymacx86.com/threads/macos-10-14-0-thinkpad-x1-extreme-igpu-issue.263916/) | 如果没猜错，这货就是 x1 隐士，<br />好几个人问过，这下省事了 |
| ThinkPad X1C 6th                   | [链接](https://github.com/tylernguyen/x1c6-hackintosh)       | [链接](https://github.com/tylernguyen/x1c6-hackintosh/blob/master/README.md) | ThinkPad X1c 6th                                             |
| ThinkPad X220                      | [链接](https://github.com/b-ggs/x220-hackintosh)             | [链接](https://github.com/b-ggs/x220-hackintosh/blob/master/README.md) | 支持 10.14+                                                  |
| ThinkPad X220                      | [链接](https://github.com/laris/Hackintosh-ThinkPad-X220-MacOS) |                                                              | ThinkPad-X220                                                |
| ThinkPad X230                      | [链接](https://github.com/littlegtplr/Hackintosh-X230-macOS) [链接](https://github.com/mighildotcom/X230-Hackintosh) | [链接](https://github.com/littlegtplr/Hackintosh-X230-macOS/blob/master/README.md) | ThinkPad X230                                                |
| ThinkPad X230                      | [链接](https://github.com/banhbaoxamlan/X230-Hackintosh) [链接](https://github.com/SynneK1337/ThinkPad_X230_Hackintosh) | [链接](https://github.com/SynneK1337/ThinkPad_X230_Hackintosh/blob/master/README.md) | ThinkPad X230                                                |
| ThinkPad X230i                     | [链接](https://github.com/fivestrong/Hackintosh-X230i-macOS) |                                                              |                                                              |
| ThinkPad X250                      | [链接](https://github.com/Janolan/x250-hackintosh) [链接](https://github.com/qwerty12/X250-Hackintosh) [链接10.15](https://github.com/teddytaod/mac-catalina-thinkpad-x250) [链接](https://github.com/banhbaoxamlan/X250-Hackintosh) |                                                              |                                                              |
| ThinkPad X260 系列                 | [链接](https://github.com/daliansky/ThinkPad-X260-hackintosh) | [链接](https://github.com/daliansky/ThinkPad-X260-hackintosh/blob/master/README.md) | ThinkPad X260<br />网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Thinkpad x390-yoga                 | [链接](https://github.com/Liu-wenxiang/Thinkpad-X390-Yoga-Clover) |                                                              |                                                              |
| Lenovo Y50(70) 系列                | [链接](https://github.com/RehabMan/Lenovo-Y50-DSDT-Patch)    | [链接](https://www.tonymacx86.com/threads/guide-lenovo-y50-uhd-or-1080p-using-clover-uefi.261723/) | Y50(70)1080P 和 4K 版本<br />网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Lenovo IdeaPad 530s                | [链接](https://github.com/corint1/Hackintosh-Lenovo-IdeaPad-530s-14ikb) |                                                              | 感谢：[39军小兵张](http://i.pcbeta.com/space-uid-4472739.html) |
| Lenovo Ideapad S340/S540           | [链接](https://github.com/IvanAleksandrov94/Lenovo-s340-s540-Big-Sur-OpenCore-i5-8265u) |                                                              |                                                              |
| Lenovo IdeaPad Y410P               | [链接](https://github.com/Z39/Y410p-OS-X-Clover-Hotpatch)    |                                                              | 感谢：[39军小兵张](http://i.pcbeta.com/space-uid-4472739.html) |
| Lenovo IdeaPad Y430P               | [链接](https://github.com/Z39/Y430p-OS-X-Clover-Hotpatch)    |                                                              | 感谢：[39军小兵张](http://i.pcbeta.com/space-uid-4472739.html) |
| Lenovo IdeaPad Y510P               | [链接](https://github.com/Z39/Y510p-OS-X-Clover-Hotpatch)    |                                                              | 感谢：[39军小兵张](http://i.pcbeta.com/space-uid-4472739.html) |
| Lenovo Y520/Y720                   | [链接](https://github.com/the-braveknight/Lenovo-Y520-macOS) [链接](https://github.com/adrianjagielak/lenovo_y520_efi) | [链接](https://www.tonymacx86.com/threads/guide-lenovo-legion-y520-y720-using-clover-uefi.261009/) | 联想 Y520 及 Y720                                            |
| Lenovo Legion Y7000                | [链接](https://github.com/hnie-xwz/EFI)                      | [链接](https://github.com/hnie-xwz/EFI/blob/macOs10.14/readme.md) | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Lenovo Legion Y7000-1060           | [链接](https://github.com/TioaTyan/Lenovo_Legion_Y7000-1060_Hackintosh) | [链接](https://github.com/TioaTyan/Lenovo_Legion_Y7000-1060_Hackintosh/blob/master/README.md) | Lenovo_Legion_Y7000-1060                                     |
| Lenovo Legion Y7000<br />Y530 系列 | [链接](https://github.com/xiaoMGitHub/Lenovo_Y7000-Y530_Hackintosh/) [链接](https://github.com/ahossny/Legion-Y530-Hackintosh) |                                                              | 全新完美 EFI，舍弃了小键盘                                   |
| Lenovo Y7000P 81T1                 | [链接](https://github.com/gclm/Hackintosh-LEGION-Y7000P-I7-9750H) |                                                              | I7-9750H                                                     |
| Lenovo Y9000X                      | [链接](https://github.com/programbw/y9000x) [链接](https://github.com/hsd815/Y9000X-4K-hackintosh) [链接](https://github.com/WangRicky/Y9000X-HACKINTOSH) [链接](https://github.com/snxiang/Y9000X-Hackintosh-FHD-OpenCore) |                                                              | 支持CNVi直插m.2网卡，推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Lenovo Y9000X 2020                 | [链接](https://github.com/Corazon0513/Y9000X-2020-i9-Hackintosh) |                                                              | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Lenovo Yoga 3 Pro 1370             | [链接](https://github.com/gdllzkusi/hackintosh--lenovo-Yoga-3-Pro-1370) | [链接](https://github.com/gdllzkusi/hackintosh--lenovo-Yoga-3-Pro-1370/blob/master/README.md) | 联想 yaga3/pro                                               |
| ThinkPad Yoga 12                   | [链接](https://github.com/gartempe/MacOS-Thinkpad-Yoga-12) [链接](https://github.com/kymodoke/MacOS-Thinkpad-Yoga-12) | [链接](https://github.com/gartempe/MacOS-Thinkpad-Yoga-12/blob/master/README.md) [链接](https://github.com/kymodoke/MacOS-Thinkpad-Yoga-12/blob/master/README.md) |                                                              |
| Thinkpad S1 Yoga 12                | [链接](https://github.com/thebinh-lg051/Thinkpad-S1-Yoga-12-Hackintosh) |                                                              |                                                              |
| Lenovo Yoga3 14                    | [链接](https://github.com/gdllzkusi/Lenovo-yoga3-14-hackntiosh) |                                                              |                                                              |
| Lenovo Yoga3 11                    | [链接](https://github.com/gdllzkusi/Lenovo-yoga3-11-hackntiosh) |                                                              |                                                              |
| Lenovo Yoga 13IKB                  | [链接](https://github.com/dragonflylee/Yoga13-Hackintosh)    |                                                              |                                                              |
| Lenovo Yoga 370                    | [链接](https://github.com/ouxuebo/YOGA370-clover)            |                                                              |                                                              |
| Lenovo Yoga 520 14IKB              | [链接](https://github.com/gasperTheGhost/Yoga-520-Hackintosh) |                                                              |                                                              |
| Lenovo Yoga 710-14isk 80TY         | [链接](https://github.com/yutayouguan/EFI)                   |                                                              | i5-6200U                                                     |
| Lenovo Yoga 710                    | [链接](https://github.com/xiaoxx970/Hackintosh-Mojave-for-Lenovo-Yoga710) |                                                              |                                                              |
| Lenovo Yoga 720                    | [链接](https://github.com/bugprogrammer/hackintosh/tree/Lenovo-yoga-720-13ikb-7200u) |                                                              | Lenovo Yoga 720-13IKB                                        |
| Lenovo Yoga 720                    | [链接](https://github.com/williambj1/Hackintosh-EFI-Lenovo-Yoga-720-12IKB) | [链接](https://github.com/williambj1/Hackintosh-EFI-Lenovo-Yoga-720-12IKB/tree/master/Resources) | Lenovo Yoga 720-12IKB                                        |
| Lenovo Yoga 730                    | [链接](https://github.com/dragonflylee/Yoga-730-hackintosh)  |                                                              | Lenovo Yoga 730-13IKB                                        |
| Lenovo Yoga S740                   | [链接](https://github.com/frozenzero123/YOGA-S740)           |                                                              | i7 1065G7                                                    |
| Lenovo Yoga 910 13IKB              | [链接](https://github.com/wjz304/Hackintosh-EFI-Lenovo-Yoga-910-13IKB) |                                                              |                                                              |
| Lenovo Z50(40)/70 系列             | [链接](https://github.com/the-braveknight/Lenovo-X50-macOS)  | [链接](https://www.tonymacx86.com/threads/guide-lenovo-z50-70-z40-70-g50-70-g40-70-using-clover-uefi.261787/) | Lenovo Z50-70/Z40-70   Lenovo G50-70/G40-70                  |
| Lenovo Miix510                     | [链接](https://github.com/Aexus/hackintosh-ideapad-miix510)   [链接](https://github.com/liuwaei/Lenovo-Miix510-EFI-Clover-for-MacOS-10.14.X) |                                                              | Lenovo-Miix510                                               |
| Lenovo Miix-520                    | [链接](https://github.com/acai66/lenovo-miix-520-hackintosh-10.14-CLOVER) | [链接](https://github.com/acai66/lenovo-miix-520-hackintosh-10.14-CLOVER) | Lenovo-Miix-520                                              |
| Lenovo Miix4                       | [链接](https://github.com/Zero-zer0/Miix700-OSX-Hackintosh-Clover) |                                                              | Lenovo-Miix4（700）                                          |
| Lenovo Miix720                     | [链接](https://github.com/jennie26/Lenovo-Miix-720-Hackintosh) |                                                              |                                                              |
| Thinkstation P910                  | [链接](https://github.com/crazyi/Hackintosh_Thinkstation_P910) |                                                              |                                                              |
| Lenovo Yoga 920 13IKB              | [链接](https://github.com/qxuchn/YOGA920-Hackintosh)         |                                                              |                                                              |


### LG

| 机型名称               | 发布地址                                                  | 教程地址 | 备注 |
| ---------------------- | --------------------------------------------------------- | -------- | ---- |
| LG Gram 13z980         | [链接](https://github.com/suzuke/LG-Gram-13z980-Opencore) |          | OC   |
| LG Gram 14z980         | [链接](https://github.com/ShiningXu/LG-Gram-macOS)        |          |      |
| LG Gram 15Z980-G.AA52C | [链接](https://github.com/ice-black-tea/LG-15Z980)        |          |      |
| LG Gram Z980           | [链接](https://github.com/ShiningXu/LG-Gram-macOS)        |          |      |

### Mechrevo 机械革命

| 机型名称                 | 发布地址                                                     | 教程地址                                                     | 备注                                |
| ------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------------------------------- |
| Mechrevo Z2              | [链接](https://github.com/cmbs2019/Mechrevo-Hackintosh)      |                                                              | i7-8750H/i5-8300H GTX1050ti/GTX1060 |
| Mechrevo Z2 Air          | [链接](https://github.com/cmbs2019/Mechrevo-Hackintosh)      |                                                              | i7-8750H/i5-8300H GTX1050ti/GTX1060 |
| Mechrevo X8ti            | [链接](https://github.com/cmbs2019/Mechrevo-Hackintosh)      |                                                              | i7-8750H/i5-8300H GTX1050ti/GTX1060 |
| Mechrevo X8ti Plus       | [链接](https://github.com/cmbs2019/Mechrevo-Hackintosh)      |                                                              | i7-8750H/i5-8300H GTX1050ti/GTX1060 |
| Mechrevo S1              | [链接](https://github.com/cmbs2019/Mechrevo-Hackintosh) [链接](https://github.com/lgs3137/MR_S1-macOS) | [链接](https://github.com/lgs3137/MR_S1-macOS/tree/master/Install) | I5-8250U/I7-8550u Mx150             |
| Mechrevo S1              | [链接](https://github.com/cmbs2019/Mechrevo-Hackintosh)      |                                                              | I5-8265U/I7-8565u Mx250             |
| Mechrevo X2              | [链接](https://github.com/cmbs2019/Mechrevo-Hackintosh)      |                                                              | i7-8750H/i5-8300H GTX1050ti/GTX1060 |
| Mechrevo S1 PLUS         | [链接](https://github.com/cmbs2019/Mechrevo-Hackintosh)      |                                                              | i7-8750H/i5-8300H GTX1050ti/GTX1060 |
| Mechrevo X7TI            | [链接](https://github.com/cmbs2019/Mechrevo-Hackintosh)      |                                                              | I7-6700HQ/I7 7700HQ                 |
| Mechrevo X7TI-S          | [链接](https://github.com/cmbs2019/Mechrevo-Hackintosh)      |                                                              | I7-7700HQ GTX1070/GTX1060           |
| Mechrevo X6TI            | [链接](https://github.com/cmbs2019/Mechrevo-Hackintosh)      |                                                              | i7-8750H/i5-8300H GTX1050ti/GTX1060 |
| Mechrevo X6TIS           | [链接](https://github.com/cmbs2019/Mechrevo-Hackintosh)      |                                                              |                                     |
| Mechrevo X1              | [链接](https://github.com/cmbs2019/Mechrevo-Hackintosh) [链接](https://github.com/tsmswifty/MECHREVO-X1-hackintosh) |                                                              | i7-7700HQ/GTX1060                   |
| Mechrevo Z2 / X8Ti 系列  | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)            | 准系统型号：同方 GK5CN6Z/GK5CN5Z    |
| Mechrevo Z2 Air          | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)            | 准系统型号：同方 GK5CN6X/GK5CN5X    |
| Mechrevo Z2-G / Z2 Air-G | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)            | 准系统型号：同方 GK5CP6X/GK5CP5X    |
| Mechrevo X3              | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)            | 准系统型号：同方 GK7CP6R            |

### MSI 微星

| 机型名称                               | 发布地址                                                     | 教程地址                                                     | 备注      |
| -------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | --------- |
| MSI GE60 2PL-403XCN                    | [链接](https://github.com/ice-black-tea/MSI-GE60) [链接](https://github.com/cs950809/MSI-GE60-2PL-403XCN-Hackintosh) |                                                              |           |
| MSI GE63 Raider RGB 8RE                | [链接](https://github.com/skyline75489/Hackintosh-MSI-GE63-Raider-RGB-8RE) |                                                              |           |
| MSI GE70 2PC                           | [链接](https://github.com/alxzoomer/msi-ge70-2pc-hackintosh) |                                                              |           |
| MSI GF63                               | [链接](https://github.com/oscarrock/hackintosh-msi-gf63-thin-9SC) |                                                              |           |
| MSI GF63 thin 9sc                      | [链接](https://github.com/LongBody/EFi-Hackintosh-MSi-GF63-thin-9sc) |                                                              |           |
| MSI GL62M-7REX                         | [链接](https://github.com/rlindsberg/Hackintosh-On-MSI-GL62m-7REX) |                                                              |           |
| MSI GL63-8RE                           | [链接](https://github.com/iAmineOHN/Hackintosh-MSI-GL63-8RE) |                                                              |           |
| MSI GL72M-7RDX                         | [链接](https://github.com/jbwharris/hackintosh-msi-GL72M-7RDX) | [链接](https://github.com/jbwharris/hackintosh-msi-GL72M-7RDX/blob/master/README.md) |           |
| MSI GP62 6QG-1071XCN                   | [链接](https://github.com/chuxubank/MSI-GP62-Hackintosh)     | [链接](https://github.com/chuxubank/MSI-GP62-Hackintosh/blob/master/README.md) | 微星 GP62 |
| MSI GS65 Stealth Thin 8RF              | [链接](https://github.com/vladichimescu/msi-gs65-hackintosh) |                                                              |           |
| MSI GS65 8SE                           | [链接](https://github.com/ErrorErrorError/msi-gs65-8SE-hackintosh) |                                                              |           |
| MSI GS73VR 7RF                         | [链接](https://github.com/dogukanoksuz/msi-gs73vr-7rf-macOS) |                                                              |           |
| MSI GV62 7RE                           | [链接](https://github.com/amogh-w/Hackintosh-MSI-GV62-7RE)   |                                                              |           |
| MSI modern 15                          | [链接](https://github.com/hla63/Msi-modern-15-Hackintosh)    |                                                              |           |
| MSI Prestige 15                        | [链接](https://github.com/KerKerOgh/MSI-Prestige-15-Hackintosh) |                                                              |           |
| MSI PS63 Modern 8RC                    |                                                              |                                                              |           |
| MSI-Z77A-G45                           | [链接](https://github.com/ac1ra/MSI-Z77A-G45-Hackintosh)     |                                                              |           |
| clover-z390-aorus-pro-wifi-9700k-rx580 | [链接](https://github.com/cheneyveron/hackintosh-clover-z390-aorus-pro-wifi-9700k-rx580) | [链接](https://github.com/cheneyveron/hackintosh-clover-z390-aorus-pro-wifi-9700k-rx580/blob/master/README.md) |           |
| MSI Z390                               | [链接](https://github.com/MonkeySdkCom/EFI-MSI-Z390-Tomahawk) |                                                              |           |
| MSI B450                               | [链接](https://github.com/jinhaozcp/Hackintosh-Ryzen-MSI-B450-Gaming-Pro-carbon-ac) |                                                              |           |

### Razer Blade 雷蛇

| 机型名称 | 发布地址 | 教程地址 | 备注 |
| -------- | -------- | -------- | ---- |
| Razer Blade 15 Base Model          | [链接](https://github.com/DocSystem/razerbladehackintosh) [链接](https://github.com/Mother-FKR/RazerBlade15-Base-Model-Hackintosh_macOS_Big_Sur) | [链接](https://github.com/Mother-FKR/RazerBlade15-Base-Model-Hackintosh_macOS_Big_Sur) | 链接2支持`Big Sur`                                           |
| Razer Blade Stealth 雷蛇灵刃潜行版 | [链接](https://github.com/widmonstertony/razer-blade-stealth-hackintosh) |                                                              |                                                              |
| Razer Blade 15 Advanced            | [链接](https://github.com/doanhmaple/Razer-Blade-15-Advanced-2018-Hackintosh) [链接](https://github.com/Errrneist/Hackintosh-Razer-Blade-Advanced) |                                                              | i7-8750H 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Razer_Blade_Advanced_early_2019    | [链接]( https://github.com/stonevil/Razer_Blade_Advanced_early_2019_Hackintosh) |                                                              | [链接](https://github.com/stonevil/Razer_Blade_Advanced_early_2019_Hackintosh) |

### Samsung 三星

| 机型名称 | 发布地址 | 教程地址 | 备注 |
| -------- | -------- | -------- | ---- |
| 三星Samsung NP300E4C           | [链接](https://github.com/installgento0/NP300E4C-hackintosh) |                                                              |                                                              |
| 三星Samsung NP300E5L           | [链接](https://github.com/bearkfear/SAMSUNG-NP300E5L-HACKINTOSH) |                                                              |                                                              |
| 三星Samsung NP300E5M           | [链接](https://github.com/zb2947244682/Samsung_300E5M_Mac_Hackintosh_EFI) |                                                              |                                                              |
| 三星Samsung NP900X3L(NT900X3L) | [链接](https://github.com/justiceserv/NT900X3L-Hackintosh)   |                                                              |                                                              |
| 三星Samsung NP950XCR-G58A      | [链接](https://github.com/wei756/NT950XCR-G58A-Hackintosh/blob/master/README-en.md) |                                                              |                                                              |

### Shinelon 炫龙

| 机型名称                     | 发布地址                                                     | 教程地址                                                     | 备注                                                         |
| ---------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 炫龙 A40L-i7                 | [链接](https://github.com/i0Ek3/Hackintosh_4_Hasee_Shinelon_A40L) | [链接](https://github.com/i0Ek3/Hackintosh_4_Hasee_Shinelon_A40L/blob/master/README.md) |                                                              |
| 炫龙 耀7000                  | [链接](https://github.com/jinmu333/Shinelon_YAO_7000_efi)    | [链接](https://github.com/jinmu333/Shinalon_YAO_7000_efi/blob/efi/README.md) | 准系统型号：同方 GK5CN5X, by @jinmu333                       |
| 炫龙 耀7000                  | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)            | 准系统型号：同方 GK5CN5X, by @kirainmoe                      |
| 炫龙 耀9000-II               | [链接](https://github.com/kirainmoe/hasee-tongfang-macos)    | [链接](https://www.bilibili.com/video/av81263778)            | 准系统型号：同方 GK5CN6X                                     |
| 神舟战神X5<br />炫龙阿尔法L9 | [链接](https://github.com/Raysamatoken/macOS-HaseeX5-ShinelonL9) |                                                              |                                                              |
| 炫龙毒刺X6                   | [链接](https://github.com/JS1993/Shinelon-X6-EFI)            |                                                              |                                                              |
| 炫龙 T3TI                    | [链接](https://github.com/283330601/shinelon-t3ti-Hackintosh) |                                                              | 9750H+1660TI                                                 |
| 炫龙 DC2/DD2                 | [链接](https://github.com/bavelee/DC2_Hackintosh)  [链接](https://github.com/yuedashen88/DC2_EFI) | [链接](https://bavelee.cn/index.php/archives/60/)            | 准系统型号：蓝天 NB50/60 TJ1/TK1 <br> yuedashen88基于大佬BaveLee之前的EFI的修改版本,修复了HDMI热插拔问题 |
| 炫龙 KP3 Plus                | [链接](http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1843619&highlight=%C9%F1%D6%DB) |                                                              | 准系统型号：蓝天 N960TC                                      |

### XiaoMi 小米

| 机型名称            | 发布地址                                                     | 教程地址                                                     | 备注                                                         |
| ------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| XiaoMi Air 2019     | [链接](https://github.com/szpinc/Hacintosh_MiBookAir13.3_i5-8250U_with_10.13.5) |                                                              |                                                              |
| XiaoMi Air          | [链接](https://github.com/billhhh/MiAir-Hackintosh)          | [链接](https://github.com/billhhh/MiAir-Hackintosh/blob/master/README.md) | XiaoMiAir_i7 7500u                                           |
| XiaoMi Air          | [链接](https://github.com/johnnync13/Xiaomi-Mi-Air)          | [链接](https://github.com/johnnync13/Xiaomi-Mi-Air/blob/master/README.md) | 小米 Air                                                     |
| XiaoMi Air          | [链接](https://github.com/ourfor/Mibook-air)                 | [链接](https://github.com/ourfor/Mibook-air/blob/master/README.md) | 小米 Air                                                     |
| XiaoMi Air          | [链接](https://github.com/whtiehack/XiaoMi-Air)              |                                                              |                                                              |
| XiaoMi Air          | [链接](https://github.com/johnnync13/Xiaomi-Notebook-Air-6200u) | [链接](https://github.com/johnnync13/Xiaomi-Notebook-Air-6200u/blob/master/README.md) | 小米 Notebook Air                                            |
| XiaoMi Air          | [链接](https://github.com/whtiehack/XiaoMi-Air)              | [链接](https://github.com/whtiehack/XiaoMi-Air/blob/master/README.md) | XiaoMi NoteBook Air                                          |
| XiaoMi Air 1gen     | [链接](https://github.com/johnnync13/Xiaomi-Notebook-Air-1Gen) |                                                              | 这哥们应该是忠实的米粉，<br />有兴趣的多多关注               |
| XiaoMi Air Skylake  | [链接](https://github.com/johnnync13/EFI_XIAOMI_NOTEBOOK_AIR_SKYLAKE) | [链接](https://github.com/johnnync13/EFI_XIAOMI_NOTEBOOK_AIR_SKYLAKE/blob/master/README.md) |                                                              |
| XiaoMi Air Kabylake | [链接](https://github.com/jasper-wan/Xiaomi-Air-i5-7200U)    |                                                              | Xiaomi Notebook Air 13.3 i5-7200U 指纹版                     |
| XiaoMi Gaming       | [链接](https://github.com/johnnync13/XiaomiGaming)           |                                                              | 额，小米游戏本                                               |
| XiaoMi Pro 系列     | [链接](https://github.com/daliansky/XiaoMi-Pro/releases)     | [链接](https://blog.daliansky.net/MacOS-installation-tutorial-XiaoMi-Pro-installation-process-records.html) | 小米 Pro 系列                                                |
| XiaoMi Ruby 15.6    | [链接](https://github.com/Jxh98/XiaoMi-Ruby-15.6-2019) [小米ruby2019集显版](https://github.com/XenOriginal/XiaoMi-Ruby-15.6-UMA-only) |                                                              | 目前ALC256声卡外放无法驱动<br />网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| XiaoMi 游戏本 8 代  | [链接](https://github.com/daliansky/XiaoMi-GLP)              |                                                              | 小米游戏本，猜的                                             |
| XiaoMi Air          | [链接](https://github.com/hevervie/Hackintosh_XIAOMI_AIR-13.3) |                                                              | 喜欢买小米的，自己区分去吧，我是分不清楚了                   |
| XiaoMi Air          | [链接](https://github.com/wilsonnkwan/Hackintosh-Xiaomi-Air-13.3-2018-Catalina) |                                                              |                                                              |
| XiaoMi Air 13.3     | [链接](https://github.com/teojs/Xiaomi-Air-i7-8550u-EFI)     |                                                              | i7-8550U                                                     |
| 红米redmibook mx250 | [链接](https://github.com/dbv/redmibook_hackintsh_EFI)       |                                                              |                                                              |


### Intel 英特尔

| 机型名称                                            | 发布地址                                                     | 教程地址                                                     | 备注                                                |
| --------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | --------------------------------------------------- |
| Intel DH67GD, DH67BL, <br />DH67CF, DH67CL 系列主板 | [链接](https://github.com/RehabMan/Intel-DH67XX-DSDT-Patch)  | [链接](https://www.tonymacx86.com/threads/guide-intel-dh67xx-with-hd3000-using-clover-uefi-hotpatch.233257/) | Intel DH67GD, DH67BL, <br />DH67CF, DH67CL 系列主板 |
| Surface Pro 3                                       | [链接](https://github.com/hacker1024/Hackintosh-Clover-SurfacePro3) |                                                              |                                                     |
| Surface Pro 4                                       | [链接](https://github.com/Neil-Steven/SurfacePro4-Hackintosh) [链接](https://github.com/bigsadan/surface-pro-4-hackintosh-10.14.3) | [链接](https://github.com/Neil-Steven/SurfacePro4-Hackintosh/blob/master/README.md) | surfacePro 4                                        |
| Surface Pro 6                                       | [链接](https://github.com/molie34/Surface-Pro-6-macOS)       | [教程](https://github.com/molie34/Surface-Pro-6-macOS)       |                                                     |
| NUC10i7                                                    |  [链接](https://github.com/HawkysCC/Hackintosh-NUC10i7)                                                            |                                                              |   支持 BigSur                                                  |

### Other 其它

| 机型名称                       | 发布地址                                                     | 教程地址                                                     | 备注                                                         |
| ------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Clevo P950HR                   | [链接](https://github.com/MegaCookie/Clevo-P950HR-Hackintosh) |                                                              | 蓝天 P950HR，猜的                                            |
| 火影地狱火X6                   | [链接](https://github.com/gaofeicm/DiYuHuo-X6-MacOS-Mojave-10.14.3-Hackintosh) |                                                              |                                                              |
| Thunderobot 911 Air            | [链接](https://github.com/athlonreg/Thunderobot-911-Air-i7-9750h) |                                                              |                                                              |
| Thunderobot 911 Air2           | [链接](https://github.com/athlonreg/Thunderobot-911-Air-i7-9750h) |                                                              |                                                              |
| 雷神笔记本黑苹果套件           | [链接](https://github.com/athlonreg/Thunderobot-Hackintosh)  |                                                              |                                                              |
| Airbook                        | [链接](https://github.com/nabaonan/airbook-6200u-efi)        |                                                              | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| 同方 GI5CN5E                   | [链接](https://github.com/rodgomesc/AVELL-G1513-FOX-7-TONG-FANG-GI5CN5E-HACKINTOSH) |                                                              |                                                              |
| GPD P2 MAX                     | [链接](https://github.com/Azkali/GPD-P2-MAX-Hackintosh)      |                                                              |                                                              |
| 微星准系统ProBox23             | [链接]( https://github.com/Twilightlee/MSI_ProBox23_hackintosh) |                                                              |                                                              |
| MaiBenBen_Damai5               | [链接](https://github.com/jasminebd/MaiBenBen-Damai5)        |                                                              | 麦本本-大麦5                                                 |
| Sony VAIO pro13                | [链接](https://github.com/raydoom/hackintosh-sony-vaio-pro13) |                                                              |                                                              |
| toshiba-B654L                  | [链接](https://github.com/yxb2018/toshiba-B654L-clover-efi)  |                                                              |                                                              |
| Terrans Force/Devil Rays  DR7  | [链接](https://github.com/Jie2GG/Hackintosh-Devil-Rays-DR7)  |                                                              | 未来人类                                                     |
| Toshiba L55W C5320             | [链接](https://github.com/martinmenchon/Hackintosh-Toshiba-L55W-C5320) |                                                              |                                                              |
| Toshiba C805                   | [链接](https://github.com/nan1jueze/TOSHIBA-C805-HM76-CLOVER-Hackintosh) |                                                              |                                                              |
| MONSTER Tulpar T7 V20.1        | [链接](https://github.com/sutsurup/MONSTER-Hackintosh)       | [链接](https://github.com/sutsurup/MONSTER-Hackintosh/blob/master/README.md) |                                                              |
| 机械师 F117B1                  | [链接](https://github.com/Lusior/F117B-Hackintosh)           |                                                              |                                                              |



### 笔记本更多的机型

| 机型名称     | 发布地址                                 | 教程地址 | 备注                                                         |
| ------------ | ---------------------------------------- | -------- | ------------------------------------------------------------ |
| **更多机型** | [链接](https://github.com/sqlsec/clover) |          | 引用自：国光之前维护的仓库                                   |
|              | [链接](https://zhih.me/hackintosh/#/)    |          | 底噪出品：**[one-key-hidpi](https://github.com/xzhih/one-key-hidpi)** |

### 笔记本相关资源

| **笔记本相关资源**   |                                                            |                                                              |                                                              |
| -------------------- | ---------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
|                      | **hotpatch**                                               |                                                              |                                                              |
| P-little             | [链接](https://github.com/daliansky/P-little)              | `Clover` 部件热修复(hotpatch)                                | 宪武做的一套 ThinkPad 补丁，刚开始上传，请期待               |
| OC-little            | [链接](https://github.com/daliansky/OC-little)             | `OpenCore` 部件热修复(hotpatch)                              | 感谢：@宪武                                                  |
|                      | **触摸板**                                                 |                                                              |                                                              |
| VoodooI2C-PreRelease | [链接](https://github.com/williambj1/VoodooI2C-PreRelease) | [触摸设备 DSDT 修补补充](https://github.com/williambj1/VoodooI2C-PreRelease/blob/master/%E8%A7%A6%E6%91%B8%E6%9D%BF%E8%A1%A5%E5%85%85.md) | [Bat.bat](https://github.com/williambj1)搞的                 |
| GenI2C               | [link](https://github.com/williambj1/GenI2C)               | 生成SSDT触摸板的热修复补丁(hotpatch)，以便支持`VoodooI2C`    |                                                              |
|                      | **无线网卡**                                               |                                                              |                                                              |
| 推荐无线网卡         | **MiniPCIe** 接口(推荐 BCM4352HMB、DW1510)                 | **博通**：BCM94322HM8L、Asus BCM94352、AzureWave AW-CE123H、AzureWave AW-NB290H、DW1510、DW1520、DW1550、 | **高通**：DW1515、DW1705、AR5BHB92、AR5BHB112 AR9285 芯片在 10.14 将不再被支持 |
|                      | **PCIe** 接口                                              | **博通**：BCM94331CD、BCM94322MC、BCM94360CD                 | **高通**：AR5BXB72、AR5BXB92、AR5BXB112                      |
|                      | **M.2** 接口                                               | **博通**：BCM94352Z(AE)、DW1560，DW1830<br />BCM94350Z(AE)/[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |                                                              |
|                      | **USB** 无线网卡                                           | RealTek系列                                                  | [链接](https://github.com/chris1111/Wireless-USB-Adapter-Clover) |

## 台式机

## AMD Ryzen

| **台式**                                                     | 发布地址                                                     | 教程地址                                                     | 备注                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ASRock B450 Gaming-ITX/ac                                    | [链接](https://github.com/LemoFire/OpenCore-ASRock-B450-Gaming-ITX-ac) |                                                              |                                                              |
| ASRock B450M Pro4                                            | [链接](https://github.com/dr03m/ASRock-B450M-Pro4-USB-Patch) |                                                              |                                                              |
| AsRock B450M Steel Legend                                    | [链接](https://github.com/marcustut/Hackintosh) [链接](https://github.com/jesdicaDomo/OpenCore-0.6.2-Ryzentosh) |                                                              |                                                              |
| ASRock Fatal1ty B450 Gaming K4                               | [链接](https://github.com/X-c0d3/EFI_Opencore_Catalina)      |                                                              |                                                              |
| ASRock H470M ITX                                             | [链接](https://github.com/FTWH/asrock-h470m-itx-opencore-i5-10500-RX5700-EFI) |                                                              |                                                              |
| ASRock x570M Pro4                                            | [链接](https://github.com/kriskbx/ryzentosh)                 |                                                              | RX 5700XT                                                    |
| ASRock X570 taichi                                           | [链接](https://github.com/yhl452493373/ryzen-hackintosh-efi) |                                                              |                                                              |
| AsRock X570 Phantom Gaming ITX/TB3                           | [链接](https://github.com/aluveitie/RyzenMacPro) [链接](https://github.com/radianttap/EFI-ASRock-X570-ITX-iMacPro1-1) |                                                              | AMD Ryzen 9 3900X<br />Sapphire Radeon RX 5500<br />支持`Big Sur` |
| Asus Prime A320M-K                                           | [链接](https://github.com/ZaRdEc22/Hackintosh-Ryzen-7-EFI)   |                                                              |                                                              |
| ASUS B350 Plus                                               | [链接](https://github.com/mikigal/ryzen-hackintosh) [链接](https://github.com/Salcedoandrew/RYZEN-OPENCORE-0.5.9) |                                                              | AMD Ryzen 7 1700/MSI RX Vega 64                              |
| ASUS ROG B450-E                                              | [链接](https://github.com/rice512/ROG-STRIX-B450-E-GAMING-OpenCore) |                                                              |                                                              |
| ASUS ROG STRIX B450-F                                        | [链接](https://github.com/nqcshady/rog-strix-b450f-opencore) |                                                              |                                                              |
| ASUS ROG Strix B450-F Gaming                                 | [链接](https://github.com/Mattis-Schulte/hackintosh-catalina) |                                                              |                                                              |
| Asus Rog Strix B450-I                                        | [链接](https://github.com/fuermosi777/hackintosh-asus-b450i-oc) [链接](https://github.com/willza3/macOS-strix-B450i) |                                                              |                                                              |
| Asus ROG Strix B450-I GAMING                                 | [链接](https://github.com/solosoyfranco/macOS-nVidia-strix-B450i) |                                                              |                                                              |
| Asus TUF B450M                                               | [链接](https://github.com/Pai2Chen/OpenCore-Asus-TUF-B450M-Plus-Gaming) [链接](https://github.com/maomingyang1314/MACOS--AMD-3700X-TUFB450-ROG5700XT-) |                                                              |                                                              |
| Asus Rog Strix B550i                                         | [链接](https://github.com/huukhai/hackintosh-rog-b550i)      |                                                              |                                                              |
| Asus TUF Gaming B550M-Plus                                   | [链接](https://github.com/ahmetdereli/Hackintosh-Opencore-Asus-TUF-Gaming-B550M-Plus-WI-FI-RX570) |                                                              |                                                              |
| Asus ROG CROSSHAIR VI HERO                                   | [链接](https://github.com/YWQBX/RyzenProEFI)                 |                                                              |                                                              |
| Asus ROG Strix X570-I                                        | [链接](https://github.com/ChanceArthur/macOS-EFI-Asus-X570I) |                                                              |                                                              |
| Asus Strix GAMING X570-I                                     | [链接](https://github.com/reimertz/hackintosh-x570i-3950x) [链接](https://github.com/ChanceArthur/macOS-EFI-Asus-X570I) |                                                              | Ryzen 9 3950x/Reden Vega 64                                  |
| Asus TUF Gaming X570                                         | [链接](https://github.com/hermanzhaozzzz/My-Opencore-EFI-for-AMD3900X-5700XT-TUF-x570-Hackintosh) |                                                              |                                                              |
| ASUS TUF Z570 Gaming Plus                                    | [链接](https://github.com/MenschLennart/AsusTUFX570GamingPlusWIFI) |                                                              |                                                              |
| AMD Ryzen 7 1700x or 3700x<br />MSI X370 Krait Gaming or ASROCK X570 Taichi<br />RX Vega64 | [链接](https://github.com/yhl452493373/ryzen-hackintosh-efi) |                                                              | 10.14.6                                                      |
| R7 3700x/MSI B450/5700XT                                     | [链接](https://github.com/harpsword/hackintosh-ryzen)        |                                                              |                                                              |
| AMD Ryzen安装教程                                            | [链接](https://github.com/MrNegativeTW/Ryzen-Hackintosh-Tutorial) [链接](https://github.com/doesprintfwork/Intel-AMD-Hackintosh-Guide) | [链接](https://kb.hackintoshisfun.ml/vanilla/v/traditional-chinese/) [链接](https://mtwstudio.gitbook.io/ryzentosh/) | 适用于`10.12` `10.13` `10.14`                                |
| AMD FX 6300/NVIDIA GTX 650                                   | [链接](https://github.com/pexcn/hackintosh-amd)              |                                                              | 主板：Asus M5A97 LE R2.0                                     |
| Gigabyte AB350 Gaming 1                                      | [链接](https://github.com/ThatsNiceGuy/ab350-gaming-hack)    |                                                              | AMD Ryzen 5 1600                                             |
| Gigabyte Aorus Pro wifi B450 MITX                            | [链接](https://github.com/zarboz/Open-Core-GB-b450)          |                                                              |                                                              |
| Gigabyte B450M-S2H                                           | [链接](https://github.com/fishaffair/b450m-s2h-catalina) [链接](https://github.com/danel8/ryzen5_3600_b450m_s2h_rx570_4g_OC) |                                                              |                                                              |
| Gigabyte X570 I Arous Pro Wifi                               | [链接](https://github.com/rexding97/AMD-Hackintosh-OpenCore6.1-EFI) |                                                              |                                                              |
| MSI B350M Gaming Pro                                         | [链接](https://github.com/nghuunghiaa111/Hackintosh-IMac)    |                                                              | AMD Ryzen 5 1400<br />MSI RX580 8GB Armor                    |
| MSI B450 GAMING PRO CARBON AC                                | [链接](https://github.com/jinhaozcp/Hackintosh-Ryzen-MSI-B450-Gaming-Pro-carbon-ac) |                                                              | Ryzen 7 3700X / RX5700                                       |
| MSI B450 TOMAHAWK MAX                                        | [链接](https://github.com/kasik96/B450-TOMAHAWK-MAX-RYZEN-5-3600-RX-570) [链接](https://github.com/bakedpotato191/ryzentosh) |                                                              | Ryzen 5 3600 / RX570                                         |
| MSI B450I Gaming Plus AC                                     | [链接](https://github.com/portrayer/Hackintosh-Ryzen-MSI-B450I) [链接](https://github.com/delbertbeta/macOS-msi-b450i-OC) |                                                              |                                                              |
| MSI-B450M Gaming Plus Max                                    | [链接](https://github.com/lay870/EFI-Big-Sur)                |                                                              |                                                              |
| MSI B450m 迫击炮                                             | [链接](https://github.com/heyxiaobai/MSI-B450m-MORTAR-Hackintosh) [链接](https://github.com/Cluas/MSI-b450m-OC) |                                                              | AMD R5 3600x/蓝宝石 RX 570<br />开发分支支持`Big Sur`        |
| MSI B450M Mortar Max                                         | [链接](https://github.com/VanXNF/Hackintosh-Ryzen-3500X-MSI-B450M-Mortar-MAX) [链接](https://github.com/erhuoL/hackintosh-B450m-mortar-max)<br />[链接](https://github.com/mckarsi/opencore-efi) |                                                              |                                                              |
| MSI B450M PRO-VDH MAX                                        | [链接](https://github.com/dellusa/Opencore-MSI-B450M-R5-3600) |                                                              |                                                              |
| MSI krait gaming x370                                        | [链接](https://github.com/yhl452493373/ryzen-hackintosh-efi) |                                                              |                                                              |
| MSI X399                                                     | [链接](https://github.com/lulujyc/MSI-X399-Gaming-Pro-Carbon-AC-1950X-Hackintosh-OpenCore-EFI) |                                                              |                                                              |
| MSI X470 Gaming Pro Carbon                                   | [链接](https://github.com/MaximumQuiet/ryzentosh)            |                                                              |                                                              |
| MSI X470 gaming PRO MAX                                      | [链接](https://github.com/wokilp/MSI_X470_GAMING_PRO_MAX-AMD-R5-2600-EFI) |                                                              |                                                              |
| MSI MEG X570 ACE                                             | [链接](https://github.com/vaasheim1995/AMD-MSI-MEG-X570-ACE-Hackintosh) |                                                              |                                                              |
| MSI MPG X570 GAMING PLUS                                     | [链接](https://github.com/SuperY/OpenCore-EFI-for-MSI-MPG-X570-Gaming-Plus) |                                                              |                                                              |
| AMD Ryzen 1700/Asus B350 Plus                                | [链接](https://github.com/mikigal/ryzen-hackintosh)          |                                                              | MSI GTX 1080 Gaming X                                        |
| AMD Vanilla Clover Patches                                   | [链接](https://github.com/AMD-OSX/AMD_Vanilla)               | [链接](https://github.com/cheneyveron/hackintosh-clover-tachi-x370-1700x-rx570) | AMD Clover补丁，以后可以<br />直接刻盘安装，10.14.5我会同步<br />更新针对AMD平台的配置文件<br />敬请期待 |
| Clover-Ryzen-MSI-B450I                                       | [链接](https://github.com/portrayer/Clover-Ryzen-MSI-B450I)  |                                                              |                                                              |
| Gigabyte X399 Aorus Extreme                                  | [链接](https://github.com/SchmockLord/Hackintosh-Threadripper-1950x-Gigabyte-X399-Aorus-Extreme) |                                                              | Threadripper 1950x@4.0Ghz                                    |
| ASRock-B365M-ITX                                             | [链接](https://github.com/imzhengziyi/ASRock-B365M-ITX-AC-opencore/releases) |                                                              |                                                              |

## INTEL CPU系列

### ASUS 华硕

| **台式（部分）**               | 发布地址                                                     | 教程地址 | 备注                                                         |
| ------------------------------ | ------------------------------------------------------------ | -------- | ------------------------------------------------------------ |
| Asus B85 Pro Gamer             | [链接](https://github.com/xl120022/ASUS-B85PG-E3-RX570-MAC10.15) |          | e3-1231v3 / rx570                                            |
| ASUS Chromebox CN62            | [链接](https://github.com/waldoxhm/asus-chromebox-cn62-guado-hackintosh) |          |                                                              |
| Asus Prime H310I-M             | [链接](https://github.com/xLidoni/i3-8100-H310I-Hackintosh_OC) |          |                                                              |
| Asus TUF B360M-PLUS-S          | [链接](https://github.com/Zerah64/hackintosh_9400f_b360_vega56) [链接](https://github.com/swlfigo/HackintoshEFI) |          |                                                              |
| ASUS TUF B460M                 | [链接](https://github.com/SmallKi-d/ASUS-B460M-TUF-I5-10500ES-RX5700) |          | I5-10500 ES / RX5700                                         |
| Asus Rog Strix B460-G Gaming   | [链接](https://github.com/huytbt/Hackintosh-Desktop-CometLake-B460G-Board-OpenCore) |          |                                                              |
| Asus B460m Plus                | [链接](https://github.com/CasperNan/opencore-ASUS-B460m-plus-10400) |          | Intel 10400 / AMD 5500XT                                     |
| Asus ROG Strix B460-I          | [链接](https://github.com/jalalabdulaziz/ROG-Strix-B460-I) [链接](https://github.com/intihyan/OC-b460i-strix-i7-10700)<br />[链接](https://github.com/lqsahut/ROG_B460i_Hackintosh) |          | I7-10700 / RX570                                             |
| Asus TUF Gaming B460M PLUS     | [链接](https://github.com/Swayyyyy/ASUS-TUF-GAMING-B460M-PLUS-RX570-Hackintosh-Opencore) |          |                                                              |
| Asus Sabertooth z87            | [链接](https://github.com/cmspeedau/Opencore-efi)            |          |                                                              |
| Asus Z97K 4980HQ               | [链接](https://github.com/efsg/ASUS-Z97K-4980HQ-Hackintosh)  |          | I7-4980HQ                                                    |
| Asus Z170-P                    | [链接](https://github.com/Sharlion/z170_6700k_hackintosh)    |          | 华硕Z170-P+6700K+RX470                                       |
| Asus ROG Maximus X Hero Z370   | [链接](https://github.com/RainshawGao/Hackintosh)            |          | Vega 56 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| ROG Maximus XI Hero Wi-Fi M11H | [链接](https://github.com/ttdevs/EFI-Z390-ROG-MAXIMUS-XI-HERO-WIFI-i7-8700K) |          |                                                              |
| Asus ROG STRIX H370-I GAMING   | [链接](https://github.com/Autocrit/Asus-ROG-STRIX-H370-I-GAMING-Hackintosh-Guide) [链接](https://github.com/sheva007/H370i_RX580_OC0.6.1) |          | mini-ITX H370 motherboard                                    |
| Asus STRIX Z270-E              | [链接](https://github.com/BradenM/Hackintosh-7700k-R9_390-iGPU) |          | Asus STRIX Z270-E                                            |
| Asus ROG Strix Z390-E          | [链接](https://github.com/xiedonghang/hackintosh) [链接](https://github.com/lbrdev/asus_z390e_opencore_hackintosh) |          | Intel i9-9900k+UHD630核显                                    |
| Asus Prime Z370-P              | [链接](https://github.com/mint-made/asus-z370p-opencore-hackintosh) |          | `强制RGB模式（EDID覆盖）`                                    |
| Asus-PRIME-Z390                | [链接](https://github.com/dhckdgjs/ASUS-PRIME-Z390-A-HACKINTOSH-Clover-iGPU-with-dGPU-UHD630-RX580) |          | ASUS-PRIME-Z390                                              |
| Asus Prime Z390-A              | [链接](https://github.com/ErickAgrazal/hackinstosh-efi) [链接](https://github.com/DiZhou92/ROG-STRIX-Z490-G-WIFI-ASUS) |          |                                                              |
| ASUS Prime Z390M PLUS          | [链接](https://github.com/Lyrance/ASUS-Prime-Z390M-PLUS-EFI) [链接](https://github.com/LHB6540/Asus-R414-Hackintosh-10.15.7)<br />[链接](https://github.com/Asphyxia-m/Asus-Z390m-plus-efi) |          |                                                              |
| Asus Prime Z490-A              | [链接](https://github.com/yilmazca/intel-i9-10900K-Asus-prime-Z490A-hackintosh) |          | OC: Intel i9-10900K 核显DP                                   |
| Asus Z490 A GAMING             | [链接](https://github.com/ngocdoan/hackintosh-z490-A-Gaming-10900k-5700) |          |                                                              |
| Asus ROG Here                  | [链接](https://github.com/kreactnative/EFI-z490-rog-hero-XII-10900k-bigSur) |          |                                                              |
| Asus ROG STRIX Z490-E          | [链接](https://github.com/taoche/Z490-E-Hackintosh)          |          | i7-10700k + RX5700XT                                         |
| Asus ROG STRIZX Z490I          | [链接](https://github.com/jergoo/Hackintosh-ROG-STRIX-Z490I) |          | OC: i7-10700k + Radeon VII                                   |
| Asus ROG STRIX Z490-G WIFI     | [链接](https://github.com/DiZhou92/ROG-STRIX-Z490-G-WIFI-ASUS) |          |                                                              |
| Asus Z490 MAXIMUS XII FORMULA  | [链接](https://github.com/shijij/OSX_EFI_Asus_Z490_MAXIMUS_FORMULA) |          | i7-10700k + RX5700XT                                         |
| Asus TUF Z490 Plus             | [链接](https://github.com/horphi/Asus-TUF-Z490-Plus)         |          |                                                              |
| Asus X299 PRIME DELUXE II      | [链接](https://github.com/yifan-gu/hackintosh)               |          | i9 7980XE + Radeon VII                                       |
| Asus X299                      | [链接](https://github.com/shinoki7/Asus-X299-Hackintosh)     |          |                                                              |
| Asus ROG STRIX X299-E GAMING   | [链接](https://github.com/Fansaly/X299-STRIX-macOS)          |          | INTEL® CORE™ i7-7800X                                        |

### ASRock 华擎

| **台式（部分）**                   | 发布地址                                                     | 教程地址 | 备注                                                         |
| ---------------------------------- | ------------------------------------------------------------ | -------- | ------------------------------------------------------------ |
| ASRock  deskmini 110               | [链接](https://github.com/suxiaogang/asrock-deskmini-110-hackintosh) |          |                                                              |
| Asrock deskmini 310                | [链接](https://github.com/liminghuang/asrock_deskmini310_hackintosh) [链接](https://github.com/huangyanan/Hackintosh-EFI-for-deskmini-310-dw1820) |          | 网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| ASRock B360-ITX/ac                 | [链接](https://github.com/jhelgert/hackintosh)               |          |                                                              |
| ASRock B360M/ac-itx                | [链接](https://github.com/jhelgert/hackintosh)               |          |                                                              |
| ASRock B360M-HDV                   | [链接](https://github.com/RealKiro/Hackintosh)               |          |                                                              |
| ASRock B360M Pro4                  | [链接](https://github.com/Joehaivo/hackintosh)               |          |                                                              |
| Asrock B460M-ITX/AC                | [链接](https://github.com/ansonliao/Asrock-B460m-ITX-AC-OC-EFI) |          |                                                              |
| AsRock B460M Pro4                  | [链接](https://github.com/yrambler2001/Hackintosh-Intel-i5-10600-iGPU-AsRock-B460M-Pro4) [链接](https://github.com/ahadrox/ASRock-B460M-Pro4-OpenCore-EFI) |          | i5-10600 / 核显                                              |
| Asrock B460M Steel Legend          | [链接](https://github.com/ducnm9/Hackintosh-Intel-i5-10400-Asrock-B460M-Steel-Legend) |          |                                                              |
| Asrock X99 Extreme3                | [链接](https://github.com/stefan2225/Asrock-X99-Extreme3-Opencore-Hackintosh) |          |                                                              |
| ASRock Z370M-ITX/ac                | [链接](https://github.com/Yellowpal/ASRock-Z370M-ITX-AC-OpenCore) |          | OpenCore                                                     |
| ASRock Z370 Pro4                   | [链接](https://github.com/athlonreg/ASRock-Z370-Pro4-Hackintosh) |          | [套路]-                                                      |
| ASRock Z390M-ITX/ac                | [链接](https://github.com/chinalichen/ASRock_Z390M_ITX_Clover_EFI) |          |                                                              |
| ASRock Z390 Phantom Gaming itx     | [链接](https://github.com/haiyang1992/Hackintosh-Opencore-Asrock_Z390_Phantom_Gaming_ITX) [链接](https://github.com/icyleaf/EFI-ASRock-Z390-Phantom-Gaming-ITX) [链接](https://github.com/bydavy/EFI-ASRock-Z390-Phantom-Gaming) <br />[链接](https://github.com/kcunanan/Jared-PC/) [链接](https://github.com/befuture/EFI-ASRock-Z390-Phantom-Gaming) |          | 华擎 Z390 Phantom Gaming itx/ac                              |
| ASRock Z390 Phantom ITX            | [链接](https://github.com/zanderzhng/EFI_Asrock_Z390_Phantom_ITX) [链接](https://github.com/seanzhang98/ASRock-Z390-Phantom-ITX-OpenCore-Hackintosh-2020) |          |                                                              |
| ASRock Z490M ITX/ac                | [链接](https://github.com/Old-Black-Dog/Hackintosh-ASRock-Z490M-ITX-ac) [链接](https://github.com/huijiewei/ASRock-Z390m-ITX-ac-Opencore)<br />[链接](https://github.com/ruibeard/OpenCore-ASRock-Z490M-ITX-ac) |          |                                                              |
| Asrock Z490M Pro4m                 | [链接](https://github.com/xuanquydsr/z490m-pro4-10700k-hackintosh) |          |                                                              |
| ASRock Z490 ITX/TB3                | [链接](https://github.com/kreactnative/EFI-ASRock-Z490-ITX-TB3-RX580) |          |                                                              |
| ASRock Z490 Phantom Gaming ITX/TB3 | [链接](https://github.com/papadiche/10900K-ASRock-Z490-Phantom-Gaming-ITX-TB3-RX-5600-XT) |          |                                                              |
| ASRock Z490 Steel Legend           | [链接](https://github.com/xiaoyaowx/Hackintosh-Z490-ASRock-Steel-Legend-Intel-10700) |          | I7-10700 / 蓝宝石 RX 5600XT                                  |

### Dell 戴尔

| **台式（部分）**                           | 发布地址                                                     | 教程地址 | 备注                                                         |
| ------------------------------------------ | ------------------------------------------------------------ | -------- | ------------------------------------------------------------ |
| Dell OptiPlex 760                          | [链接](https://github.com/Austcool-Walker/Dell-Optiplex-760-hackintosh-OpenCore) |          |                                                              |
| Dell OptiPlex 3050                         | [链接](https://github.com/Leif160519/Dell-OptiPlex-3050-EFI) [链接](https://github.com/fgprodigal/Optiplex-3050-EFI-OC)<br />[链接](https://github.com/mxltxt/Dell-OptiPlex-3050-OC-EFI) |          |                                                              |
| Dell OptiPlex 3070                         | [链接](https://github.com/bfrorum10/DELL-3070-MFF-Catalina-10.15.6-OC-0.5.9) |          |                                                              |
| Dell OptiPlex 9020M                        | [链接](https://github.com/mingcheng/dell-optiplex-9020m-hackintosh) [链接](https://github.com/JimLee1996/Hackintosh_OptiPlex_9020)<br /> [链接](https://github.com/W-MS/OptiPlex-9020-Catalina) |          | Disable MSR 0xE2 (i.e. cfg lock) `setup_var 0xDA2 0x00`<br /> Increase DVMT to 96M `setup_var 0x263 0x03`<br /> 链接3支持Catalina |
| Dell OptiPlex 7040                         | [链接](https://github.com/optiplex-osx/Dell-OptiPlex-7040-Clover-EFI) [链接](https://github.com/monaive/DELL-OptiPlex-7040-Clover) |          |                                                              |
| Dell OptiPlex 7050                         | [链接](https://github.com/kuaima/Dell-OptiPlex-7050-Clover-EFI) |          |                                                              |
| Dell OptiPlex 7060<br />Dell OptiPlex 7070 | [链接](https://github.com/W-MS/OptiPlex-7060and7070-Catalina) [链接](https://github.com/Jianhua-Wang/DELL-Optiplex-7060-7040-Clover) |          | Increase DVMT to 64M `setup_var 0x8DC 0x2` ，不支持96M模式，<br />切勿使用0x3或在其他型号使用此命令。支持Catalina。 |
| Dell PowerEdge T30                         | [链接](https://github.com/cstrouse/Dell-PowerEdge-T30-Hackintosh) |          |                                                              |
| Dell Precision 3240                        | [链接](https://github.com/billzhong/dell-precision-3240-compact-hackintosh) |          |                                                              |
| Dell Pricision 3520                        | [链接](https://github.com/sdh0618/Pricision-3520-EFI-Catalina) |          |                                                              |
| Dell Precision T3610                       | [链接](https://github.com/cstrouse/Dell-T3610-Hackintosh)    |          |                                                              |
| Dell Precision T3620                       | [链接](https://github.com/fivestrong/Hackintosh-Dell-Precision-T-3620) |          |                                                              |
| Dell Vostro 3267                           | [链接](https://github.com/Drovosek01/hackintosh_DELL_Vostro_3267_i5-6400/blob/master/docs/ENG/README.md) |          |                                                              |
| Dell Vostro 3669                           | [链接](https://github.com/daliansky/Dell_Vostro_3669_Hackintosh) |          |                                                              |

### Gigabyte 技嘉

| **台式（部分）**               | 发布地址                                                     | 教程地址                                                     | 备注                                                         |
| ------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 技嘉 GB-BXi5H-4200 系列主板    | [链接](https://github.com/RehabMan/Gigabyte-BRIX-s-DSDT-Patch) | [链接](https://www.tonymacx86.com/threads/guide-gigabyte-brix-using-clover-uefi-gb-bxi5h-4200-gb-bxi5-4570r-gb-bxi7-4770r.261710/) | 技嘉 GB-BXi5H-4200 系列主板                                  |
| Gigabyte B85-HD3               | [链接](https://github.com/lttztt/B85-i5_4590-HACKINTOSH-Clover-EFI) |                                                              | i5-4590 / RX570                                              |
| GIGABYTE B250M-D3H             | [链接](https://github.com/beyondgary/Hackintosh_i5-7500_B250_HD630_EFI) |                                                              |                                                              |
| Gigabyte B365M AORUS           | [链接](https://github.com/tsln1998/AORUS-B365M-EFI)          |                                                              |                                                              |
| Gigabyte B360M AORUS PRO       | [链接](https://github.com/liangzhenduo0608/hackintosh-efi) [链接](https://github.com/HoracePeng/hackintosh-b360m-opencore) |                                                              | 备注：链接2为OC                                              |
| Gigabyte B360 AORUS Gaming 3   | [链接](https://github.com/littlegtplr/Hackintosh-Clover-folder-for-Coffee-Lake-builds) |                                                              |                                                              |
| Gigabyte B360m d2v             | [链接](https://github.com/Matchas-xiaobin/EFI-B360m_d2v_dvi_uhd630) |                                                              | 技嘉B360m，支持DVI输出                                       |
| Gigabyte B360M D3H             | [链接](https://github.com/laelsirus/GA-B360M-D3H-with-UHD630-iGPU-AMD-dGPU-CLOVER) |                                                              | GA-B360M-D3H                                                 |
| Gigabyte B360M DS3H            | [链接](https://github.com/sqlsec/B360M-DS3H-I5-9600KF-RX580-CLOVER) |                                                              | 国光自用：i5-9600KF RX580                                    |
| Gigabyte B460M Aorus Pro       | [链接](https://github.com/dovtuan/Gigabyte-B460M-Aorus-Pro-Hackintosh-Open-Core) |                                                              | i5-10400 / RX570                                             |
| Gigabyte B460M-DS3H            | [链接](https://github.com/bangbaew/Gigabyte-B460M-DS3H-Hackintosh) |                                                              | i5-10400 / RX480                                             |
| Gigabyte C246 WU4              | [链接](https://github.com/SeonMe/Gigabyte-C246-WU4-Hackintosh-OC) |                                                              | Intel Xeon E-2278G / Sapphire RX 5500XT                      |
| Gigabyte Designaire Z390       | [链接](https://github.com/baughmann/designaire-z390-intel-i9-9900k-opencore) |                                                              |                                                              |
| G1 sniper M7 intel B150M       | [链接](https://github.com/infonekingdom/G1M7)                |                                                              |                                                              |
| Gigabyte H110m sh2             | [链接](https://github.com/DMNerd/Hackintosh_EFI)             |                                                              |                                                              |
| Gigabyte H87M-D3H              | [链接](https://github.com/aqeebimtiaz/EFI-for-Mojave-Hackintosh-Gigabyte-H87M-D3H-i34440-HD4600-8GB) |                                                              |                                                              |
| Gigabyte X370N                 | [链接](https://github.com/cwr31/z370n-hackintosh) [链接](https://github.com/qinkangdeid/z370n-wifi-hackintosh) |                                                              | Gigabyte Z370N                                               |
| Gigabyte Z270X-UD3             | [链接](https://github.com/cfryerdev/efi-opencore-7700K-Z270X-UD3) |                                                              | OpenCore 0.6.0                                               |
| Gigabyte Z270X-UG              | [链接](https://github.com/icedterminal/ga-z270x-ug)          | [链接](https://github.com/icedterminal/ga-z270x-ug/blob/master/README.md) |                                                              |
| Gigabyte Z370N WIFI            | [链接](https://github.com/b166ar/Mac-Mini-Killer) [链接](https://github.com/yangbe/z370n-wifi-vega64) [链接](https://github.com/zhangdongpo/Z370N-Wi-Fi-Hackintosh-EFI)<br />[链接](https://github.com/edenpulse/z370n-i7-8700K-RX5700XT-Odin) |                                                              | Mac-Mini-Killer<br />Z370N WIFI VEGA64                       |
| Gigabyte Z370 HD3P             | [链接](https://github.com/kinoute/Hack-Z370-HD3P-i5-8400)    |                                                              |                                                              |
| Gigabyte Z390 AORUS            | [链接](https://github.com/cmer/gigabyte-z390-aorus-master-hackintosh) |                                                              | **备注：**<br />如果不是9900k/9700k/8500/8700k CPU，<br />需要打`Device RTC`补丁 |
| Gigabyte Z390 AORUS ELITE      | [链接](https://github.com/liusming/hackintosh)               |                                                              | I9-9900K/Intel (Z380) HD 630 2G                              |
| Gigabyte Z390 Aorus Pro        | [链接](https://github.com/sarkrui/Hackintosh-Z390-Aorus-Pro-9700K-RX580) |                                                              | OpenCore/i7-9700K/蓝宝石 RX580 8G                            |
| Gigabyte Z390 AORUS PRO        | [链接](https://pcpartpicker.com/product/L9YLrH/gigabyte-z390-i-aorus-pro-wifi-mini-itx-lga1151-motherboard-z390-i-aorus-pro-wifi) |                                                              | WIFI Mini ITX                                                |
| Gigabyte Z390 AORUS PRO WIFI   | [链接](https://github.com/shiruken/hackintosh)               |                                                              | i7-9700K + Radeon RX 5700 XT                                 |
| Gigabyte Z390 Master           | [链接](https://github.com/felixyin/clover-z390master-i99900k-rx580-970pro) |                                                              |                                                              |
| Gigabyte Z390 AORUS MASTER ATX | [链接](https://github.com/vmzhivetyev/hackintosh-efi)        |                                                              |                                                              |
| Gigabyte Z390 M Gaming         | [链接](https://github.com/tspng/gigabyte-z390-m-gaming-hackintosh) |                                                              | 技嘉 Z390m                                                   |
| Gigabyte Z390 gaming           | [链接](https://github.com/dbv/hackintosh_9600k_Z390_RX580)   | 小辉自用: i5-9600k RX580 2304sp矿                            |                                                              |
| Gigabyte Z390 Gaming X         | [链接](https://github.com/wqh0109663/Gigabyte-Z390-Gaming-X-Hackintosh) |                                                              |                                                              |
| Gigabyte Z390 M                | [链接](https://github.com/xxiaofeng132/Gigabyte-Z390M-Gaming-Hackintosh) |                                                              | 技嘉Z390m-gaming                                             |
| Gigabyte Z390 Ultra            | [链接](https://github.com/mrpaulphan/gigabyte-z390-ultra-master-hackintosh) |                                                              |                                                              |
| Gigabyte Z390-UD               | [链接](https://github.com/kong-git/Z390-OC-UHD630) [链接](https://github.com/kong-git/Z390-UD-RX580) |                                                              | OpenCore 核显/RX580独显                                      |
| Gigabyte B365M Aorus Elite     | [链接](https://github.com/ChuanfengZhang/Gigabyte-B365M-UHD630-Clover) [链接](https://github.com/hookybaby/hackintoshEFI) | [链接](https://www.bugprogrammer.me/2020/05/27/Hackintosh_for_Z490_10900K.html) | Gigabyte B365M i5-9400 UHD630 Clover config                  |
| Gigabyte Z490 AORUS ELITE      | [链接](https://github.com/bugprogrammer/hackintosh/tree/Z490-AORUS-ELETE+10900K+RX5700XT) |                                                              | OC: 10900K+5700XT                                            |
| Gigabyte Z490 AORUS Pro AX     | [链接](https://github.com/ankanpratik/Gigabyte-Z490-AORUS-Pro-AX-EFI-OpenCore-) |                                                              |                                                              |
| Gigabyte Z490 AORUS Master     | [链接](https://github.com/hoangviet/Hackintosh-Intel-i9-10900k-Gigabyte-Z490-Aorus-Master) |                                                              |                                                              |
| Gigabyte Z490 Aorus Ultra      | [链接](https://github.com/tagyro/Hackintosh_Gigabyte_Z490_Aorus_Ultra) [链接](https://github.com/rayovims/Hackintosh-EFI-Partion) |                                                              |                                                              |
| Gigabyte Z490 Vision D         | [链接](https://github.com/SchmockLord/Hackintosh-Intel-i9-10900k-Gigabyte-Z490-Vision-D) [链接](https://github.com/xiaovie/Hackintosh-Intel-i9-10900k-Gigabyte-Z490-Vision-D)<br />[链接](https://github.com/rursache/Hackintosh-i9-10900k-Z490-Vision-G) [链接](https://github.com/eos-alchemist/EFI.Z490.Vision.D) |                                                              | OC: 10900K+Radeon VII                                        |
| Gigabyte Z490 Vision G         | [链接](https://github.com/georgetree/hackintosh-10700k-Gigabyte-Z490-Vision-g)  [链接](https://github.com/samuel21119/Intel-i9-10900-Gigabyte-Z490-Vision-G-Hackintosh) |                                                              |                                                              |
| Gigabyte Z490 Gaming X         | [链接](https://github.com/weiyien/Hackintosh_GIGABYTE_Z-490_I5-10400) [链接](https://github.com/SwimmingPig/Hackintosh-Intel-i5-10400-Gigabyte-Z490M-Gaming-X) |                                                              | OC:10400+RX5500XT(核显没驱动,另外处理)                       |
| Gigabyte Z77P D3               | [链接](https://github.com/cloverkits/GA-Z77P-D3-EFI)         |                                                              | GA-Z77P-D3                                                   |
| Gigabyte Z77X D3H              | [链接](https://github.com/nickw444/opencore-efi)             |                                                              |                                                              |
| Gigabyte GA-Z77X-DS3           | [链接](https://github.com/tdyn2000/GIGA-Z77X-DS3-Catalina-EFI) |                                                              |                                                              |
| Gigabyte Z97X Gaming 5         | [链接](https://github.com/amogh-w/Hackintosh-4790K-Z97X-GTX-960) |                                                              |                                                              |

### HP 惠普

| **台式（部分）**      | 发布地址                                                     | 教程地址 | 备注            |
| --------------------- | ------------------------------------------------------------ | -------- | --------------- |
| HP Elitedesk G3       | [链接](https://github.com/lavjamanxd/hp-elitedesk-g3-hackintosh) |          |                 |
| HP Prodesk 400 G4 MT  | [链接](https://github.com/3rr0rists/EFI-OpenCore-HP-Prodesk-400-G4-MT) |          |                 |
| HP ProDesk 480 G4     | [链接](https://github.com/SummerEmber/HP-ProDesk-480-G4)     |          |                 |
| HP Prodesk 600 G1 DM  | [链接](https://github.com/ZqinKing/EFI-HP-ProDesk-600-G1-DM) |          |                 |
| HP Prodesk 600 G1 SFF | [链接](https://github.com/kidddjh/HP-Prodesk-600-G1-SFF)     |          |                 |
| HP ProDesk 600 G4     | [链接](https://github.com/ljzxzxl/HP-ProDesk-600-G4-)        |          |                 |
| HP Z420               | [链接](https://github.com/yansheng1003/Hackintosh)           |          | E5 1650v2       |
| HP Z600 Workstation   | [链接](https://github.com/lutzmor/hp_z600_hackintosh)        |          | Mac-Mini-Killer |
| HP Z620 Workstation   | [链接](https://github.com/d4vinder/HP-Z620-Hackintosh-macOS-Catalina) [链接](https://github.com/mokiii/HP-Z620-Hackintosh-macOS_10.13-10.15) |          |                 |

### Intel 英特尔

| **台式（部分）**          | 发布地址                                                     | 教程地址                                                     | 备注        |
| ------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ----------- |
| Intel NUC 5、6、7、8 系列 | [链接](https://github.com/RehabMan/Intel-NUC-DSDT-Patch)     | [链接](https://www.tonymacx86.com/threads/guide-intel-kaby-lake-nuc7-using-clover-uefi-nuc7i7bnh-nuc7i5bnk-nuc7i3bnh-etc.261711/) | mini 主机   |
| NUC8I5BEH                 | [链接](https://github.com/dongyubin/nuc8i5beh)               | [链接](https://chengxuxiaohei.cn/mac-anzhuang.html) [链接](https://osy.gitbook.io/hac-mini-guide/) |             |
| NUC8i5BEK                 | [链接](https://github.com/Hyejeongdd/NUC8i5BEK-Hackintosh)   |                                                              |             |
| NUC8i7BEH                 | [链接](https://github.com/sarkrui/NUC8i7BEH-Hackintosh-Build) [链接](https://github.com/wilsonnkwan/Hackintosh-NUC8i7BEH-Catalina) [链接](https://github.com/honglov3/NUC8I7BEH) | [链接](https://osy.gitbook.io/hac-mini-guide/)               | 链接3为`OC` |
| NUC7i7BNH                 | [链接](https://github.com/calebchow9/Intel-NUC7i7BNH-Hackintosh) |                                                              |             |
| NUC7i5BEK                 | [链接](https://github.com/331296441/NUC7i5BEK)               |                                                              |             |
| NUC10i7                   | [链接](https://github.com/HawkysCC/Hackintosh-NUC10i7)       |                                                              |             |

### Lenovo 联想

| **台式（部分）**                           | 发布地址                                                     | 教程地址 | 备注                                                         |
| ------------------------------------------ | ------------------------------------------------------------ | -------- | ------------------------------------------------------------ |
| Lenovo M93P                                | [链接](https://github.com/mingcheng/lenovo-thinkcentre-m93p-hackintosh) [链接](https://github.com/SummerEmber/Lenovo-ThinkCentre-M93p-Tiny) |          | 联想 M93P 系列主机                                           |
| 联想 Lenovo 启天 M415-D339                 | [链接](https://github.com/static-host/Hackintosh-OpenCore)   |          |                                                              |
| Lenovo 天逸 510S Mini                      | [链接](https://github.com/daliansky/Lenovo-TianYi-510S-Mini-Hackintosh) |          | 联想天逸510S Mini小主机                                      |
| Lenovo ThinkCentre M4500q                  | [链接](https://github.com/samawong/hackintosh-clover-configure-for-lenovo-m4500q-n000-model) |          |                                                              |
| Lenovo ThinkCentre M710Q                   | [链接](https://github.com/daliansky/Lenovo-M710Q-Hackintosh) |          | 小兵自用，长期维护<br />网卡推荐：[DW1820A](https://blog.daliansky.net/DW1820A_BCM94350ZAE-driver-inserts-the-correct-posture.html) |
| Lenovo ThinkCentre M720Q                   | [链接](https://github.com/fronttang/Lenovo-ThinkCentre-M720Q-Hackintosh) [链接](https://github.com/tobagin/m720q-OpenCore-Catalina/) |          |                                                              |
| Lenovo ThinkCentre e 73                    | [链接](https://github.com/riku2015/Efi-files-for-lenovo-e73) |          |                                                              |
| Lenovo M73 Tiny                            | [链接](https://github.com/rehandalal/m73-tiny-hackintosh)    |          |                                                              |
| Lenovo Thinkcentre M910x                   | [链接](https://github.com/ylen0l/Hackintosh-Lenovo-Thinkcentre-M910x-OpenCore-Efi) |          |                                                              |
| Lenovo Thinkpad P1 <br />MobileWorkStation | [链接](https://github.com/p455555555/Thinkpad-P1-EFI)        |          |                                                              |

### MSI 微星

| **台式（部分）**          | 发布地址                                                     | 教程地址                                                     | 备注                                                         |
| ------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| MSI B250M-E               | [链接](https://github.com/rakiy/Hackintosh_MSI_B250M_EFI)    |                                                              |                                                              |
| MSI B360                  | [链接](https://github.com/SuperNG6/MSI-b360-10.14.4-EFI)     |                                                              | 也适用于<br />MAG Z390 TOMAHAWK <br />(MS-7B18)              |
| MSI B360M MORTAR IMACPRO  | [链接](https://github.com/andot/MSI-B360M-MORTAR-IMACPRO-EFI) |                                                              |                                                              |
| MSI B360M i3-8100/rx570   | [链接](https://github.com/shm007g/hackintosh-msi-b360m-i3-8100-rx570) |                                                              |                                                              |
| MSI B360M MORTAR OpenCore | [链接](https://github.com/GeQ1an/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI) [链接](https://github.com/CeuiLiSA/Opencore-EFI) | [链接](https://github.com/GeQ1an/MSI-B360M-MORTAR-HACKINTOSH-OPENCORE-EFI/blob/master/README.md) |                                                              |
| MSI B460M MORTAR          | [链接](https://github.com/josways/B460M-MORTAR) [链接](https://github.com/IlikemacOS/B460M-MORTAR-Comet-Lake-IGPU-AGPU)<br />[链接](https://github.com/cheneyxx/Hackintosh-10400-B460M-MORTAR) |                                                              | I5-10400 / RX550                                             |
| MSI H81M-IE35 | [链接](https://github.com/MoeGuoH/EFI-MSI-H81M-IE35) | |  |
| MSI Z270 PC-MATE | [链接](https://github.com/koscakdomen/Hackintosh_EFI) | | |
| MSI Z370-A                | [链接](https://github.com/daliansky/Z370-Hackintosh)         | [链接](https://github.com/daliansky/Z370-Hackintosh)         | 黑果小兵MSI Z370-A自用EFI                                    |
| MSI Z370m mortar i7-9700k | [链接](https://github.com/JackyCZJ/Z370M-MORTAR-I7-9700K-M9PEG-CLOVER) |                                                              |                                                              |
| MSI  Z370-TOMAHAWK  i7-8700k | [链接](https://github.com/luffythink/Hackintosh-EFI)         | [链接](https://github.com/luffythink/Hackintosh-EFI/blob/master/README.md)         | clover稳定版 and oc版                                        |
| MSI Z390-Gaming-EDGE-AC   | [链接](https://github.com/fnoopv/MSI-Z390-Gaming-Edge-AC_OC) |                                                              | 微星MPG-Z390-Gaming-Edge-ac OpenCore EFI                     |
| MSI Z390i Gaming EDGE AC | [链接](https://github.com/mojo2012/hackintosh-efi) | |  |
| MSI Z390i                 | [链接](https://github.com/GaryOAO/MSI-Z390i-hackintosh-clover) |                                                              |                                                              |
| MSI MAG Z390 TOMAHAWK     | [链接](https://github.com/xushuduo/MSI_Z390_TOMAHAWK_I5-9600K_HACKINTOSH_OPENCORE_EFI) |                                                              | MSI MAG Z390 TOMAHAWK + i5-9600K + RX590 HACKINTOSH OPENCORE EFI |
| MSI MEG Z490 ACE          | [链接](https://github.com/kreactnative/z490-ace-10700k-catalina) [链接](https://github.com/kreactnative/EFI-z490-ace-10700k-bigSur) |                                                              | 链接1为catalina，链接2为Big Sur                              |
| MSI MAG Z490 TOMAHAWK     | [链接](https://github.com/Dir3Rav3n/MSI-MAG-Z490-TOMAHAWK-i7-10700-OpenCore-) |                                                              | i7-10700 / RX580                                             |
| MSI Z490M Gaming Edge     | [链接](https://github.com/redcweed/z490)                     |                                                              | Intel i7-10700 / XFX RX590                                   |
| MSI Z490i Unify           | [链接](https://github.com/kingwood77/MSI-Z490i-Unify-Hackintosh) [链接](https://github.com/wjz304/Hackintosh-EFI-MSI-Z490i-Unify) |                                                              | i5-10400 / RX580                                             |
| MSI Z97 Gaming 5 | [链接](https://github.com/plcharriere/Hackintosh/blob/master/Z97G5/) | | i5-4690K |

### Mini 迷你系列

| **台式（部分）**             | 发布地址                                                     | 教程地址 | 备注                  |
| ---------------------------- | ------------------------------------------------------------ | -------- | --------------------- |
| Cloud Hin H170               | [链接](https://github.com/kdwycz/cloud-hin-h170-stx-hackintosh) [链接](https://github.com/matri/hipda-h170-opencore) |          | 云轩H170              |
| Deskmini-310                 | [链接](https://github.com/yuqi/Deskmini-310-Hackintosh)      |          | Deskmini-310          |
| Soarsea mini PC              | [链接](https://github.com/EngLearnsh/Soarsea-i9-8950HK-Hackintosh) |          | S200H                 |
| CM238 i7-8950H UHD630 ALC269 | [链接](https://github.com/kkzzhizhou/S200H_I7-8750H_Hackintosh) |          | S200H_I7-8750H 小主机 |
| I7-8850H迷你主机             | [链接](https://github.com/n0jack/i78850h-minipc-hackintosh)  |          |                       |
| DQ77KB                       | [链接](https://github.com/siwilizhao/DQ77KB-I7-3770S-Hackintosh) |          |                       |

### 台式机其它机型

| 机型名称                   | 发布地址                                                     | 教程地址                                                     | 备注             |
| -------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ---------------- |
| ACER Veriton D430          | [链接](https://github.com/SummerEmber/ACER-Veriton-D430)     |                                                              |                  |
| 华南金牌B75                | [链接](https://github.com/LeUKi/Hackintosh-EFI-huanan_B75)   |                                                              | e3-1230-v2 RX460 |
| Huanan X79 E5-2670, GTX650 | [链接](https://github.com/cheneyveron/clover-x79-e5-2670-gtx650) | [链接](https://github.com/cheneyveron/clover-x79-e5-2670-gtx650/blob/master/README.md) | 华南 x79 V2      |
| Ant Country X79 Basic      | [链接](https://github.com/m1qnet/X79-Hackintosh-Catalina)    |                                                              |                  |
| X79 E5-2696-v2             | [链接](https://github.com/cmd2001/X79-E5-2696-v2-R9-Nano-Clover-EFI) |                                                              | R9 Nano          |

## 硬件兼容列表

| 机型名称         | 发布地址                                                     | 教程地址                                                     | 备注                                                     |
| ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------------------------------------------------------- |
| **硬件兼容列表** | [链接](https://github.com/CrazyPegAsus/macOS-Mojave-Compatibility-hardware-list) |                                                              | 感谢: [CrazyPegAsus](https://github.com/CrazyPegAsus)    |
| 黑苹果购买指南   | [链接](https://github.com/khronokernel/Anti-Hackintosh-Buyers-Guide) |                                                              | Hackintosh Buyers Guide                                  |
| 黑苹果安装学院   | [链接](https://github.com/huangyz0918/Hackintosh-Installer-University) | [链接](https://github.com/huangyz0918/Hackintosh-Installer-University/blob/master/README-CN.md) | 这个和本repo功能类似，既然作者开放了，我们也可以收录补充 |
| 黑苹果互助项目   | [链接](https://github.com/bessyjl/HackintoshClover)          |                                                              | 和本repo类似                                             |

## 其它机型请提交到[这里](https://github.com/daliansky/Hackintosh) 



## 感谢名单

- [Apple](https://www.apple.com/) 的 macOS
- [RehabMan](https://github.com/rehabman)维护的项目：[OS-X-Clover-Laptop-Config](https://github.com/RehabMan/OS-X-Clover-Laptop-Config) [Laptop-DSDT-Patch](https://github.com/RehabMan/Laptop-DSDT-Patch) [OS-X-USB-Inject-All](https://github.com/RehabMan/OS-X-USB-Inject-All)等
- [Acidanthera](https://github.com/acidanthera) 维护的项目：[OpenCorePkg](https://github.com/acidanthera/OpenCorePkg) [lilu](https://github.com/acidanthera/Lilu) [AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup) [WhateverGreen](https://github.com/acidanthera/WhateverGreen) [VirtualSMC](https://github.com/acidanthera/VirtualSMC) [AppleALC](https://github.com/acidanthera/AppleALC) [BrcmPatchRAM](https://github.com/acidanthera/BrcmPatchRAM) [MaciASL](https://github.com/acidanthera/MaciASL) 等
- [headkaze](https://www.insanelymac.com/forum/profile/1364628-headkaze/) 提供的工具：[hackintool](https://github.com/headkaze/Hackintool) [PinConfigurator](https://github.com/headkaze/PinConfigurator) [BrcmPatchRAM](https://www.insanelymac.com/forum/topic/339175-brcmpatchram2-for-1015-catalina-broadcom-bluetooth-firmware-upload/)  
- [CloverHackyColor](https://github.com/CloverHackyColor)维护的项目：[CloverBootloader](https://github.com/CloverHackyColor/CloverBootloader) [CloverThemes](https://github.com/CloverHackyColor/CloverThemes) 
- 宪武整理的：[P-little](https://github.com/daliansky/P-little) [OC-little](https://github.com/daliansky/OC-little) 
- [chris1111](https://github.com/chris1111)维护的项目：[VoodooHDA](https://github.com/chris1111/VoodooHDA-2.9.2-Clover-V15) [Wireless USB Adapter Clover](https://github.com/chris1111/Wireless-USB-Adapter-Clover) 
- [zxystd](https://github.com/zxystd)开发的[itlwm](https://github.com/zxystd/itlwm) [IntelBluetoothFirmware](https://github.com/zxystd/IntelBluetoothFirmware) 
- [lihaoyun6](https://github.com/lihaoyun6)提供的工具：[CPU-S](https://github.com/lihaoyun6/CPU-S) [macOS-Displays-icon](https://github.com/lihaoyun6/macOS-Displays-icon) [SidecarPatcher](https://github.com/lihaoyun6/SidecarPatcher) 
- [xzhih](https://github.com/xzhih)提供的工具：[one-key-hidpi](https://github.com/xzhih/one-key-hidpi) 
- [Bat.bat](https://github.com/williambj1)更新维护的[精解OpenCore](https://blog.daliansky.net/OpenCore-BootLoader.html)
- [athlonreg](https://github.com/athlonreg)更新维护的[OpenCore 0.5+ 部件补丁](https://blog.cloudops.ml/ocbook/) [Common-patches-for-hackintosh](https://github.com/athlonreg/Common-patches-for-hackintosh)
- [github.com](github.com)
- [码云 gitee.io](gitee.io) 
- [扣钉 coding.net](coding.net) 

## 参考及引用：

- https://deviwiki.com/wiki/Dell
- https://deviwiki.com/wiki/Dell_Wireless_1820A_(DW1820A)
- [Hervé]([https://osxlatitude.com/profile/4953-herv%C3%A9/](https://osxlatitude.com/profile/4953-hervé/)) 更新的Broadcom 4350:https://osxlatitude.com/forums/topic/12169-bcm4350-cards-registry-of-cardslaptops-interop/
- [Hervé]([https://osxlatitude.com/profile/4953-herv%C3%A9/](https://osxlatitude.com/profile/4953-hervé/)) 更新的DW1820A支持机型列表:https://osxlatitude.com/forums/topic/11322-broadcom-bcm4350-cards-under-high-sierramojave/
- [nickhx](https://osxlatitude.com/profile/129953-nickhx/) 提供的蓝牙驱动：https://osxlatitude.com/forums/topic/11540-dw1820a-for-7490-help/?do=findComment&comment=92833
- [xjn819](https://blog.xjn819.com/)： [使用OpenCore引导黑苹果](https://blog.xjn819.com/?p=543) [300系列主板正确使用AptioMemoryFix.efi的姿势(重写版）](https://blog.xjn819.com/?p=317) 
- [insanelymac.com](https://www.insanelymac.com/) 
- [tonymacx86.com](https://www.tonymacx86.com/) 
- [远景论坛](http://bbs.pcbeta.com)
- [applelife.ru](https://applelife.ru/) 
- [olarila.com](https://www.olarila.com/)

  

## QQ群列表：

1161377948 [黑果小兵黑苹果技术群5](https://qm.qq.com/cgi-bin/qm/qr?k=kBV9vCnz-NqtXXJiwnUhaLyJN1D7G0n6&jump_from=webapi) 2000人群 新开群
553283949 [黑果小兵黑苹果技术群6](https://qm.qq.com/cgi-bin/qm/qr?k=kr_hZc5pKK4TCDRaFPwRlfAiB4528InP&jump_from=webapi) 2000人群 新开群
688324116 [一起黑苹果](https://qm.qq.com/cgi-bin/qm/qr?k=Fp4HZ5e8A61oCu0GMS5YUqP6COc43-AO&jump_from=webapi) 2000人群 人满为患
331686786 [一起吃苹果](https://qm.qq.com/cgi-bin/qm/qr?k=No8zvDfvDicT-GfSApw1RMBI-3MQ7zM3&jump_from=webapi) 2000人群 人满为患
257995340 [一起啃苹果](https://qm.qq.com/cgi-bin/qm/qr?k=acztqL9efoqAOoptc_3moZ9b3Sgczu9_&jump_from=webapi) 2000人群 远景报备群
875482673 [黑果小兵黑苹果技术群](https://qm.qq.com/cgi-bin/qm/qr?k=aZNyoRum_er2mruqmnbX_93ncHNgsyak&jump_from=webapi) 2000人收费群 已满员，请加4群
1058822256 [黑果小兵黑苹果技术群2](https://qm.qq.com/cgi-bin/qm/qr?k=1sIT0BDaejgr9t1Hlw16cMnw_Z96zleV&jump_from=webapi) 2000人收费群 已满员，请加4群
819662911 [黑果小兵黑苹果技术群3](https://qm.qq.com/cgi-bin/qm/qr?k=aJx9xO7vAmyslCuOdK0bRMmDLpvOCeRw&jump_from=webapi) 2000人收费群，请加4群
954098809 [黑果小兵黑苹果技术群4](https://qm.qq.com/cgi-bin/qm/qr?k=iu042k0X5snr--dzAxOzcsvD9Zft9yx7&jump_from=webapi) 2000人收费群，尚有空位
701278330 [黑苹果无线网卡交流群](https://qm.qq.com/cgi-bin/qm/qr?k=x57TlUmxz88oXGDWjMOOsWokYi8klE11&jump_from=webapi) 1000人群 DW1820A技术支持群
891434070 [Catalina黑苹果交流群](https://qm.qq.com/cgi-bin/qm/qr?k=TUAxSUUtw_T1N62V0kF1sWvMcDr_eoxc&jump_from=webapi) 2000人群 远景报备群
939122730 [Catalina黑苹果交流II群](https://qm.qq.com/cgi-bin/qm/qr?k=g_rpf7m0LJllE6WHY9c0gVvCTBm1MtuN&jump_from=webapi) 2000人群
891677227 [黑果小兵高级群](https://qm.qq.com/cgi-bin/qm/qr?k=xsuIOzF7RXYaRTTbJ5o_UjzohRDUx5UY&jump_from=webapi) 2000人群
943307869 [黑果小兵高级群II](https://qm.qq.com/cgi-bin/qm/qr?k=aoSvqrbysdjPo0Wa_XvvPuMG9NMEtOie&jump_from=webapi) 2000人群
538643249 [OpenCore技术交流群](https://qm.qq.com/cgi-bin/qm/qr?k=si7f9Mfzs82wHGvKLVhBLmW87YA31y92&jump_from=webapi) 2000人群 大神众多非OC适配者慎入
942112153 [天逸510s Mini黑苹果交流群](https://qm.qq.com/cgi-bin/qm/qr?k=N5cjw5ksrnmk-RMQ4fPCOo5D_Dxiu47B&jump_from=webapi) 1000人群 非专用机型请勿加入
673294583 [小新Pro黑苹果技术群](https://qm.qq.com/cgi-bin/qm/qr?k=GgcMJM5-98yB-fc6zyGcTI3OuesrSBRk&jump_from=webapi) 2000人群 非专用机型请勿加入
946132482 [小新Pro黑苹果](https://qm.qq.com/cgi-bin/qm/qr?k=r-m99xC-BPIRdVkEjU6duvqXMJ-1FOwA&jump_from=webapi) 500人群 非专用机型请勿加入
943181023 [联想小新Air黑苹果交流群](https://qm.qq.com/cgi-bin/qm/qr?k=OGO_GSX9ZhtbQ_HNns57Vdxm5pR1wH6V&jump_from=webapi) 500人群 非专用机型请勿加入



## Telegram群：

黑果小兵的部落阁 [http://t.me/daliansky](https://t.me/daliansky)



## 微信公众号：【`黑果小兵的部落阁`】

![WeChat](http://7.daliansky.net/WeChat/WeChat.png)

## 关于打赏

如果您认可我的工作，请通过打赏支持我后续的更新

| paypal                                                       | 微信                                                       | 支付宝                                               |
| ------------------------------------------------------------ | ---------------------------------------------------------- | ---------------------------------------------------- |
| [![paypal_daliansky](http://7.daliansky.net/paypal_daliansky.png)](https://www.paypal.me/daliansky) | ![wechatpay_160](http://7.daliansky.net/wechatpay_160.jpg) | ![alipay_160](http://7.daliansky.net/alipay_160.jpg) |

[![img](https://img.shields.io/github/stars/daliansky/Hackintosh.svg?color=ff69b4&label=%E7%82%B9%E8%B5%9E&logoColor=ff69b4&style=social)](https://github.com/daliansky/Hackintosh) [![img](https://img.shields.io/github/followers/daliansky.svg?label=%E7%B2%89%E4%B8%9D&logoColor=success&style=social)](https://github.com/daliansky/Hackintosh) ![img](https://img.shields.io/github/contributors/daliansky/Hackintosh.svg?color=red&label=%E8%B4%A1%E7%8C%AE%E4%BA%BA%E6%95%B0) [![img](https://img.shields.io/github/last-commit/daliansky/Hackintosh.svg?color=orange&label=%E6%9C%80%E8%BF%91%E6%8F%90%E4%BA%A4)](https://github.com/daliansky/Hackintosh) [![img](https://img.shields.io/badge/link-996.icu-red.svg)](https://996.icu/)

 
