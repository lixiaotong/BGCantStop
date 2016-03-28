# BGCantStop

## php项目架构
###架构的关键 在于消减耦合, 方便将来的维护和拓展
###在此架构如下：

1. + application
	1. + library //本地类库
	2. + plugins //其他插件
	3. + models //数据模块
	4. + controllers //控制模块
		1. - Index.php //默认控制器
	5. + views    
		1. + index   
			1. - index.phtml //默认视图
2. + public
	1. - index.php //入口文件 
	2. + css
	3. + img
	4. + js
3. + conf
	1. - application.ini //配置文件   
  
