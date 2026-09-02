# AI API中转站推荐与评测

## 写在前面的话


2026-6-15  更新

~~目前最好的策略, 大概率是自己买一个土区的GPT Plus, 每个月80块钱左右.~~

~~方法是自己注册一个土区的apple id, 然后去mtcgame这里买一个礼品卡, 或者去闲鱼上买礼品卡,价格稍贵一点, 但是也能接受.~~

土区涨价了, 只有菲区还划算点. 菲区麻烦点, 简单点就用美区或者别的区. 各个区的价格可以看这里[官方套餐](https://www.hvoyai.com/official-plans/chatgpt)

有人测过, 20刀的plus大概能用出400刀的token. 如果加上各种重置, 海鲜市场上买个重置, 实际token更多, 还是很划算.

具体的订阅和使用方法可以看这个github. https://github.com/hvoyai/chinaGPTClaude

弄完之后, 挂个机场, 用codex, 不管是写电脑, 还是聊天,或者日常很多事情(譬如给照片打个水印, 写个文章)都很方便.
基本上够自己用了.

如果实在嫌麻烦, 找一些排名靠前的中转站, 选一些价格在 人民币 ¥1(进)6(出)/一百万Token的GPT 5.6 Sol中转站, 少充点钱, 也不是不行.

追求效果的, 可以上Claude, 效果好一些, 价格要贵很多. 选Claude就要认真看下下面的推荐文章. 
一般来说,价格太便宜的,要不是掺水, 要不是不稳定,要不是收费有坑, 要注意点. 

----

我们先在国内想要安心的使用最先进的AI API 真是太难了. 国外官方的AI不仅价格贵, 而且经常被误封账号, 就会误事.

选择一个好的中转站不容易, 要看下面的这些点

1. 最重要的是稳定，如果它自己经常宕机或延迟极高，那不仅没省事反而耽误事. 所以要优先买那些信誉好,运行时间长, 最好有群的站
2  第二个是速度. 一个站点如果返回速度过慢, 用起来会难受死.
3. 模型的覆盖性: 一个好的中转站应该让你一站式调用全球顶尖模型, 最好能尽快上官方的最新模型.
4. 中转站的收费有很多问题. 很多站看起来价格低, 实际运行起来价格很高. Token计数, 或者价格费率, 都是造成价格不同的很重要原因.  另外站点最好要有清晰的账单, 否则将来哪一天突然账单异常了,都查不到原因. 也要警惕价格异常便宜的模型, 大概率是拿着GLM这种低价国产模型代替高价的国外模型.
5. 每个站都有跑路的危险, 优先选择公司运营的站点. 还有他们客服响应问题的速度, 站点速率波动时有没有通知这些.
6. 注意隐形的点, 无量站比较容易做文档的就是缓存价格和缓存命中率. 正常来说, 缓存价格应该是10%左右, 但是有些站会多收点, 15%, 还有黑心站收30%.

为了解决下面的问题, 我对使用过的中转站做一个评价.

在所有使用之前, 切记一点, 这个行业不稳定, 不要大额充值, 用多少充多少.

站点的价格更新太快了..我努力让这些价格是准确的.  

[禾维AI](https://hvoyai.com/) 现在上面增加排行, 有后台不停检测端口, 并且更新实时价格, 可以从排行榜上挑选合适的中转站

至于具体的检测代码, 已经不开源了. 

![banner](pic/banner.png)

btw: 希望能加入评测的中转站站长, 请来[contactUs](https://www.hvoyai.com/contact)提交您的站信息吧.

## 推荐的

### [DuiAPI](https://www.hvoyai.com/relaySite?id=40424&name=duiapi&source=git)
DuiAPI (对 API) 是一个主打直连官方平台的站点，支持 Qwen3.7-Max、GLM-5.2、DeepSeek-V4 等主流模型，新站很多模型5折优惠比如GLM-5.2、Qwen3.7现在都在打折，其它模型也在不同程度的打折，可以使用他的**5折特惠分组。现在新用户注册送2刀，立即到账。**

还有一点他计费比较清晰，调用记录也可以追溯，对需要做成本核算、接口测试、产品原型验证或者企业内部工具集成的使用者会比较友好。

整体看，这个站更偏规范化和可管理性，不是单纯卷最低价的路线。如果你比较在意模型来源、调用记录和账单透明度，可以跑一下自己的真实场景试试看。
### [CUN.ai](https://www.hvoyai.com/relaySite?id=40325&name=CUN.ai&source=git)
CUN.ai 是今年2026年新上线的一个站点，在开发者社区中迅速火起来热度很高。支持模型种类挺多的GPT、Claude、DeepSeek、Gemini、Qwen、GLM 等都有，当下热门的Claude Fable 5、Claude Sonnet 5、Claude Opus 系列、GPT 5.6 Sol、GLM-5.2 等都有，团队效率挺高的。

他有按量计费, 也有套餐订阅，站长非常豪气，经常在hvoy的[免费兑换码](https://hvoyai.com/free-tokens/invite-codes)页面投放兑换码，一个新用户总体可以得到价值 **90人民币** 的额度。

即使抢不到给hvoy用户的这个大额兑换额度，新用户直接去注册也可获得约60块钱的额度。

（具体活动以站点为准哈）。

可以趁着活动先用赠送的新人额度跑一下自己的真实场景，再决定要不要长期使用。

### [hao.ai](https://www.hvoyai.com/relaySite?target=https%3A%2F%2Fhao.ai%2Fzh%3Futm_source%3Dhvoyai%26utm_medium%3Dfree&name=hao.ai&source=git)
这个站已支持GPT、Claude、xAI Grok 等主流模型，并兼容了 OpenAI、Anthropic 等常用协议与SDK。他们还提供模型路由、故障回退、团队管理及完整调用日志，模型价格也不贵，大概是官方参考价的 1.5 折。

发展很快，用户体量挺大的，可以小额充值试一下。

### [EiRouter](https://www.hvoyai.com/relaySite?target=https%3A%2F%2Fwww.cc-max.cc%2Fsign-up%3Futm_source%3Dhvoyai%26utm_medium%3Dfree&name=EiRouter&source=git)
这个站使用起来体验还不错，主打GPT和Claude系列模型，也支持Deepseek-v4-flash，分组划分的比较细致可以满足不同用户的需求，追求极致稳定的用户可以使用GPT精品和CC满血高端这类的分组；追求性价比的用户可以使用普通组，Claude是1.2倍率，GPT是0.4倍率。

这家充值比例是1:1，可以小额充值试用后再决定要不要长期使用。

### [Modelflare](https://www.hvoyai.com/relaySite?target=https%3A%2F%2Forigin.modelflare.dev%2Fsign-up%3Futm_source%3Dhvoyai%26utm_medium%3Dfree&name=Modelflare&source=git)
这家站有个特惠活动，单笔充值 US$20 后可解锁 GPT 特惠分组，这个组很便宜，解锁这个组后GPT‑5.6‑Sol 价格大概是¥0.51(进)3.01(出)/一百万Token，问了站点的客服说没有使用上限的限制。

站点由美国 LLC 主体 Havenbyte LLC 运营，支持 GPT、Claude、Gemini、Grok 等主流模型和常用兼容协议；API Key 可以配置有序回退，调用记录可查看 Token、延迟、状态和实际成本。缓存补偿也是一个这个站的一个亮点。部分 OpenAI 价格优先、稳定和高级分组提供每日 65%、75%、85% 的缓存命中率保障；符合条件的请求如果未达到目标，平台会补偿差额，结算后可在用量看板查看。

推荐小额先试一下，觉得不错的话再参加他们的充值解锁特惠分组的活动，以降低长期使用的成本。

### [SudoCode](https://www.hvoyai.com/relaySite?id=40095&name=SudoCode&source=git)
看名字就知道是一个专门编程的站点.
这是一个 2026 年刚成立的站, 站点对于模型支持非常快速. 新的模型基本第一时间就能上线.

模型方面, 目前gpt5.6 sol价格是人民币¥1(进)6(出)/一百万Token,  Opus5的满血 CC Max 渠道价格是人民币¥7(进)35(出)/一百万Token, 这两个的价格都还不错.

网站支持退款, 可以开发票.

### [DDTokens](https://www.hvoyai.com/relaySite?target=https%3A%2F%2Fddtnew.com%2F%3Faff%3DpyZV&name=DDTokens&source=git)
这个站模型种类挺多的包含GPT、Claude、Gemini、Grok、Kimi、DeepSeek、GLM、Qwen、MiniMax等，他们现在有个活动，注册加他们的Q群或Telegram联系管理员可以领取¥5试用额度，可以领取一下去试试。

### [ToolCode](https://www.hvoyai.com/relaySite?target=https%3A%2F%2Ftoolcode.top%2Fregister%3Futm_source%3Dhvoyai%26utm_medium%3Dfree&name=ToolCode&source=git)
这个站是2025年12月上线的站点，主打GPT系列和Claude系列， 也支持Kimi-K3、gpt-image-2生图、Gemini和Grok等。这个站有不少企业客户，追求稳定的用户可以使用它的纯享分组，追求性价比的用户可以使用它的优惠分组，5.6-sol福利价最低能做到¥0.6(进)4.1(出)/一百万Token。综合性价比很不错。

### [云渡](https://www.hvoyai.com/relaySite?target=https%3A%2F%2Fyundu.lol%2Fregister%3Futm_source%3Dhvoyai%26utm_medium%3Dfree&name=%E4%BA%91%E6%B8%A1&source=git)
云渡目前支持 GPT、Claude 等主流模型，其中 GPT-5.6-sol 的价格为¥0.6(进)4.1(出)/一百万Token；Claude Opus 系列的价格为¥2.5(进)12.5(出)/一百万Token

价格挺透明的，按实际 Token 用量计费，主流模型和优质渠道的更新速度也可以，适合对模型价格和使用成本有要求的开发者。

### [PackyCode](https://www.hvoyai.com/relaySite?id=39842&name=PackyCode&source=git)
PackyCode 大约是25年初开始活跃, 是国内比较早针对Claude Code进行优化的供应商.

这个站点与开源社区互动比较频繁, 站长在x上也非常活跃, 客服响应比较快. 随着发展, 这个站已经是很多中转站的上游供应商.

我现在主流用法是, 要不就用便宜的GPT 5.6 Sol, 1-2块钱/一百万Token.
要不就用贵的, 质量较好的Claude Code, 大概10块钱左右/一百万Token.

质量较好的渠道是cc, Fable-5  20(进) 100(出)/一百万Token, 几乎不注水. 但是真的好贵. 

GPPT 5.5 现在是人民币¥2.5(进)15(出)/一百万Token

Gemini现在好多渠道都用不了,或者响应速度巨慢, 用下来只有PackyCode速度是最快的, 质量还可以. 价格是 Gemini 3.1 Pro是 人民币¥6(进)36(出)/一百万Token.

他们对于国内的模型支持比较全, 支持阿里百炼的api, MiniMax(官方价格的5折),GLM(九折). 

新人注册送1元, 可以先试试再决定购买.  最少充值50块, 支持开发票.

### [9527code](https://www.hvoyai.com/relaySite?id=39937&name=9527code&source=git)
9527code是2025年12月就成立的一家站点，稳定性和真实性方面的口碑不错，号称是若发现模型降级、套壳或掺水，经核实，假一赔十。去试了一下售后流程，客服响应很快，用起来比较省心。

价格的话，除了按量计费，还提供月套餐，月套餐倍率更低；他们也经常举办用户互动方面活动，还时常给新/老用户推出活动专属福利、特惠分组、赠送额度，对于追求稳定性并计划长期使用的用户会更加划算。可以关注一下这家站的公告和平台活动，赶上的时候还挺合适的。

### [ToTokens](https://www.hvoyai.com/relaySite?target=https%3A%2F%2Ftotokens.cc%2Fregister&name=ToTokens&source=git)
这个站成立于2026年2月，支持Gpt、Claude等主流模型，客服和技术支持服务效率不错。gpt-5.6-sol价格是¥0.7(进)4.5(出)/一百万Token，他们针对专用分组做了容灾与秒级故障转移，高峰期也还稳定的，企业和中转站联系会有专属倍率优惠，10元起充可以小额测试一下试试。

### [我的贾维斯](https://www.hvoyai.com/relaySite?id=40324&name=%E6%88%91%E7%9A%84%E8%B4%BE%E7%BB%B4%E6%96%AF&source=git)
这个站是今年6月初上线的，上线后凭借价格优势和服务发展迅速。充值是1RMB=1刀，GPT 5.6 Sol 输入价格 0.5 元/百万 tokens（Pro 号池0.1倍率），Fable-5 输入价格 10 元/百万 tokens（Max 号池 1倍率）。支持开票 + 支持对公，客服响应速度快。

这个站有时候会在 [hvoy](https://hvoyai.com/free-tokens/invite-codes) 的免费兑换码投放兑换码，有需要的新用户可以关注一下领取体验一下。

### [灵算](https://www.hvoyai.com/relaySite?id=39980&name=%E7%81%B5%E7%AE%97&source=git)
灵算这个站我自己试了一段时间后感觉还挺适合开发者直接拿来干活的，GPT 系列价格挺有优势的，GPT 5.6 Sol 现在是¥0.79(进)4.74(出)/一百万Token，GPT-5.4 是¥0.395(进)2.37(出)/一百万Token。实际用下来，稳定性方面我也比较满意，接口响应比较稳。

它的gpt-image-2 生图，1K 图 1 毛一张，拿来做文章配图、产品图草稿、封面图或者一些轻量设计需求，成本很低。

如果你想找一个便宜且稳定性也不错的GPT站，可以试试这家。


### [YKH.AI](https://www.hvoyai.com/relaySite?id=39975&name=YKH.AI&source=git)
我比较喜欢这个站的一点是没有很多营销词，如果你想找一个界面干净、方便快速接入的 AI API 站点可以看看这个。追求性价比的话可以选 lite 分组算下来¥0.25/一百万Token，追求稳定性高的话可以选纯pro号池是 ¥0.5/一百万Token，便宜的和稳定的全都有，可以满足不同用户的需求。

这个站的站长说YKH.AI 这个名字是 You Know How 的缩写，想对用户表达他的站要把“问题怎么问、上下文怎么整理、下一步怎么走”这件事做得更清楚，是个非常有心的站长哈哈，可以试试看。

### [智惠API](https://www.hvoyai.com/relaySite?id=40026&name=%E6%99%BA%E6%83%A0API&source=git)
这个站是2026年新开的一个站点，模型比较全，支持 Claude、GPT、Gemini、Grok 等大模型。

Max满血渠道的 Opus5 价格是 ¥6.5(进)32.5(出)/一百万Token， Fable 5的价格是 ¥13(进)65(出)/一百万Token。Kiro逆向是¥1(进)5(出)/一百万Token的超低价，GPT 5.6 Sol模型价格是 ¥0.75(进)4.5(出)/一百万Token。

该站最近推出了会员等级计划，根据不同会员等级每次充值享受不同的额外赠送比例，用于奖励忠诚会员，站内消费越久，权益越高。

### [XycAi(星道智能)](https://www.hvoyai.com/relaySite?id=40216&name=XycAi%28%E6%98%9F%E9%81%93%E6%99%BA%E8%83%BD%29&source=git)
这个站号称是有正规大模型备案号和一些正规出海资质的合规对外企业，说是可以解决企业软件安全审查中上家数据合规性问题以及税务问题（有这方面需求的小伙伴请自行和站点核实哈）。

价格也不贵，GPT 5.6 Sol是2.2折，opus4.8是3.9折，他们支持的模型很多还有很多国产模型gpt、opus、豆包、DeepSeek、千问、可灵等都支持，还是做的很不错的。

### [UU API](https://www.hvoyai.com/relaySite?id=39863&name=UU+API&source=git)
UU API 主要支持Claude 和GPT. 也支持gpt-image-2 来生成图片.

Claude 建议使用 MAX分组, 实测都是max号池, 质量没啥问题. opus-4.8的价格是 11(进)55(出)/一百万Token.

GPT 5.6 Sol 价格是 1.5(进)9(出)/一百万Token. 还可以吧.

gpt生图是按次的, 4分钱一次.

平台支持支付宝和微信支付. 新注册用户送一块钱进行调试

### [Poixe AI](https://www.hvoyai.com/relaySite?id=39845&name=Poixe+AI&source=git)
这个站是一个从 2024 年开始做, 在中转站里, 算是干了非常久的. 

整个站的风格我很喜欢, 不是审美疲劳的New API的这种风格.

支持 GPT,Claude,Gemini,DeepSeek,Doubao,Qwen ,Grok 这些模型.

不同级别会员价格不一样,充一点钱就能Vip1,能八折.

Opus 4.8 价格是人民币 28/140 一百万 Token.
GPT5.6 价格是人民币 14/84 一百万 Token, GPT5.4 价格是人民币 28/168一百万 Token. (官方的东西, 真贵啊)

价格是不便宜. 我试了下接口, 接口质量是相当好, 完全没掺水, 速度也快.
网站上提供一个免费的接口,譬如 GPT4o这种.
支持开发票.

总体来说,这个适合企业客户, 质量好, 价格也在这里摆着.

btw:这个站点的域名老容易打错.


### [RightCode](https://www.hvoyai.com/relaySite?id=39848&name=RightCode&source=git)
**但是这个站点最近使用时,出现了较多的错误, 接口也不太稳. 暂时先保留意见**

就是为编程准备的, 只支持Claude, Gemini和GPT的接口.  

值得推荐的渠道是 /claude 渠道, Fable-5 价格是人民币¥20(进)100(出)/一百万Token. 

质量也不错, 对的起这个价格.

GPT 系列还可以, GPT 5.6 Sol是人民币¥2(进)12(出)/一百万Token, 不是特别稳定, 但是我自己使用时, 发现 Token 消耗非常高.

Gemini系列的接口也很便宜, 大概是官网价格的1折.

有网友说有时拿别的模型掺水. 

最少可以充1元 , 获得5元的额度, 先试试效果.

## 中性

### [Chintao AI](https://www.hvoyai.com/relaySite?target=https%3A%2F%2Fchintao.ai%2Fregister%3Futm_source%3Dhvoyai%26utm_medium%3Dfree&name=Chintao%20AI&source=git)
很新的一个站点. 2026年3月份做的. 

但是我自己试了下, 接口质量很好, ~即使是逆向kiro或者aws的接口, 质量都很稳定很不错.~(现在也挂了)

价格上也算是便宜的,  Opus4.8 是人民币¥4.8(进)24(出)/一百万Token.
但是在这个质量上来说, 这个价格算很好. 接口基本不挂,基本没掺水.

### [ModCon](https://www.hvoyai.com/relaySite?id=40106&name=ModCon&source=git)

ModCon是25年11月成立的一个站, GPT系列做的还不错.
GPT 5.6 Sol的价格是0.9, 挺稳定的.


### [aigocode.com](https://www.hvoyai.com/relaySite?id=39782&name=AlGoCode&source=git)
aigocode是一个口碑还不错的APIKEY网站, 目前没有发现用低价模型代替高级模型的情况. 我自己用的这段时间稳定性还行. 模型方面只有Claude, GPT和 Gemini，网站支持月卡套餐. 目前最低的套餐是4周399人民币, 也就是100人民币每周, 对应的额度是110元每周. 算是不便宜的. 稳定性偶尔会有波动.


### OpenRouter.ai
在所有的网站里, 是OpenRouter最先开始这个模式的

一个API可以使用多个模型,  最新的GPT API, Anthropic API, Gemini , 国内的DeepSeek, Kimi, MiniMax都可以第一时间使用.

不过现在国内的信用卡也已经用不了Claude, GPT这些接口了, 这个网站不再太适合我们

稳定性非常不错,  而且都是原厂模型, 直接使用就行. 

缺点是价格比较贵, 很多情况下比原厂价格还要贵5%. 



### 哈基米
也是一个玩酒馆朋友比较常用的网站.

网站是按照1:200进行充值.

支持的模型很多, Claude, Deepseek, Gemini, Minimax, Kimi, GPT 这些都支持.

可以按量, 也可以按次计费.

特价的按次的Opus4.6 有0.06人民币/次的(掺水严重),  0.15元/次的(掺水), 其他价格的可以大家自己试试.

按量的Sonnet4.6 价格是人民币¥1.5(进)7.5(出)/一百万Token, 是掺水的.
按量的Opus4.6 价格是¥2.5(进)12.5(出)/一百万Token, 也是是掺水的.


### Ekan8
支持Gemini和Claude

Claude 只支持Opus4.6, 可以按次也可以按量.
按量的Opus4.6 thinking 还有100万上下文的Opus4.6 价格是人民币¥3.5(进)17.5(出)/一百万Token, 这个价格也还行.

~按次的Opus4.6 价格是每次0.15人民币, 100万上下文. 这个接口确实很少掺水, 值得这个价格. ~

2026-4-13更新: 最近接口质量不太行了

这个站的接口质量是我测过的"酒馆"站里, 质量和价格比最高的.

Gemini3.1 Pro都是按次的, 每次4分钱.

### [cocodot](https://cocodot.co)
OpenAI 兼容的 AI API 中转,一个 Key 调 Claude / GPT / Gemini / DeepSeek 等,支付宝人民币充值、按量计费。费率公开(开卡 / 充值 / 消费明码),主打不降智——降不降智可用开源工具 [LLMprobe](https://github.com/cocodot2026/LLMprobe) 自行验证(实测 87/100)。海外注册公司运营,余额可转、卡内资金持牌机构托管。接入地址 `https://cocodot.co/api/ai/v1`。


## 不推荐的

### 闲鱼上的中转站
试过好几个, 闲鱼上/小红书不知名中转站, 基本要不是模型掺水的特别厉害, 要不就是速度不达标,太看运气了.

而且很多新站真的很不靠谱.  跑路的我都见过几个.
一定要小心.



###  AI派
这也是一个比较新的网站

只支持Claude, Gemini, GPT. 刚开始支持NanoBanan2, 4k文生图

Claude方面, 好玩的是只支持Sonnet4.6和Opus4.6, 其实也是, 与其用4.0那些接口, 还不如用国产的呢.

价格方面, 看起来很便宜

**不过需要注意的是, 这个站的缓存价格比较贵,是0.52倍. (一般网站都是0.1倍). 写代码大量使用缓存, 所以这个站其实很贵**

少充点, 以防跑路.

2026-4-11 更新
这个站最近claude相关接口返回特别慢.使用起来很难受

2026-4-30 更新
最近这个站接口质量不太好, 以及价格上不透明, 不再推荐了.  

有几个用户给我反馈, 说AI派现在接口慢,扣费还贵. 所以大家远离这里.


### 大肘子
大肘子是一个RP友好的中转站

这个站在xhs上讨论很多, 但是接口质量真的很差. 这个站反代的非常明显, 特点是按调用次数收费, 而不是常见的按量收费.

还是远离骂声多的.
