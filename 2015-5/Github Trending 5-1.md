##Github Trending repositories 第三期

不知道大家的五一都是怎么过的，Rube过了一个撸码的五一。ok 继续带来本周 Github 热门项目。		

1.	antirez / **disque** [https://github.com/antirez/disque](https://github.com/antirez/disque)	

	Disques 是由 Redis 之父新开源的一个分布式内存消息代理。Disques 虽然是独立于 Redis 的一个新项目，但是它重用了 Redis 大部分的网络源代码，客户端协议等，并且把默认端口改为了7711.需要提醒的是目前 Disques 处于研究测试阶段，详细的[介绍](http://www.infoq.com/cn/news/2015/04/Disque-Redis-github)，如果想要深入的研究下，小编推荐[中文文档](http://disquebook.com/index.html).		
2. Rich-Harris / **ramjet** [https://github.com/Rich-Harris/ramjet](https://github.com/Rich-Harris/ramjet)

	<img src="https://cloud.githubusercontent.com/assets/1162160/7279487/5d668dea-e8ea-11e4-9b0d-a9ba2f1165cc.gif" width=500/>    
	看到上面的动画是不是很惊喜，他就是用 ramjet 实现的，ramjet 能使一个 DOM 过渡到另一个 DOM 变得平滑且优雅。     
	**安装**		
	安装很简单 
	```  
	npm install ramjet  
	```	    
	ramjet 不仅在 PC 端有很好的效果，在移动端的效果也十分优雅哦~ ,浏览器支持 IE9+  
				
3. mortenjust / **androidtool-mac**	[https://github.com/mortenjust/androidtool-mac](https://github.com/mortenjust/androidtool-mac)	

	Androidtool Mac 是一个很火的工具，它能够将 Android 手机或者智能手表与 Mac 相连。连接 Mac 之后能够进行一键截屏，录像和安装 APK，这是不是一个很酷的工具。   
	Androidtool Mac 是使用 Swift 编写 Mac 下的视图，使用 Shell 操作 adb 进行一些安装等操作，实现很简单，但是这小工具的创意无限。小编设想一个场景，你编写了一个 Android 端的动画效果需要将这个效果展示出来，那你就可以通过 Androidtool Mac 录制然后到处 gif 图。     
	<img src="https://raw.githubusercontent.com/mortenjust/androidtool-mac/master/Demos/phonerecording.gif" width=500 />		
4. jonathanslenders / **pyvim**	[https://github.com/jonathanslenders/pyvim](https://github.com/jonathanslenders/pyvim)		
	pyvim 是一个使用纯 Python 实现的一个 Vim 编辑器。可以使用 pip 命令进行安装   
	      
	pip install pyvim		
	
	如果你真的想要将自己的编辑器换成 pyvim的话，在 ~/.bashrc 中就可以修改     
	<pre>
	alias vi=pyvim 
	export EDITOR=pyvim	
	
5. moose-team / **friends**   [https://github.com/moose-team/friends](https://github.com/moose-team/friends)    

	friends 是一个基于 Web 的点对点聊天工具，用到了 WebRTC 技术，如果需要学习关于这方面的知识，看他的源码还是很有意思的。    
	[可以查看他们的主页来了解更具体的信息](http://moose-team.github.io/friends/),小编上幅界面图   
	<img src="http://moose-team.github.io/friends/screenshot.png" width=500/>   
6. code-mc / **loadtoast**    
	这是一个非常漂亮的 Android 端的等待动画，采用 material design 风格，看了这个你就无法忍受原生的丑陋动画了。现在 github 上有很多现成的 UI 实现，小编也是写 Android 的，写久了会发现其实很多的实现原理都是相似的，如果您对图形学等方面有兴趣，又想自己尝试下，不如在 dribbble 上找一个设计，自己动手去实现吧。
	
	<img src="https://camo.githubusercontent.com/96592555c77792a317564369f8ff53bafcba2a13/687474703a2f2f692e696d6775722e636f6d2f57776f784c4d752e676966" width=200 />	
7. hashicorp / **vault**  [https://github.com/hashicorp/vault](https://github.com/hashicorp/vault)

	是一个用 Go 实现的密钥管理工具,[官网](https://www.vaultproject.io/)    
	小编再来推荐一个用 Java 实现的密钥管理工具 [keywhiz](https://github.com/square/keywhiz)， [官网](http://square.github.io/keywhiz/)
	 
	
好了，本周项目介绍就到这里了。新的一周开始了，收拾收拾开始一周的美好生活吧，对小编来说，这又是忙碌的一周。GeniusVczh 说造一套轮子是学习编程语言的好办法, 很值得。祝福每一位伟大的工匠吧。