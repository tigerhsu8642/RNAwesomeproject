# RNAwesomeproject
React Native跨平台项目

1、根据官网操作 https://reactnative.cn/docs/environment-setup

执行程序命令
cd AwesomeProject
yarn android
或者
yarn react-native run-android

2、如果出现PowerShell yarn : 无法加载文件 C:\Users\Admin\AppData\Roaming\npm\yarn.ps1,因为在此系统上禁止运行脚本错误

搜索powershell，右键以管理员身份运行
打入  ：set-ExecutionPolicy RemoteSigned
查看执行策略：get-ExecutionPolicy
可获得 yarn 脚本执行权限
