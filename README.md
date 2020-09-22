# artphp
artphp


#安装tp
```
composer create-project topthink/think artphp
```

#进入artphp目录

#添加应用模式
```
composer require topthink/think-multi-app
```

#快速生成应用

```
php think build index
```

#引入模板引擎驱动
```$xslt
composer require topthink/think-view
```
#插件
```$txt
composer require zzstudio/think-addons
//安装时会生成配置文件，如果没有生产可以使用如下命名进行生成。
php think addons:config 
```