#����.babelrc
	{
		"presets":[
		 "es2015"//ת�����
		],
		"plugins":[]
	}
	
#��װbabel	
	npm i --save-dev babel-preset-es2015 //��װes2015
	
	npm i --global babel-cli//������ת��
	
	npm i --save-dev babel-cli  //��װ����Ŀ��

#�趨����	
	'package.json':
		"scripts": {
			"build": "babel src -d lib"   //����ָ������   npm run build
		},
	
#ת���ļ�	
	babel a.js   //a.js�еĴ���ת�����������̨
	
	babel a.js -o b.js  //a.js ת�������b.js
	
	babel src -d dist  //dist����Ŀ¼�е��ļ�ת��
	