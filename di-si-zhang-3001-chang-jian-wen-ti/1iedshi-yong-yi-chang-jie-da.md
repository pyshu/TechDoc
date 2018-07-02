1、IDE报错：\[EXCEPTION\]:java.net.ConnectException: Connection refused: connect ...是什么原因。

此问题主要有两个原因：一种是GW的Web页面没有开启IDE调试；另一种是由于Session过期所致，点击IDE中Remote Host内Refersh重连。

2、编译代码的过程中，出现IDE一直停在Upload Project的界面未退出。

此问题需先确认编译时是否选中为整个Python App工程，如已经选中需点击Run in Background 退出编译。如多次编译情况一样那就请检查代码。





