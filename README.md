# 付费机场推荐/SSR和V2ray节点订阅机场,专线机场,科学上网

下面有几个稳定的专线机场推荐，方便正在找ssr/v2ray节点订阅机场的人，老有人让我推荐机场，我就写下来，谁要发给谁，让他自己选。

机场推荐购买付费账号，收费机场比较好，不建议买付费的VPN,感觉付费VPN不如付费ssr/v2ray机场；花钱可以节省很多时间和精力,而且贵点的稳定点舒服很多，不可能又便宜又稳定流量还多的。用了好的就回不去了；之前自己搭建虽然最安全，但是容易受到高墙干扰，维护很麻烦不推荐购买直接使用搜索vpn出来的软件，迟早药丸免费机场/白嫖机场一般不太稳定；下面有几个稳定的机场推荐，包括ssr、ss、v2ray、trojan等协议，也有可以打游戏的、IPLC专线机场等。因为现在防火墙在每年64、国庆、除夕都会进行干扰代理，目前的方法是反向墙国内中转服务器，所以敏感时期需要使用专线，如果是企业，需要高稳定性直接买专线机场就好。

TelegramT机场观察频道：https://t.me/jichangtj   掌握最新机场优惠折扣通知，最新机场推荐评测与测速图，最新科学上网相关新闻与消息

建议收藏本页，持续更新
如果觉得有帮助到您，Star下呗~~~ 经常更新！！！最近更新时间：2021.10.23


**如何挑选机场？(个人观点不一定对)**

1.机场主要就是看线路。总体线路质量：内网的阿里云/AIA/CC>IPLC>IELP>CN2>普通公网普通中转。在保证能流畅看视频前提下，稳定性最重要，然后才是追求更高的速度。一分钱一分货，vps 和线路注定，稳定&流量多&便宜==不存在。总体越贵越好（不绝对），不建议买直连ss/ssr/v2ray机场，v2ray起速慢点。尽量选择有AIA、CC、ILPC国际专线和中转、BGP中转的，比较稳。 IPLC是入口和出口中间那小段不过墙，但是从你家到iplc入口，以及iplc出口到落地机，以及落地机到目标服务器仍然是在公网，公网网络抖动是很频繁的。腾讯云Anycast（AIA）则多入口BGP入口，就近接入腾讯云入口，然后走腾讯云内网进行传输到全球各地。目前机场届最高端的线路了，稳定性高延迟低，除了贵没啥缺点。

看你使用的网络运营商: 电信和联通一般都不错。移动，教育网和中国铁通最好买BGP三网中继线路，体验才好。目前主流的是利用公有云不同区域的VPC之间内网互通机制，组建的内网。最经典的就是阿里云的经典网络内网，可惜已经没了。目前公有云的VPC内网互联主要有两种类型：第一个是点对点:（如阿里云的高速通道, UCloud的UDPN） 和 多点网络互通:（如阿里云的CEN, 腾讯云的CCN, 华为云的CC, UCloud的UGN,Zenlayer的CN）。专线另一主流就是腾讯AIA代表的网络加速服务。多数是利用公有云厂商地域上广泛分布的服务器，结合Anycast技术，将网络流量就近导入公有云服务器,然后走公有云自有全球骨干网(专线/内网/MPLS)，到达目标服务器。一部分是两个地区端对端的专线（比如花卷莞港/苏日专线）。


2.尽量买开了比较久的大机场，因为跑路概率小，小机场可能便宜，但是分分钟跑路，跑路了就啥也没有了，买过的都懂。大机场比较有钱买好的线路和加带宽，小机场很可能没钱运营下去。机场主最好是在境外的。别买QQ机场，这不是自爆吗？    

便宜机场套路1：典型的小机场捞钱手法：突然搞活动活动力度过大，吸引用户。 AFF比例非常高，吸引推广。然后便宜短时间大批人购买涌入很容易拉跨。小的机场随时因为资金不足跑路，大的如布丁，喵帕斯，线路一流有实力有背景的rixclod也跑了。   

便宜机场套路2：线路多，但是复用，就是虽然显示多条线路但入口和落地其实是同一条线路，见过10条线路其实都是一条！不少机场这样搞，看上去线路多，骗子。一挂挂一片。就算没挂，当你觉得某条线路不快，切换线路，切了10条都是同一条。    

便宜机场套路3：月抛机场，买的都是月抛线路，很便宜。但是线路变化频繁，随时跑路。我推荐的机场都没这些问题。   

