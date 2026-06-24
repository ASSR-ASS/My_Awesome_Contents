---
created: 2026-05-18 10:00
ended: 2026-05-20 13:15
EventLevel: Chain
Module: TAA
SubModule:
Notes:
---
#### 想整理一下...
**`2026-05-18 10:00`**
你的B站收藏夹的视频数量已经超过4000了！看着分散在40多个收藏夹里的石山收藏夹，你决定整理一下...

---
[开始整理。](#塞进大象的柜子 “他还想不到这会很累”)

#### 塞进大象的柜子
**`2026-05-18 10:10`**
你把所有视频塞进了你的默认收藏夹里。面对着包含几千个视频的默认收藏夹，你在尝试手动分类的旅程中尝试了几个小时后便意识到这条路是走不通的——至少在一个合理的时间里是这样。

---
[投向自动化工具的怀抱。](#工具选型 “他以为他能一劳永逸...”)

#### 工具选型
**`2026-05-18 14:00`**
在Github上搜寻了一段时间后，你的目光锁定在了5个仓库上：
1. [sunrisever/bilibili-favorites](https://github.com/sunrisever/bilibili-favorites “Export Bilibili favorites, classify with ChatGPT/Claude/Gemini or other frontier LLMs, then sync folders back | 导出B站收藏夹，交给ChatGPT/Claude/Gemini等通用大模型分类，再同步回文件夹”)
2. [RadiumAg/bilibili-favorites](https://github.com/RadiumAg/bilibili-favorites “一个谷歌插件，快速对b收藏夹内容进行分类，查看最近收藏夹情况，对收藏夹进行关键字总结”)
3. [madoka-chann/Bilibili-AI-Favorites-Organizer](https://github.com/madoka-chann/Bilibili-AI-Favorites-Organizer “使用 AI 轻松整理你的 B站收藏。自动分类视频，减少混乱，让你的收藏夹变成结构清晰、可检索的内容库。”)
4. [KIKIN-0721/Bili-Favorites-Classifier](https://github.com/KIKIN-0721/Bili-Favorites-Classifier “一个自动拉取B站公开收藏夹，进行分类并同步的小工具”)
5. [atri1011/Bilibili-Favorites-Classifier](https://github.com/atri1011/Bilibili-Favorites-Classifier “ai自动整理收藏夹”)

选哪个？

---
[sunrisever的仓库。](#反人类设计)
[RadiumAg的仓库。](#意外收获)
[madoka-chann的仓库。](#这进度条咋不动啊？)
[atri1011的仓库。](#有时候，慢就是快。)
[KIKIN-0721的仓库。](#也许会有用？)

#### 反人类设计
**`2026-05-18 14:30`**
在你费劲读完了这个仓库AI味满满的自述文件和理解了反人类的仓库结构后，你做出了理智的决定：

---
[放弃这个仓库](#工具选型 “真不敢相信我用了一个小时的时间来干这个”)

#### 意外收获
**`2026-05-18 15:30`**
你发现这个仓库以浏览器插件的形式存在。这会给你带来方便...
...但事情没那么简单。
这个仓库的AI分类功能在分类提示词上可自定义程度低，而且还有偶发的无法获取收藏列表，无法抓取登录态等问题。
你原本要卸掉这个插件，但是你发现这个插件的数据统计功能做得还行，而且有个“性格分析”的模块你很感兴趣，所以你决定把它作为一个统计插件保留下来。

---
[继续前进](#工具选型)

#### 这进度条咋不动啊？
**`2026-05-18 17:00`**
这个作为JS用户脚本的分类工具的漂亮界面给你留下了深刻印象，自述文件里的丰富功能也让你认为自己找到了一个相对合适的工具。
直到进度条卡住的时候，你都是那么想的。
在一切配置完后，你按下了开始键。除了偶尔的报错信息和极其罕见的“AI批次处理完成”提示外，你在长达数小时的等待中没有看见分类进度条有任何明显的填充。终于，你的耐心走向枯竭。

---
[删除用户脚本](#工具选型)

#### 有时候，慢就是快。
**`2026-05-19 17:00`**
一整天过去了。你终于配置好了这个python仓库的环境。说实话，这是你第一次让一个仓库去发挥功能而不是一个发行包。类似RadiumAg的仓库，这个工具的AI分类Prompt可自定义程度低，但好在没有出现其他在RadiumAg的仓库中出现的问题。于是你决定采用这个工具，并尝试在原来的分类方法上做一些变通来适应这种情况。

---
[尝试变通](#尝试变通)

#### 也许会有用？
**`2026-05-19 17:00`**
在配置atri1011的仓库途中，你顺手将这个仓库克隆了下来。作为唯一一个没有任何AI功能的工具，它的视频分类原理全靠视频本身的分区和标签属性。但你的收藏夹里有近千个没有上述两个属性的视频，这让这个工具难以成为你分类的主力。除此之外，这个工具的功能可用性还可以，不像前一天的3个工具一样有硬伤。于是你决定...

---
[保留这个工具的安装，去用那个最后一个能用的工具](#有时候，慢就是快。)

#### 尝试变通
**`2026-05-19 18:09`**
你了解到，这个工具会在让你选择一些收藏夹作为分类对象以后，再选择另外一些收藏夹作为分类的目标。这提醒你或许可以通过更改收藏夹名称来引导AI将视频放到正确的地方。然后，再将名称改回你习惯用来做收藏夹管理的名字。

---
[就这么办](#续-尝试变通)
[好麻烦...要不我们换一条路？](#另一条道路)

#### 续-尝试变通
**`2026-05-19 18:27`**
面对浩如烟海的收藏视频，你意识到仅凭你现有的通用内容分类方案是不足以处理你的B站收藏的。于是，你打算先导出你的B站收藏夹——类似json文本的形式，然后让构建新分类系统的任务交给AI。凭借这个新分类系统，你可以合适地命名你的收藏夹名称并且能将它们融入进你既有的框架里。

---

[很好，立刻寻找导出工具](#尝试变通-2)

#### 另一条道路
**`2026-05-19 18:32`**
此时，你也萌生出了另外一个想法：说不定你可以放弃使用B站的收藏夹来收藏B站视频，转而使用更好用的一些替代方案来管理自己在B站上的收藏
你不久就找到了替代方案：[TLRKFXE/BiliShelf](https://github.com/TLRKFXE/BiliShelf “一个替代 bilibili 收藏夹管理方案的浏览器插件”)
相较B站原生收藏夹，它具有很多更好的特性，并且支持与B站收藏夹双向同步和收藏夹文本导出。这个新的导出方式说不定可以解决导出文件过大的问题。
但是，同步收藏夹的时候似乎遇到了和madoka-chann的工具一样的问题：进度条跑不动。
于是，我们只能退回到之前的方案，尝试对那个巨大的json文件进行分割。

---
[...](#尝试变通-3)


#### 尝试变通-2
**`2026-05-19 18:35`**
经过一番寻找，你找到了[ayasa520/bilibili-favorites-exporter](https://github.com/ayasa520/bilibili-favorites-exporter “ 用于导出并本地展示 B 站收藏夹”)。开工。
文件导出来了，问题随之出现：它太大了。没法被大多数模型提取。
好在你之前就想出了另外一条道路。

---
[另外一条道路](#另一条道路)

#### 尝试变通-3
**`2026-05-19 19:44`**
[rookiejefren/favorites-manager](https://github.com/rookiejefren/favorites-manager “一键导出知乎、b站、抖音的收藏夹内容。”)只导出了标题，还要手动翻页，下一个。
[JuJuIsTheMostCuteCat/bilibili-fav-export](https://github.com/JuJuIsTheMostCuteCat/bilibili-fav-export “ 一键导出 B站/小红书个人收藏夹到 Excel 的 Chrome 插件，方便知识管理与备份。”)速度奇慢无比，但好像还能跑
...

---
[等等我们需要整理一下思路！](#小结)

#### 小结
**`2026-05-19 20:09`**
在用过那么多工具后，你决定整理一下你现在的思路：
1. 直接对B站收藏夹进行AI分类：失败。
	1. ~~[sunrisever/bilibili-favorites](https://github.com/sunrisever/bilibili-favorites “Export Bilibili favorites, classify with ChatGPT/Claude/Gemini or other frontier LLMs, then sync folders back | 导出B站收藏夹，交给ChatGPT/Claude/Gemini等通用大模型分类，再同步回文件夹”)~~
	2. ~~[RadiumAg/bilibili-favorites](https://github.com/RadiumAg/bilibili-favorites “一个谷歌插件，快速对b收藏夹内容进行分类，查看最近收藏夹情况，对收藏夹进行关键字总结”)~~
	3. ~~[madoka-chann/Bilibili-AI-Favorites-Organizer](https://github.com/madoka-chann/Bilibili-AI-Favorites-Organizer “使用 AI 轻松整理你的 B站收藏。自动分类视频，减少混乱，让你的收藏夹变成结构清晰、可检索的内容库。”)~~
	4. ~~[atri1011/Bilibili-Favorites-Classifier](https://github.com/atri1011/Bilibili-Favorites-Classifier “ai自动整理收藏夹”)~~
2. 导出文本态收藏夹信息，分割文本后，AI对文本态信息做出分类建议后让AI分类插件根据收藏夹名进行分类：进行中。
	1. 导出工具
		[rookiejefren/favorites-manager](https://github.com/rookiejefren/favorites-manager “一键导出知乎、b站、抖音的收藏夹内容。”)只有标题和链接，需半自动翻页，.txt/.json/.md
		[ayasa520/bilibili-favorites-exporter](https://github.com/ayasa520/bilibili-favorites-exporter “ 用于导出并本地展示 B 站收藏夹”)全自动完成，速度快，但文本结构不清晰，.json
		[JuJuIsTheMostCuteCat/bilibili-fav-export](https://github.com/JuJuIsTheMostCuteCat/bilibili-fav-export “ 一键导出 B站/小红书个人收藏夹到 Excel 的 Chrome 插件，方便知识管理与备份。”)速度极慢，不能切屏，.xlsx
	2. AI分类插件
		[atri1011/Bilibili-Favorites-Classifier](https://github.com/atri1011/Bilibili-Favorites-Classifier)主用
		[RadiumAg/bilibili-favorites](https://github.com/RadiumAg/bilibili-favorites “一个谷歌插件，快速对b收藏夹内容进行分类，查看最近收藏夹情况，对收藏夹进行关键字总结”)备用，数据统计
3. 在2的基础上，分割文本后，添加一个与B站官方收藏夹并行的收藏夹系统：进行中。
	1. 导出工具
		[TLRKFXE/BiliShelf](https://github.com/TLRKFXE/BiliShelf “一个替代 bilibili 收藏夹管理方案的浏览器插件”)全自动完成，速度慢（需要等待同步），功能多，文本结构清晰，.json/.csv
	2. AI分类插件
		[atri1011/Bilibili-Favorites-Classifier](https://github.com/atri1011/Bilibili-Favorites-Classifier)主用
		[RadiumAg/bilibili-favorites](https://github.com/RadiumAg/bilibili-favorites “一个谷歌插件，快速对b收藏夹内容进行分类，查看最近收藏夹情况，对收藏夹进行关键字总结”)备用，数据统计
- 另外，你还保留有一个用来抓取分区和标签的工具 [KIKIN-0721/Bili-Favorites-Classifier](https://github.com/KIKIN-0721/Bili-Favorites-Classifier “一个自动拉取B站公开收藏夹，进行分类并同步的小工具”)，目前不准备让它参加分类工作流。

---
[继续总结](#续-小结)

#### 续-小结
**`2026-05-19 20:42`**
目前，你觉得让2和3方案并行是一个决定哪个导出工具会留下来的好方法。所以目前的安装列表如下：
- 以本地仓库应用存在的
	- [atri1011/Bilibili-Favorites-Classifier](https://github.com/atri1011/Bilibili-Favorites-Classifier)-AI分类插件，主用
	-  [KIKIN-0721/Bili-Favorites-Classifier](https://github.com/KIKIN-0721/Bili-Favorites-Classifier “一个自动拉取B站公开收藏夹，进行分类并同步的小工具”)-抓取分区和标签的工具，保留
- 以用户脚本（脚本猫）插件存在的
	- [rookiejefren/favorites-manager](https://github.com/rookiejefren/favorites-manager “一键导出知乎、b站、抖音的收藏夹内容。”)导出工具，只有标题和链接，需半自动翻页，.txt/.json/.md
- 以不上架的Edge插件存在的
	- [RadiumAg/bilibili-favorites](https://github.com/RadiumAg/bilibili-favorites “一个谷歌插件，快速对b收藏夹内容进行分类，查看最近收藏夹情况，对收藏夹进行关键字总结”)AI分类插件，备用，数据统计
	- [JuJuIsTheMostCuteCat/bilibili-fav-export](https://github.com/JuJuIsTheMostCuteCat/bilibili-fav-export “ 一键导出 B站/小红书个人收藏夹到 Excel 的 Chrome 插件，方便知识管理与备份。”)导出工具，速度极慢，不能切屏，.xlsx
	- [ayasa520/bilibili-favorites-exporter](https://github.com/ayasa520/bilibili-favorites-exporter “ 用于导出并本地展示 B 站收藏夹”)导出工具，全自动完成，速度快，但文本结构不清晰，.json
	- [TLRKFXE/BiliShelf](https://github.com/TLRKFXE/BiliShelf “一个替代 bilibili 收藏夹管理方案的浏览器插件”)带并行收藏夹的导出工具，全自动完成，速度慢（需要等待同步），功能多，文本结构清晰，.json/.csv
在清理不需要的工具过后，你决定继续按照`导出->分割->AI分析文本->AI输出分类项->用分类项命名收藏夹并且建立两个体系的对应关系->AI分类插件进行分类`的工作流进行

---
[更进一步](#小结-2)

#### 小结-2
**`2026-05-19 21:10`**
- ~~[JuJuIsTheMostCuteCat/bilibili-fav-export](https://github.com/JuJuIsTheMostCuteCat/bilibili-fav-export “ 一键导出 B站/小红书个人收藏夹到 Excel 的 Chrome 插件，方便知识管理与备份。”)导出工具，速度极慢，不能切屏，.xlsx~~
- ~~[rookiejefren/favorites-manager](https://github.com/rookiejefren/favorites-manager “一键导出知乎、b站、抖音的收藏夹内容。”)导出工具，只有标题和链接，需半自动翻页，.txt/.json/.md~~
以上两项被排除。
当前整理工作流：
1. 导出工具
	- [TLRKFXE/BiliShelf](https://github.com/TLRKFXE/BiliShelf “一个替代 bilibili 收藏夹管理方案的浏览器插件”)全自动完成，速度慢（需要等待同步），功能多，可补全标签，文本结构清晰，.json/.csv
	- [ayasa520/bilibili-favorites-exporter](https://github.com/ayasa520/bilibili-favorites-exporter “ 用于导出并本地展示 B 站收藏夹”)导出工具，全自动完成，速度快，但文本结构不清晰，.json
2. 分割
3. AI分析文本与输出分类项
4. 命名与建字典
5. AI分类插件
	- [atri1011/Bilibili-Favorites-Classifier](https://github.com/atri1011/Bilibili-Favorites-Classifier)主用
	- [RadiumAg/bilibili-favorites](https://github.com/RadiumAg/bilibili-favorites “一个谷歌插件，快速对b收藏夹内容进行分类，查看最近收藏夹情况，对收藏夹进行关键字总结”)备用，数据统计
目前的安装列表如下：
- 以本地仓库应用存在的
	- [atri1011/Bilibili-Favorites-Classifier](https://github.com/atri1011/Bilibili-Favorites-Classifier)-AI分类插件，主用
	-  [KIKIN-0721/Bili-Favorites-Classifier](https://github.com/KIKIN-0721/Bili-Favorites-Classifier “一个自动拉取B站公开收藏夹，进行分类并同步的小工具”)-抓取分区和标签的工具，保留
- 以不上架的Edge插件存在的
	- [RadiumAg/bilibili-favorites](https://github.com/RadiumAg/bilibili-favorites “一个谷歌插件，快速对b收藏夹内容进行分类，查看最近收藏夹情况，对收藏夹进行关键字总结”)AI分类插件，备用，数据统计
	- [ayasa520/bilibili-favorites-exporter](https://github.com/ayasa520/bilibili-favorites-exporter “ 用于导出并本地展示 B 站收藏夹”)导出工具，全自动完成，速度快，但文本结构不清晰，.json
	- [TLRKFXE/BiliShelf](https://github.com/TLRKFXE/BiliShelf “一个替代 bilibili 收藏夹管理方案的浏览器插件”)带并行收藏夹的导出工具，全自动完成，速度慢（需要等待同步），功能多，文本结构清晰，.json/.csv

---
[那么，开始吧。](#大事不妙)

#### 大事不妙
**`2026-05-19 23:36`**
你的主AI插件，[atri1011/Bilibili-Favorites-Classifier](https://github.com/atri1011/Bilibili-Favorites-Classifier)的上传请求被B站拦截了！
备用AI插件的使用状况也不容乐观...

---
[到此为止了吗...](#回收残值)

#### 回收残值
**`2026-05-20 00:09`**
还好，我们的工作流直到第四步为止运行的都很顺利，这为我们建立了一个可堪一用的分类框架。即使没有AI的辅助，我们也能缓慢地进行分类了。
我们现在要做的，也是唯一能做的，就是把这个新生的框架给整合进现有的分类体系中。
时值5-20，你的上下眼皮愈发亲密...

---
[沉沉睡去...](#第三天)

#### 第三天
**`2026-05-20 10:34`**
在最后一次试用备用AI插件失败后，你彻底放弃了AI分类的计划。
在整合框架的过程中，你发现事情远没你想象的那么容易。有很多框架条目出现了重叠和领域规模不对等的问题，它们还涉及多个平台。这需要你花费好一段时间来推进整合进度

---
[整合进行中...](#整合完成！)

#### 整合完成！
**`2026-05-20 13:00`**
终于。52个收藏夹。你将B站的收藏体系与你的既有框架良好地整合了起来。虽然有4131个挤在默认收藏夹里的视频，但从客观事实来说，在有一个好框架的基础上，将它们分配到合适的地方只是时间问题。
是时候收拾一下烂摊子，将精力转向其他事项了

---
[折磨终于结束了。](obsidian://open?vault=Concrete%20Council%20Bouleuterion&file=%E6%83%85%E6%8A%A5%C2%B7%E5%AE%89%E5%85%A8%E7%89%B9%E5%88%AB%E6%A8%A1%E5%9D%97~Cute%20Cat%20%26%20Cyber%20Catgirls'%20Coalition~%2FCCCCC%2F%E4%BA%8B%E4%BB%B6%E5%8D%95%E5%85%83%E5%90%88%E9%9B%86.base)
[看看烂摊子（安装列表）](#最终安装列表)

#### 最终安装列表
**`2026-05-20 13:10`**
- 以本地仓库应用存在的
	- [atri1011/Bilibili-Favorites-Classifier](https://github.com/atri1011/Bilibili-Favorites-Classifier)-用来获取B站收藏夹的文本化列表工具，保留
	-  [KIKIN-0721/Bili-Favorites-Classifier](https://github.com/KIKIN-0721/Bili-Favorites-Classifier “一个自动拉取B站公开收藏夹，进行分类并同步的小工具”)-抓取分区和标签的工具，保留
- 以不上架的Edge插件存在的
	- [RadiumAg/bilibili-favorites](https://github.com/RadiumAg/bilibili-favorites “一个谷歌插件，快速对b收藏夹内容进行分类，查看最近收藏夹情况，对收藏夹进行关键字总结”)数据统计，保留
	-  ~~[ayasa520/bilibili-favorites-exporter](https://github.com/ayasa520/bilibili-favorites-exporter “ 用于导出并本地展示 B 站收藏夹”)导出工具，全自动完成，速度快，但文本结构不清晰，.json，删除~~
	- [TLRKFXE/BiliShelf](https://github.com/TLRKFXE/BiliShelf “一个替代 bilibili 收藏夹管理方案的浏览器插件”)并行收藏夹，全自动完成，速度慢（需要等待同步），功能多，文本结构清晰，.json/.csv，保留

---

[折磨终于结束了。](obsidian://open?vault=Concrete%20Council%20Bouleuterion&file=%E6%83%85%E6%8A%A5%C2%B7%E5%AE%89%E5%85%A8%E7%89%B9%E5%88%AB%E6%A8%A1%E5%9D%97~Cute%20Cat%20%26%20Cyber%20Catgirls'%20Coalition~%2FCCCCC%2F%E4%BA%8B%E4%BB%B6%E5%8D%95%E5%85%83%E5%90%88%E9%9B%86.base)