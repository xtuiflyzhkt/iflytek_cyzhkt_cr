# 科大讯飞-畅言智慧课堂-分析
（预计于2021-05-13 20:00前更新内容）<br>
点view code查看内容<br>
网站:http://119.188.248.210:23456/cyzhkt<br>
* 360加固是一个类似VMP的东西，我们正尝试使用xposed脱壳<br>
测试型号:华为<暂不公开><br>
预安装6个应用程序包:<br>
应用商店(com.iflytek.mdmstore)<br>
讯飞输入法(com.iflytek.inputmethod)<br>
StudentLauncher(com.android.launcher3)<br>
畅言学生登录(com.iflytek.iflylogin)<br>
本机管理(com.iflytek.mdmadmin)<br>
管控平台(com.iflytek.mdmservice)<br>
*某些机型预安装:管控设置(com.iflytek.mdmsetting)<br>
注意:应用商店和管控平台会检查apk的名称，包名，签名，文件大小，改包名或者使用中间人安装应用程序的方式是不可行的(特殊情况除外)<br>
建议:包名可以改成本机管理然后拖到hw_init/....../app/mdmadmin里面改名mdmadmin.apk，因为目前本机管理可以被替换
