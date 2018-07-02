IED开发应用时建议每一个Python App工程都使用单独的工作目录。打开IDE并选择工作目录。

![](/assets/iedworkspaceselection.png)

新建工程，File -&gt; New -&gt; New Project。

![](/assets/newproject1.png)Project name为工程名称（自定义）， Host为设备IP地址，Password为设备序列号。

![](/assets/newproject2.png)

![](/assets/newproject3.png)

![](/assets/configpythonenv.png)

连接成功。

![](/assets/connectscheck.png)

接下来就可以开始编写我们的App，这里就不在描述代码的编写过程（由于IED编辑代码偶尔会触发未知BUG,建议使用第三方代码编辑工具）。下面就使用第三方工具开发的App源码导入工程目录编译打包为例。

将下载的工程文件PyappSample文件中src目录下的文件拷贝并替换新建工程文件目录src下的文件。

![](/assets/newappcode.png)

刷新缓存

![](/assets/refresh.png)

编译工程文件，需要选中需要编译的工程，然后再点击Compile Pyc。

![](/assets/compile.png)

最终通过打包方式生成InRouter9XX平台的可执行压缩包Python应用文件，即&lt;工程名&gt;.tar为生成后的应用文件。

![](/assets/packaging.png)

