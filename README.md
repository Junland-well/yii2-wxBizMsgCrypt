# yii2-wxBizMsgCrypt
yii2框架下的微信第三方平台授权加解密

相对于官方下载的文件，作了如下修改 <br/>
1.把php7弃用的mcrypt加密改成OpenSSL。 <br/>
2.构造函数 __construct()代替class同名方法。 <br/>
3.把几个文件整合在同一个文件，直接use即可。 <br/>
