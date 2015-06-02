#sqlserver2005 sql server database services安装失败解决方法

在安装sql2005时，先安装“native client向导”（sqlncli.msi），再装SQL2005！

    如果你不幸没有那么做的话，也没关系。
    安装完后不是提示sql server database services安装失败吗，那好不管他，照样结束安装.
    1、手动卸载native client并且重新安装native client，目录：\SQL2005\sql2005-cd1\Setupsqlncli.msi
    2、在安装文件夹的“server”-》“setup”文件夹里找到sqlRUN_SQL.msi文件，
    这个就是sql server database services的安装文件了，执行他来单个安装服务。这样做也是没问题的。
    之后在安装客户端工具和示例就行了。

客户端工具下载连接 :http://www.microsoft.com/zh-cn/download/confirmation.aspx?id=8961 