![三色图.jpg](https://cdn.jsdelivr.net/gh/hwanz/SS-SSR-V2ray/img/0.jpg)


3.稳定与协议没有关系，协议不是最重要的，线路才是。ss，ssr，v2ray，trojan都行，被识别了目前只是封ip，损失的是机场主。你换一条线路即可。总体而言ss延迟相对较低。非敏感时期的日常使用中转就好 不一定要用专线。不一定要用专线。专线不一定就好，需要看同时使用人数，几百人挤同一条小水管不如几个人的中转，甚至不如直连。

4.看入口，入口和用户本地网络之间的相性决定了用户使用机场的上限和下限。因为你到入口并非是直达，从你家到入口会绕来绕去才到达。假如机场只有深圳入口，使用深港专线，而你在大陆北方，得在大陆里面绕来绕去，环游大半个中国，然后才到深圳，然后从深圳的入口到机场的线路，再直达香港。这时候延迟就贼高了。拖累你的短板是入口了。中转基本是上海、广州入口：cn2  上海联通 珠海/广州移动等，因为国内流量出境基本是广州上海。中转很重要，因为一旦中转挂了中转线路就没办法转发流量到落地机了

5.备用很重要！买2-3个稳定的比买一堆垃圾的好，因为你就用其中一到两家，一个主用一个备用。买多了放着浪费。没有一直稳定的机场，没有。就算是以稳出名的也有不稳的时候，因此如果你是重度翻墙用户当主用出问题时就需要备用，否则主用出问题就直接失联了。有些机场是需要代理才能打开的，失联或者忘记续费你就无办法续费了，死循环。可以买按量付费的套餐备用，不用不花钱。


3.如果可以直接加telegram群，翻翻Telegram的历史消息，如果很糟糕肯定有其它用户吐槽的。

4.看测速图：看平均速度是否稳定，看google延迟是否低。同时需要看测试的运营商，带宽，地址。测速图好看不代表好用，但是测速非常不好看基本不好用。

5.别买youtuber 大V推荐的。

6.尽量选择gmail、outlook、protonmail等邮箱注册，如果可以尽量选择数字货币支付。不要使用真实个人信息。

7.需要看奈飞 hbo等的，需要买有原生节点/DNS解锁的线路。

8.机场线路可以打游戏，需要使用专门的游戏线路；游戏、语音、BT需要线路支持UDP；机场一般禁止BT。

9.一下别买太长时间，有些人觉得目前买的机场速度还行且便宜觉得后面要涨价于是一下买五年的，虽然当前表现不错，但很难保证之后是什么样子。即使说稳定也只敢说是过去这一段时间稳定，谁也不敢保证后面一定稳。机场不是长久行业。人数是变化的，墙也是一直在加固的，政策也是在变化的。怕跑路，就月付/季付！月付/季付才是规避风险最好的方法。月付才是大爷，想换一家就换一家。年付容易被绑架。。。机场老板跑路了还会卖用户表。各位记得定时换下机场的密码，最好每家机场的密码都不一样。

10.有试用先试用。但是试用可能不限速，套餐限速。所以需要看购买的套餐带宽是否是限速的。

11.好机场一般很少搞活动，除非是刚开的，如果天天搞活动，肯定是平时价格太贵了。

12.机场落地机线路就是就是 aws  ec2   azure  linet  ntt nhn linode digital ocean；香港：hkbn wtt  hkt hgc；台湾：hinet；澳门：ctm。不需要记住大概知道下就行了。需要了解的是你买的多个机场他们的上游和线路是不是一样的。避免一个线路出问题了另外一个也一样。比如常见的ddos。

13.稳定的翻墙成本会越来越高

14.买多少流量的套餐？看你拿来做什么咯。看看网页看看youtube基本最低套餐都足够的。拿来下载就需要自己评估了。同时记得看倍率，有些倍率是很低的。比如0.2，真正流量就需要乘以5倍。

15.抄袭我的请要点脸。上面都是我长期使用总结出来的，直接全复制粘贴，家人安好？


**免费软件**

迷雾通
免翻墙，github下载地址: [https://dlj.tf/yz75wM](https://dlj.tf/yz75wM)
官网，需要翻墙才能打开 : https://geph.io/zhs/ 


**ssr和V2ray付费专线机场推荐**

国内动不动封IP加干扰，用过不少便宜的机场，容易翻车,用着太糟心，所以最后还是加钱求稳定，舒服很多：
vps 和线路注定，稳定&流量多&便宜==不存在

规律：

机场面板基本用的那几套，主要还是看机场主买的线路质量。一分钱一分货，越贵越好，不推荐买直连ss/ssr机场，v2ray起速慢点。尽量选择有ILPC国际专线和中转的，比较稳（移动墙中墙，教育网和中国铁通、长城宽带最好买BGP三网中继线路，体验才好）。日常使用中转就好，敏感时候使用专线救急

拿2020年两会期间某家机场公告举个例子：“经证实，墙是持续性的，通俗易懂来讲他每15分钟墙一波，目前受影响的为所有直连ssr节点，v2ray直连持续性断流，目前暂停修复所有直连线路，待两会结束后再进行修复，V1请尽量使用IPLC线路，其他套餐的会员请使用中转线路。”


如果打不开链接就是被墙了，可以先下载蓝灯或者使用免费SS/SSR节点；



### TAG(腾讯云AIA专线机场)
全AIA专线SSR机场,稳,稳定性高延迟低，目前最顶级的线路了。想要冷门节点的，或者体验AIA顶级专线，大家都推荐这家。冷门节点非常多，同时也一直在增加冷门节点，140+个节点。推荐季付及以上套餐真实流量是翻倍的，每15天/10天流量重置，15天重置就是流量 × 2；每10天重置就是流量乘3。大流量用户的选择。机场主在香港。有自家app,操作简单，方便萌新使用。官网(如果打不开请切换为全局代理)： <a href="https://dlj.tf/ZERWcvq" target="_blank">https://dlj.tf/ZERWcvq</a>


>专线: 有，月付無香港、新加坡等節點  
游戏节点：有27條（季度以上用戶可以使用）     
原生节点：有    
节点国家与地区：非常多    
入口：广州、上海。    
UDP：大部分支持Full Cone       
落地：以色列、印度、台湾、香港、新加坡、日本、澳门、越南、韩国、马来西亚、俄罗斯、德国、爱尔兰、法国、荷兰、英国、加拿大、美国、澳洲、阿根廷、印尼、土耳其、柬埔寨、泰国、菲律宾、瑞士、巴西、冰岛、烏克蘭、南非、智利等 
网络监控：http://system.tagvpn.xyz     
开业时长：2年+   
入口ip数量 6   
落地ip数量 100   
客户端数目：10個 
一键使用客户端： 有   
协议：SSR   
专门客服：有           
流媒体解锁情况：https://node.tagvpn.xyz/    


套餐:

套餐 | 线路 | 流量 | 价格 |客户端数目 
---- | ---  | --- | --- | --- 
1 | 中转+专线 |800G/月 |30块/月 | 10
2 | 中转+专线 |1800G/月 |55块/月 | 10
3 | 中转+专线 |2400G/月 |100块/月 | 10
4 | 中转+专线 |200G/年 |100块/年 | 10
5 | 中转+专线 |500G/年 |250块/年 | 10
6 | 中转+专线 |1230G/年 |500块/年 |10


<details>
  <summary>具体入口和落地信息</summary>
  
     入口:
    China Beijing, Beijing Guanghuan Xinwang Digital*2
    China Unknown City, China Mobile*1
    China Unknown City, China Telecom Guangdong*1
    Hong Kong Unknown City, Tencent cloud computing*2

    落地：
    Argentina Buenos Aires, Servicios y Telecomunicaciones S.A.*1
    Australia Unknown City, Network Presence*3
    Austria Vienna, Akenes SA*1
    Belgium Unknown City, EDIS GmbH*1
    Brazil São Paulo, Misaka Network, Inc.*1
    Cambodia Phnom Penh, Cambo.Host*1
    Canada Genelle, LIMEWAVE*4
    Chile Santiago, Grupo Zgh SpA*1
    Czechia Prague, Filip Hruska*1
    Denmark Albertslund Municipality, Adeo Datacenter ApS*1
    Finland Unknown City, Easylinehost Finland Oy*1
    France Unknown City, Ikoula Net SAS*1
    Germany Frankfurt am Main, Kamatera Inc*1
    Germany Munich, Webhosting24 GmbH*2
    Hong Kong Central, DMIT*1
    Hong Kong Central, HGC Broadband*1
    Hong Kong Central, Netvigator*4
    Hong Kong Kwun Hang, HK Cable TV*1
    Hong Kong Repulse Bay, HGC Broadband*1
    Hungary Unknown City, RackForest Kft.*1
    Iceland Unknown City, 1984 ehf*1
    India Mumbai, LeapSwitch Networks Pvt*2
    Indonesia Unknown City, PT Cloud Hosting Indonesia*2
    Ireland Galway, Digiweb ltd*1
    Isle of Man Unknown City, Amati Foundation*1
    Isle of Man Unknown City, Netcetera Ltd.*1
    Israel Haifa, O.m.c. Computers & Communications Ltd*1
    Israel Tel Aviv, O.m.c. Computers & Communications Ltd*1
    Italy Unknown City, Seflow S.N.C. Di Marco Brame' & C.*1
    Japan Kyoto, Kagoya Japan*1
    Japan Tokyo, Amazon.com*6
    Japan Tokyo, GMO GlobalSign Holdings K.K.*1
    Japan Tokyo, Kirino LLC*1
    Japan Unknown City, GMO GlobalSign Holdings K.K.*1
    Macao Macao, Companhia de Telecomunicacoes de Macau SARL*1
    Malaysia Unknown City, IP ServerOne Solutions Sdn Bhd*3
    Mexico Unknown City, Truxgo S. de R.L de C.V*1
    Netherlands Unknown City, i3D.net B.V*1
    New Zealand Hamilton, MikiPro*1
    Norway Unknown City, TerraHost*1
    Pakistan Unknown City, Multinet Pakistan Pvt.*2
    Poland Unknown City, Meverywhere sp. z o.o.*1
    Portugal Unknown City, Dream Fusion - IT Services, Lda*1
    Russia Unknown City, Hosting technology LTD*1
    Russia Unknown City, LLC Intelcom*1
    Russia Unknown City, Optibit LLC*1
    Russia Yuzhno-Sakhalinsk, Sakhalin Network Communications Co. (SNC)*1
    Singapore Singapore, Amazon.com*1
    Singapore Singapore, Kirino LLC*5
    Singapore Singapore, Zenlayer*2
    South Africa Johannesburg, Misaka Network, Inc.*1
    South Korea Incheon, Amazon.com*3
    South Korea Seoul, SK Broadband*1
    South Korea Unknown City, Korea Telecom*1
    Spain Barcelona, iFog GmbH*1
    Switzerland Unknown City, Beelastic AG*1
    Taiwan New Taipei, Chunghwa Telecom*4
    Taiwan Xitun, Chunghwa Telecom*1
    Thailand Unknown City, Bangmod Enterprise Co.*1
    Thailand Unknown City, UIH*1
    Turkey Izmir, Meric Hosting*1
    Ukraine Vinnytsia, FOP Reznichenko Sergey Mykolayovich*1
    United Arab Emirates Dubai, Microsoft Azure*1
    United Kingdom London, Kamatera Inc*1
    United States New Castle, HON*3
    United States Philadelphia, HON*1
    United States Santa Clara, Kamatera Inc*1
    Vietnam Unknown City, FPT Telecom Company*2

  
</details>

关于AIA（腾讯云 Anycast公网加速 AIA）：
官方简介：Anycast 公网加速（Anycast Internet Acceleration，AIA）是一个覆盖多地的动态加速网络，可以大幅提升您业务的公网访问体验。不同于其他应用层加速服务，AIA 能实现 IP 传输的质量优化和多入口就近接入，减少网络传输的抖动、丢包，最终提升云上应用的服务质量，扩大服务范围，精简后端部署。之前TG两大机场rixcloud yoyu/w8v都使用AIA线路，获得一致好评。21年后越来越多机场用上了AIA节点，很多用来当作游戏节点。多入口BGP入口，就近接入腾讯云入口，然后走腾讯云内网进行传输到全球各地。目前机场届最高端的线路了，稳定性高延迟低，除了贵没啥缺点。
   
  ![tag测速图.png](https://cdn.jsdelivr.net/gh/hwanz/SS-SSR-V2ray/img/tag.png)
  
  历史测速： <a href="https://honven.netlify.app/tag%E6%B5%8B%E9%80%9F%E6%95%B4%E5%90%88.html" target="_blank">tag历史测速结果整合</a>

<br>

------

### Catnet（华为云专线）

ss协议华为云CC专线机场，BGP接入Cloud Connect，华为云和AIA体验差不多，成本高，都挺好。梦迪家分站，比主站人少。速度不错。不限制设备数目。官网：https://dlj.tf/KUphrLw  

>专线: 有   
流媒体解锁：youtube Premium、HBO Max 、Abema TV 、 DAZN、PCR jP   
节点国家与地区：俄罗斯、印度、印度尼西亚、台湾、、德国、意大利、新加坡、香港、日本、美国、 荷兰、菲律宾、越南   
开业时长：1年+
UDP：支持     
入口ip数量 2   
落地ip数量 44   
协议：ss   
专门客服：有   
TG频道： [https://t.m/Catnet_CN](https://t.me/Catnet_CN)      


套餐:
>Small: 半年付120，每月70G，可4个在线设备   
Meduim：半年付270, 每月300G；月付50；可5个在线设备      
   

<details>
  <summary>具体入口与落地信息 shadowsocks流媒体解锁范围</summary>
   入口：
   China Unknown City, Huawei Cloud Service data center*2


    落地：
    Germany Frankfurt am Main, Choopa, LLC*1
    Hong Kong Central, Kirino LLC*8
    Hong Kong Kowloon, Netvigator*2
    India Bengaluru, Digital Ocean*1
    Indonesia Unknown City, APIK Media Networks*1
    Italy Milan, Seflow S.N.C. Di Marco Brame' & C.*1
    Japan Tokyo, Kirino LLC*8
    Netherlands Unknown City, Chociz Services*1
    Philippines Manila, Scloud Pte*1
    Russia St Petersburg, Misaka Network, Inc.*1
    Singapore Singapore, HIVELOCITY*1
    Singapore Singapore, Kirino LLC*7
    South Korea Seoul, Choopa, LLC*1
    Taiwan Unknown City, Kirino LLC*3
    Thailand Bangkok, Scloud Pte*1
    United States Seattle, Kirino LLC*5
    Vietnam Unknown City, FPT Telecom*1

</details>

关于华为云（云连接CC）
官方简介：云连接（Cloud Connect）能够提供一种快速构建跨区域VPC及云上多VPC与云下多数据中心之间的高速、优质、稳定的网络能力，帮助用户打造一张具有企业级规模和通信能力的全球云上网络。
华为云线路跟阿里云，腾讯云相比少了些POP，亚太地区只有香港，曼谷，新加坡，美国没POP，但是整体体验也不错。

   ![catnet测速图.png](https://cdn.jsdelivr.net/gh/hwanz/SS-SSR-V2ray/img/catnet.png)
  
   历史测速： <a href="https://honven.netlify.app/catnet%E5%8E%86%E5%8F%B2%E6%B5%8B%E9%80%9F%E7%BB%93%E6%9E%9C%E6%95%B4%E5%90%88.html" target="_blank">catnet历史测速结果整合</a>

 
 <br>
 
 ------
 
 
### Gacloud（阿里云入口） 
SS隧道，G口阿里云BGP入口，香港老板，已有机场行业多年经验。多年自有机房，国际走任播ANY。速度不错。入口总带宽4G。后期会引入专线
有分组：C优质和H精品组，入口都一样，出口精品的优先级会更高，人数不一样，精品人少，碎片负载会更少。如果有新产品或者遇到波动，会优先给精品接入更贵的产品以及优化。这2个组都是完全独立的入口出口，每个组都是2个地区入口，地域解析就近接入。新用户有10块优惠券，券后19块起。 新用户充值每满100送10块。想找人数少的机场的，这家值得推荐。
官网（使用这个链接赠送10块优惠券）：https://dlj.tf/D59Qaw7

>节点国家与地区：香港、日本、新加坡、美国、台湾   
老板肉身：香港   
UDP: 部分支持Full Cone   
开业时长：半年+   
入口ip数量 2 （深圳和上海）   
落地ip数量 33   
协议：SS   


套餐:   
>基础套餐 | BGP线路 |每月100G流量，29块/月，每月150G流量，78块/季度；每月200G流量，252/半年， |21块起 | 3个在线设备           
进阶套餐 | BGP线路,双程CN2线路 |每月100G流量，49块/月；每月150G流量，135块/季度；每月200G流量，468/半年 |21块起 |3个在线设备        

  ![gacloud测速图.png](https://honven.vercel.app/uploads/vpn/gacloud.png)
  
  
------
  
  
  
### STC-SERVER

IEPL专线+Anycast ，SSR + V2RAY协议机场，老板在香港，可以月付。也有按量付费，推荐买来当备用。即使你不买这家的套餐，也应该买个按量付费当作备用，以防买的那家出问题失联，不用不花钱还。
官网(如果打不开请切换为全局代理)： https://dlj.tf/amqkVeF



>专线: 有   
Anycast：有   
流媒体解锁：有    
节点国家与地区：香港、日本、新加坡、美国、台湾  
老板肉身：香港    
UDP: 部分支持Full Cone     
一键使用客户端： 有    
开业时长：1年+   
入口ip数量 10   
落地ip数量 32   
直连节点数量：0   

套餐:

>按量付费：0.8块/G,不用不花钱.
基础套餐 | BGP线路,线路38条 |每月100G流量，38块/月，2/3个在线客户端    
进阶套餐 |  BGP线路,线路38+13条 |每月100G流量，48块/月，3/4个在线客户端     
旗舰套餐 |  BGP线路+IPLC线路,线路38+13+7条 |每月100G流量，88块/月，4/5个在线客户端    
企业套餐 |  BGP线路+IPLC线路,线路38+13+7+4条 |每月100G流量，108块/月，5/6个在线客户端   

<details>
  <summary>具体入口和落地信息</summary>
  
    入口：
     China Nanjing, China Unicom Liaoning*1
     China Pudong, China Unicom Shanghai*1
     China Shanghai, China Unicom Shanghai*1
     China Suzhou, China Mobile*2
     China Unknown City, CHINATELECOM JiangSu YangZhou IDC networkdescr: Ya*1
     China Unknown City, China Mobile*2
     China Unknown City, China Telecom Shanghai*2
  

    落地：
    China Tianjin, SuperInternet ACCESS Pte*2
    Hong Kong Central, China Mobile Hong Kong Broadband*1
    Hong Kong Central, Hong Kong Broadband Network*2
    Hong Kong Kowloon, Netvigator*5
    Hong Kong Kwun Hang, China Mobile Hong Kong Broadband*1
    Hong Kong Lai Chi Kok, Hong Kong Broadband Network*1
    Hong Kong Sham Tseng, Netvigator*1
    Hong Kong Tin Shui Wai, Netvigator*1
    Hong Kong Tuen Mun, Netvigator*4
    Japan Tokyo, Kirino LLC*3
    Taiwan New Taipei, Chunghwa Telecom*5
    Taiwan Tainan City, Chunghwa Telecom*4
    United States Los Angeles, DMIT*1
    United States Seattle, Kirino LLC*1

   
</details>

   
  ![STC-SERVER测速图.png](https://cdn.jsdelivr.net/gh/hwanz/SS-SSR-V2ray/img/stc.jpg)

   历史测速： <a href="https://honven.netlify.app/stc%E5%8E%86%E5%8F%B2%E6%B5%8B%E9%80%9F%E7%BB%93%E6%9E%9C%E6%95%B4%E5%90%88.html" target="_blank">stc历史测速结果整合</a>

<br>
  
  
  ------



###  少数派（IEPL专线）

ssr+v2ray，全IEPL专线机场。后端负载均衡，也挺稳。需要注意提前续费，因为没有代理上不去这家官网。官网(已屏蔽中国大陆访问，请切换为全局代理打开)：  <a href="https://dlj.tf/5bwQ7oB" target="_blank">https://dlj.tf/5bwQ7oB</a>


>专线：有   
原生节点：有     
落地：美国、台湾、新加坡、日本、香港、德国、英国、俄罗斯、菲律宾     
UDP:支持        
老板肉身：墙外    
开业时长：1年+    
UDP: 部分支持Full Cone,需要自己手动开
一键使用客户端： 有    
入口ip数量 4    
落地ip数量 22        
直连节点数量：0        
协议：SSR + V2ray    
TG频道： [少数派的广而告之](https://t.me/joinchat/Rw92xD_F57WssTZj)    


套餐：

套餐 | 流量 | 价格 |客户端数目 
---- | --- | --- | --- 
1 | 200G/月 |29/月 | 3
2 | 300G/月 |45/月 | 3
3 | 600G/月 |89/月 | 10


<details>
  <summary>少数派具体入口和落地信息</summary>
   
     入口
    China Beijing, Beijing Guanghuan Xinwang Digital*2
    China Unknown City, China Mobile*2  

    落地
    China Tianjin, SuperInternet ACCESS Pte*1
    China Unknown City, Amazon.com*2
    Hong Kong Central, HGC Broadband*1
    Hong Kong Central, Netvigator*2
    Hong Kong Shatin, Hong Kong Broadband Network*1
    Hong Kong Unknown City, Amazon.com*2
    Japan Tokyo, Linode*3
    Philippines Manila, IP-Converge Data Center*1
    Russia Moscow, Forest NET*1
    Singapore Singapore, Amazon.com*2
    Taiwan New Taipei, Chunghwa Telecom*2
    United Kingdom Kington, FxTransit LTD*1
    United States New Castle, Nato Research*3
  
</details>
  
  最新测速图更新在频道：https://t.me/jichangtj
 ![少数派测速图.jpg](https://cdn.jsdelivr.net/gh/hwanz/SS-SSR-V2ray/img/shaoshupai.png)
 
 历史测速： <a href="https://honven.netlify.app/%E5%B0%91%E6%95%B0%E6%B4%BE%E5%8E%86%E5%8F%B2%E6%B5%8B%E9%80%9F%E7%BB%93%E6%9E%9C%E6%95%B4%E5%90%88.html" target="_blank">少数派历史测速结果整合</a>


<br>

------

### 跑路云（IEPL专线）

IEPL专线+BGP中转SS+V2ray机场。实力大佬，手上很多家机场，这家是他们家最大的，也是线路类似最多的。不少线路是它自家的。STANDARD套餐主打公网中转（DRL节点），PREMIUM套餐主打专线（BGP节点）并且PREMIUM套餐支持90％SLA。总接入IEPL带宽已达1.6Gpbs。
圈内主流能拿得到的专线全部集齐了：卷中港、华为广港 、腾讯AIA香港 、 香港阿里云CEN 、 上海-香港Azure骨干 、佛山电信-香港IEPL 、深圳移动-香港IEPL；
nat、流量转发、独立线路都有。10块里面左右很值得推荐了。
官网(使用这个链接赠送1块余额)： [https://dlj.tf/CmeG4ih](https://dlj.tf/CmeG4ih)

>专线: 有    
免费公益节点：4条直连线路    
游戏节点：GAME游戏加速节点为SSR协议，VIP3以上才有SSR    
流媒体解锁：Netflix、youtube Premium、HBO Max 、Abema TV 、 DAZN、PCR jP     
节点国家与地区：香港、日本、新加坡、美国、台湾、马来西亚、韩国、印度尼西亚、澳门、以色列、俄罗斯、冰岛、加拿大、印度、土耳其、巴西、德国、法国、澳大利亚、瑞士、英国、菲律宾、阿根廷    
老板肉身：境外     
开业时长：1年+     
UDP：支持     
入口ip数量 8        
落地ip数量 58    
客户端数目：2个    
协议：SSR + V2ray(建议ssr)    
专门客服：有    
TG频道： [https://t.me/paoluztz](https://t.me/paoluztz)    
奈飞Netflix：部分线路可看非自制剧      


套餐:
>VIP2：8块/月,50G,只有V2ray协议； 142/年,128GB流量/月。（别买v2等级的套餐!!!）          
VIP3：标准12.90块/月,增量90G； 19.90块/月,200G； 年付232.9年,288GB流量/月； SS+V2ray协议（建议这个起！）。          
VIP4：标准32.90块/月，350G； 增量41.90块/月,450G；年 付345.9/年,428GB流量/月； SS+V2ray协议+BGP专有路线（最好买这个套餐）。          


<details>
  <summary>具体入口与落地信息 shadowsocks流媒体解锁范围</summary>
  
     入口：
      China Beijing, Beijing Guanghuan Xinwang Digital× 1
      China Nanjing, China Unicom Liaoning× 1
      China Ningbo, China Mobile× 1
      China Unknown City, China Mobile× 6
      China Unknown City, China Mobile Guangdong× 1
      China Unknown City, China Telecom jiangsu province backbone× 1
      China Unknown City, China Unicom Liaoning× 1
      South Africa Unknown City, Cnservers LLC× 2
      Taiwan New Taipei, Chunghwa Telecom× 7
      Taiwan Xindian, Chunghwa Telecom× 1


    落地：
    Argentina Buenos Aires, T-Wireless× 1
    Australia Unknown City, Network Presence× 1
    Belgium Dessel, iFog GmbH× 1
    Brazil Campinas, Microsoft Azure× 1
    Canada Unknown City, OVH SAS× 1
    China Tianjin, SuperInternet ACCESS Pte× 1
    France Unknown City, VIRTUA SYSTEMS× 1
    Germany Unknown City, Accelerated IT Services GmbH× 1
    Hong Kong Central, China Mobile Hong Kong Broadband× 1
    Hong Kong Central, Scloud Pte× 1
    Hong Kong Shatin, Tianhai InfoTech× 1
    Hong Kong Tsimshatsui, Netvigator× 3
    Hong Kong Unknown City, Amazon.com× 1
    Hong Kong Unknown City, DMIT× 1
    Hong Kong Unknown City, HGC Broadband× 8
    Iceland Unknown City, 1984 ehf× 1
    India Mumbai, Linode× 1
    Indonesia Unknown City, PT Cloud Hosting Indonesia× 1
    Israel Tel Aviv, O.m.c. Computers & Communications Ltd× 1
    Japan Chiyoda-ku, So-net× 1
    Japan Heiwajima, Choopa, LLC× 3
    Japan Tokyo, GMO GlobalSign Holdings K.K.× 1
    Japan Tokyo, Linode× 2
    Japan Tokyo, OSOA Corporation., LTD× 2
    Japan Tokyo, Oracle Cloud× 2
    Japan Tokyo, SAKURA Internet× 1
    Japan Unknown City, SAKURA Internet× 1
    Macao Macao, MTel SAR× 1
    Malaysia Kamunting, TM Net× 1
    Philippines Unknown City, Eastern Communications× 1
    Russia Novosibirsk, Adman LLC× 1
    Russia St Petersburg, Misaka Network, Inc.× 1
    Russia Unknown City, Adman LLC× 1
    Russia Unknown City, LLC Baxet× 1
    Singapore Singapore, DigitalOcean× 2
    Singapore Singapore, Kirino LLC× 1
    Singapore Singapore, Linode× 2
    South Africa Unknown City, Cnservers LLC× 3
    South Korea Seoul, Oracle Cloud× 2
    Switzerland Unknown City, FSIT AG× 1
    Taiwan New Taipei, Chunghwa Telecom× 14
    Taiwan Xindian, Chunghwa Telecom× 1
    Turkey Istanbul, Hostigger INC.× 1
    United Kingdom London, Digital Ocean× 1
    United States Fremont, Linode× 1
    United States Los Angeles, DediPath× 6
    United States Reston, Misaka Network, Inc.× 1
    United States Seattle, Kirino LLC× 4
    Vietnam Unknown City, FPT Telecom Company× 1


    ----------shadowsocks流媒体解锁范围------------
    香港：Netflix、TVB、HBO GO、Fox+、Bilibili 港澳台、Viu

    日本：Netflix、Pixiv、Niconico
    日本(带Ex)除了日本解锁的内容以外额外解锁 Happyon、AbemaTV、DMM、DAZN、TVer、大部分日本手游

    台湾：Netflix、Bilibili 港澳台、動畫瘋、四季線上影視、Line TV

    美国：Netflix、Hulu、HBO、Amazon Video、Disney Now、Disney+
    美国(带Ex)：除了上条美国解锁的内容以外额外解锁 Discovery+

    英国：Netflix、BBC、Channel 4
    新加坡、马来西亚：Netflix、Fox+、Amazon Video 
    瑞士、冰岛、德国、澳门等节点 默认支持Netflix

    带Y标签节点: 不支持流媒体

   
</details>


ss节点南方移动测速结果：

  ![跑路云ss测速图.png](https://cdn.jsdelivr.net/gh/hwanz/SS-SSR-V2ray/img/paoluss.png)

  历史测速： <a href="https://honven.netlify.app/%E8%B7%91%E8%B7%AF%E4%BA%91%E5%8E%86%E5%8F%B2%E6%B5%8B%E9%80%9F%E7%BB%93%E6%9E%9C%E6%95%B4%E5%90%88.html" target="_blank">跑路云历史测速结果整合</a>
  
<br>

------

### Blinkload（IEPL+AIA专线）

ss协议全IEPL+部分AIA+BGP专线稳定运营5年的老机场，香港老板，自有机房，总稳定性很好。年付起。Business套餐有AIA,是最稳的套餐且无限速，有钱推荐你买这个肯定没错，被跑路机场搞怕了，想找多年稳定运营的这家值得推荐。[官网注册地址](https://dlj.tf/a88T4sC)


>专线: 有    
UDP：部分FullCone-PortRestrictedCone        
落地：台湾、香港、新加坡、日本、美国    
开业时长：5年+    
UDP：部分FullCone-PortRestrictedCone
入口ip数量 29    
落地ip数量 29    
流媒体解锁：Netflix、youtube Premium、HBO Max 、 DAZN、PCR jP    
协议：SSR + SS    
专门客服：有       
TG频道： [https://t.me/thessrchannel](https://t.me/thessrchannel)       
奈飞Netflix：ipv6解锁部分线路可看非自制剧      



套餐：

套餐 | 线路 | 流量 | 价格 |客户端数目 
---- | ---  | --- | --- | --- 
Pro | 专线  | 200Gi/月起 | 499.9 HKD/年 | 6+
Lite | 专线 | 100G/月 | 399.9 HKD/年| 6+
Micro | 专线 | 50G/月 | 299.9 HKD/年| 6+
Business |专线 | 1000G/月起 | 2888/年起 | 30+


<details>
  <summary>Pro套餐具体入口与落地信息</summary>
          
    入口:
    China Unknown City, China Mobile 
    China Unknown City, China Telecom Guangdong

    落地
    Hong Kong Unknown City, Blinkload Technology Co., Ltd Hong Kong× 12
    Singapore Unknown City, Blinkload Technology Co., Ltd× 4
    Taiwan New Taipei, Chunghwa Telecom× 3
    United States Unknown City, Blinkload Technology Co., Ltd× 4

   
</details>

Pro套餐2021-05-29南方移动测速结果：

 ![Blinkload测速图.png](https://cdn.jsdelivr.net/gh/hwanz/SS-SSR-V2ray/img/blinkload.png)

  历史测速： <a href="https://honven.netlify.app/blinkload%E5%8E%86%E5%8F%B2%E6%B5%8B%E9%80%9F%E7%BB%93%E6%9E%9C%E6%95%B4%E5%90%88.html" target="_blank">blinkload历史测速结果整合</a>

<br>

------


### AAEX（IELP专线+CN2）

IELP/IPLC专线+CN2 中继,ss协议。老板也是IDC，机场服务器提供商。
不限制设备数目。
官网：（不需要代理）  <a href="https://dlj.tf/r4UFMEK" target="_blank">https://dlj.tf/r4UFMEK</a> 
官网链接2： <a href="https://bit.ly/32pxvlR" target="_blank">https://bit.ly/32pxvlR</a>

注册新账号需要先购买新套餐。
需要 ** 无限流量套餐 ** 的机场，就推荐这家。搞无限流量套餐的机场很少，因为机场主怕被用破产。稳定的的就更少了。
我之前买来下数据的，每个月下4T左右。速度看自家带宽了。200M跑满是可以的。

>专线: 有   
中转：有   
原生节点：有   
节点国家与地区：多   
入口：华东，华南。   
落地：香港、台湾、日本、美国、德国、法国、英国、瑞士、爱尔兰、俄罗斯、加拿大、新加坡、澳大利亚
开业时长：4年+      
UDP：支持Full Cone    
入口ip数量 3   
落地ip数量 42   
直连节点数量：0   
IPv6:支持   
协议：SSR + SS   
专门客服：有   
TG频道： [https://t.me/AAEX_Channel](https://t.me/AAEX_Channel)      


套餐：

>无限流量套餐 | 中转+专线，全部节点 |无限流量 |99块/月 | 每2T工单重置一次，不限制设备数目          
标准套餐 | 中转+专线，全部节点| 300GG/月 |150块/月 | 不限制设备数目          


<details>

  <summary>具体入口与落地信息</summary>
  
       入口
      China Shanghai, China Telecom Shanghai×2
      China Unknown City, China Mobile×1

    落地
    Australia Sydney, Linode×1
    Germany Frankfurt am Main, Linode×1
    Hong Kong Central, Netvigator×1
    Hong Kong Unknown City, Aaex Network Technology Ltd×10
    Japan Tokyo, Aaex Network Technology Ltd×9
    Singapore Singapore, OVH SAS×1
    Taiwan Miaoli, Chunghwa Telecom×5
    Taiwan Nantun, Chunghwa Telecom×5
    United States Unknown City, Aaex Network Technology Ltd×9

</details>

<br>

  
 ![AAEX测速图.png](https://cdn.jsdelivr.net/gh/hwanz/SS-SSR-V2ray/img/aaex.png)

  历史测速： <a href="https://honven.netlify.app/aaex%E5%8E%86%E5%8F%B2%E6%B5%8B%E9%80%9F%E7%BB%93%E6%9E%9C%E6%95%B4%E5%90%88.html" target="_blank">aaex历史测速结果整合</a>

<br>

------



### Just my sock

搬瓦工官方的ss+v2ray机场：线路是IPLC/GIA+CN2   
相比私人的机场，好处就是安全，无审计，基本不会跑路，信息泄露概率小。   
对安全性的重视程度较大的和担心私人机场跑路，有敏感操作的用户，推荐买这家。   
支持paypal和支付宝支付，5.2%折扣循环优惠码：JMS9272283  
官网注册地址,需要代理或全局模式访问 :  <a href="https://bit.ly/3weANGp" target="_blank">https://bit.ly/3weANGp</a>

>专线: 有     
落地：香港、日本、美国     
开业时长：1年+     
协议：SSR + V2ray    
专门客服：有      



套餐:


Just My Socks IPLC HK 100 ** EARLY ACCESS ，IPLC香港：    
v2ray协议，3条线路，100G/每月15刀，限速100Mbps，3个设备。新出的套餐，搬瓦工还是懂得大家需要什么。   
不一定有货，挺抢手的，已入手观察中，产品购买链接： <a href="https://bit.ly/39zLsSe" target="_blank">https://bit.ly/39zLsSe</a>

Just My Socks Hong Kong  香港节点： 
100流量，34.99美元/月,3个设备。限速100Mbps  
500G流量，149.99美元/月,5个设备.限速500Mbps  


Just My Socks Tokyo   日本节点：  
100G流量，29.99美元/月,3个设备。限速100Mbps  
500G流量，135.99美元/月,5个设备.限速200Mbps  


Just My Socks LA 洛杉矶节点（这个套餐不建议，很慢）：  
500G流量，5.88美元/月,5个设备。限速2.5 Gbps  
1T流量，9.88美元/月,不限设备数。限速5 Gbps  
5T流量，48.99美元/月,不限设备数。限速5 Gbps  

肯定还是有人想自建，最好购买它家CN2 GIA线路：  <a href="https://bit.ly/3sDxUwC" target="_blank">https://bit.ly/3sDxUwC</a> 

  JMS IPLC测速图

  ![JMS IPLC测速图.jpg](https://cdn.jsdelivr.net/gh/hwanz/SS-SSR-V2ray/img/jms.jpg)
        

<br>

------


### 翼游（公网中转）

ssr+v2ray+trojan，中继机场。从线路质量来看，价格算是比较便宜的。有各个平台小白一键使用客户端。   
官网(如果打不开请切换为全局代理)：  <a href="https://dlj.tf/jb7tT7z" target="_blank">https://dlj.tf/jb7tT7z</a> 


>中继：有     
原生节点：有     
落地：美国、台湾、新加坡、日本、香港     
老板肉身：北美     
开业时长：1年+   
入口ip数量 1   
UDP：部分支持Full Cone     
落地ip数量 20   
直连节点数量：0  
一键使用客户端： 有     
协议：SSR + V2ray +Trojan    
专门客服：有      



套餐 |  流量 | 价格 |客户端数目 
---- |  --- | --- | --- 
1 |60G/月 |10块/月 | 2
2 | 150G/月 |15块/月 | 3
3 | 300G/月 |25块/月 | 5
4 | 500G/月 |35块/月 | 6
5 | 1000G/月 |75块/月 | 18


<details>
  <summary>翼游SSR+V2ray+trojan具体入口和落地信息</summary>

    入口：
    China Unknown City, China Mobile*1

    落地：
    China Unknown City, Amazon.com*1
    Hong Kong Central, Microsoft Azure*1
    Hong Kong Unknown City, Kirino LLC*4
    Japan Tokyo, Amazon.com*3
    Japan Tokyo, Linode*1
    Singapore Singapore, Amazon.com*1
    Singapore Singapore, Microsoft Azure*2
    South Korea Seoul, Microsoft Azure*1
    Taiwan Chang-hua, Chunghwa Telecom*2
    United States San Jose, Amazon.com*2
    United States Unknown City, Microsoft Azure*2
  
</details>

  
  ![翼游测速图.png](https://cdn.jsdelivr.net/gh/hwanz/SS-SSR-V2ray/img/yiyou.png)
  
  历史测速： <a href="https://honven.netlify.app/yiyo%E5%8E%86%E5%8F%B2%E6%B5%8B%E9%80%9F%E7%BB%93%E6%9E%9C%E6%95%B4%E5%90%88.html" target="_blank">yiyo历史测速结果整合</a>

<br>


------

### 羊圈

 Trojan/SSR 协议大机场。推荐这家是因为有人需要回国线路，现在很多机场都没回国了，难得找到一家。官网：https://dlj.tf/a3J7Mnp        

>解锁国内音乐/视频/直播  
协议：回国是Trojan  
开业时长：5年+  
TG频道：MieLink｜羊圈 - 通知频道   

套餐:  
回国服务：每月100G流量，月付69块。2个在线ip。  

------


<br>

# 机场就一句话：一分钱一分货！机场推荐是信息差，不了解的人很容易被坑。被推荐很垃圾的机场。
为啥都是推荐机场主肉身在墙外的机场：因为肉身在墙内很容易被抓。
<br>大家没太多时间天天找机场换着用。肉身在墙外相对安全，跑路概率相对小。

如果觉得有帮助到您，Star下呗~~~ 经常更新！！！


telegram机场观察频道，机场推荐，机场优惠，新闻，欢迎关注：[https://t.me/jichangtj](https://t.me/jichangtj)

原文: [https://dlj.tf/sjKR2eb](https://dlj.tf/sjKR2eb)

我的科学上网过程：一开始是用免费的vpn，比如自由门，无界，蓝灯等，很慢很慢；也用过浏览器插件比如谷歌上网助手，但只能上谷歌；还通过改hosts文件上谷歌，也是很快就得重新换新的；然后也用别人分享的ss/ssr节点，一般没过多久基本就用不了了；后面决定花钱自己买vps线路比如vultr、搬瓦工、谷歌云和aws白嫖搭建ss/v2ray，但是很快就被封了，换ip还要钱，或者晚高峰速度很慢；然后才到买收费机场，一开始贪便宜，也是网上搜，也很担心博主为了恰饭推荐不好的机场。然后就是买过很便宜的机场，人贪便宜的心理作祟，便宜肯定人多，然后堵了，也是坑了。机场体验不好，大部分时候是因为使用的人多了但是机场主不扩容，就堵了。例子太多了。只要买过低价机场的都知道。目前为止，体验最好的还是收费机场。再也不想折腾了。


## 其它博客
<br>
<a href="https://honven.netlify.app/%E7%A7%91%E5%AD%A6%E4%B8%8A%E7%BD%91%E6%96%B9%E6%B3%95%E6%B1%87%E6%80%BB(%E5%85%8D%E8%B4%B9%E4%B8%8E%E4%BB%98%E8%B4%B9).html" target="_blank">稳定高速机场推荐</a> 

windows客户端：
[win/mac客户端推荐使用clash,可以定制规则，v2ray和ss/ssr可以一起使用，自动选择延迟最低的节点](https://honven.top/clash%E6%95%99%E7%A8%8B.html)

游戏客户端推荐：
[netch使用教程](https://honven.netlify.app/netch%E6%95%99%E7%A8%8B.html)

[sstap使用教程](https://honven.netlify.app/sstap%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B.html)

https://github.com/nekohasekai/SagerNet

安卓客户端推荐：
[Android—Clash for Android 使用教程](https://honven.netlify.app/Android%E2%80%94Clash%20for%20Android%20%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B.html)

[安卓ssr-v2ray-trojan代理客户端ssrray使用教程](https://honven.netlify.app/%E5%AE%89%E5%8D%93ssr-v2ray-trojan%E4%BB%A3%E7%90%86%E5%AE%A2%E6%88%B7%E7%AB%AFssrray%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B.html)

SagerNet: https://github.com/SagerNet/SagerNet 
支持的代理协议: SOCKS、Shadowsocks、SSR、VMess、VLESS、Trojan.

<br>
IOS客户端推荐：

<a href="https://honven.netlify.app/IOS-Shadowrocket(%E5%B0%8F%E7%81%AB%E7%AE%AD)%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B.html" target="_blank">IOS-Shadowrocket(小火箭)使用教程</a> 

[Quantumult简单使用教程](https://honven.netlify.app/Quantumult%E7%AE%80%E5%8D%95%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B.html)

[QuantumultX小白简单使用教程](https://honven.netlify.app/QuantumultX%E5%B0%8F%E7%99%BD%E7%AE%80%E5%8D%95%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B.html)

[路由器老毛子Padavan固件ss/v2ray机场服务器订阅设置和clash配置](https://honven.netlify.app/%E8%80%81%E6%AF%9B%E5%AD%90Padavan%E5%9B%BA%E4%BB%B6ssv2ray%E6%9C%BA%E5%9C%BA%E6%9C%8D%E5%8A%A1%E5%99%A8%E8%AE%A2%E9%98%85%E4%B8%8Eclash%E9%85%8D%E7%BD%AE.html)

[机场订阅链接转换收集与教程](https://honven.netlify.app/%E6%9C%BA%E5%9C%BA%E8%AE%A2%E9%98%85%E9%93%BE%E6%8E%A5%E8%BD%AC%E6%8D%A2%E6%95%99%E7%A8%8B.html):支持ss、ssr、v2ray转clash/quantumultx等

[Telegram频道推荐](https://honven.netlify.app/telegram%E7%94%B5%E6%8A%A5%E9%A2%91%E9%81%93%E7%BE%A4%E7%BB%84%E6%8E%A8%E8%8D%90.html)
<br>
