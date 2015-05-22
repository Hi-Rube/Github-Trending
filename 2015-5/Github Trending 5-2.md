隔了两个星期后，Rube继续为您带来Github上热门项目的介绍。

*	typicode/**json-server** [https://github.com/typicode/json-server](https://github.com/typicode/json-server)		  

	json-server 能够为开发者快速构建一个基于 REST API 的服务器，这对开发调试等十分方便。		     
	
	如何利用 json-server 呢。首先开发者需要构建一个 db.json。
	
	```       
	{
  	"posts": [
    { "id": 1, "title": "json-server", "author": 	"typicode" }
 	 ],
 	"comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  	]
	}
	```      
	
	然后呢，然后干什么，只需运行命令 json-server --watch db.json 就可以了。这样你就可以对 posts,comments 进行 REST 形式的增删改查了。是不是狠方便咯。     
				
*	square/**leakcanary** [https://github.com/square/leakcanary](https://github.com/square/leakcanary)		
	leakcanary 是一个 Java 的内存泄露检测工具，当然可以用到 Android 上咯。 leakcanary 可以大幅度减少开发中遇到的 OOM 的问题, 同时他能将内存泄露点以一种漂亮的方式展现出来  
	 
	<img src="https://github.com/square/leakcanary/blob/master/assets/screenshot.png" width=500/>     
	以下有两篇文章,都是相应的外文翻译		
	第一篇为 leakcanary 的 github 上 README 的[翻译](http://www.jianshu.com/p/7db231163168)      
	第二篇为 关于 leakcanary 的一次[尝试和分析](http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2015/0509/2854.html)				
	
*	schachmat/**wego** [https://github.com/schachmat/wego](https://github.com/schachmat/wego)     

	wego 是一个用 go 编写的终端天气客户端。对，命令行还能这么丰富多彩你想不到吧。    
	wego 的功能丰富能够   
	1. 显示5天的天气状况			
	2. 能够显示天气图标，那可是纯 print 出来的哦。   
	3. 显示的信息丰富，有温度，风速风向，降水量，降水概率等

	<img src="https://camo.githubusercontent.com/c3d2b92671f1ded5d5a9a9ebafdc836527f97269/687474703a2f2f7363686163686d61742e6769746875622e696f2f7765676f2f7765676f2e676966" width=500/>				
			
*	segmentio/**deku** [https://github.com/dekujs/deku](https://github.com/dekujs/deku)		

	deku 是一个轻量级的 React 替代品， deku 之所以轻量因为它的大小大约只有 10kb。deku 借鉴于 React 但并不依赖 class-like syntax 的前端库。效率很高，很新潮（不支持旧的 browser，用了 ES6 的语法），每一个 component 可通过 beforeRender, render, afterRender, beforeMount, afterMount 等来定义一个 lifecycle。			
	      
	关于 deku 的用法可以参考这篇[文章](https://segment.com/blog/deku-our-functional-alternative-to-react/)
	<img src="https://camo.githubusercontent.com/743d6f80dc7e7f7e624857479454c891b18a6b3c/687474703a2f2f662e636c2e6c792f6974656d732f31733054325a3346327a3139304d3178317831592f64656b752d6c6f676f2e706e67" width=100/>
	
*	okor/**justice** [https://github.com/okor/justice](https://github.com/okor/justice)	

	justice 是一个 web 性能显示工具，justice 将会创建一个页面上的工具栏用来显示网页进行一些操作的时间性能，fps等。这为开发者为网页性能调优等提供了方便。justice 还能够自定义显示性能指标的样式。使用方法狠简单。      
	git clone 项目后将 justice 的项目文件用 script 标签引进来就可以了			
	```
	<script type="text/javascript" src="../build/justice.mapped.min.js"></script>
	```					
				
	然后执行Justice.init();					
	
	```
<script type="text/javascript">
  Justice.init();
</script>	
 
	```			
	
	<img src="https://camo.githubusercontent.com/16475306f69fe8ba9a00d90ba864746b9cd61203/687474703a2f2f692e696d6775722e636f6d2f7a4b616a3666442e706e67" width=500/>   
	
	
*	sindresorhus/**awesome** [https://github.com/sindresorhus/awesome](https://github.com/sindresorhus/awesome)     

	sindresorhus 大神整理的一个优秀资源的列表，里面包含的东西好多狠丰富，从语言层面到理论，从理论到实践。。。

	
