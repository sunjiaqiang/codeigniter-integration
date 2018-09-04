# CodeIgniter-integration

基于CI框架3.1.9的hmvc模式整合的一些插件和常用功能，如果对hmvc不是很了解的同学，可以先百度一下，
如果你有php基础和框架使用经验(yii,thinkphp等)，一般来说这些功能都能整合进这些框架中。

# 简介

使用CI框架在开发项目的过程中，整理了一下项目中常用的功能和SDK整合，这些功能全部通过测试，放心使用，
此项目不是一套完整的项目，这是整合了各种功能，方便在开发新项目的时候拿来使用。

# 相关整合功能

将本项目clone下来，并配置好域名
假设你的域名为xxx.com

	1.plupload多图上传 访问地址http://xxx.com/plupload/index/index

	2.webupload多图上传 访问地址http://xxx.com/webupload/index/index
	
	3.PHPQRCode生成二维码 访问地址http://xxx.com/qrcode/index/index
	
	4.tcpdf生成pdf 访问地址http://xxx.com/pdf/index/index
	
	5.整合PHPmailer 访问地址http://xxx.com/email/index/index(需要配置你自己的163邮箱和邮箱独立密码，并配置好邮箱相关配置)
	
	6.wangeditor编辑器整合 访问地址http://xxx.come/editor/index/index
	
	7.ajax无刷新分页 访问地址http://xxx.com/ajaxpage/index/index
	
	8.ajax滚动加载数据 访问地址http://xxx.com/scroll/index
	
	9.php日历签到 访问地址http://xxx.com/calendar/index/calendar_one
	
	10.php普通日历 访问地址http://xxx.com/calendar/index/calendar_two
	
	11.内容数据静态化 访问地址http://xxx.com/createstatic/index/index(批量数据生成)
	
	12.jquery电子签名 访问地址http://xxx.com/signature/index/index
	
	13.highcharts柱状图数据显示 访问地址http://xxx.com/analysis/index/index
	
# 使用说明
本着开源以及使广大猿们少走弯路和少造轮子的精神，开源这些源码，你可以使用到你的任何项目当中去，但是不得将此源码中的任何功能进行售卖，
一经发现本人保留追究其责任的权利。