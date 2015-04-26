#Github Trending repositories 第一期

####小编Rube每周为大家介绍部分github上最新的流行的项目

1. ResearchKit/**ResearchKit** [https://github.com/ResearchKit/ResearchKit](https://github.com/ResearchKit/ResearchKit)     
 
	ResearchKit™框架是一个开源的软件框架，使开发者能够很容易地创建用于医疗研究或其他研究项目的应用程序。目的使我们的移动设备成为一个医疗传感器，将诸多设备一起构建一个用于医疗研究的传感器网络。在Github上包含了一个苹果开发的示例app和4个其他医疗机构在AppStore上发布的app。[示例app介绍及框架原理概况](http://www.infoq.com/cn/news/2015/04/apple-researchkit-github)         
	
	**环境要求**:需要Xcode6.3或更高版本,在iOS8.0或更高版本的设备上运行
	
2. facebook/**react-native** [https://github.com/facebook/react-native](https://github.com/facebook/react-native)

	React Native可以使开发者使用Javascript和React来开发移动端本地应用,能够更容易地构建跨平台应用。链接一些资料:    
	
	-  [关于React Native的讨论](http://www.zhihu.com/question/27852694)
	-  [项目中的英文文档翻译](https://github.com/reactjs-cn/react-native)   
	-  目前发布的是iOS版本,Android版本预计在2015年10月份发布。[关于React Native适配安卓的讨论](http://www.zhihu.com/question/29658748)
	-  [React Native通信机制的介绍](http://blog.cnbang.net/tech/2698/?from=groupmessage&isappinstalled=1)
	-  [天猫在实践中的总结](https://github.com/tmallfe/tmallfe.github.io/issues)

	React Native 3月末开源以来国内社区对此的讨论十分热烈,开发热情很高,小编因此也有所尝试,[项目地址](https://github.com/Hi-Rube/baoz-ReactNative)。
	
3.	Yalantis/**GuillotineMenu** [https://github.com/Yalantis/GuillotineMenu](https://github.com/Yalantis/GuillotineMenu)    

	一个使用Swift实现的断头台过渡动画。    
	![menu](https://camo.githubusercontent.com/10639e803a90fadd751d3683c497c449e2a48339/68747470733a2f2f6431337961637572716a676172612e636c6f756466726f6e742e6e65742f75736572732f3439353739322f73637265656e73686f74732f323031383234392f64726166745f30362e676966)     
	
	**环境要求**:iOS 8.0   
	##安装 
	####CocoaPods    
	即将推出。

	####手动安装

	-  将“GuillotineMenu”文件夹添加到您的项目。
	-  在界面生成器创建一个视图控制器，并设置它的类是GuillotineMenuViewController或它的子类。
	-  将您的视图控制器连接GuillotineMenuViewController通过GuillotineMenuSegue
	-  如果是GuillotineMenuSegue,那么在prepareForSegue方法中调用destination.setMenuButtonWithImage（<＃UIImage>)

	```
	@objc protocol GuillotineAnimationProtocol: NSObjectProtocol {
   		func navigationBarHeight() -> CGFloat
   		func anchorPoint() -> CGPoint
   		func hostTitle () -> NSString
	}}
	```

	-  您需要为GuillotineMenuViewController设置的属性如下代码所示：
	
	```
	override func prepareForSegue(segue: UIStoryboardSegue, sender: AnyObject?) {
   		let destinationVC = segue.destinationViewController as! GuillotineMenuViewController
  		 destinationVC.hostNavigationBarHeight = self.navigationController!.navigationBar.frame.size.height
  		 destinationVC.hostTitleText = self.navigationItem.title
 		 destinationVC.view.backgroundColor = self.navigationController!.navigationBar.barTintColor
  		 destinationVC.setMenuButtonWithImage(barButton.imageView!.image!)
}
	```
	
	-  只要通过点击菜单按钮,图像旋转就会出现。

	**版本:1.0**  	 
	**证书:MIT**
	
	
4.	hackers-painters/**samurai-native** [https://github.com/hackers-painters/samurai-native](https://github.com/hackers-painters/samurai-native)

	samurai-native 可以让您使用标准Web开发技术 (HTML+CSS) 构建基于私有浏览器内核的原生应用。现已支持 iOS，后续[GeekZoo](http://baike.baidu.com/link?url=1s2VuhKynFs5yYmaEDpbtg7NAU1vFsmmVoHFf005nDllkBV32PtwedqfN5NE4flZ8esi9PeMxsmOGIW8G_V9CK)团队会继续支持Android。     
	samurai-native是[BeeFramework](https://github.com/gavinkwoe/BeeFramework)的精华，BeeFramework作者[Gavin.Kwoe](https://github.com/gavinkwoe)的前端功力深厚，小编在此敬仰!但是以上提到的两个框架的学习曲线都较为陡峭。   
	
	[中文介绍地址](https://github.com/hackers-painters/samurai-native/blob/master/README_CN.md)
	
	
5. torvalds/**linux**[https://github.com/torvalds/linux](https://github.com/torvalds/linux)     

	Linux在这周获得了许多新的关注,因为Linux4.0正式发布。     
	主要的更新内容为:   
	+  新增“实时内核补丁”。无需重启，实时修补内核
	+  改进对部分硬件的支持,存储系统,图形图像和音频的支持
	+  集成了更多的ARM
	+  ...
	
6. box/**t3js** [https://github.com/box/t3js](https://github.com/box/t3js)    

	T3是建设大规模的Web应用程序客户端的JavaScript框架。它的设计是基于可扩展的JavaScript应用架构，具体的原则：
	-  执行部件之间松耦合
	-  使依赖明确
 	-  提供了扩展点，以允许不可预见的要求
	-  抽象出共同点
	-  促进项目渐进增强

		<img src="http://t3js.org/img/design-diagram@2x.png" style="width:50%"/>
		
	####Design
	T3是大多数JavaScript框架不同。它的意思是小块的整体架构，它允许你建立可扩展的客户端代码。    
	T3允许你决定自己想要创建的组件类型，可创建的组件类型分为三类：   
	
	+  服务（Services）：为应用提供额外工具的库，例如cookie utility、URL encoder/decoder、popup menus
	+  模块（Modules）：模块可以使用服务来完成任务，但模块不能直接引用其他模块
	+  行为（Behaviors）：混合模块，旨在允许连接由多个模块共享的事件。例如，拦截链接点击来执行Ajax导航。行为可以使用服务来完成任务，但是不能直接引用模块或其他行为

	如上图所示蓝色块代表模块,黄色块代表服务,绿色块代表行为。三者通过一个类似总线的东西在Application中保持一定的联系。      
	
	**环境要求及浏览器支持**:     
	依赖jQuery v1.8.0及以上版本    
	Internet Explorer 8及以上	     
	Firefox (最新版本)        
   Chrome (最新版本)      
   Safari (最新版本)
   
   [详细了解见官网](http://t3js.org/)
   
7. JadenGeller/**Helium** [https://github.com/JadenGeller/Helium](https://github.com/JadenGeller/Helium)	     

	Helium是一个在OS X下的浮动的浏览窗口，让您观看的视频，浏览的网页以及正在做的事情一直保持活动可见的状态。你的窗口内容将永远在其他窗口之上，即使你切换了任务。Helium支持自定义的半透明模式，让你同时看到你的内容和你的工作，当它半透明的时候,鼠标是无法点击它的。你可以点击,拖曳和滚动它之后的内容。     
	
	小编看来这是一个灰常有趣的项目哩~，给作为程序员的小编带来了福音，只有一个屏幕伤不起啊...回过头想想它的名字Helium是不是想到了什么~       
	![](http://heliumfloats.com/screenshot.png)      
	[在官网可以下载这个应用](http://heliumfloats.com/)
	
8. knadh/**niltalk** [https://github.com/knadh/niltalk](https://github.com/knadh/niltalk)    

	Niltalk是一个用Go语言编写的简单的，私人的，免费的基于Web的多房间聊天室，使用WebSockets进行服务器与客户端的通信。 			
	#####安装
	```
	go get github.com/goniltalk/niltalk
	```
	您可以将GOPATH切换到niltalk目录下,运行```go get ./...```来下载软件包的依赖关系。

	#####用法
	+ 运行Redis		
	+ 配置config.json中的必要的值
	+ 在您的GOPATH目录niltalk下执行./run（您可能需要执行chmod 755./run设置权限为755）			
	
	[快进来试试](https://niltalk.com/)
	![](http://cdn.ilovefreesoftware.com/wp-content/uploads/2015/04/Niltalk-Chats.jpg)
	
9. cjwirth/**awesome-ios-ui** [https://github.com/cjwirth/awesome-ios-ui](https://github.com/cjwirth/awesome-ios-ui)   
	wasabeef/**awesome-android-ui** [https://github.com/wasabeef/awesome-android-ui](https://github.com/wasabeef/awesome-android-ui)     
	资源介绍时间,这两个项目分别是iOS和Android的UI/UX库,里面的动画棒棒哒~    
	
	timjacobi/**angular2-education** [https://github.com/timjacobi/angular2-education](https://github.com/timjacobi/angular2-education)   
	angular2的帮助教程也出来了。     
	getify/**You-Dont-Know-JS** [https://github.com/getify/You-Dont-Know-JS](https://github.com/getify/You-Dont-Know-JS)   
	Javascript系列知识一直很火


10. nvbn/**thefuck** [https://github.com/nvbn/thefuck](https://github.com/nvbn/thefuck)				

	第十个来介绍下个压箱底的，已经火很多天了，可能早已被人熟知。     
	**thefuck**给广大运维人员带来了福音，能够纠正上一次的控制台命令，只需要fuck一下就能纠正。详细的话，试一下你就知道多好玩了。
	
	
这是小编第一次做这个工作，如有不足请多多提意见哦~
	
	