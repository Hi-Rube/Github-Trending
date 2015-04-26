##Github Trending repositories 第二期

啊哈一周这么快就过去了，小编Rube继续给你带来本周Github上的热门项目。   
本周 thefuck 继续成为最热门的项目，关注度极高。其他的就让小编我来一一介绍吧!    

1.	bendc/**sprint**   [https://github.com/bendc/sprint](https://github.com/bendc/sprint)			

	Sprint 是一种高性能的为现代浏览器服务的 DOM 库。尤其在移动端，Sprint 将发挥高效的作用，并且它的体积极小，在 gzip 压缩下只有 5KB。     
	Sprint 的使用应该很熟悉，因为它有和 jQuery 一样的链式 API。     
	   
	*code eg:*```$("div").addClass("new").append("<p>Hi Sprint</p>");```	
	####介绍	
	Sprint 是一个独立的库，它不是用来代替 jQuery 的，jQuery 能够做更多的事情能够处理更多的问题，支持更多的浏览器。Sprint 更专注于 DOM ,它提供了一层友好又不失性能的操作层。			
	####性能		
	在介绍中说到了性能，[详细性能对比图表](https://github.com/bendc/sprint) 
	主要对比了 Sprint 0.9.2，Zepto 1.1.6，jQuery 2.1.3 之间的性能差别，可以看到Sprint的性能还是比较有优势的。			
	举列一个 add 的性能对比如下
	![](https://camo.githubusercontent.com/a8f87e5a03c1e35e62d45c8400d008e8be9a8547/687474703a2f2f737072696e746a732e636f6d2f706572662d74657374732f6164642e706e67)	
2.	bevacqua/**dragula**	[https://github.com/bevacqua/dragula](https://github.com/bevacqua/dragula)				
				
	dragula 使在网页上拖放变得简单且令人激动,[戳这可以了解例子](http://bevacqua.github.io/dragula)。			
	dragula 目前支持所有的现代浏览器及IE7+。	
	####未来的开发方向
	+	使 dragula 更容易设置		
	+ 	没有臃肿的依赖
	+  能够智能地计算出自身的排序顺序			
  	+	操作时产生视觉反馈
  	+ 	提供触摸事件！				
  		
3. 	Dogfalo/**materialize**		[https://github.com/Dogfalo/materialize](https://github.com/Dogfalo/materialize)		
	Dogfalo 是一个基于 Material Design 风格的 CSS 框架，[官网地址]( 
http://materializecss.com)。   
	这个框架小编极力推荐哦，最近的项目中 (hybrid app) 也想有所尝试,在官网的教程指引下你会建立一个炫酷的视图,[样例传送门](http://materializecss.com/showcase.html)		
	![](http://materializecss.com/images/showcase/danielangel.png)			
	![](http://materializecss.com/images/showcase/tuanphongtruong.png)	
		
4. 	yhat/**rodeo**	[https://github.com/yhat/rodeo](https://github.com/yhat/rodeo)			

	Rodeo 是一个以处理数据为己任的 Python IDE，小编极力推荐。这也是一个以 web 为载体的 IDE，瞬间亲切感爆棚~，你可以把它想象成一个 IPython Kernel 的 web 版。在开发 IDE 时作者很大程度上受到 Eclipse 和 Sublime Text 的影响和激励。     
	**安装方法:**			
	
	```
 	$ pip install -U rodeo
 	$ rodeo .
	
  	_______      ___   ______   ________    ___
 	|_   __ \  .'   `.|_   _ `.|_   __  | .'   `.
  	 | |__) | /  .-.  \ | | `. \ | |_ \_|/  .-.  \
  	 |  __ /  | |   | | | |  | | |  _| _ | |   | |
  	_| |  \ \_\  `-'  /_| |_.' /_| |__/ |\  `-'  /
 	|____| |___|`.__.'|______.'|________| `.___.'

 	''''''''''''''''''''''''''''''''''''''''''''''''''
  	 URL: http://localhost:5000
  	 DIRECTORY: /Users/glamp/repos/yhat/big-data/kung-foo
 	''''''''''''''''''''''''''''''''''''''''''''''''''   
 	```		
 	
 	不多说果断上图				
 	**脚本执行**
 	![](https://github.com/yhat/rodeo/raw/master/rodeo/static/img/screenshot-files-with-output.png)					
 	**数据分析**
 	![](https://github.com/yhat/rodeo/raw/master/rodeo/static/img/screenshot-mpl-complex.png)		  
 
 
5.	syl20bnr/**spacemacs**				

	![](https://github.com/syl20bnr/spacemacs/raw/master/doc/img/spacemacs-python.png)				
	
	spacemacs 首先会让你想到 emacs 。但是，打住。小编认为它是一份接近完美的配置工程，不仅仅是一个编辑器。为什么又是编辑器呢，因为它已经将原生的 emacs 打造成了另一个磨样，并且结合了一些 vim 的特性。			
	
	但是对于 编辑器 vim emacs，IDE...的争论一直没停过，spacemacs 出现肯定会带来一些争论。 小编认为每个人都有自己的喜好，只要能够满足自己的需求并创造出价值的工具都是好工具。				


6.	 kabukky/**journey**		

	这是一个使用 golang 编写的博客系统，采用了 Ghost 主题。      
	journey 有几个优点：			
	
	+	高性能，采用 golang 编写对于性能来讲肯定不错。    
	+	容易上手使用，在任何设备和地方都可以更新自己的帖子打开 <code>yourblog.url/admin/</code>	就能进行操作。
	+ 	容易扩展，支持插件机制，能够编写插件实现更多自定义的功能。   
	+  安全方便，别的博客可能需要安装 Nginx 或者 Apache 然后启用 HTTPS。 但是journey 只需要轻松地将你的证书放上去配置一下就可以了。
	+  没有依赖，轻量且速度快，需要的内存极小，比如在 OSX 系统下只需要 3.5MB 的内存就可以顺利地工作。

	赶快去试一试吧[官网](https://kabukky.github.io/journey); 
	
7. 接下来发一些Rube推荐的资源吧。				

	adamwulf/**app-launch-guide**			
	这是一部独立开发 app 的权威指南，里面包含了你开发一个 app 的所需，包括规划，编码，发布，推广，营销等等等等。			
	
	akullpp/**awesome-java**		
	java 资料和资源合集		
	
	
**好了，这周的内容就到这里了。在编写此文时，得到消息尼泊尔 8.1 级已经导致了数千人遇难，小编在这里默默哀悼，愿逝者安息，亲爱的地球请平息你浮躁的心情。**


	
 	
 
 
 	
 	
 	
 	
 			