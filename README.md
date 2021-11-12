# egretPublishRPK
白鹭h5项目发布到各种快游戏的一些记录

1.有4m分包大小的限制

# oppogame
1.打包指令 quickgame subpack release (node v8.9.2) \n
2.nodejs打包，打包过程可能会存在内存不足问题 需要设置下 setx NODE_OPTIONS --max_old_space_size=4096 \n
3.更新版本-可能需要更换下分包名 \n
4.测试包存放手机的目录：Android\data\com.nearme.instant.platform\files\subPkg
5.用AS调试看 jsw log


# fastgame
1.adb查看log                adb logcat -s jsLog
2.使用华为快应用助手将包安装到华为手机

# qgame 小米快游戏
1.打包指令 npm run release
2.调试
1）npm run server 扫码
2）⼿机 USB 连接到 PC 
3）浏览器 chrome://inspect/ （需要梯子）

# vivogame
1.qg.showDialog 接口和其他快游戏不一样
2.没有文件管理器对象
