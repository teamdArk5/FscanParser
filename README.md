# FscanParser
 一个用于处理fsacn输出结果的小工具（尤其面对大量资产的fscan扫描结果做输出优化，让你打点快人五步！！！）

## 版本支持
目前只支持最新版本fscan(**1.8.4**)的扫描结果：`fscan.exe -h 192.168.5.1/24 -o outputlocal.txt`

## 工具界面

### 日志输出

处理过后的结果内容

![](images/Log.png)

### NetInfo

显示基于网卡数量信息，如为多网卡的机器我们就优先渗透。

![NetInfo](images/NetInfo.png)

### Windows

显示Windows的机器信息

![Windows](images/Windows.png)

### Web

显示的是Web相关信息

![Web](images/Web.png)



### BugList

显示存在漏洞的信息

![BugList](images/BugList.png)

### WeakPass

显示弱口令信息，支持连接、执行命令、自动截图留存整证明、自动连接并截图导出到docx等

![WeakPass](images/WeakPass.png)

​	直接连接弱口令，无需再打开其他的连接工具。

![Connect](images/Connection.png)

​	导出弱口令连接证明图到doc

![export docx](images/exportDocx.png)

## 更新
* 2024年8月24日 v1.2
  * 新增文本框拖拽获取路径功能。
  * 新增Linux选项卡的右键菜单。
  * 新增Web选项卡的awvs导出，支持直接导出到awvs扫描的csv
* 2024年8月23日 v1.1
  * 增加数据库右键菜单
  * 增加网卡（多）信息显示
  * 增加网段无信息端口选项卡显示