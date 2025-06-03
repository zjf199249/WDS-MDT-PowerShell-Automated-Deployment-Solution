使用PowerShell脚本进行自动化部署

存放软件目录：
D:\Applications

存放驱动目录：
系统驱动D:\Drivers\win11
PE驱动D:\Drivers\PE

存放WDS配置目录：
D:\WDS

存放MDT配置目录：
D:\MDT



包括以下脚本

部署WDS脚本
部署MDT脚本

创建任务序列：


导入系统镜像
导入软件方案

导入驱动方案：
获取设备型号命令：(Get-WmiObject -Class Win32_ComputerSystem).Model

提取软件GUID，写入到Rules
更新MDT
WDS添加启动映像
