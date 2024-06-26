第一步：环度通过SEHCA提供的运营商平台向SHECA申请 支持IP的SSL申请。

第二步：环度通过运营商平台的界面获取文件验证路径和验证值，如下图展示
![image](https://github.com/SHECA-Alvin/cabgroup/assets/163508594/c637902a-9d49-49d3-b2b3-39b6d7d17a7e#pic_left)

第三步：SHECA默认会去扫描该IP下的443和80端口下的路径去验证是否配置了预期值。

系统的域名验证扫描日志如下:
![image](https://github.com/SHECA-Alvin/cabgroup/assets/163508594/c379289e-90ab-4211-b902-5a9f4e9d431b#pic_left)


从日志可以看到SHECA通过该IP的443端口扫描了预期值，并将域名验证判定为通过，由于该讨论中不涉及企业信息验证，因为不做过多的描述。
