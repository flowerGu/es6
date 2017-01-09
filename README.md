#配置.babelrc
	{
		"presets":[
		 "es2015"//转码规则
		],
		"plugins":[]
	}
	npm i --save-dev babel-preset-es2015 //安装es2015
	
	npm i --global babel-cli//命令行转码
	
	npm i --save-dev babel-cli  //安装在项目中
	
	'package.json':
		"scripts": {
			"build": "babel src -d lib"   //设置指定命令   npm run build
		},
	
	babel a.js   //a.js中的代码转码输出到控制台
	
	babel a.js -o b.js  //a.js 转码输出到b.js
	
	babel src -d dist  //dist整个目录中的文件转码
	