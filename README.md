# AI API中转站推荐与评测

## 写在前面的话
2026-04-18  更新

不想看下面的长文, 就看这段话.

对于愿意折腾的人, OpenAI最近风控松了点, 所以现在最便宜的方案, 就是去买一些 GPT plus的号, 一个月几块钱. 多买几个号,  搭配cliproxyAPI, 一个月就足够用了.

对于不愿意折腾的人, 但是预算又一般的人(其实就是大部分人), 可以在下面推荐的站点里, 选一些有GPT5.4的中转站. 
现在GPT5.4 基本都没有掺水的, 一般是人民币¥1.5(进)9(出)/一百万Token左右, 物美又价廉. 
对于普通用法, 一个月不会超过100块钱, 比国产的各种编程包便宜,效果又好很多.

追求效果的, 可以上Claude, 效果好一些, 价格要贵很多. 选Claude就要认真看下下面的推荐文章. 
一般来说,价格太便宜的,要不是掺水, 要不是不稳定,要不是收费有坑, 要注意点. 

----

我们先在国内想要安心的使用最先进的AI API 真是太难了. 国外官方的AI不仅价格贵, 而且经常被误封账号, 就会误事.

选择一个好的中转站不容易, 要看下面的这些点

1. 最重要的是稳定，如果它自己经常宕机或延迟极高，那不仅没省事反而耽误事. 所以要优先买那些信誉好,运行时间长, 最好有群的站
2  第二个是关注服务器节点位置。对于国内开发者，如果中转服务器在香港、新加坡, 就比在美国的站点好很多.
3. 模型的覆盖性: 一个好的中转站应该让你一站式调用全球顶尖模型, 最好能尽快上官方的最新模型.
4. 中转站的收费有很多问题. 很多站看起来价格低, 实际运行起来价格很高. Token计数, 或者价格费率, 都是造成价格不同的很重要原因.  另外站点最好要有清晰的账单, 否则将来哪一天突然账单异常了,都查不到原因. 也要警惕价格异常便宜的模型, 大概率是拿着GLM这种低价国产模型代替高价的国外模型.
5. 每个站都有跑路的危险, 优先选择公司运营的站点. 还有他们客服响应问题的速度, 站点速率波动时有没有通知这些.

为了解决下面的问题, 我对使用过的中转站做一个评价.

在所有使用之前, 切记一点, 这个行业不稳定, 不要大额充值, 用多少充多少.

站点的价格更新太快了..我努力让这些价格是准确的.  

