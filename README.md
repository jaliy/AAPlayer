# noteapp

##AAPlayer(基于html5的视频播放器)

 基于html5的video标签，二次开发更加美观的视频播放器组件AAPlayer

###Demo

* 手机访问[Demo](http://jaliy.github.io/AAPlayer/)

###项目地址：

```shell
git clone https://github.com/jaliy/AAPlayer.git
```

##使用方法:
var aaplayer = new AAPlayer(options);
##参数选项
 * options.el        			{{DOM}}      		: 父容器
 * options.src         			{{String}}      	: 视频地址
 * options.width      			{{Number || String}}: 视频宽度
 * options.height        		{{Number || String}}: 视频高度
 * options.hideCtrl   			{{Boolean}}      	: 是否显示控制区域
 * options.hideTime           	{{Number}}    		: hideCtrl为true时，鼠标移开视频后隐藏时间间隔
 * options.autoplay           	{{Boolean}}    		: 是否自动播放,默认false

##API

 * 播放：aaplayer.play();

 * 暂停：aaplayer.pause();
