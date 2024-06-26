第一步：环度通过我们提供的运营商平台向SHECA IP SSL申请证书

第二步：SHECA向通过运营商管理平台的界面获取文件验证路径和验证值，如下图展示
 ![image](https://github.com/SHECA-Alvin/cabgroup/assets/163508594/3e39ccce-dd0d-46ff-a821-92d99d245739) 

第三步：SHECA默认会去扫描该IP下的443和80端口下的路径去验证是否配置可验证通过的值，仅记录验证通过的值 

相关系统的域名验证扫描日志如下
![image](https://github.com/SHECA-Alvin/cabgroup/assets/163508594/c379289e-90ab-4211-b902-5a9f4e9d431b)


从日志可以看到SHECA通过该IP的443端口扫描了值，由于该讨论中不涉及组织审核，因为我只讲述了域名的审核流程