[hvoy网站](https://hvoy.ai/#sonnet-4-6-ranking) 现在上面增加排行, 有后台不停检测端口, 并且更新实时价格,可以从排行榜上挑选.


![banner](pic/banner.png)

## 推荐的

### [PackyCode](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fwww.packyapi.com%2Fregister%3Faff%3DgF1p&name=PackyCode&source=git)
PackyCode 大约是24年底25年初开始活跃, 是国内比较早针对Claude Code进行优化的供应商.

这个站点与开源社区互动比较频繁, 站长在x上也非常活跃, 客服响应比较快. 随着发展, 这个站已经是很多中转站的上游供应商.

2026-4-3 更新, 现在最便宜的是Sonnet4.6 是人民币¥2.4(进)12(出)/一百万Token, Opus4.6是人民币4(进)20(出)/一百万Token 质量一般.

质量较好的渠道是 Sonnet4.6 人民币 ¥7.5(进)37.5(出)/一百万Token, Opus4.6 12.5(进)62.5(出)/一百万Token , 几乎不注水

Codex现在是人民币¥1.25(进)7.5(出)/一百万Token

Gemini现在好多渠道都用不了,或者响应速度巨慢, 用下来只有PackyCode速度是最快的, 质量还可以. 价格是 Gemini 3.1 Pro是 人民币¥6(进)36(出)/一百万Token.

他们对于国内的模型支持比较全, 支持阿里百炼的api, MiniMax(官方价格的5折),GLM(九折). 

新人注册送1元, 可以先试试再决定购买.  最少充值50块, 支持开发票.



### [RightCode](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fwww.right.codes%2Fregister%3Faff%3Da8707f0d&name=RightCode&source=git)
就是为编程准备的, 只支持Claude, Gemini和GPT的接口. 

~价格很便宜, Kiro逆向的接口大概是官网的0.4折. Opus 4.6 反代的价格是人民币¥1.5(进)7.5(出)/一百万Token, Sonnet 4.6的价格是人民币¥0.9(进)4.5(出)/一百万Token ~ (2026/3/22更新, 但是反代渠道最近不可用)


值得推荐的渠道是 /claude 渠道, Sonnet4.6 价格是人民币¥4.5(进)22.5(出)/一百万Token, Opus4.6 价格是人民币¥7.5(进)37.5(出)/一百万Token. 

质量也不错, 对的起这个价格.

~Codex有月套餐, 50人民币一个月对应每日可用60$+昨日未用完的额度, 80人民币一个月对应每天120元+昨日未用完的额度.是目前看到最便宜的.(2026/3/29更新, team没了, 月套餐也没了)~

GPT 现在比较划算一点, GPT5.4 是人民币¥1.25(进)7.5(出)/一百万Token

Gemini系列的接口也很便宜, 大概是官网价格的1折.

有网友说有时拿别的模型掺水, 我自己试了一段时间还好.

最少可以充1元 , 获得5元的额度, 先试试效果.

文档非常清晰, 接口响应速度比较快.


### [Poixe AI](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fpoixe.com%2Fi%2Fsgurn9&name=Poixe%20AI&source=git)
这个站是一个从 2024 年开始做, 在中转站里, 算是干了非常久啦

整个站的风格我很喜欢, 不是审美疲劳的New API的这种风格.

支持 GPT,Claude,Gemini,DeepSeek,Doubao,Qwen ,Grok 这些模型.

不同级别会员价格不一样,充一点钱就能Vip1,能八折.

Sonnet4.6 的价格是人民币 16.8/84 一百万 Token, Opus4.6 价格是人民币 28/140 一百万 Token.
GPT5.4 价格是人民币 14/84 一百万 Token.

价格是不便宜. 我试了下接口, 接口质量是相当好, 完全没掺水, 速度也快.
网站上提供一个免费的接口,譬如 GPT4o这种.
支持开发票.

总体来说,这个适合企业客户, 质量好, 价格也在这里摆着.

2026-04-17 更新: 他们新推退出了一些反代的模型(包括sonnet4.6), 这个反代的价格相对亲民了很多.
Sonnet4.6的价格是人民币 10.5/63 一百万Token.(虽然还是不便宜)

每个用户每天可以免费用一些反代出来的sonnet-4.6和gpt5.3.   
轻度用户可以去白嫖, sonnet4-6每天可以白嫖50次.[页面在这里](https://poixe.com/pricing?i=sgurn9), 后面有free就是可以免费用几次的. 

btw:这个站点的域名老容易打错.

### [柏拉图AI](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fapi.bltcy.ai%2Fregister&name=%E6%9F%8F%E6%8B%89%E5%9B%BEAI&source=git)
柏拉图好像是一个比较老的API站, 2024年就有了.
他的优点是支持市面上基本上所有的模型, 除了常见的OpenAI, Claude, Gemini这三家外, DeepSeek, 豆包, MiniMax, QWen,GLM这些也支持, 他们还支持  Mid-journey(文生图),suno_music(文生歌), 快手可灵(文生视频),Ideogram(文生图)等等.
可能别的地方找不到的接口, 都可以在这里找到.

这一点非常厉害.

另外, 这个网站除了大陆外, 还有美国,香港的接入点,还不错. 接口的响应也挺快.

用户注册送2毛钱, 每天签到能送一点钱.

价格方面, 质量比较好的Claude Opus4.6是人民币¥10(进)50(出)/一百万Token, Sonnet4.6是人民币¥6(进)30(出)/一百万Token. 

GPT5.4是人民币¥2.5(进)15(出)/一百万Token.

不支持月卡.

接口挺稳定的, 适合企业使用使用.
可以开发票.

### [DawCode](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fdawclaudecode.com%2Fregister%3Faff%3Dnbv1&name=DawCode&source=git)
2026年新开的一个站点, 提供Claude, GPT,Gemini三种类型的API.

~价格也不贵, 逆向出来Opus4.6 价格是人民币¥2(进)10(出)/一百万Token.~
2026-4-13 更新: 现在价格不便宜了, 比较好用的是cc-stu分组 Opus4.6 是人民币¥7.5(进)37.5(出)/一百万Token, Sonnet4.6是人民币¥4.5(进)22.5(出)/一百万Token

目前不支持GPT5.4, GPT5.3-codex的价格是¥1(进)6(出)/一百万Token.

有套餐, 但是价格一般, 最便宜的是188一个月, 每天只有10元的额度.

提供了几个线路, 但是接口响应速度一般. 但是看监控稳定性还可以.

我试了下MAX和给Claude Code的接口, 质量还挺好. 

优点是新用户注册送4块钱的额度, 每天可以签到送一些额度. 很适合进行尝试, 感觉不错再充钱


### [云雾AI](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fyunwu.ai%2Fregister%3Faff%3Dh4RW&name=%E4%BA%91%E9%9B%BEAI&source=git)
这也是一个老牌的中转站

优点是, 支持的模型很多, Claude, GPT, Gemini, DeepSeek这些常用的, Qwen, Doubao, Midjourney, Kling, Minimax, 文心一言, 这些都支持.
上新模型也比较快, 更多的是面向企业的服务, 稳定性挺好, 还可以开发票.

有美国和国内的高防域名.

Claude 接口方面, 他们的逆向出来的东西不是很行.

可以使用Claude code专用组, Opus4.6的价格是人民币¥6(进)30(出)/一百万Token. 我自己测试了下, 感觉没掺水.

GPT 5.4是人民币¥1(进)6(出)/一百万Token. 价格是不便宜.

追求稳定的企业客户可以上, 稳定性还行.

新用户送一点钱,每天签到还能送点钱, 值得试试. 

### [发现AI](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fwww.findcg.com%2Fregister%3Fref%3DR98526288a85c&name=%E5%8F%91%E7%8E%B0AI&source=git)
发现AI是2026年3月上线的一个站点, 只支持GPT, Claude和Gemini的接口

MAX 的Sonnet4.6 是人民币¥12(进)60(出)/一百万Token, Opus4.6 是人民币¥20(进)100(出)/一百万Token. 价格是不便宜.
也支持按次收费, 0.05人民币一次, 比很多二次元的动辄0.1人民币一次要便宜很多

也有Codex接口, 目前是GPT5.4 是人民币 ~¥0.001(进)0.006(出)/一百万Token,  **就是免费了**, 挺厚道的.~ 
(3-30 更新, 因为team封号潮, 现在要 人民币¥0.63(进)3.8(出)/一百万Token)

用户注册送0.1元额度, 可以进行尝试. 每次最少充1元. 

推荐现在需要使用API切愿意切换的, 可以注册这个站, 免费蹬. 
缺点是, 我这里连这个网站速度有点慢, 不知道你们那里如何.
新站记得少充点钱.

## 中性

###  [AI派](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fapi.aipaibox.com%2Fregister%3Faff%3DGivs&name=AI%E6%B4%BE&source=git)
这也是一个比较新的网站

只支持Claude, Gemini, GPT. 刚开始支持NanoBanan2, 4k文生图

Claude方面, 好玩的是只支持Sonnet4.6和Opus4.6, 其实也是, 与其用4.0那些接口, 还不如用国产的呢.

价格方面, Sonnet4.6 最便宜是"自营"的号池, 人民币¥0.9(进)4.5(出)/一百万Token, Opus4.6的是人民币¥1.6(进)8(出)/一百万Token.
还有反重力反代的, 价格比"自营"的贵10%左右.
我试了下, 质量很不错,几乎不注水

*不过需要注意的是, 这个站的缓存价格比较贵,是0.5倍. (一般网站都在0.1-0.2倍之间). *

~GPT5.4刚上, 价格是人民币¥0.5(进)3(出)/一百万Token.~(又下了)

Gemini 3.1 pro价格是¥1.8(进)10(出)/一百万Token.

新用户登录送0.2的额度, 可以去试试. 最低充值0.2人民币, 先试试效果.

少充点, 以防跑路.

2026-4-11 更新
这个站最近claude相关接口返回特别慢.使用起来很难受

### [SunnyPumpkinAPI](https://hvoy.ai/relaySite?name=SunnyPumpkinAPI&source=git)
2024年开始做的一个网站, 站长人还挺好的.

支持GPT, Claude, Gemini,Grok, Kling接口.

Sonnet4.6便宜的接口价格是 人民币4.5(进)/22.5(出) 一百万Token
Opus4.6 便宜的接口价格是 人民币7.5(进)/37.5(出) 一百万Token,
接口质量都还行

Gemini3.1 Pro 的接口价格是 人民币0.4(进)/2.4(出) 一百万Token, 价格不贵, 但是接口有时会429限速.

不过好像最近因为接口压力大, 暂停注册了. 等开放注册了可以去试试

### [SSSAICode](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fwww.sssaicode.com%2Fregister%3Fref%3DBO64DM&name=SSSAICode&source=git)
大概是2025年开始的一个网站, 主要给编程准备的. 提供Claude, GPT,Gemini三种类型的API.
可用率还不错, 文档非常完善, 可以看得出是用了心做的.

有香港和美国的API节点,接口响应速度比较快.

价格方面, 逆向的Opus4.6是人民币¥1.8/9一百万token, MAX号池是人民币¥4/20 一百万token.
GPT5.4是人民币¥1/6 一百万token.

~提供包月的套餐, 最便宜的是149人民币每月, 每周额度75元, 每个月300元.可以用所有的模型.~(2025/3/20更新,已经暂停月卡)

如果要充值, 最低充值100人民币, 不方便用户进行尝试.

2025-3-22更新: 最近封号很多, 已经下掉了MAX号池分组, 只留下了反代的分组.

###  [FoxCode](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fcode.newcli.com%2Fauth%2Fregister%3Faff%3D5O8P&name=FoxCode&source=git)
之前这个网站是有包月套餐的,  现在只有按量计费的

这个网站的AWS渠道(就是Kiro逆向), 是我看到过最便宜的, 相当于官方的0.2折左右.
Opus4.6 的价格是人民币¥0.5(进)2.5(出)/一百万Token.

有网友反馈这个网站会拿别的模型掺水, 但是这个价格, 还要什么摩托车?

但是缺点是, 没有试用额度, 每次最少买35人民币.

### [SparkCode](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fsparkcode.top%2Fregister%3Faff%3DEYOo&name=SparkCode&source=git)
支持Claude, Gemini, GPT, Kimi, GLM. 常用的编程模型都支持了.

Sonnet 4.6的价格是人民币¥3(进)15(出)/一百万Token, Opus 4.6价格是¥5(进)25(出)/一百万Token. 试了下, 质量还行, 对得起价格吧.

GPT5.4的价格是人民币¥0.5(进)4(出)/一百万Token.

Gemini 3.1 Pro的价格是人民币¥2(进)12(出)/一百万Token, 但是最近都没有资源.

用户注册送2块钱, 可以去试试. 每次最少只用充1块钱.  有按月套餐, 89块钱可以买150的额度, 199买350的额度. 感觉不如少量现充合适


### [Aiberm](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Faiberm.com%2Fregister%3Faff%3DmZPL&name=Aiberm&source=git)
26年新作的一个API站点.
这个站长也有很多项目, 做的都还不错.
价格上没太多优势, Claude系列是官网2折左右, 网友反馈稳定性还可以.
codex是价格1折.

做的好的一点是, 市面上常见的AI接口基本都支持, Kimi, MiniMax, DeepSeek,GLM, Grok, 都比官网便宜一些(10%多点)

### [IKunCode](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fapi.ikuncode.cc%2F&name=IKunCode&source=git)
这也是一个专注于编程的API站点, 所以只支持Claude, GPT和Gemini.

只有按量收费一个收费方式
QQ群里大家比较活跃.

逆向的Opus4.6 收费人民币¥2(进)10(出)/一百万Token, 不是最便宜的那种.

这个站还有一个优点, 他们有一个自己的状态监控页, 可以方便让你知道目前接口的状况.

### [TimiCC](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Ftimicc.com%2Fregister%3Fref%3D2CT3TAP7&name=TimiCC&source=git)
2026年1月成立的一个站点. 主要是为写代码准备的

支持GPT(Codex) 和 Claude和他们自己的一个编程用的模型.

现在GPT team的号(只支持GPT5.2以下)是0.05折, 和免费没什么区别.

Claude code这部分的AI主要是逆向的, 价格是Opus 4.6 是 ¥1.75(进)8.75(出)/一百万Token, Sonnet4.6是人民币¥1(进)5(出)/一百万Token.


每个用户注册送1元的额度, 
如果想要试试Codex编程, 并且对效果没太多要求的, 可以试试他们.

另外, 这个网站有一个自研的模型, 0.01折, 就是免费了, 对于质量没要求的, 只想试试AI编程的可以推荐玩下这个.

不过, 他们只支持QQ邮箱注册. 挺那啥的...




###  [YesCode](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fco.yes.vg%2Fregister%3Fref%3Dgasd&name=YesCode&source=git)
也是主要为编程准备的网站, 提供Claude, GPT,Gemini三种类型的API.
Opus 4.6 价格是官网的2折, 也就是人民币¥7(进)35(出)/一百万Token.
GPT 5.4的价格是人民币¥2.1(进)12(出)/一百万Token.

值得一提的是, 网站提供了一个分组,可以用0.001折(基本免费)的价格使用GPT5.2/5.1 来进行编程. 如果只是想要试试Codex的朋友可以买这个模型试试.

有Codex包月套餐, 最便宜的是140人民币一个月, 每天20元额度, 每个月总共不超过210元.

网站从25年年中开始运行, 一直到现在的稳定性不错. QQ群里网友聊天气氛也还可以.

### [Terminal.Pub](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fterminal.pub%2Fregister%3Faff%3DrJW5&name=Terminal.Pub&source=git)
这是一个2026年2月份新开的站点, 专注于编程的API, 只支持Claude, GPT和Gemini.

价格来说, 真是太便宜了, 有免费的组. 不免费的组, 也有0.15折的Claude接口. 
Opus4.6收费是人民币¥0.5(进)2.5(出)/一百万Token. Sonnet 4.6 是人民币¥0.3(进)1.5(出)/一百万Token. 真的很便宜, 这么便宜都有点怕
稳定性还需要等待时间验证.

站点还支持GPT和Kimi, 但是价格一般.

这个站点不支持月卡形式.
对价格敏感又想尝试Claude的, 可以试试这个.

###  [XcodeBest](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fxcode.best%2Fregister%3Faff%3DmLST&name=XcodeBest&source=git)
2026年3月初刚开的站点, 专注于编程的API, 只支持Claude, GPT.

价格也算是便宜的
Opus4.6收费是人民币¥0.75(进)3.75(出)/一百万Token. Sonnet 4.6 是人民币¥0.45(进)2.25(出)/一百万Token

但是效果和稳定性也需要等待观察.


###  [ByteCat](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fwww.bytecatcode.org%2Fregister%3Faff%3DFHhY&name=ByteCat&source=git)
2026年1月新开的站点, 支持Claude, GPT, Gemini.
Opus4.6收费是人民币¥0.75(进)3.75(出)/一百万Token.

### [CCFly](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fccfly.codes%2F%3FinviteCode%3DDAN39VOO&name=CCFly&source=git)
这也是一个2026年新创建的站点. 

目前这个站只支持Claude 系列的接口, 所以做的也比较专业.
Opus4.6是人民币¥5(进)25(出)/一百万Token. Sonnet是人民币¥3(进)15(出)/一百万Token

除了这种号池模式外, 网站还支持Claude Code的MAX拼车服务,让你有独享账号. 就是价格不便宜, 如果自己一个账号, 每个月是2300人民币, 如果两人拼车, 每人1150人民币.作为对比, 官方是200美元一个月, 约1400人民币. 但是这个网站能帮你免去了封号的危险, 还是适合一部分人的.


###  [OhMyGPT](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fx.dogenet.win%2Fi%2F034RZ3DS&name=OhMyGPT&source=git)
OhMyGPT顾名思义之前是一个做GPT起家的中转站, 现在市面上主流的模型, Claude, Gemini, GPT, minimax, GLM, QWEN这些都能支持. 
他们的优点是很多区域都有CDN,网络延时可以保证.

写代码可以使用Claude, GPT这些, 平时养养龙虾就用便宜的模型, 譬如MiniMax.

价格方面, 和官网价格基本一样(贵). 如果对稳定性有很高要求的朋友,可以看看这家.


### [LinkAPI](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Flinkapi.ai%2Fregister%3Faff%3D6bq6&name=LinkAPI&source=git)
LinkAPI是2025年12月上线的一个站点, 支持的模型非常多, Claude, GPT, Gemini, DeepSeek, Kimi, Grok, GLM, Qwen这些都支持.

价格方面, Claude系列接口支持按次收费和按量收费. Sonnet4.6按次收费是每次0.1人民币, Opus4.6按次是每次0.2人民币. (比大肘子特价时贵一点)

按量是Opus4.6 最便宜的渠道是人民币¥2.5(进)12.5(出)/一百万Token, Sonnet4.6 是人民币¥1.5(进)7.5(出)/一百万Token. 我自己试了下, 是稳定掺水的.

codex的GPT 5.4 是人民币¥0.5(进)3(出)/一百万Token.

每天可以签到, 得到几分钱. 新用户可以冲个一块钱试试感觉怎么样.

###  [DDShub](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fwww.ddshub.cc%2F&name=DDShub&source=git)
网站的名字很可爱, 叫呆呆兽. 2026年3月份开始的.

网站只提供Claude Max的反代, 充值现在只能在QQ群里找站住充. 比例是 2人民币 : 1美元.

也就是说, Sonnet4.6的价格是 人民币¥6(进)30(出)/一百万Token, Opus4.6的价格是人民币¥10(进)50(出)/一百万Token.

接口试了下, 质量还过得去的.

之前有包月的套餐, 最近没有了.

新用户注册没有试用的额度.  最低充值10元.

### [aigocode.com](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Faigocode.com%2Finvite%2FZJS7W25Q&name=aigocode.com&source=git)
aigocode是一个口碑还不错的APIKEY网站, 目前没有发现用低价模型代替高级模型的情况. 我自己用的这段时间稳定性还行.
模型方面只有Claude, GPT和 Gemini. 支持 Claude 4.6 & Codex 5.3 & Gemini 3.

Opus4.6 最便宜的反代价格是人民币¥2(进)10(出)/一百万Token, 他们自己推荐的opus4.6方案是¥9(进)45(出)/一百万Token
GPT5.3的价格是人民币¥1.5(进)9(出)/一百万Token.
按量的价格比较合适.

网站支持月卡套餐.
目前最低的套餐是4周399人民币, 也就是100人民币每周, 对应的额度是110元每周.
算是不便宜的. 稳定性偶尔会有波动.

### [BUZZ](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fbuzzai.cc%2Fregister%3Faff%3DB0Er&name=BUZZ&source=git)
BUZZ是2026年年初新开的一个站.目前只有Claude 和GPT的接口

价格方面很合适.
最便宜的接口是反重力反代出来的的, 价格只有官方的0.4折.Opus 4.6的价格是人民币¥1.5(进)7.5(出)/一百万Token, Sonnet4.6 是¥0.9(进)4.5(出)/一百万Token.
MAX号号池方面, Opus 4.6的价格是人民币¥9(进)45(出)/一百万Token, Sonnet4.6 是¥5.4(进)27(出)/一百万Token.

GPT很便宜,  GPT5.4 是¥0.13(进)0.75(出)/一百万Token.

最近这一个月稳定性还挺好.
而且这个网站价格标识非常清晰, 有清楚的缓存命中记录. 网站风格我挺喜欢的.

美中不足的是没有新用户的使用. 最少要充值10块钱进行试用.

有一个qq群, 不太活跃.


### [ZeroCode](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fzerocode.sbs%2Fregister%3Faff%3DSc3E&name=ZeroCode&source=git)
ZeroCode 是2026年年初开的一个站. 支持Claude, Gemini, GPT.

价格是分等级的, 做了VIP能便宜一点

一般用户, 最便宜的Sonnet4.6(逆向) 是¥0.6(进)3(出)/一百万Token,  最便宜的Opus 4.6的价格是人民币¥1(进)5(出)/一百万Token.

GPT5.4价格是 人民币¥0.77(进)4.5(出)/一百万Token.

新用户送1块钱的额度.
QQ群不太活跃

### [DuckCoding](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fwww.duckcoding.ai%2Fregister%3Faff%3DbRob&name=DuckCoding&source=git)
这是2025年10月开始运营的站点.

支持Claude, Gemini,GPT 和 Grok.

目前最便宜的是自己建的MAX池子, Sonnet4.6 价格是人民币¥4.5(进)22.5(出)/一百万Token. Opus4.6 最便宜是¥7.5(进)37.5(出)/一百万Token.
用户登录送1块钱, 每天能送一点钱.
MAX池子用起来是没有掺水.

最少充值一块钱进行尝试. 只支持QQ邮箱进行注册

### [ClaudeCN](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fclaudecn.top%2Fregister%3Faff%3D3Uez&name=ClaudeCN&source=git)
大概是2025年开始运营的一个站, 稳定性应该还行把.

支持Claude, Gemini,GPT和minimax.

Sonnet4.6 最便宜的是人民币¥4.8(进)24(出)/一百万Token. Opus4.6 最便宜是¥8(进)40(出)/一百万Token.
站点使用起来感觉还行. 

最少充1块钱,可以试试. 20以上就有VIP等级.


### [米醋AI](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fwww.openclaudecode.cn%2Fregister%3Faff%3DrBFh&name=%E7%B1%B3%E9%86%8BAI&source=git)
前身是OpenClaudeCode, 之前的风波里表现还挺好. 现在重新开张.
站长是一个大V, 应该有信誉度.

支持Claude, Gemini和GPT,Grok的系列的API接口. 没有包月卡.

价格方面, 便宜的Opus4.6 是人民币¥1(进)5(出)/一百万Token, 他们维护的MAX号池价格是人民币¥6(进)30(出)/一百万Token. 
Sonnet4.6的价格是人民币¥3.6(进)18(出)/一百万Token

看他们自己的Status网站, 自己维护的MAX号池稳定性100%, 而且试用看起来也是没有掺水. 但是可能因为风控, 最近接口不太稳定.

GPT5.4的价格是人民币¥0.87(进)5.3(出)/一百万Token

新用户没有免费额度, 可以先冲一块钱试试.


### [FastCode](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fapi.timebackward.com%2Fregister%3Faff%3DuVJB&name=FastCode&source=git)
2026年3月新开的一个站, 现在还有开业送钱的活动

除了支持Claude, Gemini,GPT之外, 基本上市面绝大多数的AI都支持, 譬如DeepSeek, Douban等等

逆向出来的Sonnet4.6是人民币¥4.2(进)21(出)/一百万Token. Opus4.6 最便宜是¥7(进)35(出)/一百万Token. 
但是我自己试了下逆向的接口, 质量不行.

质量还可以的是官转的, 好用的是Sonnet4.6 是人民币¥12(进)60(出)/一百万Token, Opus4.6要¥20(进)100(出)/一百万Token.

Gemini的接口很慢, 不建议用

最少充1块钱,可以试试. 可以开发票, 可以对公转账

### codesome.ai
联系站长的微信可以给你10元的试用额度. 自己试用过后,没出现过稳定性问题. 站长微信回话时间大概是1个小时左右
月卡的话, 289一个月, 每天30元额度.  贵一档的是389一个月, 每天40元额度. 
可以使用cc, 价格还行, 稳定性差点, 也可以使用codex, 稳定性较高.
模型方面只有Claude, GPT5.4  和 Gemini

这个站相对来说比较新, 长期稳定性还等待观察.

###  [无限API](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Finfai.cc%2Fregister%3Faff%3D8EmH&name=%E6%97%A0%E9%99%90API&source=git)
支持的模型很多, 基本上你想得到的都支持.
OpenAI, Claude, Gemini, DeepSeek, 豆包, MiniMax, QWen,GLM这些也支持, 他们还支持  Mid-journey(文生图),suno_music(文生歌), 快手可灵(文生视频),Ideogram(文生图),xiaomi等等都有. 可能别的地方找不到的接口, 都可以在这里找到. 这一点很好.

可以开发票.

价格方面, 最便宜逆向出来的Sonnet价格是人民币¥1.8(进)9(出)/一百万Token, 是掺水的.
官转价格是 ¥12(进)60(出)/一百万Token, 试了下效果还可以.

GPT5.4 价格是 ¥1.5(进)9(出)/一百万Token, 很贵, 不推荐使用了.

这个站应该适合企业用户, 追求稳定和效果的.

不支持月卡.  新用户登录送几毛钱, 签到送几毛钱,可以试试效果.

### [DoroAI](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fdoro.lol%2Fregister%3Faff%3DsAVO&name=DoroAI&source=git)
这也是一个2026年2月份新建的站.

支持Claude, Gemini和GPT,Grok的系列的API接口. 之前有包月卡, 现在(2026-3-24)没了.
有美国和香港两个接入站点.

价格方面, Claude 便宜的有反重力逆向的, Sonnet4.6的价格是人民币¥0.66(进)3.3(出)/一百万Token. 价格不是最便宜的, 但是质量还相当不错. 
看来很多新站点质量还好一些.

GPT5.4的价格是 人民币¥0.38(进)3(出)/一百万Token. 感觉是不如Sonnet4.6值.

新用户注册送0.5元的额度, 最少充值5人民币

### [Cubence](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fcubence.com%2Fsignup%3Fcode%3DSCG4A2RZ&name=Cubence&source=git)
这是一个2025年下半年新建的站, 站做的还挺好看的.

支持Claude, Gemini和GPT,Grok的系列的API接口.

逆向的Opus4.6 是人民币¥1.5(进)7.5(出)/一百万Token, 逆向的Sonnet4.6 是¥0.9(进)4.5(出)/一百万Token. 价格还不错, 看群里网友反应稳定心也还可以.

新用户注册没有使用的额度, 最少一次要充值30人民币.

### [神马AI](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fapi.whatai.cc%2Fregister%3Faff%3DkjU5110733&name=%E7%A5%9E%E9%A9%ACAI&source=git)

这个站支持的模型特别多, 除了Gemini, Claude, GPT之外, 还有Minimax, Kimi这些都有.

像对话,视频,绘画,音乐,ppt各种类型的模型都支持. 
很大的一个站.

Sonnet4.6逆向大概是人民币¥4.8(进)24(出)/一百万Token, Opus4.6逆向大概是人民币¥8(进)40(出)/一百万Token
GPT5.4价格是人民币¥5(进)30(出)/一百万Token.

新用户注册送0.2额度, 每天能签到

微信客服回复速度挺快的, 支持开发票.

### [V-API](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fapi.gpt.ge%2Fregister%3Faff%3DBPl9&name=V-API&source=git)

也是支持很多模型, 除了Gemini, Claude, GPT之外, 还有Minimax, Kimi这些都有.

像对话,视频,绘画,音乐,ppt各种类型的模型都支持, 还支持数字人, 修图, OCR这些

注册就立刻送了0.3美金，首充还会再减2RMB，充的多折扣也会相对大些；充值付款支持微信RMB.

有qq 微信 tg客服，感觉响应都不是很及时

### [MNAPI](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fwww.mnapi.com%2Fregister%3Faff%3DawGu&name=MNAPI&source=git)

大概是2025年初成立的一个站
支持 Claude, Gemini, OpenAI, DeepSeek,Grok 等模型. 有按次收费的, 也有按Token收费的

Claude三方逆向渠道价格是官网的0.4折，支持Claude code但不支持缓存；Claude官key价格是官网的5折

有个TG用户交流群，客服回应速度慢

新用户送1元的额度, 平台无最低充值门槛充1元也能充，感兴趣的可以小小的试试

### OpenRouter.ai
在所有的网站里, 是OpenRouter最先开始这个模式的

一个API可以使用多个模型,  最新的GPT API, Anthropic API, Gemini , 国内的DeepSeek, Kimi, MiniMax都可以第一时间使用.

不过现在国内的信用卡也已经用不了Claude, GPT这些接口了, 这个网站不再太适合我们

稳定性非常不错,  而且都是原厂模型, 直接使用就行. 

缺点是价格比较贵, 很多情况下比原厂价格还要贵5%. 

### [aicodemirror](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fwww.aicodemirror.com%2Fregister%3Finvitecode%3D7C06QL&name=aicodemirror&source=git)
aicodemirror 是一个老牌的中转站, 之前使用的人很多
目前支持Claude, GPT, Gemini 三种api. 
价格方面,Claude是官方渠道是3.8折, 如果是反代出来的接口目前是1.9折. codex和Gemini很便宜, 分别是0.6折和1折.





### [Chintao AI](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fchintao.cn%2Fregister%3Faff%3DRF8V&name=Chintao%20AI&source=git)
很新的一个站点. 2026年3月份做的. 

但是我自己试了下, 接口质量很好, ~即使是逆向kiro或者aws的接口, 质量都很稳定很不错.~(现在也挂了)

价格上也算是便宜的, 我觉得合适的Sonnet4.6 是 人民币¥3.6(进)18(出)/一百万Token, Opus4.6 是人民币¥4.8(进)24(出)/一百万Token.
但是在这个质量上来说, 这个价格算很好. 接口基本不挂,基本没掺水.

新用户注册送10块钱, 值得去试试.

充值10块钱就能做VIP, 以后都打8折. 

有一个风险是这是一个新站, 少充点,以防跑路



### [LingxiCode](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fnew.050602.xyz%2Fregister&name=LingxiCode&source=git)
LingxiCode 是2025年年底开的一个站. 支持Claude, Gemini, GPT, DeepSeek, Kimi, GLM, MiniMax这些常用的.

价格方面比较便宜, 最便宜的Sonnet4.6 是¥0.9(进)4.5(出)/一百万Token,  最便宜的Opus 4.6的价格是人民币¥5(进)25(出)/一百万Token.
但是接口质量一般.

GPT5.4价格很贵, 人民币¥1.37(进)8.25(出)/一百万Token.

还有, 为什么用一个这么便宜, 这么难记的域名..

新用户送0.5. 不支持月卡.

### [Duomi](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fduomi.uk%2Fhome&name=Duomi&source=git)
是一个比较新的站点, 可能是2026年3月刚做的.

目前问题是文档比较乱, 系统不稳定, 接口响应慢, 经常没法使用.
价格方面也不便宜.

可以考虑等稳定一点再使用

好像已经倒闭/换域名了

### [接口AI](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fjiekou.ai%2F&name=%E6%8E%A5%E5%8F%A3AI&source=git)
价格基本和官方差不多,甚至有一些接口比官方贵很多.
优点是, 目前没有大规模Token 掺水的严重投诉，属于比较正经的收税方。支持企业开发票.
在线客服找不到人. 
这个价格有更多选择

### [大肘子](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fapi.dzzi.ai%2Fregister%3Faff%3DAUIz&name=%E5%A4%A7%E8%82%98%E5%AD%90&source=git)
大肘子又是一个RP友好的 中转站

这个站在xhs上非常火, 大家的反馈都很好. 这个站反代的非常明显, 特点是按调用次数收费, 而不是常见的按量收费.

新用户注册会送0.5元, 每天还可以签到. 对于一些便宜模型, 应该可以请求好几次. 
而且时不时还会一些免费的模型可以用.

只允许qq邮箱注册, 售后QQ群目前到了6群, 群里比较活跃.

因为编程时一个任务一般需要多次请求, 所以这个站不适合编程使用. 而在酒馆场景下适合一些. 

### [哈基米](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fapi.gemai.cc%2Fregister%3Faff%3Dtzn3&name=%E5%93%88%E5%9F%BA%E7%B1%B3&source=git)
也是一个玩酒馆朋友比较常用的网站.

网站是按照1:200进行充值.

支持的模型很多, Claude, Deepseek, Gemini, Minimax, Kimi, GPT 这些都支持.

可以按量, 也可以按次计费.

特价的按次的Opus4.6 有0.06人民币/次的(掺水严重),  0.15元/次的(掺水), 其他价格的可以大家自己试试.

按量的Sonnet4.6 价格是人民币¥1.5(进)7.5(出)/一百万Token, 是掺水的.
按量的Opus4.6 价格是¥2.5(进)12.5(出)/一百万Token, 也是是掺水的.

新用户注册送0.5人民币, 可以自己去感受下

### [Ekan8](https://www.hvoy.ai/relaySite?target=https%3A%2F%2Fapi.ekan8.com%2Fregister%3Faff%3DfLYm&name=Ekan8&source=git)
支持Gemini和Claude

Claude 只支持Opus4.6, 可以按次也可以按量.
按量的Opus4.6 thinking 还有100万上下文的Opus4.6 价格是人民币¥3.5(进)17.5(出)/一百万Token, 这个价格也还行.

~按次的Opus4.6 价格是每次0.15人民币, 100万上下文. 这个接口确实很少掺水, 值得这个价格. ~

2026-4-13更新: 最近接口质量不太行了

这个站的接口质量是我测过的"酒馆"站里, 质量和价格比最高的.

Gemini3.1 Pro都是按次的, 每次4分钱.


## 不推荐的

### 闲鱼上的中转站
试过好几个, 闲鱼上不知名中转站, 基本要不是模型掺水的特别厉害, 要不就是速度不达标, 太看运气了.

